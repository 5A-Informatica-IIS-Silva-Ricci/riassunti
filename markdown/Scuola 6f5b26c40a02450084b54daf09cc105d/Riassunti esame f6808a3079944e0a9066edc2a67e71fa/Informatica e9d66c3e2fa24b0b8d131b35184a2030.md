# Informatica

# **Database (base di dati)** 🗂️

*Di che cosa ci occupiamo?*
Di **raccogliere**, **organizzare** e **conservare** dei **dati** (milioni di dati).

<aside>
🔑 Un **sistema informativo** è un sistema che si occupa di raccogliere, organizzare e conservare dati.
ES: Sistema informatico di un comune, di una biblioteca, di una banca…

</aside>

<aside>
🔑 Un **sistema informatico** è un sistema informativo automatico.

</aside>

La gestione di grandi e persistenti quantità di dati può avvenire attraverso l’utilizzo di file 📁 (file system) o attraverso DBMS (Data Base Management System).

Il **DBMS** gestisce quantità di dati che sono:

- grandi (milioni di dati)
- persistenti (reperibili successivamente)
- condivise
- garanti di riservatezza
- efficienti
- efficaci

---

# **Ciclo di vita di un sistema informativo**

1. Studio di fattibilità → analisi dei costi e delle alternative possibili
2. Analisi dei requisiti → analisi dei requisiti hardware e software
3. Progettazione
    - **progettazione concettuale**
    - **progettazione logica**
    - **progettazione fisica**
4. Attuazione con eventuali revisioni e correzioni
5. Funzionamento

---

# **Progettazione concettuale → Modello E-R** (Entità - Relazione)

## Costrutti principali:

1. **Entità** → attraverso l’entità si rappresenta una categoria di soggetti che hanno vita propria.
    
    [https://lh3.googleusercontent.com/dw1uqUwoOA8B4gGYpXSyZoThUC00uCr67ExUFLXGTkNfX5GdA5LAxGFObWmI6kda1WjkDz3KGg1WrRPurx7pa3fLLQjll05GLt5KFuFilQtMXnc0sO9bV7k6u92u9wI2gbZ-KODxs3VrCroFlQ](https://lh3.googleusercontent.com/dw1uqUwoOA8B4gGYpXSyZoThUC00uCr67ExUFLXGTkNfX5GdA5LAxGFObWmI6kda1WjkDz3KGg1WrRPurx7pa3fLLQjll05GLt5KFuFilQtMXnc0sO9bV7k6u92u9wI2gbZ-KODxs3VrCroFlQ)
    
2. **Relazione o Associazione** → una relazione associa due o più entità e si rappresenta attraverso il rombo.
    
    [https://lh5.googleusercontent.com/uazdTU2InXaVpCYYFyXHvr4M199ZSzg3V1eaNSsiSqr9W5_DrKEkoyPYUnpOnKQqGxc3ibnLBd51w16ZB-zSPrLAT4WtAaZTKxlRkKcmMcmTM9aq7yEnpyn6l6msgJUQf5KS8GeB5aJ4E4R7mA](https://lh5.googleusercontent.com/uazdTU2InXaVpCYYFyXHvr4M199ZSzg3V1eaNSsiSqr9W5_DrKEkoyPYUnpOnKQqGxc3ibnLBd51w16ZB-zSPrLAT4WtAaZTKxlRkKcmMcmTM9aq7yEnpyn6l6msgJUQf5KS8GeB5aJ4E4R7mA)
    
3. **Attributi di entità e relazioni** → descrivono le caratteristiche di un'entità o di una relazione
    
    [https://lh4.googleusercontent.com/ll-BKWDEr16E8poQctdyhqU3bxldzLu5zwK_vsCCE6TpY6OLuNb2zxnTTHaY0VN9lvZ9p3FSs_IWTQiI2DQ46qC0yFtApgWpL9uWZPmGpx8oTC08WM4P4hfEc-iN5hkUkFrtd6TORL1KAdOrrg](https://lh4.googleusercontent.com/ll-BKWDEr16E8poQctdyhqU3bxldzLu5zwK_vsCCE6TpY6OLuNb2zxnTTHaY0VN9lvZ9p3FSs_IWTQiI2DQ46qC0yFtApgWpL9uWZPmGpx8oTC08WM4P4hfEc-iN5hkUkFrtd6TORL1KAdOrrg)
    

*Esempio modello E-R*

![Untitled](../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled.png)

---

## Componenti

![Untitled](../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%201.png)

---

## **Tipi di relazione**

La **relazione** è il legame fra due o più entità e ne esistono di **3 tipi**:

1. **Relazione 1-1**: definisce un legame tra le occorrenze di due entità di tipo uno ad uno
    
    [https://lh3.googleusercontent.com/wh0ao7D69-CzR3N6P_blbQTdequMBVR8N_hxFyaf71r4AUWSbfoIKCZ8FuGy2MI9i1G8VqUxadQ_2OIRA7siBbZpMtrgiTEj5wjFePv6riXbRUYT7aq4bKenSfBTEVjv4Phr33ZJ2lG5HItbjw](https://lh3.googleusercontent.com/wh0ao7D69-CzR3N6P_blbQTdequMBVR8N_hxFyaf71r4AUWSbfoIKCZ8FuGy2MI9i1G8VqUxadQ_2OIRA7siBbZpMtrgiTEj5wjFePv6riXbRUYT7aq4bKenSfBTEVjv4Phr33ZJ2lG5HItbjw)
    
2. **Relazione 1:n**: lega ciascuna occorrenza di un’entità con più occorrenze di un’altra entità
    
    [https://lh3.googleusercontent.com/JmZTUJmOBgCMEaao9qD0z3evXHZA17NBBfA3_fj7rYMTPy2tBpx-AJOcoTjh0ZGtsNnJ6drlRJmvBOvB9IPhT5jfgAqWFwQG18GIHbRHyNcQRGZ_1WJktNi6vsYCXT8v6QsjrY5ZKMLigGwxHw](https://lh3.googleusercontent.com/JmZTUJmOBgCMEaao9qD0z3evXHZA17NBBfA3_fj7rYMTPy2tBpx-AJOcoTjh0ZGtsNnJ6drlRJmvBOvB9IPhT5jfgAqWFwQG18GIHbRHyNcQRGZ_1WJktNi6vsYCXT8v6QsjrY5ZKMLigGwxHw)
    
3. **Relazione n:m**; lega più occorrenze di un’entità a più occorrenze di un’altra entità
    
    [https://lh3.googleusercontent.com/h_J58v1S7XJuEqkYJVNoP25RY1opalGJ00p5jLdgrFo54-DAagmZ9-KpfQNY98L4a4kc83Ar74Z3sRtXhamkzwe4cYmM4iS0ga2cs0zJYhaeRtpub3xpL8AnGNnK7JtF8bJ4zxH1ORPtMU6NNQ](https://lh3.googleusercontent.com/h_J58v1S7XJuEqkYJVNoP25RY1opalGJ00p5jLdgrFo54-DAagmZ9-KpfQNY98L4a4kc83Ar74Z3sRtXhamkzwe4cYmM4iS0ga2cs0zJYhaeRtpub3xpL8AnGNnK7JtF8bJ4zxH1ORPtMU6NNQ)
    

---

## **Cardinalità**

<aside>
🔑 E’ una **coppia di numeri naturali** che specifica il numero minimo e massimo di **occorrenze** che possono essere in relazione con una specifica occorrenza.

</aside>

**CARDINALITA’ MINIMA**:

- 0 → partecipazione opzionale
- 1 → partecipazione obbligatoria

**CARDINALITA’ MASSIMA**:

- 1 → massimo 1 partecipante
- n → più partecipanti
    
    [https://lh5.googleusercontent.com/d2KpoBRIo3GvegpD3YPBTkUQxc8wWvXX8GgYBldU0Sm0ZlHhOzKsbglqmLt-UaqcbzDhDQd3baa-m75Yp0-bBaSffhXpkeSjvSBoIXm1TQItGrGgeZkitsFfNkYKcrV6ZpvRBrugeXLRNsbY1Q](https://lh5.googleusercontent.com/d2KpoBRIo3GvegpD3YPBTkUQxc8wWvXX8GgYBldU0Sm0ZlHhOzKsbglqmLt-UaqcbzDhDQd3baa-m75Yp0-bBaSffhXpkeSjvSBoIXm1TQItGrGgeZkitsFfNkYKcrV6ZpvRBrugeXLRNsbY1Q)
    

---

## **Generalizzazioni**

<aside>
🔑 Sono **legami logici** tra un’entità padre (che contiene caratteristiche generiche) e una o più entità figlie (specializzazioni del padre).

</aside>

Rappresentazione:

[https://lh5.googleusercontent.com/5XFBYVsdv_v4C8mbSSeYPTx5nfktMSVtlPAx0owCZV-GdTB-Ttr9GDzlxeszC8ZSZOi-j_37sD9vsu35V2wel53NpAGZPWFqHTxMl_ggHBsNaX-8esF-uDFLWwsI4JimpjbhRodnLJIaX9qXJg](https://lh5.googleusercontent.com/5XFBYVsdv_v4C8mbSSeYPTx5nfktMSVtlPAx0owCZV-GdTB-Ttr9GDzlxeszC8ZSZOi-j_37sD9vsu35V2wel53NpAGZPWFqHTxMl_ggHBsNaX-8esF-uDFLWwsI4JimpjbhRodnLJIaX9qXJg)

## **Relazione IS-A:**  Come può essere?

- **TOTALE O PARZIALE**
    - **TOTALE**: si verifica quando nella relazione i figli rappresentano completamente l’entità padre (*Es: persona → uomo e donna*).
    - **PARZIALE**: si verifica quando nella mia relazione i figli rappresentano solo parzialmente l’entità padre (*Es: persona → studente e lavoratore*). In questo esempio una persona può essere né uno studente né un lavoratore.
- **ESCLUSIVA O SOVRAPPOSTA**
    - **ESCLUSIVA**: si verifica quando un elemento del padre può essere attribuito solamente ad un’entità figlia (*Es: persona → uomo e donna*). Una persona può essere solo uomo o donna.
    - **SOVRAPPOSTA**: si verifica quando un elemento del padre può essere attribuito a due o più entità figlie (*Es: persona → studente e lavoratore*). In questo esempio uno studente può essere anche un lavoratore.

---

# Anomalie ⚠️

| nome_dip | nome_prog | stipendio | budget | ruolo |
| --- | --- | --- | --- | --- |
| Rossi | Marte | 2200 | 50000 | responsabile |
| Rossi | Mercurio | 2200 | 70000 | collaboratore |
| Verdi | Marte | 2300 | 50000 | collaboratore |
| Neri | Marte | 2400 | 50000 | collaboratore |

**ANOMALIE**:

- **di inserimento**: posso inserire i dati del dipendente solo se partecipa ad un progetto perché la chiave è composta da nome_dip + nome_prog.
- **di cancellazione**: se un dipendente termina la sua collaborazione con un progetto devo cancellare tutta la tupla (riga).
- **di aggiornamento**: se varia un campo (ES: stipendio) devo aggiornare tutte le tuple nelle quali è presente.

---

# **Analisi delle ridondanze**

<aside>
🔑 Per **ridondanza** si intende la presenza di **dati uguali** nella stessa tabella o nella relazione che potrebbero essere derivati in diversi modi.

</aside>

Ci sono vari tipi di ridondanze:

- **derivabili da operazioni tra attributi della stessa entità/relazione**
    
    [https://lh4.googleusercontent.com/lZoJ0r2EdBto9CL6nhZgdbTnoEd5rJ3ouJyrhq6Es5fKTFTdZ5bYkbzBXz7BGJsejSj2Z3lOiCw28sDKD3s73YFfTthDw2_IxYBAuYIOkq1YGIV2XHGIXUejigv8LgWcHHL8AN5Vxv6qUGN0OA](https://lh4.googleusercontent.com/lZoJ0r2EdBto9CL6nhZgdbTnoEd5rJ3ouJyrhq6Es5fKTFTdZ5bYkbzBXz7BGJsejSj2Z3lOiCw28sDKD3s73YFfTthDw2_IxYBAuYIOkq1YGIV2XHGIXUejigv8LgWcHHL8AN5Vxv6qUGN0OA)
    
- **derivabili da operazioni tra attributi di entità/relazioni diverse**
    
    [https://lh3.googleusercontent.com/stBJwTFhFt4wLCKKJTf5WpIDAT4i9w3DvIphuKbklKw0-5sg3i8-E6CKKDP18c79SOlSHy5kQSWvhH3-QaKuGiUS3OT7RFcHCZrgSlvYCi9ZmS6YZZlAxJ3kzA5WuAnxZm4h-2g3dlszpMHDYQ](https://lh3.googleusercontent.com/stBJwTFhFt4wLCKKJTf5WpIDAT4i9w3DvIphuKbklKw0-5sg3i8-E6CKKDP18c79SOlSHy5kQSWvhH3-QaKuGiUS3OT7RFcHCZrgSlvYCi9ZmS6YZZlAxJ3kzA5WuAnxZm4h-2g3dlszpMHDYQ)
    
- **derivabili da operazioni di conteggio**
    
    [https://lh4.googleusercontent.com/BDaomXxfzuZ0nXP4fm2Xu0i_NoWXKFEuA1tVUowABp2Kki5nqMnxshAQ5GyU8UXAX2nUELrIadaD-4q_NBV48vWJ5npeS0hr6WR_SD3SK02xyRMiqx6T2I-NSvm_sB4QP8tAMw3VmhxGX3f_DA](https://lh4.googleusercontent.com/BDaomXxfzuZ0nXP4fm2Xu0i_NoWXKFEuA1tVUowABp2Kki5nqMnxshAQ5GyU8UXAX2nUELrIadaD-4q_NBV48vWJ5npeS0hr6WR_SD3SK02xyRMiqx6T2I-NSvm_sB4QP8tAMw3VmhxGX3f_DA)
    

La presenza di ridondanze porta a vantaggi e svantaggi

👍🏼 **Vantaggi**

- riduce al minimo gli accessi necessari per calcolare la variabile ridondante

👎🏼 **Svantaggi**

- occupazione di memoria
- aumenta gli accessi per aggiornare il dato ridondante

---

# **Normalizzazione**

## **Normalizzazione classica**

La **normalizzazione** è un procedimento che ha come obiettivo l’**eliminazione di ridondanze e inconsistenze** (*anomalie*).

**Ridondanza** = presenza di dati ripetuti

**Anomalia:**

- di **aggiornamento**: se viene modificato il budget del progetto p1 si devono aggiornare più dati;
- di **inserimento**: se un nuovo impiegato non partecipa ad un progetto non lo posso inserire;
- di **cancellazione**: se un dipendente termina la partecipazione a tutti i progetti perde l’informazione relativa al suo stipendio.

| codice imp. | stipendio | progetto | budget | ruolo |
| --- | --- | --- | --- | --- |
| i1 | 1000 | p1 | 10000 | impiegato |
| i1 | 1000 | p2 | 20000 | impiegato |
| i2 | 3000 | p1 | 10000 | amministratore |
| i3 | 2500 | p1 | 10000 | analista |

## Livelli di Forma normale

**1 Forma normale (1NF)**

Uno schema è in 1NF solo se ogni attributo è espresso in forma atomica (non ulteriormente scomponibile.

**2 Forma Normale (2NF)**

Uno schema è in 2NF solo se:

- è in 1NF;
- tutti i campi non chiave dipendono funzionalmente dalla chiave intera e non da una parte di essa.

**3 Forma Normale (3NF)**

Uno schema è in 3NF solo se:

- è in 2NF;
- ogni attributo non chiave dipende dalla chiave in forma diretta e non transitiva.

## **Normalizzazione di Boyce-Codd**

**Dipendenza funzionale**: vincolo di integrità che esprime una dipendenza di tipo funzionale tra attributi di una relazione (*tabella*).

| matricola | nome | cognome | materia | docente | voto |
| --- | --- | --- | --- | --- | --- |
| m1 | Aldo | Paoli | matematica | Rinaldi | 25 |
| m2 | Luigi | Neri | matematica | Rinaldi | 26 |
| m3 | Anna | Neri | chimica | Rossi | 25 |
| m4 | Ada | Rinaldi | chimica | Rossi | 27 |
| m1 | Aldo | Paoli | economia | Baldi | 30 lode |

Dipendenze funzionali:

→ matricola → (nome, cognome)

matricola → nome

matricola → cognome

→ materia → docente

→ matricola, materia → voto

Una relazione R è nella forma normale di Boyce-Codd se per ogni dipendenza funzionale X→Y,  X è chiave di R.

*Possiamo notare che questa tabella non è normalizzata secondo Boyce-Codd.*

---

# **Progettazione logica → Modello logico**

Per passare dal modello concettuale al modello logico bisogna effettuare alcune operazioni:

### **ENTITÀ**

Bisogna **eliminare tutti gli attributi composti**

[https://lh5.googleusercontent.com/FrD5aZKdW3MMPuzfapSeGb9YpxQfmW9m2T6Ey9YdpZKXXr6GPFBlqhM2ETmiMLa9tHCXCbCSG0h1GUp1snGiwXVGVTWWbR9nc7dKqUHw-Qv8qO8CwqXWc8g30txPwGTry2RNx1nDIktGbJlBFA](https://lh5.googleusercontent.com/FrD5aZKdW3MMPuzfapSeGb9YpxQfmW9m2T6Ey9YdpZKXXr6GPFBlqhM2ETmiMLa9tHCXCbCSG0h1GUp1snGiwXVGVTWWbR9nc7dKqUHw-Qv8qO8CwqXWc8g30txPwGTry2RNx1nDIktGbJlBFA)

```ruby
Dipendente (matricola, nome, cognome, cap, via, civico)
```

### **RELAZIONE M-N**

Bisogna **specificare i legami con il vincolo di integrità referenziale**

[https://lh6.googleusercontent.com/CuK0BmJ3v_ztZDjM1tp_EAMhllUSS7MjwLioCD-JzI5IushjhccEvsuW3OP3fjXahHFEASuSj4hi6Rm7DqvHhs-rWqpoZbD_E4MArpy7u02eEsHP-jmUYg5NaXRgrqAZYy3ILQ5_eIxwnTFJww](https://lh6.googleusercontent.com/CuK0BmJ3v_ztZDjM1tp_EAMhllUSS7MjwLioCD-JzI5IushjhccEvsuW3OP3fjXahHFEASuSj4hi6Rm7DqvHhs-rWqpoZbD_E4MArpy7u02eEsHP-jmUYg5NaXRgrqAZYy3ILQ5_eIxwnTFJww)

```ruby
Studente (matricola, nome, cognome)
Materia (nome, descrizione)
Esame (matricola, materia, data, voto)
con v.i.r. di matricola con matricola di Studente
con v.i.r. di materia con nome di Materia
```

### **RELAZIONE 1-N**

Bisogna **specificare i legami con il vincolo di integrità referenziale**

[https://lh4.googleusercontent.com/R5EGisAVv32HzNONaAbBWX36k_M3V31WBFVs-Aena1jHmTEYR5voKf77vLeg_Z1o9RzmcT0TJ2NZiHVPkGR-RMzeZiuRFDPYIva9ULCdlEFQ_m-yihMzaoVfbux4Ww4KoYUTCQjbscPy8fKfMA](https://lh4.googleusercontent.com/R5EGisAVv32HzNONaAbBWX36k_M3V31WBFVs-Aena1jHmTEYR5voKf77vLeg_Z1o9RzmcT0TJ2NZiHVPkGR-RMzeZiuRFDPYIva9ULCdlEFQ_m-yihMzaoVfbux4Ww4KoYUTCQjbscPy8fKfMA)

```ruby
Preside (c.f., cognome, nome)
Studente (matricola, nome, cognome, preside)
con v.i.r. di preside con c.f. di Preside
```

### **RELAZIONE 1-1**

1. **con cardinalità minima = 1**
    
    ![Untitled](../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%202.png)
    
    ```ruby
    Presidente (codP, nome, cognome)
    Stato (sigla, nome, popolazione, presidente)
    con v.i.r. di presidente con codP di Presidente
    ```
    
2. **con cardinalità minima = 0**
    
    [https://lh4.googleusercontent.com/QauqViyj_xXaQB4KVbUE5Z2fwoqvhpdS_RJ8mi3hXT_GvfITOql-yiBzQCrwiHmW4lByoH7pIyfqu-DJpdBKKQ4hxCJfKzCf9n_eUAdJONsozZNva5tJ7TnbMSwJ8ziOJ__Vw6bV7bDaSjb-xg](https://lh4.googleusercontent.com/QauqViyj_xXaQB4KVbUE5Z2fwoqvhpdS_RJ8mi3hXT_GvfITOql-yiBzQCrwiHmW4lByoH7pIyfqu-DJpdBKKQ4hxCJfKzCf9n_eUAdJONsozZNva5tJ7TnbMSwJ8ziOJ__Vw6bV7bDaSjb-xg)
    
    ```ruby
    Persona (c.f., nome, cognome)
    Auto (targa, modello, colore, proprietario)
    con v.i.r. di proprietario con c.f. di Persona
    ```
    
    **–** In questo caso abbiamo messo il codice fiscale di Persona all’interno di Auto poiché un’auto ha sempre un proprietario. Se avessimo fatto il contrario il campo targa messo dentro a Persona sarebbe potuto essere risultato vuoto per alcune tuple.
    
3. **con entrambe le cardinalità minime = 0**
    
    [https://lh6.googleusercontent.com/HY870c4T_J4cONwnuYQQS2E59sgupWOLSj_5_MDfUx1zg81zAuDC4AnM2j7_YKOG7EqX611l7M2QdqImrX4fBA0w-zuUQRrHgDv0Frtk1yhZAEAXpMd342_GUMFowcjzVHxIm_ytHxqx_vgHsw](https://lh6.googleusercontent.com/HY870c4T_J4cONwnuYQQS2E59sgupWOLSj_5_MDfUx1zg81zAuDC4AnM2j7_YKOG7EqX611l7M2QdqImrX4fBA0w-zuUQRrHgDv0Frtk1yhZAEAXpMd342_GUMFowcjzVHxIm_ytHxqx_vgHsw)
    
    ```ruby
    Impiegato (c.f., cognome, nome)
    Dipartimento (codD, nome, descrizione, impiegato)
    con v.i.r. di impiegato con c.f. di Impiegato
    ```
    
    **–** In questo caso abbiamo inserito la chiave di Impiegato dentro Dipartimento poiché ipotizziamo abbia meno tuple.
    

### **ENTITÀ DEBOLI (con chiave esterna)**:

![Untitled](../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%203.png)

```ruby
Università (nome, città, anno)
Studente (matricola, uni, nome, cognome)
con v.i.r. di uni con nome di Università
```

### **RELAZIONE IS-A**

Devo prima **ristrutturare** la relazione IS-A

[https://lh5.googleusercontent.com/5IGjEl7Xa3EseKtJq-moxEGUMCU39lhx4d5F-CIlAngLZvNAtvg9QLeOXJl8DRPz34VG1jR0dbG_RpJmKnpXFjxHgoOjbHMjxa84baIBZiyJQFRMJVQY4gckbc0nfX0S-CjtRF91k54YMG3Dfg](https://lh5.googleusercontent.com/5IGjEl7Xa3EseKtJq-moxEGUMCU39lhx4d5F-CIlAngLZvNAtvg9QLeOXJl8DRPz34VG1jR0dbG_RpJmKnpXFjxHgoOjbHMjxa84baIBZiyJQFRMJVQY4gckbc0nfX0S-CjtRF91k54YMG3Dfg)

1. **Ristrutturazione alla Superclasse** (all’entità padre)
    
    In questo caso rimane solo l’entità padre che assorbe gli attributi e le relazioni delle entità figlie e aggiunge un campo per distinguerle.
    
    [https://lh6.googleusercontent.com/t3vOvLVHe9lCJIm9XEKJKPxAv4RH2Zwe9AEFNXfl4grKS_bslNlWRO5uTUyUal_bdjhoT-7yVJ3V77BB9azXTGrUo1x4yuxyC1t6wE7oSdxy74B-E23EMbknDET5qcbzOoxRmXAbbnhVW3GWgw](https://lh6.googleusercontent.com/t3vOvLVHe9lCJIm9XEKJKPxAv4RH2Zwe9AEFNXfl4grKS_bslNlWRO5uTUyUal_bdjhoT-7yVJ3V77BB9azXTGrUo1x4yuxyC1t6wE7oSdxy74B-E23EMbknDET5qcbzOoxRmXAbbnhVW3GWgw)
    
2. **Ristrutturazione alle Sottoclassi** (alle entità figlie)
In questa ristrutturazione rimangono solo le entità figlie che assorbono chiave e attributi dell’entità padre.
    
    [https://lh5.googleusercontent.com/13nlXPrVgt1b1fReVH1y-teyF-A1D_99f9Ub4OYmdEB5QLCcezjW8oQo8fyVfpAG1eAedABMqxNp9PxRIiacGRNXxVqJr4Mj4kTR59dcxr0X9oXLA8kDeSAKdeKRSuTj11C6EIYeLVr9SV07Dw](https://lh5.googleusercontent.com/13nlXPrVgt1b1fReVH1y-teyF-A1D_99f9Ub4OYmdEB5QLCcezjW8oQo8fyVfpAG1eAedABMqxNp9PxRIiacGRNXxVqJr4Mj4kTR59dcxr0X9oXLA8kDeSAKdeKRSuTj11C6EIYeLVr9SV07Dw)
    
    <aside>
    ⚠️ In questo caso non posso usare la ristrutturazione alle sottoclassi poiché la mia relazione è di tipo parziale e questa  					ristrutturazione me la trasforma a totale. Posso applicarla solo a relazioni IS-A totali (*Es: persona → uomo e donna*).
    
    </aside>
    
3. **Ristrutturazione ad Entità deboli**
    
    In questa ristrutturazione rimangono tutte le entità ma le figlie prendono dal padre chiave e attributi.
    *La ristrutturazione ad entità deboli è sempre possibile ed è consigliabile utilizzarla quando le entità figlie sono fortemente specializzate.*
    
    [https://lh3.googleusercontent.com/K6cLsud27i0Zh05lpPmRvjPyHIuk-B-FsL3mX5vtH6lOMs0608EAlTmCMyZB7X3koF9p9lPb5y_3KhYOpR5uvpQomgSmIpzPf_byiLPAVCgW52qME5HhnG-laa864ek54zMQFqV9K7PNqFh8tw](https://lh3.googleusercontent.com/K6cLsud27i0Zh05lpPmRvjPyHIuk-B-FsL3mX5vtH6lOMs0608EAlTmCMyZB7X3koF9p9lPb5y_3KhYOpR5uvpQomgSmIpzPf_byiLPAVCgW52qME5HhnG-laa864ek54zMQFqV9K7PNqFh8tw)
    

---

# **Progettazione fisica → Modello fisico**

Il modello fisico si attua attraverso il linguaggio [**SQL**](Informatica%20e9d66c3e2fa24b0b8d131b35184a2030/SQL%201289ba5b6a7349a4bd3d148127a292b5.md) 

---

# Programmazione delle pagine web principali

La programmazione delle pagine web principali di un applicativo può essere effettuata attraverso diversi linguaggi.
Noi abbiamo utilizzato [PHP](Informatica%20e9d66c3e2fa24b0b8d131b35184a2030/PHP%20db663680b718487e8b0d646462355a4c.md).

[PHP](Informatica%20e9d66c3e2fa24b0b8d131b35184a2030/PHP%20db663680b718487e8b0d646462355a4c.md)  è un linguaggio utilizzato per la programmazione di pagine web dinamiche.

---

# Transazioni

Una transazione è un’unità logica di elaborazione che corrisponde a una serie di operazioni fisiche elementari (letture/scritture) sul DB.

Esempi:

*In entrambi i casi tutte le operazioni elementari devono essere eseguite.*

## ACID

L’acronimo **ACID** indica le 4 proprietà che il DBMS deve garantire che valgano per ogni transazione

- **Atomicity** = una transazione è un’unità di elaborazione
Il DBMS garantisce che la transazione venga eseguita come un tutt’uno
- **Consistency** = una transazione lascia il DB in uno stato consistente
Il DBMS garantisce che nessuno dei vincoli di integrità del DB venga violato
- **Isolation** = una transazione esegue indipendentemente dalle altre
Se più transazioni eseguono in concorrenza, il DBMS garantisce che l’effetto netto è equivalente a quello di una qualche esecuzione sequenziale delle stesse.
- **Durability** = gli effetti di una transazione che ha terminato correttamente la sua esecuzione devono essere persistenti nel tempo
Il DBMS deve proteggere il DB a fronte di guasti

## Esiti di una transazione

Nel modello considerato **una transazione** (il cui inizio viene indicato nel seguito dalla parola chiave `BEGIN`, anche se in SQL è implicito)
**può avere solo 2 esiti**:

1. **Terminare correttamente**:
Questo avviene solo quando l’applicazione, dopo aver eseguito tutte le proprie operazioni, esegue una particolare istruzione SQL, detta `COMMIT` (o `COMMIT WORK`), che comunica “ufficialmente” al Transaction Manager il termine delle operazioni.
2. **Terminare non correttamente** (anticipatamente)
    1. È la transazione che, per qualche motivo, decide che non ha senso continuare e quindi “abortisce” eseguendo l’istruzione SQL `ROLLBACK` (o `ROLLBACK WORK`).
    2. È il sistema che non è in grado (ad es. per un guasto o per la violazione di un vincolo) di garantire la corretta prosecuzione della transazione, che viene quindi abortita.

*Se per qualche motivo la transazione non può terminare correttamente la sua esecuzione il DBMS deve “disfare” (`UNDO`) le eventuali modifiche da essa apportate al DB.*

## Esecuzione seriale di transazioni

Un DBMS, dovendo supportare l’esecuzione di diverse transazioni che accedono a dati condivisi, potrebbe eseguire tali transazioni in sequenza (“serial execution”).
Ad esempio, due transazioni T1 e T2 potrebbero essere eseguite in questo modo, in cui si evidenzia la successione temporale (“schedule”) delle operazioni elementari sul DB:

![Untitled](../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%204.png)

## Possibili errori

### Lost update

Il seguente schedule mostra un caso tipico di lost update, in cui per comodità si evidenziano anche le operazioni che modificano il valore del dato X e si mostra come varia il valore di X nel DB.

![Untitled](../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%205.png)

Il problema nasce perché T2 legge il valore di X prima che T1 (che lo ha già letto) lo modifichi (“entrambe  vedono l’ultimo biglietto”).

### Dirty Read

In questo caso il problema è che una transazione legge un dato “che non c’è”:

![Untitled](../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%206.png)

### Unrepeatable read

Ora il problema è che una transazione legge due volte un dato e trova valori diversi (“il prezzo nel frattempo è aumentato”):

![Untitled](../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%207.png)

## Riassumendo

Una transazione è un’unità logica di elaborazione che, nel caso generale, si compone di molte operazioni fisiche elementari che agiscono sul DB.

Le proprietà di cui deve godere una transazione si riassumono nell’acronimo ACID (Atomicity, Consistency, Isolation, Durability)

Isolation richiede che venga correttamente gestita l’esecuzione concorrente delle transazioni.

Consistency è garantita dal DBMS verificando che le transazioni rispettino i vincoli definiti a livello di schema del DB.

---

# Fonti

- Riassunto Fragonas
    
    [](https://docs.google.com/document/d/19ffw2w-5GIc7dBU0Q_iI9jeHIWeIOsVxFIlb4ju65gs/edit?usp=drivesdk)
    
- Transazioni
    
    [](http://www-db.deis.unibo.it/courses/SI-T/PDF/04.8.SQL.transazioni-2p.pdf)
    
- Altre pagine
    
    [**SQL**](Informatica%20e9d66c3e2fa24b0b8d131b35184a2030/SQL%201289ba5b6a7349a4bd3d148127a292b5.md)
    
    [PHP](Informatica%20e9d66c3e2fa24b0b8d131b35184a2030/PHP%20db663680b718487e8b0d646462355a4c.md)
    
    [Simulazione esame](Informatica%20e9d66c3e2fa24b0b8d131b35184a2030/Simulazione%20esame%207fbafb2d94814cbabd263e13418f8671.md)