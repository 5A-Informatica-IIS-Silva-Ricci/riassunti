# Simulazione esame

---

# Ipotesi

> 
> 

# Diagramma ER

![Screenshot 2022-06-22 at 22.44.06.png](../../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Simulazione%20esame%20fa91afca8c0c450a81c1d6442ed0c628/Screenshot_2022-06-22_at_22.44.06.png)

## Ristrutturazione IS-A

- **Superclasse**
    
    ![Screenshot 2022-06-22 at 22.45.26.png](../../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Simulazione%20esame%20fa91afca8c0c450a81c1d6442ed0c628/Screenshot_2022-06-22_at_22.45.26.png)
    
- Sottoclasse
    
    ![Screenshot 2022-06-22 at 22.47.22.png](../../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Simulazione%20esame%20fa91afca8c0c450a81c1d6442ed0c628/Screenshot_2022-06-22_at_22.47.22.png)
    
- Entità debole
    
    ![Screenshot 2022-06-22 at 22.51.22.png](../../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Simulazione%20esame%20fa91afca8c0c450a81c1d6442ed0c628/Screenshot_2022-06-22_at_22.51.22.png)
    

### Diagramma completo

![Screenshot 2022-06-22 at 23.01.46.png](../../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Simulazione%20esame%20fa91afca8c0c450a81c1d6442ed0c628/Screenshot_2022-06-22_at_23.01.46.png)

---

# Documentazione

> 
> 

---

# Modello Logico

```ruby
Utente(id, username, psw)
con v.i.r. di id con Cliente(id)

Cliente(id, nome, cognome, data_nascita, email)

AddettoHD(id, nome, cognome)

Tecnico(id, nome, cognome, data_nascita, email)

Ticket(id, stato, locazione, cliente, addettoHD, tecnico)
con v.i.r. di cliente con Cliente(id)
con v.i.r. di addettoHD con AddettoHD(id)
con v.i.r. di tecnico con Tecnico(id)

Report(id, data, tempo, riassunto, commento, convalidato, ticket)
con v.i.r. di ticket con Ticket(id)
```

---

# Modello fisico

```sql
CREATE TABLE cliente (
  id INT PRIMARY KEY auto_increment, 
  nome VARCHAR(50) NOT NULL, 
  cognome VARCHAR(50) NOT NULL, 
  data_nascita DATE NOT NULL, 
  email VARCHAR(30) NOT NULL
);

CREATE TABLE utente (
  id INT PRIMARY KEY REFERENCES cliente(id) ON UPDATE CASCADE ON DELETE no action, 
  username VARCHAR(20) NOT NULL, 
  psw CHAR(255) NOT NULL
);

CREATE TABLE ticket (
  id INT PRIMARY KEY auto_increment, 
  stato INT NOT NULL DEFAULT 0, 
  locazione INT NOT NULL DEFAULT 0, 
  cliente INT REFERENCES cliente(id) ON UPDATE CASCADE ON DELETE no action, 
  addettohd INT REFERENCES addettohd(id) ON UPDATE CASCADE ON DELETE no action, 
  tecnico INT REFERENCES tecnico(id) ON UPDATE CASCADE ON DELETE no action
);
```

---

# Query

- elenco dei ticket attualmente aperti riportando il nome del cliente che li ha aperti, la data di apertura, il tecnico che li sta seguendo;

```sql
SELECT tik.id id_ticket, c.nome AS nome_cliente, tec.nome nome_tecnico
FROM Ticket tik, Cliente c, Tecnico tec
WHERE tik.cliente = c.id AND tik.tecnico = tec.id
```

- tempo medio di chiusura dei ticket completati in un certo intervallo temporale fornito in ingresso.

```sql
// Utile per ottimizzare i tempi di ricerca
CREATE INDEX data_completamento_ticket ON Ticket(data_completamento);

SELECT AVG(data_inizio - data_completamento) 
FROM Ticket
WHERE data_completamento BETWEEN data1 AND data2;;
```

---

# PHP

Richiesta ticket 

```php
<?php
session_start();
spl_autoload_register(function ($class_name) { include $class_name . '.php';
});
```

```php
<?php

class ConnessioneDb {
    CONST DB_HOST = "localhost";
    CONST DB_NAME = "dipendenti";
    CONST DB_USER = "";
    CONST DB_PASSWORD = "";

    private static $dbManager = null;

    private $connection;

    private function __construct() {
        $this->connection = new mysqli( self::DB_HOST, self::DB_USER, self::DB_PASSWORD, self::DB_NAME);
        if ($this->connection->connect_error)
            die("Si è verificato un errore: ". $this->connection->connect_error);
    }

    public static function getInstance() {
        if (self::$dbManager == null)
            self::$dbManager = new ConnessioneDb();
        return self::$dbManager;
    }

    public function creaTicket($cliente) {
        $query = "INSERT INTO Ticket (cliente) VALUES (?)";
        $prepared = $this->connection->prepare($query);
        $prepared->bind_param("s", $cliente);
        $prepared->execute();
        $result = $prepared->get_result();
        if ($result == false) return false;
        else
            return true;
    }

    public function tabella_ticket($cliente) {
        $query = "SELECT * FROM Ticket WHERE cliente=?";
        $prepared = $this->connection->prepare($query);
        $prepared->bind_param("s", $cliente);
        $prepared->execute();
        $result = $prepared->get_result();

        $rows = $result->num_rows;

        $tabella = "<table>";
        if ($rows > 0) {
            while ($row = $result->fetch_assoc())
                $tabella = $tabella."<tr><td>".$row["nome_ticket"]."<tr><td>";
        } else {
            $tabella = "<h1>Nessun ticket presente</h1>";
        }

        return $tabella;
    }
 }
```

```php
<?php
include "autoloader.php";
$connessione = ConnessioneDb::getInstance();
?>

<html>
<head>
    <title>Lista ticket</title>
</head>
<body>
    <h1>Visualizza ticket aperti</h1>
    <?= $connessione->tabella_ticket($_SESSION["cliente"]) ?>
</body>
</html>
```

```php
<html lang="it">
<head>
    <title>Richiesta ticket</title>
</head>
<body>
<form method="get" action="richiesta_ticket.php">
    <input type="submit" id="richiesta" name="richiesta" value="Richiedi ticket">
</form>
</body>
</html>
```

```php
<?php
include "autoloader.php";

if (isset($_GET["richiesta"])) {
    $connessione = ConnessioneDb::getInstance();
    $connessione->creaTicket($_GET["cliente"]);

    header("location:ticket_creato.html");
} else
    header("location:richiesta_ticket.html");
```