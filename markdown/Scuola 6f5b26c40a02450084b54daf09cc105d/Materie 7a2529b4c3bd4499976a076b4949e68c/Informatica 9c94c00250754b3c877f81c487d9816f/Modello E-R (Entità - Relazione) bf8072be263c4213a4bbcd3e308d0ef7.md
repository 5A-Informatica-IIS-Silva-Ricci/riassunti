# Modello E-R (Entità  - Relazione)

### Entità

Attraverso l'entità si rappresenta una categoria di soggetti che hanno vita propria.

### Relazione

Una relazione associa due o più entità.

### Relazione ricorsiva

È un legame tra un entità e se stessa

### Attributi di entità e relazioni (attributi semplici)

Descrivono le caratteristiche di una entità / relazione.

### Attributi composti

Sono attributi raggruppati che presentano affinità.

---

# Chiavi

### Chiave interna (chiave semplice)

Attributo o insieme di attributi che identificano univocamente le occorrenze di un'entità.

### Chiave esterna

È una chiave che utilizza attributi anche di altre entità.

---

# Tipi di relazione

- 1 : 1
    
    Definisce un legame tra le occorrenze di due entità di tipo uno ad uno
    
- 1 : n
    
    Lega ciascuna occorrenza di un'entità con più occorrenze di un'altra (1 a molti)
    
- n : n
    
    Molti a molti
    

---

# Cardinalità di relazione

È una coppia di numeri naturali che specifica il numero minimo e massimo di occorrenze che possono essere in relazione con una specifica occorrenza.

In genere il minimo è

- 0 partecipazione opzionale
- 1 partecipazione obbligatoria

Il massimo invece

- 1 singolo
- n multipli

![Untitled](Modello%20E-R%20(Entita%CC%80%20-%20Relazione)%20bf8072be263c4213a4bbcd3e308d0ef7/Untitled.png)

---

# Generalizzazioni

Sono legami logici tra un'entità padre (che contiene caratteristiche generiche) e una o più entità figlie (specializzazioni del padre)

![Screenshot 2021-12-12 at 16.42.46.png](Modello%20E-R%20(Entita%CC%80%20-%20Relazione)%20bf8072be263c4213a4bbcd3e308d0ef7/Screenshot_2021-12-12_at_16.42.46.png)

### Relazione IS-A

- **Totale** o **Parziale**
    - **Totale**: si verifica quando nella mia relazione i figli rappresentano completamente l'entità padre (Es persona → uomo e donna)
    - **Parziale**: si verifica quando nella mia relazione i figli rappresentano solo parzialmente l'entità padre (Es persona → studente e lavoratore, una persona può non essere ne uno studente ne un lavoratore)
- **Esclusiva** o **Sovrapposta**
    - **Esclusiva**: si verifica quando un elemento del padre può essere attribuito solamente ad una entità figlia (Es persona → uomo e donna, una persona può essere solo o uomo o donna)
    - **Sovrapposta**: si verifica quando un elemento del padre può essere attribuito a due o più entità figlie (Es persona → studente e lavoratore, uno studente può essere anche un lavoratore). Per rendere questo esempio una relazione esclusiva basta creare un'altra entità studente&lavoratore e riservare le altre due a chi è esclusivamente studente o lavoratore