# Squadra basket

### Modello E-R

![Untitled](Squadra%20basket%20fc9fc6289f4f4b35b7068ee70a99945c/Untitled.png)

### Modello logico

```jsx
Campionato(nome, anno)
Squadra(nome, nomeCampionato, anno)
	con v.i.r. di nomeCampionato con nome di Campionato
	con v.i.r. di anno con anno di Campionato
Giocatore(id, nome, cognome, data_nascita, luogo_nascita)
Ruolo(nome, descrizione)
appartenenza(nome, nomeCampionato, anno, id, presenze, numero, canestri)
	con v.i.r. di nome con nome di Squadra
	con v.i.r. di nomeCampionato di nomeCampionato di Squadra
	con v.i.r. di anno con anno di Squadra
	con v.i.r. di id con id di Giocatore
ruoli(nome, id, da, a)
	con v.i.r. di nome con nome di Ruolo
	con v.i.r. di id con id di Giocatore
```

### Modello fisico

```sql
CREATE DATABASE IF NOT EXISTS basket;

CREATE TABLE IF NOT EXISTS Giocatore(
    id INT AUTO_INCREMENT PRIMARY KEY,
    cognome VARCHAR(30) NOT NULL,
    data_nascita DATE NOT NULL,
    luogo_nascita VARCHAR(50) NOT NULL
);

CREATE TABLE IF NOT EXISTS Ruolo(
	nome VARCHAR(20) PRIMARY KEY,
	descrizione VARCHAR(200) NOT NULL
);

CREATE TABLE IF NOT EXISTS Campionato(
	nome VARCHAR(20),
	anno INT(1),
	PRIMARY KEY (nome, anno)
);

CREATE TABLE IF NOT EXISTS Squadra(
	nome VARCHAR(20),
	nomeCampionato VARCHAR(20) REFERENCES Campionato(nome),
	anno INT(1) REFERENCES Campionato(anno),
	PRIMARY KEY (nomeCampionato, anno)
);

CREATE TABLE IF NOT EXISTS appartenenza(
	nome VARCHAR(20) REFERENCES Squadra(nome),
	nomeCampionato VARCHAR(29) REFERENCES Squadra(nomeCampionato),
	anno INT(1) REFERENCES Squadra(anno),
	id INT REFERENCES Giocatore(id),
	presenze INT DEFAULT 0,
	numero INT NOT NULL,
	canestri INT NOT NULL DEFAULT 0,
	PRIMARY KEY (nome, nomeCampionato, anno, id)
);

CREATE TABLE IF NOT EXISTS ruoli(
	nome VARCHAR(20) REFERENCES Ruolo(nome),
	id INT REFERENCES Giocatore(id),
	da DATE NOT NULL,
	a DATE,
	PRIMARY KEY (nome, id, da)
);
```