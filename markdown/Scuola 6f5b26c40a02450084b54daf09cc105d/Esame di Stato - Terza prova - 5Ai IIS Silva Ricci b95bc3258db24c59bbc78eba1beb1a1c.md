# Esame di Stato - Terza prova - 5Ai IIS Silva Ricci - Anno 2021/2022

# ⌨️ Informatica

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

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled.png)

---

## Componenti

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%201.png)

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
    
    ![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%202.png)
    
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

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%203.png)

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

Il modello fisico si attua attraverso il linguaggio [**SQL**](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/SQL%20dfd8a0d5a7f44a75b219183e07ac5502.md) 

---

# Programmazione delle pagine web principali

La programmazione delle pagine web principali di un applicativo può essere effettuata attraverso diversi linguaggi.
Noi abbiamo utilizzato [PHP](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/PHP%202fda3f6e032742f0b3fc0992346b3759.md).

[PHP](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/PHP%202fda3f6e032742f0b3fc0992346b3759.md)  è un linguaggio utilizzato per la programmazione di pagine web dinamiche.

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

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%204.png)

## Possibili errori

### Lost update

Il seguente schedule mostra un caso tipico di lost update, in cui per comodità si evidenziano anche le operazioni che modificano il valore del dato X e si mostra come varia il valore di X nel DB.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%205.png)

Il problema nasce perché T2 legge il valore di X prima che T1 (che lo ha già letto) lo modifichi (“entrambe  vedono l’ultimo biglietto”).

### Dirty Read

In questo caso il problema è che una transazione legge un dato “che non c’è”:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%206.png)

### Unrepeatable read

Ora il problema è che una transazione legge due volte un dato e trova valori diversi (“il prezzo nel frattempo è aumentato”):

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%207.png)

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
    
    [**SQL**](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/SQL%20dfd8a0d5a7f44a75b219183e07ac5502.md)
    
    [PHP](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/PHP%202fda3f6e032742f0b3fc0992346b3759.md)
    
    [Simulazione esame](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Simulazione%20esame%20fa91afca8c0c450a81c1d6442ed0c628.md)
    

---

# 📡 TPSIT

# I sistemi distribuiti

Le architetture dei sistemi informativi si sono sviluppate ed evolute nel corso degli anni passando da schemi centralizzati a modelli distribuiti.

<aside>
🔑 Nei **sistemi centralizzati** le applicazioni girano in un singolo processore, o comunque su **un solo host** che costituisce l’unico componente autonomo nel sistema.
Un sistema informatico è centralizzato quando **dati e applicazioni** risiedono in un **unico nodo elaborativo**.

</aside>

Un sistema informatico si dice **distribuito** se almeno una delle seguenti due condizioni è verificata:

- **elaborazione distribuita**: le applicazioni risiedono su più host che collaborano tra loro;
- **base di dati distribuita**: il patrimonio informativo è ospitato su più host.

<aside>
🔑 *Un sistema distribuito è costituito da un insieme di applicazioni logicamente indipendenti che collaborano per il perseguimento di obiettivi comuni attraverso un’infrastruttura di comunicazione hardware e software*.

</aside>

Alle applicazioni vengono dati nomi diversi in funzione dei diversi ruoli:

- Cliente (**client**)
- Servente (**server**)
- Attore (**actor**): quando assume sia il ruolo di cliente che quello di servente.

## Classificazione dei sistemi distribuiti

1. Sistemi di calcolo distribuiti che generalmente sono configurati per il calcolo ad alte prestazioni:
    - cluster computing: connessione di **computer omogenei** allo scopo di parallelizzare l’elaborazione.
    - grid computing: la cooperazione di calcolo può essere effettuata anche utilizzando **macchine eterogenee**.
2. Sistemi informativi distribuiti: tra questi sistemi troviamo il **Web**, che risulta essere il più grande sistema distribuito.
3. Sistemi distribuiti pervasivi che sono una nuova generazione di sistemi che hanno tipicamente **connessioni di rete wireless** che generalmente sono sottoparti di sistemi più grandi.

## Vantaggi dei sistemi distribuiti 👍🏼

**Affidabilità**

Grazie alla sua ridondanza è in grado di “sopravvivere” ad un guasto di un suo componente.

**Integrazione**

Capacità di un sistema distribuito di integrare componenti spesso eterogenei tra loro, sia per tipologia hardware, sia per sistema operativo.

Sono stati definiti appositi linguaggi come `XML` e notazioni `JSON` per favorire lo scambio di informazioni nel web e permettere un’agevole ed efficiente pubblicazione di dati complessi.

**Trasparenza**

Come trasparenza si intende il concetto di *vedere* il sistema distribuito non come un insieme di componenti ma come un unico sistema di elaborazione.

Esistono otto forme di trasparenza:

1. di **accesso**: accedere a risorse locali e remote con le stesse operazioni, in modo unico e uniforme.
2. di **locazione**: nascondere dove è localizzata una risorsa e permettere di accedere a essa senza conoscerne la locazione.
3. di **concorrenza**: si permette ai processi di operare in maniera concorrente.
4. di **replicazione**: le operazioni di duplicazione vengono effettuate all’insaputa degli utenti.
5. ai **guasti**: viene mascherato il guasto e il recovery di una risorsa.
6. alla **migrazione**: si nasconde l’eventuale spostamento di una risorsa senza interferire sulla sua modalità di accesso.
7. alle **prestazioni**: vengono nascoste le operazioni necessarie per riconfigurare il sistema al variare del carico.
8. di **scalabilità**: il sistema viene espanso senza interrompere o modificare il funzionamento.

**Economicità**

Generalmente i sistemi distribuiti offrono spesso un miglior rapporto prezzo/qualità dei sistemi centralizzati basati su mainframe.

**Apertura**

Con la definizione di protocolli standard si favorisce l’apertura all’hardware e software di fornitori diversi in modo da avere:

- interoperabilità: implementazioni diverse su elaboratori di diverso tipo possono coesistere per comporre un unico sistema.
- portabilità: un’applicazione sviluppata su un sistema operativo può funzionare su di un altro presentando la medesima interfaccia all’utente in modo da non modificare l’operatività.
- ampliabilità: è relativamente semplice *far crescere* il sistema aggiungendo sia componenti hardware che software.

**Connettività e Collaborazione**

Nei sistemi distribuiti la possibilità di condividere risorse hardware e software comporta vantaggi economici. Per esempio è possibile condividere apparecchiature speciali di costo elevato, quali stampanti particolari, plotter, ecc..

**Prestazioni e scalabilità**

La crescita di un sistema distribuito con l’aggiunta di nuove risorse e, quindi, di nuovi servizi, fornisce a tutti i suoi componenti un miglioramento delle prestazioni e permette di sostenere l’aumento del carico di richieste: questa possibilità prende il nome di **scalabilità orizzontale**.

**Tolleranza ai guasti**

La possibilità di replicare risorse offre una certa garanzia di tolleranza ai guasti; la presenza di un componente guasto non deve pregiudicare il funzionamento del sistema ma, al limite, introdurre solo inefficienze in termini di tempo di risposta.

## Svantaggi legati alla distribuzione 👎🏼

**Complessità**

Proprio per la struttura hardware i sistemi distribuiti sono più complessi di quelli centralizzati: richiedono strumenti per la l’interconnessione degli host e tecniche per l’instradamento corretto dei messaggi.

**Sicurezza**

Con la connessione di più host tra loro si crea la possibilità di accedere a dati e risorse anche a chi non ne ha il diritto: nascono nuove problematiche connesse alla sicurezza che nel caso di sistemi centralizzati erano inesistenti.

**Comunicazione**

Il trasferimento a distanza delle informazioni richiede nuove tipologie di sistemi di telecomunicazione, sia cablati sia wireless, e l’aumento esponenziale degli utenti fa sì che giornalmente aumenti la richiesta di bande trasmissive, anche per migliorare la qualità del servizio offerto.

---

# Evoluzione dei sistemi distribuiti

**Architetture distribuite hardware: dalle SISD al cluster di PC**

Esistono diverse possibilità per classificare le architetture hardware. Noi ricordiamo quella di **Flynn** che si basa sui due flussi di informazioni normalmente presenti nei calcolatori: 

- Flusso delle istruzioni
- Flusso dei dati

|  | Dati singoli | Dati multipli |
| --- | --- | --- |
| Istruzioni singole | SISD | SIMD |
| Istruzioni multiple | MISD | MIMD |

## **SISD**

Un elaboratore come la macchine di **Von Neumann** che ha un solo flusso dati e un solo flusso istruzioni è una macchina Single Instruction stream - Single Data stream (SISD): tutte le macchine che hanno una singola CPU come i personal computer, le workstation e i mainframe appartengono a questa categoria.

## **SIMD**

Nelle macchine SIMD l’elaborazione avviene su più flussi dati in contemporanea ma con un singolo flusso di istruzioni.

## **MISD**

A questa categoria appartengono gli elaboratori che eseguono più istruzioni sullo stesso flusso dati: nel modello di calcolo MISD esistono quindi più processori, ognuno con un proprio flusso di istruzioni che verranno eseguite sullo stesso flusso di dati.

Con questa tipologia di architettura a oggi non sono ancora state costruite macchine da commercializzare.

## **MIMD**

L’architettura Multiple Instruction stream - Multiple Data stream comprende tutte le tipologie di elaboratori composti da più unità centrali di elaborazione indipendenti che possono lavorare su stream di dati anch’essi indipendenti.

Viene effettuata un ulteriore classificazione delle macchine MIMD in riferimento a come è suddivisa la memoria fisica, e cioè possiamo avere:

- Macchine MIMD a memoria fisica condivisa → **multiprocessor**
- Macchine MIMD a memoria privata→ **multicomputer**

## Cluster computing

Con cluster computing si intende un sistema distribuito costituito da un insieme di nodi ad alte prestazioni interconnessi tramite una rete locale ad alta velocità: devono essere **omogenei**, cioè i singoli nodi hanno lo stesso sistema operativo, hardware molto simile e sono connessi attraverso la stessa rete.

Differisce da una rete di PC principalmente per:

- la potenza di elaborazione ad alte prestazioni
- la velocità del trasferimento dati
- la centralizzazione fisica delle macchine, tutti i PC sono montati sullo stesso rack
- la presenza di una applicazione di management che permette di lanciare processi su altri PC, monitorare il loro comportamento ecc.

Abbiamo due possibili architetture:

1. **Organizzazione gerarchica con singolo nodo principale**
2. organizzazione **Single System Image**: per esempio MOSIX, che effettua un bilanciamento automatico del carico effettuando una eventuale migrazione di processi.

## Grid computing

Con grid computing si intende un sistema distribuito di calcolo altamente decentralizzato, composto da un grand numero di nodi disposti a griglia (grid) e caratterizzati da un grado elevato di **eterogeneità** sia per hardware, per il software, la tecnologia di rete, le politiche di sicurezza e molto altro.

**Sistemi distribuiti pervasivi**

Questa è una nuova generazione di SD i cui nodi sono piccoli, mobili, con connessioni di rete wireless e spesso facenti parte di un sistema più grande.

**Reti domestiche e domotica**

Le reti domestiche sono caratterizzate dall’assenza di un amministratore di sistema e generalmente sono sistemi completamente auto-configuranti e autogestiti in quanto generalmente gli utenti non hanno conoscenze specifiche di connettività

**Wearable computing**

Oggi i sistemi wearable computing sono essenzialmente utilizzati per l’assistenza sanitaria ed effettuano il monitoraggio di parametri biologici o memorizzando i dati in un computer palmare oppure trasmettendo i dati a un sistema di archiviazione remoto.

## Architettura a terminali remoti

Tutte le operazioni vengono effettuate da un’unica entità centrale alla quale sono collegati terminali privi di capacità di elaborazione che si limitano a visualizzare e inviare e ricevere le informazioni alla entità centrale.

## Architettura client-server

I client richiedono un servizio a un server *di competenza*, che è in grado di esaudirne la richiesta, la elabora e invia la risposta.

Possono essere presenti più server che offrono più servizi contemporaneamente così come più client possono richiedere lo stesso servizio o servizi differenti sia a server diverso che allo stesso server.

Inoltre un server può essere contemporaneamente anche client: quindi può essere server per uno, o più, servizi e client per altri richiedendo i servizi che necessita ad altri server.

## Architettura WEB-centric

L’evoluzione che negli ultimi anni ha caratterizzato i sistemi distribuiti riguarda il Web: la diffusione capillare delle piattaforme mobili ha provocato uno spostamento delle applicazioni sul server facendo  regredire gli host quasi a host utilizzati solo per l’interfaccia grafica verso l’utente.

Il Web server è il centro del sistema distribuito al quale i client vi accedono per ottenere dei servizi: tutta la computazione avviene sui server che restituisce ai client il risultato.

## Architettura cooperativa

L’evoluzione dell’architettura client-server è l’architettura cooperativa che si basa su entità autonome che esportano e richiedono servizi secondo il modello di sviluppo a componenti per la programmazione lato server proprio della programmazione a oggetti.

## Architettura completamente distribuita

In opposizione alla architettura Web-centric troviamo l’architettura completamente distribuita, tipica di sistemi dove è necessaria la cooperazione di gruppi di entità paritetiche, come nei sistemi groupware, che dialogano tra loro offrendo ciascuno i propri servizi e richiedendo servizi che spesso risultano essere duplicati per garantire l’immunità ai guasti.

## Architettura a livelli

Per alleggerire il carico elaborativo dei serventi sono state introdotte le applicazioni multilivello, nelle quali avviene la separazione delle funzionalità logiche del software in più livelli.

Si introducono gli **strumenti** ****di** **middleware**, cioè uno strato software *in mezzo* che si colloca sopra al sistema operativo ma sotto i programmi applicativi, e sono l’evoluzione dei sistemi operativi distribuiti.

<aside>
💡 Il middleware ha lo scopo di realizzare la comunicazione e le interazioni tra i diversi componenti software di un sistema distribuito.

</aside>

Tra le funzionalità del middleware troviamo:

- I servizi di astrazione e cooperazione
- I servizi per le applicazioni
- Il servizio di comunicazione

# La comunicazione nel Web con protocollo HTTP

## HTTP e il modello client - server

Il Web è basato sul modello **client - server**.

I **client** sono elementi **attivi** che richiedono pagine Web ai server e ne visualizzano il contenuto.

I **server** sono elementi **passivi** che rimangono in ascolto di eventuali connessioni di nuovi client su una determinata porta TCP, secondo un modello a server passivo e forniscono ai client le pagine Web o le risorse richieste.

HTTP è un protocollo usato per trasmettere risorse, non solo file. Una risorsa è identificata da un URI o URL.

- **URI** (*Uniform Resource Identifier*): set generico di nomi o indirizzi che rappresentano stringhe assegnate alle risorse
- **URL** (*Uniform Resource Locator*): termine informale, utilizzato solo nelle specifiche tecniche, associato a popolari protocolli quali HTTP, FTP, ecc..

## Il protocollo HTTP

<aside>
💡 Http è un protocollo di testo che fornisce il livello di trasporto a tutti i protocolli applicativi basati su di esso.

</aside>

**Http**, acronimo di *Hyper Text Transfer Protocol*, è un **protocollo** che consente di **inviare e ricevere le risorse Web** da un host chiamato **server** a un altro chiamato **client**.

Per comunicare utilizza le sessione, dove ciascuna inizia stabilendo per prima cosa una connessione TCP al server, utilizzando di default la porta TCP 80, effettuando poi una request contenente un URL. In risposta il server produce e restituisce il file richiesto e, nella situazione più semplice, chiude la connessione TCP immediatamente dopo.

**Conversazione Client - Server**

Ogni conversazione tra client e server sul Web inizia con una richiesta rappresentata da un messaggio di testo creato dal client in formato HTTP. Il client invia la richiesta al server, quindi attende la risposta.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%208.png)

## Tipi di connessioni

Il protocollo HTTP utilizza TCP come protocollo di trasporto per effettuare le connessioni tra client e server.

Nella connessione di HTTP 1.1 di tipo permanente il **server lascia aperta la connessione TCP** dopo aver spedito la risposta. Le successive richieste e risposte fra client e server utilizzano sempre la stessa connessione.

Esistono due tipi di connessioni permanenti:

- connessione permanente **incanalata →**  le richieste vengono via via aggiunte a una coda chiamata pipeline, mentre le risposte vengono processate e inviate nello stesso ordine delle richieste.
- connessione permanente **non incanalata →** il client passa una nuova richiesta solo quanto la risposta alla precedente è stata ricevuta.

## HTTP Request

La prima riga della request contiene la versione del protocollo HTTP utilizzato, mentre nelle righe successive vengono indicate gli header, rappresentate da diversi elementi, ciascuno dei quali composto da un nome, seguito dai due punti e da un valore.

Gli header più comuni sono: 

- la versione del browser che prende il nome di User-Agent
- l’host presente nell’URL

Una http request è un messaggio testuale inviato dal client al server HTTP ed è formato da tre elementi:

- riga di richiesta,
- intestazione HTTP (header)
- corpo del messaggio (message body)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%209.png)

**Riga di richiesta**

La riga di richiesta contiene:

- Il metodo:
    - `GET`
    - `HEAD`
    - `POST`
    - `PUT`
    - `DELETE`
    - `OPTIONS`
- l’URI (o URL) è l’identificativo di risorsa richiesta
- la versione

**Intestazione HTTP**

L’intestazione HTTP contiene tutte le informazioni necessarie per l’identificazione del messaggio ovvero i vari header (*esempio:* `content-type: text/html`).

**Corpo del messaggio**

Il corpo del messaggio di richiesta contiene i dati trasportati.

## Messaggio di risposta: HTTP Response

- Una riga iniziale con versione protocollo e stato
- un’intestazione facoltativa
- un corpo facoltativo.

## Metodi HTTP

<aside>
💡 API → Application Programming Interface

</aside>

> Le applicazioni RESTful consentono di effettuare operazioni da remoto sui dati presenti nei server, che lo permettono, sfruttando i metodi del protocollo HTTP. Le operazioni di tipo CRUD (*Create, Retrieve, Update, Delete*) possono essere così descritte:
> 
- chiedere dati al server (`GET`)
- creare dati sul server (`POST`)
- modificare o sostituire i dati sul server (`PUT`)
- cancellare dati sul server (`DELETE`)

## I codici di stato

I codici di stato, o status code, sono dei codici restituiti dai server HTTP per indicare al client l’esito di una richiesta.

1. `100-199` (*Information*): questi codici di risposta forniscono informazioni temporanee alla richiesta, durante il suo svolgimento e a partire dalla versione 1.0 viene sconsigliato il loro utilizzo.
2. `200-299` (*Successful*): questo intervallo di codici di stato indica il completamento di una richiesta con successo.
3. `300-399` (*Redirection*): questi codici vengono utilizzati per comunicare una varietà di stati che non indicano un errore, ma che richiedono un trattamento particolare da parte del browser.
4. `400-499` (*Client error*): questo intervallo di valori viene utilizzato per indiCare le condizioni di errore provocate dal comportamento del client.
5. `500-599` (*Server error*): è una classe di messaggi di errore, prodotti come risposta a problemi verificatisi sul server.

# Le applicazioni Web e il modello client - server

Due concetti fondamentali stanno alla base delle applicazioni Web:

1. Tecnologie client - side e server - side
2. linguaggi di mark-up e linguaggi di programmazione

## Tecnologie del Web

Possiamo distinguere le tecnologie del Web in due gruppi:

1. Tecnologie **client - side**: sono le strutture tecnologiche in cui l’elaborazione avviene sul client, tipicamente nel browser:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2010.png)

1. Tecnologie **server - side**: sono le strutture tecnologiche in cui l’elaborazione avviene sul server, tipicamente nel Web server:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2011.png)

<aside>
💡 Nella realizzazione di applicazioni Web le tecnologie client - side o server - side non vengono scelte arbitrariamente: ci sono elaborazioni che si possono fare solo client-side e altre che si possono fare solo server-side.

</aside>

**Linguaggio del Web**

Nel web vengono utilizzate **due tipologie di linguaggi**: i linguaggi di **mark-up** **e** i linguaggi d **programmazione**.

1. I linguaggi di mark-up servono a scrivere documenti strutturati, come `HTML`, `XML`, `JSON`
2. I linguaggi di programmazione servono a scrivere programmi, come `Java` e `PHP`.

## Il modello client - server

Il modello client-server è costituito da un insieme di host che gestiscono una (o più) risorse, i server, e da un insieme di client che richiedono l’accesso ad alcune risorse distribuite.

Non sono gli host ad essere server o client ma i processi che sono in esecuzione su di essi, dove come processo si intende un programma in esecuzione.

Lo schema di funzionamento di un modello client - server: 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2012.png)

1. Il client manda una richiesta al server
2. il server riceve la richiesta
3. il server esegue il servizio richiesto
4. il server manda una risposta ed eventualmente dei dati
5. il client riceve la risposta

Alcuni servizi tipici delle architetture Client - Server sono:

- Telnet
- HTTP
- FTP
- SMTP, IMAP4, e così via.

<aside>
💡 Un client per comunicare con un server usando il protocollo TCP/IP deve per prima cosa connettersi al socket dell’host dove il server è in esecuzione specificando l’indirizzo IP della macchina e il numero di porta sulla quale il server è in ascolto.

</aside>

## Comunicazione unicast e multicast

- **Unicast**: il server comunica con un solo client alla volta accettando una richiesta di connessione solo se nessun altro client è già connesso.
- **Multicast**: al server possono essere connessi più client contemporaneamente.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2013.png)

## Livelli e strati

Le architetture client - server sono normalmente **organizzate** **a** “livelli” (**tier**) dove ogni livello corrisponde a un nodo o gruppo di nodi di calcolo su cui è distribuito il sistema.

In genere nelle applicazioni possiamo individuare tre tipi principali di funzionalità che corrispondono a una struttura in tre strati:

- **front-end** o presentation tier: interfaccia verso l’utente
- **logica applicativa** o middle tier (*business logic*)
- **back-end** con accesso alle risorse e ai dati, anche detto *data tier*.

Solitamente viene utilizzata questa nomenclatura:

- **Presentation Layer** (*PL*): composta dall’insieme delle procedure o moduli dedicate all’acquisizione e alla presentazione dei dati all’utente
- **Resource Management Layer**: è composto dall’insieme delle procedure che gestiscono i dati
- **Business Logic Layer**: è il corpo centrale dell’applicazione che comprende la logica della elaborazione.

## Architettura a un livello - 1 tier

Questa architettura non rientra nella tipologia client -server e può essere classificata come architettura a un solo livello.

Tutta l’elaborazione è effettuata dall’elaboratore centrale e i terminali servono solo per I/O.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2014.png)

## Architettura a due livelli - 2 tier

- un livello server
- un livello client

Possiamo individuare due sottocategorie:

1. il modello **Thin-client**, dove il server è responsabile della logica applicativa e gestione dei dati e il client è responsabile della visualizzazione:
    
    ![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2015.png)
    
2. Il modello **Thick-client** dove il server è responsabile della gestione dei dati mentre il client è responsabile della logica applicativa e della presentazione:
    
    ![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2016.png)
    
    <aside>
    💡 Il limite delle architetture client - server a due livelli è che sono poco scalabili dato che il server deve gestire la connessione e lo stato della sessione di ciascun client.
    
    </aside>
    
    ## Architettura a tre livelli - 3 tier
    
    - front-end o presentation tier
    - logica applicativa o middle tier
    - back-end con accesso alle risorse e ai dati, detto data tier.
    
    I vantaggi dell’introduzione del middleware sono notevoli, soprattutto in termini di prestazioni, in quanto in questo modo si favorisce la distribuzione della quantità di elaborazione.
    
    Nei sistemi 3-tier è però più difficile la progettazione, lo sviluppo e l’amministrazione.
    
    ![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2017.png)
    
    ## Architetture multi-tier
    
    Le architetture client - server a N livelli sono una generalizzazione del modello client - server a tre livelli dove vengono scomposti e introdotti un numero qualunque di livelli e server intermedi.
    
    <aside>
    💡 Questa scomposizione viene effettuata per suddividere ulteriormente i compiti dei vari strati: prende il nome di multi-tier
    
    </aside>
    

# Le applicazioni di rete

Il livello applicazione implementa i vari protocolli, tra cui:

- SMTP
- FTP
- HTTP
- DNS

> Non va quindi confusa l’applicazione con il livello di applicazione: il livello di applicazione è lo strato protocollare che mette a disposizione i protocolli mediante i quali le applicazioni possono comunicare tra host remoti.
> 

## Applicazioni di rete

In generale un’applicazione di rete è costituita da un insieme di programmi che vengono eseguiti su due o più computer contemporaneamente.

<aside>
💡 L’applicazione di rete prende anche il nome di applicazione distribuita dato che non viene eseguita su di un solo elaboratore.

</aside>

## Identificazione di un servizio mediante socket

<aside>
💡 L’identificazione non può avvenire soltanto mediante l’indirizzo IP del destinatario, in quanto quest’ultimo individua soltanto l’host ma non il processo specifico e su un host sono sicuramente in esecuzione più processi contemporaneamente.

</aside>

Per individuare il processo viene utilizzato un identificatore unico per l’host, chiamato numero di porta.

Il client contatta il server usando l’**identificatore dell’host** (indirizzo IP) + l’**identificatore del servizio** (numero di porta)

> Un numero di porta non può essere associato a più processi ma un server può offrire più servizi, ciascuno su un’apposita porta.
> 

Questo meccanismo prende il nome di **socket** ([I socket e la comunicazione con i protocolli TCP/UDP](https://www.notion.so/I-socket-e-la-comunicazione-con-i-protocolli-TCP-UDP-9e68b5567d024e148c6481d165b11053)).

> *Il server offre il servizio a più client e deve gestire la concorrenza: il socket di connessione è anche chiamato socket di benvenuto e alla richiesta accettata di un client il server crea dinamicamente un nuovo thread e gli assegna un socket di connessione.*
> 

## Architettura per l’applicazione di rete

- Client server
- Peer to peer
- Architetture ibride

**Architettura client server**

La caratteristica principale è che deve sempre esserci un server attivo che offre un servizio restando in attesa che uno o più client si connettano a esso per poter rispondere alle richieste che gli vengono effettuate.

Un client non è in grado di comunicare con gli altri client ma solo con il server: più client invece possono comunicare contemporaneamente con lo stesso server.

**Architettura Peer to Peer**

In questo tipo di architettura abbiamo coppie di host chiamati peer che dialogano direttamente tra loro

<aside>
💡 E’ formato da un insieme di entità autonome capaci di auto organizzarsi, che condividono un insieme di risorse distribuite presenti all’interno di una rete. Il sistema utilizza tali risorse per fornire una determinata funzionalità in modo completamente o parzialmente decentralizzato.

</aside>

- **P2P decentralizzato**
    
    Un peer ha sia funzionalità di client che di server ed è impossibile localizzare una risorsa mediante un indirizzo IP statico.
    
    Le risorse che i peer condividono sono dati, la memoria, la banda ecc..
    
- **P2P centralizzato**
    
    è un compromesso tra il determinismo del modello client - server e la scalabilità del sistema puro: ha un server centrale che conserva informazioni sui peer e risponde alle richieste su quelle informazioni effettuando quindi la ricerca in modalità centralizzata.
    
    I peer sono responsabili di conservare i dati e le informazioni.
    
- **P2P ibrido**
    
    è un P2P parzialmente centralizzato dove sono presenti alcuni peer determinati dinamicamente che hanno anche la funzione di indicizzazione: gli altri nodi sono anche chiamati leaf peer.
    

## Servizi offerti dallo strato di trasporto

Ogni applicazione deve scegliere tra i protocolli di trasporto quale deve adottare per realizzare un protocollo applicativo in base ai servizi che sono necessari alle specifiche esigenze della applicazione, che possono essere:

- Trasferimento dati affidabile,
- ampiezza di banda
- temporizzazione
- sicurezza

**Trasferimento dati affidabile**

Intendiamo un servizio che garantisce la **consegna completa e corretta dei dati**.

Ci sono due protocolli:

- **UDP**: protocollo senza connessione da utilizzarsi quando la perdita di dati è un fatto accettabile in quanto non è affidabile.
- **TCP**: orientato alla connessione da utilizzarsi quando la perdita di dati è un evento inaccettabile.

**Ampiezza di banda**

Alcune applicazioni necessitano di una garanzia sulla larghezza di banda minima disponibile, come la trasmissione di un evento in diretta in una web - TV.

**Temporizzazione**

Alcune applicazioni per essere “realistiche” ammettono solo piccoli ritardi per essere efficaci: lo strato di trasporto non è in grado di garantire i tempi di risposta perchè le temporizzazioni presenti assicurano un certo ritardo end-to-end tra le applicazioni.

Il protocollo TCP garantisce la consegna del pacchetto ma non il tempo che ci impiega e neppure il protocollo UDP, nonostante sia più veloce del TCP, è temporalmente affidabile.

**Sicurezza**

Un’applicazione può richiedere allo strato di trasporto la cifratura di tutti i dati trasmessi in modo tale che anche se questi venissero intercettati da malintenzionati non si perda la riservatezza.

È quindi possibile che vengano richiesti dei servizi di sicurezza da applicare per garantire l’integrità e la riservatezza dei dati.

# Applicazione di rete

I processi hanno la necessità di scambiare messaggi con gli altri processi della medesima applicazione, per comunicare tra loro questi processi devono mettersi in contatto tramite i loro indirizzi e utilizzare i servizi offerti dal livello di applicazione.

La pila protocollare di Internet (TCP/IP) è costituita da cinque livelli:

- Applicazione (Messaggio)
- Trasporto (Segmento)
- Rete (Datagram)
- Collegamento (Frame)
- Fisico (Segnale fisico)

<aside>
💡 Lo strato di trasporto della rete Internet mette a disposizione delle applicazioni attive in ciascun host due distinti protocolli di trasporto: **TCP** e **UDP**.

</aside>

TCP e UDP svolgono funzioni diverse, cioè offrono servizi diversi allo strato applicativo:

- il protocollo **TCP** è orientato alla connessione (*connection - oriented*) ed è affidabile
- il protocollo **UDP** è senza connessione (*connectionless*) e quindi non affidabile.

# Le porte di comunicazione e i socket

<aside>
💡 Affinchè un processo, presente su un determinato host, invii un messaggio a un qualsiasi altro host, il processo mittente deve identificare il processo destinatario in modo univoco.

</aside>

Ogni PC ha una sola porta fisica di connessione al network, perciò sono state introdotte le porte logiche che identificano il processo corretto.

Questo numero di porta viene definito port address oppure sinteticamente port, in questo modo è possibile instaurare simultaneamente più comunicazioni cosicchè due applicazioni possono comunicare l’una con l’altra indipendentemente dal fatto che sulla rete stiano avvenendo altre comunicazioni.

> Il numero di port è specificato su 2 Byte, **da 0 a 65535**.
> 
- I port da **0 a 1023** sono riservati ad applicazioni particolari, costituiscono i cosiddetti **well-know port numbers**.
- I port da **1024 a 49151** sono riservati a porte registrate e sono usasti da alcuni servizi ma possono anche essere utilizzati dai client.
- I numeri di porta da **49152 a 65535** sono liberi per essere assegnati dinamicamente dai processi applicativi.

*Alcuni esempi*

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2018.png)

<aside>
💡 I numeri di porta logica sono relativi soltanto al protocollo considerato: una determinata porta per il protocollo TCP è diversa dallo stesso numero di porta per il protocollo UDP.

</aside>

L’identificazione di un servizio avviene quindi combinando l’indirizzo IP dell’host e della porta logica, metodo che prende il nome di **socket**.

<aside>
🔑 Un **socket** è formato dalla coppia **<indirizzo IP:numero della porta>** è un identificatore analogo a una porta, cioè a un punto di accesso/uscita, unico per ogni rete.

</aside>

Esiste una struttura chiamata **association** che consente d’identificare ogni singola connessione in modo univoco e che contiene le seguenti informazioni:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2019.png)

# Socket e i processi client - server

<aside>
💡 Il client deve conoscere l’indirizzo IP e il numero di porta usati dal server per potersi collegare al socket di destinazione.

</aside>

*Quando un client apre un socket non dovrebbe utilizzare una porta nota, in quanto riservata per l’offerta di servizi.*

# La connessione tramite socket

Il concetto di socket è stato sviluppato come estensione diretta del paradigma UNIXX di I/O su file, si basa sulla sequenza:

- **Open**: permette di accedere al file
- **Read/Write**: accedono ai contenuti del file
- **Close**: terminazione dell’utilizzo del file.

Le funzioni utili per l’utilizzo dei socket in Java sono:

- `ServerSocket()`: crea un nuovo socket
- `close()`: termina l’utilizzo di un socket
- `bind()`: collega un indirizzo di rete a un socket
- `listen()`: aspetta messaggi in ingresso
- `accept()`: comincia a utilizzare una connessione in ingresso
- `connect()`: crea una connessione con un host remoto
- `write()` trasmette dati su una connessione attiva
- `read()`: riceve dati da una connessione attiva

## Famiglie e tipi di socket

Esistono varie famiglie di socket, dove ogni famiglia riunisce i socket che utilizzano gli stessi protocolli, in particolare ricordiamo:

- **Internet socket** (AF_INET): è quella che permette il trasferimento di dati tra processi posti su macchine remote connesse tramite LAN
- **Unix Domain Socket** (AF_UNIX): permette il trasferimento di dati tra processi sulla stessa macchina Unix

> La principale differenza tra queste due famiglie è l’indirizzo:
> 
> 
> AF_UNIX è praticamente il pathname valido nel file system della macchina.
> 
> AF_INET è specificato in due valori:
> 
> - Indirizzo IP che individua un unico host internet
> - Numero di porta che specifica una particolare porta dell’host

## Tipi di socket

I socket sono di **tre tipi**:

- **Stream** socket
- **Datagram** socket
- **Raw** socket

## Stream socket

Con gli stream socket si realizza una connessione sequenziale tipicamente asimmetrica, affidabile e full-duplex basata su stream di byte di lunghezza variabile.

Ogni processo crea il proprio endpoint richiamando la primitiva `socket()` e successivamente:

- Il server si mette in ascolto e quando gli arriva una richiesta la esaudisce mediante la primitiva `accept()` che crea un nuovo socket dedicato alla connessione
- il client si pone in coda sul socket del server e quando viene accettato dal server crea implicitamente il binding con la porta locale.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2020.png)

<aside>
💡 Il protocollo TCP è basato su questo tipo di socket.

</aside>

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2021.png)

## Datagram socket

Con i datagram socket viene realizzata la comunicazione che permette di scambiare dati senza connessione mediante il trasferimento di datagrammi che inoltrano messaggi di dimensione variabile, senza garantire ordine o arrivo dei pacchetti.

Ogni processo crea il proprio endpoint richiamando la primitiva che crea il socket e successivamente:

- Il server si mette in attesa di ricevere i dati e alla loro ricezione può inviare una risposta
- Il client invia il pacchetto di dati al server e può mettersi in attesa di una risposta con le stesse primitive che ha utilizzato il server.

Al termine della comunicazione il socket viene chiuso.

<aside>
💡 Il loro vantaggio è quello di trasferire velocemente i dati, *decade* anche il concetto di client e server dato che utilizzano le stesse primitive e solo il loro ordine stabilisce nella applicazione quale processo fa la funzione di server e quale quella di client

</aside>

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2022.png)

## Trasmissione unicast e multicast

L’**unicast** è la normale situazione in cui un mittente invia e un destinatario riceve con eventualmente l’inversione dei ruoli, mentre il **multicast** è utilizzato per trasmettere informazioni a più host contemporaneamente.

<aside>
💡 Il TCP è per la sua natura di protocollo orientato alla connessione, sempre unicast.

L’UDP è invece multicast.

</aside>

Nella comunicazione di tipo multicast un insieme di processi formano un gruppo di multicast e un messaggio spedito da un processo a quel gruppo viene recapitato a tutti gli altri partecipanti appartenenti al gruppo.

Le API multicast devono contenere primitive per:

- unirsi a un gruppo (join)
- lasciare un gruppo (leave)
- spedire messaggi a un gruppo
- ricevere messaggi indirizzati a un gruppo del quale l’host fa parte.

La gestione dei gruppi è di tipo dinamico:

- un host può unirsi o abbandonare un gruppo in qualsiasi momento e può appartenere a più gruppi
- non è necessario appartenere a un gruppo per poter inviare a esso dei messaggi
- i membri del gruppo possono appartenere alla medesima rete o a reti fisiche differenti

Come indirizzo di multicast viene utilizzato un indirizzo IP di classe D, gli indirizzi possono essere:

- **permanenti**, l’indirizzo di multicast viene assegnato dalla IANA e rimane assegnato a quel gruppo anche se in un certo momento non ci sono più partecipanti
- **temporanei**, richiedono la definizione di un opportuno protocollo per evitare conflitti nell’attribuzione degli indirizzi ai gruppi ed esistono solo fino al momento in cui esiste almeno un partecipante.

<aside>
💡 Nei router viene mantenuta la corrispondenza tra l’indirizzo di multicast e gli indirizzi IP dei singoli host che partecipano al gruppo.

</aside>

> La comunicazione multicast utilizza il paradigma **connectionless** dato che devono essere gestite contemporaneamente un alto numero di connessioni.
> 

## Esempio socket in Java

### Stream socket

```java
import java.io.IOException;
import java.net.InetAddress;
import java.net.Socket;
import java.net.ServerSocket;

public class StreamClient {
		public StreamClient() throws IOException {
        // Creo il socket connesso al server socket tramite IP e porta
        Socket cs = new Socket(InetAddress.getLocalHost(), 1025);

        // Invio "4" al server
        cs.getOutputStream().write(4);
        // Aspetto la risposta
        int square = cs.getInputStream().read();
        // Visualizzo la risposta
        System.out.println(square);

        // Chiudo il socket
        cs.close();
		}
}

public class StreamServer {
    public StreamServer() throws IOException {
        // Creo il socket per il server
        ServerSocket ss = new ServerSocket(1025);
        // Abilito le richieste
        Socket ds = ss.accept();

        // Aspetto una richiesta
        int n = ds.getInputStream().read();
        System.out.println("Richiesto il quadrato di " + n);
        // Creo la risposta
        int square = n*n;
        // Invio la risposta
        ds.getOutputStream().write(square);

        // Chiudo il socket
        ss.close();
    }
}
```

### Datagram socket

```java
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.net.DatagramPacket;
import java.net.DatagramSocket;
import java.net.InetAddress;
import java.nio.charset.StandardCharsets;

public class DatagramClient {
    public DatagramClient() throws IOException {
        // Creo il socket datagram
        DatagramSocket ds = new DatagramSocket();

        // Prendo in input da tastiera del testo
        BufferedReader tastiera = new BufferedReader(new InputStreamReader(System.in));
        String testo = tastiera.readLine();
        // Creo il buffer con i byte del testo
        byte[] buffer = testo.getBytes(StandardCharsets.UTF_8);

        // Creo il pacchetto datagram
        InetAddress indirizzoServer = InetAddress.getLocalHost();
        DatagramPacket packet = new DatagramPacket(buffer, buffer.length, indirizzoServer, 1025);

        // Invio il pacchetto
        ds.send(packet);

        // Preparo il pacchetto che dovrà contenere la risposta ricevuta dal server
        byte[] bufferResponse = new byte[2048];
        DatagramPacket response = new DatagramPacket(bufferResponse, bufferResponse.length);

        // Aspetto la risposta
        ds.receive(response);
        // La visualizzo
        System.out.println(new String(response.getData()).trim());

        // Chiudo il socket
        ds.close();
    }
}

public class DatagramServer {
    public DatagramServer() throws IOException {
        // Creo il socket datagram
        DatagramSocket ds = new DatagramSocket(1025);

        // Creo il buffer ed il pacchetto datagram per la richiesta del client
        byte[] buffer = new byte[2048];
        DatagramPacket packet = new DatagramPacket(buffer, buffer.length);

        // Aspetto un pacchetto
        ds.receive(packet);

        // Estrapolo il messaggio
        String messaggio = new String(packet.getData()).trim();

        // Invio la risposta con il messaggio in UpperCase
        String messaggioUppercase = messaggio.toUpperCase();
        DatagramPacket response = new DatagramPacket(messaggioUppercase.getBytes(StandardCharsets.UTF_8), messaggio.length(), packet.getAddress(), packet.getPort());
        ds.send(response);

        // Chiudo il socket
        ds.close();
    }
}
```

### Esempio applicativo

[Socket/src/main/java/socket/esercizi/giocodellabomba at main · 5A-Informatica-IIS-Silva-Ricci/Socket](https://github.com/5A-Informatica-IIS-Silva-Ricci/Socket/tree/main/src/main/java/socket/esercizi/giocodellabomba)

# Le applicazioni lato server

<aside>
🔑 Con il termine **programmazione server - side** viene indicato il meccanismo mediante il quale tutto o parte del documento richiesto dal client viene generato in seguito a un’elaborazione che viene eseguita dal server.

</aside>

Oggi sono disponibili diverse tecniche di programmazione server-side.

Una prima classificazione può essere fatta in base alla “relazione” che questi programmi hanno con l’HTML:

- **Codice separato**, associato ad un URL:
    - Common Gateway Interface (CGI)
    - Java servlet
    - NSAPI (o server API)
- **Codice embedded in HTML**:
    - Server Side Includes - Apache
    - PHP
    - Java Server Pages (JSP)

## Common Gateway Interface (CGI)

Viene invocata una procedura indicando l’indirizzo del programma CGI il quale viene eseguito sul server e al quale vengono inviati i parametri letti nel form html.

Le operazioni sono:

1. Il client invia al server la richiesta di eseguire un programma CGI
2. Il server chiama il programma indicato dal client passandogli i parametri letti nel form
3. Il programma CGI esegue le operazioni e comunica al server la pagina HTML di risposta
4. il server invia al client i dati elaborati

Per comunicare con l’utente il programma CGI produce una pagina HTML e la passa al Web server che la invia al client.

## Servlet

La principale differenza tra servlet e CGI è che gli script CGI sono eseguiti dal sistema operativo e sono potenzialmente meno portatili delle **servlet** che vengono **eseguite dalla JVM** integrata nel Web server.

Gli script CGI inoltre vengono cariati ed eseguiti una volta per ogni richiesta, mentre le servlet vengono caricato solo una volta e viene creato un thread per ogni richiesta.

<aside>
💡 Una servlet è un componente software scritto in **Java**, gestito da un “container”, che produce contenuto Web dinamico.

</aside>

Il Web server stesso svolge la funzione di container occupandosi della gestione del ciclo di vita delle servlet.

Una servlet interagisce con un Web client attraverso il paradigma di comunicazione request/response.

Flusso di esecuzione:

1. Un client invia una richiesta per una servlet a una Web application server
2. Se si tratta di una prima richiesta allora il server carica la servlet
3. Si attiva un thread che gestisce la comunicazione tra il client e la servlet
4. Il server invia al thread-servlet la richiesta pervenutagli dal client
5. Il thread-servlet costruisce e imposta la risposta e la inoltra al server
6. Il server invia la risposta al client

Il servlet container più diffuso e utilizzato è **tomcat**.

## Ciclo di vita di una servlet

- `init()`: al momento del caricamento in memoria il container invoca il metodo `init()` che inizializza la servlet e le variabili.
- `service()`: questo metodo serve per ricevere e rispondere alle richieste dei client.
- `destroy()`: per terminare l’esecuzione di una servlet viene invocato questo metodo, solitamente solo quando termina l’esecuzione del Web server.

**Strutturazione delle directory:**

- 📂 webapps → 📂 nome_progetto:
    - file *.html, *.jsp, ecc.
    - 📂 WEB-INF
        - 📂 classes
            - classi java compilate in file *.class
        - 📂 lib
            - eventuali file di libreria *.jar
        - web.xml

Il file **web.xml**, chiamato anche *Deployment descriptor*, serve per configurare l’applicazione Web in modo che Tomcat possa gestire le richieste da parte dei client.

Vengono definiti: 

- il nome della classe che definisce la servlet
- i percorsi che causano l’invocazione della servlet
- una serie di parametri di configurazione

**Esempio web.xml**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<web-app>
    <servlet>
        <servlet-name>NomeServlet</servlet-name>
        <servlet-class>dev.giuliopime.NomeServlet</servlet-class>
    </servlet>

    <servlet-mapping>
        <servlet-name>NomeServlet</servlet-name>
        <url-pattern>/percorso</url-pattern>
    </servlet-mapping>
</web-app>
```

## Vantaggi delle servlet

- **Efficienza**: vengono caricate una sola volta.
- **Portabilità**: Java è facilmente portabile su ogni piattaforma
- **Persistenza**: quando una servlet viene caricata rimane in memoria
- **Gestione delle sessioni**: con le servlet è possibile memorizzare i dati delle sessioni

## Svantaggi delle servlet

- Con le servlet si *mescola* la logica dell’applicazione con la presentazione
- A volte risulta difficoltoso dover inglobare all’interno del codice Java il codice HTML
- Ogni modifica del codice richiede una ricompilazione esplicita e il riavvio dell’applicazione o del server

# Connessione a database tramite JDBC

**JDBC** racchiude una serie di classi per poter accedere alle basi di dati con metodi e schemi di funzionamento molto intuitivi.

JDBC è un’interfaccia, cioè uno “strato di programmazione” che si interpone tra il codice Java e i database.

Per prima cosa è necessario caricare il driver idoneo per l’utilizzo del particolare database che si intende utilizzare.

Come secondo passo si apre una connessione verso un database sfruttando il driver caricato:

`jdbc:mysql://[hostname][:port]/[dbname]`

Per interagire con il DBMS attraverso delle query viene creato un oggetto `java.sql.Statement`.

I risultati ottenuti vengono salvati in un oggetto di tipo `ResultSet`.

Oltre alla stringa di connessione dovremo fornire username e password per accedere al database.

## **JSP**

La tecnologia JSP (*Java Server Pages*) è basata su Java e permette lo sviluppo di applicazioni web con contenuti dinamici senza dover essere legati a un ambiente in particolare. Una pagina JSP è rappresentata da codice HTML con incapsulate al suo interno delle direttive JSP, racchiuse in un particolare tag `<%...%>`, rappresentanti codice Java.

La programmazione di pagine JSP è una fusione tra la programmazione dinamica in linguaggio PHP e quella effettuata mediante la realizzazione delle servlet. Con la tecnologia JSP è possibile utilizzare strumenti come i JavaBean per spostare tutta la logica al loro interno in modo da ridurre al minimo l’utilizzo delle scriptlet <%...%>.

# Web Service

## **Definizione**

Un  **Web service** è un componente applicativo largamente utilizzato. Possiamo definirlo come un sistema software in grado di mettersi al servizio di una applicazione comunicando su di una medesima rete tramite il protocollo **HTTP**. Un Web service consente quindi alle applicazioni che vi si vogliono collegare di usufruire delle funzioni che mette a disposizione. Questa tecnologia si basa su due caratteristiche fondamentali:

- **multipiattaforma**: client e server non devono avere le stesse configurazioni per comunicare fra di loro. Il servizio web fornisce quindi un terreno comune;
- **condivisione**: nella maggior parte dei casi, un servizio web non è disponibile solo per un unico client ma è progettato per avere l’accesso di più client contemporaneamente.

Un Web service viene **indirizzato tramite un URI** (*Uniform Resource Identifier*).
Un aspetto importante è rappresentato dal linguaggio **WSDL** (*Web Service Description Language*). I servizi web dispongono di un file in WSDL che descrive il servizio in modo più dettagliato.

La comunicazione avviene attraverso diversi protocolli e architetture, come ad esempio SOAP o REST.

## **SOAP**

SOAP (*Simple Object Access Protocol*) **è un protocollo standard** ideato inizialmente per consentire la comunicazione tra applicazioni realizzate con linguaggi e piattaforme diverse. Trattandosi di un protocollo, richiede l’integrazione di regole che ne aumentano la complessità e il carico di gestione sul sistema, comportando tempi di caricamento delle pagine più lunghi. Una richiesta di dati inviata a un API SOAP può essere gestita tramite uno dei protocolli a livello applicativo (HTTP, SMTP, TCP, ecc.) Una volta ricevuta la richiesta, i **messaggi** SOAP di ritorno devono essere restituiti come documenti in **formato XML**.

## **REST**

REST (*Representational State Transfer*) è un insieme di principi architettonici incentrati sulle esigenze di ottimizzazione di servizi web e applicazioni mobili. Trattandosi sostanzialmente di linee guida o raccomandazioni, la loro implementazione è lasciata agli sviluppatori. In genere, una richiesta di dati inviata ad una API REST avviene tramite il protocollo HTTP. Una volta ricevuta la richiesta, le API progettate per REST (chiamate API o servizi web RESTful) possono restituire i messaggi in numerosi formati: HTML, XML, testo semplice o JSON.

---

# 🌐 Sistemi e Reti

# VLAN

Lo standard **802.1Q** definisce le specifiche che permettono di definire **più reti locali virtuali (VLAN)** distinte, utilizzando una **stessa infrastruttura fisica**.

Ciascuna VLAN si comporta come se fosse una rete locale **separata dalle altre:**

- I pacchetti broadcast sono **confinati** all’interno della VLAN
- La **comunicazione a livello 2** è confinata all’interno della VLAN
- La connettività tra diverse VLAN può essere realizzata **solo a livello 3**, attraverso routing.

## Scopo

L’utilizzo delle Virtual Lan permette di realizzare:

- **Risparmio**: non è necessario realizzare una nuova infrastruttura di rete locale con apparti e linee dedicate per creare una nuova LAN parallela entro lo stesso ambiente della LAN preesistente;
- **Aumento di prestazioni:** il confinamento del traffico broadcast permette di evitare la propagazione di frame verso destinazioni che non hanno necessità di riceverlo;
- **Aumento della sicurezza**: una utenza connessa ad una VLAN non ha modo di vedere il traffico interno alle altre VLAN
- **Flessibilità**: lo spostamento fisico di una utenza all’interno dei locali raggiunti dalla infrastruttura di rete può essere realizzato senza modifiche della topologia fisica, ma logicamente attraverso l’opportuna riconfigurazione degli apparati di rete.

## Requisiti

Per realizzare una VLAN è necessario che gli switch di rete siano capaci di **distinguere** le diverse VLAN.

Gli apparati devono **osservare lo standard 802.1Q**

Vi sono diversi modi per realizzare una VLAN:

- **Port based (**o private VLAN);
- **Tagged** (802.1Q).

In ogni caso dentro lo switch devono essere **definite le VLAN**, con nome e numero identificativo per distinguerle una dall’altra.

## Funzioni dello Switch in 802.1Q

Esistono tre funzioni che gli switch devono saper svolgere:

1. **Ingress**: lo switch deve essere in grado di capire **a quale VLAN appartiene** un frame in ingresso.
2. **Forwarding:** lo switch deve conoscere verso quale porta inoltrare il frame, **in funzione** della VLAN di appartenenza.
3. **Egress**: lo switch deve poter trasmettere il frame in uscita in modo che la sua **appartenenza** alla VLAN venga **correttamente interpretata** da altri switch.

## Port based VLAN (Untagged)

Prevede **l’assegnazione statica** di ciascuna porta ad una VLAN.

> Porte diverse possono essere assegnate a **VLAN differenti.**
> 

Di fatto in questo modo si **partiziona** uno switch in due o più switch logici.

Le VLAN untagget non richiedono l’osservanza dello standard 802.1Q, ma solo che lo switch ne supporti la configurabilità.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2023.png)

## VLAN 802.1Q (Tagged)

Lo standard viene utilizzato per poter **condividere** lo stesso link fisico **tra VLAN differenti.**

Per poter fare ciò lo switch deve poter **distinguere** la VLAN di appartenenza **del frame in arrivo.**

Lo standard definisce una **modifica del formato** del frame ethernet aggiungendo **4 byte** che trasportano le informazioni sulla VLAN.

Poiché tutti gli switch **devono concordare** sulla VLAN di appartenenza di un frame, l’identificativo (**VLAN tag**) della VLAN **deve essere uguale per tutti gli switch.**

Il formato del frame Ethernet secondo lo standard 802.1Q contiene due campi aggiuntivi:

- TPI (**Tag Protocol Identifier**): due bytes di valore **81 00** che identificano il frame come 802.1Q.
- TCI (**Tag Control Information**): due bytes che trasportano le informazioni sulla tag:
    - I primi tre bit indicano l’eventuale livello di priorità del frame
    - Il quarto bit (**CFI**) vale 1 se il frame proviene da una LAN token ring
    - I restanti 12 bit (**VID**) trasportano la **VLAN tag** (da 0 a 4095)
        
        ![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2024.png)
        

Il campo **TPI** ha un valore che non è utilizzato come *protocol type* nei frame Ethernet ordinari, questo permette di **identificare** immediatamente se un frame è di tipo 802.1Q e una scheda Ethernet non conforme a questo standard **scarterebbe** il frame.

Il frame così costituito rappresenta una violazione dello standard Ethernet poiché eccede la dimensione massima e tutti gli switch che osservano questo standard devono poter accettare frame con 2 byte in più.

## Porte Tagged ed Untagged

In uno switch 802.1Q **tutte le porte** devono essere associate ad **una o più** VLAN.

> Se la porta è associata ad una VLAN “port based” (untagged) i frame ricevuti da quella porta **non trasporteranno TAG**, né dovranno trasportala i frame in uscita
> 

<aside>
💡 Il link attestato su tali porte si dice **Access link**

</aside>

> In caso contrario la porta sarà associata ad una o più VLAN in **modalità Tagged**, ed i frame trasporteranno le informazioni di tag
> 

<aside>
💡 Il link associato a tali porte si dice **Trunk link**

</aside>

La VLAN di appartenenza del frame è definito dal valore inserito nella TAG.

## Porte ibride

Lo standard richiede che una porta **possa** essere associata ad **una VLAN** in modalità **untagged** e ad **altre VLAN** in modalità **tagged.**

<aside>
💡 Il link su tali porte si dice **Hybrid link**

</aside>

> Se non ha la TAG il frame appartiene alla VLAN **a cui la porta è associata in modalità untagged**
> 

> Se ha la TAG la VLAN è **definita dal valore** di tale TAG.
> 

*La VLAN a cui la porta è associata in modalità untagged viene anche detta **PVID (**Private Vlan ID).*

## Funzioni in 802.1Q

- **Ingress**: quando viene ricevuto un frame lo switch **deve identificare la VLAN di appartenenza**:
    - Se il frame è **untagged** la VLAN è identificata con **la VLAN a cui la porta è associata**
        
        > Se il link è di tipo **trunk** il frame viene scartato.
        > 
    - Se il frame è **tagged,** la VLAN viene identificata dalla **TAG.**
        
        > Se il link è **access,** o la porta non è associata in modalità tagged alla VLAN indicata nella TAG, il frame viene scartato.
        > 
- **Forwarding**: una volta identificata la VLAN di appartenenza vengono applicate le regole di forwarding e viene identificata la porta di uscita
    - La, o le, porte in uscita **devono essere associate** alla VLAN di appartenenza del frame.
- **Egress**: questa funzione può richiedere la modifica del frame ricevuto:
    - Se il frame in ingresso è 802.1Q e la porta in uscita è associata alla VLAN di appartenenza in modalità tagged, il frame non subisce modifiche;
    - Se il frame in ingresso è untagged e la porta in uscita è associata alla VLAN di appartenenza in modalità untagged, il frame non subisce modifiche;
    - Se il frame in ingresso è **802.1Q** e la porta di uscita è **untagged**, la TAG viene **rimossa;**
    - Se il frame in ingresso è **802.3** e la porta di uscita è **tagged**, la TAG viene **inserita.**

*Negli ultimi due casi lo switch deve **ricalcolare** il valore del **CRC.***

## Coesistenza con apparati non 802.1Q

Gli apparati che **non osservano** lo standard 802.1Q saranno connessi su porte dello switch associate esclusivamente in modalità **untagged**.

Questo garantisce che ogni frame ricevuto **sarà associato ad UNA VLAN** e nessun frame di tipo 802.1Q **sarà inoltrato verso l’apparato**, in quanto la TAG deve essere rimossa.

Questo permette di inserire in una rete locale apparati 802.1Q senza dover **sostituire l’hardware preesistente.**

![Esempio topologia 802.1Q](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2025.png)

Esempio topologia 802.1Q

Nell’esempio il link tra i due switch è di tipo **trunk** e trasporta frame di entrambe le VLAN.
Gli switch **devono inserire** la tag per trasmettere i frame verso l’altro switch.
Gli switch **dovranno rimuovere** la tag prima di inoltrare i frame verso la stazione di destinazione.

Nessun frame appartenente ad una VLAN può raggiungere stazioni connesse su porte associate ad un’altra VLAN.

*Per realizzare una comunicazione tra stazioni appartenenti a VLAN differenti i dati devono essere inoltrati **a livello di rete** da un router*.

## Protocol based VLAN

L’assegnazione di un frame ad una VLAN può essere effettuata **dinamicamente,** in funzione di diversi parametri.

> Le regole di assegnazione **devono essere configurate** negli switch opportunamente, non tutti gli switch 802.1Q sono in grado di effettuare l’assegnazione dinamica.
> 

I parametri possono essere:

- Indirizzo IP del mittente
- Protocol type del frame Ethernet
- Indirizzo Ethernet della stazione mittente.

Un esempio tipico è la assegnazione **definita dal MAC address**: nessuna stazione può accedere ad una VLAN se il suo MAC non è registrato dall’amministratore della rete, **indipendentemente dalla porta a cui si connette.**

## Default VLAN

Gli switch 802.1Q vengono venduti con una VLAN **predefinita**, detta **default VLAN.**

Alla default VLAN è assegnata la TAG **1.**

Tutte le porte appartengono alla default VLAN in **modalità untagged** (PVID = 1)

> Poichè una porta non può essere associata a più di una VLAN in modalità untagged, per modificare il PVID di una porta si deve prima rimuovere l’associazione della porta in modalità untagged preesistente.
> 

## Esempi di comunicazione tra VLAN con router

![Per ogni vlan collegata si collega un cavo al router](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2026.png)

Per ogni vlan collegata si collega un cavo al router

![Si utilizza un unico cavo in modalità trunk (Router - on - a - stick)](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2027.png)

Si utilizza un unico cavo in modalità trunk (Router - on - a - stick)

# VLAN - Trunking Protocol (VTP)

La configurazione delle VLAN deve essere effettuata per ogni switch presente nella rete LAN.

Nel caso di LAN di dimensioni elevate:

- Complessità di gestione;
- Possibilità di errori nella configurazione.

Il protocollo **Vlan Trunking Protocol (VTP)** consente di configurare le VLAN su solo uno switch, che si occupa poi di distribuire le VLAN a tutti gli switch della rete.

Il protocollo VTP **riduce** la configurazione **manuale** degli switch.

Nel VTP troviamo:

- VTP domain;
- VTP Server;
- VTP Client;
- VTP Transparent;
- VTP Advertisement;
- Trunk.

Il comando che consente di valutare la configurazione VTP di uno switch è

`Switch# ***show vtp status***`

I parametri da configurare sono:

- VTP version;
- VTP domain;
- VTP mode;
- Config Revision;
- VLANs.

## VTP Version - VTP mode

Esistono due versioni del protocollo VTP: 1, 2.

La versione di default è la 1.

Il parametro VTP mode può assumere tre diversi valori, a seconda del ruolo dello switch:

- Server
- Client
- Transparent

Di default lo switch lavora come Server.

## Vtp Domain Name

E’ il nome del dominio VTP cui lo switch appartiene, un VTP domain è un insieme di switch che si scambiano VTP advertisement per la distribuzione delle VLAN.

Uno switch può possedere un solo dominio VTP alla volta.

Il dominio si propaga dal VTP server a tutti i VTP client.

> Di default è *`Null`.*
> 

## VTP Advertisement

Un messaggio VTP è inviato ogni qual volta bisogna propagare le VLAN.

Esistono tre tipi di Advertisement:

1. **Summary**: contengono il **VTP Domain Name** ed il **Config Revision**. Sono inviate ogni 5 minuti ed hanno lo scopo di informare i vicini del corrente VTP Config Revision. Vengono inviati anche subito dopo una modifica.
2. **Subset**: contengono informazioni sulle VLAN (inserimento, cancellazione, modifica).
3. **Request**: inviate ad un VTP server per richiedere l’invio di un messaggio **Summary** e di eventuali messaggi **subset.**

## VTP Config Revision

E’ un **contatore** che viene incrementato ogni volta che si verifica una modifica relativa al VTP: Vlan aggiunta o rimossa.

Inizialmente è impostato a zero.

Consente agli switch di determinare se le informazioni memorizzate sono aggiornate o meno.

## Configurazione VTP Server

```json
// Configurare la modalità server e il VTP Domain Name

Switch(config)# vtp mode server

Switch(config)# vtp domain nome

//Controllare ed eventualmente configurare la versione del protocollo VTP e la password

Switch(config)# vtp version

//configurare le VLAN (E le porte TRUNK)

Switch(config)# show vtp statu

//Verificare che lo switch abbia la configurazione di default

// abilitare modalità Client

Switch(config)# vtp mode client

//configurare le porte di access
```

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2028.png)

---

# Tecniche di crittografia

> La crittografia è nota fin dall’antichità e si è sviluppata nel corso del tempo, soprattutto in ambito militare.
> 

La **codifica** e la **decodifica** sono eseguite da uno o più **algoritmi crittografici**, che utilizzano:

- Una o più funzioni **matematiche**;
- Una o più **chiavi** per operazioni di cifratura e decifratura.

## Elementi di crittografia

- **Crittografia:** procedimento di cifratura e decifratura dei messaggi basato su funzioni parametriche;
- **Testo in chiaro:** messaggio originario;
- **Algoritmo di cifratura:** effettua sostituzioni e trasformazioni sul testo in chiaro;
- **Algoritmo di decifratura:** effettua il lavoro inverso dell’algoritmo di cifratura;
- **Chiave**: parametro dell’algoritmo di cifratura o decifratura.

## Classificazione dei sistemi crittografici

I sistemi crittografici possono essere distinti in base a:

- Tipo di operazioni usate per trasformare il testo in chiaro in testo cifrato:
    - **Sostituzione**: ogni elemento del testo in chiaro è trasformato in un altro elemento;
    - **Trasposizione**: gli elementi del testo in chiaro sono riorganizzati.
- Numero di chiavi (distinte) utilizzate:
    - **Chiave singola:** crittografia a chiave simmetrica (o chiave segreta), le chiavi del mittente e del destinatario sono identiche;
    - **Due chiavi**: crittografia a chiave asimmetrica (o a chiave pubblica), la chiave di cifratura è pubblica, la chiave di decifratura è privata.
- Il modo in cui il testo in chiaro è elaborato:
    - **Cifrario a blocchi:** elabora in blocchi di dimensioni fissa;
    - **Cifrario a flusso:** elabora senza una lunghezza predefinita.

## Cifrari a sostituzione

Le tecniche di sostituzione sostituiscono le lettere del testo in chiaro con altre lettere (o numeri, simboli, ecc..).

Una della più semplici e famose è la **cifratura di Cesare.**

## Cifrari a trasposizione

Le lettere del testo in chiaro non cambiano (come nella sostituzione) ma ne viene alterata la posizione.

Il testo cifrato è quindi una permutazione del testo in chiaro.

La chiave è la permutazione stessa, un attacco a forza bruta dovrebbe quindi tentare tutte le permutazioni possibili (ovvero n!, n lunghezza del messaggio).

## Crittoanalisi

Opposte alla crittografia si sono sviluppate tecniche di **crittoanalisi** con lo scopo di analizzare e cercare di violare le comunicazioni cifrate: ovvero **decifrare il testo senza conoscere la chiave.**

Esistono due modi:

- **Attacchi a forza bruta:** si prova ogni chiave possibile, fino a trovare quella corretta.
- **Analisi crittografica:** si sfruttano informazioni sull’algoritmo, le caratteristiche dei testi in chiaro o l’analisi di coppie note di testi in chiaro/testo cifrato.

Un sistema di cifratura è **computazionalmente sicuro** se il testo cifrato soddisfa uno dei seguenti criteri:

- Il costo per rendere inefficace il cifrario supera il valore dell’informazioni cifrata;
- Il tempo richiesto per rendere inefficace il cifrario supera l’arco temporale in cui l’informazione è utile.

Esistono due tipi di sicurezza:

- Sicurezza **incondizionata**: è impossibile decifrare il testo senza sapere la chiave, indipendentemente dal tempo e dalla quantità di dati disponibili;
- Sicurezza **computazionale**: come abbiamo visto prima,
    - Il costo della violazione supera il valore delle informazioni crittografate;
    - Il tempo di violazione supera la vita utile delle informazioni crittografate.

---

Esistono due tipi principali di crittografia: 

- **Simmetrica**
- **Asimmetrica**

## Crittografia simmetrica

Usa **una sola chiave** per cifrare e decifrare, mittente e destinatario usano la **stessa chiave**.

Esiste però il problema della distribuzione delle chiavi.

![Esempio crittografia Simmetrica](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2029.png)

Esempio crittografia Simmetrica

Un esempio di crittografia simmetrica è il doppio operatore **XOR**.

### Svantaggi 👎🏼

- Difficoltà nel mantenere la chiave K segreta;
- La segretezza dipende dai possessori di K;
- Per N conoscenti bisognerebbe avere N chiavi distinte;
- Difficoltà per la distribuzione sicura della chiave K, ovvero dello scambio.

## La crittografia Asimmetrica

Nasce nel 1975 ed è chiamata anche “**crittografia a chiave pubblica**”.

Risolve il problema della **distribuzione sicura delle chiavi** poichè utilizza una coppia di chiavi.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2030.png)

Le due chiavi sono **correlate MATEMATICAMENTE:** i messaggi codificati con la chiave pubblica possono essere decodificati solo con la chiave privata e viceversa.

Anche conoscendo la chiave pubblica **non è possibile** risalire alla corrispondente chiave private se non con calcoli che richiedono un tempo molto elevato.

La coppia di chiavi viene generata da un **software**.

Ogni persona che vuole ricevere i messaggi cifrati deve fornirsi di una coppia di chiavi:

- La chiave **privata** mantenuta segreta;
- La chiave **pubblica** viene distribuita liberamente a tutte le persone con cui si vuole comunicare.

I mittenti devono così conoscere solamente la chiave pubblica del destinatario e la chiave privata è conservata solamente dal destinatario, risolvendo il problema dello scambio delle chiavi.

---

## Firma digitale

<aside>
🔑 La firma digitale può essere considerata come l’equivalente elettronico della firma autografa posta su carta.

</aside>

Essa consente di garantire la certezza che quel documento appartiene al firmatario.
Il documento in formato digitale sottoscritto con firma digitale ha perfetta validità legale.

La firma digitale garantisce:

- **Integrità:** assicura che il documento digitale non abbia subito modifiche successive alla sottoscrizione;
- **Autenticità:** garantisce l’identità del firmatario;
- **Non ripudio**: impedisce al sottoscrittore di negare la paternità del documento, dato che la firma gli attribuisce piena validità legale.

Per generare una firma digitale è necessario utilizzare una coppia di chiavi digitali asimmetriche attribuite in maniera univoca ad un soggetto detto titolare.

La chiave privata è conosciuta solo dal titolare ed è usata per generare la firma digitale da apporre al documento.

Viceversa la chiave da rendere pubblica è usata per verificare l’autenticità della firma.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2031.png)

> **Hash:** letteralmente significa sminuzzare. E’ un algoritmo che restituisce una sequenza di lunghezza ben definita avendo come input un messaggio di lunghezza qualsiasi
> 

> **Finger-print:** letteralmente significa impronta digitale. E’ un documento prodotto dall’algoritmo di hash a partire da quello originale. Documenti diversi elaborati dall’algoritmo di hash producono una finger-print diversa.
> 
1. Il primo passo consiste nel generare, con l’**hash**, un “riassunto” del documento originale. La modifica al contenuto del messaggio porta ad avere una diversa impronta - digitale.
2. L’impronta digitale viene crittografata con la chiave privata del mittente, ottenendo la “firma digitale”.
3. La firma digitale viene allegata al documento originale, il messaggio completo può essere inviato al destinatario dopo averlo crittografato con la chiave pubblica del destinatario.
4. Il destinatario decripta il messaggio ottenendo il documento orginale e la firma.
5. Il destinatario, utilizzando la chiave pubblica del mittente, ricava la **finger - print.**
6. A questo punto sarà sufficiente confrontare questo finger-print con quello che egli calcolerà in modo autonomo.
    
    Se i due finger print corrispondono egli sarà sicuro che:
    
    1. Il messaggio è integro.
    2. Chi ha spedito il messaggio è veramente chi dice di essere;
    3. Il mittente non può ripudiare il messaggio.

Firmare un documento elettronico è un’attività semplice e veloce, per eseguirla è necessario essere dotati di:

- Dispositivo di generazioni delle firme (smart cad o pen drive);
- Lettore di smart card/pen drive;
- Software di verifica e firma.

---

## Certificati

Il certificato di sottoscrizione rappresenta l’elemento chiave della firma digitale; non è altro che un file rilasciato dall’ente certificatore contenente tutti i dati identificativi del titolare.

L’impiego della firma digitale permette di migliorare i rapporti tra Pubbliche Amministrazioni, cittadini e imprese, riducendo notevolmente la gestione in forma cartacea dei documenti, proprio come indicato da **AGID** (Agenzia per l’Italia Digitale).

L’agenzia si occupa di:

- Offrire **l’elenco di certificatori accreditati** a cui si può richiedere la firma digitale;
- Sottoscrivere una lista dei certificati delle chiavi di certificazione;
- Definire le linee guide per la vigilanza sui gestori qualificati;
- **Autorizza i certificatori** a svolgere la propria attività conferendogli il ruolo di “Certificatori accreditati”;
- effettua **vigilanza** sui certificatori accreditati.

Esiste però la problematica di “mascheramento”, ovvero: siamo certi noi che il certificato che riceviamo sia effettivamente del mittente? e non sia di qualcuno che si “maschera” come tale?

La soluzione di questo problema viene fatta attivando una particolare procedura per la consegna della chiave pubblica: la chiave viene racchiusa all’interno di un certificato digitale che oltre a essa contiene le informazioni sul mittente.

Questo certificato deve essere a sua volta validato da un ente certificatore (**CA, Certification Autorithy)** che garantisce l’identità del proprietario del certificato firmandone le chiavi pubblica e privata con la propria chiave privata: in questo modo ne rende impossibile per chiunque la manomissione.

Quindi il certificato digitale è un documento informatico contenuto nella smartcard del titolare e firmato digitalmente dal certificatore. I dati contenuti nel certificato sono:

- Dati del proprietario e la chiave pubblica;
- Dati del certificato, tra cui la data di scadenza;
- Dati della **CA**.

Un malintenzionato dovrebbe effettuare le seguenti operazinoi per sostituirsi all’effettivo mittente:

1. Violare la cifratura del CA che protegge le due chiavi;
2. Sostituire le chiavi originale con delle chiavi fasulle;
3. Ricodificare il tutto con la chiave privata della **CA.**

> Le pratiche relative alla identificazione dell’utente prima della emissione del certificato vengono fatte dalla **Registration Authority** che, in base alla tipologia del soggetto, svolge le necessarie indagini e attiva le relative procedure per l’identificazione certa del richiedente.
> 

**Registration Authority** e **Certification Authority** sono enti pubblici o privati **accreditati**.

Un **certificato digitale** può avere diversi formati:

- Chiavi **PGP/GPG;**
- Certificati **X.509;**

<aside>
💡 La differenza sostanziale tra questi due è che è possibile creare il proprio certificato PGP/GPG in modo autonomo e in pochissimi istanti, mentre per X.509 è necessario rivolgersi a un ente addetto.

</aside>

### Richiedere un certificato digitale

1. **Generazione della coppia di chiavi asimmetriche da utilizzare per cifrare le comunicazioni:** le comunicazioni tra CA e richiedente devono essere protette e quindi viene generata una coppia di chiavi dal CA;
2. **Il richiedente comunica informazioni circa la propria identità al CA;**
3. **La Registration Authority inizia la verifica dei dati ricevuti;**
4. Se i controlli vanno a buon fine, la **Certification Authority genera il certificato e lo firma digitalmente** con la propria chiave privata: viene firmato perchè i dati contenuti non vengano modificati.
5. **Il certificato firmato viene inviato al richiedente** che provvederà a installarlo sul proprio server.

Esistono numerosi programmi che consentono di **criptare** file:

**Gestione file:**

- Kleopatra: unisce alla crittografia la gestione dei certificati;
- FileVault: crea file auto-estraenti e auto-decifranti.

**Disco fisso:**

- VeraCrypt: crea dischi fissi cifrati.

**Dati:**

- Data Scramble: trasforma i dati in un’immagine bitmap con algoritmo MD5.

---

# Algoritmi di cifratura

# → DES

1977 → Reso pubblico

1998 → Viene rotto

### Tipologia (Simmetrico & A Blocchi)

- **Simmetrico**: cifratura e decifrazione con la stessa chiave
- **A blocchi**: messaggio suddiviso in blocchi cifrati indipendentemente

### Proprietà

- **Diffusione**: altera la struttura del testo in chiaro spargendo i caratteri su tutto il testo cifrato
- **Confusione**: combinare in modo complesso il messaggio e la chiave

### Algoritmo

![DES.png](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/DES.png)

# 3-DES

Introdotto → 1999

Consiste in 3 passi di cifratura DES consecutivi con chiavi diverse, per un totale di 168 bit di chiave (56 x 3, le chiavi sono da 64 bit ma ne hanno 8 di parità).

In ordine avviene:
cifratura → decifrazione → cifratura (per la codifica)
decifrazione → cifratura → decifrazione (per la decodifica)

### 3 varianti a seconda delle chiavi

- tre chiavi diverse
- k1 e k3 uguali: sicurezza di 112 bit
- tre chiavi uguali: usata per garantire la compatibilità con il DES standard (sicurezza 56 bit)

---

# → IDEA

IDEA utilizza chiavi da 128 bit che al primo passo vengono suddivide in 8 blocchi da 16 bit ciascuno.

Le prime 6 chiavi generate vengono utilizzate direttamente nel primo passo dell’algoritmo; nei passi successivi invece la chiave usata al passo precedente viene shiftata ciclicamente di 25 posizioni a sinistra, per poi essere suddivisa nuovamente in 8 blocchi da 16 bit.

> Nell’ultimo passo vengono utilizzati soltanto i primi 4 blocchi ottenuti dalla chiave shiftata.
> 

Il messaggio da cifrare viene suddiviso in blocchi da 64 bit e, ad ogni passo, il blocco da 64 bit viene suddiviso in 4 blocchi da 16 bit, chiamati A, B, C, D:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2032.png)

Ad ogni passo **i** (1≤ **i** ≤ 8), avvengono le seguenti operazioni:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2033.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2034.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2035.png)

I passaggi visti fino ad ora vengono eseguiti 8 volte.

Arrivati all’ultimo round, il 9°, vengono eseguiti meno passaggi:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2036.png)

Una volta arrivati al 9° round l’algoritmo è terminato e basterà unire **G1, G2, G3, G4** per ottenere il testo cifrato da inviare.

Lo schema completo di **IDEA** è il seguente: 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2037.png)

### Decifrazione

La decifrazione del messaggio segue lo stesso identico schema, ma le chiavi utilizzate sono invertite rispetto a **MUL** e **ADD.**

### Vantaggi

- La forza di **IDEA** sta nella segretezza della chiave e che si ha un range di possibili chiavi pari a 2^128.
- L’algoritmo è abbastanza facile da applicare ed è molto veloce; si potrebbe anche rendere più veloce eseguendo solamente 4 round al posto di 9, dato che è stato dimostrato che diventa impossibile da forzare dopo il quarto passo.
- Può essere implementato sia via software che hardware, con semplici componenti che lavorano a 16 bit.

---

# → RSA

<aside>
💡 **Idea base:** Dati due numeri primi **p** e **q** è facile calcolare il prodotto 
**n= p*q**, mentre è molto difficile calcolare la **fattorizzazione** di **n.**

</aside>

 E’ un algoritmo di cifratura **Asimmetrico**.

E’ composto da:

- Chiave **pubblica** di 2 numeri → K (pub) = (pub, n);
- Chiave **privata** di 2 numeri → K (pri) = (pri, n);

Per **cifrare un messaggio**:

> c = **m^pub mod n**
> 

dove m è un carattere o un blocco del messaggio trasformato in binario

Per **decifrare un messaggio:**

> m = **c^pri mod n**
> 

### Come si ricavano le chiavi K(pub) e K(pri)?

1. Sceglio due numeri **primi** **a** e **b** molto grandi e calcolo 
    
    n = a * b → **secondo numero delle chiavi**
    
2. Determino **z** = **(a-1)*(b-1)**
    
    e sceglo le chiavi:
    
    1. *Pri →* non deve avere fattori comuni con **z;**
    2. *Pub →* deve soddisfare l’equazione **(pub*pri) mod z = 1**

---

## → Diffie - Hellman

Prendiamo in esempio Alice e Bob, entrambi conoscono due numeri, **g** e **p** pubblici e **p** è un **numero primo**.

Inoltre Alice conosce un numero segreto **‘a’** e Bob conosce un numero segreto **‘b’.**

→ Alice calcola **A = g^a mod p** e lo comunica a Bob;

→ Bob calcola **B = g^b mod p** e lo comunica ad Alice;

→ Alice calcola **K = B^a mod p = [g^b mod p]^a mod p = g^ab mod p;**

→ Bob calcola **K = A^b mod p = [g^a mod p]^b mod p = g^ab mod p;**

Così facendo Alice e Bob hanno condiviso un numero segreto (**K**) senza mai comunicarlo esplicitamente.

Chiunque può osservare A, B, g ep ma queste informazioni non sono sufficienti per ricavare il numero K.

Infatti K è calcolabile solo conoscendo **a** o **b**, che tuttavia sono segreti e non vengono mai comunicati.

Ricavare **a** da **A** (o b da B) significa risolvere un logaritmo discreto, il che è computazionalmente difficile.

> Se questo numero **K** rappresenta la chiave di un algoritmo di cifratura simmetrica si è trovato un modo per condividere la chiave senza la necessità di un canale di comunicazione sicuro.
> 

Il problema però è che Alice e Bob non hanno potuto scegliere il valore di tale numero, ma è casuale.

Perciò l’algoritmo di **Diffie - Hellman** non è un algoritmo di **crittografia** ma è esclusivamente un algoritmo di **scambio delle chiavi**.

---

## → Crittografia Ibrida

Essendo che:

- Cifrari **Simmetrici** sono veloci ma hanno un numero di chiavi molto elevato (e considerato anche il problema dello scambio sicuro delle chiavi).
- Cifrari **Asimmetrici** sono lenti ma più efficienti.

Allora si è pensato all’utilizzo di un cifrario **ibrido:**

→ Cifrario **Simmetrico** per la comunicazione;

→ Cifrario **Asimmetrico** per lo scambio di chiavi **k**.

In particolare:

<aside>
💡 Il messaggio viene crittografato con un algoritmo **a chiave simmetrica**, in cui la **chiave** è generata **casualmente.**
La **chiave casuale** generata per cifrare il messaggio viene **crittografata** mediante la chiave pubblica del destinatario.

</aside>

Il destinatario, tramite la sua chiave privata, decifra la chiave **simmetrica** utilizzata per codificare il messaggio.

Tramite questa chiave decodificata, decodifica il messaggio stesso.

---

## → AES

**A**dvanced **E**ncryption **S**tandard

L’**AES** è un cifrario a blocchi.

Utilizza blocchi da 128 bit e può usare chiavi da 128, 192 e 256 bit.

La lunghezza della chiave influisce sulla **schedulazione** delle chiavi e sul **numero** di round, però **non** influisce sulla struttura di alto livello di ciascun round.

I 128 bit vengono divisi in 16 byte, per poi essere sistemati all’interno di una tabella 4x4, così come la chiave:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2038.png)

### A - processo di cifratura

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2039.png)

1- **SubBytes:** è una funzione SBOX nella quale tramite righe e colonne il valore iniziale di una cella (ad esempio cella 1,1 contenente il valore 19) viene alterato.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2040.png)

Così per ogni byte all’interno della tabella 4x4.

2- **ShiftRows:** la seconda riga della tabella viene shiftata verso sinistra di 1 byte, la terza riga di 2 bytes e la quarta riga di 3 bytes.

 3- **MixColumns:** ogni cella di ogni colonna viene “modulo moltiplicata” con una matrice predefinita:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2041.png)

4- **AddRoundKey**: viene eseguito lo **XOR** tra ogni colonna della tabella 4x4 ottenuta dai tre passaggi precedenti e ogni colonna della tabella 4x4 contenente la chiave:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2042.png)

Così da ottenere:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2043.png)

> Queste trasformazioni vengono eseguite per 9 round consecutivi, l’ultimo round, quello finale, non include il **MixColumns**.
> 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2044.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2045.png)

### B - Key Schedule

La chiave viene divisa in 11 sotto - chiavi usate nel round iniziale, nei 9 round centrali e nel round finale.

La chiave può essere vista come un array di 32-bit words (colonne) numerate da 0 fino a 43, dove le prime 4 sono riempite con la chiave ricevuta.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2046.png)

Le colonne multipli di 4 (W4, W8, …, W40), quindi le prime di ogni tabella, sono calcolate applicato **RotWord** e **SubBytes** (visto prima) alla colonna precedente:

> **RotWord** consiste nello spostare il primo byte da sopra a sotto.
> 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2047.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2048.png)

Successivamente viene effettuato uno **XOR** tra il risultato ottenuto dalla **SBOX** e la “word” situata in 4 posizioni prima e una costante chiamata **Rcon.**

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2049.png)

Per quanto riguarda le restanti colonne invece basterà calcolare tramite uno **XOR** il risultato tra la colonna precedente e quella posizionata in 4 posizioni prima.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2050.png)

---

## Le funzioni HASH

<aside>
💡 Una **funzione hash** trasforma un messaggio di lunghezza variabile in un output di lunghezza fissa (chiamato **hash** o **digest** del messaggio originale).

</aside>

Per soddisfare le condizioni di sicurezza, gli algoritmi per le funzioni hash devono seguire queste proprietà:

- Devono essere **coerenti** → a input uguali corrispondono output uguali;
- Devono essere **casuali** → impedire l’interpretazione accidentale del messaggio originale;
- Devono essere **univoci** → la probabilità che due messaggi diversi generino lo stesso hash deve essere **virtualmente** nulla;
- Devono essere **non invertibili** → non deve essere possibile risalire al messaggio originale dall’output.

> Le funzioni hash non invertibili vengono normalmente utilizzate per assegnare un’**impronta digitale** a un messaggio o a un file.
> 

Le funzioni hash non invertibili vengono utilizzate per accertarsi che nessuno in fase di trasporto sia intervenuto sul contenuto del messaggio.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2051.png)

Il problema in questo caso è che non c’è modo di proteggere l’impronta da eventuali intrusi.

E’ possibile infatti che qualcuno interferisca impersonando il mittente o il destinatario nelle comunicazioni sicure.

Perciò le funzioni hash **vanno combinate** con sistemi a chiave pubblica per l’assegnazione di firme digitali.

Tra le funzioni hash più comuni troviamo:

→ L’algoritmo **MD4** (Message digest 4);

→ L’algoritmo **MD5** (Message digest 5);

→ L’algoritmo **SHA** (Secure Hash Algorithm).

Gli attuali prodotti per la sicurezza utilizzano principalmente algoritmi MD5 e SHA, entrambi basati sul sistema MD4.

> MD5 elabora l’input a blocchi da 512 bit e produce un output (digest) da 128. 
SHA elabora blocchi da 512 bit e produce un digest da 160 bit.
> 

### → MD5

Il messaggio viene elaborato a blocchi di 512 bit e viene prodotto un **hash** da 128 bit.

Ad ogni iterazione si calcola una funzione che prende in ingresso il blocco corrente del messaggio e il valore dell’hash all’iterazione precedente.

L’hash finale è quello risultante dall’ultima iterazione.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2052.png)

Prima di iniziare l’elaborazione si aggiunge al messaggio un **padding** in modo che la lunghezza totale risulti un multiplo di 512 bit.

In particolare:

→ Si aggiunge un bit a 1 e poi tanti 0 affinchè la lunghezza risulti di 64 bit minore rispetto ad un multiplo di 512.

→ Gli ultimi 64 bit contengono la lunghezza originale del messaggio.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2053.png)

Un’iterazione MD5 è composta da **4 passi,** perciò ogni blocco del messaggio viene elaborato in 4 “round” successivi.

La funzione utilizzata dipende dal round:

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2054.png)

In ogni round la funzione di compressione viene applicata 16 volte.

### → SHA

L’elaborazione eseguita dagli algoritmi SHA è simile a quella MD5, è costituita da quattro fasi: le prime due sono identiche mentre la terza utilizza uno schema a 8 registri (al posto di 4) e nel passo 4 la sequenza di bit viene divisa in blocchi da 512 bit o 1024, a seconda dell’algoritmo.

---

# La sicurezza delle reti

La sicurezza dei sistemi informativi mira a proteggere le informazioni dalle minacce di tipo **umane** e **naturali**.

Le minacce di tipo **umane** possono essere indotte da **interessi personali** e possono essere attacchi **interni** o **esterni**.

Gli **attacchi interni** possono essere condotti da dipendenti o ex dipendenti che conoscono la struttura.

Le minacce **naturali** sono dovute a **eventi naturali** tipo innondazione, incendi, terremoti, ecc..

Per evitare si eseguono misure **preventive** come il posizionamento dei dati in locali adeguati.

Tra gli eventi **intenzionali,** ovvero gli **attacchi** troviamo:

→ **Ip spoofing / Shadow server**: qualcuno si sostituisce ad un host;

→ **Packet sniffing:** si leggono password di accesso o dati riservati;

→ **Connection hijacking**: si inseriscono o modificano i dati durante il loro transito in rete;

→ **Denial of service (DoS) e Distributed DoS (DDoS):** si impedisce il funzionamento di un servizio.

Tra gli eventi **accidentali**, cioè gli errori e i malfunzionamenti, individuiamo:

→ Non adeguatezza degli strumenti;

→ Locale server sensibile alle innondazioni;

→ Errata gestione delle password;

→ Ecc..

Le principali tipologie di minacce sono:

- **Attacchi passivi;**
- **Attacchi attivi.**

### Attacchi passivi

Tra gli attacchi passivi troviamo:

→ Lettura del contenuto, ad esempio medianto lo **sniffing** di pacchetti;

→ Analisi del sistema e del traffico di rete, senza analizzare i contenuti.

### Attacchi attivi

Tra gli attacchi attivi troviamo:

→ **Intercettazione**: mira a intercettare le password per avere accesso al sistema;

→ **Sostituzione di un host**: qualcuno si sostituisce ad un host falsificando l’indirizzo di rete;

→ **Ping flooding;**

→ **SYN attack;**

**→ Distributed Denial of Service (DDoS);**

→ **Phishing:** attraverso spamming di email si attrae un utente su un server pirata;

→ **Intrusione**: accesso non autorizzato a uno o più host.

E’ necessario perciò introdurre delle misure di sicurezza per proteggere sia le informazioni presenti sugli host sia quelle circolanti sulla rete.

Bisogna però effettuare una distinzione tra:

- Sicurezza nella rete;
- Sicurezza sugli host:
    - A livello di sistema operativo
    - A livello di applicazione

I tre “pilastri” della sicurezza sono:

- **Prevenzione**: mediante protezione dei sistemi e delle comunicazioni;
- **Rilevazione**: mediante il monitoraggio e il controllo degli accessi
- **Investigazione**: con l’analisi dei dati, il controllo interno, ecc..

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2055.png)

Per quanto riguarda la **prevenzione** troviamo diverse tecniche, come:

→ **Uso della crittografia**;

→ **Autenticazione degli utenti,** nel dettaglio troviamo:

- Identificazione: risponde alla domanda “Chi sei?”
- Autenticazione: risponde alla domanda “Come mi accerto che sei tu?”
- Autorizzazione: risponde alla domanda “Cosa posso fare?”

→ **Firma elettronica**;

→ **Connessioni TCP sicure mediante SSL;**

→ **Firewall.**

→ **Reti private e reti private virtuali (VPN).**

---

## La sicurezza per i messaggi di posta elettronica

La posta elettronica è il servizio di internet più importante dati che è utilizzato praticamente da tutti coloro che hanno un account.

La posta è lo strumento preferenziale per sferrare attacchi sulla rete dato che il protocollo **SMTP** non offre alcuna garanzia di riservatezza.

Una email può essere esposta ad attacchi mentre “sosta” in buffer temporanei presso **switch, router, gateway e host** intermedi.

> Le specifiche originarie del protocollo SMTP non prevedono nessuna forma di autenticazione.
> 

Nei protocolli **POP3** e **IMAP** che, al contrario di SMTP, prevedono una forma di autenticazione, la comunicazione avviene in chiaro, per cui i pacchetti spediti possono essere intercettati su uno qualsiasi dei computer attraversati. In questo modo è possibile scoprire perfino la stessa password.

La sola cifratura non garantisce una sicurezza adeguata per i messaggi che transitano su internet.

I problemi di sicurezza della posta elettronica sono materialmente difficili da risolvere, si può peroò ridurre il problema usando connessioni protette tramite **SMTP + SSL** e **POP + SSL** e utilizzando tecniche di sicurezza fornite da **PGP** e da **S/MIME.**

---

La posta elettronica viene implementata attraverso la cooperazione di due tipi di sottosistemi:

- Mail User Agent (MUA);
- Mail Transport Agent (MTA).

### MUA

E’ l’interfaccia con il client, è un programma di gestione di posta (Outlook) operativo sul client, che deve:

→ Possedere un’interfaccia utente per l’inserimento, la composizione, la ricezione e la lettura dei messaggi;

→ Conoscere il protocollo per spedire i messaggi (**SMTP**);

→ Conoscere il protocollo **POP3** e **IMAP4;**

→ Conoscere la sintassi di composizione dei messaggi.

### MTA

Funge da ponte tra due MUA, è l’interfaccia con la rete e quindi si iccupa della ricezione e trasmissione dei messaggi.

L’MTA può essere:

→ Un server SMTP che gestisce la spedizione e la ricezione dei messaggi verso e da altri server SMTP;

→ Un server POP3 che gestisce la spedizione dei messaggi al client;

→ Un server IMAP4 che permette la gestione dei messaggi sul server dal client.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2056.png)

Gli obiettivi di una *posta sicura *****sono: 

- **Integrità**: il messaggio non può essere modificato;
- **Autenticazione**: identifica il mittente;
- **Non ripudio**: il mittente non può negare di aver spedito la mail;
- **Riservatezza**: i messaggi non siano leggibili agli intrusi.

## Il protocollo S/MIME

Il protocollo SMTP presenta un limite dal punto di vista della protezione e una sua alternativa è il protocollo S/MIME che fornisce due servizi di protezione:

1. Firme digitali;
2. Crittografia dei messaggi.

Questi due servizi sono alla base della protezione dei messaggi S/MIME in quanto un messaggio può essere **firmato, cifrato** oppure essere sottoposto a **entrambi**.

### Firme digitali

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2057.png)

### Crittografia dei messaggi

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2058.png)

### Interazione delle firme digitali con la crittografia dei messaggi

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2059.png)

Invece per decifrare un messaggio bisognerà: 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2060.png)

### PGP

**P**retty **G**ood **P**rivacy è uno dei più celebri software per la crittografia a chiave pubblica utilizzato soprattuttop er codificare le email.

Obiettivo principale del PGP è quello di aumentare la rapidità della codifica **RSA**.

Con PGP per procedere al criptaggio di un messaggio la prima operazione da effettuare è quella di generare una **session key:** generata in modo estremamente casuale e verrà usata una sola volta per cifrare il messaggio.

Quindi questa viene criptata con la chiave pubblica del destinatario e inviata insieme al messaggio.

Perciò, riassumendo:

1. Mittente genera una chiave;
2. Mittente si procura la chiave pubblica RSA del **destinatario**;
3. Mittente utilizza tale chiave per codificare la chiave generata randomicamente;
4. Mittente cifra il messaggio attraverso l’uso dell’algoritmo simmetrico **IDEA.**

Il destinatario, una volta ricevuto il messaggio, per prima cosa decripta la chiave randomica (**session key**) e lo fa utilizzando la propria chiave privata.

Una volta decriptata la utilizza per decifrare il messaggio ricevuto.

### Firma con message digest

**PGP** migliora il sistema di firma aggiungendo una funzione **hash unidirezionale** che prende in input il messaggio di lunghezza variabile e genera un output di lunghezza prefissata.

Il **digest** e la **chiave privata** sono utilizzati da **PGP** per creare la “firma” che viene spedita insieme la testo.

Alla ricezione del messaggio **PGP** ricalcola il **digest** e lo confronta con quello ricevuto in modo da verificare la correttezza della firma.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2061.png)

## I protocolli SSL / TLS

**S**ecure **S**ocket **L**ayer e **T**ransport **L**ayer **S**ecurity.

Offrono meccanismi di sicurezza alle applicazioni che usano il protocollo TCP e sono in grado di rendere sicuri numerosi protocolli applicativi come HTTP, POP3, IMAP, ecc..

TLS e SSL lavorano a livello **transport** della pila ISO/OSI si interpongono tra il livello **application** e il protocollo **TCP.**

TCP/IP consente di leggere ed alterare i dati che vengono inviati in rete.

### Caratteristiche

→ Fornisce l’autenticazione per applicazioni server e client;

→ Cifra i dati prima di inviarli su un canale pubblico;

→ Garantisce l’integrità dell’informazione;

→ E’ stato progettato per essere efficiente.

### Componenti

→ **Handshake Protocol:**

Permette alle parti di negoziare i diversi algoritmi necessari per la sicurezza delle transazioni e consente l’eventuale autenticazione tra le parti.

→ **Record Protocol:**

Si occupa della compressione, del MAC e della cifratura.

→ **Change Chiper Spec Protocol:**

Impone l’esecuzione di un nuovo handshake per rinegoziare i parametri di sicurezza e ripetere l’autenticazione.

→ **Alert Protocol:**

Notifica situazioni anomale o segnala eventuali problemi.

![Rappresentazione delle componenti SSL / TLS](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2062.png)

Rappresentazione delle componenti SSL / TLS

### Handshake Protocol

E’ utilizzato dalle due parti (client e server) e permette di:

→ Negoziare la versione del protocollo e l’insieme degli algoritmi crittografici da utilizzare (**ciperhsuite**).

→ Stabilire le chiavi crittografiche da utilizzare.

→ Autenticare client e server (opzionale): utilizzo di certificati digitiali per ottenere la chiave pubblica dell’altro endpoint e verificarne l’identità.

### Ciperhsuite

Gli algoritmi crittografici usati da SSL/TLS dipendono dalla ciperhsuite su cui si sono accordate le parti.

La ciperhsuite e gli algoritmi di compressione sono negoziati mediante l’handshake.

Una ciperhsuite definisce:

→ Funzione hash usata dall’HMAC (es. SHA).

→ Schema di cifratura simmetrica (es. 3DES) → Sia block cipher che stream cipher.

→ Schema per l’accordo e lo scambio di chiavi (es. RSA oppure DH).

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2063.png)

### Sessione sicura

Una sessione sicura rappresenta una sequenza di valori che possono essere utilizzati con SSL/TLS:

→ Valori segreti calcolati durante l’handshake;

→ Ciperhsuite stabilita durante l’handshake.

Stabilire tutti i parametri ogni volta che c’è una connessione può essere inefficiente, perciò una sessione può sopravvivere tra più connessioni.

### Costo di una Sessione

Lato client:

→ Generazione di valori random;
→ Verifica del certificato del server;
→ Generazione valori random per la chiave;

→ Calcolo della chiave attraverso hash.

Lato server:

→ Generazione di valori random;

→ Decifrazione valori inviati dal client;

→ Verifica del certificato del client;

→ Calcolo della chiave attraverso gli hash.

### Informazioni di Stato relativi a Sessione e Connessione

**Sessione**:

→ Session ID;

→ Certificati;

→ Algoritmo di compressione e ciperhsuite;

→ Master key: per la derivazione delle varie chiavi utilizzate dal protocollo;

→ Riesumabile: valore booleano che indica se la sessione può essere utilizzata in più connessioni.

**Connessione:**

→ Numeri di sequenza;

→ Chiavi MAC;

→ Chiavi di cifratura;

→ Vettori di inizializzazione (IV);

Chiavi ed IV sono creati in base alla Master Key.

---

Il protocollo di Handshake può essere eseguito in forma abbreviata, per riesumare una sessione precedentemente stabilita.

### Autenticazione: Certificate, Certificate {Request, Verify}

Sono i messaggi che consentono alle parti di autenticarsi.

Il messaggio *Certificate* contiene una lista di certificati:

→ Il certificato del server deve essere conforme all’algoritmo di autenticazione specificato nella ciperhsuite.

→ Il certificato del client deve essere inviato solo se c’è un messaggio *Certificate Request.*

L’eventuale certificato del client deve essere conforme alle specifiche indicate nel messaggio di richiesta.

> L’invio dei certificati non è obbligatorio ma quello del server può essere necessario.
> 

### Certificate Verify

Il messaggio *Certificate Verify *****viene inviato dal client solo se quest’ultimo ha inviato il proprio certificato al server.

### {Client, Server}Key Exchange

Il server invia il messaggio *Server Key Exchange* se il proprio certificatao non è adeguato al tipo di autenticazione stabilito nella chipersuite.

Il messaggio *Client Key Exchange* è obbligatorio. Con esso le parti hanno le informazioni necessarie per poter calcolare la chiave di cifratura simmetrica da utilizzare in seguito all’handshake

---

Il messaggio *Server Key Exchange* viene usato con il messaggio *Finished* per l’identificazione del server.

### Change Cipher Spec - Finished

Mediante il messaggio *Change Cipher Spec* ogni parte indica all’altra che sta per usare gli algoritmi e le chiavi appena negoziate.

I messaggi *Finished* sono di testing, sono i primi messaggi che vengono inviati utilizzando algoritmi e chiavi negoziate durante le fasi precedenti.

### Record Protocol

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2064.png)

### Change Cipher Spec Protocol

E’ utilizzato per aggiornare la ciphersuite in uso tra client e server.

Il protocollo consiste in un unico messaggio, inviato da una delle due parti all’altra; il messaggio è dato da un singolo byte di valore 1.

### Alert Protocol

Usato da una parte per trasmettere messaggi di alert all’altra.

Ciascun messaggio è caratterizzato da un livello di severità: **warning** o **fatal.**

I messaggi possono essere tipo: unexpected message, handshake failure, unsupported certificate, …

---

## Firewall

<aside>
💡 **Firewall** è un termine inglese che significa “*muro tagliafuoco*” ed è un componente **passivo** di difesa perimetrale che può anche svolgere funzioni di collegamento tra due o più tronconi di rete.

</aside>

> **Firewall Hardware**: componente passivo che opera una difesa perimetrale della nostra rete locale (LAN).
> 

> **Firewall Softwate (o Personal Firewall):** software che viene installato direttamente sul PC da proteggere. 
Il personal firewall esegue anche un controllo a livello di programma. (Monitorizza l’attività di scambio dati da e verso internet di tutto il software).
> 

### I limiti di un firewall

Ci sono due tipologie di problemi di sicurezza:

→ Configurazioni **non corrette**: attraverso una configurazione apposita si sarebbero potuti evitare incidenti.

→ Problematiche **tecniche**: nonostante una buona configurazione firewall, è possibile accedere ad un componente che si riteneva protetto sfruttando errori di programmazione o vulnerabilità del firewall.

### Cosa non può fare un firewall?

→ Protezione da attacchi interni:

Una volta che il “muro” del firewall è stato oltrepassato, questo non è più di alcuna utilità. Infatti ci offre una protezione perimetrale e tutto ciò che è interno all’area è escluso dal filtraggio.

→ Social Engineering:

Usato per indicare coloro che telefonano agli impiegati spacciandosi per membri della sicurezza per estorcere informazioni.

→ Integrità dei dati:

E’ impensabile chiedere ai firewall in reti di grandi dimensioni di controllare tutti i pacchetti alla ricerca di virus. La soluzione sarebbe applicare un antivirus in tutte le macchine.

→ Cattiva configurazione:

Non è in grado di distinguere da solo ciò che va bloccato e ciò che va accettato. Quindi la qualità del firewall dipende dalla qualità della configurazione.

### Classificazione dei firewall

Una prima classificazione viene fatta sul tipo di protezione che il firewall deve fare:

→ **Ingress firewall**: vengono controllati i collegamenti incoming (in arrivo).

→ **Egress firewall**: vengono controllati i collegamenti outgoing (uscenti), cioè l’attività del personale all’interno della LAN verso l’esterno.

Una seconda classificazione si basa sul numero di host protetti contemporaneamente:

→ **Pesonal Firewall:** proteggono il singolo host consentendo, generalmente di default, qualsiasi traffico verso l’esterno e bloccando quello in ingresso.

→ **Network firewall:** si interpone fra la LAN e internet e controlla tutto il traffico passante.

La terza classificazione viene fatta secondo il livello di intervento:

→ **Filtri di pacchetti IP:** permettono di bloccare o abilitare selettivamente il traffico che attraversa il firewall, definendo i protocolli, gli indirizzi IP e le porte utilizzate.

→ **Server proxy**: rappresentano una sorta di intermediario che si occupa di intrattenere le connessioni per conto di qualcun altro nella rete interna.

### Personal firewall

Può essere semplicemente un programma installato sul proprio PC che protegge da attacchi esterni: il traffico dall’interno verso l’esterno è consentito per default mentre il traffico dall’esterno verso l’interno è vietato per default.

Sono utilizzabili solo a scopo personale ma impensabili in una azienda in quanto risulterebbero economicamente non convenienti.

### Network firewall

Sono i classici firewall aziendali dove una o più macchine sono dedicate al filtraggio di tutto il traffico da e per una rete locale.

A seconda del livello di rete nel quali si fanno i controlli i firewall possono essere classificati in:

- **Packet filtering router:** network level gateway;
- **Stateful inspection**: gateway a livello di trasporto;
- **Proxy server**: gateway a livello di applicazione.

### Packet filtering router

Scherma i pacchetti dipendentemente dal protocollo, dall’indirizzo della sorgente e della destinazione e dai campi di controllo presenti nei pacchetti in transito, cioè analizza le informazioni contenute nell’header **TCP/IP** per individuare:

→ **IP** del mittente o del destinatario;

→ Indirizzo **MAC** sorgente o destinatario;

→ Numero di porta verso cui è destinato il pacchetto;

→ Protocollo da utilizzare.

Il firewall decide se il pacchetto può essere accettato o meno attraverso un algoritmo di scelta che si basa su una lista di regole precedentemente definite: 

→ Ciò che NON è specificatamente permesso è proibito (**deny**).

→ Ciò che NON è specificatamente probiti è permesso (**permit**).

In base a queste regole i pacchetti possono essere:

→ **Accept/allow:** il firewall permette al pacchetto di raggiungere la sua destinazione.

→ **Deny:** il firewall scarta il pacchetto senza che questo passi attraverso il firewall.

→ **Discart/reject:** il firewall scarta il pacchetto senza restituire nessun messaggio d’errore all’host sorgente, implementando il cosiddetto blach hole, che elimina il pacchetto senza che la sua presenza venga rivelata agli estranei.

### Vantaggi

- **Trasparenza**: l’utente non si accorge della presenza del firewall.
- **Velocità**: effettuando minori controlli rispetto agli altri firewall risulta essere il più veloce.
- **Immediatezza**: tramite la definizione di una singola regola si può difendere un’intera rete.
- **Gateway-only**: non sono richieste ulteriori configurazioni aggiuntive per i client.
- **Topologia della rete interna invisibile dall’esterno:** se viene aggiunto un NAT, dall’esterno l’unico host visibile è il gateway.

### Svantaggi

- **Basso livello**: è veloce ma non è in grado di elaborare le informazioni dei livelli superiori a quello di rete e quindi non è in grado di bloccare attacchi mirati a vulnerabilità di una specifica appliazione.
- **Mancanza di servizi aggiuntivi**: non permettono la gestione di servizi come l’autenticazione, il filtraggio URL e dei contenuti delle pagine Web.
- **Logging limitato:** i file di log contengono poche informazioni che generalmente sono insufficienti per verificare se il firewall compie sempre il proprio dovere.
- **Vulnerabile allo spooing**: dato che vengono filtrari i pacchetti in base alla loro provenienza, i casi di IP spooing non vengono riconosciuti.
- **Testing complesso**: è lungo e complicato effettuare le prove che verifichino il funzionamento.

### Stateful inspection

Anche detti firewall di seconda generazione, effettuano il filtraggio non sul singolo pacchetto ma **sulla connessione**.

Alla richiesta di connessione, se questa viene accettata, vengono memorizzate le sue caratteristiche in una tabella di stato in modo che i successivi pacchetti non vengano più analizzati ma gli venga permesso il transito, risparmiando al firewall notevoli quantità di elaborazione.

Nella tabella di stato per ogni connessione sono memorizzati:

→ Identificatore univoco del collegamento;

→ Indirizzi IP sorgente e destinazione;

→ Interfacce di rete utilizzate;

→ Stato della connessione:

- Handshaking se si è nella fase iniziale;
- Established se la connessione è stata stabilita;
- Closing se la connessione è terminata e si sta per eliminare la entry.

### Vantaggi

- **Buon rapporto prestazioni/sicurezza**: offre un ottimo compromesso fra le prestazioni e la sicurezza dato che effettua meno controlli durante la connessione.
- **Protezione da IP spooing e session hijacking**: è molto più difficile riuscire a violare il firewall.
- **Tutti i vantaggi del packet filtering router.**

### Svantaggi

- **Protocollo unico**: sfruttando molte delle caratteristiche del protocollo TCP risulta difficilmente utilizzata all’interno di altre infrastrutture di rete;
- **Servizio di auditing limitato**: le informazioni che registra nei file di log sono ancora insufficienti.
- **Mancanza di servizi aggiuntivi**: non permette servizi aggiuntivi come la gestione delle autenticazioni e il filtraggio dei contenuti.
- **Testing complesso:** è lungo e complicato effettuare le prove che verifichino il funzionamento.

### Proxy server

Applica una politica di sicurezza molto più severa di un packet filtering router.

Viene installato un programma mirato sul gateway per ogni applicazione desiderata.

Se l’amministratore di rete non installa il programma proxy per una determinata applicazione, il servizio non è supportato e non può essere inoltrato attraverso il firewall.

Il **proxy** è un programma che viene eseguito sul gateway che funge da intermediario a livello di applicazione.

Nelle applicazioni client - server un application proxy comunica con il client simulando di essere il server, e viceversa, con il server simulando di essere il client.

### Vantaggi

- **Controllo completo**: non fa verifiche solo alle informazioni contenute nell’header del pacchetto ma usa anche quelle contenute nel body.
- **Log dettagliati**: le informazioni memorizzate sono molto accurate.
- **Nessuna connessione diretta**: ogni volta i pacchetti in entrata e uscita vengono totalmente rigenerati.
- **Sicurezza anche in caso di crash**: un crash di un packet filtering router permetterebbe a qualunque pacchetto di viaggiare indisturbato, mentre un crash del proxy bloccherebbe completamente la connessione.
- **Supporto per connessioni multiple**: può capire se connessioni separate appartengono alla stessa applicazione.
- **User - friendly:** regole di filtraggio molto più facili da configurare rispetto a quelle di un packet filtering.
- **Autenticazione e filtraggio contenuti:** supportano un’autenticazione rigida dell’utente.

### Svantaggi

- **Costo.**
- **Difficoltà di amministrazione.**
- **Poco trasparente**: i computer interni devono essere configurati per utilizzare il proxy invece di collegarmi direttamente al server.
- **Un proxy per ogni applicazione**: per ogni servizio che si vuole fare passare attraverso il firewall c’è bisogno di un proxy dedicato.
- **Basse performance:** richiede molto lavoro per la cpu.

### Bastion host

> Indichiamo l’host configurato per respingere attacchi contro la rete interna e più in generale tutti quegli host che fungono da firewall critici per la sicurezza della rete.
> 

Possiede in genere le seguenti caratteristiche:

- Unico calcolatore della rete interna raggiungibile da internet;
- Dotato di software strettamente necessario, il più possibile privo di bug utilizzabili come vie d’accesso.
- File System a sola lettura.
- Numero minimo dei servizi e nessun account utente.
- Eliminazione dei servizi non fidati.

### DMZ

> E’ la sigla di **D**emilitarized **Z**one ed è una “sezione di rete”.
> 

La zona demilitarizzata è una porzione di rete che separa la rete interna dalla rete esterna: i server nella DMZ sono accessibili dalla rete pubblica, perciò non sono **trusted** dalla rete interna, e quindi devono essere segregati, in quanto, se venissero compromessi, questo non deve produrre effetti nella rete aziendale.

La DMZ permette di effettuare la sicurezza perimetrale, cioè protegge una rete nei punti in cui essa è a contatto con il mondo esterno, interponendosi tra la LAN aziendale e la WAN esterna.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2065.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2066.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2067.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2068.png)

### Architettura 3 - TIER

Utilizzando un’architettura dove sono separati Web server, Application Server e il Database, è buona norma mettere il Web server verso l’esterno e collocare nella DMZ l’application server, che di solito ospita la business logic e si collega al DB, il quale è all’interno della LAN.

> Nelle ditte in cui la sicurezza dei dati è vitale, è possibile introdurre un sistema di stratificazione della DMZ inserendo anche più di due firewalls e più DMZ.
> 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2069.png)

---

## Reti private virtuali (VPN)

> Il termine VPN (Virtual Private Network) nasce alla fine degli anni 90 e si pone come evoluzione delle linee dedicate tra diverse sedi aziendali.
> 

Nel passato infatti i collegamenti tra sedi remote di una stessa società, e quindi tra reti LAN remote, avvenivano solo se era presente una linea di comunicazione fisica dedicata, come per esempio via cavo.

Le reti **private dedicate**, o reti private “vere e proprie” possiedono alcuni vantaggi:

→ Larghezza di banda sempre disponibile;

→ Nessun problema di accesso;

→ Prestazioni garantite;

→ Sicurezza garantita.

Le reti private dedicate possiedono un rapporto costi/benefici non sempre elevato.

Inoltre queste reti possiedono elevati costi per l’installazione e la manutenzione, oltre a tempi lunghi per la configurazione e riconfigurazione, in quanto non sono scalabili.

Le **reti private virtuali (VPN)** invece sono configurabili e riconfigurabili facilmente, sono scalabili e offrono un valido rapporto tra costi e funzionalità.

Le **VPN** possiedono i seguenti vantaggi:

→ Costi ridotti;

→ Multiplexing dei canali logici;

→ Trasparenza, in quanto il gestore della rete pubblica potrebbe anche non essere a conoscenza della VPN;

→ Scalabilità.

Tuttavia le VPN implicano tre **problematiche**:

→ Velocità di trasmissione non sempre garantita;

→ Autenticazione necessaria;

→ Sicurezza delle trasmissioni con protocolli e tecniche di cifratura e tunneling.

### Tunneling

<aside>
💡 é il processo di trasmissione di informazioni riservate attraverso una rete pubblica in modo tale che i nodi che appartengono alla rete pubblica siano inconsapevoli che il processo di trasmissione faccia parte della rete privata.

</aside>

I dati vengono suddivisi in sezioni di dimensioni ridotte, chiamate pacchetti, che vengono trasmessi nel tunnel fino a destinazione.

Durante il tragitto nel tunnel i pacchetti vengono **crittati** e **incapsulati.**

Gli strati di **tunneling VPN** possono essere creati ai seguenti livelli:

→ Livello 2: collegamento dati;

→ Livello 3: livello di rete.

I **protocolli** coinvolti nel processo di **tunneling** sono:

- Protocollo **PPTP** (Point to Point Tunneling Protocol)
    
    In questo protocollo i dati vengono mantenuti al sicuro anche se comuincati su reti pubbliche.
    
- Protocollo **L2TP**
    
    Questo protocollo prevede la combinazione dell’utilizzo del **PPTP** e dell’inoltro a livello 2 ed è usato per supportare le VPN come parte di servizi ISP.
    

### Scenari di applicazione di una VPN

Esistono principalmente tre scenari di applicazione delle VPN:

- Collegamento di due o più sedi aziendali attraverso una rete aperta (**site to site**);
- Accesso alla rete aziendale da casa o da mobile (**End to site**);
- Accesso remoto da un computer a un altro (**end to end**).

### VPN site to site

Si applica quando vi è la necessità di collegare più reti locali attraverso un canale di trasmissione **pubblico** su di una arete di comunicazione virtuale.

Questa situazione potrebbe per esempio verificarsi quando vi è l’esigenza di stabilire un collegamento tra diverse aree aziendali.

Questa struttura richiede la presenza di un **router VPN** per ciascuna sede, che rappresenta il **tunnel VPN** tra reti locali.

### VPN end to site

Trovano applicazione quando la rete aziendale deve essere accessibile da remoto o da casa.

### VPN end to end

Quando l’accesso remoto non avviene su di una rete locale, ma solo da una postazione all’altra.

Una VPN **remote desktop** viene utilizzanta quando per esempio un impiegato vuole accedere da casa al suo computer direttamente sulla postazione presente sul posto di lavoro.

### VPN e sicurezza

Possiamo classificare le reti private in tre categorie, in base al grado di sicurezza offerto:

1. **Trusted VPN**
    
    La sicurezza è affidata al **provider (ISP)** della rete pubblica.
    
    Le trusted VPN assicurano le proprietà dei percorsi ma non garantiscono un alto livello di sicurezza.
    
2. **Secure VPN**
    
    I protocolli di cifratura e tunneling sono **IPsec** e **TLS/SSL** che assicurano la cifratura dei dati ma non garantiscono le proprietà dei percorsi.
    
3. **Hybrid VPN**
    
    Si tratta di un tentativo di unire le caratteristiche di entramve le reti VPN.
    

### Categorie d’uso delle VPN

Possiamo suddividere le VPN in tre principali **categorie d’uso:**

1. **Remote access**
2. **Intranet**
3. **Extranet**

### 1. Remote access

Permette a un utente di connettersi da una postazione remota alla rete privata. 

E’ necessario possedere due componenti:

- NAS (Network Access Server), si tratta di un server di accesso alla rete.
- Software VPN client, consente di connettersi alla VPN usando il proprio computer.

### 2. 3. Intranet ed Extranet

Abbiamo una VPN di tipo site to site, dove la società consente l’accesso remoto in larga scala

Nella categoria **Intranet** la comunicazione avviene esclusivamente tra i siti della stessa società, secondo il modello site to site.

Nella categoria **Extranet** la comunicazione avviene tra società che hanno interessi comuni, sempre secondo il modello site to site.

---

# Wireless e reti mobili

Tra le reti wireless possiamo distinguere due famiglie:

1. Reti **radiomobili**, sono reti wireless dove i terminali possono spostarsi sul territorio senza perdere la connettività con la rete, come la **rete cellulare.**
2. Wireless **LAN** (WLAN), sono reti wireless che forniscono coperture e servizi tipici di una LAN.

Nelle reti cellulari la connessione deve essere “passata” tra celle adiacenti senza che venga a perdersi il collegamento: questo passaggio prende il nome di **handover** (o handoff)

Le funzionalità aggiuntive che devono essere svolte in sistemi che presentano utenti in “mobilità” sono:

- Localizzazione
- Registrazione
- Handover

> Come per le reti cablate anche per le reti wireless viene fatta una classificazione sulla base della distanza geografica che il segnale trasmesso dai dispositivi che si connettono alla rete può raggiungere.
> 

### WLAN (Wireless Local Area Network)

Sono le reti maggiormente diffuse con il oro raggio di copertura che va dai 100 ai 500 metri.

Una rete Wlan è costituita da **Station (Sta)** e **Access Point** (**AP**).

### WWAN (Wireless Wide Area Network)

Sono reti wireless di dimensione geografica estesa sino a una decina di kilometri e nascono dall’esigena di raggiungere utenti che difficilmente potrebbero avere connessioni cablate, come paesi di montagna o aree difficilmente raggiungibili o antieconomiche per le normali linee fisse.

Le reti WWAN sono realizzate con diversi standard:

- Prima generazione **(1G)**;
- Seconda generazione **(2G)**;
- Terza generazione **(3G);**
- Quarta generazione **(4G)**
- Quinta generazione **(5G).**

---

Troviamo anche altre tecnologie wireless, come ad esempio l**’irDA,** tecnologia di interconnessione dati che utilizza i raggi **infrarossi**.

---

### Pregi delle WLAN

→ Assenza di cablaggio

→ Facilità di installazione

→ Basso costo

→ Mobilità

### Difetti delle WLAN

→ Inaffidabilità del mezzo trasmissivo

→ Sensibilità alle interferenze

→ Privacy

→ Capacità inferiore alle LAN cablate

> Tutto il traffico generato/ricevuto dalle stazioni (STA) è trasferito tramite l’Access Point (AP)
> 

### Problametiche del Wi-Fi

> **Capture effect**: è un fenome per il quale fra due segnali inviati a una stazione destinatario, il più forte risulta attenuato e rallentato a causa del più debole.
> 

> **Problema della stazione nascosta (hidden terminal):** siano date tre stazioni A, B, C, e A stia trasmettendo a B: se C ascolta il mezzo trasmissivo lo troverà libero e sarà convinta di poter trasmettere a B, ma cominciando a trasmettere disturberà la trasmissione di A.
> 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2070.png)

> **Problema della stazione esposta (exposed terminal):** è il problema inverso al precedente, supponiamo che B stia trasmettendo ad A e che C voglia trasmettere a D: ascoltando l’etere, C sentirà la trasmissione di B e concluderà erroneamente di non poter trasmettere, invece essendo D fuori dalla portata di B e A fuori dalla portata di C, le due trasmissioni potrebbero avvenire contemporaneamente.
> 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2071.png)

## Topologie di rete per IEEE 802.11

### Ad hoc Network (Independent Basic Service Set - IBSS)

All’interno del **BSS** (”independent” BSS) le stazioni possono comunicare direttamente l’una con l’altra senza l’ausilio di un AP.

---

<aside>
💡 **Funzione di coordinazione** (Distributed Coordination Function - DCF): insieme di regole per la gestinoe dell’accesso al mezzo condiviso che garantiscono uguali probabilità di successo nella trasmissione di dati.

</aside>

### **Basic Service Set (BSS) (Infrastructure mode)**

E’ una BSS con un componente chiamato Access Point che fornisce la funzione di relay per la BSS.

La comunicazione tra stazione avviene solo attravero l’AP.

L’AP può fornire la connessione al **Distribution System.**

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2072.png)

## Gestione accesso al mezzo 802.3 vs 802.11

In una rete locale Ethernet classica, il metodo di accesso utilizzato per i terminali è il CSMA/CD (Carrier Sense Multiple Access with Collision Detector), per cui ogni terminale è libero di comunicare in qualsiasi momento.

In un ambiente senza fili questa procedura non è possibile dato che le due stazioni comunicanti con un ricettore non si sentono reciprocamente.

Così la norma 802.11 propone il protocollo detto **CSMA/CA** (Carrier Sense Multiple Access with Collision Avoidance).

Questo protocollo usa un meccanismo per evitare le collisioni basato sul principio di ricevuta di ritorno reciproca tra l’emittente e il ricevente.

La stazione che vuole emettere ascolta la rete. Se la rete è occupata la trasmissione sarà differita.

In caso contrario, se il media è livero per un tempo dato (detto DIFS - Distributed Inter Frame Space), allora la stazione può emettere.

La stazione trasmette un messaggio detto Ready to Send che contiene informazioni sul volume dei dati e sulla velocità di trasmissione.

Il ricevente risponde con Clear To Send se è pronto a ricevere i dati, poi la stazione comincia l’emissione dei dati.

Alla ricezione di tutti i dati emessi dalla stazione, il ricevente invia una ricevuta di ritorno chiamata ACK.

Tutte le stazioni vicine aspettano per un periodo di tempo che considerano necessario alla trasmissione del volume di informazioni da emettere alla velocità annunciata.

Il livello MAC del protocollo 802.11 offre un meccanismo di **controllo di errore** che permette di verificare l’integrità del frame. Si tratta di una differenza fondamentale con lo standard Ethernet.

In una rete senza fili il tasso di errore è più elevato, ragione per cui un controllo di errore è stato integrato a livello collegamento dati.

D’altra parte il tasso di errore aumenta generalmente con dei pacchetti di dimensione importante, per questo l’802.11 offre un meccanismo di **frammentazione**, che permette di scomporre un frame in più pezzi.

## Il ruolo dell’Access point

Un Access Point è un’entità che permette la distribuzione dei servizi MAC via Wireless Medium (WM) per le stazioni a esso associate.

L’Access Point può essere configurato per funzionare in due modalità:

### Root Access Point

Realizza la funzione di DCF e di apparato di associazione per le stazioni presenti nel BSS.

Questa è la configurazione di default che troviamo in ogni AP.

Quando una stazione viene associata all’AP, questo ne scrive l’indirizzo MAC in una tabella che mantiene aggiornata con le nuove connessioni o disconnessioni.

Alla ricezione di un pacchetto dal WM, se l’indirizzo MAC di destinazione è presente nella tabella associata al AP, il pacchetto viene ritrasmesso nel WM, altrimenti se l’indirizzo non è presente nella tabella delle stazioni associate all’AP il pacchetto viene tradotto e trasmesso nella porta wired.

Alla ricezione di un pacchetto dalla porta wired ha un comportamento simile: se l’indirizzo MAC di destinazione è presente nella tabella delle stazioni associate il pacchetto viene tradoto e trasmesso nel WM, mentre se l’indirozzo non è presente nella tabella il pacchetto viene scartato.

### Repeater Access Point

L’Access Point funziona come repeater e ha il compito di ritrasmettere i pacchetti che riceve dal WM sul WM.

## La sicurezza delle reti wireless

Come ogni comunicazione cablata, la trasmissione senza fili presenta da sempre diverse problematiche relative alla sicurezza.

I problemi principali che riguardano una WLAN sono:

→ **Riservatezza**: i dati trasmessi attraverso il canale non devono essere intercettati e interpretati;

**→ Controllo di accesso**: alla rete possono accedere solo gli host autorizzati;

→ **Integrità dei dati**: i messaggi trasmessi non devono essere manomessi.

### Tipologie di attacchi alle reti wireless

- **Eavesdropping (intercettazione)**: possibilità che entità non autorizzate riescano a intercettare i segnali radio scambiati tra una stazione e l’access point.
- **Accessi non autorizzati**: un intruso si intromette alla rete senza averne l’autorizzazione.
- **Interferenze e jamming**: tutte le apparecchiature in grado di emettere segnali a radiofrequenza entro la banda di funzionamento della rete rappresentano potenziali sorgenti di interferenza: se esiste la **volontà** di queste emissioni si parla di **jamming**.
- **Danni materiali**: possono essere fatti danni materiali allo scopo di creare malfunzionamenti o interruzioni dei servizi.

---

### La crittografia dei dati

L’operazione di codifica dei dati fornisce riservatezza e integrità.

## WEP - Wired Equivalent Privacy

E’ un protocollo di sicurezza a livello **data link** della pila ISO/OSI.

> Venne rilasciato e integrato tra le specifiche di sicurezza delle reti Wi-Fi troppo velocemente. Soltanto dopo l’immissione sul mercato si dimostrò che la sua sicurezzaa non era assolutamente assimilabile a quella delle reti cablate, e che normali utenti informatici avrebbero potuto violare in pochissimo tempo la crittografia utilizzata.
> 

Si basa sul **modello a chiave simmetrica** mediante un algoritmo che permette di modificare un blocco di testo in chiaro calcolandone lo XOR bit a bit con una chiave di cifratura pseudicasuale.

### Codifica

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2073.png)

La *Chiave di cifratura* viene realizzata a partire dalla *chiave segreta* che viene concatenata con un **initialization vector (IV)**, numero casuale di 24 bit.

Verrà spedito l’initializing vector insieme al testo cifrato e la Secret Key.

### Decodifica

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2074.png)

Tramite l’Initialization Vector e la secret key si risale alla key stream la quale, eseguendo lo XOR con il Ciphertext, ci riporta al testo decifrato assieme al suo Integrity Check Value (ICV), che verrà comparato con il nuovo ICV calcolato.

### WPA/WPA2

Il **Wireless Proteced Access** rappresenta una miglioria del WEP, esistono due diverse configurazioni in cui lavora:

- Modalità **Personal.**
- Modalità **Enterprise.**

Dove la modalità Personal è consigliata per le applicazioni **SOHO - Small Office Home Office.**

Le principali migliorie introdotte dal WPA sono nelle dimensioni della chiave, che diventa da 128 bit, e del vettore di inizializzazione, che passa a 48 bit.

> WPA utilizza inoltre un nuovo protocollo, il **Temporary Key Integrity Protocol (TKIP)**, che permette di cambiare le chiavi crittografiche utilizzatae dopo un certo numero di dati scambiati.
> 

Inoltre, al posto del CRC - 32 viene utilizzato il **Message Integrity Code (MIC)** per effettuare il controllo dell’integrità dei dati.

Il **MIC** è un **Message Authentication Codes (MAC)**, permette di rilevare la presenza di messaggi falsi nella comunicazione.

### WPA2

WPA2 è un’aggiornamento del WPA e utilizza l’algoritmo **AES** al posto dell’**RC4** per la cifratura dei dati.

**AES** può avere diverse modalità di utilizzo, chiamate modalità operative:

- Electronic Codebook (ECB),
- Counter (CTR);
- Cipher-Block Chaining (CBC).

Quella che viene maggiormente utilizzata è la CBC alla quale spesso viene aggiunto un controllo di integrità dei dati MIC, la modalità prende il nome di CBC-MAC.

---

## Autenticazione

E’ il processo tramite il quale un computer, un software o un utente verifica la corretta identità di un altro computer, software o utente che vuole comunicare attraverso una connessione.

Un esempio che tutti noi effettuiamo tutti i giorni è la comune procedura di “login” per accedere a un sistema di elaborazione.

### Il sistema di autenticazione 802.1X

> La prima forma di autenticazione si basava sulla conoscenza dell’SSID della rete: prende il nome di **OSA** (Open System Authentication) dove l’Access Point autorizzava chiunque fosse a conoscenza del nome della rete.
> 

Un sistema di autenticazione aggiuntivo è quello che si basa sul filtraggio dei MAC Address dei dispositivi wireless, ma prevede una lunga procedura manuale a opera degli amministratori di rete.

Per garantire un metodo più affiadbile di autenticazione e autorizzazione, l’IEEE 802.11i ha proposto una struttura di protezione WLAN basata sul protocollo 802.1X.

I componenti del sistema di autenticazione sono:

- L’utente di rete (supplicant);
- Un dispositivo di accesso alla rete (Authenticator);
- Un servizio di autenticazione, autorizzazione e accesso (AAA), generalmente un server RADIUS.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2075.png)

1. Un client entra nel raggio d’azione dell’AP, questo richiede le credenziali di accesso al client.
2. Il client si identifica all’AP, che inoltra le informazioni ricevute ad un server RADIUS.
3. Il server richiede altre credenziali al client per verificarne l’identità, specificando anche il tipo di credenziali richieste.
4. Il client invia le proprie credenziali al RADIUS.
5. Il server verifica le credenziali: se sono valide invia una chiave di autenticazione crittografa all’AP.
6. L’AP utilizza la chiave di autenticazione per trasmettere in modo protetto le chiavi di autenticazione per accedere alla rete.

---

# Modello client/server e distribuito per i servizi di rete

Le applicazioni distribuite possono essere suddivise secondo tre livelli applicativi.

1. Il livello **presentazione** si occupa di gestire la logica di presentazione.
2. Il livello della **logica applicativa** o logica di business si occupa delle funzioni da mettere a disposizione all’utente.
3. Il livello di **logica di accesso** ai dati si occupa della gestione dell’informazione, eventualmente con accesso alle basi di dati.

Questi tre livelli applicativi possono essere installati su vari livelli hardware, detti **tier,** dove un livello rappresenta una macchina con differente capacità di elaborazione.

Un’applicazione può essere:

- **Single tier**: i tre livelli sono ospitati su una singola macchina o host.
- **Two tier:** i tre livelli sono divisi fra una macchina **utente**, che ospita il livello di presentazione, e la macchina **server** che ospita il livello di accesso ai dati; il livello di **logica applicativa** può risiedere sul lato utente o server o essere distribuito fra i due.
- **Three tier**: i tre livelli risiedono ciascuno su una macchina dedicata.

> Le architetture dei sistemi informatici si sono sviluppate ed evolute nel corso degli anni passando da sistemi **centralizzati** a **sistemi distribuiti**, maggiormente rispondenti alle necessità di decentralizzazione e di cooperazione delle moderne organizzazioni.
> 

<aside>
💡 Parliamo di sistema informatico centralizzato quando i dati e le applicazioni risiedono in un unico nodo elaborativo.

</aside>

<aside>
💡 Un sistema informatico **distribuito** è quello che realizza almeno una delle seguenti situazioni:
- Le **applicazioni** risiedono su più nodi elaborativi;
- Il **patrimonio informativo** è ospitato su più nodi elaborativi.

</aside>

Un **sistema distribuito** è costituito da un insieme d’applicazinoi logicamente indipendenenti che collaborano per il perseguimento d’obiettivi comuni.

## Server farm

I **tier fisici** possono essere realizzati anche come **server farm** che viene gestita dagli altri livelli come se fosse un’unica risorsa.

<aside>
💡 Una server farm è formata da un insieme di elaboratori che condividono le applicazioni e i dati.

</aside>

Le server farm possono essere realizzate secondo due principi progettuali:

- **Cloning**
- **Partitioning**

### Cloning

Su ogni nodo che la compone vengono installate le stesse applicazioni software e gli stessi dati formando in tal modo dei cloni.

Le richieste vengono poi inviate ai vari cloni attraverso un sistema di **load - balancing.**

I **RACS** si possono presentare in due configurazioni:

- Shared nothing;
- Shared disk.

Nella prima configurazione i dati memorizzati sono replicati su ogni clone e risiedono in un disco fisso locale a ogni clone.

Questa configurazione presenta ottime prestazioni per applicazioni di tipo read-only.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2076.png)

Nella seconda configurazione, detta anche **cluster**, i cloni condividono un server di memorizzazione che gestisce i dischi fissi.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2077.png)

### Partitioning

La tecnica di **partizionamento** prevede la duplicazione dell’hardware e del software ma non dei dati, che invece vengono ripartiti tra i nodi.

Ogni nodo svolge quindi una funzione specializzata.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2078.png)

Il partizionamento è trasparente alle applicazioni, le richieste vengono inviate alla partizione che possiede i dati rilevanti.

Tuttavia i dati sono memorizzati su un singolo server, questo significa che in caso di guasto la parte di servizio da esso gestita non risulta più accessibile.

Questa caratteristica è nota come proprietà di **graceful degradation.**

Per risolvere questo problema si impiega spesso la **clonazione** dei singoli server, creando in tale modo dei **pack.**

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2079.png)

## Architetture dei sistemi web

Gli elementi essenziali di un moderno sistema web sono:

- Il **web server**, che si occupa della gestione delle richieste HTTP;
- Lo **script engine**, un processo che eseguie script per la generazione di pagine HTML dinamiche;
- L’**application server**, che assume il ruolo di middle tier e implementa la logica di business.
- Il **DBMS server**, che si occupa della gestione dei dati.
    
    ### Configurazione con due tier e unico host
    
    Questa configurazione utilizza una sola macchina fisica che supporta l’esecuzione di **web server, script engine e DBMS.**
    

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2080.png)

### Configurazione con tre tier e dual host

In questa configurazione **web server** e **script engine** sono ospitati su una stessa macchina, mentre il **DBMS** è eseguito su una macchina dedicata.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2081.png)

### Configurazione con tre tier e server farm

Per ottenere un sistema che migliori le caratteristiche di **disponibilità, scalabilità e prestazioni** è necessario duplicare i due componenti più critici del sistema: **web server** e **script engine.**

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2082.png)

### Configurazione con cinque tier e server farm

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2083.png)

## Amministrazione della rete

Attraverso l’amministrazione di rete si implementano le procedure e le politiche necessarie per garantire il corretto funzionamento della rete, a partire dall’autenticazione degli utenti fino al monitoraggio e al mantenimento delle corrette funzionalità degli apparati.

### L’autenticazione del client

In un sistema distribuito l’autenticazione riguarda la verifica dell’identità di un utente.

Questa operazione è chiamata **autenticazione del client**.

Sulla base di questa verifica il sistema permette o nega l’utilizzazione di risorse e l’esecuzione di procedure.

Gli schemi adottati per l’autenticazione sono fondamentalmente tre:

- User to host: è il metodo usato dall’host per autenticare gli utenti.
- Host to host: è il metodo usato dall’host per convalidare l’identità di altri host.
- User to user: è il metodo usato per verificare che i dati elettronici provengano effettivamente dall’utente in questione e non da qualcuno che si spaccia per il mittente.

### Amministrazione del sistema operativo

Attualmente i sistemi operativi di rete sono altresì sistemi operativi **multiutente**. Più utenti possono accedere contemporaneamente al sistema utilizzando le risorse messe a disposizione dal file system.

La sicurezza di questi sistemi è basata sui permessi che vengono associati alle varie risorse, in modo da restringerne l’accesso ai soli utenti abilitati.

L’amminsitrazione centralizzata di un sistema viene garantita nei sistemi windows mediante il servizio Active Directory, che permette la creazione e la modifica di **utenti, gruppi, politiche di sicurezza** e autorizzazioni relative alle risorse.

## Il troubleshooting

Le reti di comunicazione sono oggetti complessi, composti da un insieme interconnesso di apparati hardware e software tramite i quali vengono forniti servizi agli utenti.

La ricerca del problema del sistema e la sua soluzione, unitamente alla produzione della documentazione che ne illustra la soluzione, viene chiamata **troubleshooting** della rete.

E’ bene generalmente verificare preliminariamente se il problema sussista effettivamente oppure no, in quanto capita che un utente non esperto associ la non fruizione di un servizio di rete come un problema di connettività.

### Controllo fisico

Una volta accertato che si tratti di un problema di rete, occorre effettuare alcune verifiche:

- Controllare l’alimentazione
- Controllare la connettività
- Verificare che il LED presente nella scheda di rete sia acceso.
- Riavviare il computer.

### Scambio di componenti di rete

Le schede di rete (NIC) possiedono dei particolari LED che indicano lo stato della connessione.

Un LED spento indica chiaramente un problema di connettività tra la scheda e lo switch.

Nel caso di LED spento occorre procedere con le successive operazioni:

- Sostituiamo il cavo che connette la scheda ala presa a muro con un altro;
- Colleghiamo il computer a un’altra presa di rete;
- Verifichiamo la connessione da un altro host della rete.

Se entrambi gli host non accedono ai servizi di rete probabilmente si tratta di un effettivo malfunzionamento della rete.

### Verifica della connettività TCP/IP

Analizza la fruibilità dei servizi di rete come per esempio **web, mail, FTP**, ecc..

Supponiamo di voler effettuare una connnessione a un host mediante TCP/IP, per esempio all’URL di un Web server, si potrebbero verificare tre errori distinti:

- Se otteniamo il tipico errore 404 significa che la rete funziona correttamente, il problema in questo caso risiede sul server;
- Se invece otteniamo un messaggio di errore del tipo “il server non esiste” allora siamo di fronte a un possibile problema di rete;
- Se invece il server risulta raggiungibile mediante l’indicazione del solo indirizzo IP allora siamo di fronte a uno dei seguenti problemi di DNS:
    - Potrebbero essere sbagliati i riferimenti ai DNS server nella configurazione di rete dell’host;
    - La presenza di un malfunzionamento;
    - Potrebbe esserci un problema sui DNS server oppure potrebbero non essere raggiungibili.

### Analisi lato client

La verifica che dobbiamo effettuare sul client per prima cosa deve tenere conto della configurazione di rete dell’host, rappresentanta dall’indirizzo IP, subnet mask e default gateway.

### Analisi lato server

La prima cosa da fare è escludere che il servizio richiesto sia per qualche motivo attualmente non disponibile. In caso contrario ptremmo provare a eseguire un ping verso l’indirizzo IP dell’host di destinazione.

Se si verifica la connessione tra i due host significa che il problema appartiene a quest’ultimo.

Se le due macchine non si connettono ma l’host riesce a connettersi ad altri indirizzi IP che risiedono sulla stessa LAN della macchina di destinazione significa che il problema consiste in qualche malfunzionamento o non corretta configurazione della macchina destinazione.

---

# 🏰 Inglese

# 🪨 Standing Stones

# Stonehenge

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2084.png)

Stonehenge (pietra sospesa, da stone, pietra, e henge, che deriva da hang, sospendere: in riferimento agli architravi) è un sito neolitico che si trova vicino ad Amesbury nello Wiltshire, Inghilterra, circa 13 chilometri a nord-ovest di Salisbury.

È il più celebre e imponente cromlech («circolo di pietra»): composto da un insieme circolare di colossali pietre erette, conosciute come megaliti, sormontate da consistenti architravi orizzontali di collegamento di cui alcune sono in quota ed è uno dei più antichi sistemi trilitici conosciuti (trilitico: sistema costituito da tri = tre + lithos = pietra, due montanti verticali ed un architrave orizzontale).

Ipotizzando che l'attuale allineamento riproduca fedelmente il precedente, alcuni sostengono che Stonehenge rappresenti un "antico osservatorio astronomico", con un significato particolare ai punti di solstizio ed equinozio, anche se l'importanza del suo uso per tale scopo è dibattuta.

<aside>
⛰️ Il sito fu aggiunto alla lista dei patrimoni dell'umanità dell'UNESCO nel 1986.

</aside>

Oltre che meta del turismo di massa, Stonehenge è luogo di pellegrinaggio per molti seguaci del celtismo, della wicca e di altre religioni neopagane, e fu teatro di un festival musicale libero tra il 1972 e il 1984.

### Translation

Stonehenge is a prehistoric monument on Salisbury Plain in Wiltshire, England, two miles (3 km) west of Amesbury.

It consists of an outer ring of vertical sarsen standing stones, each around 13 feet (4.0 m) high, seven feet (2.1 m) wide, and weighing around 25 tons, topped by connecting horizontal lintel stones. Inside is a ring of smaller bluestones. Inside these are free-standing trilithons, two bulkier vertical Sarsens joined by one lintel. The whole monument, now ruinous, is aligned towards the sunrise on the summer solstice. 

Archaeologists believe that Stonehenge was constructed from 3000 BC to 2000 BC.
One of the most famous landmarks in the United Kingdom, Stonehenge is regarded as a British cultural icon. It has been a legally protected Scheduled Ancient Monument since 1882, when legislation to protect historic monuments was first successfully introduced in Britain. The site and its surroundings were added to UNESCO's list of World Heritage Sites in 1986. Stonehenge is owned by the Crown and managed by English Heritage.

---

# The Nine Ladies

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2085.png)

The Nine Ladies is a stone circle located on Stanton Moor in Derbyshire in the English East Midlands. The Nine Ladies is part of a tradition of stone circle construction that spread throughout much of Britain, Ireland, and Brittany during the Late Neolithic and Early Bronze Ages, over a period between 3300 and 900 BCE. The purpose of such monuments is unknown, although archaeologists speculate that the stones represented supernatural entities for the circles' builders.

Measuring 10.8 metres in diameter, the stone circle consists of ten millstone grit stones, although for several centuries one of these was buried, providing the impression that there had been nine stones. Whether the tenth was part of the original prehistoric design or a later addition is unknown. A single monolith, the King Stone, stands to the southwest of the circle; it is unknown if this was placed there in deliberate reference to the Nine Ladies circle or whether their proximity is incidental.

---

# Roll Right Stones

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2086.png)

The Rollright Stones are a complex of three Neolithic and Bronze Age megalithic monuments near the village of Long Compton, on the borders of Oxfordshire and Warwickshire. 

They were built at different periods in late prehistory. During the period when the three monuments were erected, there was a continuous tradition of ritual behaviour on sacred ground, from the 4th to the 2nd millennium BCE.

The first to be constructed was the Whispering Knights, a dolmen that dates to the Early or Middle Neolithic period. It was likely to have been used as a place of burial. This was followed by the King's Men, a stone circle that was constructed in the Late Neolithic or Early Bronze Age, it has parallels to other circles located further north, in the Lake District, implying a trade-based or ritual connection. The third monument, the King Stone, is a single monolith. 

By the Early Modern period, folkloric stories had developed about the Stones, telling of how they had once been a king and his knights who had been turned to stone by a witch. Such stories continued to be taught amongst local people well into the 19th century.

In the 20th century, the stones became an important site for adherents of various forms of Contemporary Paganism, as well as for other esotericists, who hold magico-religious ceremonies there. They also began to be referred to more widely in popular culture, being featured in television, literature, music and art.

---

# Avebury

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2087.png)

Ad Avebury, nella contea inglese dello Wiltshire, nei dintorni dell'omonimo villaggio, si trovano un grande henge e numerosi cerchi di pietre. Si tratta di uno dei monumenti neolitici europei meglio conservati ed è databile attorno a 5000 anni fa. È più antico del sito megalitico di Stonehenge, che si trova a circa 32 km a sud, anche se i due siti sono quasi contemporanei. Si trova approssimativamente a metà strada tra Marlborough e Calne, poco distante dalla A4 a nord della A361 verso Wroughton.

Avebury è di proprietà della National Trust.

### Translation

Avebury is a Neolithic henge monument containing three stone circles, around the village of Avebury in Wiltshire, in southwest England. One of the best known prehistoric sites in Britain, it contains the largest megalithic stone circle in the world. It is both a tourist attraction and a place of religious importance to contemporary pagans.

Constructed over several hundred years in the third millennium BC, during the Neolithic, or New Stone Age, the monument comprises a large henge (a bank and a ditch) with a large outer stone circle and two separate smaller stone circles situated inside the centre of the monument.

Avebury is owned and managed by the National Trust. It has been designated a Scheduled Ancient Monument, as well as a World Heritage Site, in the latter capacity being seen as a part of the wider prehistoric landscape of Wiltshire known as Stonehenge, Avebury and Associated Sites.

---

## Resources

[https://www.youtube.com/watch?v=nqz0pyNqY14](https://www.youtube.com/watch?v=nqz0pyNqY14)

# ⚔️ The Falkland/Malvinas War

La guerra delle Falkland o guerra delle Malvine fu un conflitto militare combattuto tra aprile e giugno 1982 tra Argentina e Regno Unito per il controllo e il possesso delle isole Falkland e della Georgia del Sud e Isole Sandwich Australi.

Alla vigilia della guerra l'Argentina si trovava nel pieno di una devastante crisi economica e di una contestazione civile su larga scala contro la giunta militare che governava il Paese. Il governo, guidato dal generale Leopoldo Galtieri, l'allora presidente, decise di giocare la carta del sentimento nazionalistico lanciando quella che considerava una guerra facile e veloce per reclamare le Falkland, su cui l'Argentina (che le chiama Malvinas, Malvine) rivendicava la sovranità. Sebbene colto di sorpresa dall'attacco, il Regno Unito organizzò una task force navale per respingere le forze argentine che avevano occupato gli arcipelaghi. Dopo pesanti combattimenti, i britannici prevalsero e le isole tornarono sotto il controllo del Regno Unito.

Le conseguenze politiche della guerra furono profonde: in Argentina crebbero dissenso e proteste contro il governo militare, avviandolo alla caduta definitiva, mentre un'ondata di patriottismo si diffuse nel Regno Unito, ridando forza al governo del primo ministro Margaret Thatcher. Il vittorioso conflitto diede fiato alle ambizioni britanniche di potenza post imperiale (dopo la grave delusione seguita alla decolonizzazione), dimostrando che il Regno Unito aveva ancora la capacità di proiettare con successo la propria potenza militare anche in una guerra a enorme distanza dalla madrepatria.

### Translation

The Falklands War was a ten-week undeclared war between Argentina and the United Kingdom in 1982 over two British dependent territories in the South Atlantic: the Falkland Islands and its territorial dependency, South Georgia and the South Sandwich Islands.

The conflict began on 2 April, when Argentina invaded and occupied the Falkland Islands, followed by the invasion of South Georgia the next day. The British government dispatched a naval task force to engage the Argentine Navy and Air Force before making an amphibious assault on the islands. The conflict lasted 74 days and ended with an Argentine surrender on 14 June, returning the islands to British control. In total, 649 Argentine military personnel, 255 British military personnel, and three Falkland Islanders died during the hostilities.

The conflict was a major episode in the protracted dispute over the territories' sovereignty. Argentina asserted (and maintains) that the islands are Argentine territory, and the Argentine government thus characterised its military action as the reclamation of its own territory. The British government regarded the action as an invasion of a territory that had been a Crown colony since 1841. Falkland Islanders, who have inhabited the islands since the early 19th century, are predominantly descendants of British settlers, and strongly favour British sovereignty. Neither state officially declared war, although both governments declared the islands a war zone.

The conflict has had a strong effect in both countries and has been the subject of various books, articles, films, and songs. Patriotic sentiment ran high in Argentina, but the unfavourable outcome prompted large protests against the ruling military government, hastening its downfall and the democratisation of the country. In the United Kingdom, the Conservative government, bolstered by the successful outcome, was re-elected with an increased majority the following year. The cultural and political effect of the conflict has been less in the UK than in Argentina, where it has remained a common topic for discussion.

## Resources

[https://www.youtube.com/watch?v=MNFjYm3UlvE](https://www.youtube.com/watch?v=MNFjYm3UlvE)

[https://www.youtube.com/watch?v=jLR7-hJZEBc](https://www.youtube.com/watch?v=jLR7-hJZEBc)

# 🤖 AI

### History

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2088.png)

### What is it?

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2089.png)

### Different types

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2090.png)

1. Purely reactive: just reacts to some inputs (chess)
2. Limited memory: uses some kind of data to create useful suggestions or intelligent answers
3. Theory of mind: has the capacity to understand thoughts and emotions and interact socially (still in the process of being invented
4. Self aware: (not invented yet)

### Applications of AI

1. Banking Fraud Detection
2. Online customer support
3. Cyber security
4. Virtual Assistants

### The future

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2091.png)

### Resources

[https://www.youtube.com/watch?v=cW9shEB8h5E](https://www.youtube.com/watch?v=cW9shEB8h5E)

# 💡 The development of computers

# Diagram

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2092.png)

# *Analytical engine*

La macchina analitica (Analytical engine in inglese) è stato il primo prototipo di un computer meccanico sviluppato per eseguire compiti generici. Il progetto fu sviluppato dal matematico, filosofo e scienziato inglese Charles Babbage (1791–1871), che cercò anche di realizzarlo praticamente. Rappresenta un importante passo nella storia dell'informatica.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2093.png)

### Translation

The Analytical Engine was a proposed mechanical general-purpose computer designed by English mathematician and computer pioneer Charles Babbage. It was first described in 1837 as the successor to Babbage's difference engine, which was a design for a simpler mechanical calculator.

The Analytical Engine incorporated an arithmetic logic unit, control flow in the form of conditional branching and loops, and integrated memory, making it the first design for a general-purpose computer that could be described in modern terms as Turing-complete.

In other words, the logical structure of the Analytical Engine was essentially the same as that which has dominated computer design in the electronic era The Analytical Engine is one of the most successful achievements of Charles Babbage.

Babbage was never able to complete construction of any of his machines due to conflicts with his chief engineer and inadequate funding.

---

# Colossus

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2094.png)

Il Colossus è stato uno dei primi computer elettronici programmabili nella storia dell'informatica. Costruito e messo in opera nel Regno Unito, durante la seconda guerra mondiale, fu in grado di decifrare i codici sviluppati dalla cifratrice Lorenz SZ 40/42 usata dai nazisti per proteggere la corrispondenza fra Adolf Hitler e i suoi capi di stato maggiore, oltre che alle comunicazioni Purple e Red giapponesi, basate sulla tecnologia di Enigma.

I servizi segreti britannici fecero di tutto per interpretare i codici dei nazisti, che però venivano cambiati quotidianamente.

Il Colossus, costruito in segreto per la Royal Navy, è stato il primo a usare le valvole termoioniche, fino ad allora usate solo da amplificatori, al posto dei relè: sfruttandone ben 1500, fu in grado di aumentare notevolmente la potenza di calcolo.

Il suo primato cronologico, tuttavia, è stato riconosciuto in ritardo a causa del rigoroso segreto imposto dal Regno Unito, resistito per decenni anche dopo la conclusione della guerra.

### Translation

Colossus was a set of computers developed by British codebreakers in the years 1943–1945 to help in the cryptanalysis of the Lorenz cipher. Colossus used thermionic valves (vacuum tubes) to perform Boolean and counting operations. Colossus is thus regarded as the world's first programmable, electronic, digital computer, although it was programmed by switches and plugs and not by a stored program.

Colossus was designed by General Post Office (GPO) research telephone engineer Tommy Flowers to solve a problem posed by mathematician Max Newman at the Government Code and Cypher School (GC&CS) at Bletchley Park. Alan Turing's use of probability in cryptanalysis contributed to its design. It has sometimes been erroneously stated that Turing designed Colossus to aid the cryptanalysis of the Enigma. (Turing's machine that helped decode Enigma was the electromechanical Bombe, not Colossus.)

Use of these machines allowed the Allies to obtain a vast amount of high-level military intelligence from intercepted radiotelegraphy messages between the German High Command (OKW) and their army commands throughout occupied Europe.

The existence of the Colossus machines was kept secret until the mid-1970s. All but two machines were dismantled into such small parts that their use could not be inferred. The two retained machines were eventually dismantled in the 1960s.

---

# Elea 9000

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2095.png)

Elea è il nome di una serie di elaboratori elettronici mainframe sviluppati da Olivetti nella seconda metà degli anni cinquanta la cui terza generazione, denominata Elea 9003, fu il primo della storia interamente realizzato con componenti a stato solido. Fu concepito, progettato e sviluppato da un piccolo gruppo di giovani ricercatori guidati da Mario Tchou.

Fu commercializzato alcuni mesi dopo l'uscita del concorrente 2002 della Siemens, che, però, ancora utilizzava alcune valvole, e vari mesi prima del lancio del 7090, il primo computer interamente a transistor realizzato dalla IBM.

L'acronimo ELEA stava per Elaboratore Elettronico Aritmetico (quest'ultimo aggettivo poi modificato in "Automatico" per ragioni di marketing).

### Translation

The Elea 9003 is one of a series of mainframe computers Olivetti developed starting in the late 1950s. The system, made entirely with transistors for high performance, was conceived, designed and developed by a small group of researchers led by Mario Tchou (1924–1961).

It was the first solid-state computer designed and manufactured in Italy.

The acronym ELEA stood for Elaboratore Elettronico Aritmetico (Arithmetical Electronic Computer, then changed to Elaboratore Elettronico Automatico for marketing reasons).

---

# Sinclair Spectrum

Lo ZX Spectrum è un home computer creato e prodotto dal 1982 fino al 1986 dalla Sinclair Research Ltd, e dal 1986 al 1992 dalla Amstrad.

In Europa fu il principale antagonista del Commodore 64 e conquistò un discreto settore di mercato grazie ad un prezzo di listino più economico; infatti le piccole dimensioni, la velocità di calcolo e il prezzo relativamente basso lo resero popolare negli anni ottanta in vari Stati del mondo.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2096.png)

### Translation

The ZX Spectrum is an 8-bit personal home computer developed by Sinclair Research. It was first released in the United Kingdom on 23 April 1982 and went on to become Britain's best-selling microcomputer.

Referred to during development as the ZX81 Colour and ZX82, it was launched as the ZX Spectrum to highlight the machine's colour display, compared with the black and white display of its predecessor, the ZX81. The Spectrum was released as eight different models, altogether they sold over 5 million units worldwide.

The Spectrum was among the first home computers in the United Kingdom aimed at a mainstream audience, similar in significance to the Commodore 64 in the US or the MO5 in France. The introduction of the ZX Spectrum led to a boom in companies producing software and hardware for the machine, the effects of which are still seen.

The machine was officially discontinued in 1992.

# 📠 Alan Turing e la macchina Enigma

# Alan Turing

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2097.png)

Alan Mathison Turing (Londra 1912 – Manchester 1954) è stato un matematico, logico, crittografo e filosofo britannico, considerato uno dei padri dell'informatica e uno dei più grandi matematici del XX secolo.

Il suo lavoro ebbe una vasta influenza sulla nascita della disciplina dell'informatica, grazie alla sua formalizzazione dei concetti di algoritmo e calcolo mediante l'omonima macchina, che a sua volta costituì un significativo passo avanti nell'evoluzione verso il moderno computer.

Per questo contributo è solitamente considerato il padre della scienza informatica e dell'intelligenza artificiale, da lui teorizzate già negli anni trenta del '900, ed anche uno dei più brillanti crittoanalisti che operarono nel Regno Unito durante la seconda guerra mondiale, per decifrare i messaggi scambiati da diplomatici e militari delle Potenze dell'Asse.

Turing lavorò infatti a Bletchley Park, il principale centro di crittoanalisi del Regno Unito, dove ideò una serie di tecniche per violare i cifrari tedeschi, incluso l'utilizzo di una macchina elettromeccanica (chiamata "Bomba") in grado di decodificare codici creati dalla macchina crittografica Enigma. Morì, suicida, a soli 41 anni.

### Translation

Alan Mathison Turing OBE FRS (1912 – 1954) was an English mathematician, computer scientist, logician, cryptanalyst, philosopher, and theoretical biologist. Turing was highly influential in the development of theoretical computer science, providing a formalisation of the concepts of algorithm and computation with the Turing machine, which can be considered a model of a general-purpose computer. He is widely considered to be the father of theoretical computer science and artificial intelligence.

In 1938, he obtained his PhD from the Department of Mathematics at Princeton University. During the Second World War, Turing worked for the Government Code and Cypher School (GC&CS) at Bletchley Park, Britain's codebreaking centre that produced Ultra intelligence. For a time he led Hut 8, the section that was responsible for German naval cryptanalysis. Here, he devised a number of techniques for speeding the breaking of German ciphers, including improvements to the pre-war Polish bombe method, an electromechanical machine that could find settings for the Enigma machine. Turing played a crucial role in cracking intercepted coded messages that enabled the Allies to defeat the Axis powers in many crucial engagements, including the Battle of the Atlantic.

Turing was prosecuted in 1952 for homosexual acts. He accepted hormone treatment with DES, a procedure commonly referred to as chemical castration, as an alternative to prison. Turing died on 7 June 1954 from cyanide poisoning. An inquest determined his death as a suicide, but it has been noted that the known evidence is also consistent with accidental poisoning.

# Enigma

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2098.png)

Enigma fu un dispositivo elettromeccanico per cifrare e decifrare messaggi. Macchina nata da un tentativo di commercializzazione poi fallito, fu ampiamente utilizzata dalle forze armate tedesche durante il periodo nazista e della seconda guerra mondiale. La facilità d'uso e la presunta indecifrabilità furono le maggiori ragioni del suo ampio utilizzo.

Nonostante fosse stata modificata e potenziata nell'arco del suo periodo di utilizzo, un nutrito gruppo di esperti riuscì a violarla dopo essersi impegnato a lungo con questo intento. I primi a decifrarla nel 1932 furono alcuni matematici polacchi: Marian Rejewski, Jerzy Różycki e Henryk Zygalski. Il loro lavoro ha permesso di ottenere ulteriori informazioni sulla sempre più aggiornata macchina dei tedeschi "Enigma", prima in Polonia e, dopo lo scoppio della guerra, anche in Francia e Gran Bretagna. La decrittazione dei messaggi cifrati con Enigma fornì per quasi tutta la seconda guerra mondiale importantissime informazioni alle forze alleate.

### Translation

The Enigma machine is a cipher device developed and used in the early- to mid-20th century to protect commercial, diplomatic, and military communication. It was employed extensively by Nazi Germany during World War II, in all branches of the German military. The Enigma machine was considered so secure that it was used to encipher the most top-secret messages.

The Enigma has an electromechanical rotor mechanism that scrambles the 26 letters of the alphabet. In typical use, one person enters text on the Enigma's keyboard and another person writes down which of the 26 lights above the keyboard illuminated at each key press. If plain text is entered, the illuminated letters are the ciphertext. Entering ciphertext transforms it back into readable plaintext. The rotor mechanism changes the electrical connections between the keys and the lights with each keypress.

The security of the system depends on machine settings that were generally changed daily, based on secret key lists distributed in advance, and on other settings that were changed for each message. The receiving station would have to know and use the exact settings employed by the transmitting station to successfully decrypt a message.

While Nazi Germany introduced a series of improvements to the Enigma over the years, and these hampered decryption efforts, they did not prevent Poland from cracking the machine prior to the war, enabling the Allies to exploit Enigma-enciphered messages as a major source of intelligence.

## Resources

[https://www.youtube.com/watch?v=ybkkiGtJmkM](https://www.youtube.com/watch?v=ybkkiGtJmkM)

# 🦠 Ransomware

Ransomware is a type of malware from cryptovirology that threatens to publish the victim's personal data or perpetually block access to it unless a ransom is paid. While some simple ransomware may lock the system without damaging any files, more advanced malware uses a technique called cryptoviral extortion. It encrypts the victim's files, making them inaccessible, and demands a ransom payment to decrypt them. In a properly implemented cryptoviral extortion attack, recovering the files without the decryption key is an intractable problem – and difficult to trace digital currencies such as paysafecard or Bitcoin and other cryptocurrencies are used for the ransoms, making tracing and prosecuting the perpetrators difficult.

Ransomware attacks are typically carried out using a Trojan disguised as a legitimate file that the user is tricked into downloading or opening when it arrives as an email attachment. However, one high-profile example, the WannaCry worm, traveled automatically between computers without user interaction.

Starting as early as 1989 with the first documented ransomware known as the AIDS trojan, the use of ransomware scams has grown internationally. There were 181.5 million ransomware attacks in the first six months of 2018. This record marks a 229% increase over this same time frame in 2017. In June 2014, vendor McAfee released data showing that it had collected more than double the number of ransomware samples that quarter than it had in the same quarter of the previous year. CryptoLocker was particularly successful, procuring an estimated US$3 million before it was taken down by authorities, and CryptoWall was estimated by the US Federal Bureau of Investigation (FBI) to have accrued over US$18 million by June 2015. In 2020, the IC3 received 2,474 complaints identified as ransomware with adjusted losses of over $29.1 million. The losses could be more than that, according to the FBI. According to a report by SonicWall, there were around 623 million ransomware attacks in 2021.

## Operation

The concept of file-encrypting ransomware was invented and implemented by Young and Yung at Columbia University and was presented at the 1996 IEEE Security & Privacy conference. It is called cryptoviral extortion and it was inspired by the fictional facehugger in the movie Alien. Cryptoviral extortion is the following three-round protocol carried out between the attacker and the victim.

[attacker→victim] The attacker generates a key pair and places the corresponding public key in the malware. The malware is released.

[victim→attacker] To carry out the cryptoviral extortion attack, the malware generates a random symmetric key and encrypts the victim's data with it. It uses the public key in the malware to encrypt the symmetric key. This is known as hybrid encryption and it results in a small asymmetric ciphertext as well as the symmetric ciphertext of the victim's data. It zeroizes the symmetric key and the original plaintext data to prevent recovery. It puts up a message to the user that includes the asymmetric ciphertext and how to pay the ransom. The victim sends the asymmetric ciphertext and e-money to the attacker.

[attacker→victim] The attacker receives the payment, deciphers the asymmetric ciphertext with the attacker's private key, and sends the symmetric key to the victim. The victim deciphers the encrypted data with the needed symmetric key thereby completing the cryptovirology attack.

The symmetric key is randomly generated and will not assist other victims. At no point is the attacker's private key exposed to victims and the victim need only send a very small ciphertext (the encrypted symmetric-cipher key) to the attacker.

Ransomware attacks are typically carried out using a Trojan, entering a system through, for example, a malicious attachment, embedded link in a Phishing email, or a vulnerability in a network service. The program then runs a payload, which locks the system in some fashion, or claims to lock the system but does not (e.g., a scareware program). Payloads may display a fake warning purportedly by an entity such as a law enforcement agency, falsely claiming that the system has been used for illegal activities, contains content such as pornography and "pirated" media.

Some payloads consist simply of an application designed to lock or restrict the system until payment is made, typically by setting the Windows Shell to itself, or even modifying the master boot record and/or partition table to prevent the operating system from booting until it is repaired. The most sophisticated payloads encrypt files, with many using strong encryption to encrypt the victim's files in such a way that only the malware author has the needed decryption key.

Payment is virtually always the goal, and the victim is coerced into paying for the ransomware to be removed either by supplying a program that can decrypt the files, or by sending an unlock code that undoes the payload's changes. While the attacker may simply take the money without returning the victim's files, it is in the attacker's best interest to perform the decryption as agreed, since victims will stop sending payments if it becomes known that they serve no purpose. A key element in making ransomware work for the attacker is a convenient payment system that is hard to trace. A range of such payment methods have been used, including wire transfers, premium-rate text messages, pre-paid voucher services such as paysafecard, and the Bitcoin cryptocurrency.

In May 2020, vendor Sophos reported that the global average cost to remediate a ransomware attack (considering downtime, people time, device cost, network cost, lost opportunity and ransom paid) was $761,106. Ninety-five percent of organizations that paid the ransom had their data restored.

## Mitigation

If an attack is suspected or detected in its early stages, it takes some time for encryption to take place; immediate removal of the malware (a relatively simple process) before it has completed would stop further damage to data, without salvaging any already lost.

Security experts have suggested precautionary measures for dealing with ransomware. Using software or other security policies to block known payloads from launching will help to prevent infection, but will not protect against all attacks As such, having a proper backup solution is a critical component to defending against ransomware. Note that, because many ransomware attackers will not only encrypt the victim's live machine but it will also attempt to delete any hot backups stored locally or on accessible over the network on a NAS, it's also critical to maintain "offline" backups of data stored in locations inaccessible from any potentially infected computer, such as external storage drives or devices that do not have any access to any network (including the Internet), prevents them from being accessed by the ransomware. Moreover, if using a NAS or Cloud storage, then the computer should have append-only permission to the destination storage, such that it cannot delete or overwrite previous backups. According to comodo, applying two Attack Surface Reduction on OS/Kernel provides a materially-reduced attack surface which results in a heightened security posture.

Installing security updates issued by software vendors can mitigate the vulnerabilities leveraged by certain strains to propagate. Other measures include cyber hygiene − exercising caution when opening e-mail attachments and links, network segmentation, and keeping critical computers isolated from networks. Furthermore, to mitigate the spread of ransomware measures of infection control can be applied. Such may include disconnecting infected machines from all networks, educational programs, effective communication channels, malware surveillance and ways of collective participation

### File system defenses against ransomware

A number of file systems keep snapshots of the data they hold, which can be used to recover the contents of files from a time prior to the ransomware attack in the event the ransomware does not disable it.

On Windows, the Volume shadow copy (VSS) is often used to store backups of data; ransomware often targets these snapshots to prevent recovery and therefore it is often advisable to disable user access to the user tool VSSadmin.exe to reduce the risk that ransomware can disable or delete past copies.

On Windows 10, users can add specific directories or files to Controlled Folder Access in Windows Defender to protect them from ransomware. It is advised to add backup and other important directories to Controlled Folder Access.

Unless malware gains root on the ZFS host system in deploying an attack coded to issue ZFS administrative commands, file servers running ZFS are broadly immune to ransomware, because ZFS is capable of snapshotting even a large file system many times an hour, and these snapshots are immutable (read only) and easily rolled back or files recovered in the event of data corruption. In general, only an administrator can delete (but cannot modify) snapshots.

### File decryption and recovery

There are a number of tools intended specifically to decrypt files locked by ransomware, although successful recovery may not be possible. If the same encryption key is used for all files, decryption tools use files for which there are both uncorrupted backups and encrypted copies (a known-plaintext attack in the jargon of cryptanalysis. But, it only works when the cipher the attacker used was weak to begin with, being vulnerable to known-plaintext attack); recovery of the key, if it is possible, may take several days. Free ransomware decryption tools can help decrypt files encrypted by the following forms of ransomware: AES_NI, Alcatraz Locker, Apocalypse, BadBlock, Bart, BTCWare, Crypt888, CryptoMix, CrySiS, EncrypTile, FindZip, Globe, Hidden Tear, Jigsaw, LambdaLocker, Legion, NoobCrypt, Stampado, SZFLocker, TeslaCrypt, XData. The No More Ransom Project is an initiative by the Netherlands' police's National High Tech Crime Unit, Europol’s European Cybercrime Centre, Kaspersky Lab and McAfee to help ransomware victims recover their data without paying a ransom. They offer a free CryptoSheriff tool to analyze encrypted files and search for decryption tools.

In addition, old copies of files may exist on the disk, which has been previously deleted. In some cases, these deleted versions may still be recoverable using software designed for that purpose.

---

# 💯 Matematica

## Funzioni

<aside>
💡 Ogni numero (positivo o negativo) la cui rappresentazione decimale è illimitata e non periodica si dice **irrazionale.**

</aside>

L’insieme formato dall’unione dell’ensieme dei numeri razionali e dell’insieme dei numeri irrazionali viene chiamato insieme dei numeri **reali** e viene indicato con la lettera **R.**

→ **Massimo e minimo di un insieme**

<aside>
💡 Sia *A* un sottoinsieme non vuoto di **R.
a.** Un numero reale *M* si dice **massimo** di *A* quando sono verificate entrambe le seguenti condizioni:

- *M* appartiene ad *A;*
- *M* è un maggiorante di *A.*

**b.** In maniera analoga, un numero reale *m* si dice **minimo** di *A* quando appartiene ad *A* ed è un minorante di *A.*

</aside>

→ **Estremo superiore ed estremo inferiore di un insieme**

<aside>
💡 Sia *A* un sottoinsieme non vuoto di **R.
a.** Si chiama **estremo superiore** di A, se esiste, il minimo dell’insieme dei maggioranti di A.
**b.** Si chiama **estremo inferiore** di A, se esiste, il massimo dell’insieme dei minoranti di A.

</aside>

---

→ **Funzione**

<aside>
💡 Si chiama funzione *f* di **dominio** *A* e **codominio** *B *****una relazione che associa a **ogni** elemento di A **uno e un solo** elemento di B. (si scrive *f: A→ B).*

</aside>

→ **Che cos’è il dominio di una funzione**

<aside>
💡 Il **dominio di una funzione** è l’insieme su cui è definita la funzione, ossia l’insieme di partenza sui cui elementi ha senso valutare la funzione.

</aside>

Per determinare il dominio basta tenere presente le indicazioni riassunte nella seguente tabella:

| Indicazioni per determinare il dominio |
| --- |
| Le operazioni di addizione, sottrazione e moltiplicazioni sono sempre definite, mentre l’operazione di divisione è definita purchè il divisore non sia nullo |
| Un radicale di indice pari è definito solo se il radicando è positivo o nullo, mentre un radicale di indice dispari è sempre definito purchè esista il radicando. |
| Il logaritmo è definito se l’argomento è positivo e la base è positiva e diversa da 1. |
| L’esponenziale (con base positiva costante) è sempre definito purchè esista l’esponente. |
| Seno e coseno sono definiti purchè sia definito il loro argomento, mentre la tangente è definita purchè il suo argomento sia diverso da π/2 + kπ. |
| Arcoseno e arcocoseno sono definiti a condizione che l’argomento sia compreso tra -1 e 1, mentre l’arcotangente è definito purchè sia definito il suo argomento. |

→ **Che cos’è il codominio di una funzione**

<aside>
💡 Il **codominio** di una funzione è l’insieme in cui sono contenute le immagini della funzione.

</aside>

A livello intuitivo il codominio coincide con l’insieme di arrivo, ovvero con l’insieme dei valori che la funzione può assumere.

→ **Classificazione delle funzioni**

Le funzioni si possono classificare in base al tipo di operazioni che compaiono nell’espressione analitica $f(x)$.

- Se compare soltanto un numero finito di operazioni di addizione, sottrazione, moltiplicazione, divisione, elevamento a potenza a esponente razionale o estrazione di radice si dice che la funzione è **algebrica**, altrimenti si dice che è **trascendente.**
- Nell’insieme delle funzioni algebriche si distinguono: funzioni **intere**, nelle quali la variabile indipendente non compare in alcun denominatore, da quelle **frazionarie**; le funzioni **razionali**, nelle quali la variabile indipendendente non compare sotto alcun segno di radice, da quelle **irrazionali.**

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2099.png)

→ **Qual è il dominio di una funzione razionale intera, di una razionale fratta, etc..**

A intuizione lo capisci.

→ **Intersezioni di una funzione con gli assi cartesiani**

Dopo aver determinato il dominio, la “seconda fase” di uno studio elemetnare della funzione consiste nel determinare i suoi eventuali *punti d’intersezione con gli assi cartesiani* e nello studiare il *segno* della funzione.

- Le ascisse degli eventuali punti di intersezione con l’asse x si ottentono ponendo $y = 0$ nell’equazione che definisce la funzione, ossia risolvendo l’equazione $f(x) = 0$; essi si dicono **zeri** della funzione.
- il punto di intersezione con l’asse y esiste a condizione che la funzione sia definita per $x = 0$; l’ordinata del punto di intersezione si calcola semplicemente ponendo $x = 0$ nell’equazione che definisce la funzione, ossia calcolando $f(0)$.
- Lo studio del segno consiste nello stabilire per quali valori di $x$ risulta $f(x)<0$  e per quali risulta $f(x) > 0$. Si risolve perciò la disequazione $f(x) > 0$ che individua gli intervalli dove la funzione è *positiva* e dove è *negativa.*

→ **Funzioni pari e dispari**

<aside>
💡 Sia data una funzione $y = f(x)$ avente dominio $D$, tale che per ogni $x ∈ D$ anche $-x ∈ D$.
**a.** Se risulta $f(-x) = f(x)$ per ogni $x ∈ D$ la funzione si dice **pari** e il suo grafico è simmetrico rispetto all’asse $y$.
**b.** Se invece $f(-x) = -f(x)$ per ogni $x ∈ D$ la funzione si dice **dispari** e il suo grafico è simmetrico rispetto all’origine.

</aside>

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20100.png)

→ **Funzioni crescenti, decrescenti, non decrescenti, non crescenti**

→ Funzioni strettamente crescenti e strettamente decrescenti

<aside>
💡 Sia $I$ un sottoinsieme del dominio della funzione $y = f(x)$.
**a. $f$** si dice **strettamente crescente** in $I$ se:
$x_1 < x_2 => f(x_1) < f(x_2)$, per ogni $x_1, x_2 ∈ I$
**b.** $f$ si dice **strettamente decrescente** in $I$ se:
$x_1 < x_2 => f(x_1) > f(x_2)$, per ogni $x_1, x_2 ∈ I$

</aside>

→ Funzioni crescenti e decrescenti in senso lato

<aside>
💡 Sia $I$ un sottoinsieme del dominio della funzione $y = f(x)$.
**a. $f$** si dice **crescente in senso lato** in $I$ se:
$x_1 < x_2 => f(x_1) <= f(x_2)$, per ogni $x_1, x_2 ∈ I$
**b.** $f$ si dice **strettamente decrescente** in $I$ se:
$x_1 < x_2 => f(x_1) >= f(x_2)$, per ogni $x_1, x_2 ∈ I$

</aside>

→ Funzione periodica

<aside>
💡 Una funzione $f: D$ → $R$ si dice **periodica** se e solo se esiste un numero $T>0$ tale che $f(x) = f(x+T)$ per ogni $x ∈ D$.

</aside>

Il minimo valore di *T*, se esiste, per cui è verificata questa proprietà si dice **periodo** (minimo) della funzione $f$.

→ Funzione invertibile

<aside>
💡 Si dice $f$ una funzione **invertibile** solo se esiste una **corrispondenza iunivoca** tra il dominio della funzione e il suo insieme immagine.

</aside>

In tal caso si chiama funzione **inversa** la funzione che associa a ciascun elemento dell’immagine di $f$ la sua (unica) controimmagine.

## I limiti

→ Asintoto verticale

<aside>
💡 Si dice che la retta di equazione $x = x_0$ è un **asintoto verticale (bilatero)** per la funzione $**y = f(x)$**  se, al tendere di $x$ a $x_0$, con $x ∈ R$, la funzione tende a $- \infin$ o a $+\infin$ o a $\infin$.

</aside>

→ Asintoto orizzontale

<aside>
💡 Si dice che la retta di equazione $y = l$ è un **asintoto orizzontale** per la funzione $**y = f(x)$**  quando il limite della funzione per $x$ che tende a $- \infin$ o a $+\infin$ o a $\infin$ è uguale a $l$.

</aside>

→ **Limiti delle funzioni elementari**

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20101.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20102.png)

**→ Teoremi sui limiti e relative forme indeterminate**

- Teorema del **confronto**
    
    L’idea di base di questo teorema è che se il grafico di una funzione $f(x)$ è compreso tra quello di due funzioni $g(x) , h(x)$ in un intorno di $x_0$ e le due funzioni $g(x), h(x)$ hanno lo stesso limite per $x \to x_0$, allora anche la funzione $f(x)$ ammette lo stesso limite per $x \to x_0$.
    
    <aside>
    💡 Siano $f(x), g(x), h(x)$ tre funzioni tali che esiste un intorno $V$ di $x_0 ∈ R^*$ per ogni $x$ del quale (eccetto al più $x_0$) tutte e tre le funzioni sono definite e risulta:
    
    $g(x)\le f(x) \le h(x)$
    
    Se $\lim_{x\to x_o} g(x)$ = $\lim_{x\to x_o} h(x) = l$ con $l ∈ R$, 
    allora anche $\lim_{x\to x_o} f(x) = l$
    
    </aside>
    

- Teorema del **confronto 2**
    
    <aside>
    💡 Siano $f(x)$ e $g(x)$ due funzioni in un intorno di $x_0 ∈ R^*$ tali che, per ogni $x$ di questo intorno (eccetto al più $x_0$), risulta $f(x) \ge g(x).$
    Se $\lim_{x\to x_0} g(x) = + \infty$, allora anche $\lim_{x\to x_0} f(x) = + \infty$.
    
    </aside>
    
- Teorema del **confronto 3**
    
    <aside>
    💡 Siano $f(x)$ e $g(x)$ due funzioni in un intorno di $x_0 ∈ R^*$ tali che, per ogni $x$ di questo intorno (eccetto al più $x_0$), risulta $f(x) \le g(x).$
    Se $\lim_{x\to x_0} g(x) = - \infty$, allora anche $\lim_{x\to x_0} f(x) = - \infty$.
    
    </aside>
    

 

- Teorema di **esistenza del limite per le funzioni monòtone**
    
    <aside>
    💡 Sia $f(x)$ una funzione monòtona (in senso stretto o lato) in un intervallo $(a, b)$; allora esistono sempre, finiti o infiniti, i limiti di $f(x)$ per $x \to a^+$ e per $x \to b^-$.
    
    </aside>
    
- Teorema di **unicità del limite**
    
    <aside>
    💡 Se una funzione$f(x)$ ammette limite per $x \to x_0$ con $x_0 ∈ R^*$, questo limite è unico.
    
    </aside>
    

- Teorema della **permanenza del segno**
    
    <aside>
    💡 Se per $x \to x_0$ con $x_0 ∈ R^*$, la funzione $f(x)$ ammette limite finito $l$, positivo (negativo), allora esiste un intorno di $x_0$ per ogni $x$ del quale, eccetto al più $x_0$, $f$ è positiva (negativa).
    
    </aside>
    

→ **Forme indeterminate**

<aside>
💡 $+ \infty - \infty$, $0 \cdot \infty$, $\frac{\infty}{\infty}$, $\frac{0}{0}$

</aside>

Ciò non significa che in questi casi il limite sia indeterminato o non si possa calcolare, ma solo che il risultato del limite può essere qualsiasi e non esiste nessun teorema che permetta di stabilirlo a priori: occorre analizzare la situazione caso per caso.

→ **Risoluzione di alcune forme indeterminate**

- Limite per x che tende a infinito di un polinomio
    
    Le funzioni *polonomiali* sono definite e continue in **R**, quindi si può incorrere in forme di indecisione solo nel calcolo di limiti per $x \to \pm \infty$.
    
    In questi casi ci si può imbattere in una forma di indecisione del tipo $+ \infty -\infty$.
    
    <aside>
    💡 Per calcolare il limite di un polinomio per $x \to \pm \infty$  **basta calcolare il limite del suo termine di grado massimo.**
    
    </aside>
    

- Limite per x che tende a infinito del rapporto tra due polinomi
    
    <aside>
    💡 Per calcolare il limite del rapporto di due polinomi per $x \to \pm \infty$ basta calcolare **il limite del rapporto dei loro termini di grado massimo.**
    
    </aside>
    

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20103.png)

## Continuità

→ Definizione di funzione continua in un punto

<aside>
💡 Sia $f$ una funzione definita in un intorno (completo) di $x_0$; se $\lim_{x \to x_0} f(x) = f(x_0)$, la funzione $f$ si dice **continua** in $x_0$.

</aside>

Se solo uno dei due limiti, da destra o da sinistra, di una funzione $f$ per $x \to x_0$ coincide con $f(x_0)$, si parla di **continuità da destra** o **da sinistra:**

- $f$  è **continua da destra** in $x_0$ se $\lim_{x \to x_0^+} f(x) = f(x_0)$;
- $f$  è **continua da sinistra** in $x_0$ se $\lim_{x \to x_0^-} f(x) = f(x_0)$

→ Funzioni continue in un intervallo

- Teorema di **esistenza degli zeri**
    
    <aside>
    💡 Sia $f$ una funzione definita e **continua** in un intervallo **chiuso e limitato** [a, b].
    Se $f(a) * f(b) <0$, allora la funzione ammette **almeno uno zero** in (a, b), ossia esiste un punto $x_o \in (a, b)$ tale che $f(x_0) = 0$.
    
    </aside>
    

- Teorema di **Weierstrass**
    
    <aside>
    💡 Sia $f$ una funzione **continua** in un **intervallo chiuso e limitato** [a,b];
    allora $f$ ammette **massimo M** e **minimo m** in [a,b], ossia esistono $x_1, x_2 \in [a,b]$ tali che:
    $f(x_1) \le f(x) \le f(x_2)$  $\forall x \in [a,b]$
    
    </aside>
    

- Teorema dei **valori intermedi**
    
    <aside>
    💡 Una funzione $f$ **continua** in un intervallo **chiuso e limitato** [a,b] assume tutti i valori compresi fra il suo minimo *m* e il suo massimo *M* in [a,b].
    In altre parole, per ogni $k \in (m, M)$ esiste $x_0 \in [a,b]$ tale che $f(x_0) = k$.
    
    </aside>
    

→ Punti singolari 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20104.png)

## Derivata

→ Definizione e suo significato geometrico

<aside>
💡 Una funzione di equazione $y = f(x)$, definita in un intorno (completo) di $x_0$, si dice **derivabile** in $x_0$ se :

$\lim_{h \to 0} \frac{f(x_0 + h) - f(x_0)}{h}$

**esiste** ed è **finito**.
Questo limite prende il nome di **derivata prima** di $f$ in $x_0$ e si indica con il simbolo $f' (x_0)$.

</aside>

La derivata, geometricamente parlando, rappresenta il coefficente angolare della retta tangente al punto del grafico della funzione.

→ Derivate di funzioni elementari

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20105.png)

→ Punti di non derivabilità

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20106.png)

→ Il differenziale

Consideriamo una funzione derivabile $y = f(x)$ e supponiamo che la variabile indipendente $x$ subisca una piccola variazione $\Delta x$.

<aside>
💡 Se $y = f(x)$ è una funzione derivabile in $x$, la variazione $\Delta y$ subita da $y$ quando $x$ subisce una piccola variazione $\Delta x$ è approsimativamente uguale a $f'(x) \Delta x$; in simboli:
$\Delta y \approx f'(x) \Delta x$

</aside>

In altre parole:

<aside>
💡 Se $y = f(x)$  è una funzione derivabile in $x$, il **differenziale** della funzione $f$ relativo al punto $x$ e all’incremento $dx$, indicato con $dy$, è così definito:
$dy = f'(x) dx$

</aside>

→ Punti stazionari, massimi e minimi relativi

**Massimo relativo**

<aside>
💡 Si dice che $x_0$ è un **punto di massimo relativo (o locale)** per una funzione $f$ di dominio $D$ se esiste un intorno di $I$ di $x_0$ tale che:
$f(x) \le f(x_0)$  per ogni $x \in I \cap D$
Il valore $M$ assunto dalla funzione in $x_0$, cioè $f(x_0)$, è detto **massimo relativo** della funzione.

</aside>

**Minimo relativo**

<aside>
💡 Si dice che $x_0$ è un **punto di minimo relativo (o locale)** per una funzione $f$ di dominio $D$ se esiste un intorno di $I$ di $x_0$ tale che:
$f(x) \ge f(x_0)$  per ogni $x \in I \cap D$
Il valore $m$ assunto dalla funzione in $x_0$, cioè $f(x_0)$, è detto **minimo relativo** della funzione.

</aside>

**Massimo assoluto**

<aside>
💡 Si dice che $x_0$ è un **punto di massimo assoluto (o globale)** per una funzione $f$ di dominio $D$ se risulta:
$f(x) \le f(x_0)$  per ogni $x \in  D$
Il valore $f(x_0)$, è detto **massimo assoluto** della funzione.

</aside>

**Minimo assoluto**

<aside>
💡 Si dice che $x_0$ è un **punto di minimo assoluto (o globale )** per una funzione $f$ di dominio $D$ se risulta:
$f(x) \ge f(x_0)$  per ogni $x \in D$
Il valore $f(x_0)$ è detto **minimo assoluto** della funzione.

</aside>

→ **Teorema di Fermat**

<aside>
💡 Sia $f$ una funzione definita in un intervallo [a,b] e sia $c$ un punto **interno** ad [a,b], in cui $f$  è **derivabile**.
Se $f$ ha in $c$ un punto di **estremo relativo**, allora $f'(c) = 0$.

</aside>

**Punto stazionario**

<aside>
💡 Se una funzione $f$ è derivabile in $c$ e $f'(c) = 0$, si dice che $c$ è un **punto stazionario** della funzione $f$.

</aside>

Il teorema di Fermat esprime una condizione *necessaria* ma non *sufficiente* perchè un punto *c* sia di estremo relativo.

→ **Teorema di Rolle**

<aside>
💡 Sia $f$ una funzione che soddisfa le seguenti ipotesi:
a. $f$ è derivabile nell’intervallo chiuso [a,b];
b. $f$ è derivabile nell’intervallo aperto (a,b);
c. $f(a) = f(b)$.
Allora esiste almeno un punto $c \in (a,b)$ per cui $f'(c) = 0$.

</aside>

→ **Teorema di Lagrange**

<aside>
💡 Sia $f$ una funzione che soddisfa le seguenti condizioni:
a. $f$ è continua nell’intervallo chiuso [a,b];
b. $f$  è derivabile nell’intervallo aperto (a,b);
Allora esiste almeno un punto $c \in (a,b)$ tale che $f'(c) = \frac{f(b) - f(a)}{b-a}$

</aside>

→ Primo corollario

<aside>
💡 Sia $f$ una funzione **derivabile** in un **intervallo** *I* e tale che $f'(x) = 0$ per ogni $x \in I$; allora $f$ è costante in $I$.

</aside>

→ Secondo corollario

<aside>
💡 Se $f$ e $g$ sono due funzioni **derivabili** in un **intervallo** $I$ e tali che $f'(x) = g'(x)$ per ogni $x \in I$, allora esse differiscono per una costante $c \in R$, cioè:
$f(x) = g(x) +c$ per ogni $x \in I$.

</aside>

→ Funzioni crescenti e decrescenti

**Criterio di monotonia per le funzioni derivabili**

<aside>
💡 Sia $f$ una funzione derivabile in un intervallo $I$:
a. se $f'(x) > 0$  per ogni $x \in I$, allora $f$ è strettamente **crescente** in $I$.
b. se $f'(x) < 0$ per ogni $x \in I$, allora $f$ è strettamente **decrescente** in $I$.

</aside>

**Criterio per l’analisi dei punti stazionari mediante la derivata prima**

<aside>
💡 Sia $f$ una funzione continua in un intorno di $I$ di $x_0$, e derivabile in $I$ tranne al più in $x_0$:
**a**. se esistono un intorno sinistro di $x_0$ in cui $f' > 0$ e un intorno destro in cui $f'<0$, allora $x_0$ è un punto di **massimo relativo** per $f;$
**b**. se esistono un intorno sinistro di $x_0$ in cui $f' < 0$ e un intorno destro in cui $f'>0$, allora $x_0$ è un punto di **minimo relativo** per $f$.

</aside>

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20107.png)

→ Funzioni concave, convesse, punti di flesso

**Funzione convessa**

<aside>
💡 Una funzione $f$ si dice **convessa** (o con la concavità verso l’alto) in un intervallo $I$ se per ogni coppia di punti $x_1, x_2 \in I$ la corda che congiunge i punti di coordinate $(x_1, f(x_1))$ e $(x_2, f(x_2))$ è **al di sopra** del grafico di $f$.

</aside>

**Funzione concava**

<aside>
💡 Una funzione $f$ si dice **concava** (o con la concavità verso il basso) in un intervallo $I$ se per ogni coppia di punti $x_1, x_2 \in I$ la corda che congiunge i punti di coordinate $(x_1, f(x_1))$ e $(x_2, f(x_2))$ è **al di sotto** del grafico di $f$.

</aside>

> Sia una funzione derivabile due volte in un intervallo $I$.
**a.** Se $f''(x) >0$ per ogni $x \in I$, allora $f$ è convessa in $I$.
**b.** Se $f''(x) < 0$ per ogni $x \in I$, allora $f$ è concava in $I$.
> 

**Punti di flesso**

<aside>
💡 Data una funzione $f$, sia $x_0$ un punto in cui $f$ è derivabile o al più $f$ presenta tangente verticale.
Il punto $x_0$ si dice **flesso** se esiste un intorno destro di $x_0$ in cui $f$ è convessa (concava) e un intorno sinistro di $x_0$ in cui $f$ è concava (convessa).

</aside>

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20108.png)

**Condizione necessaria per un punto di flesso**

<aside>
💡 Sia $f$ una funzione definita in un intervallo $I$ e sia $x_0$ un punto interno a $I$ in cui $f$ è derivabile due volte. Se $x_0$ è un punto di flesso, allora $f''(x) = 0$

</aside>

Questa è necessaria ma non sufficiente a garantire che $x_0$ sia un punto di flesso.

Questa affermazione non è invertibile.

→ **Teorema di de l’Hopital**

Esiste qualche legame tra il limite per $x \to x_0$ del rapporto $\frac{f(x)}{g(x)}$ tra due funzioni $f$ e 

$g$ e il limite per $x \to x_0$ del rapporto delle loro derivate, ossia $\frac{f'(x)}{g'(x)}$?

La risposta è affermativa ed è espressa nel seguente teorema

<aside>
💡 Siano $f$ e $g$ due funzioni derivabili in un intorno $I$ di $x_0 \in R$, eccetto al più $x_0$, e siano verificate le seguenti ipotesi:
**a. $\lim_{x \to x_0} f(x) = \lim_{x \to x_0} g(x) = 0$ 
oppure $\lim_{x \to x_0} f(x) = \pm \infty$ e $\lim_{x \to x_0} g(x) = \pm \infty$.

b. $g'(x) \ne 0$** per ogni $x \in I$, con $x \ne x_0$

**c.** esiste $\lim_{x \to x_0} \frac{f'(x)}{g'(x)}$

Allora esiste anche $\lim_{x \to x_0} \frac{f(x)}{g(x)}$ e si ha: $\lim_{x \to x_0} \frac{f(x)}{g(x)} = \lim_{x \to x_0} \frac{f'(x)}{g'(x)}$

</aside>

## Integrali

→ Primitiva

<aside>
💡 Una funione $F$ si dice **primitiva** di una funzione $f$ in un intervallo $I$ se è derivabile in $I$ e per ogni $x \in I$ la sua derivata in $x$ è uguale a $f(x)$, cioè se:
$F'(x) = f(x)$ per ogni $x \in I$

</aside>

Se $F$ è una primitiva della funzione $f$ in un **intervallo** $I$, allora l’insieme di tutte e sole le primitive di $f$ in $I$  è costituito dalle funzioni:

$G(x) = F(x) +c$    al variare di $c$ nell’insieme dei numeri reali

→ Integrale indefinito

<aside>
💡 L’insieme di tutte le primitive di una funzione $f$ si dice **integrale indefinito** della funzione $f$ e si indica con il simbolo:
$\int f(x) dx$
che si legge “integrale indefinito di $f(x)$ in $dx$”.

</aside>

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20109.png)

→ Integrali immediati

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20110.png)

→ Linearità dell’integrale indefinito

L’integrale della somma di due funzioni è la somma degli integrali delle due funzioni, e l’integrale del prodotto di una funzione per una *costante* è il prodotto della costante per l’integrale della funzione:

<aside>
💡 **a. $\int[f(x) + g(x)] dx = \int f(x) dx+ \int g(x) dx$
b. $\int k \cdot f(x) dx = k\cdot \int f(x) dx$**  per ogni $k \in R$

</aside>

→ Integrazione per scomposizione

Esso consiste nel cercare di scrivere la funzione da integrare, se possibile, sotto forma di *combinazione lineare* delle funzioni elementari di cui sopra riportata la tabella.

L’integrale può così essere calcolato sfruttando le proprieta di linearità.

In poche parole si cerca di riscrivere la funzione da integrare come la somma di più funzioni elementari per rendere il calcolo più semplice.

→ Integrazione di funzioni **composte**

In pratica, le regole di integrazione delle funzioni elementari possono essere generalizzate al caso in cui l’argomento della funzione integranda non è $x$ ma $f(x)$,  *a patto che la funzione integranda sia moltiplicata per $f'(x)$.*

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20111.png)

→ Integrazione per **sostituzione**

Si basa sulla seguente formula:

> $\int f(x) dx = \int f(g(t))g'(t) dt$    con $x = g(t)$
> 

Per calcolare $\int f(x) dx$ mediante il **metodo di sostituzione** si procede come segue:

<aside>
💡 **1.** si pone $x = g(t)$ e si calcola $dx = g'(t)$;
**2.** si riscrive l’integrale in termini di $t$, sostituendo $g(t)$ al posto di $x$ e $g'(t) dt$ al posto di $dx$, e si calcola l’integrale nella variabile $t$ così ottenuto;
**3.** si ritorna infine alla variabile $x$, eseguendo sul risultato la sostituzione inversa.

</aside>

→ Integrazione per **parti**

In base alla regola di derivazione del prodotto di due funzioni, si ha:

> $D[f(x) \cdot g(x)] = f'(x) \cdot g(x) + f(x) \cdot g'(x)$
> 

In termini di integrali indefiniti otteniamo:

> $\int [f'(x) \cdot g(x) + f(x) \cdot g'(x)] dx = f(x) \cdot g(x)$
> 

Ovvero:

> $\int f'(x) \cdot g(x)dx + \int f(x) \cdot g'(x) dx = f(x) \cdot g(x)$
> 

Da cui ricaviamo:

> $\int f(x) \cdot g'(x) dx=  f(x) \cdot g(x) - \int f'(x) \cdot g(x)dx$
> 

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20112.png)

## L’integrale definito

<aside>
💡 PROBLEMA
Consideriamo una funzione $y = f(x)$, continua e positiva (o nulla) nell’intervallo [a,b].
Come possiamo definire il concetto di area per la regione di piano, detta **trapezoide**, limitata dal grafico della funzione, dall’asse x e dalle rette di equazioni $x = a$ e $x = b$?

</aside>

Definiamo degli opportuni rettangoli, sommando l’area dei quali riusciremo ad approssimare ciò che intuitivamente riteniamo essere l’area del trapezoide.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20113.png)

→ Il concetto di integrale definito (**somma di Riemann**)

<aside>
💡 Sia $f: [a,b] \to R$. Consideriamo i punti:
$a = x_0, x_1, x_2, ... , x_{n-1}, x_n = b$
che suddividano l’intervallo [a,b] in *n* intervalli aventi la stessa ampiezza, uguale a:
$\Delta x = \frac{b-a}{n}$
Scelto in ciascuno degli *n* intervalli $[x_{i-1}, x_i]$ un punto arbitrario $c_i$, chiamiamo **somma di Riemann** della funzione $f$ nell’intervallo [a,b] la somma:
$S_n = \displaystyle\sum_{i = 1}^n f(c_i) \Delta x$

</aside>

Se è una funzione continua, si potrebbe dimostrare che $\lim_{n \to + \infty} S_n$ esiste finito ed è **indipendente dalla scelta dei punti** $c_i$.

Ha senso perciò dare questa definizione:

→ Integrale definito

<aside>
💡 Sia $f: [a,b] \to R$ una funzione continua.
Si chiama **integrale definito** della funzione $f$ nell’intervallo [a,b] il $\lim_{n \to + \infty} S_n$, essendo $S_n$ una somma di Riemann della funzione $f$ nell’intervallo [a,b].
L’integrale definito viene indicato con il simbolo:
$\int_{a}^b f(x) dx$
E si legge “integrale da *a* a *b* di $f(x)$ in $dx$”.

</aside>

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20114.png)

→ Proprietà dell’integrale definito

- L’integrale definito, così come l’integrale indefinito, gode delle proprietà di linearità (somma e moltiplicazione).

- Additività rispetto all’intervallo di integrazione:
    
    <aside>
    💡 Per ogni $a,b,c \in R$ risulta:
    $\int_{a}^b f(x) dx = \int_{a}^c f(x) dx + \int_{c}^bf(x) dx$
    
    </aside>
    
- Monotonia rispetto alla funzione integranda
    
    <aside>
    💡 Se $f$ e $g$ sono due funzioni continue nell’intervallo [a,b] e $f(x) \le g(x)$ per ogni $x \in [a,b]$, allora:
    $\int_{a}^b f(x) dx \le \int_{a}^b g(x) dx$
    
    </aside>
    
- Valore medio di una funzione
    
    <aside>
    💡 Data una funzione $f$, continua nell’intervallo [a,b], definiamo **valore medio** della funzione $f$ nell’intervallo [a,b] il numero:
    $\frac{1}{b-a} \int_{a}^b f(x) dx$
    
    </aside>
    
    Perciò se $f$ è continua in [a,b] esiste un numero $c \in [a,b]$ tale che $f(c)$  è uguale al valore medio della funzione in [a,b], ossia tale che: $f(c) = \frac{1}{b-a} \int_{a}^b f(x) dx$
    

→ La funzione integrale

Supponiamo che $f$ sia una funzione continua in un intervallo [a,b]; per ogni $x \in [a,b]$ la funzione $f$ è continua nell’intervallo [a,x], quindi possiamo definire l’integrale di $f$ su [a,x]:

> $\int_{a}^x f(t) dt$
> 

Questo integrale, una volta fissato *a*, dipende univocamente dalla variabile *x*, pertanto è possibile definire una nuova funzione, detta **funzione integrale**, che associa a ogni $x \in [a,b]$ il valore dell’integrale.

<aside>
💡 Sia $f$ una funzione continua su [a,b]; si chiama **funzione integrale** di $f$ la funzione $F:[a,b] \to R$ definita da:
$F(x) = \int_{a}^x f(t) dt$

</aside>

→ Teorema fondamentale del calcolo integrale

<aside>
💡 Sia $f$ una funzione continua su [a,b] ed $F:[a,b] \to R$ la funzione integrale associata a $f$ (relativa al punto *a*), definita da:
$F(x) = \int_{a}^x f(t) dt$
Allora la funzione $F$ è derivabile (quindi anche continua) in [a,b], e risulta:
$F'(x) = f(x)$  per ogni $x \in [a,b]$

</aside>

→ Calcolo dell’integrale definito

Il calcolo di un integrale definito avviene di solito sulla base del seguente teorema, che recupera la nozione di *primitiva* di una funzione:

<aside>
💡 Sia $f(x)$ una funzione continua in [a,b], e sia $F(x)$ una sua qualsiasi **primitiva** in [a,b], allora:
$\int_{a}^b f(x) dx = F(b) - F(a)$

</aside>

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20115.png)

→ Applicazioni geometriche dell’integrale definito: **aree**

Abbiamo visto che $\int_{a}^b f(x) dx$ rappresenta l’area con segno della regione di piano (trapezoide) limitata dal grafico della funzione $y = f(x)$.

Ci poniamo ora il problema di determinare l’area della regione piana limitata dai grafici di *due* funzioni $y = f(x), y = g(x)$ nell’intervallo [a,b].

<aside>
💡 Siano $f$ e $g$ due funzioni continue in [a,b], tali che $f(x) \ge g(x)$  per ogni $x \in [a,b]$.
Allora l’**area** della regione di piano limitata dai grafici di $f$ e $g$ nell’intervallo [a,b] è data da:
$\int_{a}^b [f(x) - g(x)] dx$

</aside>

In altre parole basterà eseguire la differenza degli integrali tra la funzione che “sta sopra” e la funzione che “sta sotto” in un determinato intervallo [a,b].

---

# 🏛️ Letteratura

# Autori e date

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20116.png)

---

# 😔 Giacomo Leopardi

# Biografia

<aside>
🐣 A **Recanati,** nel 1798 nasce Giacomo Leopardi, primo genito di una stirpe nobile.

</aside>

Il padre, il conte Monaldo Leopardi, è un **erudito** che attribuisce allo studio un valore sommo ed educa i propri figli a trascorrere nella **ricca biblioteca di famiglia** gran parte del tempo fin dalla primissima infanzia.

La madre, la marchesa Adelaide Antici, è una donna **dura e severa** con i suoi figli e si occupa con rigore dell’amministrazione economica della famiglia.

Per questa ragione e per la **rigida educazione religiosa** ricevuta, Adelaide rinuncia poco più che ventenne alla propria giovinezza e si consacra a due occupazioni esclusive: appianare i debiti familiari e dedicarsi a pratiche devote.

**Giacomo** si distingue molto presto dai fratelli, impiegando negli studi una **passione smodata** e dimostrando un **talento straordinario**; quando il ragazzo compie quattordici anni il prete precettore che era stato suo maestro smette le sue lezioni perchè non aveva più niente da insegnarli.

Dagli appunti trovati nelle sue carte, probabilmente annotati intorno ai vent’anni, emerge la figura di un fanciullo **disposto alla fantasia, curiosissimo** di tutto.

Giacomo ricorda il suo **desiderio di primeggiare** tra i fratelli e il suo **odio per la tirannide.**

Trova spazio l**’apprensione per chiunque soffra**, che lo fa fuggire quando sente rimproverare a voe alta qualche servitore di casa o gli fa sperare che un ragazzetto guardato dalla finestra di casa risparmi la lucciola che gli si è posata addosso.

La reclusione genera nel giovane Giacomo **desideri di vedere il mondo.**

Questa intensa vita interiore si esprime non soltanto nella scrittura di **opere erudite e filologiche**, ma anche in **poesia:** ha soltanto diciotto anni quando pubblica *Le rimembranze.*

Il giovane prova una sofferenza sempre più forte per i limiti di **Recanati,** è infatti una **società chiusa** e del tutto arretrata sul piano culturale.

<aside>
💭 Leopardi assume una posizione molto personale **a favore del Classicismo**

</aside>

---

A diciannove anni Leopardi entra in corrispondenza con il letterato Pietro **Giordani.**

Diventa subito per Leopardi un **riferimento intellettuale e affettivo** fondamentale.

Le lettere che Leopardi invia a Giordani testimoniano un’ansiosa esigenza di riconoscimento e la **ricerca di quel calore umano** di cui l’arida educazione familiare lo aveva privato.

In quello stesso 1817 Leopardi inizia ad annotare sentimenti e riflessioni in quaderni che denominerà “**Zibaldone dei pensieri**” e sarà pubblicato soltanto dopo la morte dell’autore.

Intanto però, intorno ai vent’anni, Leopardi comincia a subire nel corpo i **segni della malattia.**

Leopardi attribuisce questa deformazione fisica ai propri studi eccessivi, e **se ne colpevolizza;** egli mostra la propria amarezza per essersi guastato la salute e soprattutto **l’aspetto esteriore**, quello a cui gli uomini attribuiscono maggiore importanza.

In verità gli studiosi hanno ipotizzato che Leopardi sia stato colpito da una malattia batterica, la **tubercolosi ossea.**

Contemporaneamente ai sintomi fisici si manifestano nel giovane anche **afflizioni dell’anima**: gravi e ricorrenti malinconie che lo gettano in uno stato di profonda prostrazione.

A questa infelicità Leopardi tuttavia non si rassegna ma resiste, lotta, chiede aiuto alle persone che ama.

Nel luglio 1819, appena raggiunta la maggiore età, Leopardi **medita la fuga** e si prepara a partire da casa in piena notta, ma viene scoperto.

il **fallimento** da un lato accresce la sua infelicità, dall’altro rende sempre più difficile e contraddittorio il rapporto con il padre.

Leopardi mostra una profonda **avversione per** questa **possessività paterna**, ma al contempo **non riesce a scindere** definitivamente **il suo legame con lui**, e continuerà a scrivergli per tutta la vita.

L’autunno del 1819 è certamente per Leopardi il tempo dell’angoscia per la fine delle sue spernza di libertà, ma è anche la stagione in cui egli compone una delle sue liriche più intenste, *L’infinito.*

Nei tre anni successivi egli non smette di cercare **impieghi e sistemazioni esterne** con l’aiuto dei parenti e degli amici; quando sta un po’ meglio legge, scrive, fa progetti, preso da un crescente desiderio di vita e azione.

Nel novembre **1822** il padre acconsente finalmente a mandarlo a Roma, nel palazzo degli zii materni; la sua speranza è che egli accetti di diventare prete.

Roma però gli appare **frivola e intellettualmente arretrata**, la sua vastità lo respinge, l’**ipocrisia** della corte papale gli ripugna.

Nell’estate del **1823** egli ritorna a Recanati dove si ferma due anni.

Si approfondisce in quel tempo la sua **riflessione filosofica**, che approda a **conclusioni** universalmente **pessimistiche.**

Questa riflessione lo conduce alla scrittura di alcune prose satiriche e filosofiche, le *Operette morali.*

Intanto Leopardi è entrato in corrispondenza con alcuni letterati fiorentini, tra cui **Viesseux.**

Conosce anche l’editore milanese Fortunato Stella, che gli dà infine l’occasione di lasciare Recanati per recarsi a **Milano**.

Inizia così il suo **lungo peregrinare** tra Milano, Bologna, Firenze e Pisa, sempre alla ricerca di una sistemazione.

<aside>
♥️ Nella primavera del 1826 Leopardi conosce a Bologna la **contessa Teresa Carniani Malvezzi,** con la quale inizia una **assidua frequentazione.**

</aside>

Alla fine dell’estate però la contessa tronca bruscamente gli incontri, malvisti dal proprio marito, scrivendo a Leopardi che la conversazione da sola con lui la annoia.

A Firenze, dove trascorre l’estate del 1827, Leopardi sente crescere la propria sofferenza, misurando la propria **distanza dai letterati fiorentini**, fiduciosi nelle riforme e nel progresso.

in settembre partecipa a un fessteggiamento in onore di **Manzoni**, che ha appena pubblicato *I promessi sposi.*

In autunno si trasferisce a **Pisa** dove trascorre un periodo di **temporaneo sollievo:** la sua salute migliora.

Nel maggio di quella stessa primaverea muore di tisi a ventiquattro anni il fratello Luigi.

Le condizioni di salute di Leopardi gli consentono di tornare a Recanati soltanto a novembre.

Il rientro a casa è per Leopardi un **patimento fisico e morale.** In quella triste solitudine dell’estate - autunno 1829 egli scrive alcune tra le sue poesie più importanti che costituiscono i ***Canti pisano - recanatesi.***

Le drammatiche lettere che Leopardi invia ai suoi corrispondenti da Recanati danno luogo a una specie di **generale mobilitazione**: inizilamente gli amici fiorentini sperano che egli possa ottenere con le sue *Operette morali* un cospicuo premio in denaro. Alla fine i letterati fiorentini gli offrono il proprio **sostegno economico per un anno**, così da consentirgli di lasciare Recanati e trovare una stabile sistemazione a Firenze.

Nel 1830 Leopardi parte da Recanati e non vi farà mai più ritorno.

A **Firenze** conduce una **vita meno solitaria**, e frequenta le case degli amici; tra cui anche **Antonio Ranieri.**

Inizia quindi nell’estate del 1830 lo **stretto legame di amicizia** tra Leopardi e Ranieri.

A Firenze Leopardi incontra una nobildonna, la bella trentenne **Fanny Targioni Tozzetti.**

La donna ha la passione di collezionare manoscritti autografi di grandi scrittori e Leopardi gliene procura di rari, facendole spessi visita, e nutrendo per lei un segreto sentimento.

SI crea così una **bizzarra trama amorosa**: Leopardi ama Fanny, la quale ama Ranieri, che ama Pelzet.

Ispirate a questa esperienza sono le poesie del “**Ciclo di Aspasia**”.

A novembre del 1832 Leopardi **scrive alla madre** per ottenere un aiuto economico.

Il sussidio richiesto, che è minimo, viene accordato.

Ranieri rimane privo di denaro e torna in famiglia a Napoli.

Il 2 settembre 1833 i due amici **partono per Napoli**.

La vita di Leopardi qui è inizialmente più **aperta e socievole.**

Per fare fronte alle incessanti **difficoltà economiche** Leopardi tenta di pubblicare una seconda edizione dei *Canti* e una edizione ampliata delle *Operette morali*, ma entrambi i testi venogno sequestrati dalla **censura** del governo borbonico.

Sempre più ammalato, Leopardi si trasferisce nel 1836 con Ranieri e Paolina, a causa di un’epidemia di **colera** che rende del tutto sconsigliabile un ritorno in città, i due amici si trattengono nella villa fino al 1837.

Anche **l’ultima lettera** di Leopardi è rivolta al padre.

<aside>
🪦 La sua morte avviene poco più di due settimane dopo, il 14 giugno 1837 e viene descritta da Ranieri nel suo *Supplemento alla notizia intorno alla vita ed agli scritti di Giacomo Leopardi.*

</aside>

# Brani

→ “Il giardino sofferente” - 32/34

→ “L’infinito” - 53/57

→ “A Silvia” - 63/68

→ “Dialogo di un venditore di almanacchi e di un passeggere” - 157/160

---

# Lo Zibaldone

Leopardi inizia a scrivere opere erudite quando è ancora un bambino.

Una prima svolta nella sua vita intellettuale si ha nel 1815 - 1816, quando abbandona i testi eruditi e scopre le **opere poetiche** degli antichi; affascinato dalla loro bellezza, Leopardi le **traduce.**

Più tardi egli descriverà questa sua giovanile scoperta della poesia come un graduale passaggio “dall’erudizione al bello”, ma non abbandonerà mai la **filologia**: dotato della virtù tipica dei filologi, **l’intuzione**, egli interverrà più volte sui testi antichi per sanare i passi illeggibili o mancanti, proponendo congetture che troveranno conferma dalla scoperta di papiri.

Nel pensiero di Leopardi si affermerà stabilmente la **forza positiva dell’immaginazione.**

Leopardi ha diciannove anni quando decide di tenere memoria delle riflessioni e dei commenti che sente nascere in sé con il procedere degli studi: egli comincia dunque nel 1817 ad **annotarli su fogli sparsi** e senza un ordine prestabilito, ma in bella e nitida grafia.

La raccolta degli appunti e dei pensieri diventa a poco a poco un informe e **smisurato scartafaccio,** senza un titolo o un ordinamento, e le sue stesse crescenti dimensioni rendono sempre più difficile il recupero delle annotazioni sparse.

I temi su cui Leopardi scrive sono molteplici: note di **lingua e filologia, riflessioni filosofiche e letterarie**, accostate una all’altra secondo la **successione spontanea** in cui si presentano alla sua mente.

Questo diario del pensiero proseguirà per circa quindici anni.

Leopardi **cerca** ripetutamente  **di catalogare i pezzi sparsi** ma soltanto nel **1845** uscirà postuma una raccolta di centoundici ***Pensieri.***

La voluminosa cartella di fogli è per Leopardi tanto preziosa che egli la porta **sempre con sé** negli spostamenti città in città; priva di titolo e intestazione rimarrà così, inedita e non organizzata, fino alla morte dell’autore.

Il manoscritto resta nelle mani dell’amico Ranieri, che a sua volta lo lascia in eredità alla **Biblioteca Nazionale di Napoli.**

La parola “Zibaldone” significava ai tempi “insieme confuso di cose”, e in particolare indicava i **quaderni di appunti** in cui gli studiosi erano soliti annotare i passi degli autori letti.

L’opera di Leopardi non si riduce tuttavia alla semplice annotazione di passialtrui, ma si costituisce come una **raccolta di pensieri originali, riflessioni, intuizioni.**

La natura provvisoria dello *Zibaldone* è testimoniata dalla **scrittura, rapida e immadiata**, come per seguire il ritmo veloce del pensiero: talvolta le parole sono abbreviate.

La struttura frammentaria e asistematica dello Zibaldone si deve anche al particolare **metodo di indagine intellettuale** di Leopardi: egli è convinto che l’esame a cui la ragione sottopone lar ealtà non sia sufficiente a cogliere il cuore delle cose, la loro vita essenziale e autentica; essa può essere intesa soltanto attraverso uno sguardo nutrito di **immaginazione e di sentimento.**

Pur nella varietà dei temi dello *Zibaldone* si può dire che l’interesse centrale del pensiero di Leopardi sia la questione della felicità.

Il problema si pone a partire dal suo contrario, cioè dalla bruciante **esperienza dell’infelicità**.
Egli ha vissuto da ragazzo slanci e passioni smisurati, lasciandosi trascinare dalla forza poetica delle sue letture, e ha coltivato imprecisati **sogni di grandezza e di gloria**, ma presto deve scontrarsi con una **realtà ostile** che lo ostacola e lo spegne.

Il pensiero leopardiano passa **dal particolare** al **generale.**

La conclusione è radicalmente negativa: **l’infelicità è la legge universale,** a cui nessun essere vivente può sottrarsi.

Strettamente connesso al problema della felicità è il **rapporto tra natura e ragione**.

Alla natura in generale Leopardi attribuisce spesso una volontà, una specie di **divinità laica e onnipotente.**

Egli considera la natura un **principio buono e scorrevole** e fa invece ricadere sulla ragione la colpa dell’infelicità umana.

Per questo gli uomini antichi erano più felici, perchè più immersi nella **fantasia e nelle illusioni**.

Secondo Leopardi inoltre l’abitudine spegne il piacere.

Nel **1824** compare all’improvviso un **ragionamento radicalmente negativo**, in cui la benignità della natura viene definitivamente abbandonata.

---

# I *Canti*

Le poesie di Leopardi escono per la prima volta a **Firenze** nel **1831** in una raccolta intitolata *Canti.*

Una seconda edizione dei *Canti* corretta e ampliata esce a **Napoli nel 1835.**

Il titolo è volutamente generico, infatti indica per Leopardi **la poesia lirica in generale.**

Il genere lirico è infatti **l’espressione libera dell’animo** dell’uomo, proprio anche di chi non ha cultura, ed è capace di **consolare** attraverso la **bellezza della parola.**

Con il titolo vuole dunque alludere sia all’autonomia dei suoi testi rispetto alle distinzioni metriche tradizionali e alle loro regole, sia alla sua idea della poesia come espressione primaria e autentica dell’uomo.

Si possono individuare nel libro cinque gruppi di testi successivi:

- Canzoni
- Idilli
- Canti pisano - recanatesi
- ciclo di Aspasia
- Ultimi canti

## Canzoni

I **temi** sono **patriottici:** il poeta deplora la decadenza dell’Italia e la diffusa viltà dei popoli nell’età della Restaurazione.

Sono gli anni in cui considera la natura come entità benevola.

Le canzoni sono scritte in una **lingua difficile, alta, densa di figure retoriche.**

Il ritmo è rapido ed energico.

## Idilli

Gli idilli sono **poesie più private e soggettive**, in cui l’infelicità dell’io lirico appare strettamente unita alle vicende esistenziali che lo riguardano.

L’unico conforto al presente freddo e ostile è il **ricordo** del passato, anche se triste, o la forza creatrice dell’**immaginazione**.

Gli idilli sono poesie più brevi delle canzoni, scritte in **endecasillabi sciolti,** con una lingua più semplice e una sintassi meno elaborata.

## Canti pisano - recanatesi

In questi canti è continuo lo scambio tra **parti descrittive e sentimentali e parti riflessive**.

il lettore non ha però mai l’impressione di trovarsi di fronte al freddo ragionamento di un filosof, ma di assistere piuttosto all’**autentica sofferenza** di un uomo che ama disperatamente la pienezza vitale e ne conosce l’illusorietà.

La lingua di questi canti si avvicina a quella degli idilli per **l’indeterminatezza lessicale e la musicalità**, per la compresenza di **parole semplici** e **letterarie**.

A parte da *A Silvia *****Leopardi elabora la cosidetta “**Canzone libera**”, in cui **endecasillabi e settenari si succedono liberamente** in base alle esigenze.

## Ciclo di Aspasia

Il tema unico di questi testi è il **sentimento amoroso** che viene esaminato come una **forza potentissima**.

In questo periodo infatti Leopardi è innamorato della nobildonna **Fanny Targioni Tozzetti.**

Il **sentimento** rivela la sua natura **ingannevole.**

---

# Le Operette Morali

Leopardi ha ventun anni quando comincia a pensare alla scrittura di un’operea letteraria in prosa.

Egli abbraccia infatti il proposito di scrivere un testo che contenga la sua **riflessione filosofica** e la diffonda tra i lettori contemporanei: non però un trattato teorico, bensì un’**opera d’invenzione.**

In questo stesso anno, come testimoniano gli appunto dello *Zibaldone*, matura il **pensiero negativo** riguardo alla condizione umana e al tempo presente.

Il diminutivo “**operette**” allude sia alla dimensione dei testi che compongono l’opera, sia al carattere apparentemente **lieve** e talvolta **scherzoso** della scrittura, mentre l’aggettivo “**morali**” si riferisce al loro **contenuto di pensiero**.

Le *Operette Morali* di Leopardi si presentano come un libro fuori moda, respingente per la sua **filosofia negativa** e scritto in una lingua tanto elevata da potere essere apprezzata da pochi.

Leopardi non resta indifferente all’incomprensione dei lettori, che anzi **patisce** come un vero e proprio **rifiuto personale**; egli infatti ha concentrato in quel libro l’essenza del suo pensiero e della sua vita.

Le incomprensioni e le critiche non scoraggiano tuttavia Leopardi, che continua a investire nel progetto le proprie energie intellettuali e a scrivere **nuovi testi** da inserire nelle edizioni successive.

L’edizione finale delle *Operette morali* costituita da ventiquattro testi, esce **postuma a Firenze**.

Le *Operette Morali* si presentano quindi come un insieme di **testi di lunghezza e forma diverse**, distribuiti nel libro secondo un disegno che esisteva nella intenzioni dell’autore, ma che risulta dififcile ricostruire.

Leopardi insiste sull’**unità filosofica** dell’opera, aggiungendo che la leggerezza della forma è soltanto esteriore, il “ridicolo” non è infatti al servizio di una vana evasione ma è un potente strumento per scardinare i luoghi comuni del pensiero.

Le operette hanno forme molteplici: novelle, racconti mitologici, monologhi, biografie fantasiose.

Molte hanno la struttura del **dialogo**, che consente di mettere a **confronto punti di vista opposti** sulla stessa questione.

I principali temi sono:

- **La teorica del piacere,** desiderato e mai sperimentabile;
- **L’indifferenza della natura;**
- **L’importanza dell’immaginazione.**

L’elemento unificante delle operette è lo **stile ironico**, l’attitudine al sorriso che si applica su tutto, anche sui contenuti più tragici.

La scrittura delle operette è curatissima ed elegante, senza nessuna concessione alla facile comunicabilità.

Leopardi si propone di creare una **nuova lingua italiana**, libera, ricca e varia.

Nella sua scrittura egli cerca la **varietà dei registri**, compreso quello popolare, accosta liberatmente parole che appartengono al passato e al presente.

L’obiettivo dichiarato è di offrire agli italiani un **modello di lingua illustre,** adatta alla scrittura di contenuti alti, che si avvalga delle molteplici potenzialità dell’italiano.

---

# 🏛️ Giosuè Carducci

# Biografia

<aside>
🐣 Nasce il 27 luglio **1835** in provincia di Lucca in una famiglia della media borghesia.

</aside>

Il padre medico liberale e carbonaro trasmette al figlio idee democratiche e filorisorgimentali.

Trascorre l’infanzia in **Maremma**, a contatto con**natura libera e selvaggia** che lascia un forte segno sul suo carattere.

La famiglia si trasferisce a Firenze dove Giosue inizia a frequentare il licelo e dimostra subito una notevole **inclinazione allo studio della retorica e delle lingue classiche**.

Qui conosce Elvira **Menicucci** cui dedica i prima versi d’amore.

Carducci si dedica con impegno e passione agli studi letterari e si laurea in Filosofia e Filologia, nello stesso anno inizia a insegnare nei licei.

<aside>
♥️ Nel 1859 sposa Elivra da cui ha quattro figli: **Beatrice, Laura, Libertà e Dante.**

</aside>

I nomi non sono casuali, dimostra infatti quanto fosse forte l’attaccamento del poeta alla tradizione letteraria.

Nel 1860 ottiene la cattedra di **Letteratura italiano**persso l’Università di Bologna.

Negli stessi anni si avvicina alla **massoneria** (inizialmente divulgare le idee illuministe ma poi si trasformano in gruppi occulti di pressione).

La **delusione per il governo postunitario** lo induce ad assumere posizioni apertamente giacobine e anticlericali, e poi socialiste e anarchiche.

Il 1870 segna per Carducci una svolta sul piano personale e famigliare: muoiono infatti la madre e il giovane figlio **Dante,** eventi che determinano un profondo e duraturo ripiegamento interiore nel poeta.

Nel 1872 Carducci inizia un’intensa realzione amorosa con **Cristofori Piva -** chiamata “Lidia” **,** una donna di grande cultura e una fervente ammiratrice dei versi carducciani.

IL carteggio intercorso tra i due amanti rivela un Carduccio **dolcemnete innamorato.**

Da questa relazione nasce anche un figlio, **Gino**.

La relazione dura fino al **1881** , anno della morte della donna.

Negli ultimi anni della sua vita il poeta si lega invece ad **Annie Vivanti**, una giovane poetessa.

Anche in questo caso un fitto carteggio tra i due testimonia un **legame profondo,** talvolta **conflittuale e tormentato.**

Sul piano politico Carducci abbandona progressivamente le posizioni libertarie e socialiste per avvicinarsi a quelle conservatrici e infine nazionalistiche.

Incontra personalmente i sovrani d’Italia ed è colpito dal fascino della **regina Margherita di Savoia** alla quale dedica l’ode *Alla regine d’Italia.*

Poi si guadagnerà il titolo di “**Poeta Vate dell’Italia Umbertina”**.

Nel 1890 è nominatore **senatore**, quindi **Cavaliere di Gran Croce**.

Nel 1906 vince il **premio Nobel** per la letteratura.

Carducci poi **cura personalmente** l’edizione completa delle sue opere.

<aside>
🪦 Carducci muore il 16 febbraio **1907.**

</aside>

---

## L’ideologia e le opere poetiche

Carducci è stato definito come “poeta della storia” non solo per la presenza massiccia di fatti e personaggi storici all’interno della sua produzione poetica, ma anche perché ha copiuto una **parabola ideologia** che da appassionato repubblicano risorgimentale lo ha visto progessivamente aderire al nazionalismo monarchico.

I mutamenti di pensiero di Carducci testimoniano infatti un’**epoca di transizione.**

All’interno della poesia di Carducci si possono individuare alcuni nuclei tematici costanti:

- il **rimpianto** per il **mondo classico** ormai perduto;
- la rivisitazione dell’**età comunale** come periodo di virtù civile.
- l’esaltazione delle **passioni risorgimentali e patriottiche;**
- la **nostalgia** per i luoghi della giovinezza
- l’incombere della **morte** sulla vita dell’uomo.

Durante il periodo in cui insegna nei lici fonda insieme ad alcuni letterati il gruppo “**Amici pedanti”,** ovvero un gruppo di difensori dei valori e dei modelli della poetica classica.

Inizia così la sua battaglia contro una poesia imitatrice degli autori stranieri.

In questo periodo pubblica le prime raccolte poetiche:

- ***Rime***
- ***Juvenilia***
- ***Levia gravia***

Sono esercizi di stile in cui ciò che conta più di tutto è la **ricercatezza del linguaggio**

La prima poesia carducciana che ottiene risonanza è *L’inno a Satana*.

Si tratta di un esempio di risoluto **anticlericalismo** in cui l’autore arriva a identificare Satana con il **progresso moderno** e la forza rivoluzionaria del lavoro umano.

Sono riconducibili al filone del classicismo anche le poesie di ***Giambi ed Epodi.***

Successivamente le poesie di Carducci subiscono un’**ulteriore evoluzione**, cui contribuiscono anche le vicende biografiche.

A Lidia sono dedicate le liriche di  ***Rime nuove***: il **tema dell’amore** si accompagna a quello del **sogno**, inteso come fuga dal presente e dalla realtà contaminata e corrotta.

Allo stesso periodo delle ***Rime nuove*** risale la composizione delle  ***Odi barbare,*** così intitolate perchè abbandona i metri tradizionali della poesia per riprodurre il **ritmo della poesia greco - latina.**

Si tratta di un **esperimento metrico**, che sarebbe senz’altro sembrato rozzo e “barbaro” ai poeti classici.

Con esso cerca di riprodurre il ritmo della poesia antica, basato su un **sistema metrico quantitativo.**

Carducci tenta con queste raccolta di **restaurare la poesia aulica della classicità.**

***Rime e ritmi*** è pubblicata nel 1899 ed è la raccolta di poesie che consacra Carducci come Poeta Vate.

Nei testi di questa raccolta prevalgono le **odi celebrative** oppure componimenti che inneggiano al **valore della patria.**

## Brani

→ “Alla stazione in una mattina d’autunno” - 68/72

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20117.png)

---

# 🎣 Giovanni Verga

# Biografia

La Sicilia è per Giovanni Verga una **terra interiore**, fondamento della sua formazione intellettuale e umana.

Egli vi trascorre l’infanzia e la giovanizze e ne riceve una **forte impronta culturale**, ma quando capisce che la sua strada è la letteratura desidera intensamente partire.

Nei suoi romanzi e nelel sue novelle la **Sicilia è inizialmente assente**.

Ma a un certo punto, come da una sorgente nascosta, la Sicilia **riemerge**, con i suoi **aspri paesaggi e la sua realtà umana**, spesso la più misera.

Egli tornerà in Sicialia dove vivrà per altri trent’anni ad amministrare le sue terre e a correggere i suoi scritti, deidcandosi a poche nuove opere, fino alla morte.

Questo ritorno non è vissuto da Verga come una rinuncia nè come una sconfitta, ma come un naturale **ricongiungimento alle fonti della sua formazione.**

La famiglia in cui nasce nel 1840 ha remote **origini nobiliari**, il padre vanta una discendenza baronale, mentre la madre è di provenienza borghese e ha ricevuto un’educazione intellettuale.

Le condizioni economiche della famiglia sono tuttavia assai instabili e Verga dovrà fare i conti per tutta la vita con la **mancanza di denaro** e il bisogno di procurarsene.

Da bambino riceve una sommaria formazione da maestri privati di appassionate idee romantiche e patriottiche.

Anche i suoi genitori hanno **orientamenti antiborbonici** e sostengono il processo risorgimentale.

Quando avviene l’unificazione dell’Italia (1861) Verga ha ventuno anni e aderisci volontariamente alla **Guardia Nazionale.**

Sul piano ideologico il giovane accompagna il **sostegno politico all’unità nazionale** con la difesa dei privilegi dei proprietari terrieri meridionali e sostiene queste idee in una serie di **articoli politici.**

A ventitrè anni, dopo la morte del padre, si convince che la sua carriera di scrittore ha bisogno di aira nuova. La destinazione ch elo attrae è Firenze, dove egli spera di trovare stimoli per la propria ispirazione.

Dopo alcuni viaggi si trasferisce nellac ittà e inizia a frequentare gli **ambienti intellettuali e i salotti letterari** più in vista, in cui viene accolto con interesse.

Conosce Luigi **Capuana**, scrittore siciliano che diventerà l’amico di tutta la vita, e stringe **varie relazioni amorose**, ottenendo tra le donne apprezzamenti lusinghieri.

Per tutta la vita Verga giurerà il proprio amore a numerose amanti, riffiutando però di impegnarsi stabilmetne e sollevando talvolta le aspre collere dei mariti offesi.

**L’assillo economico** tormenterà lo scrittore per tutta la vita, assumendo la forma di una vera e propria ossessione: nelle sue lettere sono frequenti i riferimenti al denaro, i calcoli minuti dei diritti editoriali e l’esibizione di una estrema parsimonia.

Le prime opere di Verga non suscitano particolare interesse, mentre per quanto riguarda ***Nedda***, una novella pubblicata da Verga sulla “Rivista italiana”, in cui per la prima volta **l’ambiente è siciliano**, i lettori e la critica si dimostrano interessati.

*Nedda* rappresenta una **innovazione tematica**, ma i modi della narrazione sono ancora tradizionali, sul modello manzoniano, con un **narratore onnisciente** estraneo al mondo rappresentato che giudica e commenta i fatti dal proprio punto di vista.

La vera e propria svolta avviene quattro anni dopo con ***Rosso Malpelo***, la prima novella “verista” di Verga, in cui cambiano radicalmente i modi della narrazione e il racconto viene affidato alle **voci dei personaggi del popolo**, senza l’intervento giudicante di un narratore esterno.

Il modello a cui Verga si ispira è quello del Naturalismo francese di Emile **Zola.**

L’interesse del pubblico per le vicende ambientate nel Sud Italia è favorito in quel tempo anche all’**inchiesta sulla “questione meridionale”** di **Sonnino.**

Le grandi opere veriste di Verga occupano lo spazio di circa un decennio, da *Rosso Malpelo* a *Mastro-don Gesualdo*, ma questa svolta poetica non è da considerarsi stabile né definitiva: accanto ai titoli veristi di romanzi e novelle lo scrittore continua infatti nello stesso periodo a pubblicare **opere di carattere più tradizionale**

Accanto ai romanzi, come abbiamo visto, Verga inizia con *Nedda* a pubblicare **novelle su riviste**, per le quali è più facile e rapido ottenere un **compenso economico**; le riunisce poi periodicamente in raccolte, tra le quali le più importanti e le più vicine alla poetica naturalista di Zola sono ***Vita dei campi***  e ***Novelle Rusticane***.

Subito dopo il successo di *Nedda*, Verga ha iniziato a lavorare a un “bozzetto marinaresco” intitolato *Padron ‘Ntoni*, richiesto dal suo editore per soddisfare la predilezione del pubblico per i temi popolari e siciliani.

Tuttavia, dopo la lettura dei testi di Zola, lo scrittore decide di trasformare la novella in un romanzo e lo intitola *I Malavoglia.*

Nelle sue intenzioni l’opera dovrebbe essere la prima di una **serie di cinque romanzi**, che egli vorrebbe riunire sotto il titolo comunie ***I vinti*** per rapprsentare la medesima condizione di sconfitta esistenziale in tutte le classi sociali, da quelle più misere a quelle privilegiate.

Il **progetto si interrompe** però dopo il secondo romanzo, *Mastro-don Gesualdo*.

*I Malavoglia* ottengono inizialmente uno **scarso successo**, dovuto alla lontananza dal gusto del pubblico della poetica verista, e ciò induce Verga a ritornare ai **temi mondani** con un romanzo tradizionale di ambiente borghese.

Nello stesso 1882, Verga ha l’occasione di fare la **conoscenza di Zola**.

L’incontro non dà seguito a un’amicizia perchè i due autori sono ideologicamente molto lontani.

Mentre si dedica all’elaborazione della sere dei *Vinti*, Verga lavora anche in altre direzioni, ricavando dalle sue novelle **adattamenti per il teatro.**

Al Carignano di Torino ottiene un grande consenso la rappresentazione di ***cavalleria rusticana,*** interpreata dalla celebre Eleonora Duse.

Nel 1890 il musicista Pietro Mascagni ricava dalla stessa vicenda un melodramma di successo, avvalendosi di un libretto non autorizzato dall’autore; Verga ricorre al tribunale ottenendo nel 1893 un consistente riscarcimento in denaro.

Dopo le prime due raccolte di novelle, Verga ne pubblica diverse altre.

Negli ultimi anni della sua vita lo scrittore si dedicherà soprattutto alle **riduzioni teatrali e cinematografiche** delle sue opere, senza però ripetere il successo di *Cavalleria rusticana.*

Con la vittoria processuale contro il musicista risolve finalmente i suoi problemi economici e decide di tornare in Sicialia.

In quello stesso anno, 1893, la rivolta dei cosiddetti “**fasci siciliani**”, gruppi di contadini e minatori in lotta da due anni contro lo sfruttamento dei padroni, viene repressa dal governo con decine di morti.

Anche di fronte a queste violenze Verga si schiera **contro i manifestanti** e plaude alla repressione, Egli non è disposti infatti ad attribuire al popolo alcuna motivazione ideale, considera **naturale la gerarchia che divide la classi sociali** ed è convinto che la **legge dell’utile** sia il motore di ogni rapporto umano.

Negli ultimi anni della sua vita si schiera con i **nazionalisti** a favore delle imprese coloniali italiane e per l’itnervento in guerra dell’Italia e guarda con simpatia all’ascesa del Fascismo, cui non fa in tempo ad aderire perchè muore all’improvviso di trombosi lo stesso anno della marcia su Roma (1922).

---

# La poetica del Verismo

Pur essendo vissuto per molti anni nelle grandi città del Centro - Nord, Verga resta fortemente legato ai **luoghi e alle tradizioni culturali della Siciali**.

In particolare si sente estraneo alla modernizzazione economica a cui il Nord Italia si è avvicinato dopo l’unificazione del paese.

Egli appartiene infatti alla **media proprietà terriera della provincia siciliana**, avversa alla politica protezionistica della Sinistra storica che favorisce le attività imprenditoriali del NOrd e ostacola gli interessi dei latifondisti meridionali.

Al conservatorismo economico si aggiunge in Verga la frustrazione derivata dal **fallimento degli ideali risorgimentali**, da ragazzo egli aveva sostenuto il processo di unificazione dell’Italia schierandosi con le truppe di Garibaldi, ma progressivamente si era accentuata la sua **estranietà** nei confronti dei **partiti al governo** del paese.

Negli anni della maturità la sua visione del mondo si incupisce: tende ad **evidenziare gli aspetti negativi** delle relazioni sociali tra gli uomini, che considera condizionate in primo luogo dalla **legge dell’utile economico.**

Gli individui di ogni classe sociale gli appaiono inevitabilmente coinvolti in una **lotta** brutale **per l’affermazione di sè**: si tratta ai suoi occhi di una **legge naturale**, che non dipende dalle condizioni storiche ed è perciò immutabile.

Verga appare un **isolato**, estraneo ai valori condivisi del suo tempo e sospettoso nei confronti di ogni progresso economico o sociale.

Di fronte a lui non si apre alcuna prospettiva di riscatto, né storico né trascendente, e la sua visione del mondo appare assoggegata a un **pessimismo materialista e assoluto.**

La consapevolezza della **degradazione** e della **miseria delle popolazioni del Sud** accresce il suo pessimismo, senza fare però vacillare in lui la convinzione che **la legge del più forte valga a ogni livello sociale** e che le vittime stesse siano sempre pronte a esercitare la loro prepotenza su chi sta al di sotto di loro.

Poichè considera la violenza e la sopraffazione dati naturali e immodificabili dell’animo umano, egli si limita a reistrarle con lo **sguardo oggettivo dello scienziato**.

La tecnica narrativa di Verga ha adottato fino a questo momento è quella tradizionale (**narratore esterno e onnisciente**); il passaggio ai temi “siciliani” non costituisce una svolta di poetica perchè la tecnica narrativa è ancora quella proprioa della letteratura romantica.

Intorno al 1876 la lettura dei romanzi di Zola è per Verga una specie di rivelazione; egli ammira la sua capacità di rappresentare il modno in modo **diretto** e largamento **documentato**.

L’interesse per la recente letteratura francese è condiviso entustiasticamente anche da Capuana, il primo a usare nei suoi saggi critici la parola “Verismo” per descrivere l’intenzione degli scrittori italiani di **imitare i romanzieri naturalisti francesi e documentare la realtà “dal vero”** rinunciando all’espressione diretta di giudizi e interpretazioni da parte del narratore

Il termine “Verismo” sarà successivamente usato dai critici per designare le caratteristiche specifiche dell’**arte di Capuana e di Verga** e distinguerle da quelle del Naturalismo.

---

Le modalità narrative veriste sono:

- **Prevalenza dei fatti minori e rinuncia al romanzesco**: L’intreccio dei romanzi veristi è costituito da **fatti ordinari**, cioè dagli eventi minori ch eoccupano la vita di ogni giorno.
- **Arretramento del narratore onnisciente, focalizzazione variabile, straniamento:** L’obiettivo fondamentale delle opere veriste di comuntare i fatti così come sono è ottenuto attraverso la cosiddetta “tecnica dell’impersonalità”, tende cioè a **scomparire** la figura del **narratore tradizionale onniscente** che offre al lettore una interpretazione sui fatti e sui personaggi.
- **Minime descrizioni dell’ambiente**: Per realizzare compiutamente l’obiettivo dell’impersonalità Verga **riduce anche sensibilimente le descrizioni dell’ambiente**, il narratore popolare dei *Malavoglia* ad esempio parla come se chi legge fosse presente sulla scena e conoscesse bene i luoghi dell’azione.
- **Assenza di una descrizione introduttiva dei personaggi**: Nelle opere veriste i personaggi **entrano in scena direttamente**, con pochissime parole di introduzione da parte del narratore.
- **Uso di una forma adatta alla materia da rappresentare:** La tecnica versita richiede una **lingua adeguata all’ambiente e ai personaggi** rappresentati. nel romanzo *I Malavoglia*, ad esempio, la narrazione è condotta in una lingua che ha i caratteri del **parlato siciliano.**

Benchè sia ben consapevole del nuovo orientamento che intende seguire nell’arte della narrazione, Verga non scrive un saggio che contenga i principi ispiratori e le regole di composizione del romanzo moderno, ma affida le sue dichiarazioni di poetica a **pochi scritti** che si trovano **a metà tra riflessione teorica e letteratura**.

La sua stagione “verista” dura **poco più di dieci anni**.

La sua evoluzione letteraria non segue pertanto un percorso lineare, ma è fatta di **sperimentazioni e ritorni indietro**, fino al silenzio degli ultimi anni.

# Brani

→ La *Prefazione* ai *Malavoglia -* 112/114

---

# I Malavoglia di Verga e L’Assommoir di Zola

Verga diventa verista dopo la lettura di Zola, in particolare dopo avere conosciuto il romanzo L’Assommoir.

La sua ammirazione per l’autore francese non verrà mai meno e si tradurrà in un proposito di **imitazione delle tecnihce narrative naturaliste** che egli, soprattutto nei Malavoglia, realizzerà in modo ancora più rigoroso rispetto al modello.

Verga accetta del Naturalismo francese **l’attenzione per i dati reali** e la ocncezione della **vita come una lotta** per l’esistenza, ma **non ne condivide la visione fiduciosa.**

Del positivo egli respinge l’idea che la scienza possa indirizzare l’umanità verso un progresso certo e inarrestabile, e ugualmente si sente **estraneo alle idee democratiche e socialiste** di Zola e al suo impegno a migliorare la condizione sociale delle classe popolari.

**Zola** racconta la storia di una **famiglia nel corso delle successive generazioni**: ogni romanzo segue uno o più personaggi della famiglia, in diversi ambienti sociali.

**Verga** si propone un progetto simile, ma con una scala ascensionale: i suoi personaggi appartengono a **classi sociali via via più elevate**.

Sia Zola che Verga realizzano romanzi il cui intreccio è costituito da fatti che appartengono alla **vita di tutti i giorni e rinunciano ai toni enfatici** anche quando descrivono eventi tragici.

Nell’*Assommoir* la reazione di Gervaise, ormai aloclizzata, alla morte del marito Coupeau, ucciso dall’alcol dopo quattro giorni di delirio e conflusioni, viene descritta attraverso uno sguardo crudele e irrisorio, senza accenti di commozione.

Nell’*Assommoir* la descrizione dell’ambiente è ricca di dettagli, tuttavia, per rispettare il principio dell’impersonalità, lo scrittore ricorre allo stratagemme di affidarla a un **personaggio nuovo rispetto al luogo dell’azione**, che da una finestra o da una vetrina ne osserva ogni particolare.

Nei *Malavoglia* invece **le descrizioni sono ridotte al minimo**.

Mentre nell’*Assommoir* i personaggi vengono **introdotti dalla voce narrante**, nei *Malavoglia* **compaiono in scena direttamente** o con minimi cenni di presentazione.

Per raffigurare in modo realistico gli ambienti dei suoi romanzi, **Zola** si avvale del **gergo quotidiano degli operai** parigini; accanto a questa però usa anche un linguaggio di **livello medio** proprio della classe borghese.

**Verga** invece si avvale di una lingua omogenea, che mantiene caratteristiche proprie del **parlato popolare** a tutti i livelli della narrazione, tanto che il lettore ha l’impressione di immergersi integralmente nella realtà rappresentata, come se a narrare i fatti fossero gli stessi protagonisti.

## Brani

→ “La partenza di ‘Ntoni e l’affare dei lupini” - 151/159

→ “Il naufragio della Provvidenza” - 161/165

→ “Padron ‘Ntoni e il giovane ‘Ntoni: due visioni del mondo a confronto” - 166/168

---

# I Malavoglia

*I Malavoglia* è considerato il capolavoro di Verga, l’opera più alta del suo periodo verista.

La vicena riguarda una **famiglia di pescatori**, ambientati in un paese siciliano subito dopo l’Unità d’Italia, **che va incontro alla rovina economica** per aver cercato fortuna con il commercio e avere perso un carico di merci durante una tempesta.

L’intenzione di Verga è quella di raffigurare in modo veritiero gli effetti che i **mutamenti sociali** e le **ambizioni individuali** generano in una civiltà arcaica, investiti e travolti dai cambiamenti della modernità.

Verga precisa che si tratta di **effetti tragici**, che il progresso sparge rovina, e che egli intende volgere il proprio sguardo sui “vinti”.

Il suo proposito è di compiere uno “studio” della realtà contemporanea sulla base dell’idea guida del **conflitto tra vecchio e nuovo, fra tradizione e modernità.**

Egli afferma di voler rinunciare alla funzinoe giudicante dell’autore, cioè **al narratore onniscente.**

Si deve allora concludere che *I Malavoglia* siano un romanzo - documento, sono un’opera **complessa** e sfuggente, **ricca e contraddittoria**, che va ben al di là delle intenzioni programmatiche dall’autore.

---

**Il nonno** riassume in sé il modo di vivere e i valori che appartengono alla **tradizione.**

Il **giovane** è invece **attratto dalla modernità**, tuttavia **l’irrequietezza del giovane** apre nell’universo culturale del nonno una crepa irreversibile, è il segno della **fine del mondo.**

---

La prima idea dei *Malavoglia* nasce in Verga subito dopo il successo della novella *Nedda*, la prima ambientata in sicilia.

Dopo la lettura dell’*Assommoir* di Zola, Verga elabora la **poetica verista** e decide di trasformare la novella incompiuta in **romanzo**.

Il romanzo esce nel febbraio **1881** ed è un **insuccesso.**

Ma Verga si dichiara convinto della **validità della sua scelta verista**, che presenta la realtà nella sua asciuttezza e senza gli effetti drammatici propri del romanzesco.

---

Il romanzo è dunque la storia di una famiglia, ma anche quella di una intera comunità.

Intorno ai Malavoglia si muovono infatti **moltissimi** altri **personaggi**, che rappresentano **i principali mestieri e ruoli sociali del paese.**

Ciascuno è identificato da un **nomignolo** che ne fissa ironicamente una caratteristica principale, per somiglianza o per opposizione, come è d’uso nella tradizione popolare siciliana.

L’ambiente del paese è **ristretto**: poichè tutti si conoscono, nessuno è al riparo da pettegolezzi e maldicenze e in quello spazoi chiuso il **giudizio popolare** è talmente importante da condizionare i destini individuali.

Rispetto alla maggior parte dei compaesani, i Malavoglia sono portatori di un **sistema di valori autentico e disinteressato** e non vengono mai raffigurati in atti di maldicenza o meschinità.

Essi rappresentano nel romanzo il tenace attaccamento ai **valori del lavoro e della tradizione**, insidiati dai cambiamenti della modernità.

---

Il **desiderio di cambiamento e miglioramento** appare nel romanzo come la **causa principale della rovina** dei protagonisti.

Tuttavia Verga sa che il nuovo è destinato comunque a imporsi, al di là delle responsbilità dei singoli.

La raffigurazione dello spazio è sia **realistica**, sia **affettiva,** in quanto gli elementi del paesaggio sono spesso trasfigurati dai sentimenti provati dai protagonisti.

---

I fatti raccontati nel romanzo occupano circa **quindici anni**.

In questo arco di tempo accadono le vicende della famiglia Malavoglia e quelle della gente del paese, **i grandi episodi e cambiamenti politici ed economici** del tempo storico che si intrecciano con la vita locale e la condizionano: **la leva militare obbligatoria** del nuovo Stato unitario; la battaglia navale di Lissa; l’epida di **colera;** la **costruzione della ferrovia**.

La storia e la modernità entrano tuttavia nel tempo del paese soltanto marginalmente, attraverso vaghi richiami, e sono percepiti come **qualcosa di lontano, minaccioso ed estraneo** alla successione monotona degli eventi paesani.

---

Contrariamente a quanto faceva Zola, che prima di scrivere un romanzo si immergeva per mesi nell’ambiente da rappresentare, studiandone dal vivo le caratteristiche, Verga **scrive** *I Malavoglia* **a Milano.**

Egli intende infatti compiere una ricostruzione intellettuale della realtà, osservandola da una certa distanza.

*I Malavoglia* sono un romanzo verista non soltanto perchè raffigurano in modo realistico un piccolo paese del Sud Italia, ma soprattutto per i modi della narrazione: la **modalità narrativa “dal basso”** e la **lingua mimetica** che riproduce il parlato e le cadenze dialettali siciliane.

La **voce narrante** dei *Malavoglia* è **anonima**, non corrsiponde a quella di un personaggio, e **parla dall’interno**.

Questa voce esprime spesso simpatia nei confronti dei malavoglia.

Ad essa si mescola però quella dei paesani, maligna e pettegola, ispirata a una **logica utilitaristica e cinica.**

Questa **mescolanza di voci** e di prospettive genera l’effetto di un **coro popolare** il quale **giudica la realtà invariabilmente dall’interno** e in modo parziale.

E’ il lettore a doversi districare tra la **molteplicità** e la **contraddittorietà dei giudizi** espressi, perchè le voci sono collocate tutte sullo stesso piano e nessuna risulta privilegiata.

---

Il realismo della rappresentazione è garantino inoltre dalle scelte linguistiche.

Anche in questo caso Verga non sceglie di raffigurare in modo esatto e documentario la realtà, ma compie un consapevole lavoro di ricostruzione letteraria: rinuncia a usare il dialetto e **inventa un italiano dialettale** in cui la cadenza delle frasi e le improprietà grammaticali imitino il modo di parlare del popolo siciliano.

---

# Novelle rusticane

All’inizio del 1883 vengono pubblice le *Novelle rusticane*, una raccolta di dodici novelle ispirate alla **poetica verista**.

Verga le compone in un momento di **difficoltà economica**.

Diversamente da *Vita dei campi*, le *Novelle rusticane* non mettono in scena eventi drammatici o personaggi che spiccano sugli altri, ma rappresentano la vita quotidiana più **ordinaria e ripetitiva**, in cui le vicende appaiono prive di coloriture sentimentali e in cui raramente si distinguono figure individuali; anche la morte viene ridotta a un fatto qualunque, di cui contano le conseguenze economiche più che quelle effettive.

Lo sguardo dello scrittore non si limita a rappresentare la vita arcaica ed elementare delle classi inferiori, ma scruta nelll’ambiente della **piccola borghesia paesana**, per farne emergere gli **inganni** e i **soprusi,** nascosti e dissimulati ma non meno violenti.

Nella visione di Verga tutti gli uomini sono impegnati in una lotta senza sosta per il predominio e vanno incontro al medesimo destino di sconfitta: in un mondo dominato dalla **mancanza di ogni valore positivo** e dalla fatale ripetitività delle sorti non sono posisbili prospettive di riscatto, per nessuno.

Le *Novelle rusticane*, con *I vinti*, condivide la **visione pessimistica** e la **sfiducia nel progresso**.

Per garantire l’obiettività della rappresentazione Verga si propone di applicare la **tecnica dell’impersonalità**, cioè di rinunciare allo sguardo esterno del narratore per adottare un punto di vista e un linguaggio interni all’ambiente raffigurato.

L’autore compie cioè un passo indietro e lascia che i personaggi si esprimano secondo i criteri di valore e le forme linguistiche loro propri, senza **alcuna mediazione.**

Tuttavia lo scrittore, che nella rappresentazione del mondo arcaico delle calssi più basse ha realizzato questo proposito attraverso la voce di un coro popolare indifferenziato, si trova ora a dovere individuare una modalità narrativa che restituisca la molteplicità delle sfumature di pensiero e i contrasti ideologici anche dell’ambiente borghese, più **complesso, sfumato e ipocrita.**

Egli tenta di realizzare questo obiettivo attraverso il **montaggio di voci e punti di vista multipli** e spesso opposti.

Vengono così smascherati i miti risorgimentali del Progresso, del Benessere, della Giustizia e della Libertà, che svelano il loro carattere di copertura dell’unico reale obiettivo di tutti: **l’affermazione di sè** e del proprio interesse materiale.

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20118.png)

---

# 👶🏼 Giovanni Pascoli

# Biografia

Nasce a San Mauro di Romagna nel 1855, quarto di dieci figli, in una famiglia non ricca ma di condizioni economiche discrete grazie al lavoro del padre, amministratore di una grande tenuta nobiliare.

All’età di sette anni viene madnato in un prestigioso collegio dove apprende in modo eccellente le lingue classiche.

Nel **1867** avviene però un **evento drammatico**, destinato a modificare le sorti della famiglia e a segnare in modo definitivo l’esistenza di Pascoli: il **10 agosto** di quell’anno suo **padre** viene **ucciso** da due sicari in un agguato.

Negli anni immediatamente successivi si sussegguono altri **lutti dolorosi**: muoiono la sorella maggiore, la madre e il fratello.

Il peggioramento delle condizioni economiche rende impossibile per Pascoli restare a Urbino ed egli termina gli studi a Firenze in una scuola meno costosa.

Grazie al conseguimento di una borsa di studio si iscrive alla facoltà di Lettere di Bologna, dove insegna Giosue **Carducci.**

Nel 1876 gli viene però revocata la borsa di studio e tale perdia, unita alla morte improvvisa del fratello, rende estremamente **precarie** le sue **condizioni economiche** e gli impedisce di pagare le tasse universitarie per l’anno successivo.

Tuttavia continua a frequentare le lezioni come libero uditore e riceve un appoggio dallo stesso Carducci, che lo raccomanda come supplente al ginnasio.

Nello stesso anno, una nuova manifestazione di dissenso gli costa **tre mesi di reclusione.**

Le sue condizioni economiche migliorane perchè riesce a ottenere nuovamente una borsa di studio e nel 1882 egli consegue finalmente la laurea.

Pascoli, che non si era mai allontanato dall’Emilia-Romagna, vive con grande spaesamento il suo primo incarico di **professore di latino e greco** in un liceo di Matera.

Nel 1884 Pascoli ottiene il trasferimento a Livorno: è l’occasione per affittare una villa in cui risiedere con le due sorelle nubili, con le quali tenta di **ricostruire il “nido” familiare.**

La scrittura di poesie iniziata durante il periodo universitario si intensifica e prende la forma di collaborazioni con riviste.

---

Tra Pascoli e d’Annunzio vi è un rapporto che oscilla continuamente tra **stima e avversione**, soprattutto da parte di Pascoli, che vive un tormentato senso di invidia per la maggiore fama riconosciuta al collega ed è ossessionato dalla **paura di subire plagi** da lui.

I rapporti si incrinano quando d’Annunzio chiede a Pascoli una serie di esempi su come tradurre metricamente in italiano un coro della tragedia greca *Antigone*, e Pascoli tace per molti mesi.

Quando gli risponde non manda i versi richiesti, ma spiega di avere intenzioni di redigere un saggio teorico sull’argomento.

A questo punto i contatti tra i due sono sospesi e tra il 1900 e il 1903 si moltiplicano le **manifestazioni di acredine da parte di Pascoli**, che continua a temere plagi e manipolazioni.

E’ d’Annunzio a fare il primo passo verso la riconciliazione, quando dedica a Pascoli la poesia posta alla conclusione della raccolta *Alcyone*.

Pascoli reagirà alternando momenti di disponibilità e stima ad altri di diffidenza e riserbo.

---

Nel corso degli anni Novanta la carriera di Pascoli sembra finalmente decollare.

Scrive anche per “Il Marzocco”, sul quale trovano posto le sue più importanti **riflessioni di poetica**, poi èdite integralmente con il titolo ***Il Fanciullino***.

Nel 1895 avviene una svolta nella vita privata di Pascoli: la sorella **Ida si fidanza** e dopo pochi mesi **si sposa**, determinando la rottura di quel “nido” familiare.

La scelta di Ida provoca un **grande turbamento** nel poeta e soprattutto teme il vincolo sempre più stretto che si verrà a creare con **Maria**.

Nel 1896 Pascoli prende contatti per lettera con una facoltosa cugina, **Imelde Morri**, alla quale in segreto propone le nozze.

La cugina accetta, e Pascoli tenta di organizzare tutto in poche settimane all’insaputa della sorella.

Venuta a conoscenza del progetto, Maria cerca di ostacolarlo mettendo i due promessi sposi uno contro l’altro e Pascoli **rinuncia al matrimonio.**

Pascoli e Maria affittano la casa di **Casatelvecchio di Barga** che diventa il **rifugio** più caro.

---

Pascoli riesce a diventare docente universitario nel 1895, a **Bologna,** ma non è del tutto soddisfatto dell’incarico, perchè si tratta di un insegnamento che considera secondario rispetto ad altri.

Accetta quindi l’offerta di insegnare Letteratura latina a **Messina** e si trasferisce in Sicilia.

Qui, dopo un **periodo difficile**, Pascoli si inserisce nel tessuto intellettuale della città.

Dopo una parentesi all’Università di **Pisa**, dove lavora alla stesura dei *Canti di castelvecchio*, per Pascoli giugne finalmente l’occasione di ricoprire la cattedra di **Letteratura italiana** da lui tanto desiderata: è chiamato infatti a **Bologna** per subentrare a Carducci.

Nell’ultima fase della sua vita è sollecitato a intervenire nella vita pubblica italiana dal suo ruolo universitario, come pure dall’influenza del modello carducciano e dannunziano del poeta-vate, ossia dell’**intellettuale** che si pone quale **guida della società** e che esalta figure da imitare.

Le ultime raccolte sono dunque caratterizzate da una **poesia di tipo risorgimentale,** in cui celebra modelli di umanità come Garibaldi: escono *Odi e inni, Canzoni di re Enzio, i Poemi italici.*

Nello stesso anno tiene a Barga un discorso poi pubblicato come ***La grande proletarie si è mossa***, in cui giustifica la guerra coloniale in Libia: è l’approdo finale del suo socialismo.

Pascoli muore nel 1912 per una malattia al fegato.

---

# Il fanciullino

Il saggio intitolato *Il fanciullino* esce a puntato sulla rivista “Il Marzocco” nel 1897, ampliato e rielaborato viene poi inserito da Pascoli nella raccolta *Miei pensieri di varia umanità*, infine nei *Pensieri e discorsi.*

Nella forma definitiva è un testo inventi brevi capitoli, in cui Pascoli espone la sua poetica, ossia le sue idee su che cosa sia la poesia e su quali siano i compiti del poeta.

L’autore non procede con rigore argomentativo, ma con eloquenza appassionata e con immagini simboliche, delineando una concezione della **poesia come attività non razionale**, spontanea, che nasce dalla fantasia e dall’immaginazione.

---

Per rappresentare la sensibilit poetica Pascoli si serve del simbolo del “fanciullo”, un essere che guarda al mondo in modo ingenuo, con lo stupore di chi vede ogni cosa per la prima volta; grazie **all’intuizione spontanea** il “fanciullo” sa immaginare e cogliere aspetti inconsueti della realtà senza le barriere e i condizionamenti dettati dalla ragione.

Questa creatura è **presente in ogni persona**: nell’infanzia coincide con il bambino, mentre nell’età adulta viene messa in disparte, perchè l’uomo maturo adotta uno sguardo razionale sul mondo, è attento ai propri obiettivi e doveri, si esprime in modo serio e convenzionale, senza dare spazio all’immaginazione e fantastia.

Nell’uomo tuttavia il “fanciullino” non scompare: resta oresente in ciascuno e può riemergere, manifestandosi con reazioni spontanee e imprevedibili davanti ai fatti della vita.

---

Il “fanciullino” possiede due qualità straoirdinarie: la capacità di “vedere” e quella di “dare il nome alle cose”.

Senza l’assillo del tempo e degli obblighi da rispettare, egli agisce seguendo il proprio istinto e il proprio stupore, soffermandosi a vedere, ascoltare, toccare ogni cosa.

Nel guardare assume **punti di vista inediti**, portando in primo piano un particolare apparentemente insignificante per ammirarlo, oppure ponendosi a una certa distanza per vedere ciò che altrimenti, per le sue eccessive dimensioni, sfuggirebbe.

Inoltre **scopre affinità e legami tra le cose**, mettendo in relazione elementi anche molto lontani tra loro.

Si tratta evidentemente di una **fanciullezza** non realistica ma **ideale**, che rappresenta l’infanzia stessa del mondo, quell’età antica mitizzata nella quale vi era un rapporto spontaneo e immediato tra l’uomo e la natura.

---

Sebbene il “fanciullino” sia presente in tutti, soltanto il poeta è in grado di conservarne davvero lo spirito e di dargli voce, attraverso la poesia.

Per Pascoli la **poesia** è uno **stato di illuminazione interiore**, che dipende dalla capacità del soggetto di cogliere, all’esterno o all’interno di sé, un dettaglio sempre, un elemento anche banale sfuggito a tutti.

Il fatto che il poeta volga la sua attenzione agli oggetti più comuni e semplici non implica che egli sia un uomo ingenuo o incolto.

Pascoli è insegnante di liceo e poi professore universitario, egli non intende certo svalutare la formazione culturale quando indica la via della semplicità, ma assume piuttosto una posizione **polmeica nei confronti** della tradizione letteraria, appesantita dalla mania **dell’”accademismo”,** della retorica, della forma fine a se stessa.

Il poeta è dunque colui che comprende come l’oggetto più umile possa rivelarsi qualcosa di molto prezioso: perchè questo avvenga occorre uno sguardo attento, ma anche l’”**arte del togliere**”.

Nel Fanciullino Pascoli riprende a sviluppa questo aspetto: il poeta conosce bene il patrimonio retorico e letterario ma sa **rinunciare a tutti gli ornamenti inutili**, si limita ad ascoltare e a comuincare ciò che il suo “fanciullino” interiore gli suggerisce.

Inoltre la poesia non deve perseguire intenzionalmente alcuno scopo pratico o sociale: non ne ha bisogno perchè è **utile di per se stessa**, per il solo fatto di esistere.

Pascoli sostiene che la capacità di comprendere la poesia è in tutti però avverte con chiarezza che soltanto pochi sono in grado di far rivivere dentro di sé il “fanciullino” e dargli voce.

Sotto questo aspetto pAscoli non è troppo dissimile da d’Annunzio: sia pure in modo diverso, entrambi rivendicano il ruolo del **poeta come mediatore** indispensabile per l’interpretazione del mondo e la formazione dell’uomo.

---

# Myricae

*Myricae* esce per la prima volta nel 1891 come opuscolo per le nozze di un amico, ma Pascoli tel tempo aggiunge, rielabora testi, progetta raggruppamenti interni tra i componimenti, accentua tematiche e atmosfere che gli stanno a cuore: l’edizione definitiva è **quasi un altro libro**, venutosi a formare nel corso di dodici anni, durante i quale le iniziali ventidue poesie sono diventate centocinquantasei.

Il titolo è ispirato a un **verso di Virgilio**, in cui il poeta latino dichiara di volersi allontanare dal tema agreste che contraddistingue la raccolta per trattare un argomento più alto con uno stile più elevato.

Il verso virgiliano assume **significato opposto**: vi si afferma dunque che le Myricae, o “tamerici”, piante modeste e comuni, piacciono e sono apprezzate, così come la vita umile di campagna che esse rappresentano.

La **semplicità** delle poesie di Pascoli tuttavia è **soltanto apparente**, poichè proprio gli oggetti più comuni pososno alludere a temi generali che riguardano l’esistenza umana, la presenza del male, il mistero del dolore e della morte.

---

E’ possibile individuare nella poesia **due discorsi paralleli**, l’un generato dal dato letterale del testo, l’altro da ciò a cui esso allude.

Occorre dunque uno **sforzo interpretativo** da parte del lettore, il quale deve rivolgere la sua attenzione a tutti gli elementi del testo e coglierne le suggestioni.

Alcune immagini assumono una valenza precisa, tanto che si può parlare di **simboli ricorrenti**, perchè il legame tra l’oggetto e l’idea si ripropone identico e resta inalterato in più testi.

Altre immagini invece costituiscono simboli più difficili da decifrare, perchè assumono significati **diversi a seconda dei contesti**.

Anche l’io lirico offre un’**immagine di sé non univoca**: talora si rappresenta come un padre, talore invece assume l’atteggiamento di un bambino segnato dal dolore e dalla solitudine, che cerca compassione.

Ugualmente i famigliari morti sono figure desiderate e rimpiante, ma da cui il poeta non riesce a liberarsi, tanto che sente la necessità di offrire loro tributi di memoria per tenere a bada la propria angoscia.

In Pascoli affiora l’oscuro **senso di colpa** di essere sopravvissuto alla morte dei propri cari.

 

---

I poeti classici che sono oggetto di **imitazione diretta** da parte di Pascoli nelle poesie in latino (Omero, Virgilio, Catullo e Orazio) costituiscono un significativo repertorio tematico, lessicale e stilistico anche per la sua poesia in lingua italiana.

Allo stesso modo, **Dante e Leopardi** sono citati in modo esplicito, oppure recuperati per **affinità tematiche**.

---

Poichè il rapporto di Pascoli con la realtà è inquieto, non più guidato nè da valori romantici nè dalla fiducia nella scienza, le forme attraverso le quali si esprime non possono che essere nuove.

I critici hanno usato la formula di “accordo eretico” con la tradizione per indiciare come Pacoli sia fortemente **radicato nella sua epoca**, ma al tempo stesso imprima una **svolta** alla lingua della tradizione, soprattutto sul piano fonico, lessicale e sintattico.

Caratteristica delle *Myricae* è la **brevità.**
Spesso mancano i **nessi logici** espliciti, di tipo temporale o casuale; il discorso procede con accostamenti improvvisi, salti inattesi e ritorni all’indietro.

All’assenza di nessi logici supplisce in qualche modo la forte presenza di legami sonori all’interno del testo, attraverso rime, anche interne.

Sono ricorrenti le **onomatopee.**

Si è parlato per Pascoli di un vero e proprio **Fonosimbolismo**, ossia la capacità delle **sillabe** di diventare **portatrici di significato** semplicemente in base al loro suono.

Hanno particolare rilevanza le **metafore e le analogie**, che esprimono associazioni imeddiate e intuitive compiute dall’io lirico tra gli oggetti.

Vi è una presenza importante di **sinestesie,** che rimandano all’idea baudelairiana e simbolista per cui **la natura è un tutto unitario** in cui si celano segrete corrispondenze.

Sul piano lessicale troviamo alcune innovaioni all’interno di un tessuto linguistico ancora abbastanza uniforme: la tendenza a mescolare alto e basso, termini dialettali e lingua letteraria.

Particolarmente significata è però la capacità di **accogliere la prosa nella poesia**, inserendo nei versi frammenti di dialogo e voci del linguaggio quotidiano.

Sul piano metrico Pascoli rispetta la tradizione per la scelta di forme chiude, ma si mostra innovativo nell’adottare **versi poco comuni e strutture metriche** note, ma **desuete**.

Il **ritmo frammentato** di Pascoli gli permette di evidenziare il particolare, il dettaglio, senza che tuttavia vengano meno l’unità e la regolarità della forma.

---

E’ possibile inoltre identificare alcune opposizioni ricorrenti, che si riproporranno in tutta l’opera del poeta.

La prima contrapposizione è quella tra ripetizioni e sperimentalismo.

Pascoli insiste in modo quasi ossessivo su alcuni temi, in particolare su quello che è stato definito il suo “**romanzo familiare**”, ossia la vicenda dell’uccisione del padre.

Alla ripetizione di temi identici si oppone la **varietà delle forme**.

Si potrebbe dire che Pascoli tenti di recuperare nella poesia quel legame con i cari divenuto impossibile nella vita, e parallelamente cerhci forme sempre nuove per rielaborare la sua tragedia familiare.

Nell’opera di Pascoli convivono la precisione del dettaglio e la costruzione di atmosfere indefinite: da un lato emerge la volontà di **rendere esattamente il dato reale**, con grande accuratezza nella scelta dei nomi.

D’altro canto si coglie la tendenza opposta a **dissolvere l’immagine nell’indeterminato**.

Il particolare preciso che affiora nell’atmosfera indeterminata si carica così di significati simbolici misteriosi.

Lo sguardo delp oeta si fissa spesso sul dettaglio, lo isola e pare esaurire in esso tutto il suo interesse, descrivendolo in forma lirica.

## Brani

→ “X Agosto” 

→ “Temporale”

→ “Il lampo”

→ “Il tuono”

→ “Novembre”

---

# I canti di castelvecchio

Mentre continua a lavorare a *Myricae*, Pascoli realizza nel 1903 un’altra raccolta intitolata *I canti di castelvecchio*, poi **ripubblicata più volte** con accrescimenti e modifiche.

Il titolo cita esplicitamente un luogo caro, Castelvecchio di Barga, dove Pascoli si era trasferito con la sorella nel **tentativo di ricreare quell’intimità familiare e domestica perduta** con la morte dei suoi cari.

Nel titolo si può cogliere anche un rimando ai *Canti* di Leopardi, con i quali vi sono alcuni punti di contatto, a partire dalla **predilezione per il vago e l’indefinito**, alla percezione della sofferenza che permea il mondo, all’idea del piacere come cessazione del dolore.

La successione delle poesie non segue l’ordine cronologico di composizione ma risponde a un **criterio tematico**: i testi sono disposti secondo il susseguirsi delle stagioni e mostrano **l’alternarsi di vita e morto nel ciclo naturale**, mentre nell’esistenza umana la morte incombe come evento irreparabile, frutto di violenza o di un mistero inspiegabile.

I testi sono più lunghi di quelli di *Myricae*, sono **composizioni più ampie e articolate**, in cui prevalgono i novennari e i senari, con ritmi spezzati e pause inattese.

Il simbolismo che costituiva una delle novità di *Myricae* viene ulteriormente accentuato: talora con **allusioni scoperte e dichiarate,**talora invece con **immagini misteriore ed evocative**.

In questa raccolta si fa più intensa anche la tendenza al plurilinguismo: abbondano i **termini tecnici** e quelli garfagnini, al punto che il poeta inserì un lessico per illustrare il significato delle **espressioni dialettati e gergali.**

## Brani

→ “La mia sera” - 349/350

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20119.png)

---

# 🦋 Gabriele D’Annunzio

# Biografia

Nella storia della letteratura italiana Gabriele D’Annunzio è stato uno degli autore più dibattuti e contrastati.

La ragione di tanto **fervore polemico** è legata alla particolare natura di **un’attività letteraria** che appare **indissociabile dalla vita dell’autore:** personalità eccentrica, disinbolta, eclettica, d’Annunzio viene da molti ricordato più per le sue azioni clamorose che per le sue opere.

Al di là delle immagini che lo stesso scrittore ha diffuso con calcolata abilità - da quella del *dandy* a quella dell’indomito poeta - soldato - si deve riconoscere a d’ANnunzio un’inesauribile e acuta capacità di assimilare le tendenze letterarie e filosofiche della sua epoca e introdurle in un paese ancora provinciale e chiuso alle novità europee.

Questo ruolo di **mediatore** capace di imporre i nuovi orientamenti del gusto della borghesia italiana, vale a d’Annunzio l’ammirazione della “moltitudine”.

Mentre infatti ottiene largo successo presso i lettori contemporanei, l’autore ha **pochi estimatori tra i letterati italiani** della sua epoca.

---

<aside>
🐣 Gabriele D’Annunzio nasce a Pescara nel 1863 come terzogenito di cinque figli.

</aside>

Il padre proviene da una famiglia modesta ma è stato adottatoa da uno zio benestante, da cui ha ereditato i beni e il cognome.

La madre, dolce e premurosa a cui il giovane è molto legato.

Al primo figlio maschio viene risercata una **formazione d’eccellenza**: il padre lo iscrive al collegio “**Cicognini**”.

Allievo studioso e brillante, il ragazzo eccelle in tutte le materie e consegue la “licenza d’onore”.

D’Annunzio tende ad attribuirsi una sorte di exxezionalità da ***enfant prodige* irrequieto e ribelle**.

Nella volontà di ricreare a posteriori un’**immagine mitizzata di sè** emerge uno dei tratti fondamentali del personaggio: di ingegno versatile, capace di assorbire e affinare competenze precise in diversi ambiti.

<aside>
👤 D’Annunzio si imporrà come un **protagonista della vita culturale e politica italiana**

</aside>

---

Negli anni del collegio d’Annunzio legge voracemente i classici (Virgilio, Catullo, Manzoni, Darwin, …) e soprattutto le *Odi barbae* di Carducci, poeta che risvegli anel giovane un’improvvisa **vocazione lirica**.

<aside>
📕 Nel 1879, a soli sedici anni, pubblica a spese del padre ***Primo vere***, un libretto di versi “carducciani”, che viene sequestrato dai docenti del collegio in quanto troppo licenzioso e sensuale.

</aside>

Per promuovere se stesso e i propri libri d’Annunzio non esita a mettersi in scena, e lo stesso Marinetti lo accusa di piegarsi al culto di *Notre-Dame la Réclame* (nostra signora pubblicità).

Per scuotere il pubblico D’Annunzio fa precedere la seconda edizione di *Primo vere* dal finto annuncio della propri amorte, accompagnata da commoventi necrologi scritti di suo pungo.

<aside>
🎓 Si iscrive alla facoltà di Lettere dell’Università “La Sapienza”, ma non porterà mai a termine gli studi, preferendo intrecciare **rapporti con gli intellettuali più influenti** del mondo editoriale romano.

</aside>

---

Nel 1882 d’Annunzio pubblica una nuova raccolta poetica, ***Canto novo***, e il volume ***Terra vergine.***

Il grande successo di queste opere lo eleva al rango di divo e lo incoraggia a coltivare il proprio mito anche al di là dei confini letterari: partecipando attivamente alla vita dei salotti e rendendo pubbliche le sue numerose avventure amorose, il giovane scrittore estende la propria **fama mondana.**

<aside>
💒 Il suo **matrimonio** con la duchessa **Maria di Gallese**, nel 1883, segue un copione romanzato, con tanto di rapimento della sposa.

</aside>

Grazie a questa unione d’Annunzio pensa di garantirsi il **tenore di vita lussuoso** che le sue abitudine dispendiose stanno mettendo in pericolo.

Dopo la nascita del primo figlio, nel 1884 l’autore si trova in **difficoltà economiche**: ha sperperato il patrimonio del padre e non potendo contare su quello del suocero a lui ostile, **si rifugia in Abruzzo.**

---

L’attività giornalistica fli permette di fare fronte ai problemi economici e diventa l’occasione di un apprendistato culturale che sarà determinante: nelle sue **recensioni** di autori italiani ed europei affina le sue qualità di osservatore dei costumi.

Intanto una nuova relazione amorosa lo lega all’esuberante **Barbara Leoni**, consolidandone la fama di **irresistibile seduttore**.

Nel 1888, nonostante le persistenti difficoltà economiche, d’Annunzio decide di licenziarsi e **isolarsi** per concentrarsi sulla stesura di un romanzo, ***Il piacere.***

**Il successo del romanzo** presso il pubblico indica che esso ha saputo soddisfare una precisa esigenza sociale.

---

Tra il 1889 e il 1890 deve prestare **servizio militare** a Roma e interrompere la produzione letteraria.

Nel 1892 vengono date alle stampe anche le ***Elegie romane**,* una sorta di diario sentimentale che si ispira alla passione del poeta per Barbara Leoni.

Nel frattempo d’Annunzio rimane attento ai nuovi fermenti culturali, la sua **adesione al Simbolismo** europeo appare ora più consapevole e matura.

---

<aside>
💭 Intorno al 1892 d’Annunzio si interessa alla **filosofia di Nietzsche** attraverso la versoine francese di *Così parlo Zarathustra.*

</aside>

Nel 1894 pubblica il romanzo ***Trionfo della morte***, che non propone ancora compiutamente la nuova figura mitica del superuomo, ma ne delinea l’avvento.

In definitiva comunque **è la morte a prevalere** sull’aspirazione alla vita.

*Il trionfo della morte, il piacere* e *l’innocente *****confluiranno nel cosiddetto **ciclo “della rosa”.**

Nel 1895 D’Annunzio pubblica ***Le vergini delle rocce,*** che segna una **svolta ideologica**, diventando una sorta di manifesto del superomismo.

---

<aside>
♥️ Durante un soggiorno a Venezia incontra la celebre attrice **Eleonora Duse**, tra i due inizia un’appassionata relazione in cui l’amore si intreccia indissolubilmente con un interesse pratico e artistico.

</aside>

<aside>
🗳️ Nel luglio 1897 lo scrittore si presenta alle elezioni politiche come **candidato alla Camera** e viene eletto **nelle file della Destra.**

</aside>

Il 1900 segna un radicale cambio di orientamento politico, d’Annunzio **passa ai banchi della Sinistra** e si candida con il gruppo socialista ma non viene eletto.

---

Nel 1898 d’Annunzio va a vivere con la Duse in una villa detta “la Capponcina”: si mette in scena con **sfarzo e stravaganza**, circondandosi di lussuosi arredi, cavalli e levrieri di razza.

Qui lavora alle prime *Laudi del cielo del mare della terra e degli eroi* e a un nuovo romanzo, ***Il fuoco*** che prolunga la fase del superuomo.

Nel 1904 vengono pubblicati il secondo e il terzo libro delle *Laudi*, che segnano una sorta di “tregua”, un ripiegamento interno: il poeta si allontana dall’autobiografismo strumentale e idealizzato del “superuomo” puntando su argomenti privati e sulle suggestioni di una lingua più pacata.

Il rapporto con la **Duse** volge al termine.

Alla Capponcina si installa la nuova amante, ma le spese sostenute per garantirle una vita di lusso portano l’autore all’inevitabile **tracollo economico**.

---

Per sfuggire ai creditori, nel 1910, si rifugia in Francia dove rimane per cinque anni.

A partire dall’anno successivo, per far fronte ai problemi economici, l’autore collabora con il “Corriere della Sera” su cui pubblica una serie di scritti autobiografici.

Nello stesso anno d’Annunzio **rifiuta la cattedra** universitaria di **Bologna** rimasta vacante dopo la morte di Pascoli.

Tra il 1912 e il 1914 d’Annunzio si dedica a un’intensa **attività** teatrale ma anche **cinematografica.**

Allo scoppio della guerra d’Annunzio si reca sul fronte francese come inviato del “Corriere della Sera”.

<aside>
🪖 Dalle colonne del quotidiano l’autore svolge un’intensa **azione di propaganda** per l’entrata in campo dell’Italia a fianco dell’**Intesa.**

</aside>

Quando il regno d’Italia decide di scendere in guerra d’Annunzio sceglie di arruolarsi.

Divenuto **poeta-soldato** il vate narra la sua esperienza e le sue imprese nei *Canti della guerra latina.*

<aside>
🪖 **Il volo su Vienna** del 1918, effettuato per lanciare volantini propagandistici di invito alla resa è l’evento più eclatante.

</aside>

Nel 1916 viene ferito e perde un occhio.

Durante il periodo di convalescenza inizia a redigere alcune note che convergeranno poi nel *Notturno.*

---

Un anno dopo la fine del conflitto, d’Annunzio si lancia nell’**impresa di Fiume**.

Al comando di uomini indignati per la “**Vittoria mutilata**”, d’Annunzio entra a Fiume senza incontrare resistenze.

---

Agli inizi del 1922 d’Annunzio cerca di ritagliarsi uno spazio politico autonomo in opposizione al programma del Partito fascista.

<aside>
🪖 I suoi rapporti con il fascismo sono **complicati**: l’autore si dimostra ideologicamente prossimo al regime, ma si sente perlopiù usurpato dalle autorità fasciste di cui spesso **non condivide le azioni.**

</aside>

Le autorità fasciste, che hanno interesse ad associare alla propria causa il celebre poeta, lo relegano a un **ruolo** più **decorativo che attivo**, sacralizzando la sua immagine e mantenendolo in tal modo sotto controllo.

---

Lo scrittore trascorre i suoi ultimi anni nella sontuosa villa sul Garda. La sua esistenza è ormai più “notturna” che mondana.

Le sue **ultime opere** sono anch’esse notturne, sia perchè scritte di notte, sia perchè gravate da un **senso di stancehzza** e di morte.

<aside>
🪦 Il poeta ormai esausto **muore** improvvisamente nel marzo del **1938.**

</aside>

---

# La poetica tra “passato augusto” e la modernità

In qunato erede consapevole del patrimonio estetico italiano, d’Annunzio si attribuisce il compito di coniugare tra loro la tradizione nota e la modernità ignota che è destinata ad accrescere il passato illustre di **nuova Bellezza**.

A differenza di molti letterati suoi contemporanei che si levano contro gli effetti nefasti dell’industrializzazione, d’Annunzio **accoglie la modernità** e le sue potenziali bellezze.

Il vate lamenta lo **scarso interesse per il passato nazionale** della **classe dirigente** borghese.

Il ricongiungimento ideale tra la classicità e la modernità prende forma compiuta in *Maia*, il primo libro delle ***Laudi***, in cui d’Annunzio trasfigura in chiave mitica un **viaggio in Grecia** realmente compiuto, facendosi iniziatore di una nuova arte moderna che trovi nell’arte antica il suo punto di origine.

---

A differenza dei futuristi, i quali esaltano una modernità che nasce sulle ceneri di un passato da distruggere, per d’Annunzio la **modernità** è dunque **debitrice dell’eredità antica e classica**, da cui non può prescindere.

D’Annunzio rivendica la sua **libertà di non essere soltanto poeta**, ma di poter attingere a ogni campo.

Questo interesse avido e a tutto campo conduce d’Annunzio a esplorare precocemente l’universo dell’immagine, dal **film** alla **fotografia:** spinto da una sconfinata fiducia nei confronti del **progresso tecnico**, d’Annunzio giugne perfino ad auspicare l’invenzione di un oggetto che conservi per la posterità la recitazione degli attori di teatro altrimenti irrimediabilmente dispersa.

Uno degli aspetti puù vistosi di questo allargamento degli orizzonti estetici è l’interesse che d’Annunzio rivolge a quelli che in seguito si definiranno i “beni culturali”: **contro il degrado artistico e ambientale,** egli milita attivamente per la salvaguardi dele bellezze artistiche e naturali italiane.

Lìapprofondita conoscenza dei beni culturali incide anche sull’elaborazione delle opere; d’Annunzio è infatti solito servirsi di **guide specializzate** per introdurre nei suoi scritti descrizioni dettagliate e notizie storiche delle grandi città d’Italia e dei loro scorci.

---

La poetica di d’Annunzio segue diverse fasi, che corrispondono alle tappe di una ricerca del ruolo dell’intellettuale nella civiltà borghese moderna.

## La prima fase

La prima fase è quella del cosiddetto “**estetismo**”, inteso come il **culto dell’arte e della bellezza** a cui vengono subordinati tutti gli altri valori, compresi quelli morali.

A incarnare l’estetismo dannunziano è Andrea Sperelli, protagonista del ***Piacere.***

## La seconda fase

Stanco degli artifici dell’estetismo, d’Annunzio si lancia in un periodo di incerte **sperimentazioni**.

Sorgono in questo periodo alcune opere che risentono del contatto con altri ambienti sociali stabilito dall’autore durante il servizio militare, ma anche della sua appassionata lettura dei **narratori russi dell’Ottocento:** è la fase solitamente definita della “**bontà**”, caratterizzata da un’esigenza di **rigenerazione** e di **purezza**, ma anche da uno studio delle **passioni più buie** dell’animo umano.

## La terza fase

Tuttavia la fase della “bontà” è una soluzione provvisoria e di breve durata.

Attraverso il mito del “superuomo” ricavata dalla lettura di **Nietzsche** d’Annunzio investe di un **nuovo compito** la figura dell’esteta, non si accontenta più di vagheggiare la bellezza rimanendo isolato dalla societa, ma si incarica di **agire sulla realtà.**

Nel filosofo tedesco d’Annunzio privilegia i principi a lui più affini, come il **vitalismo “dionisiaco”**, la teoria del “superuomo”, la **libertà d’azione dell’individuo superiore**.

Il “superuomo” incarna una nuova filosofia che implica il superamento dell’umano ma non la supremazia dell’uomo sull’uomo, in d’Annunzio questa filosofia diventa **azione pratica e politica**, e si traduce in violenza, rifiuto della democrazia, bellicismo e disprezzo delle masse.

L’artista superuomo si attribuisce la missione di **profeta** di questo nuovo ordine rivestendo un ruolo più attivo, più politico.

Mentre durante la fase dell’estetismo e quella del superuomo d’Annunzio aveva opposto alla volgarità moderna il culto della bellezza e dell’eroismo del passato, intorno agli inizi del secolo il mito superomistico entra a sua volta in crisi: l’intervento attivo dell’intellettuale-superuomo nella realtà implica un’opposizione violenta contro la modernità.

La pubblicazione delle prime *Laudi* segna una svolta radicale: il poeta non si contrappone più al mondo moderno, ma ne canta la **segreta bellezza, inneggiando** agli aspetti tipici della **modernità**.

La dirompente energia moderna rivela ai suoi occhi il fascino di un **nuovo mito.**

Con *Alcyone*, l’ultlima delle *Laudi*, d’Annunzio abbandona i toni celebrativi e politici dei primi due libri: l’atmosfera che domina il libro è contemplativa e il tema lirico centrale è quello della **metamorfosi panica**, cioò la fusione dell’io lirico con la natura.

Proteso a conseguire l’immortalità attraverso la perdita della propria identità umana nel ritmo della natura, il poeta si identifica con le diverse presenze animali, vegetali e minerali e, trasfigurandosi, attinge a una **condizione divina**

---

In seguito alla lettura di Nietzsche e ai suoi contatti con le **avanguardie storiche**, d’Annunzio esplora **nuove dimensioni estetiche** che prevedono un rapporto più diretto tra lo scrittore e il suo pubblico.

D’Annunzio viene considerato da molti come un **precursore della comunicazione di massa.**

Tra le sue doti di mediatore culturale della società dei consumi vi è quella di **inventore** di nuovi nomi, motti, slogan e messaggi pubblicitari di **grande successo.** (Vittoria mutilata, tramezzino, …)

Più che di vere e proprie invenzioni si tratta il più delle volte di **calchi** tratti **dal latino**.

D’Annunzio considera **l’arte** come una “continuazione” e un’**elevazione dell’esistenza** che, liberata dalla propria imperfezione, assume un valore assoluto e sacrale.

La forma d’arte più adatta a esprimere questa “continuità vitale” è il **romanzo.**

---

Il vate rivendica a sè il ruolo di “artefice” della lingua, il quale ha il compito di operare il fecondo **ricongiungimento tra il passato** augusto e **la modernità**.

Le parole per d’Annunzio sono sace e vanno preservate nella loro incomparabile **unicità**: esse sono “simboli senza possibile sinonimia” che rivelano il loro splendore soltanto “all’artefice il quale sappia scrutarne le origini”.

La lingua italiana non deve dunque essere inventata *ex novo*, ma **riscoperta in tutta la sua infinita ricchezza**, riportando alla luce i suoi tesori accumulati nei secoli.

La modernità non coincide pertanto con l’invenzione di nuove parole, ma con l’armonizzazione e la **combinazione nuova di elementi** che sono **caduti in disuso** e che l’artefice deve riattivare, rimettere in circolazione.

Compito del poeta è anche quello di recuperare il **potere arcaico** della parole creatrice, riportando alla luce un patrimonio originario di espressioni della sfera prelinguistica che, sepolte nella coscienza universale, accomunano il poeta a tutti gli esseri viventi.

---

D’Annunzio trae la sua grande perizia linguistica non da un paziente lavoro di filologo, ma dal contatto con alcuni eruditi di fama che gli forniscono interi repertori di **parole rare e preziose**.

In questo senso la sua è una vera e propria officina che usa, rielabora e **contamina** tra di loro termini tratti dai **lessici speciali**.

D’Annunzio lamenta l’**assenza di un registro medio nella lingua italiana**, la quale ha il difetto di essere o dialettale oppure artificiosa.=

---

# Il piacere

*Il piacere* è il primo romanzo scritto da d’Annunzio.

Il protagonista **Andrea Sperelli** è un giovane aristocratico raffinato e coltissimo che discende da una famiglia di artisti.

Andrea si isola sdegnosamente nel **culto di una bellezza raffinata e artificiosa** adottando uno stile di vita eccezionale e stravagante, distante dal vivere e dalla morale comuni.

E’ **diviso tra due figure femminili antitetiche**: la fatale Elena muti, la passione erotica, e Maria Ferres, donna pura.

Andrea Sperelli rappresenta almeno in parte *l’alter ego* di d’Annunzio, il quale nutre nei confronti del suo personaggio un **sentimento duplice,** fatto al tempo stesso di **ammirazione** e di **coscienza critica.**

---

Sul piano formale, il romanzo è riconducibile a modelli diversi.

Da un lato, l’evidente ambizione di **ricostruire un preciso ambiente sociale** indica che il superamento del Verismo non è ancora del tutto avvenuto.

Dall’altro lato, il romanzo appare dominato dall’introspezione psicologica dei personaggi e dai loro tortuosi **processi interiori.**

Per d’Annunzio la narrativa postnaturalista deve **mettere in contatto l’analisi psicologica** dei personaggi **e la descrizione dei luoghi e degli avvenimenti.**

<aside>
🗣️ La lingua del romanzo è **aulica**, preziosa e la sua avvolgente sensualità risente dell’**influsso di Baudelaire** e delle suggestioni sintetiche dei simbolisti.

</aside>

## Brani

→ “Un destino eccezionale intaccato dallo squilibrio” - 395/397

→ “Un ambiguo culto della purezza” - 399/402

---

# Alcyone

*Alcyone *****appare lontano dai toni celebrativi e politici dei primi due libri delle *Laudi* ed è percorso da una vena poetica perplessa e malinconica.

<aside>
🗣️ **L’atmosfera** che vi domina è **contemplativa** e il tema lirico centrale è quello della metamorfosi panica, cioè della fusione dell’io lirico con la natura, con il flusso della vita universale.

</aside>

Proteso a **conseguire l’immortalità** attraverso la perdita della propria identità umana nel ritmo della natura, il poeta si identifica con le diverse presenze animali, vegetali e minerali e, trasfigurandosi, attinge a una **condizione divina.**

Il tema mitologico e la parabola stagionale appaiono uniti dal **motivo comune della “fine”**: la tristezza per l’inevitabile declino dell’estate viene associata all’angoscia nata dalla perdita della dimensione mitica dopo la caduta di Icaro.

---

**L’alternarsi delle fonti e dei registri**, le forme espressive sperimentali, l’organizzazione metrica, il raffinato tessuto analogico, fonico e melodico fanno del terzo libri delle *Laudi *****un **testo capitale del primo NOvecento** a cui attingeranno molti poeti successivi.

## Brani

→ “Pioggia nel pineto” - 417/424

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20120.png)

---

# 🎭 Luigi Pirandello

# Biografia

La nascita di Luigi Pirandello avviene in un luogo imprevisto e in un tempo inatteso: la madre si è infatti allontanata dalla casa per sfuggire al colera che devasta la Sicilia, e si è rifugiata in un podere di campagna, chiamato **Caos;** è l’ che Luigi Pirandello viene al mondo nel **1867.**

<aside>
💡 Pirandello afferma che la sua esistenza porta impressi sin dall’inizio i segni del caso: l’imprevedibilità degli eventi e l’assenza di un ordine comprensibile del mondo.

</aside>

Se nella madre Luigi trova confidenza e affetto, **con il padre** Stefano ha un **rapporto difficile**, segnato dall’incopmrensione e dalla reciproca diffidenza.

Padre e figlio sembrano appartenere a mondi opposti: il primo è un abile commerciante di zolfo non disposto all’ascolto nè incline a interessi di tipo intellettuale; Luigi è invece riflessivo, misurato, inadatto ai lavori pesanti e alle attività pratiche.

> Da bambino si appassiona alla letteratura, ma in casa non trova libri e fatica a procurarsi altri testi; pertanto ascolta rapito le fiabe e le leggende del folklore siciliano narrate dalla serva di casa, molte delle quali costituiranno le basi per le future novelle.
> 

Il padre gli impone studi tecnico - commerciali, perchè spera di inserirlo un giorno nell’attività di produzione e vendita dello zolfo.

Alla fine del secondo anno però Luigi escogita uno stratagemma per passare al Liceo: finge di essere stato rimandato e, con i soldi che il padre gli dava per le ripetizioni estive prende lezioni di latino in modo da sostenere gli esami del ginnaio.

Quando ormai Luigi frequenta da mesi la nuova scuola il padre scopre l’inganno e lascia che il figlio continui gli **studi liceali a Palermo**, dove la famiglia si è trasferita per motivi lavorativi.

Dentro di sè va intanto maturando il proposito di diventare poeta.

La distanza con il padre si fa ancora più profonda quando Luigi scopre che Stefano Piranedlo tradisce la moglie con una cugina.

Molti elementi di questa **drammatica vicenda familiare** saranno raccontati tempo dopo in una novella, ***Ritorno,*** che costituisce una sorta di “vendetta” del figlio nei confronti del tradimento paterno.

A diciannove anni Luigi si innamora di una cugina, riesce a conquistarla ma la famiglia di lei acconsente al fidanzamento soltanto a patto che Luigi si associ al padre nel commercio dello zolfo.

Il giovane Pirandello sperimenta un lavoro faticosissimo sotto il sole e ciò lo segna: gli conferma in modo definitivo la sua assolutà **estranietà alle attività pratiche del mondo,** lo motiva ulteriormente a volgersi alla scrittura.

> Il padre spinge Luigi a iscriversi all’Università imponendogli la facoltà di **Legge**; obbedisce, ma parallelamente si iscrive anche a **Lettere.**
> 

I sentimenti per la cugina vanno svanendo e perciò si trasferisce a **Roma**.

All’Università La Sapienza di Roma, nel 1887, Pirandello non rinnova l’iscrizione a Legge ma si dedica soltanto a Lettere.

Successivamente si trasferirà all’**Università di Bonn**.

Resterà in Germania un’anno e mezzo, lamentandosi con gli amici per la dipendenza economica dal padre.

Ormai libero da promesse matrimoniali, Pirandello si stabilisce a Roma, determinato a fare della scrittura la sua professione.

Non vuole insegnare perché gli pare una scelta riduttiva rispetto all’impegno letterario.

La situazione di precarietà economica finisce però con l’esasperazione di Pirandello che arriva così a combinare un **matrimonio di surfaro** per interessi economici.

<aside>
💍 Luigi Pirandello sposa dunque nel 1894 **Antonietta Portolano**, figlia di un uomo in rapporti di amicizia e affari con il padre.

</aside>

Nello stesso anno esce la prima raccolta di novelle di Pirandello, *Amori senza amore.*

Durante il fidanzamento Pirandello aveva sperato di fare di Antonietta una compagna nel suo percorso artistico, ben presto però appare chiaro che Antonietta, donna graziosa e buona padrona di casa, è ingenua e incolta, non in grado di seguire Pirandello nella sua tortuosa ricerca letteraria.

Nel giro di pochi anni nascono tre figli.

Antonietta comincia a manifestare i primi segni di **fragilità psichica** che vengono però attribuiti alla debilitazione del fisico per i frequenti parti.

Le necessità economiche si moltiplicano: le rendite della dote non sono sufficienti e Pirandello deve dedicarsi all’**insegnamento**, ottenendo una cattedra all’**Istituto superiore di Magistero di Roma.**

<aside>
📉 Stefano Pirandello aveva investito molto denaro, tra cui l’intera dote della nuora, nella gestione di una **miniera di zolfo.**

Nel 1903 si allaga e il danno è irreparabile, la perdita economica è immensa.

</aside>

Quando Antonietta apprende la notizia viene colta da una **paralisi** e smarrisce il controllo di sé.

Anche Pirandello è disperato per la notizia e arriva ad ipotizzare il suicidio.

<aside>
🔖 Per ottenere compensi, oltre a insegnare, inizia a dare **lezioni private** di italiano e di tedesco, si occupa di **traduzioni,** senza smettere di scrivere **opere nuove**: gli viene infatti richiesto un romanzo da pubblicare a puntate e nel giro di pochi mesi vede la luce ***Il fu Mattia Pascal.***

</aside>

E’ finalmente un successo.

Le condizioni mentali della moglie peggiorano e la sua malattia si manifesta come gelosia ossessiva verso il marito.

In una lettera del 1914 si sfoga e si giustifica verso l’amico Ugo Ojetti.

Prosegue poi lamentando le **difficoltà economiche.**

Pirandello è ormai un autore riconosciuto e riesce a scrivere con ritmo ininterrotto, **porta a termine moltissime opere,** tra cui il saggio *L’umorismo*, i romanzi *Suo marito* e *I vecchi e i giovani* e numerose novelle.

Nel 1915 il primogenito, partito volontario per il fronte, viene ferito e catturato dagli austriaci. 

Pirandello, che si era schierato tra gli interventisti nel primo conflitto mondiale, si mobilita per ottenere uno scambio di ostaggi ma il governo di Vienna, vista la notorietà dello scrittore, avanza pretese che il primo ministro italiano reputa inaccettabili.

La figlia, **Lietta,** è invece costretta a trasferirsi da una parente perchè la madre la accusa di volerla avvelenare e la aggredisce.

Il primogenito torna a casa nel 1919 e nello stesso anno convince il padre a far ricoverare Antonietta in una clinica psichiatrica.

Pirandello sembra voler dimostrare in tutti i modi il suo affetto verso i figli, con il risutlato però di **intervenire** spesso **pesantemente nella loro vita.**

Alle difficoltà con i figli si accompagna tuttavia il recupero di un **rapporto più tollerante** con il proprio padre.

A partire dal 1915 Pirandello si dedica prevalentemente alla stesura di opere teatrali.

<aside>
🎭 L’**editore Treves** procede nella pubblicazione in volumi di tutte le novelle apparse su rivista e raccoglie le opere teatrali in una serie di libri dal titolo ***Maschere nude.***

</aside>

Con una lettera pubblicata sul quotidiano “L’Impero” nel 1924, Pirandello chiede pubblicamente a Mussolini la tessera del partito fascista.

<aside>
🇮🇹 L’adesione al **fascismo** da parte di un intellettuale in vista come Pirandello pochi mesi dopo l’uccisione del deputato socialista Giacomo Matteotti a opera degli ssquadristi suscita un’ondata di polemiche.

</aside>

Secondo i critici l’adesione al fascismo sono da ricercarsi in un genere di **delusione:** quella di chi, proveniente da una famiglia garibaldina a ntiborbonica, ha assistito al **fallimento degli ideali risorgimentali.**

Pirandello non rinnegherà mai aperatamente la sua scelta, ma nel tempo il suo atteggiamento diviene sempre più **critico nei confronti del regime.**

<aside>
🏆 Nel **1934** viene insignito del **premio Nobel** ma di fronte all’Accademia di Svezia non pronuncia il tradizionale discorso di ringraziamento; questa omissione è dettata dal fatto che, ormai contrario a Mussolini, non voleva trovarsi costretto a menzionare il governo italiano e il partito fascista

</aside>

Nel 1925 assume la direzione artistica del Teatro d’Arte di Roma.

Pirandello interviene tenendo vere e proprie lezioni nelle quali impone agli attori di trasformarsi nei personaggi: se i personaggi sono come “statue” create dall’autore, l’attore deve limitarsi a metterle in movimento, senza alterarle con la propria soggettività.

Pirandello apprezza particolarmente una giovane attrice, **Marta Abba.**

Tra i due nasce un legame profondo e intenso e la donna diventerà per lui compagna, ispiratrice e interprete prediletta.

Il Teatro d’Arte chiude però nel 1928 per mancanza di fondi.

Tra il 1928 e il 1934 compone una serie di testi dedicati al **mito**.

L’ultimo, *I giganti della montagna*, sarà portato a termine dal figlio sulla base di indicazioni e appunti ricevuti dal padre.

<aside>
☠️ Nel dicembre del **1936** si ammala di polmonite e muore a 69 anni nella sua casa romana, mentre terminano le riprese per la versione cinematografica del *Fu Mattia Pascal.*

</aside>

---

## Il saggio su *L’umorismo* e la poetica di Pirandello

<aside>
✍️ Pirandello scrive nel 1908 un saggio in cui espone le sue considerazioni sull’argomento “Umorismo e Comicità”.

Il testo, intitolato *L’umorismo,* è dedicato al protagonista del romanzo che nel 1904 aveva finalmente attirato su Pirandello l’interesse della critica e del pubblico.

</aside>

L’opera è strutturata in due parti: 

Nella prima lo scrittore analizza il **significato del termine** “umorismo” nelle varie lingue europee.

Nella seconda definisce le **caratteristiche proprie dell’umorismo**, con abbondanza di riferimento filosofici e letterari, ma servendosi anche di esempi concreti per illustrare il suo pensiero.

<aside>
💭 Per Pirandello nell’arte umoristica la **riflessione** assume un ruolo determinante e attivo nel processo creativo, perchè **analizza e scompone la realtà**, la presenta al lettore in un modo nuovo, suscitando in lui una particolare reazione che lo scrittore chiama “**sentimento del contrario**”.

</aside>

Secondo Pirandello, comico è ciò che suscita il riso immediato: quando un personaggio o una situazione sono il contrario di ciò che ci aspetteremmo, non possiao che metterci a ridere.

> Vecchia signora “imbellettata”
> 

Se tuttavia subentra la riflessione, se qualche elemento del testo suggerisce che quella sproporzione è determinata da una causa serie, amara, e che quel comportamento apparentemente comico risulta drammatico e doloroso per chi lo sta vivendo, al riso si unisce un **sentimento di pietà.**

L’umorismo scaturisce dunque dall’unione tra percezione e riflessione .

Altri personaggi che per Pirandello esemplificano la **concezione umoristica dell’arte** sono **don Chisciotte**, protagonista del romanzo di Miguel de Cervantes, e **don Abbondio**, nei *Promessi Sposi* di Alessandro Manzoni.

Davanti a tali personaggi il lettore prova uno **stato d’animo di perplessità**, poichè si sente come diviso tra sensazione opposte: vorrebbe ridere, e lo fa, ma il riso “è turbato”.

Pirandello poi introduce i concetti di “vita” e “forma”.

<aside>
💭 La “**vita**” è il **perpetuo divenire**, inafferrabile e irriducibile; la “**forma**” è invece la **struttura esteriore**, il proprio ruolo nel mondo.

</aside>

Gli uomini sono convinti di avere un’identità stabile, riconoscibile dagli altri, univoca.

In realtà la loro è una forma vuota, una **maschera** che indossano consapevolmente o incosapevolmente, che ciascuno attribuisce a sè e dagli altri riceve.

L’uomo per Pirandello è dunque un insieme di contraddizioni, di elementi contrastanti e incoerenti.

Caratteristica specifica dell’umorismo è proprio la “scomposizione”, ossia la **tendenza a mostrare contemporaneamente più aspetti della realta** e della natura di un personaggio.

Nell’arte umoristica le cause delle azioni umane non sono mai facilmente individuabili e separabili le une dalle altre: la **personalità** non è qualcosa di definito, stabile, coerente, ma un **magma fluido** inafferrabile, che agisce sulla base di istinti e tensioni contrastanti.

Per Pirandello l’umorismo non è soltanto oggetto di riflessione saggistica ma diviene elemento fondamentale della poetica.

In tutte le sue opere si assiste infatti alla commistione inscindibile tra elementi comici e riflessione tragica: dietro ogni fatto drammatico è in agguato l’**ombra del ridicolo,** così come in situazioni divertenti traspare un lato serio.

<aside>
💭 La **realtà** non è mai presentata come un tutto organico ma apparte **frammentata,** contradittoria, inafferrabile; secondo lo scrittore umorista non è infatti possibile arrivare a una conoscenza oggettiva e univoca del mondo e dell’uomo poichè ogni conoscenza dipende dalla percezione del soggetto. Tale approccio è definito dai critici “**relativismo conoscitivo**”

</aside>

L’uomo tuttavia cerca un modo per vivere con gli altri: come abbiamo visto, ciascuno indossa inconsapevolmente una “**maschera**”, si costruisce una “forma” che lo renda riconoscibile a chi gli sta intorno e in tal modo si illude di vivere in modo autentico e di essere libero.

<aside>
🎭 La sensazione che l’uomo prova quando scopre di indossare una maschera che non coincide con la vita autentica è di vertigine, come di chi si trovi improvvisamente sospeso sul vuoto: **tutto** ciò che fino a quel momento appariva ordinato, razionale, si rivela improvvisamente **fittizzio, casuale, insensato**.

</aside>

La prima reazione è il tentativo di cancellare questa scoperta, fare finta di nulla e riprendere la vita come prima.

Un’altra frequente reazione nei personaggi pirandelliani è quella di **fuggire dalla forma** stessa: ad esempio Mattia Pascal, ben presto però egli scopre che anche la sua **nuova identità** non è che un**’altra maschera.**

Vi sono poi alcuni personaggi che cercano un compromesso: nell’impossibilità di rifiutare del tutto la forma, tentano di ritagliarsi piccoli **momenti di libertà** attraverso l’immaginazione, per poi riprendere il proprio ruolo ordinario.

Un’altra soluzione parziale è quella di permettersi **azioni bizzarre e incoerenti**, purchè all’insaputa di tutti: se infatti gli altri vedessero il personaggio agire in quel modo lo riterrebbero pazzo; dunque, se egli non vuole compromettere la sua relazione con il mondo, è obbligato ad **agire in segreto.**

<aside>
💭 Il pessimismo di Pirandello nei confronti dell’uomo sconfina talvolta con il **nichilismo.**

Tuttavia il suo modo di avvicinarsi al mondo non è cinico ma umoristico.

</aside>

Pirandello non cessa di **soffrire con i suoi personaggi** e di provare **compassione** per la loro pena di vivere, nella quale si specchia l’assurdità della condizione umana.

Lo scrittore umorista infatti non si considera superiore ai personaggi e ai lettori, a differenza del poeta decadente.

---

# Il fu Mattia Pascal

Uscito a puntate nel 1904 il *fu Mattia Pascal* è raccolto in volume nello stesso anno e ripubblicato altre tre volte.

Il romanzo inoltre viene tradotto quasi subito in svariate lingue e viene conosciuto in tutta Europa.

A tale successo di pubblico non corrisponde però un’accoglienza iniziale altrettanto calorosa da parte della critica: molti intellettuali dell’epoca vedono nell’opera soltanto un prodotto di facile intrattenimento e, Benedetto Croce, esprime un **giudizio negativo** su Pirandello, determinando così una generale diffidenza nei confronti del suo romanzo.

Ma è negli anni Sessanta che avviene una vera e propria rivalutazione da parte della critica, con la collocazione del *Fu Mattia Pascal* in quella “rivoluzione” europea di primo Novecento che interessa la forma stessa del romanzo.

<aside>
💭 In questo libro infatti Pirandello introduce una serie di **novità** che riguardano la **struttura narrativa**, la definizione del protagonista, i temi affrontati e **sperimenta le idee fondamentali** della sua poetica, che saranno poi esposte in forma teorica nel saggio *L’umorismo.*

</aside>

La vicenda è narrata in prima persona da Mattia Pascal, nella forma di un lungo *flashback*, ed è composta di **diciotto capitoli**, che possono essere suddivisi in quattro parti:

- **prima parte,** che potremo definire “**cornice**”, protagonista è “il fu” Mattia Pascal, che si accinge a narrare la propria vicenda.
- **seconda parte** che chiameremo “**antefatto**”, copre circa tre anni di tempo, dall’inizio vero e proprio dell’azione sino alla decisione di non tornare più a casa.
- **terza parte**, che possiamo definire “il **tentativo di una nuova vita**”, il protagonista è Adriano Meis.
- **quarta parte**, che definiamo “**ritorno impossibile e ripresa della cornice**”, protagonista è “il fu” Mattia Pascal che tenta di rientrare nella sua precedente esistenza senza riuscirci.

Il *fu Mattia Pascal* è un romanzo che usa molti elementi narrativi classici, ma li ripropone in modo completamente nuovo.

Pirandello però non si limita a riutilizzare questi materiali narrativi, ma ne prende le distanze, accompagnandoli con una continua riflessione.

Alcune tra le novità pirandelliane sono:

- la **vicenda** scelta è estremamente **insolita**, tanto che venne accusata di inverosimiglianza.
- il **protagonista** non è un eroe in senso classico ma un **antieroe**, un inetto che tenta di trasgredire ma non ha mai il coraggio di ribellarsi veramente a ciò che gli appare ingiusto o detestabile.
- è presente una **focalizzazione sull’io narrato**: i fatti, sebbene siano già accaduti, sono raccontati dal punto di vista del personaggio che li sta vivendo.
- il **narratore-personaggio** riflette costantemente ma è **inattendibile:** mente a se stesso, adducendo per i propri atti troppe motivazioni, spesso contradittori, eccessivamente dettagliate oppure vaghe e imprecise.
- le **parole** non sono scelte per il loro valore evocativo e musicale, per la loro natura rara e preziosa, come nela narrativa dannunziana, ma sono **concrete e adeguate al carattere del personaggio.**

<aside>
🏡 L’ambiente, nell’orizzonte di Mattia Pascal, non offre nessuna consolazione alla solitudine dell’uomo.

Il paese natale ligure ma con caratteristiche siciliane non è inifatti un “**nido**” accogliente e familiare.

</aside>

Nel romanzo compaiono alcuni temi ricorrenti nella produzione pirandelliana, tra i quali spiccano il problema dell’identità individuale, la famiglia come trappola, il relativismo filosofico.

La vicenda di Mattia Pascal lo porta a scoprire che l’**identità** non è oggettiva e stabile, ma condizionata da mille elementi e dunque **inafferrabile e inconsistente.**

Al suo ritorno il protagonista comprende che, una volta spezzata la convenzione sociale, **nulla è più come prima.**

Il **senso di soffocamento e costrizione** si incarna nella vicenda di Mattia Pascal come mostrano i litigi con la insopportabile suocera.

Al tempo stesso, però, le **istituzioni sociali** mantengono per il protagonista un’irresistibile **forza di attrazione:** Adriano Meis infatti si duole di non poter sposare Adriana, Mattia Pascal alla fine è combattuto tra la volontà di rientrare a casa propria e quella di liberarsi per sempre dal giogo della suocera e dalle vecchie responsabilità.

A differenza di quanto avviene nei romanzi più tradizionali, a chi legge non viene chiesto di identificarsi nel personaggio ma di osservarlo e di riflettere, con un atteggiamento umoristico.

Lo stile della narrazione adotta dunque alcuni espedienti utili a generare un effetto di straniamento per obbligare il lettore a mantenere una distanza critica.

A ciò contribuiscono scelte lessicali inattese, parole che ostacolano la fluidità del racconto  perchè sono inconsuete, quasi dei veri e propri neologismi; anche le descrizioni inducono il lettore a osservare con distacco i **personaggi** quando questi risultano **eccessivi e caricaturali.**

I procedimenti linguistici che spingono il lettore a riflettere e ad osservare dall’esterno le molteplici sfaccettature della realtà sono gli **espedienti di tipo recitativo-teatrale:** appelli al lettore, interiezioni, esclamazioni, domande retoriche.

## Brani

→ La conclusione, pag. 190-192

---

# Uno, nessuno e centomila

<aside>
🗓️ Il romanzo *Uno, nessuno e centomila* è frutto di una lunghissima elaborazione: Pirandello lo inizia nel 1909 e lo porterà a compimento soltanto quindi anni dopo, nel 1925.

</aside>

Nella produzione letteraria di Pirandello questo romanzo riveste un **duplice ruolo**: da un lato chiude la stagione dei romanzi, portando alle estreme conseguenze il percorso di critica al concetto di identità iniziato con il *Fu Mattia Pascal;* dall’altro riflette il passaggio a una nuova fase di poetica.

In questa fase assume un ruolo centrale la **natura,** intesa quale energia istintiva e slancio vitale, come appunto suggerisce la conclusione di questo stesso romanzo.

L’idea principale del romanzo è sintetizzata nel titolo: il protagonista, che si è sempre creduto “uno”, ossia dotato di una personalità fissa e coerente, scopre che gli altri lo vedono in modo diverso da come egli pensa; alla sua rappresentazione di sè non si contrappone però una sola immagine alternativa, ma “centomila” diverse.

Inoltre l’idea che il protagonista ha di sè non può imporsi come la più forte o veritiera: le atlre centomila appaiono tutte parimenti legittime, per quanto limitate e inconsistenti; egli si rende così conto di essere “nessuno” e sceglie coscientemente di **rifiutare qualsiasi identità.**

La definitiva scomparsa dell’io non è percepita dal protagonista come una morte bensì come una **liberazione.**

---

Il romanzo è diviso in 8 libri.

Alla **distruzione dell’io** corrisponde la dissoluzione della struttura logica del racconto: la trama procede per sbalzi, soste riflessive, ritorni all’indietro, in una sorta di diario eterogeno in cui l’atto di dire e riflettere diventa più importante dei fatti stessi.

Il narratore parla in prima persona, in forma retrospettiva ma senza abbandonare la **focalizzazione sul personaggio,** come Mattia Pascal.

La forma predominante è quelal del monologo interiore, a cui subentra spesso una sorta di dialogo con il lettore, che viene chiamaato in causa e incalzato attraverso allocuzioni.

---

In *Uno, nessuno e centomila* compaiono molti temi propriamente pirandelliani:

- il **relativisimo assoluto**: per Pirandello non esiste un’identità nè una verità univoca, in grado di imporsi su tutte le altre.
- l’**incomunicabilità** e la **solitudine**: poichè la percezione di sé e degli altri è sempre soggettiva, si crea il paradosso per cui gli uomini non parlano davvero tra loro, ma ciascuno si rivolge all’immagine che ha dell’altro.
- la **follia**: poiché Vitangelo parla e si comporta in modo inatteso, incoerente, inspiegabile, viene considerato pazzo.

---

<aside>
🔖 Il romanzo potrebbe dunque essere letto come un esempio di autoanalisi, un modo per **liberarsi dalle angosce della vita**, proiettando sui personaggi la propria voglia di abbandonarsi all’irresponsabilità della follia.

</aside>

---

## Brani

→ Il naso e la rinuncia al proprio nome, pag. 205-208

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20121.png)

---

# ⏳ Marcel Proust

# Biografia

Marcel Proust nasce nel **1871** in un elegante sobborgo di Parigi.

I genitori appartengono all’**alta borghesia parigina**: il padre è un medico e la madre è figlia di un ricco agente di cambio ebreo.

Il bambino, piuttosto schivo e **dotato di grande sensibilità interiore**, stabilisce un legame privilegiato e quasi morboso con la madre che gli trasmette i suoi gusti letterari e artistici.

Iscritto in uno dei migliori licei della capitale, Marcel stringe alcune importanti amicizie e comincia a **frequentare i salotti dell’alta borghesia e dell’aristocrazia parigina.**

Dopo il liceo si iscrive alla Facoltà di Diritto ma frequenta al tempo stesso alcuni corsi alla Scuola di Scienze politiche e all’Università della Sorbone, dove segue le lezioni di Henri **Bergson**, il filosofo che stava rivoluzionando le nozioni di tempo e durata.

Già durante gli anni del liceo Proust collabora alla rivista “*Le Banquet*”.

Nel 1896 esce in volume la raccolta di **racconti *I piaceri e i giorni**.* 

Nel frattempo Proust ha già cominciato la stesura di un’opera che costituisce il primo abbozzo della futura *Ricerca* e che, rimasta incompiuta, verrà pubblicata postuma nel 1952 con il titolo *Jean Santeuil.*

Intanto, quando la salute glielo concede, compie alcuni viaggi in Europa, tra cui uno a Venezia con la madre.

Dopo la morte di entrambi i genitori rimane profondamente afflitto, **si isola sempre più dal mondo** dedicandosi alla stesura della sua opera di maggior impegno, ***Alla ricerca del tempo perduto***, che uscirà in sette volumi successivi dal **1913 al 1927.**

Ormai non frequenta più gli amici di un tempo e **si consacra alla sua immensa opera** scrivendo di notte e dormendo di giorno.

Ormai segregato in casa a scrivere, si ammala di bronchite nel 1922 ma rifiuta di curarsi.

Proust muore nel novembre del **1922.**

Parallelamente alla scrittura narrativa svolge un’intensa attività di critico, fin da ragazzo si dedica a un particolare tipo di esercizio letterario che consiste nell’imitare, parodiandolo, lo stile degli scrittori più celebri.

Il pensiero critico elaborato da Proust prepara e accompagna la stesura della *Ricerca.*

## Alla ricerca del tempo perduto

*Alla ricerca del tempo perduto* è un colossale ciclo romanzesco che racconta in sette libri la vita di quattro generazioni lungo un periodo di quarantacinque anni.

All’incrocio tra diversi generi, l’opera, di forte **ispirazione autobiografica**, è un **affresco della società francese** all’inizio del secolo ma anche la **storia di una vocazione artistica:** il narratore, Marcel, esteta improduttivo, scopre soltanto alla fine, dopo una lunga esperienza di tempo “perduto”, che deve diventare uno scrittore e che per riuscirci occorrerà soltanto che trascriva quello che ha già dentro di sè.

Quello che conta nel romanzo, più che l’argomento, è la struttura: la trama non segue i fatti nella loro successione logica e cronologica; il **tempo** scorre ma è continuamente **interrotto e dilatato** dal sorgere improvviso di **ricordi involontari e di riflessioni** che organizzano i frammenti del racconto secondo un **ordine più interiore che logico**, ordine instabile, fluttuante, benchè non meno rigoroso di quello razionale. Il filo che unisce l’insieme è costituito da alcuni **nuclei tematici ricorrenti** nell’intera opera, come l’amore, la gelosia, la critica, …,

> Il racconto ha la forma di un **lungo monologo interiore** e si sviluppa attraverso frasi molto estese; i dialoghi sono spesso inglobati nel discorso, e frequenti sono le parentesi e i trattini per introdurre il pensiero del narratore
> 

## Le “intermittenze del cuore”

Influenzato dagli studi filosofici di **Bergson** sul tempo come “durata” interiore, Proust costruisce la sua ricerca del tempo perduto sulla base della cosiddetta “memoria involontaria” che, diversa dalla “memoria volontaria” che è diretta dalla ragione, scatta a partire da alcune **sensazioni** le quali, in maniera imprevista, **fanno affiorare un ricordo del profondo.**

<aside>
💡 **Il tempo perduto può essere ritrovato soltanto attraverso questo tipo di memoria involontaria.**

</aside>

Con uno stimolo esterno genera nel soggetto sensazioni ed emozioni impreviste che resuscitano improvvisamente un **momento del passato in tutta la sua verità.**

## Brani

→ Le intermittenze del cuore, pag. 98 - 101

---

# 🪖 Giuseppe Ungaretti

# Giuseppe Ungaretti

<aside>
🐣 Nasce nel 1888 ad **Alessandria d’Egitto** da genitori emigrati dalla provincia di Lucca.

</aside>

A due anni perde il padre e viene allevato dalla madre in un’atmosfera familiare segnata dal lutto e dalla nostaliga: i racconti materni dell’Italia lo riempiono di meravigli ae alimentano i suoi sogni.

L’infanzia egiziana lascia un **segno incancellabile** nella sua immaginazione: la **luce accecante** del giorno e i **rumori** sinistri delle notti si imprimono nella sua memoria, mentre i paesaggi continuamente modificati dalla sabbia del **deserto** gli trasmettono un senso generale di **precarietà**, come se nulla potesse resistere all’azione corrosiva della natura e del tempo.

Ad Alessandria il giovane compie **studi rigorosi** in una scuola di lingua francese e si avvicina ai gruppi di rivoluzionari.

Ben presto gli interessi di UNgaretti si orientano verso la letteratura e la poesia, sopratttutto italiana e francese: fin dagli anni di scuola legge la prestigiosa rivista francese “Mercure de France” e inizia a collaborare ad alcuni periodici egiziani con **articoli di critica** letteraria.

Dopo avere fallito alcuni investimenti commerciali, decide di seguire la propria **vocazione letteraria** e lascia a ventiquattro anni Alessandria per recarsi a **Parigi (1912)**, che in quegli anni è la patria della cultura eropea d’avanguardia

---

Durante il viaggio verso la capitale francese Ungaretti decide di fare una **tappa in Italia**, che si materializza infine in un paesaggio profondamente diverso da quello a cui erea abituati.

La vista delle montagne gli lascia un’impressione indimenticabile: si trova infatti improvvisamente di fronte, nella **terra dei suoi avi** a uno sconosciuto **orizzonte di stabilità** e lo vive come una rivelazione improvvisa della **profondità della storia** e delle proprie radici.

Tuttavia decide di proseguire il viaggio e si stabilisce a **Parigi**.

Risalgono a questi anni i suoi primi contatti con gli intellettuali parigini legati alle **avanguardie artistiche e letterarie**: i francesi Bergson, Apollinarie e i futuristi italiani.

Ungaretti perfeziona **l’apertura cosmopolita** della propria educazione, già favorita dalla nascita in una città affollata di emigrati da ogni paese.

Parigi offre a Ungaretti la strada per giungere a una più profonda **consapevolezza di sé** e riconoscersi definitivamente come poeta.

Il lungo periodo di apprendistato culturale si concretizza infine nel febbraio del 1915, quando Ungaretti, tornato in Italia, pubblica le sue **prime poesie su “Lacerba”.**

<aside>
💭 Negli stessi mesi egli abbandona le idee anarchiche e sovversive per assumere **posizioni nazionaliste e patriottiche** e partecipa alla campagna per l’intervento dell’Italia nella Prima guerra mondiale.

</aside>

Arruolatosi come **soldato semplice**, è inviato a combattere sull’altopiano friulano nel **Carso.**

Alla disumanità della vita in trincea Ungaretti reagisce affidandosi alla **poesia**, vera e propria **esperienza conoscitiva** capace di rivelare all’uomo il senso misterioso delle cose e di restituirgli lo **slancio vitale** necessario a sopravvivere.

<aside>
📕 Nel dicembre del **1916** esce a Udine la prima raccolta di poesie di Ungaretti, ***Il porto sepolto***

</aside>

Viene stampato diverse volte con un titolo diverso: *Allegria di naufragi, Il porto sepolto,* e, infine, *L’allegria.*

Nelle **diverse stampe** la raccolta subisce revisioni e rimaneggiamenti.

---

Nel 1918 il reggimento di Ungaretti si trasferisce sul fronte francese e il poeta decide di **rimanere in Francia** anche alla fine della guerra.

<aside>
🪖 Nel 1919 Ungaretti **aderisce al Fascismo**, nel cui programma nazionalistico e sovversivo si riconoscono nel dopoguerra molti reduci delusi come lui.

</aside>

Nel 1921 lascia la Francia per stabilirsi a Roma, dove ottiene un impiego all’ufficio stampa del Ministero degli Esteri.

Sono questi gli anni in cui Ungaretti si pone il problema di conciliare la spinta rivoluzionaria e anarchica propria della sua formazione con un’**esigenza di ordine e misura.**

<aside>
📕 Sul piano letterario ciò comporta il **recupero della tradizione** e dei modelli classici della letteratura: il risultato di questa svolta di poetica è la seconda raccolta, ***Sentimenti del tempo***, pubblicata nel **1933.**

</aside>

Ungaretti sottopone le proprie poesie, anche quelle già pubblicate, a un instancavile **lavoro di risistemazione**, spostandole talvolta da una raccolta all’altra.

<aside>
📕 Una sezione di *Sentimenti del tempo*, chiamata ***Inni***, rispecchia la ocnversione di Ungaretti al **cattolicesimo.**

</aside>

Accanto all’attività di letterato, Ungaretti esercita quella di **critico letterario, traduttore e conferenziere.**

---

Nel **1936** Ungaretti acoglie l’invito a occupare la cattedra di **Letteratura italiana** dell’Università di **San Paolo del Brasile** e vi si stabilisce con la famiglia, fino al 1942.

Sul piano degli affetti familiari sono però anni di profonda afflizione, per la **morte dell’unico fratello** e la drammatica **perdita del figlio Antonietto**.

<aside>
📕 Il bisogno di superare questi lutti determina una ripresa della scrittura poetica e ispira a Ungaretti le liriche della terza breve raccolta, ***Il dolore.***

</aside>

Nel 1942 Ungaretti torna in **Italia**, accolto dal regime fascista con la nomina onorifica a membro dell’Accademia d’Italia e l’assegnazione della cattedra di Letteratura italiana contemporanea all’Università di Roma.

Nello stesso anno pubblica l’**edizione definitiva delle due prime raccolte.**

Con la caduta del fascismo Ungaretti attraversa un momento difficile: vengono infatti messi sotto accusa i suoi legami con il regime ed egli rischia di perdere la cattedra universitaria che ha ottenuto senza conoscorso.

Tuttavia recupera presto la considerazione dei lettori e dei critici e la sua **fama di poeta** si diffonde sia in Italia sia all’estero.

---

<aside>
📕 Nel **1969** a compimento di un lavoro di rielaborazione durato una vita, l’opera poetica di Ungaretti viene raccolta in un **unico volume**, intitolato *Vita d’un uomo, Tutte le poesie.*

</aside>

Non si può tuttavia affermare che sia la vita del poeta a ispirare la sua poesia: piuttosto **è la poesia a ricostruire e dare significato alla sua vita**, rivelando il poeta a se stesso e facendogli scoprire, attraverso improvvise e parziali **illuminazioni**, il senso della propria esperienza.

Anche negli anni della **vecchiaia** Ungaretti continua la sua instancabile attività di letterato e conferenziere, ricevendo importanti riconoscimenti.

La sua **vitalità** gli fa prediligere la compagnia dei giovani discepoli, con cui ama intrattenersi in **conversazioni letterarie e in letture pubbliche.**

<aside>
🪦 Di ritorno da un viaggio dagli Stati Uniti per ricevere un premio, il poeta si ammala e muore improvvisamente a Milano, nel giugno del **1970.**

</aside>

---

# La formazione e la poetica

La nascita in Egitto, in un ambiente di emigranti caratterizzato dalla mescolanza di culture e lingue differenti, favorisce l’intenazionalità della formazione intellettuale di Ungaretti, il quale si trova presto a contatto con tendenze culturali molto diverse.

Lo studio in una scuola di lingua francee e la curiosità per tutti i fermenti innovativi del pensiero lo mettono precocemente in contatto con l’**ambiente francese delle avanguardie**.

Con inesauribile energia egli assiste a lezioni e conferenze, cerca contatti con gli intellettuali, interviene nelle polemiche, partecipa attivamente all’atmosfera di **fervore creativo** che caratterizza Parigi negli anni Dieci del Novecento.

I poeti Apollinaire e Mallarmé sono considerati da Ungaretti maestri nell’arte di ricercare **nuove sonorità poetiche**: essi isolando la parola nel verso e nellap agina e privandola di punteggiatura, trasformano il testo poetico in una specie di partitura musicale.

Con i futuristi Ungaretti condivide soprattutto il bisogno di **rinnovare la parola letteraria**, la denuncia di una tradizione logora e delle sue regole, il frequente ricorso all’**analogia** per generare nuove suggestioni di senso.

FIn dal 1919 prende le distanze dagli eccessi avanguardistici e dalle “parole in libertà” di Filippo Tommaso Marinetti, riconoscendo la necessità di **valorizzare la tradizione letteraria** e individuando in Petrarca e Leopardi i suoi maestri illustri.

---

Negli anni Venti matura anche l’avversione di Ungaretti per la teoria di Freud, attraverso la polemica contro quelle avanguardie, come il Surrealismo, che applicano all’arte i principi della psicoanalisi, attribuendo al sogno e all’inconscio un ruolo centrale nell’ispirazione e nella scrittura.

La “scrittura automatica” di Breton è considerata da Ungaretti espressione di una cieca soggettività, che si limita a riprodurre sulla pagina impulsivamente il disordine dell’inconscio; la parole è invece per il poeta il risultato di un **lavoro di scavo e ricerca**, e tale sforzo non può prescindere dalla memoria della **tradizione.**

Benché la parola trovata alla fine di questo percorso abbia il potere quasi magico di accendere una luce sulle profondità segrete dell’uomo e di aprire al poeta uno **spiraglio sull’assoluto**, essa non può tuttavia esaurire il mistero irriducibile che riguarda la vita.

Proprio la convinzione che sia **impossibile fare luce sugli abissi interiori** dell’io se non per momentanee folgorazioni separa decisamente Ungaretti dalla psicoanalisi freudiana che tale mistero si propone di svelare.

---

Se il rapporto con le avanguardie nel periodo parigino è stato per Ungaretti la tappa necessaria per definirsi come poeta, negli anni successivi egli si colloca sempre più in una linea di continuità cn i classici della letteratura italiana, di cui studia il verso e il linguaggio nell’incessante sforzo di tornare, attraverso la **“memoria” della tradizione letteraria**, all’”incoscienza” originaria della lingua, al suo potere di “rivelazione” del mondo.

Egli individua in **Petrarca e Leopardi** i due poeti che hanno saputo attribuire alla lingua letteraria la facoltà di trasmettere ai lettori un’emozione estetica e una vera e propria **rivelazione di significato**.

Bisogna dunque mirare a **restituire alla parola la sua nudità, la sua primitività**, senza dimenticare la **musica della tradizione** da cui essa deriva.

Una tale accurata attenzione al fare poetico, alla ricerca della parola e al rinnovamento del metro della tradizione induce Ungaretti in diverse occasioni a polemizzare con le concezioni estetiche del filosofo **Benedetto Croce**, secondo cui la poesia consiste esclusivamente nella fantastia e nell’intuizione, mentre è **minimizzato l’aspetto formale.**

Ma **la poesia non può essere ridotta a “pura anima”**: essa è anche forma, metro, musica di secoli da cui non possiamo prescindere.

La poesia non deve nemmeno spostare l’attenzione esclusivamente sulla forma, come avviene per la poesia pura dei simbolisti.

La poesia deve essere dunque non soltanto esercizio formale, ma “atto di purificazione morale”, via al **perfezionamento interiore**, cammino verso la **verità**.

Ecco dunque individuato il compito del poeta, che da una parola scelta tra quelle della tradizione, ma rinnovata nella sua espressività, deve fare scaturire la **rivelazione di un significato** che sia anche una spinta al perfezionamento morale.

---

# L’allegria

La vicenda compositiva ed editoriale della prima raccolta poetica di Ungaretti è lunga e articolata.

Dalla prima edizione del 1916 il poeta compie un continuo lavoro di revisione che produce molteplici varianti: si aggiungono poesie, se ne tolgono altre.

Nella sua formazione definitiva la raccolta comprende cinque sezioni:

- *Ultime*
- *Il porto sepolto*
- *Naufragi*
- *Girovago*
- *Prime*

La titolazione volutamente rovesciata allude forse alla mescolanza **tra i diversi livelli temporali** della composizione.

La vicinanza con le avanguardie e il cosmopolitismo della formazione culturale consentono a Ungaretti di sentirsi libero dai condizionamenti della tradizione liricia italiana e di comporre, almeno all’inizio, una poesia **indipendente dalle forme metriche regolari.**

**Unisce le parole in modo inedito,** le isola inlunghi **silenzi**, dà loro concretezza dìimmagine incorniciandole in **spazi bianchi**: lo scopo è di restituire alle parole logorate dall’uso la capacità di esprimere nuovi significati.

I versi dell’*Allegria* presuppongono anzi una versa e propria “religione dell’arte”, una valorizzazione della poesia come **ricerca dell’assoluto”,** cioè di un **significato supremo e misterioso.**

La prima raccolta si presenta come una specie di **diario** di una ben precisa esperienza storica: quella del **soldato in trincea** durante la Prima guerra mondiale.

Accanto al titolo della maggior parte delle poesie il poeta inserisce infatti **indicazioni di tempo e di luogo**, come se volesse tenere puntualmente traccia di impressioni ed eventi della guerra.

Lo stesso Ungaretti ha voluto presentare la composizione dell’opera come il frutto di una **ispirazione occasionale**, dichiarando di avere scritto le poesie direttamente al fronte, su pezzi di carta di recupero.

Le poesie dell’*Allegria* **non sono un diario di guerra:** esse si presentano piuttosto come una riflessione sul senso della vita e della morte, sulla natura e sul tempo, sulla salvezza e sulla dannazione, e testimoniano la **tensione dell’uomo verso una condizione di armonia con il mondo,** di pace e di innocenza.

L’esperienza quotidiana della sofferenza e della morte genera nel poeta un profondo desiderio di vita; questo stretto legame tra la minaccia di soccombere e la volontà di aggrapparsi all’esistenza è all’origine del secondo titolo scelto dal poeta per la raccolta, *Allegria di Naufragi*.

La parola “allegria” potrebbe apparire poco adatta a poesie che trattano di distruzione e di morte, ma **l’ossimoro** che la unisce a “naufragi” evidenza proprio la volontà del poeta di reagire alla **rovina** della guerra con la forza dell’**istinto vitale.**

La poesia ha dunque il potere di offrire una via di salvezza: essa consente infatti al poeta **l’evasione dalla sofferenza** e dalla brutalità della guerra grazie alla capacità della parola di esprimere i **valori segreti dell’esistenza** con nuova e meravigliosa chiarezza.

La poesia assume cos’ un valore universale: l’esperienza del dolore e il bisogno di liberarsene non appartengono soltanto all’individuo, ma sono comuni a tutti gli uomini, e il poeta è colui che attraverso la faticosa ricerca della parola riesce a **esprimere la voce di tutti.**

---

## I temi dell**’Allegria.**

I temi del naufragio e dell’allegria, cioè del dolore e dell’istinto vitale, si manifestano in tutta la raccolta attraverso le immagini simboliche del buio e della luce.

La **desolazione del poeta** travolto dalla guerra, angosciato per la percezione della propria fragilità e impotente a dare un senso alla propria esperienza si traduce spesso nell’immagine del **buio che lo chiude e lo minaccia.**

Allo stesso modo il buio costituisce lo **sfondo delle esperienze più drammatiche** del poeta-soldato, come il frastuono minaccioso delle armi durante una battaglia notturna.

La luce indica invece tutto ciò che si **oppone al naufragio e all’assurdità della guerra**: si tratta a volte della luce smorzata della luna, che riesce a farsi largo tra le tenevre e accompagna le momentanee pause delle battaglie.

Altre volte è la luce piena del mattino o del giorno che sembra **cancellare temporaaneamente il dolore** e disporre il poeta ad accogliere pienamente la vita con una improvvisa eccitazione o con la percezione dell’**armonia dell’io con l’intero universo.**

Il bisogno di **evasione dalla sofferenza** si manifesta spesso come **metamorfosi dell’io** che si disumanizza, si trasforma in cosa, aspria all**’annullamento**.

Il poeta si raffigura talvolta come un minerale disanimanto, o anche come un oggetto inerte.

L’io si riduce a oggetto insignificante, sperduto in un **infinito universo** che lo opprime e gli rivela la sua nullità, oppure lo **accoglie** nella quiete, o lo **inebria** di meraviglia.

---

Nella ricerca di un senso da dare all’esperienza terribile della guerra, il poeta si confronta con Dio.

La constatazione dell’estrema **fragilità umana** e dell’universalità del dolore genera un **desiderio di trascendenza**, che si manifesta in domande piene di **scetticismo.**

La risposta oscilla nell’**incertezza**: da una parte il poeta sente di non ptersi affidare alla fede come i più semplici tra i suoi compagni, dall’altra si abbandona all’aperta preghiera a Dio, nella lirica che conclude la raccolta, perchè gli conceda una morte senza lunghe sofferenze.

L’esperienza del soldato in trincea non è fatta soltanto dell’affanno delle battaglie, ma anche di lunghe pause e interruzioni, in cui trova spazio il **ricordo**; è così per la memoria dell’amico arabo, morto suicida a Parigi prima della guerra, op er i fiumi delle città attraversate nell’infanzia e nella giovinezza.

Il sogno è anche il luogo in cui si manifesta il **desiderio dei sensi**, l’unica forma in cui è presente l’amore nell’*Allegria*: dolora **nostalgia di corpi lontani** e di abbracci perduti e sognati.

Parallelamente all’imagine dell’”uomo di pena” che si trascina nel fango della trincea, Ungaretti delinea per sè anche quella del **nomade**, del “girovago” alla ricerca di un approdo.

Mutano i paesaggi e si alternano nella raccolta le tre terre di Ungaretti: **l’Africa, l’Italia, Parigi.**

Ma anche quando il poeta, cresciuto in un **incrocio di varie culture** sembra giungere infine a riconosceri in una patria, l’Italia per cui combatte come soldato, la sua condizione di sradicamento riemerge, impedendogli di sentirsi in pace.

**La nostalgia della patria** è in realtà un’ansia dell’anima, l’illusoria ricerca di una **terra promessa dello spirito** dove sentirsi autentico e purificato.

---

## Le novità metriche e stilistiche

*Il porto sepolto* viene accolto dai lettori come un’opera di **forte rottura**.

L’innovazione radicale a cui ungaretti sottopone i modelli metrici e formali della tradizione lo identifica ben presto come il **poeta della modernità.**

L’aspetto caratteristico della poesia di Ungaretti è l’ampio territorio degli **spazi bianchi**, che appaiono come specie di luoghi fisici, spogli e silenziosi, in cui le parole risaltano con l’intensità di un grido.

In questo bianco si stagliano versi brevi, talvolta brevissimi (Versicoli), che mettono in rilievo alcune parole, a volte marginali, come articoli o preposizioni.

Così la parola diventa la protagonista assoluta del discorso poetico e il suo potere di evocare immagini e significati viene amplificato, coerentemente con una poetica che la identifica com il tramite per giungere a una verità.

Gli spazi bianchi, così come le lettere maiuscole distribuite tra i versi, si sostituiscono alla **punteggiatura**, che è completamente **assente:** scandiscono le pause e determinano il ritmo del discorso, che richiede una pronuncia molto rilevata e lenta.

Ungaretti sceglie per le poesie dell’*Allegria* parole di **registro medio**, proprie del linguaggio comune e prive di preziosismi e ricercatezze: non è la rarità a intensificarne il significato, ma il loro **emergere nude nel silenzio**, come oggetti che affiorino da un abisso.

Il loro effetto è potenziato dalle figure retoriche, in particolare dall’**analogia,** cioè dall’**accostamento imprevisto**, senza mediazioni logiche, di parole molto lontane per il significato: così il cuore del poeta è accostato a un villagio distrutto dalla guerra.

Frequentissime sono anche le **similitudini**, che fissano concretamente le parole nell’immaginazione del lettore coinvolgendo tutti i **sensi**: il pianto del poeta è inaridito come una pietra, l’aria è perforata dai colpi di fucile come un tessuto di pizzo.

Per consentire alla singola parola di emergere e di liberarsi dalle pighe del discorso, la **sintassi** è **semplice** ed è costituita da **periodi brevi**, per lo più formati da un’unica proposizione.

Dominano i **verbi alla prima persona** dell’indicativo presente, segno dell’importanza dell’esperienza diretta dell’io nella poesia di Ungaretti.

L’aspetto forse più scandaloso è la **brevità assoluta** di alcune poesie, che con pochissime parole si imprimono nel bianco immenso della pagina.

I due versi di *Mattina* appaiono ancora oggi una specie di provocazione che infrange le aspettative comuni sulla forma e la lunghezza della poesia, ma sono in realtà la coerente manifestazione di una poetica che attribuisce alla **parola nuda e isolata** la potenzialità di **illuminare interi unviersi di senso.**

## Brani

→ “Fratelli” 

→ “Sono una creatura”

→ “I fiumi”

→ “San Martino del Carso”

→ “Mattina

→ “Soldati”

→ “Veglia”

---

# Sentimento del Tempo

La seconda raccolta di Ungaretti, *Sentimento del Tempo*, esce nel 1933, ma le poesie che la compongono sono state scritte a partire dal 1919.

L’elaborazione di *Sentimento del Tempo *****va di pari passo con la revisione dell’*Allegria* e dal **1942** assumo anche il titolo *Vita d’un uomo*.

Tuttavia le differenze di poetica tra le due raccolte sono manifeste e mostrano che a partire dagli anni Venti Ungaretti assume una nuova maniera di comporre versi, più regolare.

Nelle poesie di *Sentimento del Tempo* il verso torna infatti a estendersi orizzontalmente e ai versicoli dell’*Allegria* si sostituiscono **endecasillabili e settenari**, con un chiaro abbandono degli aspetti più rivoluzionari della prima raccolta.

Tale ritorno alla tradizione rimane però confinato in *Sentimento del Tempo*, senza estendersi altrove.

Esistono dunque nell’opera di Ungaretti **due maniere poetiche differenti**, come se il poeta operasse su due tavoli di lavoro paralleli; esse confluiscono poi in un **unico disegno compositivo**, dalle forme diverse ma coesistenti.

---

Dopo l’esperienza rivoluzionaria delle avanguardie, si assiste nel dopoguerra in Italia a un generale **ritorno all’ordine** nelle arti e in letteratura.

Anche Ungaretti condivide in quel tempo la volontà diffusa di “ritrovare ordine”.

Egli però **non vuole rinunciare al verso.**

Il verso è secondo Ungaretti uno “strumento” che bisogna accordare con i tempi moderni e con la propria voce attuale, restituendogli in tal modo vita e risonanza.

Tra i poeti italiani, egli presceglie **Petrarca e Leopardi** come **modelli di armonia.**

Il titolo della raccolta, *Sentimento del Tempo*, annuncia proprio questo proposito di recuperare la percezione della **continuazione della poesia attraverso il tempo,** riconoscendo nel passato alcuni altissimi modelli a cui cercare di intonare il proprio canto e il proprio cuore.

---

In *Sentimento del Tempo* **scompare la guerra**, che era stata il tema dominante dell’*Allegria*, e domina, come un vero e proprio personaggio, la **natura,** spesso attraverso vere e proprie **personificazioni.**

Spesso il poeta si rivolge agli elementi naturali come interlocutori di un **dialogo diretto e segreto**, nell’intento di scorgere al di là dell’apparenza sensibile il **mistero** che essi custodiscono; ma è ricorrente anche il dialogo con la **morte**, cui è dedicata un’intera sezione che la rappresenta in modo piuttosto convenzionale come **approdo temuto e insieme sospirato.**

---

Con il proposito di accostare ciò che è più distante per ottenere effetti suggestivi e poetici, Ungaretti usa frequenti **metonimie**, ricorrendo a immagini concrete e materiali per descrivere l’astratto, l’immateriale.

La natura descritta con immagini così corporee appare tutavia percorsa da un respiro **divino**: vi si aggirano creature evanescenti, ninfe e divinità del mito.

Gli elementi della **mitologia classica** pagana convivono con aperti riferimenti alla **tradizione cristiana.**

Accanto alla contemplazione della **caduta dell’uomo**, debole e tentato dal peccato, troviamo il **sogno di una purezza paradisiaca**, anteriore al male.

L’uomo riconosce la propria superbia nel credersi immortale e **si rivolge a Dio**, che si è incarnato e ha sofferto per tutti gli uomini, perchè si mostri infine e lo conforti.

---

Il ritorno all’ordine nella poesia di Ungaretti si manifesta soprattutto sul piano metrico - stilistico: scompare la frantumazione metrica e vengono adottate misure più estese, torna a essere usata la **punteggiatura**, le poesie appaiono più lunghe e articolate.

La maggiore estensione del verso e dei testi non contribuisce però alla chiarezza del discorso poetico, anzi l’oscurità risulta accresciuta e diffusa nella raccolta.

Accanto a poesie in cui la lingua conserva una sua evidenza comunicativa e la sintassi si snoda in modo coerente, se ne trovano altre in cui sembra smarrirsi il rapporto tra significante e significato, e risluta molto difficile ricostruire i passaggi lodifici tra un’idea e l’altra.

Il potere evocativo delle parole è affidato agli **accostamenti inusuali**, alla **sintassi tortuosa** e soprattutto alle **analogie estreme**.

Il ricorso all’ellissi sintattica, ovvero alla **soppressione dei legami logici** tra le idee, è consapevole e mira a essere **specchio del mistero** profondo di cui la poesia vuole essere espressione.

L’esplorazione dell’ignoto richiede dunque che il poeta usi un codice diverso da quello della comunicazione, una lingua che rinunci a essere veicolo di significato e si proponga invece di accendere improvvise **suggestioni.**

Tuttavia la raccolta di Ungaretti si distingue dalle opere dei poeti ermetici successivi per una maggiore presenza di contenuti capaci di comunicare un significato; resistono al suo interno poesie che conservano una certa **comprensibilità** e non pretendono di essere contemplate unicamente come oggetti decorativi.

Ungaretti si può dunque considerare il padre dei poetici ermetici italiani, ma non compiutamente poeta ermetico egli stesso.

## Brani

→ “Di luglio” - 441

---

# Riassunto

![Screenshot 2022-05-26 at 18.28.03.png](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Screenshot_2022-05-26_at_18.28.03.png)

---

# 🕶️ Eugenio Montale

# Biografia

<aside>
🐣 Eugenio montale nasce a Genova nel **1896.**

</aside>

Il **paesaggio ligure si incide profondamente nella sua immaginazione** e diviene parte integrante della sua identità poetica.

Il mare, la tessa ssolata e arida diventeranno punti di riferimento costanti della sua prima raccolta poetica.

<aside>
🎓 Dopo le elementari, Montale frequenta le scuole tecniche in un istituto religioso, conseguendo non senza fatica il **diploma di ragioniere.**

</aside>

Non è però facile per il giovane trovare una strada che gli garantisca l’indipendenza economica: **non continua gli studi** all’università, né si trova un lavoro.

Di salute piuttosto cagionevole e di carattere introspettivo, il giovane Montale si sente **poco adatto alla vita degli affari**; egli stesso si definisce ironicamente “ricco di imprecisabili vocazioni extra-commerciali”.

In un’epoca come gli anni Venti dell’ascesa del fascismo, in cui trionfava un modello di uomo ben diverso, virile, sicuro di sè e dedito all’azione, Montale considera la propria **inettiduine alla vita attiva** non come un privilegio, bensì come un segno di diversità e di **fallimento esistenziale.**

---

Negli **ultimi anni della guerra** Montale frequenta a Parma un corso per allievi ufficiali, dove conosce Sergio Solmi, letterato torinese con cui stringe un’amicizia.

<aside>
🪖 Combatte al fronte come **volontario in Trentino**, e intanto comincia a comporre **poesie** e a tenere un **diario.**

</aside>

Tornato a Genova nel 1920 conosce Camillo Sbarbaro.

Il suo talento musicale avrebbe potuto aprirgli la carriera del cantante lirico, e per qualche anno egli effettivamente **studia da baritono**, ma nel 1923 Montale abbandona con un certo sollievo questa prospettiva, ritenendo di non avere il “sistema nervoso adatto” per affrontare il pubblico.

<aside>
📕 Il **1925** è un anno decisivo anche per l’affermazione di Montale come poeta: nel mese di giugno pubblica la prima raccolta, *Ossi di Seppia.*

</aside>

Parallelamente, Montale si dedica a un’assidua **attività di critico letterario**, manifestando anche in questo campo una posizione personal,e non assimilata a quella della cultura dominante.

Montale manifesta un vivo interesse per una letteratura aperta alle **novità culturali europee**, come la psicoanalisi e l’innovazione formale del romanzo d’avanguardia, e si sente invece estraneo all’altisonante modello dannunziano, a cui oppone le “semplici forme e talora dimesse” di Svevo.

---

<aside>
🇮🇹 Montale assume una posizione intellettualmente vicina ai primi antifascisti, pur non occupandosi mai di politica attiva.

</aside>

Nel 1927 lascia Genova per Firenze, dove la casa editrice **Bemporad gli ha offerto un impiego**; vi si adatta però con fatica perchè, obbligato a lavorare otto ore al giorno, lo considera un **ostacolo all’attività intellettuale.** 

Nel 1928 viene nominato **direttore del Gabinetto Viesseux.**

A Firenze **frequenta gli intellettuali di “Solaria”**, rivista letteraria fondata nel 1926 e considerata con sospetto dal fascismo.

<aside>
♥️ Poco dopo l’arrivo a Firenze Montale conosce **Drusilla Tanzi**, che divene la sua compagna e più tardi moglie.

</aside>

Sempre a Firenze si avvia l’altra relazione fondamentale della sua vita: nel 1933 incontra **Irma Brandeis**, con la quale stringe un legame sentimentale e spirituale che dura fino al 1938, anno in cui le leggi razziali la costringono a tornare negli Stati Uniti.

---

Dopo il **licenziamento dal Gabinetto Viesseux**, Montale vive faticosamente di traduzioni e collaborazioni a diverse riviste.

Nel **1939** escono ***Le occasioni.***

---

Durante la Seconda guerra mondiale, trascorsa a Firenze, Montale presta il proprio aiuto ad alcuni amici ebrei costretti alla clandestinità, come Umberto Saba e Carlo Levi.

Alla fine del conflitto vive una brevissima stagione di **impegno politico attivo**: per pochi mesi si iscrive infatti al **Partito d’Azione** e fa parte del Comitato per la Cultura e per l’Arte del CLN.

Già dal 1946 Montale aveva iniziato a collaborare da Firenze con il **“Corriere della Sera”**; nel 1948 è assunto dal quotidiano come redattore e si trasferisce a **Milano**, dove inizia un’intensissima **attività giornalistica**.

Il poeta può infine compiere come inviato speciale quei **viaggi** che avrebbe voluto intraprendere durante la giovinezza, per allargare i ristretti orizzonti della sua città natale.

<aside>
🏆 Nel **1975** riceve il **premio Nobel per la letteratura**.

</aside>

Milano e Firenze lo nominano cittadino onorario. 

**La perdita della moglie** Drusilla Tanzi è l’evento che induce Montale a **ricominciare a comporre versi**.

<aside>
📕 Le poesie dedicate a lei, gli ***Xenia***, appaiono nel **1971** come prima sezione di ***Satura**,* la sua quarta raccolta poetica.

</aside>

Con *Satura* inizia per Montale un nuovo periodo di intensa produzione poetica, che corrisponde a una **svolta nella sua concezione della poesia**: convinto che nella società di massa non sia più possibile una poesia alta, intellettualmente impegnata, egli compone **versi di tipo diaristico**, talvolta **satirici** e provocatoriamente **prosastici**.

<aside>
🪦 A Milano Eugenio Montale **muore il 12 settembre 1981.**

</aside>

Il funerale è celebrato a Milano nel duomo, alla presenza delle più alte cariche dello Stato.

---

# La formazione e la poetica

Montale non ha una formazione accademica: **studia da solo.**

I primi decenni del secolo sono dominati dalle Avanguardie letterarie, ma esse hanno sul giovane Montale un’influenza limitata: egli **rifiuta** gli eccessi **futuristi** e i ripigamenti sentimentali e malinconici dei **crepuscolari**.

Alcune affinità si possono cogliere comunque con la poesia di **Gozzano**, soprattutto il gusto di accostare **espressioni auliche a elementi quotidiani.**

Tra i contemporanei lascia certamente un segno anche il ligure **Sbarbaro**, di cui Montale legge le poesie di *Pianissimo.*

Quanto ai poeti della generazinoe precedente, sono in particolare Pascoli e d’Annunzio a esercitare una palese **influenza** sulla poesia di Montale, e ciò avviene soprattutto sul **piano lessicale e metrico**. 

Di Pascoli sono visibili i segni nel “gusto per la terminologia esatta e specifica, specie della flora e fauna”.

Della poesia di d’Annunzio egli apprezza soprattutto l’abile **tecnica di versificazione**, e la considera un modello imprescindibile per i moderni.

Altrettanto necessario però gli pare, per un moderno, “attraversare d’Annunzio per approdare a un territorio suo”, come ha saputo fare Gozzano.

Gli echi della **creatività verbale** dannunziana sono ben percepibili nelle tre prime raccolte montaliane, così come alcuni aspetti tematici: nei **paesaggi marini**, degli *Ossi di Seppia*, è possibile ad esempio riconoscere atmosfere affini a quelle di *Alcyone.*

**Rifiuta** le pretese di eccezzionalità della poesia dannunziana e **la funzione profetica del poeta-vate**, così come l’idea pascoliana della superiore chiaroveggenza del poeta-fanciullo.

Montale stesso ha preso apertamente le distanze dalla volontaria frattura tra poesia e significato attuata dall’Ermetismo e ha sempre manifestato una certa freddezza nei confronti di Ungaretti e della sua poetica dell’assoluto.

Non si può infine ignorare l’influsso di Dante e Leopardi nell’opera di Montale: più visibile il primo.

Dante è presente nell’opera di Montaleinnanzitutto per il **lessico**, per tutti quei vocaboli che nella *Commedia* caratterizzano il mondo infernale.

Montale sottolinea come una delle principali qualità del poeta fiorentino fosse la capacità “di rendere sensibile l’astratto”.

L’impronta dantesca è visibile anche sul **piano tematico**, nella descrizione di una condizione umana di prigionia e dannazione, così come nella presenza di **figure femminili** sul modello di Beatrice, cui è assegnato il compito di annunciatrici di una **possibile salvezza**.

Montale ha in comune con Leopardi soprattutto l’**atteggiamente disilluso** nei confronti della vita, l’idea che l’età adulta smascheri gli **inganni di una mitica giovinezza, la resistenza stoica** e dignitosa dell’uomo che affronta senza viltà una precaria condizione esistenziale, lo stretto **legame** sempre conservato tra **poesia e filosofia.**

---

Montale è stato sempre un appartato, diffidente rispetto alla storia e all’impegno sociale, quasi un **osservato esterno della vita.**

La letteratura svolge per Montale un ruolo conoscitivo: è uno strumento per **indagare le forme universali della condizione umana**, più che le questioni temporanee della storia e della politica.

Costretto a prendere coscienza della dolorosa **insensatezza della vita**, il poeta le oppone la propria fragile **volontà di resistenza**, che non si trasforma però in un nitervento diretto nella realtà.

Oggetto della poesia è dunque l’uomo, la sua condizione di esiliato nel mondo, lo spaesamento che nasce dalla **caduta di ogni sistema di certezze.**

Non soltanto il poeta è incapace di sentirsi personalmente inserito nella vita, ma avverte dolorosamente la sofferenza universale, il “male di vivere” che riguarda tutti.

Egli non può ignorare le assurde **catene della vita** che imprigionano l’uomo in una condizione di dolore.

Talora è offerto all’angoscia qualche sollievo, per quanto effimero: è l’attimo in cui il pensiero si placa e cessa momentaneamente il suo tormento, oppure l’istante in cui si può sperare nell’apparizione di una donna, una sorta di salvatrice che potrebbe rivelare il senso della vita.

Ma questo evento si compie eccezionalmente e non dura: è uno **spiraglio improvviso e provvisorio** nella rete opprimente dell’esistenza, da cui si intravede una verità che resta inafferrabile.

E tuttavia il poeta **non si rassegna**, non rinuncia all’idea che la vita debba, in qualche modo, avere un significato: la sua poesia è un’incessante ricerca di quel significa, che a volte appare debolmente, ma resta irraggiungibile. 

Il poeta non ha alcuna dote particolare che gli consenta di trovare una risposta agli interrogativi esistenziali.

Il poeta non è un individuo eccezionale, un poeta-vate con la sua enfase e il sou esibito slancio vitale; è un isolato, che si distingue dagli altri per una vocazione ineliminabile ma priva di utilità pratica: l’attitudine a **guardare oltre l’apparenza delle cose.**

La dignità morale del poeta consiste nel guardare in faccia la realtà **rifiutando le facili consolazioni** e riconoscendo il destino umano di infelicità senza illusioni o compiaciuto vittimismo.

Nelle ultime raccolte poetiche **l’assenza di significato** appare **più radicale**: la società di massa sembra avere travolto e consumato tutto, compresa la poesia.

Se fino agli anni Cinquanta Montale assegnava alla figura del poeta per lo meno la funzione di interpretare la solitudine esistenziale di ogni uomo, i versi della vecchiaia rivelano invece una maggiore disillusione sul possibile valore della poesia.

Eppure, benchè evidentemente priva di utilità per sè e per gli altri, **la poesia appartiene all’uomo,** è ineliminabile dal mondo ed **esisterà sempre.**

Nel momento stesso in cui afferma che la poesia non serve a nessuno, né agli altri né a chi la scrive, **Montale le riconosce tuttavia una inevitabile presenza nel mondo.**

---

## La poetica del “Correlativo oggettivo”

Una poesia che mira a rappresentare il dolore dell’esistenza deve porsi il problema di come affrontare una materia facilmente soggetta alle incursioni dei sentimenti.

Emblematica a questo proposito è la poesia ***Spesso il male di vivere ho incontrato***, in cui l’espressione del **dolore universale** viene affidata a elementi del **mondo non umano**.

A tale intento di oggettivazione, ovvero di rappresentazione dello stato d’animo attraverso **elementi concreti**, Montale resta fedele in tutta la sua opera, pur nel variare dei modi espressivi delle successive raccolte.

Tale procedimento, che è stato accostato alla poetica del “**correlativo oggettivo”**, consiste, come afferma Montale, nel “costruire oggetti che sprigionino il sentimento senza dichiararlo”.
Si tratta cioè di scrivere poesie in cui lo stato d’animo non sia più rivelato in modo esplicito, come in *Spesso il male di vivere ho incontrato*, ma resti **nascosto dietro oggetti concreti** su cui si siano accumulati “sensi e soprasensi”, in modo sempre meno comprensibile per il lettore.

La poetica del **correlativo oggettivo**, che affida a un oggetto la rappresentazione di un significato astratto, si collega apertamente con **l’allegoria** di Dante.

Ma se l’allegoria medievale, che si avvale di associazioni conosciuto dai lettori, era comprensibile da chi condivideva quella cultura, l’allegoria moderna appare **priva di una chiara relazione tra l’oggetto e la realtà rappresentata**, e ciò la rende difficilmente decifrabile dal lettore, che spesso non riesce ad attribuire un senso certo agli oggetti rappresentati.

Questa **oscurità irrisolta** si traduce nello **smarrimento del lettore.**

Nella loro **apparente insignificanza** essi amplificano la percezione della vanità, del **non-senso universale.**

---

Montale elabora uno strumento linguistico deliberatamente lontano dal preziosismo dei simbolisti e di d’Annunzio, alla ricerca di un **tono sobrio**, antieloquente.

Nel suo verso si può riconoscere una forte tendenza **all’esattezza terminologica** e all’ampliamento del vocabolario, anche di quello normalmente non ammesso in poesia: **termini alti** della tradizione letteraria si accompagnano a **parole dimesse** che designano oggetti quotidiani o che appartengono ai **linguaggi tecnici e settoriali**, e sono numerosi i **neologismi**.

Montale rifiuta dunque il vocabolario sublime e l’aspirazione alla solennità della tradizione poetica: sono frequenti nei suoi versi le contaminazioni tra un **lessico letterario**, scelto per la sua rarità, e **parti narrative o discorsive.**

La profonda innovazione realizzata da Montale sul piano lessicale è attenuata dalla ricorrente presenza di versi tradizionali e **rime.**

Il poeta, estraneo alla rivoluzione metrica dei futuristi e di Ungaretti, affida alla forma regolare il compito di erigere una sorta di **difesa contro il disordine** e l’incertezza della vita interiore.

---

# *Ossi di Seppia*

*Ossi di seppia* comprende poesie scritte tra il 1920 e il 1924.

Il titolo allude al **paesaggio marino**, ma è anche metafora di una **condizione esistenziale:** gli scheletri di seppia che si possono vedere sulle acque o sulle rive del mare sono da un lato emblema del desiderio da parte del poeta di dimenticare la condizione umana e di congiungersi con la natura, dall’altro metafora della degradazione dell’io, che si sente simile a uno scarto, a un relitto scarnificato e inutile.

Si respira nell’opera un’atmosfera particolare e nuova: non la magniloquenza dei versi dannunziani, le invenzioni verbali dei futuristi o gli accenti dimessi dei crepuscolari, bensì un tono dolente, che in modo sobrio dà voce alla disperazione esistenziale.

L’io lirico è sempre in primo piano ed esprime la soggettività del poeta, la sua interiorità, i suoi affetti; è un io concentrato nella **tensione a decifrare il senso del reale**, paralizzato e sospeso di fronte alla consapevolezza della vanità della vita.

In diverse occasioni Montale ha sottolineato l’importanza del **paesaggio ligure** presente in *Ossi di seppia*, e lo ha definito uno **spazio “esistenziale”,** in quanto riflesso dello stato d’animo dell’io.

Elementi ricorrenti agli *Ossi *****sono: in primo luogo il muro, che è un’immagine significativa e ripetuta, emblema del **destino di esclusione** cui l’uomo si sente condannato, e poi la **sofferenza del vivere** e la luce del sole estivo, abbagliante, nell’ora soffocante del meriggio.

Sullo sfondo domina spesso il **mare**, nei cui confronti il poeta manifesta un sentimento ambivalente: da una parte è vitalità sognata e irraggiungibile, dall’altra è forza che travolge e lascia relitti, come gli ossi di seppia abbandonati sulla spiaggia.

Gli elementi liguri del paesaggio degli *Ossi* sono spesso descritti da Montale con un’**aggettivazione** che crea il particolare tono linguistico della raccolta.

Tra le parole poetiche si trovano **termini nobili e rari** accanto ad altri più **umili e usati**, sempre però scelti con **estrema precisione.**

D’altra parte egli recupera le **misure metriche tradizionali**, soprattutto l’endecasillabo.

L’intenzione di evitare la musicalità più scontata fa sì che le parole e i suoni si urtino tra loro in **soluzioni aspre e non cantabili**, ma in cui rime, assonanze, allitterazioni suggeriscano l’esistenza di una profonda armonia.

Lo sforzo del poeta è testo a fare aderire il linguaggio all’oggetto della poesia: egli mira cioè a trovare una forma capace di esprimere la tensione conoscitiva dei suoi versi, la sua ininterrotta ricerca di un senso dell’esistenza.

La scelta è allora quella di affidare agli **oggetti** il compito di rappresentare **concetti e stati d’animo.**

Il poeta non ha tuttavia alcuna pretesa di superiorità rispetto agli altri uomini, né attribuisce alla poesia una particolare chiaroveggenza: essa non è che uno **strumento** per mezzo del quale egli conduce coraggiosamente la propria indagine sulla condizione umana.

Dallo stato di imprigionamento dell’uomo pare a volte possibile un’evasione, l’apertura di uno strappo nelle ferree leggi che determinano l’esistenza; il tema della possibilità di sfuggire anche soltanto per un attimo alla disarmonia e di **intravedere il senso** che sempre ci sfugge compare per la prima volta negli *Ossi* ma sarà costante nell’opera di Montale, che esprimerà di volta in volta questa intravista via d’uscita con **immagini metaforiche di liberazione.**

Ma il prodigio annunciato è una **speranza delusa**, non si realizza mai compiutamente, anzi, se ci si spinge al di là delle apparenze può accadere di scoprire che il segreto del mondo coincida con l’abisso del nulla.

In questa ricerca ssumono un ruolo decisivo anche i numerosi interlocutori dell’io, personaggi con o senza nome, spesso **figure femminili** lontane o perdute, che rafforzano il poeta nella sua volontà di resistenza morale o fanno balenare una **speranza di salvezza.**

## Brani

→ “Spesso il male di vivere ho incontrato” - 534

---

# Le occasioni

La seconda raccolta di Montale, *Le occasioni*, comprende poesie di **ricerca esistenziale**, in cui il poeta tenta di scorgere o di recuperare nel passato gli istanti in cui le cose sembrano promettere la possibilità di uscire dall’insensatezza della vita e di **entrare in contatto con un significato.**

Questa raccolta è costituita da **quattro sezioni**, di cui solo la seconda h aun titolo.

Nelle *Occasioni *****cambia il paesaggio: quello ligure è sostituito da quello toscano.

E’ diverso anche il clima: in generale prevale una sensazione di **angoscia**  e di **inquietudine**, conseguenza inevitabile del progressivo **oscurarsi del tempo storico,** con il consolidamento del fascismo, l’affermarsi del nazismo, l’emanazione delle leggi razziali.

Tema dominante di tutta la raccolta è l’assenza della donna amata: il poeta cerca nel mondo che lo circonda **tracce della sua donna ormai lontana**, nel tentativo speso illusorio di ritrovare e trattenere un **ricordo cui ancorare la propria esistenza.**

Anche in queste poesie gli **elementi concreti e sensibili** sono al centro della rappresentazione.

Un paesaggio, un oggetto, un animale non sono mai casuali ma **alludono a situazioni vissute**, benchè spesso imprecisate o sfuggenti.

La rappresentazione delle situazioni interiori attraverso **oggetti concreti** si realizza nelle *Occasioni* in modo più oscuro rispetto a quanto accadeva negli *Ossi di seppia*.

Montale infatti diffonde nei suoi versi oggetti che alludono a stati d’animo e a situazioni esistenziali **senza però offrire indicazioni che ne chiariscano il significato**.

In questo senso egli si spinge o ltre la poetica di *Ossi di seppia*, in cui gli elementi materiali rappresentavano esplicitamente la situazione interiore.

Il risultato è una **poesia difficile**, impegnativa**, dai molti possibili significati.**

La poesia delle *Occasioni* è certo di difficil einterpretazione, ma non è il frutto di una oscurità deliberata e programmatica, come quella cercata dai poeti ermetici.

Montale si propone infatti di **non smarrire il senso delle parole e la coerenza tra le frasi**.

Montale non è interessato a una poesia volutamente indecifrabile, resta per lui un’esigenza irrinunciabile lo **sforzo di capire il mondo**, l’aspirazione alla chiaroveggenza.

---

Di questa virtù illuminante e chiarificatrice sono portatrici le donne.

La donna si definisce progressivamente come colei che almeno per un istante può rischiarare il buio del presente, fino ad assumere **caratteristiche quasi divine**, soprannaturali.

Le *Occasioni* sono la narrazione di un **amore “in assenza”,** un dialogo ininterrotto con una donna lontana, partita per sempre o smarrita nell’oscurità della memoria.

Sono molte le donne delle *Occasioni*.

La vera protagonista delle *Occasioni ***è Irma Brandesi****,****** la studiosa americana con cui Montale ebbe una relazione d’amore.

Il suo nome tuttavia non compare mai, le sarà attribuito lo pseudonimo di **Clizia.**

**Creatura salvifica** venuta dal cielo a offrire soccorso al poeta smarrito per la sua assenza.

Le sue improvvise appirizioni ce la mostrano astratta e concentrata come un **visiting angel**, **capace di salvare dal male**, benchè ella stessa colpita dal male e dalla sofferenza.

---

Nelle *Occasioni* convivono **registri linguistici differenti**: parole appartenenti al linguaggio quotidiano, proprie del parlato, si trovano mescolate con termini più rari, di derivazione letteraria.

Sul piano della metrica nelle *Occasioni* c’è un recupero dei **versi tradizionali**, prevalentemente **l’endecasillabo.**

## Brani

→ “Ti libero la fronte dai ghiaccioli” - 552

---

# Satura

Montale trascorre **dieci anni in un quasi totale silenzio poetico**.

Tuttavia, componendo alcuni epigrammi in coda ai suoi articoli, afferma di avere iniziato a riconoscere in sé un’inclinazione verso una poesia più vicina alla **lingua quotidiana** e ai **ritmi della prosa**.

L’abbassamento discorsivo del linguaggio deriva da una fondamentale novità tematica: il poetea è immerso nella società massificata e meccanizzata degli anni Sessanta del Novecento.

E’ per lui un **mondo dominato dall’apparenza**, in cui non sembrano più trovare spazio i valori intellettuali e umanistici che erano stati l’essenza della sua formazione.

Il titolo offre una **chiave di lettura** della raccolta: la parola latina *satura* indica infatti un piatto di varie primizie offerto agli dèi, e già nella letteratura latina si riferiva a **testi di temi e linguaggi molto diversi**, spesso ironici.

L’intenzione di Montale è di sotolineare la varietà tematica e la **prevalenza del registro ironico** nella raccolta.

La raccolta è divisa in quattro sezioni: Xenia I, Xenia II, Satura I, Satura II.

Le poesie delle prime due sezioni si presentano perciò come **offerte del poeta alla memoria della moglie morta**, in un tono insieme addolorato e ironico.

Convinto della propria radicale estranietà a un mondo in cui **i valori della letteratura vengono emarginati** e prevalgono ideologie e fedi che non gli è possibile condividere, Montale accetta il proprio isolamento senza dissimulare né attenuare la propria amare consapevolezza della condizione umana.

E’ evidente il gusto del poeta per le affermazioni illogiche e per i **giochi di parole**; si tratta di frasi che si sottraggono a un senso razionale e comunicano nella loro contraddittorietà un’**immagine assurda del reale.**

**Il confine tra vita e morte è sempre più incerto**, la vita appare misteriosa tanto quanto la morte, e il paradosso è che l’esistenza è tanto insignificante che si può credere di essere morti senza saperlo.

Domina incontrastata la figura della moglie **Mosca, rievocata dopo la morte** attraverso i minimi **atti della sua esistenza quotidiana**.

La donna **perde il proprio ruolo di annunciatrice di senso** semplicemente perchè non sembra più possibile trovare un senso nel mondo e nella storia: tutto sfugge.

Tuttavia, seppure in modo diverso, Mosca assolve alla stessa funzione rivestita dalle altre donne che hanno accompagnato il poeta e ispirato la tua poesia: **gli dà soccoro nella sua inettitudine ad affrontare la vita.**

Eppure questa donna che Montale doveva sentire così radicalmente diversa da sé non era una donna ordinaria: capace di affrontare la sofferenza fisica, ella era **ricca di istintiva vitalità,** e amava tutto ciò che interrompeva il corso monotono dell’esistenza.

Da quando Mosca non c’è più il **poeta la cerca negli oggetti quotidiani**, nel ricordo delle lunghe telefonate, ed è infine costretto a confessarle il proprio **peregrinare sulle sue tracce.**

Tutti gli *Xenia* sono l’affettuosa rievocazione del rapporto con la moglie.

Tuttavia il tono delle poesie **non risulta mai lamentoso**.

E’ questa una costante dello stile di Montale, che reagisce alla commozione con deliberati abbassamenti di tono, scegliendo **registri ironici, leggeri, disinvolti** e rinunciando ai modi stilistici patetici e tragici con cui viene tradizionalmente trattato il tema della morte.

---

**Il tono prosastico e narrativo** dei testi li distingue da quelli delle raccolte precedenti.

Il lettore percepisce che è mutata l’idea stessa della poesia: essa **cessa di essere un mezzo di rivelazione**, sia pur intermittente, di verità, e diventa uno “strumento quotidiano e quasi immediato, valido accanto a altri, di osservazione e riflessione”:

La scrittura assume un carattere diaristico e occasionale.

Accanto alle parole tratte dall’**uso colloquiale** se ne incontrano di più ricercate e letterarie.

L’effetto generale di questa mescolanza non è lo scarto dal quotidiano, ma la sua riaffermazione, ottenuta attraverso l’**abbassamento ironico della lingua letteraria**.

Si moltiplicano inoltre le **parole straniere**, soprattutto anglosassoni, e i **giochi di parole,**  come se il poeta volesse sperimentare ogni modo di esprimere il reale di fronte alla sua essenza incomprensibile e dunque ineffabile.

## Brani

→ “Avevamo studiato per l’aldilà” - 570

→ “Ho sceso dandoti il braccio” - 572

---

# Riassunto

![Screenshot 2022-05-26 at 18.28.21.png](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Screenshot_2022-05-26_at_18.28.21.png)

---

# 🤐 Salvatore Quasimodo

# Biografia

<aside>
🐣 Quasimodo nasce a Modica, vicino a Ragusa, nel **1901.**

</aside>

Il padre è trasferito a Messina subito dopo il disastroso **terremoto del 1908.**

Lo spettacolo del **dolore** e della **devastazione** naturale si imprime in modo indelebile nella mente del bambino.

Quasimodo non compie studi classici ma viene avviato **all’istruzione tecnica**; si iscrive poi alla facoltà di Ingegneria a Roma, tuttavia deve interrompere gli studi per ragioni economiche e si adatta a svolgere **molti mestieri.**

Nel frattempo matura in lui una intensa **passione per la poesia**.

Inizia a scrivere testi poetici e parallelamente studia con caparbietà e rigore il latino e il greco, sotto la guida di un **insegnante privato.**

Per seguire la sua vocazione letteraria si trasferisce a **Firenze** nel 1929 e viene introdotto nell’ambiente intellettuale della città. L’anno dopo esce la sua prima **raccolta** *Acque e terre.*

---

Nel 1938 decide finalmente di abbandonare il lavoro di geometra cibile e **inizia a lavorare nell’editoria.**

Nel 1940 pubblica la sua tradizione dei *Lirici greci***,** che suscita **polemiche nel mondo accademico** ma generale apprezzamento per la resa poetica, e l’anno successivo è nominato insegnante di Letteratura italiana al conservatorio di Milano.

Nel 1943 è denunciato da una spia come antifascista, ma non viene arrestato; non prende parte attivamente alla Resistenza ma dopo la guerra **si iscrive al Partito comunista**, benchè la sua militanza politica duri pochi anni.

<aside>
🏆 Nel **1959** gli viene assegnato il **premio Nobel per la Letteratura.**

</aside>

L’attribuzione del premio suscita **vivaci contestazioni** nell’ambiente intellettuale italiano.

<aside>
🪦 Muore improvvisamente nel 1968 per un’emoraggia celebrale.

</aside>

---

## L’evoluzione poetica

Quasimodo porta all’esasperazione il modello di espressione poetica derivato dalle poesie di Giuseppe Ungaretti, poi confluite in *Sentimento del tempo*: adotta infatti un **linguaggio oscuro**, quasi indecifrabile, che tende alla brevità estrema e al frammento.

Elemento cardine di questa poesia non è il verso, ma la **singola parola**, che cessa di essere un mezzo di comunicazione verso l’esterno per trasformarsi in **strumento di indagine** proprio dell’io lirico.

Le poesie scritte da Quasimodo in questi anni contribuiscono a stabilire alcune delle costanti poi considerate dalla critica come proprie dello stile ermetico: la **brevità**, la presenza di **sostantivi privi di articoli**, la prevalenza di **termini astratti, l’anomalia delle costruzioni** sintattiche, la densità di **analogie** e **metafore**, la ricerca di una intensa **musicalità.**

A differenza di altri poeti ermetici, Quasimodo introduce nella sua poesia temi autobiografici, primo tra tutti quello della **Sicilia arcaica** e leggendaria, con profonde radici greche, evocata attraverso **elementi simbolici del paesaggio.**

Si aggiungono il tema dell’**infanzia**, la condizione di **esilio** della terra natale, la presenza dei **morti, la fragilità** della carne.

Le raccolte pubblicate a partire dagli anni Quaranta mostrano la **svolta profonda** che si determina in Quasimodo dopo l’esperienza della Seconda guerra mondiale e il **contatto con il dolore** inflitto dagli uomini ad altri uomini.

Temi centrali della riflessione di Quasimodo divengono ora la **guerra, la violenza** che stravolge la natura umana, la condizione dell’uomo in quanto membro di una **collettività civile.**

Il linguaggio si adegua alla nuova esigenza comunicativa e diviene più **concreto e aperto**, sebbene mantenga alcuni elementi retorici della precedente stagione come la diffusa presenza di sinestesie, metafore, antitesi.

Nella metrica viene abbandonata la tendenza al frammento e prevalgono gli **endecasillabili, i settenari e i quinari.**

## Brani

→ “Ed è subito sera” - 373

→ “Alle fronde dei salici” - scheda

→ “Uomo del mio tempo” - 379

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20122.png)

---

# 🧪 Primo Levi

# Biografia

Da ragazzo Primo Levi mostra un carattere schivo e giudizioso: vive a Torino frequentando pochi amici, studia, legge, cammina in montagna.

Questa vita iniziata per scorrere come tante altre viene travolta all’improvviso dal Lager: a ventiquattro anni Levi **viene deportato ad Auschwitz**, dove rimane per undici mesi. Al suo ritorno nulla è più come prima.

Il ragazzo appartato e tranquillo non essite più, e Levi inizia una **lunga battaglia contro la disumanità** di cui è stato testimone.

É una lotta fatta di libri, di lezioni e di dibattiti che lo trasforma in un intellettuale dalla parola limpida e autorevole, sempre più ascoltato, riconosciuto, stimato.

Due sono dunque le vite di Levi: la prima, ordinata e tranquilla, chiusa nel piccolo ambiente dei giovani studenti torinesi; la seconda, dopo la frattura del Lager, sempre più pubblica e condivisa.

---

<aside>
🐣 Primo Levi nasce a Torino il **31 Luglio 1919** da un’antica famiglia ebraica piemontese.

</aside>

Il padre, Cesare, è un ingegnere elttrotecnica, la madre, Ester Luzzati, è una giovane di ventiquattro anni.

Dopo avere frequentato il licelo classico di Torino si iscrive alla facoltà di **Chimica**, attratto da una disciplina che gli pare offrire un codice per capire l’universo.

Già al liceo le discipline scientifiche sembrano a Levi più ricche di risposte di quelle umanistiche: talmente scarso è il suo interesse per la letteratura che all’esmae di maturità viene rimandato nel tema di italiano.

All’Università si appassiona immediatamente alle lezioni dei suoi professori, ma l’anno successivo alla sua iscrizione vengono emanate le **leggi raziali** (1938).

<aside>
🎓 Nel 1941 **si laurea a pieni voti**, con lode: in seguito esprimerà la convinzione che l’eccellenza di quel risultato fosse un modo, da parte dei professori, di manifestare indirettamente il proprio dissenso verso le leggi antisemite.

</aside>

Subito dopo la laurea Levi deve cercarsi un lavoro: il padre infatti muore lo stesso anno di tumore e il giovane si preoccupare di provvedere economicamente alla famiglia.

<aside>
🪖 Levi intanto si avvicina al Partito d’azione clandestino e dopo l’armistizio dell’8 settembre 1943 compie una scelta politica: insiieme con alcuni dei suoi amici decide di **aderire alle formazioni partigiane** antifasciste che si stavano costituendo sulle montagne.

</aside>

Il 13 dicembre **viene arrestato dai fascisti**; dopo due mesi rrascorsi nel campo di concentramento di Fossoli, il 22 febbraio 1944 Levi è deportato ad Auschwitz.

---

Levi trascorre nel Lager unidici mesi, da febbraio 1944 a gennaio 1945, quanto le truppe russe liberano il campo di Auschwitz; il viaggio di ritorno seguirà un **lungo e tortuoso tragitto** attraverso l’Europa centrale e durerà da giugno a ottobre del 1945.

L’arrivo a casa, a Torino, non porta con sè la gioia sperata.

Tormentato dal dolore per l’esperienza del Lager e dal **senso di colpa** per essere sopravvissuto a tanti compagni che gli parevano migliori di lui, Levi sta male.

La fine della guerra è vissuta con sollievo dagli italiani: i partigiani raccontano le loro imprese e vengono trattati da eroi, mentre i reduci dai Lager sentono tutto il peso della prigionia e dell’umiliazione subita; nessuno vuole ascoltare i loro racconti.

Ora tutti voglio guardare avanti, dimenticare.

Per Levi **la memoria è un imperativo** in primo luogo personale, per liberarsi da un peso insostenibile, poi morale e civile, per garantire il ricordo dovuto ai morti e proteggere i vivi dal ripetersi del male.

Già nel Lager egli era riuscito ad annotare poche righe con altissimo rischio; nel gennaio **1946** trova un impiego in una fabbrica di vernici vicino a Torino in cui per un po’ di tempo non gli viene assegnato un compito preciso, e **scrive in pochi mesi *Se questo è un uomo**.*

Il libro è pronto nel 1947, ma l’editore Einaudi, a cui Levi lo propone, non vuole pubblicarlo: i tempi non sembrano adatti a vendere libri tanto dolorosi.

Lo pubblica invece una piccola casa editrice torinese, ne venderà solamente poco più della metà.

<aside>
💍 Nello stesso mese di gennaio 1946 Levi conosce per caso **Lucia Morpurgo**, di cui si innamora e che lo aiuta a ritrovare la voglia di vivere.

Nel settembre 1947 Levi sposa Lucia, da cui avrà due figli.

</aside>

---

<aside>
🔖 Dopo la nuova pubblicazione di *Se questo è un uomo* da parte della casa editrice Einaudi nel 1958, esce ***La tregua***, il libro di memoria che racconta il lungo ritorno ad Auschwitz.

</aside>

L’opera ottiene il premio letterario Campiello, ma i critici faticano ancora ad accettare l’idea che Levi sia uno scrittore e tendono a ridurne il ruolo a quello di testimone.

In quegli stessi anni Sessanta Levi **orienta la sua scrittura verso l’invenzione**: con lo pseudonimo di Damiano Malabaila pubblica una raccolta di quindi racconti intitolata ***Storie naturali***.

Si tratta di testi in gran parte di tema fantascientifico, spesso brevi e con una forte impronta morale.

Una seconda raccolta di racconti, intitolata ***Vizio di forma***, esce nel 1971, questa volta con il nome di Levi, ma ottiene dai lettori un tiepido interesse.

---

<aside>
🔖 Con la pubblicazione del ***Sistema periodico (1975),*** la raccolta di racconti “sulla chimica e sui chimici” concepita per parlare del suo mestiere, Levi diventa scrittore a tempo pieno.

</aside>

Nello stesso anno infatti dà le sue dimissioni dalla fabbrica di vernici.

Anche in questo libro la memoria è presente, sia quella autobiografica del giovane studioso sia quella del Lager, che ritorna di tanto in tanto come tetro orizzonte delle vicende narrate.

<aside>
🔖 Tre anni dopo, nel 1978, Levi pubblica il suo primo romanzo di piena invenzione, ***La chiave a stella.***

</aside>

Storia di un montatore di gru che gira il mondo per svolgere il suo mestiere, sostenuto dalla convinzione che la vera felicità a cui l’uomo può asprirare è quella del “lavoro ben fatto”.

<aside>
💭 In tutte le opere di Levi, sia di testimonianza sia d’invenzione, si può cogliere un tratto costante della sua personalità di scrittore: la curiostià per la natura umana, l’interesse per le sfumature dei caratteri e dei modi di vivere insieme, il grande valore attribuito alla dignità dell’uomo.

</aside>

É come se anche nelle opere di fantasia Levi non potesse fare a meno di parlare della propria esperienza, del proprio bisogno di **comprendere l’uomo e i fatti della storia**.

---

Intanto Levi è divenuto sempre più un personaggio pubblico: a partire dagli anni Sessanta le sue opere sono tradotte in moolti paesi stranieri.

Nelle scuole si diffonde la lettura dei suoi libri, proprio con i ragazzi delle scuole Levi si è assunto l’impegno della **trasmissione della memoria**.

Intanto, a partire dalla fine degli anni Settanta, si diffonde in Europa il fenomeno del **revisionismo storico**, ovvero l’esplicita negazione della verità storica dello sterminio nazista da parte di intellettuali di diversi paesi, compresi quelli tedeschi.

La memoria del Lager, mai veramente accantonata nella scrittura di Levi, compresa quella d’invenzione, torna a essere il tema centrale della sua ultima opera.

Lo scrittore sente il bisogno di una **riflessione più ampia e documentata sul Lager** che tocchi i principali problemi filosofici, morali, storici sollevati da quella esperienza.

Il frutto di questa analisi critica è il saggio ***I sommersi e i salvati*** uscito nel **1986,** è l’opera più impegnata e alta di Levi, un vero e proprio **testamento intellettuale.**

Si aggrava intanto la **crisi depressiva** di cui Levi soffre periodicamente.

Il ricovero per un intervento chirurgico e la necessità di accudire nella propria casa l’anziana madre e la suocera gravemetne ammalate accrescono la prostrazione dello scrittore.

<aside>
☠️ L’11 aprile 1987 Levi muore a 67 anni nella sua casa di Torino, lasciandosi cadere nella tromba delle scale.

</aside>

---

# La chiave a stella

*La chiave a stella* è un’ “antologia di avventure di lavoro”, cioè la narrazione in quattordici episodi delle **vicissitudini di un operario** che gira il mondo per svolgere il mestiere di montatore di gru e tralicci industriali.

La vicenda ha la forma di **dialogo** tra un narratore, chimico e scrittore, ovvero Levi, e l’operaio Libertino Faussone, che nella **lingua semplice e diretta** di un uomo illetterato gli racconta la sua esperienza.

Il protagonista del libro riferisce dunque la sua vicenda da **testimone diretto,** proprio come ha fatto Levi in *Se questo è un uomo* e *La tregua,* ma in questo caso le vicende e il personaggio sono **frutto di fantasia.**

L’idea del libro nasce da una **lettura** e da un **viaggio.**

Le quattordici storie raccontate nel libro derivano anche dai racconti degli amici e da letture di articoli su riviste specializzate o manuali tecnici.

A partire da questo vario materiale lo scrittore inventa le avventure di Faussone, sentendosi per la prima volta **libero**, come dichiara in un’intervista del 1979, **dal dovere di verità** che si era imposto per i libri sul Lager.

Il tema centrale dei racconti di *La chiave a stella* è quello del lavoro, inteso come un’opportunità di **realizzazione di sé** per chi ha la possibilità di svolgerlo con competenza e passione.

Levi evidenzia **il valore liberatorio e gratificante** del lavoro compiuto **a regola d’arte**.

Il perfezionismo tecnico, l’orgoglio professionale, la responsabilità per l’esito della propria opera costituiscono la base dell’appagamento che si può trarre da ogni mestiere.

Nel libro viene infatti valorizzato il laboro come **atto “creativo”,** cioè svolto grazie a una specifica abilità tecnica, e respinta invece l’opinione secondo cui il lavoro è “un’espressione puramente servile dell’uomo”.

Attraverso un mestiere liberamente scelto l’uomo infatti costruisce se stesso, e dagli errori compiuti apprende il modo per non ripeterli, perfezionando la propria capacità di affrontare i problemi e ricavando piacere dal miglioramento di sé.

La principale novità è la lingua: Levi ha voluto infatti riprodurre nel libro la cadenza del **dialetto piemontese** popolare parlato dal protagonista.

Sono frequenti anche le irregolarità grammaticali proprie della **lingua parlata da una persona poco colta.**

Per sottolineare il carattere **illitterato** della lingua di Faussone, Levi si avvale anche della grafia “all’italiana” delle parole straniere.

Lo scarto della lingua rispetto a quella curata ed elegante fino ad allora usata da Levi nei suoi libri è frutto di una sua scelta consapevole, nata dalla volontà di **aderire con la scrittura alla vita vera.**

## Brani

→ Pensare con le mani, pag. 755-758

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20123.png)

---

# ⛰️ Italo Calvino

# Biografia

Italo Calvino si è sempre presentato come un uomo **riluttante a parlarse di sé,** dati biografici non ne dava mai o li dava falsi.

Erano inoltre ben note la sua **timidezza** nel parlare e la sua indole restia a condurre una conversazione.

Eppure ha rilasciato nella sua vita più di **duecento interviste**.

Come si spiega questa **contraddizione?** Consapevole della funzione che l’intellettuale riveste nella società del secondo Novecento, Calvino non si sottrae alle domande e al confronto, e accetta il suo ruolo pubblico, tuttavia è molto **attento alla propria immagne.**

Porge con discrezione una chiave di lettura di sé, quella dell’uomo coerente ma no nstatico, mai appagato né immobile.

<aside>
🐣 Italo Calvino nasce nel **1923** in una famiglia di scienziati

</aside>

Il padre è un agronomo di fama internazionale, la madre è laureata in scienze naturali.

Tuttavia quello **sguardo scientifico sulla realtà** a cui Calvino sembra dichiararsi estraneo non manca di alsciare tracce nella sua produzione letteraria, manifestandosi come desiderio di esattezza.

Proprio a causa dell’attività lavorativa del padre Calvino nasce lontano dall’Italia, a **Santiago de Las Vegas,** a Cuba.

Il paesaggio che però continuerà a ripresentarsi nei suoi libri come ambiente naturale persistente è quello di Sanremo, in Liguria, dove la sua famiglia si trasferisce a metà degli anni Venti.

A quell’epoca Sanremo rappresenta una cittadina **cosmopolita**, luogo d’incontro popolato di figure interessanti ed eccentriche provenienti da tutta Europa.

Qui Calvino trascorre l’infanzia e l’adolecenza, in un **ambiente benestante e laico**, senza una vera consapevolezza dei contrasti politici che agitano l’Italia fascista.

I suoi genitori sono ostili a Mussolini, ma più per un rifiuto dell’arroganza e della volgarità fasciste che per una vera scelta politica; per molto tempo il giovane Calvino non sente la necessità di assumere posizioni nette.

Negli anni liceali scrive i **primi racconti**, ma la sua passione per la letteratura resta un **segreto inconfessabile** in famiglia.

Per tradizione familiare si iscrive dunque alla **facoltà di Agraria** a Torino e sostiene i primi esami.

<aside>
💭 Nel 1943 la sua posizione politica diviene più definita: festeggia con gli amici la caduta di Mussolini.

</aside>

Poi, l’8 Settembre 1943, **si sottrae alla chiamata alle armi** della Repubblica di Salò e nel 1944 si unisce ad una brigata comunista.

L’esperienza della **guerra partigiana** segna per lui il passaggio da una fase della vita ad un’altra: dal mondo protetto del ragazzo borghese si vede improvvisamente proiettato in una condizione adulta.

Nelle brigate dei partigiani percepisce contraddizioni ed elementi incomprensibili, ma anche un desiderio di riscatto.

Nel dopoguerra pertanto aderisce al Partito comunista e inizia un periodo di **attiva militanza politica.**

---

Nel 1945 si trasferisce a Torino, abbandona gli studi di agraria e si iscrive a Lettere; diviene **amico di Cesare Pavese.**

<aside>
💼 Il 1946 è l’anno in cui Calvino inizia a collaborare con la casa Editrice Einaudi, e il suo primo incarico è quello di **vendere libri a rate.**

</aside>

Non è un periodo semplice dal punto di vista economico; vive in una “gelida soffitta torinese” vicina alla stazione.

Spesso per guadagnare qualcosa rivende l’olio ligure portato da casa.

Riesce però a pubblicare alcuni racconti sui quotidiani e in pochi mesi scrive il suo **primo romanzo,** *Il sentiero dei nidi di ragno*, dedicato all’esperienza della lotta partigiana, che l’editore Einaudi accetta di pubblicare nel 1947.

Progressivamente la posizione di Calvino presso Einaudi diviene più significativa: passa a occuparsi dell’ufficio stampa, poi dal 1950 è **assunto** stabilmente **come redattore.**

Tra i suoi compiti vi è anche quello di **esaminare manoscritti** e di rispondere a coloro che non saranno mai scelti per la pubblicazione.

Nella casa editrice Calvino ha soprattutto la possibliità di **inserirsi nel gruppo intellettuale** che più di ogni altro delinea il panorama culturale italiano del dopoguerra.

---

Fondamentale nella giovinezza di Calvino è **l’esperienza politica**.

Con l’adesione al Partito comuinsta inizia per lui un periodo di attiva militanza.

Collabora con l’organo principale del partito, partecipa a incontri e dibattiti, si accosta al movimento operaio.

Tuttavia in lui viene maturando un **dissidio** tra il desiderio di essere al servizio della verità e della giustizia sociale e l’obbligo di giustificare i metodi autoritari sovietici per ordine del partito.

Quando nel 1956 il segretario Chruscev denuncia i crimini di Stalin e apre un percorso di rinnovamento, Calvino si impegna nel dibattito interno al PCI affinchè il partito elabori una **linea italiana per il comunismo**, pienamente autonoma da quella sovietica.

Le sue attese però vanno deluse: nell’ottobre del 1956 **la rivoluzione ungherese** viene **repressa con violenza** dai carri armati russi.

Calvino **lascia il partito** e rinuncia alla collaborazione con “l’Unità”, spiegando le sue ragioni in un lungo articolo nell’agosto del **1957**.

Dopo alcuni mesi di silenzio, Calvino si impegna nuovamente su **temi d’attualità** e scrive alcuni lucidi saggi sulla crisi dello spirito rivoluzionario e sulle avanguardie ideologiche marxiste.

Nella sua esperienza di narratore, Calvino ha manifestato un continuo desiderio di “cambiare rotta”, di **ricercare** sempre **forme espressive nuove.**

Negli anni Cinquanta pubblica una **trilogia di racconti fantastico - allegorici** (*Il visconte dimezzato, il barone rampante, il cavaliere inesistente),* cura una scelta e trascrizione di duecento **fiabe** della tradizione folkloristica regionale, raccoglie una cospicua antologia di suoi ***Racconti*** e scrive un libro che affronta in modo diretto una realtà problematica del presente.

La critica si mostra fin dall’inizio piuttosto ben disposta nei suoi confronti, ma la sua **notorietà** si consolida soprattutto **negli anni Sessanta,** e Calvino riceve molte **offerte di collaborazioni** da parte di quotidiani, riviste, cinema, teatro, televisione.

Davanti a tante richieste il suo atteggiamento oscilla tra la curiosità e il timore di disperdersi. Si può dire che Calvino riesca a coniugare la disponibilità a esplorare i nuovi mezzi di comunicazione con la **disciplina rigorosa** necessaria alla scrittura.

<aside>
🔖 Nel 1963 pubblica altri due **testi realistici** e un **romanzo per ragazzi** a metà strada tra il filone fiabesco e quello realistico.

</aside>

Seguono **raccolte di racconti** che sviluppano in modo fantastico ipotesi e formule scientifiche.

---

Nel 1980 Calvino raccoglie i suoi principali contributi saggistici nel libro *Una pietra sopra**,*** con il quale sembra voler chiudere la stagione dell’”**impegno”**, ricapitolando le tappe del suo percorso di **intellettuale** chiamato a offrire nella sua epoca storica una **chiave di lettura del reale**

Calvino ne indica le tre principali fasi, corrispondenti all’incirca a tre decenni:

- il **momento militante** (anni Cinquanta), in cui ha creduto che la narrativa avesse una valenza politica;
- la **scoperta della complessità** (anni Sessanta), quando la società gli è parsa “sempre meno padroneggiabile”;
- la **perplessità sistematica** (anni Settanta), in cui viene meno la sua fiducia nella possibilità di indirizzare il corso degli eventi.

Anche nelal narrativa Calvino assume il **ruolo dell’osservatore distaccato,** che convoglia ogni energia nella descrizione.

---

Calvino dunque **interpreta** come scrittore e come intellettuale **quarant’anni di cultura italiana:** attraversa diverse correnti letterarie, come il Neorealismo.

Negli ultimi anni appare sempre meno ottimista: anche di fronte alla **fatica di comprendere il mondo**, non rinuncia mai a tenere desta una vigile **fiducia nelle capacità della ragione**, secondo il modello del razionalismo settecentesco.

---

Nell’estate **1985** Calvino labora a un **ciclo di lezioni** che gli è stato chiesto dall’Università di Harvard, ma è colto da un malore improvviso.

Viene ricoverato in un ospedale di Siena e muore pochi giorni dopo.

Gli appunti di quegli interventi usciranno postumi con il titolo di *Lezioni americane* e suggeriscono cinque **valori da conservare** per il nuovo millennio: “Leggerezza”, “Rapidità”, “Esattezza”, “Visibilità”, “Molteplicità”.

---

## La scrittura “realistica”

La partecipazione alla Resistenza è fondamentale per la formazione umana e politica di Calivino.

I mesi che trascorre insieme con le brigate partigiane comuniste sulle Preapli liguri sono per lui molto duri, ma gli permettono di **sentirsi parte di un momento storico** decisivo.

Dopo la liberazione avverte quindi come molti altri l’urgenza di raccontare, di rappresentare in tutta la loro concretezza fatti, personaggi, ambienti; desidera però trovare un modo per unire la forza dell’esperienza con la necessaria distanza dalla situazione personale, per potere creare una **rappresentazione** esemplare, in quale modo **epica**, in cui tutti si possano rispecchiare.

Sceglie dunque di ispirarsi a un ragazzino reale conosciuto nelle formazioni partigiane e di renderlo protagonista di una **storia inventata,** in cui affiorano persone e ricordi concreti, ma che vengono modificati e deformati dall’immaginazione.

<aside>
🔖 Nasce così il romanzo ***Il sentiero dei nidi di ragno***, scritto in pochi mesi e pubblicato dall’editore Einaudi.

</aside>

*Il sentiero dei nidi di ragno* può essere letto in molti modi.

É un romanzo picaresco, ossia una narrazione che vede come protagonisti **uomini di condizione sociale umile*,*** che cercano di sopravvivere grazie a una serie di espedienti e attraverso vicende tragiche e grottesche.

Nonostante i limiti umani e culturali di coloro che hanno combattuto,  per Calvino gli **ideali** della Resistenza restano validi e **degni di essere perseguiti**. Come spiega nel libro il commisario Kim, alcuni lottano per la terra, altri per migliori condizioni di lavoro, altri per vaghe idee intellettuali, altri ancora per il desiderio di una casa lontana; in tutti comunque c’è un autentico **furore**, una spinta di **riscatto umano**.

Proprio questa tensione morale trasforma anche i peggiori tra i partigiani in **protagonisti attivi e generosi.**

Nel primo romanzo di Calvino emergono anche molti elementi propri della narrazione fiabesca.

Ad esempio, il personaggio principale è un bambino che passa attraverso **numerose avventure e prove;** esiste un **luogo misterioso** e segreto in cui può rifugiarsi e nascondere il suo **tesoro,** sognando di portarvi l’amico ideale; la **pistola** è “**l’oggetto magico”** che dovrebbe servirgli per entrare definitivamente nel mondo degli adulti; **l’apparizione** di Cugino nella nebbia ricorda quella di un gigante buono, per l’aspetto fisico massiccio e il linguaggio burbero ma gentile; il gesto di Pin che getta dietro di sé nel bosco nòccioli di ciliegia, sperando così di farsi ritrovare da Lupo Rosso **rinvia alla fiaba di Pollicino.**

Quella di Pin è anche la storia di una formazione mancata.

Pin è un bambino gettato nel mondo degli adulti, che si finge forte e spregiudicato parlando di armi e di donne, ma che di fatto **continua a essere infantile**: si abbandona ai sogni e alle fantasie, cerca protezione, desidera un vero amico, vorrebbe che i grandi si interessassero come lui alle tane dei ragni.

Alla fine del libro Pin è convinto che Cugino si rechi da sua sorella come cliente, mentre il partigiano va ad ucciderla, in quanto spia dei fascisti, proprio con la pistola prestatagli dal ragazzino.

Pin non è sfiorato dal sospetto, anzi, crede con gioia alla bugia che Cugino gli racconta al suo ritorno, e **si lascia prendere per mano**, come un bambino accanto ad un padre.

Il percorso di formazione non si è compiuto: il bambino **rimane** tale, o forse Pin, che era stato costretto troppo presto a mostrarsi grande, è finalmente libero di essere un bambino inconsapevole, protetto da una figura paterna nella notte.

<aside>
🔖 Tra il 1945 e il 1948 Calvino scrive anche una **trentina di racconti** che confluiscono nel volume *Ultimo viene il corvo*, pubblicato nel 1949.

</aside>

Le storie sviluppano memorie legate alla Resistenza e alla guerra, ricordi dell’infanzia ligure, vicende ambientate nella difficile situazione sociale ed economica dell’immediato dopoguerra.

I protagonisti sono ragazzini, e Calvino **esplora possibillità narrative** differenti, compiendo veri e propri “**esercizi di stile”**.

---

# Il sentiero dei nidi di ragno

Per una nuova edizione del *Sentiero dei nidi di ragno* apparsa nel 1964, Calvino scrive una lunga *Prefazione*, che si presenta come una **riflessione dell’autore sulla propria opera.**

Tutti coloro che avevano vissuto la guerra e la Resistenza erano carichi di **storie da raccontare** e in un momento in cui finalmente era di nuovo possibile **esprimersi in libertà** si andava accumulando una sorta di “**tradizione orale**”.

Secondo Calvino, *I Malavoglia* di Giovanni **Verga** erano i **punti di riferimento** per i giovani scrittori desiderosi soprattutto di riuscire a trovare un modo per trasformare il “materiale grezzo” dell’esperienza in un’opera letteraria in grado di esprimere “il sapore aspro della vita”.

Calvino individua come radice del Neorealismo proprio questa **ricerca di una forma** in grado di dare sapore di verità a contenuti urgenti; egli sentiva di **avere a disposizione un paesaggio suo.**

L’autore ripete più volte che *Il sentiero dei nidi di ragno *****è il **primo romanzo** che ha scritto, e ne **sottolinea alcuni limiti** che attrivuisce alla sua ingenuità giovanile: il tentativo quasi folkloristico di inserire espressioni in dialetto, modi di dire popolari e canzoni.

Sentendosi protagonista di un **momento decisivo della storia**, Calvino avverte una **responsabilità** che rischia di paralizzarlo: per questo adotta il **punto di vista di un bambino**, per raccontare gli eventi da una prospettiva inconsueta.

Il modo in cui Pin guarda gli adulti corrisponde simbolicamente a quello con cui Calvino, affronta la **realtà brutale della guera partigiana.**

<aside>
💭 Lo scrittore non intende rappresentare la guerra partigiana in modo celebrativo e retorico, mostrando la **realtà** anche **imperfetta e brutale** del mondo partigiano, vuole dimostrare ai benpensanti che anche coloro che si erano gettati nella lotta senza motivazioni ideali e con tanti difetti umani erano comunque divenuti delle “forze storiche attive”, erano stati spinti da uno **slancio che li aveva resi migliori.**

Calvino afferma di avere voluto scrivere imitando lo stile asciutto di **Hemingway** e la sincerità e il vigore degli scrittori russi degli anni Venti.

</aside>

Da questo insieme di suggestioni letterarie è derivato al *Sentiero dei nidi di ragno* un inconfondibile **tono fiabesco** che Pavese è stato il primo a notare, e che Calvino riconosce come uno degli elementi caratteristici del proprio stile.

La riflessione di Calvino si chiude con l’ammissione di una parziale sconfitta. Non è *Il sentiero dei nidi di ragno* il romanzo “epico” della Resistenza.

Infine, ripensando alla propria esperienza, Calvino si rimprovera per non avere avuto la pazienza di **custodire più a lungo quel patrimonio di memorie.**

La **scrittura a “caldo”** infatti secondo Calvino brucia i ricordi, ne fissa alcuni in una forma definitiva e cancella tutti gli altri.

---

# La scrittura fantastico fiabesca e la riflessione sui problemi sociali

Poco prima della sua morte improvvisa, Calvino spiega di avere ideato a metà degli anni Cinquanta tre racconti lunghi realistici accomunati dalla scelta di una **forma narrativa tradizionale**, dalla volontà di **indagare temi del presente** e di mostrare la reazione di un intellettuale di fronte agli aspetti negativi della società e della condizione umana in generale.

Si tratta di *La speculazione edilizia, La giorna d’uno scrutatore, La nuvola di smog.*

Sebbene continui a trattare temi di attualità in romanzi realistici come *La speculazione* *edilizia* e *La nuvola di smog*, negli anni Cinquanta Calvino si dedica soprattuttto alla **narrazione fantastico - fiabesca** e ciò lo espone al rischio di essere accusato di “**disimpegno intellettuale**”.

In realtà il tentativo di Calvino è quello di **coniugare leggerezza e impegno*:*** egli inventa storie inverosimili perchè ha ben presente la natura pedagogica della fiaba, che contiene sempre un ammaesstramento morale.

Scrive pertanto tre romanzi che prendono spunto da **immagini fantastiche** ma che intendono rappresentare **tematiche esistenziali dell’uomo contemporaneo.**

Di questo periodo fanno parte: *Il visconte dimezzato, Il barone rampante, Il cavaliere inesistente.*

Nei tre romanzi si possono individuare alcune caratteristiche affini:

- si tratta di storie **inverosimili**, con protagonisti irreali;
- lo **spazio** è immaginario, il **tempo** è lontano dal presente;
- i contesti sono **storicamente riconoscibili;**
- l’**io narrante** è sempre **interno;**
- le tre storie hanno una valenza **allegorica.**

---

Negli anni Cinquanta Calvino si dedica inoltre a un accurato lavoro di ricerca e sistemazione del **patrimonio di fiabe popolari** di tutte le regioni d’Italia.

Tra le varie versioni Calvino sceglie quelle a suo giudizio più belle e originali e le **traduce dal dialetto** per renderle accessibili al pubblico.

Inoltre lo scrittore **aggiunge elementi di invenzione** là dove gli pare necessario.

Attraverso questo lavoro Calvino si convince sempre di più del fatto che tra fiaba e realtà non vi sia contrapposizione

---

# Riassunto

![Screenshot 2022-05-26 at 18.28.43.png](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Screenshot_2022-05-26_at_18.28.43.png)

---

# → Personaggi rilevanti

---

# 💭 Sigmund Freud

## Il rimosso

Secondo Freud la psiche di un soggetto è dominata da attività inconscie. La mente è paragonabile ad un iceberg 🧊 di cui l’inconscio ne è la struttura prevalente, diviso in due zone:

1. Il preconscio: contenuti temporaneamente inconsci che attraverso uno sforzo di attenzione possono essere riportati alla luce.
2. Inconscio o Rimosso: elementi che possono essere ripresi solo da particolari tecniche psicoanalitiche poichè mantenuti inconsci dalla forza chiamata rimozione.

## Accedervi

Far rilassare il paziente il più possibile e farlo abbandonare ai propri pensieri, generando una fase di transfert.

## La personalità

La personalità dell’individuo si crea a partire dall’equilibrio di tre “istanze” inconsce:

1. Es: obbedisce sempre al principio di piacere
2. Super-io: insieme delle proibizioni dell’individuo, apprese dalla società in cui vive.
3. Io: equilibra le pressioni contraddittorie tra Es e Super-Io

## Come si manifesta l’inconscio

1. Sogni: Il contenuto dei sogni cela un desiderio nascosto, interpretare i sogni significa scorgere tratti del proprio Es.
2. Contrattempi quotidiani (esempio perdere oggetto = sentimento negativo per esso)
3. Sintomi nevrotici: il sintomo nasce da impulsi dell’Es rimossi, sempre di origine sessuale.
4. Arte: la produzione artistica riflette la nostra personalità al completo
5. Religione

---

# ⏱️ Henri Bergson

## La concezione del tempo

### Tempo della scienza

Secondo Bergson il limite della scienza è di considerare il tempo come qualcosa di:

- spazializzato: successione di momenti distanti uno dall’altro, misurabili, tutti uguali.
- reversibile: qualcosa che si può ripresentare uguale a se stesso

È assimilabile a una collana di perle, tutte uguali, separabili e su una linea retta.

### Tempo della coscienza

Esiste al contrario il tempo della vita, ciò che percepiamo attraverso la nostra coscienza, e consiste in:

- Momenti che non potranno mai più ripresentarsi, irripetibili
- Momenti qualitativamente diversi uno dall’altro
- Continuo scorrere senza sosta e sovrapporsi di eventi passati, presenti e futuri.

Nella durata del tempo della coscienza non è possibile distinguere e isolare alcun momento.

È come un gomitolo perchè il nostro passato ci segue, e s’ingrossa senza sosta del presente che raccoglie sul suo cammino.

---

# → Correnti

---

# 🗿 Crepuscolarismo

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20124.png)

---

# 🔒 Ermetismo

Negli anni Trenta del Novecento nascono numerose riviste culturali che si occupani in particolare di poesia, tra cui **“Il Frontespizio”, “Letteratura”, “Solaria”.**

Alcuni luoghi delle città diventano **leggendari punti di ritrovo** degli intellettuali: il Caffè Giubbe Rosse accoglie il gruppo “Lettaratura”.

A Firenze inoltre vivono poeti non fiorentini come Montale.

Pur nella diversità degli orientamenti, gli intellettuali sono accomunati dal difficile rapporto con il regime fascista, nei confronti del quale assumo talora posizioni di **aperto dissenso**, o più frequentemente atteggiamenti di **distacco**, di **non collaborazione**, di nascosto rifiuto.

In questo contesto nasce il cosiddetto “**Ermetismo**”: non si tratta di una vera e propria “scuola” ma di un **modo di intendere e praticare la poesia** con scelte linguistiche e stilistiche affini che si sviluppa in particolare tra gli anni Trenta e Quaranta del Novecento, ma che caratterizza anche una significativa parte della produzione poetica del dopoguerra.

A Firenze giugne nel 1929 **Quasimodo** e dà alle stampe la sua prima raccolta di liriche, *Acque e terre*, nella quale si colgono alcune caratteristiche proprie del nuovo modo di fare poesia, ossia **l’estrema concentrazione verbale e la densità metaforica e analogica.**

Il termine “ermetismo” viene usato per la prima volta con accezione negativa, per designare il carattere oscuto ed elitario della nuova poesia: il nome deriva da **Ermete Trismegisto**, figura leggendaria dell’età ellenistica che in alcuni trattati avrebbe esposto **dottrine mistiche di origine egiziana**, di difficile comprensione e riservate a pochi iniziati.

I poeti ermetici manifestano una fiducia incondizionata nel **valore della letteratura**, alla quale intendono dedicare un **impegno totale**.

I poeti del gruppo degli ermetici affermano di voler attingere all’”Assoluto”: ricercano la “parola assoluta”, “l’assolutezza naturale”, la “metafisica creatività”.

Più in generale il termine “assoluto” va inteso in senso etimologico, ossia “**distacco**” **della parola da tutto ciò che è realtà concreta.**

Nei confronti del mondo, essi scelgono la distanza: di fronte al male della realtà vedono come unica soluzione possibile quella di rifugiarsi nel mondo astratto della parola poetica.

Si tratta pertanto di un “assoluto” non trasmissibile: è un’**esperienza individuale del poeta** nella sua solitudine, **non condivisa con gli altri uomini**, ai quali non sono forniti strumenti esplicativi per dotare di senso il testo.

La lingua in cui si esprime la poesia ermetica è dunque lontana dalla comunicazione ordinaria, perchè il suo scopo non è “rappresentare” ma “costruire” **oggetti verbali autonomi**, astratti, capaci di **attingere al mistero del mondo** e dell’uomo.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20125.png)

---

# 🔨 Scapigliatura

Molti giovani artisti che negli anni Sessanta e Settanta dell’Ottocento risiedono nelle grandi città del Nord Italia sono accomunati da un forte senso di **insofferenza e sfiducia** nei confronti della generazione che li ha preceduti.

Tentano di vivedere dedicandosi unicamente all’arte, ma le condizione precarie li condannano a un ruolo secondario e talvolta alla totale **emarginazione.**

Non assumono una funzione politica attiva di portavoce degli esclusi, ma scelgono di esprimere l’insoddisfazione dichiarando la loro **diversità rispetto ai modelli** apprezzati dalla media e alta borghesia.

Nei loro testi **si oppongono alle istituzioni** del nuovo Regno d’Italia.

Esprimono insomma una **volontà di rottura** contro quelli che all’epoca sono considerati “padri della patria” (Manzoni, Verdi).

Non si tratta però soltanto di scrittori e letterati, ma di giovani che amano esplorare vari campi artistici.

Carlo Righetti definisce questi come “bohème”, ovvero con un ostile di vita volutamente al di fuori delle convenzioni sociali, tipico nell’Ottocento di giovani **artisti e intellettuali parigini**.

Alcune caratteristiche del movimento sono:

- Il luogo in cui i disagi e le situazioni conflittuali emergono in modo evidente è lo **spazio cittadino moderno**
- gli scapiglati sono **giovani**
- esprimono **qualità intellettuali,** con qualche eccezione
- si sentono estranei alla loro epoca
- non hanno scrupoli **etici**
- sentono la contrapposizione tra i loro ideali e la **mancanza di denaro**
- sono impazienti e si sentono pronti a **sovvertire le regole.**

Nella **poesia** il rinnovamento è soprattutto tematico e non formale.

La provocazione si concentra sulla scelta di **argomenti insoliti e scandalosi**, presentati attraverso un **lessico diretto e inconsueto.**

Il poeta dà spazio **all’erotismo, al gusto per il macabro e il grottesco.**

Tanto nei racconti quanto nei romanzi si sceglie la strada del **realismo esasperato**, quasi espressionistico, sia quella del **fantastico**, con l’irruzione di elementi soprannaturali.

Il linguaggio è rinnovato con la **mescolanza di parole** dialettali, tecnicismi, espressioni popolari, vocaboli ricercati.

Aver contribuito a diffondere in Italia la **conoscenza di autori stranieri** e l’introduzione del **genere fantastico** nella nostra letteratura sono i meriti oggi concordemente riconosciuti alla Scapigliatura.

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20126.png)

---

# ⚗️ Realismo e naturalismo

In Francia, già a partire dagli anni Trenta dell’Ottocento, si afferma in letteratura una tendezza all’abbandono dell’irrazionalismo romantico e al recupero dell’**oggettività** e del realismo.

I precursorsi sono:

- **De Balzac;**
- “**Stendhal**”.

Stendhal indaga nei suoi romanzi le psicologie di personaggi inseriti in **vicende negative e torbide**.

Balzac invece è autore di una serie imponente di **romanzi di impianto relista** in cui compaiono più di duemila personaggi di ogni classe sociale.

Intorno al 1850 una tendenza al realismo la troviamo nell’opera di **Gustave Flaubert**, il quale raffigura personaggi ordinari fortemente condizionati dal **carattere** e dall’**ambiente sociale.**

In ***Madame Bovary*** Flaubert descrive il carattere e i desideri irealizzabili di una donna della borghesia di campagna.

---

Il Naturalismo è una particolare corrente del realismo letterario compresa tra gli anni Sessanta e gli anni Novanta dell’Ottocento, caratterizzata da uno stretto legame tra scienza e letteratura.

La storia di questo movimento è inserparabile dal pensiero e dall’opera di Emile **Zola.**

Il presupposto nuovo su cui si fonda l’opera dei naturalisti è che il **metodo sperimentale** delle scienze esatte possa essere **applicato alla scrittura letteraria**, e che la conoscenza certa dei fatti e dei comportamenti umani conduca al **progresso sociale.**

Il proposito dei naturalisti di applicare il metodo scientifico in letteratura è espressione dello spirito razionalista e scintista che domina in Francia nella seconda metà del secolo.

Il paese sta infatti vivendo un periodo di **grande prosperità.**

In questo clima di **espansione economica** la borghesia si arricchisce rapidamente e gli operai cominciano a organizzatsi in partiti e sindacati per affermare i propri diritti.

Così il romanzo contrasta la propria reputazione di leggerezza assumendo un **ruolo sociale** serio ed educativo: quello di divulgare la **conoscenza del reale** e di contribuire **al miglioramento della società**

---

# Emile Zola

Nasce a **Parigi nel 1840,** ma vive l’infanzia e l’adolescenza in Provenza.

Quando ha solo sette anni il padre muore di una polmonite contratta in cantiere.

Ben presto la famiglia si trova costretta a liquidare all’asta la società e ad affronatre gravi difficoltà economiche.

Emile abbandona gli studi e conduce una **vita disordinata** passando da un mestiere all’altro fino a quando viene assunto alla **libreria Hachette**.

Si schiera con decisione **a favore** della pittura di **Manet**  che egli apprezza per il suo spirito di verità.

Intensifica inoltre l’attività di giornalismo letterario e politico, opponendosi in modo energico alla politica di Luigi Napoleone Bonaparte, il monarca del Secondo impero.

E’ con il romanzo ***Thérèse Raquin*** che Zola imprime una svolta naturalista alla sua scrittura, suscitando le critiche indignate di chi accusa l’opera di essere troppo cruda, ai limiti della pornografia.

Negli stessi mesi inizia a concepire il progetto monumentale di **una serie di romanzi** intorno alle **vicende di una famiglia** (Rougon - Macquart) durante il Secondo Impero, costituita da venti romanzi.

La pubblicazione procede con regolarità e assicura a Zola un reddito mensile e una posizione sempre più rilevante.

Le accese critiche sollevate da alcuni romanzi - come “*L’Assommoir”* - contribuiscono a consolidare la **celebrità** dell’autore e a **diffondere le sue teorie estetiche** rivoluzionarie.

I proventi derivati dalle vendite dell’Assommoir consentono a Zola di acquistare nel 1878 una casa di campagna.

Le sue opere suscitano scandalo e vendono migliaia di copie: il nono romanzo dei **Rougon - Macquart**, che narra la vicenda di una **prostituta** nell’ambiente lussuoso dell’alta borghesia parigina, vende cinquantacinquemila copie.

A sessantadue anni muore improvvisamente di asfissia per le esalazioni di una stufa.

---

## La poetica naturalista

Il **fondamento filosofico** del Naturalismo si trova nelle teorie positiviste diffuse nel XIX secolo, secondo cui, grazie alla scienza, la **realtà** può essere **conosciuta razionalmente** in tutti i suoi aspetti.

Il saggio di Charles Darwin *L’origine delle specie* in cui lo scienziato espone la sua **teoria della selezione naturale** ispira il filosofo **Taine**, il quale identifica nella *race*, nel *milieu*, e nel *moment historique* i tre principali fattori che influenza il carattere dell’uomo.

Zola si avvicina all’idea del **determinismo sociale** che sarà fondamento della sua poetica.

L’enunciazione teorica dei principi naturalisti è esposta da Zola in tre principali riflessioni di poetica:

- La prefazione di *Thérèse Raquin*
- L’introduzione alla *Fortuna dei Rougon*
- Il saggio *Il romanzo sperimentale*

La prima qualità del romanziere naturalista è quella che Zola definisce “**il senso del reale**” cioè la capacità di osservare con scrupolo la realtà del mondo contemporaneo.

Il metodo di lavoro richiede la **meticolosa raccolta di dati**.

Oltre a osservare conc ura, il romanziere deve anche saper **riprodurre ciò che ha visto.**

Zola sottolinea dunque l’importanza dell’**individualità dello scrittore** e del suo talento non soltanto nella selezione dei fatti ma anche nella loro esposizione.

Il lavoro dello scrittore naturalista si presenta quindi come l’equivalente letterario dell’opera di un pittore impressionista, che **coglie un’impressione particolare della realtà** e la restituisce alla scrittura.

I venti romanzi dei *Rougon - Macquart *****sono uniti tra loro dai personaggi, tutti appartenenti alla **stessa famiglia**, studiata nel corso di **cinque generazioni.**

L’intenzione dell’autore è di seguire lo **sviluppo dei condizionamenti fisiologici e ambientali** a cui sono sottoposti i membri della famiglia.

La capostipite è Adèlaide Foque, che ha avuto figli da due uomini di classe sociale differente: quella borghese del marito Rougon, e quella popolare dall’amante Macquart.

Su tutti pesano le **leggi dell’ereditarietà e** quelle **dell’ambiente**; così la patologia originaria della madre, la follia, si dissemina tra i suoi discendenti manifestandosi in modi diversi.

Nel piano dell’opera Zola dichiara l’intenzione di passare in rassegna ogni ambiente sociale, compreso quello delle prostitute, degli assassini, dei marginali; il Naturalismo ha infatti l’ambizione di **vedere tutto, di rappresentare tutto**, con una particolare attenzione alla miseria economica e morale del popolo.

Il desiderio di verità che sta alla base della poetica naturalista ha un suo corrispettivo nelle scelte formali.

Per rappresentare fedelmente un ambiente sociale, Zola non esita ad adottare il linguaggio che lo caratterizza, anche quello più basso e volgare, ritenuto fino ad all’ora inacettabile in un’opera letteraria.

Nell’Assommoir ad esempio egli ricorre all’**Argot**, il gergo parlato dagli operai parigini.

Questa **contaminazione** **della lingua letteraria con la parlata popolare** è apparsa subito ai lettori un sovvertimento inaccettabile dei codici letterari, sollevando un coro di accuse.

Il secondo espediente a cui Zola ricorre per trasmettere un’impressione di realtà è l’uso generalizzato del **discorso indiretto libero**, attraverso cui egli realizza la fusione tra la voce del narratore e quella dei personaggi.

L’incertezza su chi stia parlando genera una situazione di **disorientamento** per il lettore, che non sa a chi attribuire i pensieri espressi e rimane privo di un sistema di valori di riferimento.

## L’Assommoir

Il termine deriva da una betola in cui Zola si reca.

Il romanzo viene pubblicato inzialmente **a puntate** nel 1876, poi **in volume** nel 1877.

Per preparare il romanzo, Zola **visita la periferia nord di Parigi**, disegnango gli schemi delle strade e delle botteghe, poi scrive un **riassunto** della trama, legge libri e articoli sull’alcolismo e sugli operai e consulta **dizionari** sull’*argot.*

Nella prefazione al romanzo Zola **si difende dalle critiche del pubblico**, che in parte lo accusa di dare degli operai un’immagine troppo negativa, in parte gli rinfaccia la volgarità della forma.

Egli dichiara che la lingua che è tanto dispiaciuta ai suoi accusatori è quella autenticamente parlata nei sobborghi, e rivendica di avere voluto scrivere “**un’opera di verità**”, il primo romanzo sul popolo che non menta.

## Brani

→ “La fame di Gervaise” - 84/89

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20127.png)

---

# 💔 Decadentismo

Negli ultimi vent’anni del XIX secolo si diffonde in vari paesi europei -  **in compresenza e in contrapposizione al pensiero razionale positivista** - un diverso atteggiamento culturale, in genere desgnato come “Decadentismo”.

In particolare troviamo

- Una generale **sfiducia nelle possibilità della ragione scientifica**: il pensiero razionale e il legame logico di causa/effetto non appaiono in grado di rispondere sino in fondo agli interrogativi sulla realtà.
- una **critica al concetto di progresso** come miglioramento continuo e illimitato.
- un diffuso **diagio nei confronti della società borghese e il rifiuto dei suoi valori.**

E’ soprattutto la filosofia di **Nietzsche**, espressa in una forma aforistica e provocatoria, a sovvertire radicalmente le certezze tradizionali e a diffondere una nuova visione del mondo, individualista, vitalistica e nichilista insieme.

In letteratura gli autori decadenti rivendicano la loro **distanza dal Romanticismo**, e più ancora dal sentimentalismo di quegli scritori che ripropongono tardivamente modelli romantici; tuttavia non mancano **elementi di continuità** tra le due epoche.

Nei paesi europi tale categoria non è usata in modo univoco, ad esempio in **Francia** si identifica con il Simbolismo, in **Inghilterra** con l’Estetismo e in **Italia** ci sono due posizioni:

- Il Decadentismo come **“Macro - categoria”** che si estende dagli anni Ottana dell’Ottocento sino al pieno Novecento e in cui troviamo anche autori come Svevo, Pirandello, Ungaretti, Montale, Saba.
- Un **uso restrittivo** riferito soltanto agli ultimi decenni dell’Ottocento. Infatti si preferisce introdurre il concetto di **“Modernismo”** per designare la produzione letteraria italiana della prima parte del XX secolo. La distinzione tra Decdentismo e Modernismo ha il vantaggio di rimarcare la **profonda differenza di pensiero e di stile** tra autori come Pascoli e d’Annunzio da un lato, e Svevo, Pirandello, Ungaretti, Montale dall’altro.

Il termine “decadente” viene usato dapprima dai positivisti con **valore dispregiativo**, per designare quella che aloro pareva una resistenza tardoromantica e sterile all’inevitabile progresso della società, un peggiormaneto morale e artistico da parte di alcuni scrittori.

Lo stesso termine viene poi **orgogliosamente rivendicato** come elemento di differenziazione e segno di identità dai letterati.

---

# Il Decadentismo in Inghilterra con Oscar Wilde

Il romanzo emblematico del Decadentismo in lingua inglese è **The Picture of Dorian Gray** di **Oscar Wilde**.

In quest’opera si realizza concretamente, attraverso un **meccanismo fantastico**, la separazione tra sfera estetica e sfera morale dell’uomo, fino alle conseguenze più luttuose.

## Oscar Wilde

Nasce a **Dublino** nel **1854** in una famiglia benestante, compie studie classici prima al Trinity College e poi a Oxford.

Il *dandy* Oscar Wilde viene a lungo acclamato nell’ambiente modano per la sua **scrittura brillante e per la sua vita eccentrica**, ma dopo una condanna in tribunale per omosessualità sarà respinto ed emarginato.

il 1895 segna l’apice del successo, ma anche l’inizio della sua rovina.

A causa di una relazione omosessuale Wilde subisce un processop er **immoralità**.

E’ condannato a **due anni di lavori forzati**.

Trascorre gli ultimi anni in Francia, sotto pseudonimo, compie alcuni viaggi in Italia e muore in un albergo di Parigi nel **1900.**

## Brani

→ “Una lezione di edonismo” - 280/282

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20128.png)

---

# 9️⃣ Inizio ‘900

Nell’orizzonte sociale e culturale di inizio Novecento ci sono pochi punti fermi: l’industrializzazione avanza trasformando radicalmente il paesaggio fisico e gli equilibri sociali, le teorie scientifiche di Einstein relaticizzano la percezione dello spazio e del tempo; la psicoanalisi di Freud rivela la complessità della mente e l’uomo si riscopre fragile di fronte a una realtà interiore ed esteriore sempre più difficile da decifrare.

---

# 🚀 Avanguardie storiche del ‘900

## Le arti figurative

Con il termine di “Avanguardie storiche” si designano alcuni movimento artistici e letterari che si affermano in Europa nei primi decenni del Novecento, promuovendo un radicale **rinnovamento dei linguaggi espressivi** in polemica con la tradizione e la cultura ufficiali.

Si tratta di gruppi internazionali e interartistici perchè riuniscono autori di **diversi paesi** e coinvolgono **tutte le arti.**

Gli artisti delle avanguardie intendono affermarsi come **audaci apripista**: al culto del dato oggettivo e della razionalità teorizzato dal Positivirmo e dal Naturalismo, essi contrappongono un **mondo percepito attraverso le sensazioni.**

Nell’atteggiamento di questi gruppi si esprimono la sfida e la provocazione, lo sberleffo e la **polemica contro la tradizione** e contro il pubblico il cui gusto viene condannato come espressione antiquata di una borghesia mediocre e affarista.

---

La contestazione nei confronti dei valori estetici tradizionali risale agli anni Ottanta dell’Ottocento, epoca in cui in Francia i **poeti Simbolisti** avevano preso le distanze dalla morale comune e dai gusti letterari borghesi approfondendo la ricerca di **nuove vie espressive.**

Rispetto all’esperienza del simbolismo, le avanguardie dell’inizio del Novecento rifiutano qualsiasi concezione estetizzante ed elitaria: **l’arte perde il suo carattere sacrale** e il poeta non appare più come un uomo isolato ed eccezionale; egli si sente un precurose, ma sa di appartenere al suo tempo e su questo tempo vuole incidere.

---

Il rifiuto dei codici culturali e dei mezzi espressivi correnti è legato alla **massiccia affermazione del mercato culturale**: in quegli anni il prodotto letterario e artistico si era progressivamente trasformato in merce, in oggetto riproducibile in serie che doveva soddisfare il gusto mediocre della maggioranza.

Gli artisti **si oppongono a questa riduzione dell’arte a prodotto di consumo** e respigono l’idea dell’arte come pacifica fruizione borghese riservata a luoghi preposti.

Vogliono invece **portare l’arte nei luoghi più frequentati**, per provocare il pubblico e sfidarlo.

---

Il rinnovamento più radicale riguarda le arti figurative, quando un gruppo di pittori, tra i quali **Henri Matisse**, espongono le loro opere e il pubblico scopre con stupore alberi viola e figura umane rosse e verdi, colori puri, violenti, buttati a caso sulla tesa per **esprimere le emozioni attraverso effetti ottici** immediati.

---

In letteratura il primo a raccogliere e a fare suoi i principi delle avanguardie artistiche è Guillaume **Apollinaire** che può essere considerato il precursore della rivoluzione letteraria di inizio secolo.

SOgnando di formare un movimento poetico globale, il poeta francese ritiene che, per avvicinarsi il più possibile alla vita, l’**atto creativo debba venire dall’immaginazione.**

Apollinaire attua un rinnovamento formale: spezza la linearità del discorso poetico e crea immagini figurate facendo ricorso al “**testo simultaneo**” nel quale fonde poesia e pittura.

 

---

Sulle tracce di Apollinaire i movimenti di avanguardia sperimentano **forme nuove, ardite e sconcertanti.**

A prevalere sono ora il **verso libero e la paratassi**, spesso accompagnati da una **disposizione irregolare delle parole.**

Il lessico si apre ad ambiti e **temi nuovi** e inediti.

Un tale sperimentalismo è legato alla rottura del canale di comunicazione con il pubblico comune: i rappresentanti delle avanguardi non intendono fars icapire, ma **vogliono provocare** e scandalizzare.

Lo scritto d’avanguardia mira a creare un’opera ileggibile nel presente e **scrive per un lettore che non c’è ancora.**

Questo futuro lettore deve essere preparato, creato, educato: per questo motivo l’opera degli scrittori d’avanguardia presenta un **carattere spesso didattico** e pedagogico.

---

## L’espressionismo

L’espressionismo è un movimento che sorge e si diffonde per lo più in Germania e in Austria nei primi decenni del Novecento, dando inizio per primo a quella **crisi dei linguaggi artistici**.

Si tratta di un orientamento artistico che, opponendosi al Naturalismo e all’Impressionismo, coionvolge diverse forme espressive.

Ciò che caratterizza l’avanguardia espressionista è un **impiego soggettivo del mezzo artistico**: l’artista fa un uso esasperato, deformante dell’espressione per manifestare il suo **stato d’animo travagliato ed estremo**.

I temi dominanti sono quelli della **città minacciosa** e soffocante, della convulsa **civiltà delle macchine,** dell’angoscia che si esprime in **corpi disarticolati** e in **volti trasfigurati** di forte violenza espressiva.

L’espressionismo trova le sue premesse nelle opere di pittoti come **Munch, van Gogh, Gauguin.**

---

In letteratura il termine “Espressionismo” viene usato per designare alcune opere letterarie che rappresentano il **mondo come una proiezione del soggetto**, delle sue ossessioni: la visione dell’artista subentra alla descrizione delle cose.

La **brevità e concentrazione delle formule**, non coordinate ma giustapposte attraverso la **paratassi**, la sistematica deformazione delle cose e dello spazio, il lessico basso, crudo, scelto per il suo valore provocatorio e demistificante, danno forma a **opere visionarie, astratte**, di forte violenza espressiva e polemica.

---

## Il Dadaismo

Il Dadaismo è un movimento artistico e letterario fondanto a Zurigo nel 1916, dal poeta francese **Tzara**.

Il termine ***dada*** è una **voce onomatopeica del linguaggio infantile** che significa propriamente “cavallo”, ma anche “giocattolo”.

I dadaisti dichiarano di averlo scelto per gioco, aprendo a caso un dizionario francese.

Un tale nome corrisponde allo spirito del movimento che, a differenza del più cupo **Espressionismo**, sceglie un **modo giocoso** di manifestarsi.

Il carattere dominante del movimento è, tanto nel campo delle arti figurative quanto in quello letterario, una forte **carica anarchica e sovvertitrice** che mira a roversciare gli schemi razionali e le rassicuranti certezze che sono alla base della mentalità benpensante.

Nella loro volontà di **demolire ogni ordine**, i dadaisti si ribellano in particolare contro il sistema dell’arte e della sua mercificazione.

Il suo intento provocatorio è quello di **desacralizzare l’impronta creatrice dell’artista** e la stessa esperienza artistica.

Oltre al rifiuto della mercificazione dell’arte, i motivi principali del Dadaismo sono la riflessione sul **legame tra arte e vita,** l’interesse per la **follia** e per **l’inconscio**, l’esaltazione del caso e del **gesto gratuito**.

A differenza del Futurismo, il Dadaismo persegue al contrario l’**alogicità**, il *nosense*, l’assurdo, l’uso di **parole prese a caso** ed elevate a opere d’arte.

---

La principale accusa che venne mossa al movimento fu quella di non essere riuscito ad andare oltre la provocazione, la protesta, lo scandalo, cioè di **non aver proposto una poetica positiva.**

Il merito maggiore del Dadaismo sta comunque nell’aver promosso la più ampia e radicale sperimentazione in tutti i campi della produzione estetica.

La **fusione di diversi linguaggi artistici**, le tecniche del *collage* e dell’*assemblage*, il fotomontaggio.

---

## Il Surrealismo

A differenza del Dadaismo, da cui pure viene condizionato, il movimento Surrealista va oltre la semplice provocazione e fa leva su un programma positivo, proponendo un vero e proprio progetto di liberazione da attuarsi tanto sul piano creativo quanto su quello sociale.

I principali esponenti sono **Breton, Soupault, Aragon, Eluard.**

Breton e i surrealisti vogliono **superare il nichilismo** e rinnovare radicalmente il rapporto tra l’individuo e il mondo moderno dominato dalla prospettiva razionale borghese.

L’arte deve rivalutare tutto ciò che il Positivismo aveva condannato ed escluso, come il **meraviglioso**, il **sogno**, le **visioni**, la **follia**, la **sessualità**, dando voce all’**inconscio**, inteso come forza in cui si manifestano le pulsioni più profonde e l’immaginazione.

Facendo appello alla teoria freudiana dell’inconscio, i surrealisti utilizzano la “**scrittura automatica**”, cioè una scrittura che, seguendo le libere e casuali associazioni della mente così come sono “dettate” dai movimenti profondi dell’io, si libera, da “qualsiasi controllo esercitato dalla ragione”.

La prima opera surrealista, *Campi magnetici,* incita a servirsi dei meccanismi dell’inconscio, proponendosi di liberare il inguaggio dalla sua funzione meramente utilitaristica.

La scrittura automatica, che prevede anche l’uso di **tecniche collettive,** porta alla **svalutazione del talento artistico individuale**.

L’analisi marxista è considerata la prospettiva più coerente, in quanto capace di proporre la liberazione totale dell’uomo, per questo i surrealisti si appoggiano a tale pensiero.

---

Il Surrealismo rivaluta l’arte primitiva, le creazioni degli alienati mentali e le forme artistiche popolari in cui domina il gusto per il **macabro e il fantastico.**

Al Surrealismo aderiscono pittori europei come **Magritte** e **Dalì.**

Il movimento surrealista si indebolisce negli anni Trenta a causa delle **divergenze politiche** tra i suoi esponenti, che nel 1927 avevano aderito al Partito comunista.

---

## Il Futurismo

Il Futurismo è un’**avanguardia interartistica** complessiva, capace di influire tanto sulle arti quanto sul costume e sui modelli di comportamento: i numerosi manifesti teorici e tecnici futuristi definiscono la linea del movimento in ogni campo, dalle arti al ruolo della donna, dalla politica alla cucina.

Il movimento viene fondanto nel **1909** da **Filippo Tommaso Marinetti**, che pubblica il primo ***Manifesto del Futurismo*** sul quotidiano francese “Le figaro”.

Questo manifesto contiene già tutte le linee essenziali del movimento: ispirandosi al **dinamismo della moderna civilità industriale**, Marinetti esalta la bellezza della velocità e della macchina.

Egli è convinto che le nuove forme di comunicazione, come il telefono, il grammofono, ecc, abbiano profondamente influenzato la sensibilità e la psiche umana, producendo fenomeni significativi come l’**attrazione per il nuovo, l’imprevisto, il pericolo e la velocità**: l’arte deve dunque adeguarsi a questa nuova percezione delle cose trovando gli strumenti espressivi più adatti e opponendosi con forza alla tradizione.

Marinetti scaglia la propria **invettiva contro le città d’arte** e propone di **distruggere i musei, le accademie, le biblioteche**, e tutte le istituzioni che celebrano l’arte nella sua separatezza e salvaguardano i valori della tradizione e del passato.

---

A differenza delle altre avanguardie, il Futurismo **non si oppone alla mercificazione dell’arte**, ma provocatoriamente la accetta, proponendo anzi di sostituire il valore estetico dell’opera con quello commerciale.

L’artista perde così l’aura conferitagli dalla critica, ma mantiene una **posizione di privilegio.**

Perfettamente adeguati alla “modernità”, i futuristi colgono l’importanza della **comunicazione di massa** e se ne servono con abilità a scopo di propaganda: lo **scandalo e la provocazione** volutamente ricercati sono efficaci strumenti per spettacolarizzare il loro messaggio e per imporsi al pubblico.

La rivolta Futurista non è priva di ambiguità: da un lato, rispetto alle altre avanguardie europee, la cui polemica antiborghese appare radicale e senza compromessi, l’adesione totale e acritica dei futuristi italiani alla modernità riflette la loro **accettazione e celebrazione dello stato sociale dominante**, quello dell’industrialismo capitalistico. Dall’altro altro, l’esaltazione del movimento aggressivo e del gesto violento spinge i futuristi a **glorificare la virilità, il militarismo, la guerra**, in definitiva, **il fascismo.**

---

Sin dalla sua prima fase, dal 1909 al 1912, il Futurismo sente l’urgenza di **trovare un linguaggio adeguato** per tradurre in modo efficace la nuova sensibilità.

Il Futurismo radicalizza il dannunzianesimo e ne diventa l’involontaria parodia.

Sul piano formale, la parola d’ordine di questa prima fase è quella del **verso libero**, innovazione che incontra l’ostilità di Pascoli e il silenzio di d’Annunzio.

Durante la seconda fase del movimento, dal 1912, al 1915, il rivoluzionamento delle forme espressive diventa più radicale: il *Manifesto tecnico della letteratura futurista*, a cui seguono altri due manifesti, segnano una svolta decisiva; per esprimere la velocità, la simultaneità edlle impressioni, la rapidità di diffusione di una notizia, il poeta non pul perdersi nei meandri della sintassi tradizionale, che prevede di subordinare tra loro le frasi.

Marinetti passa così dal verso libero alle **parole in libertà**, gettate sulla pagina senza ordine logico e associate per analogia, seguendo una **immaginazione senza fili.**

I poeti futuristi devono **distruggere la sintassi**, abolire la punteggiatura, sopprimere l’aggettivo e prediligere l’uso dei verbi all’infinito, dell’onomatopea e della **poesia visiva**.

L’uso delle **analogia** permette di **penetrare l’essenza della materia** nelle sue diverse e opposte componenti.

---

Se nell’ambito letterario il Futurismo rimane piuttosto scarso di risultati, più significativi sono invece i risultati sul piano della pittura.

Troviamo **Boccioni, Carrà, Balla** che sottoscrivono il *Manifesto dei pittori futuristi.*

Vengono così elaborati i concetti di **dinamismo plastico, simultaneità, polimaterismo** e di **compenetrazione dei piani.**

---

Durante la fase che va dal 1915 al 1920 il Futurismo accentua la sua tendenza alla politicizzazione.

Se i membri del movimento avevano ripetuto sin dall’inizio che le loro idee non riguardavno soltanto le arti, ma anche la politica e un **nuovo senso del vivere**, con l’avvicinarsi della Prima guerra mondiale le loro posizioni si trasferiscono sempre più sul piano d’azione, sfociando prima nella **partecipazione alle manifestazioni interventiste**, poi a quelle fasciste e imperialiste.

Dopo la guerra i futuristi si organizzarono in un **partito politico**, passando progressivamente dalle iniziali posizioni genericamente nazionalistiche a antimonarchice a un **sovversivismo di destra** che esalta l’espansione imperialistica e l’azione violenta di gruppi organizzati.

La maggior parte dei futuristi aderisce al **fascismo**, che considerano come la realizzazione minima del loro programma politico.

Nel 1920 si chiude la cosiddetta “**fase eroica**”, il movimento continua a sopravvivere anche negli anni Venti e Trena ma senza più reale incidenza nella vita culturale e politica.

# Filippo Tommaso Marinetti

<aside>
🐣 Filippo Tommaso Marinetti nasce ad Alessandria d’Egitto nel **1876.**

</aside>

La famiglia si trasferisce a **Milano nel 1894**.

Dopo aver conseguito il baccalaureato a Parigi, si iscrive alla facoltà di Legge a Pavia.

Il **Fratello Leone muore** e Filippo matura in quegli anni profondi **sensi di colpa** e un cupo pessimismo, che si convertirà in seguito in un atteggiamento di **ostentato ottimismo** fondato sull’idea dell’uomo invincibile e immortale.

RIceve i primi riconoscimenti in Francia, dove collabora ad alcune riviste di Parigi ma **elabora le sue idee a Milano.**

Egli cerca una terza via tra l’estetismo decadente di d’Annunzio e la marginalità ostentata dei Crepuscolari.

Nella società industriale, dominata da mezzi di comunicazione, il poeta non può più starsene in disparte, ma deve **rivolgersi alle masse.**

Marinetti mostra sin dall’inizio una perfetta padronanza dei mezzi di comunicazione e un’are sapiente della pubblicità che fanno di lui un **abilissimo organizzatore di cultura** capace di suscitare energie intellettuali e adesioni anche grazie agli scandali e alle azioni eclatanti.

Nel 1909 pubblica il “*Manifesto del Futurismo*”, in questo e nei successivi manifesti Marinetti, dando prova di una **retorica tagliente** di grande efficacia, lancia la propria **invettiva contro i miti romantici e di tutta l’arte passatista.**

L’azione riformatrice di Marinetti appare più decisiva in campo teatrale: l’idea di uno **spettacolo sintetico** in cui i personaggi, ridotti a individualità astratte, operano in uno spazio scenico polidimensionale diventerà un punto di **riferimento decisivo per il successivo teatro di avanguardia.**

---

In campo politico, Marinetti oscilla tra **posizioni diverse**: dal socialismo umanitario all’anarchia, dalla sinistra al fascismo.

Con l’avvicinarsi della Prima guerra mondiale, l’attivismo programmatico dei manifesti si trasforma in nazionalismo e **acceso interventismo.**

Nel 1918 egli elabora l’idea di fondare un “**partito futurista**” il cui programma comprende l’educazione patriottica e militare nelle scuole, ma anche un miglioramento delle condizioni dei lavoratori.

Gli intenti antisocialisti e antiborghesi del programma attirano l’attenzione di Benito Mussolini, da cui Marinetti rimane a sua volta affascinato.

**Nel fascismo Marinetti crede di vedere la realizzazione delle sue idee futuriste e rivoluzionarie.**

Marinetti muore nel 1944, sotto la Repubblica di Salò.

## Brani

→ “Manifesto del Futurismo” - 48

→ “Manifesto tecnico della letteratura futurista” - 51

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20129.png)

---

# 📒 La crisi del Romanzo

## La rivoluzione romanzesca del primo Novecento

Nei primi tre decenni del Novecento si compie in Europa una vera e propria **rivoluzione estetica** che, insieme con la poesia, la musica e la pittura, tocca anche l’arte del romanzo e il modo di rappresentare i personaggi.

La filosofia di Henri **Bergson**, la teoria psicoanalistica di Sigmund **Freud** e la nuova fisica di Albert **Einstein** corrodevano a poco a poco le solide strutture del pensiero sulle quali poggiava la **società positivista, dissolvendo la nozione di tempo e quella di individuo:** 

> I romanzieri non possono più accontentarsi della struttura tradizionale del romanzo e cercano **nuove forme** per **esprimere la coscienza incerta** del soggetto in questo mondo frantumato.
> 

Il romanzo europeo **non** cerca più allora di **riprodurre la vita** né di offrire un’immagine veritiera delle relazioni umane; dal piano oggettivo del narratore si passa al **piano soggettivo del protagonista.**

## La realtà filtrata dalla coscienza

<aside>
💡 Il sapere a “cosa serve” e “quando si usa” viene dissolto nel ‘900

</aside>

Paul **Valéry** riassume efficacemente la comune insoddisfazione dell’epoca verso le forme romanzesche  tradizionali proclamando il suo fermo **rifiuto di una scrittura narrativa che si limita a una piatta descrizione dei fatti.**

A interessare gli scrittori non è più la realtà esterna ma lo **spazio vivente della coscienza**, l’unico a cui il romanziere possa avere veramente accesso.

La realtà, filtrata attraverso la coscienza del protagonista, non si presenta più cristallizzata in una forma stabile e definitiva ma appare fluida, sfaccettata, instabile, intermittente.

Nascono così opere prive di una struttura “logica”, in cui l’ordine cronologico viene manomesso e il racconto lineare è sostituito dal **disordinato flusso di impressioni, di immagini, di impulsi del personaggio.**

Tra le opere più significative di questa rivoluzione troviamo: 

- *Alla ricerca del tempo perduto* di Marcel **Proust**
- *Ulisse* di James **Joyce**
- *Al Faro* di Virginia **Woolf**
- *I romanzi* di Franz **Kafka**

## Personaggi divorati dall’interiorità

La disgregazione delle forme romanzesche tradizionali coincide con la **dissoluzione** stessa **del personaggio.**

Il romanzo ottocentesco di Alessandro Manzoni aveva creato grandi figure umane la cui apparenza fisica e profondità psicologica erano dotate di un forte rilievo individuale e offrivano l’illusione del reale.

E’ proprio questa corrispondenza tra individuo e società a essere messa in crisi dai grandi innovatori del romanzo.

Al centro delle loro narrazioni si trova un personaggio divorato dalla sua vita interiore, un “inetto” la cui volontà risulta indebolita al punto che egli **non sembra più** **in grado di assumere un’identità persistente,** né di conoscere i mezzi necessari a realizzare i suoi incerti fini.

Il suo rapporto con la società è ambiguo e problematico e la sua coscienza riflette il conflitto con **un mondo a cui si sente radicalmente estranea.**

## **Una n**arrativa analitica

La narrativa precedente era esplicativa, la nuova è **interrogativa**, analitica: alla ricerca delle cause sostituisce la **ricerca del senso delle cose**, un senso che, retto da un principio di instabilità, compare e sfugge continuamente.

## Le modalità della focalizzazione

Mentre nel romanzo ottocentesco dominava la narrazione in terza persona, i romanzi di questo periodo sono spesso scritti in prima persona.

La vera novità formale è legata alle modalità della focalizzazione, che seguono due tendenze concorrenti:

> La prima consiste nell’**interiorizzazione del mondo romanzesco da parte di una coscienza:** la narrazione è cioè espressione di una soggettività nella quale la realtà del mondo viene per così dire assorbita; la focalizzazione è allora prevalentemente **interna.**
> 

All’interno di questa tendenza troviamo:

- Proust
- Woolf
- Joyce
- Svevo

> La seconda consiste invece nell’**abolizione del soggetto**, in modo tale che il discorso narrativo non appaia più come la manifestazione di una coscienza, ma diventi anonimo, non assegnabile ad alcun soggetto; la focalizzazione è in questo caso **esterna**.
> 

In questa troviamo:

- Kafka

---

# Il romanzo in Italia

Mentre nel resto d’Europa la critica segue con interesse l’evoluzione del romanzo discutendo sulle forme del suo rinnovamento, in Italia i critici assistono con indiffrenza a un tale dibattito.

<aside>
💭 Lo scarso interesse per il rinnovamento delle forme nasce da un’impostazione critica condivisa, che associa **il rifiuto teorico dei generi letterari** a una **concezione astorica del romanzo** inteso come una sorta di essenza immutabile che, definita una volta per tutte secondo il modello classico (Manzoni), non può essere modificata nel tempo.

</aside>

Così, mentre nel resto d’Europa il romanzo si avvia a uno sconvolgimento senza precedenti, in Italia i critici e i letterati discutono soprattutto di “stile”, di eleganza formale e non concepiscono che si rimetta in discussione la struttura tradizionale.

L’ostilità italiana prende origine da una concezione del romanzo **ispirata al modello classico**, in base al quale la forma romanzesca esprime un soggetto o rappresenta il mondo per un soggetto.

<aside>
💡 Il timore diffuso è che **la dissoluzione della forma possa mandare in frantumi anche l’unità del soggetto.**

</aside>

Si ha la paura che si perda di vista ciò che dà unità e senso al mondo romanzesco: l’uomo.

---

Il cosiddetto “modernismo” avrà in Italia alcune caratteristiche particolari, come il **mantenimento di una trama** anche nei romanzi più destrutturati e il **rifiuto del più radicale “flusso di coscienza”.**

In questi anni, in Italia, a dettare la moda in fatto di gusto letterario sono alcune riviste fiorentine.

Il primo decennio del Novecento è caratterizzato dal diffondersi di numerose **riviste politico-culturali** che presentano alcuni tratti comuni: si pongono provocatoriamente **contro il positivismo** e le sue espressioni letterarie, il Naturalismo e il Verismo.

Sul piano letterario tentano di aprire la cultura italiana alle influenze europee, ma rimangono **fortemente vincolate a un estetismo di stampo dannunziano,** che tende a non riprodurre, ma a “trasfigurare” la realtà.

Diversa dalle altre e decisiva per il discorso sul romanzo è la più importante tra le riviste fiorentine “**La Voce**”.

La rivista conosce due fasi molto diverse fra loro: 

- Nella prima fase è caratterizzata dalla volontà di dare “voce” alla nuova generazione intellettuale, spingendola a uscire dal suo isolamento e a reagire alla retorica.
- Nella seconda fase si trasforma da rivista politico-culturale a rivisita **puramente letteraria**, teorizzando la poetica detta del “frammento” e difendendo la necessità di una prosa lirica, breve, intensa, che verrà poi denominata “**prosa d’arte**”.

I principi di questa poetica sono:

lo scrittore deve saper cogliere le vibrazioni segrete del sentimento, esprimendosi in una **prosa “lirica”,** cioè in un **componimento intenso e breve** stilisticamente puro, formalmente perfetto.

Alla luce di questa poetica i “frammentisti” sviluppano un vero e proprio programma dell’**antinarrativa**: contrari a ogni forma di letteratura “costruita” e “oggettiva” essi **guardano con diffidenza al romanzo**, che considerano come un accumulo di materiali disordinati.

---

In un tale clima ostile al rinnovamento del genere romanzesco, gli scrittori italiani che vogliono dedicarsi alla narrativa sperimentando nuove forme devono farlo quasi chiedendo il permesso, clandestinamente.

I due autori italiani più vicini al rinnovamento europeo delle forme narrative sono **Pirandello e Svevo**, i quali sfuggono tanto al purismo dei “frammentisti” quanto al conservatorismo.

I due scrittori giungono da strade diverse a un **romanzo di tipo nuovo, analitico e destrutturato.**

Sin dai suoi primi romanzi **Svevo porta il dramma dentro il personaggio** creando un campo narrativo mobile, instabile.

Pirandello racconta **l’incertezza** di ogni forma, di ogni verità, attraverso una **forma frantumata** che **mima la progressiva dissoluzione del protagonista.**

Tuttavia **l’Italia non è pronta ad accogliere il rinnovamento delle forme romanzesche**: i primi romanzi di Svevo vengono ignorati dalla critica.

L’accoglienza delle opere di Pirandello, pur molto meno ostile di quella riservata a Svevo, traduce la stessa difficoltà italiana ad accogliere le novità in fatto di narrativa.

Non a caso lo scrittore siciliano riesce a imporsi in Italia non tanto con i suoi romanzi, ma attraverso lo “scandolo” del suo teatro.

---

# Riassunto

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20130.png)

---

# 🌍 Storia

# Le radici del ‘900

## 📍1. Che cos’è la società di massa?

Che cosa intendiamo quando parliamo di **società di massa**?

Parliamo della **nostra** società. Infatti nella società attuale si è realizzata una diffusione *di massa* dei prodotti di consumo.

In altri termini, nella societò di massa si verifica il fenomeno del “pieno”, le città sono “piene di gente”, le strade anche, le case anche.

La **massa** è dunque un insieme omogeneo in cui i singoli individui scompaiono rispetto al *gruppo*, nuovo e più importante soggetto politico e civile.

> Nella **società di massa** i cittadini vivono nei grandi agglomerati urbani, a stretto contatto tra di loro.
> 

<aside>
💡 Sono state le trasformazioni politiche, economiche e culturali della **seconda rivoluzione industriale** a produrre una società co uniformata e omogenea.

</aside>

Alcuni hanno visto in questa trasformazione un momento positivo di affermazione della democrazia; altri un processo di appiattimento delle personalità.

> Con la **terza rivoluzione industriale** la società di massa si diffonderà in tutto il pianeta dando luogo a un fenome che non è solo economico, ma anche politico e culturale: la ***globalizzazione.***
> 

---

Alla fine dell’Ottocento solo Francia, Germania e Svizzera prevedevano nei loro ordinamenti il suffragio universale maschile.

<aside>
💡 In **Italia** l’introduzione del suffragio universale maschile avvenne nel **1912.**

</aside>

Si andò dunque ad affermare il modello del **partito politico di massa**, come forma di partecipazione popolare all’organizzazione politca dello Stato.

Contemporaneamente ai partiti di massa, sorsero **organizzazione sindacali** a livello nazionale.

Lo **sciopero** era lo strumento di lotta che utilizzavano per dare più forza alle rivendicazioni operaie.

---

La diffusione su larga scala dei beni di consumo rese più comoda la vita di molte famiglie.

Si diffusero anche i **mass media**, come i quotidiani, la radio e la televisione.

Fu proprio la **stampa quotidiana e periodica** a incrementare maggiormente la produzione e la vendita.

Nell’economia assunse un ruolo importantissimo il **terziario**, cioè la produzione di *servizi*: commercio, banche, ospedali ecc.

Anche il mondo della scuola subì un mutamento sostanziale: l**’istruzione** non venne più considerata un bene elitario, ma un’opportunità da offrire a tutti i cittadini.

La scuola venne organizzata e finanziata dallo stato.

---

## 📍2. Il dibattito politico e sociale.

il dibattito ideologico che si era sviluppato per tutto il corso dell’Ottocento aveva fatto propri i temi della riflessione politica settecentesca: i limiti del potere dello Stato e i diritti dei cittadini.

- I **conservatori** guardavano con preoccupazione alle rivendicazioni di operai e contadini: sostenevano che gli scioperi avrebbero sprofondato la società nel disordine e chiedevano allo Stato di reprimere tutte le agitazioni popolari.
- I **liberali** esaltavano il valore della libertà e dell’iniziativa individuali, chiedendo alllo stato di astenersi da ogni intervento nel campo dell’economia.
- I **socialisti** sostenevano invece che una società più giusta non potesse nascere se non dalle lotte dei ceti più oppressi: agricoltori e operai.
- La **chiesa** condannava sia il socialismo che il libero mercato, invitando imprenditori e lavoratori ad abbandonare lo scontro e a realizzare una collaborazione pacifica.

---

Nel corso dell’Ottocento all’interno del movimento socialista si impose la tendenza marxista, che individuava nella rivoluzione lo strumento del riscatto del proletariato.

In tutti i Paesi sorsero i partiti socialisti.

> Il primo a formarsi e il più importante fu l’**SPD**, il *Partito Socialdemocratico Tedesco.*
> 

I partiti socialisti europei, nonostante le diverse caratteristiche, erano uniti da alcuni obiettivi comuni: tutti auspicavano il superamento del sistema capitalistico e la gestione sociale dell’economia.

Tutti facevano capo a un’organizzazione erede di quella **Prima Internazionale Socialista.**

---

La nascita della **Seconda Internazionale Socialista** sorse nel **1889,** quando i principali partiti socialisti si riunirono a Parigi per approvare alcune importanti deliberazioni: la limitazione della *giornata lavorativa di otto ore *****e la proclamazione di una giornata mondiale di lotta per il ******primo maggio* di ogni anno.

A dominare ideologicamente la Seconda Internazionale fu il marxismo.

Progressivamente però si delinearono due tendenze all’interno dei partiti:

- Quella **socialdemocratica** che rifiutava la rivoluzione ponendo in luce la necessità di un’azione democratica e riformista da parte delle classe operaria.
- Quella **rivoluzionaria** che non rinunciava all’obiettico individuato da Marx: una società senza classi da raggiungere attraverso una rivoluzione violenta.

L’interprete principle della tendenza socialdemocratica fu **Eduard Bernstein.**

L’interprete principle della tendenza rivoluzionaria fu **Karl Kautsky.**

---

In Francia ebbe origine un’altra tendenza al’interno del movimento operaio, ch eprese il nome di *sindacalismo rivoluzionario**.***

I sindacalisti francesi insistevano sulla necessità di addestrare le masse operarie alla lotta, più che sulle conquiste economiche dei lavoratori.

**Georges Sorel** fu l’interprete più autorevole ed esaltò la violenza proletaria.

---

**Leone XIII** fu caratterizzato dalla ricerca di una proposta sociale coerente con il messaggio evangelico.

Questa ricerca si concretizzò nel **1891** con la **Rerum Novarum**, contenente:

- **denuncia degli eccessi del capitalismo**: viene ribadita la condanna al liberalismo.
- **condanna delle teorie socialiste e colletivistiche** che sostengono l’abolizione della proprietà privata.
- **invito allo Stato a intervenire** per rimuovere le cause che possono esasperare il conflitto tra operai e padroni.
- **condanna della lotta di classe** ed esortazione alla collaborazione tra padroni e operai.

---

Solo nel **1919** il *non expedit *****sarà completamente abrogato e i cattoliti potranno dar vita a un loro partito: il *Partito Popolare Italiano *****fondato dal sacerdote **Luigi Sturzo.**

---

La rivoluzione industriale portò le donne nelle fabbriche.

Nell’industria la donna era doppiamente discrimanta, sia perchè a parità di lavoro percepiva un salario minore, sia perchè era esclusa dalle funzioni dirigenziali e di responsabilità.

Nacquero in Inghilterra e negli Stati Uniti i primi movimenti delle **suffragette**, così chiamate perchè rivendicavano l’*estensione del suffragio alle donne.*

Si può sintetizzare la protesta di quei tempi con le parole de *Il pane e le rose*, la canzone di lotta delle donne americane.

---

## 📍3. Nazionalismo, razzismo, irrazionalismo

L’idea di nazione si affermò in Europa nella prima metà dell’Ottocento.

A partire dal 1850 essa assunse sempre più un carattere reazionario e militaresco, fino a diventare ideologia di guerra durante il primo conflitto mondiale.

Il nazionalismo si diffuse in tutta Europa assumendo caratteristiche a seconda dei contesti:

- Il **nazionalismo tedesco** ebbe come programma il *pangermanesimo;*
- Il **nazionalismo italiano** rivendicò per l’Italia le terre ancora irredente, come il Trentino.

---

Il razzismo consiste nel ritenere che esistano razze superiore e inferiori, e che la razza superiore abbia il diritto - dovere di sottomettere quella inferiore.

Questa terioa ebbe il suo precursore nel francese **Joseph Arthur de Gobineau.**

---

Tra Ottocento e Novecento anche il contestò culturale mutò: al positivismo subentrò l’**irrazionalismo**, caratterizzato dalla volontà di andare al di là della scienza. (Freud, Nietzsche, …)

In generale si affermò un’atmosfera di crisi in contrasto con l’ottimismo positivistico, un nuovo clima culturale che si è soliti definire **decadentismo.**

---

## 📍4. L’invenzione del complotto ebraico.

Un caso particolare di razzismo è quello che attribuisce agli Ebrei caratteristiche morali negative e in particolare la pervicace volontà di comandare sulle razze superiori: poichè gli Ebrei non avrebbero le qualità morali e fisiche per diventare una razza dominante, gli ambienti antisemiti hanno ritenuto che questo potese accadere soltanto con l’inganno e con attività segrete.

A questo scopo comparvero i *Protocolli dei Savi di SIon**,*** un libretto che presenta un piano ebraico per il dominio del mondo.

*I Protocolli* sarebbero nati per volontà del capo della **polizia segreta russa** come propaganda destinata a giustificare la politica antiebraica del suo Paese.

---

## 📍5. Il sogno sionista.

Il sentimento di diversità e l’antisemitismo giocarono un ruolo determinante per la nascita del movimento sionista.

Fu la Russia la vera culla delle prime forme di **sionismo**.

Nel 1896, **Theodor Herzl** espresse il suo progetto di riunificazione degli Ebrei della **diaspora** in una nazione ispirata agli ideali democratici dei movimenti patriottici europei del primo Ottocento.

Per alcuni anni l’Organizzazione Sionista Mondiale fu impegnata nel lavoro diplomatico per ottenere ufficialmente dalla Turchia la possibilità per gli Ebrei di stanziarsi in Palestina.

Ma la Turchia rifiutò.

In realtà, mentre si discuteva su quale dovesse essere la terra per gli Ebrei, la **colonizzazione** della Palestina era già in atto.

Tuttavia solo una minoranza di Ebrei scelte la **Palestina**; infatti la maggior parte di coloro che lasciarono l’Europa si diresse verso l’**America.**

---

# Età giolittiana e Belle époque

Il nuovo secolo sembrò dare l’avvio a un’epoca di pace e benessere.

Le scoperte e le invenzioni si susseguivano senza sosta.

Malattie un tempo terribili diventarono curabili.

Il periodo che va dalla fine dell’Ottocento al 1914 è stato chiamato *Belle époque**,*** l’epoca bella per eccellenza.

Una definizione curiosa se si pensa che si trattò di un’epoca in cui si diffusero pericolosamente il **nazionalismo** e il **razzismo** ed esplosero nelle relazioni internazionali contraddizioni tali che portarono alla strage del 1914-18.

*Belle époque* per ricordare la sperimentazione artistica e la vita brillante nelle grandi capitali europee simboleggiata dal locale più alla moda di Parigi, **Moulin rouge.**

E’ quindi fuorviante leggere il periodo a cavallo fra i due secoli in modo esclusivamente ottimista o drammatico.

Esistevano Stati che puntavano tutto sulla **potenza militare.**

Anche l’aumento delle **spese militari** venne considerato come l’inevitabile premessa di un conflitto o come uno strumento deterrente nei confronti di una guerra.

Il nazionalismo e il razzismo avrebbero presto manifestato tutta la loro pericolosità.

---

Durante quest’epoca numerosi intellettuali rifletterono sulla grande novità politica rappresentata dalla massa.

Nel 1895 venne pubblicato il saggio *Psicologia delle folle* dello psicologo **Gustave Le Bon.**

L’originalità dell’opera consisteva in una acuta e preveggente capacità di analisi delle motivazioni, spesso irrazionali, del **comportamento delle folle.**

La seconda rivoluzione industriale aveva indotto grandi utamenti, per Le Bon la dinamica storica non era mossa dai rapporti economici di produzione, ma dalle **opinioni** e dalle **credenze.**

---

Le Bon afferma che la **politica** del suo tempo aveva assunto caratteri decisamenti diversi rispetto al passato: era la nuova **religione delle masse.**

---

## 📍2. I caratteri generali dell’età giolittiana

Nel 1901 il re Vittorio Emanuele III nominò presidente del conglio *Giuseppe Zanardelli.*

Lo affiancava come ministro degli Interni, **Giovanni Giolitti.**

Giolitti era un uomo pratico, moderato, esperto conoscitore della macchina burocratica statale.

Zanardelli lasciò che fosse Giolitti a prendere le decisioni più importanti e quando rassegnò le dimissioni fece sì che Giolitti stesso gli subentrasse come Primo ministro.

Dal 1901 al 1914 si parla di **età giolittiana.**

In realtà Giolitti non resse il governo per tutti questi anni: faceva parte del suo modo di far politica l’abbandonare nei momenti di crisi il potere nelle mani di uomini di fiducia. In questo modo continuava la propria opera. Una volta dimostrata l’incapacità di amici e avversari, tornava al governo.

---

L’età giolittiana coincide con il decollo della rivoluzione industriale.

I progressi più evidenti si registrarono nell’industria **siderurgica** e nell’industria **elettrica** e **meccanica**.

Queste industrie aveveano sede soprattutto nel cosidetto **triangolo industriale**, formato da Torino, Milano e Genova.

---

L’industria italiana fu fortemente aiutata nel suo nascere dall’intervento statale.

Particolare rilievo ebbero le varie **commesse statali** nel campo dei trasporti ferroviari.

La **politica protezionistica** attuata con l’imposizione di alte tasse sui prodotti esteri, favorì notevolmente lo sviluppo delle industrie del Nord Italia mentre danneggiò il Mezzogiorno.

---

Lo sviluppo industriale portò **notevoli miglioramenti nel livello medio di vita** degli italiani.

I segni più evidenti di questo straordinario sviluppo si videro nelle **città**.

La popolazione però si spostò in grande misura dalle compagna alle città, di conseguenza la vita delle cità comportò **nuovi disagi** per gli abitanti e soprattutto per quelli delle classi operaie costretti a vivere in quartieri generalmente sovraffollatti.

---

In questo contesto economico e sociale si svolse l’azione politica di Giolitti.

Egli elaborò un suo piano di riforme, allo scopo di allargare la partcipazione alla vita dello Stato italiano, coinvolgendo in particolare il **Partito socialista italiano**.

All’interno del Partito socialista italiano si erano formate due correnti: quella **riformista** e quella **massimalista.**

**I riformisti** ritenevano che si dovesse cambiare la società gradualmente, attraverso le riforme.

I **massimalisti**, guidati da Benito Mussolini, ritenevano che per cambiare la società fosse necessario ricorrere alla rivoluzione, senza scendere a patti con i governi borghesi.

---

## 📍3. Il doppio volto di Giolitti

L’azione di governo di Giolitti fu caratterizzata da una profonda contraddizione.

Il suo modo di far politica venne definito del “doppio volto”:

- Un **volto aperto** e **democratico** nell’affrontare i problemi del Nord;
- Un **volto conservatore** e **corrotto** nello sfruttare i problemi del Sud.

---

Per quanto riguarda il Nord, Giolitti assunse un atteggiament olungimirante verso le nuove forze sociali; egli infatti **consentì gli scioperi** e fece assumere al governo una posizione di neutralità di fronte ai conflitti sindacali.

Ma Giolitti non si limitò a consentire gli scioperi, varò nel contempo alcune **riforme** che migliorarono le condizioni di lavoro degli operai:

- Orario di lavoro diminuito, massimo di 10 ore.
- Cassa nazionale per l’invalidità e la vecchiaia dei lavoratori.
- Maternità delle lavoratrici e il lavoro dei fanciulli.

La lotta sindacale portò all’**aumento dei salari** dei lavoratori che poterono così cominciare ad acquistare non solo prodotti alimentari, ma anche prodotti industriali.

Nel Nordo si andò diffondendo quel benessere economico tipico della società di massa.

---

Altri interventi si ebbero nel campo ferroviario, con la statalizzazione delle **ferrovie**.

Nell’età giolittiana però non venne affrontata la **questione meridionale**, ovvero il drammatico ritardo del Sud rispetto al Nord.

Anzi, nell’età giolittiana il divario del Paese crebbe.

Gran parte del flusso di denaro che arrivò al Sud alimentò **clientele** e **corruzione.**

Il Sud per Giolitti era un semplice serbatorio di voti da controllare in modo spregiudicato.

---

I salari dei lavoratori del Sud, a causa della scarsa offerta di lavoro e della sovrabbondanza di manodopera, scesero enormemente, portando in tutto il Meridione povertà e disoccupazione.

L’**emigrazione** fu un fenomeno doloroso, che tuttavia portò un po’ di ricchezza nelle terre più povere.

Chi lavorava all’esterno mandava parte della propria paga (**rimesse**) in italia.

---

## 📍4. Tra successi e sconfitte.

Giolitti ritenne opportuno riprendere la politica coloniale per due principali motivi:

- Voleva dimostrare ai nazionalisti che il suo era un governo in grado di aumentare il **prestigio internazionale** dell’Italia.
- Voleva accontentare l’**opinione pubblica** che riteneva fosse necessario conquistare nuove terre.

Giolitti cambiò obiettivo: non più l’Etiopia ma la Libia.

Nel **1911** l’Italia dichiarò guerra alla **Turchia** che dominava la **Libia.**

L’esercito occupò subito le principali città, ma dopo i primi successi iniziarono le difficoltà.

Non riuscendo a piegare la resistenza libica, l’Italia attaccò direttamente la Turchia, occupando alcune isole delle Sporadi che andarono a formare il dominio italiano nel **Dodecaneso.**

I Turchi firmarono nel **1912** il **Trattato di Losanna** con il quale cedevano all’Italia il dominio sulla Libia.

---

L’avventura coloniale comportò notevoli spese a cui non corrispose affatto la creazione di grandi opportunità per gli emigranti italiani.

La Libia infatti non era quella terra fertile e rigogliosa come veniva descritta.

---

La principale riforma democratica dell’età giolittiana fu l’approvazione, nel **maggio 1912**, di una nuova legge elettorale, che introduceva il **suffragio universale maschile.**

Con questa legge furono ammessi al voto i cittadini maschi che avessero compiuto il trentesimo anno d’età.

Per accedere al voto all’età di ventuno anni era invece necessario aver adempiuto gli obblighi del servizio militare o saper leggere e scrivere.

---

Il *Non expedit* venne in parte ammorbidito da Pio X.

Non era ancora permesso costituire un partito cattolico, ma in tutto il mondo cattolico vi era un grande fermento.

Nel 1913 Giolitti stipulò con l’Unione elettorale cattolica, presieduta dal conte Filippo Gentiloni, un accordo: il **Patto Gentiloni.** I cattolici promettevano di votare quei candidati liberali che avessero sottoscritto l’impegno di difendere la Chiesa.

Grazie a questo patto Giolitti riuscì a ottenere nuovamente la maggioranza.

---

La guerra in Libia aveva indebolito il governo di Giolitti. Molti erano coloro che criticavano il capo dell’esecutivo.

Giolitti preferì dare le dimissioni, pensava probabilmente che sarebbe stato richiamato al potere come era sempre successo.

Come suo successore indicò **Antonio Salandra**, un uomo politico conservatore.

Salandra però non seguì l’esempio di Giolitti nei confronti delle manifestazioni popolari.

Scoppiarono dei disordini che per la presenza dei socialisti presero il nome di **settimana rossa**. Salandra inviò l’esercito a reprimerli.

L’Italia tornava così a quel clima di tensione che aveva caratterizzato la crisi di fine secolo.

La situazione internazionale stava precipitando verso la **prima guerra mondiale**, Giolitti si opporrà, ma inutilmente.

L’età giolittiana era veramente finita.

---

# La Prima Guerra mondiale

La prima guerra mondiale (1914-1918) ebbe varie cause, alcune delle ascrivibili a situazioni presenti in Europa da molto tempo.

Queste **cause remote** erano di carattere politico, economico e militare.

Le **cause politiche** riguardavano i contrasti fra gli Stati europei e alcuni problemi presenti al loro interno, come:

- il desiderio di rivincita dei Francesi rispetto alla sconfitta subita dai Tedeschi.
- la secolare rivalità tra Austria e Russia.
- la presenza di due schiermanete di Stati contrapposti: la **Triplice Alleanza** (Germania, Austria, Italia) e la **Triplice Intesa** (Gran Bretagna, Francia, Russia).

---

Le principali cause **economiche** furono:

- La rivalità economica fra la **Gran Bretagna** e la **Germania**, procovata soprattutto dalla rapida crescita industriale di quest’ultima.
- La necessità per tutte le potenze industriali di espandere il proprio mercato e di garantirsi il rifornimento delle **materie prime.**

---

La scelta dei governi di dichiarare la guerra o di entrare nel conflitto in atto fu facilitata:

- Dal dilagante **nazionalismo**;
- dalle tesi **razziste**;
- dall’applicazione del **darwinismo**;
- dal fatto che molti **giovani** vedessero nella guerra l’unica possibilità di cambiamento.

---

<aside>
💡 La scintilla scoccò il **28 giugno 1914,** quando un nazionalista serbo uccise a **Sarajevo** l’erede al trono d’Austria, l’arciduca *Francesco Ferdinando* e sua moglie.

</aside>

L’Austria il **23 luglio** inviò alla Serbia un ***ultimatum*** che richiedeva entro 48 ore lo svolgimento di richieste umilianti.

Il governo serbo non poteva che respingerle.

Di conseguenza il **28 luglio** l’Austria dichiarò guerra alla Serbia.

---

Immediatamente scattarono le clausole delle alleanze stabilite negli anni precedenti e, nel giro di appena due giorni, si passò a una guerra europea.

All’ordine di mobilitazione generale impartito all’esercito il **29 luglio** dallo zar di Russia, rispose la Germania, che dichiarò guerra alla Russia e alla Francia, perchè si dava per scontato l’intervento di quest’ultima a fianco dell’alleato russo.

Le truppe tedesche diedero immediatamente attuazione al piano “Schlieffen”, attraversando il Beglio e il Lussemburgo per arrivare in Francia, determinando l’entrata in guerra della Gran Bretagna a fianco della Francia e della RUssia contro l’Austria e la Germania.

Solo l’Italia si dichiarò neutrale.

---

Il **31 ottobre** entrava in guerra anche la Turchia, in appoggio degli imperi centrali.

---

## 📍2. L’Italia in guerra

Nell’**agosto del 1914** il governo presieduto da *Antonio Salandra* proclamò la neutralità del nostroa PAese, appellandosi alle clausole della Triplice Alleanza.

Si formarono così due schieramenti contrapposti e, al tempo stesso, eterogenei al loro interno: i **neutralisti** e gli **interventisti.**

---

Fra i pareri favorevoli alla pace spiccava quelllo autorevole di **Giovanni Giolitti**, che voleva ottenere dall’Austria Trento e Trieste offrendo proprio la *neutralità italiana.*

Oltre ai *liberali* che si ispiravano al pensiero di Giolitti, era schierata contro la guerra la maggioranza dei socialisti.

Anche la maggior parte dei cattoliti rifiutava la prospettiva di guerra.

Lo stesso papa **Benedetto XV** aveva condannato ogni tipo di conflitto.

---

La posizione favorevole all’intervento in guerra era sostenuta soprattutto dai *nazionalisti* e dagli *irredentisti*, convinti che la violenza bellica fosse un segno di vitalità della nazione.

Fra gli intellettuali troviamo **Gabriele D’Annunzio e Giovanni Papini.**

Gli interventisti di destra avevano come obiettivo prioritario la liberazione di Trento e Trieste dal dominio austriaco.

Anche gli *alti ufficiali* dell’esercito e *l’ambiente della corte* intorno al re Vittorio Emanuele III vedevano nella guerra un’occasione per conseguire maggiore prestigio.

L’organo principale dell’interventismo di sinistra divenne ben presto il quotidiano diretto da **Benito Mussolini,** che era stato un importante dirigente del Partito Socialista.

---

Mentre nel Paese il dibattito pro o contro l’intervento assumeva toni sempre più accesi, il governo italiano agiva per via diplomatiche.

Il tentativo di ottenere dall’Austria il riscatto dei territori italiano fu inutile, perchè il governo austriaco intendeva attendere la fine del conflitto.

Il **26 aprile 1915**, il ministro degli Esteri Sonnino sottoscrisse a nome del governo il **Patto di Londra**.

Il patto impegnava l’Italia a entrare in guerra nel giro di un mese e le garantiva, in caso di vittoria dell’Intesa, diversi territori; inoltre fu concordata la possibilità di partecipare all’eventuale spartizione delle colonie tedesche.

Il 3 maggio l’Italia uscì dalla triplice Alleanza.

<aside>
💡 Il **24 maggio 1915** l’Italia dichiarò guerra all’Austria - Ungheria.

</aside>

---

## 📍3. La grande guerra

L’esercito italiano non era ancora pronto a sostenere un conflitto impegnativo.

Comandante supremo dell’esercito italiano fu nominato il generale **Luigi Cadorna**, che si distinse subito per la durissima disciplina imposta ai soldati.

Non si fidava dell’esercito di massa, formato da militari di leva, e ricorse a gravi punizioni per ogni mancanza.

Il generale Cadorna decise di portare un attacco frontale alle posizioni tenute dagli Austriaci.

Fra **giugno e dicembre 1915** si svolsero le prime quattro *battaglie dell’Isonzo**.***

Nel **giugno del 1916** gli Austriaci scatenarono la **Strafexpedition**, la *spedizione punitiva* contro l’ex alleato ritenuto colpevole di tradimento.

---

Intanto i Tedeschi riuscirono a occupare importanti zone industriali della Francia e a controllare le attività produttive ed estrattive del Belgio.

All’inizio del 1916 i Tedeschi prepararono, contro l’esercito francese, un’offensiva che sfociò nella battaglia di *Verdun.*

Sin dall’inizio del conflitto la Gran Bretagna aveva attuato un **blocco navale**, al fine di impedire che ai porti tedeschi giungessero materie prime e derrate alimentari.

 

---

La prospettiva di una lunga durata della guerra faceva prevedere un aumento delle difficoltà economiche per gli imperi centrali.

Perciò, fin dal mese di **febbraio** **1917** i Tedeschi decisero di intensificare la **guerra sottomarina,** per bloccare tutti i rifornimenti ai Paesi nemici.

Particolare scalpore aveva già destato l’affondamento del transatlantico *Lusitania.*

Ciò spinse gli **USA** a **entrare nel conflitto** al fianco dell’Intesa (**1917**).

Il 1917 fu un anno decisivo per le sorti del conflitto, non solo per l’intervento degli USA.

Nel **marzo** il regime zarista russo fu rovesciato e sostituito da una repubblica, il governo provvisorio decise di proseguire la guerra.

Ma i Tedeschi riuscirono a penetrare nel territorio russo, perchè i soldati russi abbandonavano il fronte.

La situazione interna divenne sempre più confusa sino alla **rivoluzione** dell’**ottobre 1917.**

Il nuovo governo decise di uscire dalla guerra e avviò con gli imperi centrali le trattative di pace, che si conclusero con l’accordo di *Brest-Litovsk*.

La Russia fu obbligata a pesanti concessioni.

---

In seguito alla crisi della Russia, l’Austria e la Germania poterono spostare delle truppe sul fronte occidentale e su quello italiano.

Con un grande sforzo offensivo gli Austriaci, appoggiati dai Tedecshi, sfondarono le linee italiane a **Caporetto.**

Il generale Cadorna dovette lasciare il comando dell’esercito e fu sostituito dal generale **Armando Diaz**, che decise di sistemare una nuova linea sul fiume *Piave*.

Il nuovo comandante impose una disciplina meno rigida e ne curò meglio l’addestramento.Le ragioni *militari* della disfatta di Caporetto sono da ricercarsi in un’offensiva ben condotta da parte degli Austriaci, ma la sconfitta fu generata da motivi ben più profondi: dal clima di sfiducia e di disagio, peraltro comune a tutti gli Stati belligeranti, diffuso al fronte e nel Paese.

I soldati erano ormai logorati, nel fisico e nello spirito.

Il **rifiuto della guerra** si manifestava soprattutto in comportamenti individuali, come la diserzione, la fuga, la simulazione di malattie.

---

Anche le popolazioni civili, oltre ai combattenti, furono coinvolte nel conflitto.

Pesanti limitazioni della **libertà personale**, razionamento del cibo, rialzo dei prezzi, aumento dei carichi di lavoro.

Le industrie ebbero uno sciluppo imponente, finanziato dallo Stato.

In pratica tutta la popolazione fu militarizzata: non solo i soldati che combattevano e che costituivano il **fronte esterno**, ma anche le persone che lavoravano nelle fabbriche e che formavano il **fronte interno.**

---

Per mobilitare la popolazione i governi ricorserso massicciamente alla **propaganda**, rivolta alle truppe per sostenerne il morale, ma anche ai civili.

Vennero stampati in ernomi quantità **manifesti** e cartoline che esaltavano le doti e le vittorie del proprio esercito.

---

La Germania e l’Austria avvertivano sempre più chiaramente che il blocco economico, attuato dall’Intesa, impediva di prolungare ulteriormente lo sforzo bellico.

Il 29 settembre la Bulgaria si arrese; l’Ungheria, la Cecoslovacchia e la Iugoslavia si dichiararono indipendenti dall’Austria, che dovette subire la **controffensiva italiana**.

Il **29 ottobre 1918** l’esercito austriaco fu sconfitto nella battaglia di **Vittorio Veneto** e costretto alla ritirata.

il **3 novembre** venne firmato l’armistizio che siglava la vittoria dell’Italia.

L’11 novembre l’imperatore Carlo I abdicò e venne proclamata la repubblica.

Anche la Germania a sua volta si preparò alla resa definitiva.

Il 9 novembre l’imperatore Guglielmo II lasciò il trono e anche a Berlino fu proclamata la repubblica.

---

## 📍4. L’inferno delle trincee

La prima guerra mondiale fu segnata dall’uso della trincea, un antichissimo sistema difensivo utilizzato nelle guerre di posizoine.

Si trattava di un **fossato** più o meno profondo.

I militari erano costretti a viverci in uno stato di tensione continua, esposti alle **intermperie**, dalle quali era ipossibile difendersi.

I combattenti dovettero sopportare **condizioni estreme di vita.**

Le **condizioni igieniche** erano pessime.

Frequenti e viruelente erano le **epidemie**.

---

Una delle caratteristiche peculiari del primo conflitto fu la tragica presenza della morte, con la quale i soldati dovevano costanetmente vivere.

**Numerosi cadaveri** di compagni e di nemici restavano nell’area compresa fra le opposte trincee per più giorni.

La loro resistenza nervosa era spesso messa a dura prova dai **bombardamenti** dell’artiglieria.

Il momento peggiore era però quello dell’**assalto alle trincee** dei nemici.

La **paura** non risparmiava nessuno.

---

## 📍5. La tecnologia al servizio della guerra

Oltre alle armi tradizionali, usate comunque con un dispiegamento mai visto, gli eserciti poterono utilizzare nuove armi e applicazioni tecnologiche messe a disposizione dai grandi progressi della scienza.

II mezzi che maggiormente sconvolsero i combattenti furono le **armi chimiche.**

Le necessitò belliche stimolarono lo sviluppo di settori industriali e scientifici di nascita recente.

Come ad esempio le **autoambulanze, la radiofonia**.

---

Un impatto più limitato ebbe l’utilizzo dell’**aviazione**.

Anche il **carro armato** fu scarsamente utilizzato.

Nella **guerra navale** fece la sua comparsa il **sottomarino**, furono i Tedeschi a utilizzarlo su grande scala.

Troviamo anche il **dirigibile** e la **mitragliatrice.**

---

## 📍7. I trattati di pace

I ministri dei Paesi vincitori si riunirono a *Parigi* il **18 gennaio 1919**, in una **Conferenza per la pace;** i delegati degli Stati vinti furono convocati, a cose fatte, solo per la firma finale.

Il più importante protagonista fu **Wilson** per gli Stati Uniti e **Orlando** per l’Italia.

→ Quattordici punti di Wilson

La **Francia** puntava a indebolire la Germania per assumere una posizione dominante nel continente europeo.

La **Gran Bretagna** voleva evitare la rovina della Germania perchè temeva che la Francia divenisse troppo potente.

---

I trattati di pace furono firmati tra il **1919** e il **1920**.

L’**Italia** ricevette dall’Austria il **Trentino, l’Alto Adige, la Venezia Giulia e Trieste.**

Il primo ministro Orlando e il ministro degli Esteri Sonnino avevano chiesto anche i territori promessi col Patto di Londra, le altre potenze riteneva però che queste concessioni avrebbero violato il nono punto di wilson, il principio di autodeterminazione e si opposero alla richiesta.

---

Le reazioni ai trattati di pace furono particolarmente violente in **Germania**, ritenevano di essere stati sottoposti a condizioni troppo dure.

L**’Italia** non evve i vantaggi sperati e questo fatto causò il risentimento nei confronti degli alleati e grandi proteste, soprattuto da parte di nazionalisti e interventisti.

Furono infatti gli **Stati Uniti** i veri vincitori della guerra: divennero la prima potenza politica ed economica del mondo e i principali creditori degli Stati europei.

---

# Cronologia essenziale prima guerra mondiale

### **1914**

28 giugno: l'**arciduca Francesco Ferdinando** d'Austria viene assassinato a **Sarajevo** dal nazionalista serbo **Gavrilo Princip**.

28 luglio: dopo l'[attentato di Sarajevo](http://www.oilproject.org/lezione/attentato-di-sarajevo-francesco-ferdinando-gavrilo-princip-6825.html) e un ultimatum caduto nel vuoto (23 luglio), **l'Austria-Ungheria muove guerra contro la Serbia**.

1 agosto: la **Germania**, alleata dell'Austria e dopo la mobilitazione delle truppe dello zar alla frontiera, **dichiara guerra alla Russia**.

2 agosto: i tedeschi mirano all'attuazione del **Piano Schlieffen**, che prevede l'apertura di un fronte occidentale contro la Francia: occupano il territorio del **Lussemburgo** e procedono verso il **Belgio**, violandone la neutralità.

3 agosto: **dichiarazione di guerra della Germania contro la Francia**, alleata della Russia; l'Italia, pur essendo alleata nella **Triplice Alleanza** di Germania e Austria, persiste nella scelta della neutralità.

4 agosto: anche la **Gran Bretagna**, alleata della Francia, **dichiara guerra alla Germania**.

6-13 agosto: le reciproche dichiarazioni di guerra (della Serbia e della Francia contro l'impero austro-ungarico e dell'Austria-Ungheria contro la Gran Bretagna) definiscono il confronto tra le forze della **Triplice Intesa** (Gran Bretagna, Francia, Impero russo) e della **Triplice Alleanza** (Austria-Ungheria, Germania e l'Italia per ora neutrale). Il 23 agosto il Giappone dichiarerà guerra agli Imperi centrali, ampliando la **dimensione "mondiale" del conflitto**.

agosto-settembre: le truppe tedesche registrano i primi successi, occupando Bruxelles sul fronte occidentale e bloccando l'avanzata dei francesi presso il Reno; sul fronte orientale, i generali **Ludendorff** e **Hindenburg** ottengono considerevoli vittorie sui russi a **Tannenberg** (17 agosto - 2 settembre) e ai **Laghi Masuri** (7 - 14 settembre).

12 settembre: i francesi bloccano l'avanzata tedesca nella prima **[battaglia della Marna](http://www.oilproject.org/lezione/riassunto-prima-guerra-mondiale-battaglia-verdun-somme-dardanelli-7190.html)**; finisce la **guerra di movimento** (o "guerra-lampo" dal tedesco *Blitzkrieg*) e si passa alla **guerra di trincea**. Il comando delle truppe tedesche ad ovest passa da Von Moltke a Von Falkenhayn.

31 ottobre: anche l'**Impero ottomano** entra nelle ostilità, alleandosi all'Austria-Ungheria e alla Germania.

### **1915**

26 aprile: dopo il **fallimento delle trattative con l'Austria** (cui l'Italia chiede compensazioni territoriali per entrare in guerra a fianca degli Imperi centrali) il governo italiano stipula segretamente e all'insaputa del Parlamento il **[Patto di Londra](http://www.oilproject.org/lezione/grande-guerra-italia-interventisti-neutralisti-strafexpedition-7503.html)**, con il quale l'Italia accetta di entrare in guerra di lì ad un mese alleandosi con la **Triplice Intesa**, ottenendo, in cambio di vittoria, il Trentino, l'Alto Adige, l'Istria, la Dalmazia (eccetto Fiume), la base navale albanese di Valona e il riconoscimento di sovranità sui possedimenti del 1912 nel Dodecaneso.

7 maggio: l'affondamento del **transatlantico Lusitania**, ad opera di un **sottomarino tedesco**, è il primo passo per l'entrata in guerra degli Stati Uniti.

24 maggio: dopo le pressanti **manifestazioni di piazza dei nazionalisti** - alla cui testa si pone [Gabriele D'Annunzio](http://www.oilproject.org/lezione/d-annunzio-poesia-5774.html) - affinché l'Italia entri in guerra, si arriva alla **dichiarazione formale di guerra** contro l'Austria.

giugno-dicembre: le prime [quattro battaglie dell'Isonzo](http://www.oilproject.org/lezione/grande-guerra-italia-interventisti-neutralisti-strafexpedition-7503.html) (23 giugno-7 luglio; 18 luglio-4 agosto; 18 ottobre-4 novembre; 10 novembre-2 dicembre) lungo il fronte italo-austriaco portano minimi avanzamenti territoriali, ad **un prezzo altissimo in termini di vite umane**.

### **1916**

21 febbraio: i tedeschi iniziano la controffensiva contro i francesi a **Verdun**. Si tratta di una delle  principali battaglie sul **fronte occidentale**, che vede contrapposti francesi e inglesi da una parte e tedeschi dall'altra in una logorante [guerra di posizione](http://www.oilproject.org/lezione/riassunto-prima-guerra-mondiale-battaglia-verdun-somme-dardanelli-7190.html) dagli ingenti costi umani.

15-31 maggio: l'**esercito austriaco** dà il via alla *Strafexpedition* (cioè **"spedizione punitiva"**) contro l'Italia **per accerchiare le truppe schierate sull'Isonzo**. Nonostante il grande impegno di uomini la spedizione fallisce.

31 maggio-2 giugno: **scontro navale** tra la flotta britannica e quella tedesca nella storica **battaglia dello Jutland**.

27 agosto: la Romania dichiara guerra all'Austria-Ungheria. Il giorno successivo l'Italia muove guerra contro la Germania e quest'ultima contro la Romania.

21 novembre: Carlo I d'Asburgo succede a **Francesco Giuseppe**.

### **1917**

3 febbraio: gli **Stati Uniti**, in reazione alla **guerra sottomarina tedesca**, interrompono le relazioni diplomatiche e si preparano all'ingresso nelle ostilità.

12 marzo: nella Russia zarista, scoppia la **"rivoluzione di febbraio"** (secondo il calendario giuliano, è il 23 febbraio), che costringe Nicola II all'abidicazione e porta all'instaurazione di un governo provvisiorio.

2 aprile: **gli USA muovono guerra contro la Germania**.

(27 giugno: anche la **Grecia** entra in guerra, schierandosi contro Bulgaria, Germania, Austria-Ungheria, Impero Ottomano. Il 14 agosto la **Cina** dichiara guerra alla Germania e all'Austria-Ungheria, seguita il 26 dal **Brasile**.)

24 ottobre: le truppe austriache e tedesche sfondano il fronte italiano a [Caporetto](http://www.oilproject.org/lezione/sintesi-prima-guerra-mondiale-luigi-cadorna-armando-diaz-trattato-di-versailles-8184.html), causando notevolissime perdite all'esercito italiano e portando la linea dei combattimenti lungo il **fiume Piave**. Si tratta del **momento più drammatico per l'Italia** nel corso di tutto il conflitto.

6 novembre (24 ottobre nel calendario russo): con la ["Rivoluzione di Ottobre"](http://www.oilproject.org/lezione/riassunto-rivoluzione-russa-bolscevichi-menscevichi-tesi-di-aprile-7655.html) **i bolscevichi prendono il potere** e instaurano il **Congresso dei Soviet**.

8 novembre: dopo la disfatta militare di Caporetto, il **generale Diaz** sostituisce Cadorna, noto per i suoi duri metodi repressivi nei confronti delle truppe.

### **1918**

8 gennaio: il presidente americano Woodrow **Wilson** presenta i **quattordici punti** il suo programma per l'**assetto mondiale post-bellico**.

3 marzo: con il **trattato di Brest-Litovsk**, la Russia comunista firma la resa verso gli Imperi centrali.

luglio-agosto: **offensiva dell'Intesa** lungo il fronte occidentale

24 ottobre-3 novembre: con un'offensiva sul Piave e sul Grappa **le truppe italiane conquistano Vittorio Veneto**. L'Austria-Ungheria , stremata e al collasso su tutti i fronti, chiede l'armistizio.

4 novembre: **armistizio fra Italia e Austria-Ungheria**.

11 novembre: con l'armistizio fra il resto degli alleati e la Germania, si conclude il primo conflitto mondiale. La **Conferenza di pace di Parigi** (18 gennaio 1919 - 21 gennaio 1920) e il [Trattato di Versailles](http://www.oilproject.org/lezione/sintesi-prima-guerra-mondiale-luigi-cadorna-armando-diaz-trattato-di-versailles-8184.html) definiranno i nuovi assetti territoriali europei.

---

# Il primo dopoguerra

## 📍1. I problemi del dopoguerra

Il nuovo assetto geopolitico creò in molti paesi europei una diffusa insoddisfazione.
La Germania si sentiva umiliata da una pace che aveva ridotto notevolmente il suo territorio.
Anche l’Italia riteneva di non essere stata ripagata a sufficienza poiché non le erano state riconosciute Fiume e la Dalmazia.
Questo bastò ai nazionalisti per parlare di vittoria mutilata.

La società delle nazioni fu fondata a Ginevra nel 1920 e l’obiettivo era quello di costituire un’organizzazione in grado di risolvere attraverso la diplomazia i contrarsi tra gli Stati.

Chi non avesse rispettato le decisioni prese avrebbe subito sanzioni economiche o militari.

La Società delle Nazioni però non riuscì a garantire una pace duratura, per due cause:

- Gli Stati Uniti rifiutarono di prenderne parte
- Mancanza di una propria forza militare

La guerra aveva causato oltre 8 milioni di morti, ai quali vanno aggiunte le vittime di una terribile epidemia di influenza: la Spagnola.
Tutto ciò determino un grave calo demografico.

Da un punto di vista economico l’Europa dovette affrontare una gravissima crisi.
Un primo importante problema riguardava le strutture produttive, infatti la guerra aveva mobilitato l’intero sistema industriale dei Paesi coinvolti: la produzione di armi, navi, aerei e cannoni aveva richiesto uno sforzo senza precedenti negli investimenti economici e tecnologici.
A guerra finita si trattava di realizzare la riconversione industriale, cioè di ritornare al normale tipo di produzione del tempo di pace.
Non tutte le imprese però potevano permettersi questa riconversione e, per questo motivo, iniziarono a licenziare o a mantenere i salari bassi: si diffusero così povertà e disoccupazione.
I debiti per le spese di guerra indussero i governi del conflitto a stampare nuova carta moneta, con la quale si innescò rapidamente l’inflazione.
I prezzi aumentavano erodendo i risparmi e i salari di tutti i lavoratori dipendenti e di chi viveva con un reddito fisso.
Fu in particolare il ceto medio a soffrire di questa situazione. L’economia europea era in ginocchio.

## 📍2. Il disagio sociale

La guerra aveva trasformato radicalmente anche la società. La generazione che aveva combattuto aveva vissuto un’esperienza senza eguali nella storia.

In Italia, per la prima volta, i ragazzi del sud si sono incontrati con quelli del nord, ritrovandosi a combattere nelle trincee. La guerra aveva causato la mobilitazione di milioni di uomini.

In questo senso aveva contribuito a creare una coscienza collettiva e aveva segnato il vero ingresso delle masse nella storia.

Il ritorno alla vita civile portò nuovi e aspri conflitti sociali: i sindacati e i partiti, consapevoli della propria forza, si organizzarono; i reduci di guerra chiesero un riconoscimento al loro impegno e un reinserimento nella società.

Inoltre:

- Gli operai volevano aumenti di salario e più potere nelle fabbriche.
- I contadini chiedevano la proprietà della terra che lavoravano
- Il ceto medio manifestava il proprio disagio economico avvicinandosi ai movimenti più autoritari.

La prima guerra mondiale influì anche sulla condizione sociale ed economica delle donne.
Lo spostamento degli uomini al fronte portarono grandi cambiamenti nella struttura sociale offrendo nuove possibilità alle donne.
Esse infatti entrarono nel mondo del lavoro in modo non paragonabile ai decenni precedenti: sostituirono gli uomini nelle fabbriche, negli uffici, alla guida dei trasporti e nei campi spesso con ruoli rilevanti e di responsabilità
Oltre a svolgere lavori tradizionalmente destinati agli uomini, le donne poterono godere di migliori condizioni economiche: durante il periodo bellico, ad esempio, le fabbriche di armi corrispondevano alle donne un salario pari anche al doppio di quello che le lavoratrici ricevevano in tempo di pace.
Il grande mutamento della figura femminile nella società influenzò anche la politica.
Questo generale processo di emancipazione dal passato e dal ruolo passivo imposto dai maschi si concretizzò ad esempio nella conquista del diritto di voto alle donne. In molti Paesi il voto alle donne non venne concesso.

Il ritorno alla vita civile per coloro che avevano combattuto nell'inferno delle trincee non fu facile: i reduci passarono dalle immani privazioni e sofferenze subite nel corso del conflitto a uno stato di disoccupazione ed emarginazione sociale, giacché i sistemi produttivi nazionali erano in crisi e non più in grado di offrire lavoro a tutti.
Molti giovani combattenti avevano trovato nel contesto della guerra un senso per la loro vita, forse anche qualche soddisfazione militare e un po' di prestigio.
Il rientro a casa fu traumatico: trovarono una società cambiata, molti non ebbero più il lavoro e mal si adattarono alla piatta quotidianità civile. L'idea di aver rischiato la vita per la patria senza ottenere nulla in cambio creava insoddisfazione e risentimento in quei giovani che avevano passato anni in trincea.
Il reinserimento dei reduci nella vita ordinaria fu così un problema di tutti i Paesi, e in genere le difficoltà finanziarie impedirono una soluzione soddisfacente.

I reduci erano uomini che avevano conservato la mentalità combattentistica, la fierezza del soldato, il cameratismo militare.
Ovunque si riunirono in associazioni che assunsero un importante ruolo sociale e politico nel dopoguerra.

Nella società l'insoddisfazione era diffusa e molti aspiravano a un nuovo sistema politico che ponesse termine alla situazione di crisi.
Tra il 1919 e il 1920, il disagio della popolazione si tradusse in tutta Europa in una lunga serie di scontri sociali.
Gli operai nelle industrie, i contadini nelle campagne, i ceti medi nelle città avviarono una stagione di lotte e manifestazioni. I borghesi moderati erano preoccupati di una rottura rivoluzionaria del sistema vigente.
La democrazia liberale vacillò, attaccata contemporaneamente dall'estrema sinistra e dall'estrema destra.
Il disprezzo per le istituzioni parlamentari, giudicate troppo deboli, raggiunse un livello allarmante. Solo nei Paesi di antica tradizione liberale, come la Francia e l'Inghilterra, il sistema politico resse.
Negli altri Stati dell'Europa, la crisi del dopoguerra aprì la strada a governi di tipo autoritario e alle dittature.

## 📍3. Il biennio rosso

Dopo la rivoluzione bolscevica del 1917, una nuova preoccupazione rese ancora più pesante il clima delle democrazie europee.
Il mito della rivoluzione, infatti, si diffuse e il modello del nuovo Stato comunista diventò per gli operai e i contadini europei un sogno realizzabile. Molti volevano «fare come in Russia»: abolire la proprietà privata e istituire la dittatura del proletariato.
I conservatori di tutta Europa temevano il contagio rivoluzionario, considerando anche che il nuovo governo della Russia era attivamente impegnato nella diffusione del comunismo.
Lenin e i bolscevichi, infatti, promuovevano la formazione di partiti comunisti in tutto il mondo.
Questi partiti dovevano prendere le distanze dai socialisti democratici, rifiutare il sistema parlamentare-democratico e impegnarsi a realizzare una rivoluzione come quella russa.
Lenin riteneva necessario riunire in un'unica organizzazione internazionale i «veri» socialisti rivoluzionari.
Nel marzo 1919, quindi, sorse a Mosca la Terza Internazionale detta anche Comintern, cioè Internazionale Comunista.
Lenin era convinto che in Europa ci fossero le condizioni per avviare una rivoluzione da estendere al mondo intero. Il Comintern avrebbe avuto il compito di coordinare e controllare il movimento comunista internazionale.
Nel luglio 1920, si tenne a Mosca il Il Congresso dell'Internazionale Comunista.
Lenin elaborò un documento in cui fissava in ventuno punti le condizioni per poter aderire al Comintern.
L'adesione ai ventuno punti implicava una totale subordinazione dei comunisti europei al partito sovietico. Iniziò così una forte contrapposizione fra socialisti riformisti e comunisti che produsse la scissione all'interno di molti partiti socialisti. Tra il 1920 e il 1921, infatti, i socialisti rivoluzionari fondarono dei partiti comunisti in molti Paesi europei.

L'esperienza di massa della guerra, la crisi economica, il mito della rivoluzione, il desiderio di una società più giusta furono gli aspetti che contribuirono al rafforzamento delle organizzazioni del movimento operaio di tutta Europa.
L'impegno nella vita politica, prima limitato a ristrette élites di notabili borghesi, si allargò alle masse di lavoratori, sempre più consapevoli della loro forza.
I lavoratori europei si aspettavano un cambiamento radicale e soluzioni nuove. La partecipazione diretta acquistava maggior peso con le frequenti manifestazioni pubbliche, i comizi, le adunate, i cortei.
Il movimento operaio chiedeva una società più giusta è più equa, rivendicava salari più alti, case a prezzi accettabili.
I contadini volevano terre da coltivare.
I partiti socialisti ottennero importanti successi elettorali mentre i sindacati raccoglievano il consenso dei lavoratori.

Tra il 1919 e il 1920 l'Europa fu toccata da un'ondata di scioperi e agitazioni operaie per l'aumento del salario e la giornata lavorativa di otto ore; quest'ultimo obiettivo venne raggiunto quasi ovunque.
Questo periodo di lotte, chiamato biennio rosso, non si limitò a semplici rivendicazioni sindacali.
Si voleva andare oltre: era in gioco il potere nello Stato e nelle fabbriche. Sorsero spontaneamente i consigli operai che, sul modello dei soviet russi, si presentavano come i rappresentanti del proletariato nella futura società comunista.
L'intensità e le conseguenze delle lotte operaie di questi anni furono diverse nei singoli Paesi europei.
In Germania, ancora prima della fine della guerra, i consigli degli operai e dei soldati avevano occupato le fabbriche e le sedi dei giornali.
L'estrema sinistra della Lega di Spartaco, guidata da Karl Liebknecht e Rosa Luxemburg, non accettava la linea moderata del Partito socialdemocratico. Anche dopo la proclamazione della repubblica, le proteste continuarono in modo violento e giunsero ad autentici tentativi rivoluzionari.
La disgregazione dell'Impero asburgico aveva ridotto l'Austria a un piccolo Stato dove nel 1919 venne proclamata la repubblica retta da un governo socialdemocratico.
I comunisti, anche qui, tentarono di spingere il popolo alla rivoluzione, ma senza successo.
In Ungheria, nel marzo 1919, socialisti e comunisti diedero vita a una Repubblica dei Consigli sul modello sovietico guidata dal comunista Bela Kun. Il progetto era di allargare quell'esperienza all'Austria, ma i comunisti ungheresi si trovarono isolati e il disegno fallì.
Anche in Italia il biennio rosso mise in crisi il vecchio sistema politico; ma portò anche alla divisione del movimento operaio con la scissione del Partito socialista.

In Germania intervenne l'esercito, che arrestò e uccise i principali responsabili delle insurrezioni.
In Italia l'iniziativa rivoluzionaria rifluì per lasciare progressivamente spazio all'affermazione del fascismo.
In Austria la vittoria elettorale andò a conservatori e clericali, forti del sostegno delle masse contadine più reazionarie.
In Ungheria, il fallimento della repubblica sovietica lasciò il potere alla controrivoluzione guidata da Miklós Horthy. Horthy eliminò fisicamente l'opposizione comunista e instaurò il primo regime autoritario dell'Europa del dopoguerra (agosto 1919).

## 📍4. Dittature, democrazie e nazionalismo

La crisi politica ed economica degli anni Venti e Trenta apri la strada a cambiamenti politici radicali in gran parte del mondo.
In Europa la crisi del dopoguerra contribuì alla nascita e alla diffusione di dittature e di regimi totalitari. Tra gli Stati più importanti, solo Francia e Gran Bretagna ressero alla crisi: in questi Paesi le classi dirigenti riuscirono a controllare il pericolo rappresentato dalle frange massimaliste dei partiti socialisti, che prospettavano rivoluzioni imminenti, e a garantire la stabilità politica entro il sistema parlamentare e democratico.
Anche in questi Stati, tuttavia, vi fu una forte affermazione delle forze moderate e conservatrici.
Nel resto d'Europa, invece, la fragilità del sistema parlamentare non resse alla spinta delle forze che premevano per una svolta autoritaria. Come abbiamo visto, l'Ungheria fu il primo Paese in cui si sperimentò l'autoritarismo di destra.
Nel 1922, Mussolini andò al governo in Italia e in pochi anni organizzò un regime dittatoriale che fu assunto come modello da molti altri Paesi.

Nel primo dopoguerra, la Francia fu guidata da governi di centro-destra. Solo nel 1924 la vittoria del «cartello delle sinistre» portò al governo, per un breve periodo, i radicalsocialisti.
Dal 1926 al 1929 il Paese fu guidato da Raymond Poincaré, capo dei moderati.
Alla fine della guerra, anche la Gran Bretagna attraversò una crisi economica e sociale molto grave. Il tradizionale primato economico inglese era passato agli Stati Uniti.
Inoltre, le nuove tecnologie e l'uso del petrolio avevano ridotto il consumo di carbone di cui la Gran Bretagna aveva il monopolio produttivo in Europa. Le conseguenze di questa situazione furono circa 2 milioni di disoccupati e un impero coloniale che cominciava a vacillare.
Negli anni Venti, i lavoratori dell'industria e del settore minerario avviarono una lunga fase di agitazioni sindacali e politiche.
Nel 1924 ci fu anche una prima esperienza di governo laburista (guidato cioè dal partito inglese di ispirazione socialista).
I conservatori, tuttavia, conquistarono il potere e attuarono una politica di rigore finanziario e di contenimento dei salari che scatenò la protesta dei lavoratori.
Nel 1926 ci fu infatti una grande ondata di scioperi. In particolare furono i minatori a condurre una lotta sindacale che si protrasse per molti mesi senza ottenere risultati a causa dell'irrigidimento del governo.

Il 29 ottobre 1923 in Turchia venne proclamata la repubblica. Kemal ne divenne il presidente e la capitale fu trasferita ad Ankara.
Il prestigio di Kemal era immenso, per questo venne soprannominato Atatürk, il «padre dei Turchi».
Secondo Atatürk, uno Stato civilizzato era innanzitutto uno Stato laico: per questo voleva liberare la Turchia dall'islam, che considerava in parte responsabile del ritardo nella modernizzazione del Paese. Atatürk chiuse le scuole religiose e le comunità monastiche a cui confiscò i beni.
A queste iniziative si accompagnò uno sforzo per laicizzare la società e la cultura. Soppresse la poligamia e assicurò alle donne l'uguaglianza completa in materia ereditaria. Nel 1934 le donne ottennero il diritto di voto e molte entrarono in Parlamento.
L'insegnamento religioso scomparve a poco a poco dal sistema scolastico controllato dallo Stato. Infine Atatürk sostituì i caratteri arabi con l'alfabeto latino, il calendario dell'egira con quello gregoriano; il giorno di riposo settimanale divenne la domenica al posto del venerdì musulmano.

## 📍5. Le colonie e i movimenti indipendentisti

Francia e Inghilterra dovettero fronteggiare anche la crescita dei movimenti indipendentisti e nazionalisti nelle colonie, in Africa e in Asia. Le popolazioni coloniali rivendicarono una maggiore autonomia e una partecipazione nell'amministrazione dei rispettivi Paesi.
L'estensione dei movimenti anticolonialisti fu determinata essenzialmente da questi motivi:
-reparti militari coloniali avevano partecipato alla guerra a fianco dell'Intesa, dando prova di lealtà: a guerra finita si aspettavano come ricompensa una maggiore autonomia;

- durante la guerra in Occidente, i combattenti avevano conosciuto le idee democratiche e quando ritornarono nelle loro terre si impegnarono a lottare per l'emancipazione della loro patria;
- la pubblicazione nel 1919 dei Quattordici punti di Wilson, due dei quali facevano riferimento alle questioni coloniali riconoscendo i diritti delle popolazioni indigene, aveva creato qualche illusione;
- l'Unione Sovietica e il Comintern svolsero un'azione a favore dei movimenti anticolonialisti, nell'ottica di liberare gli «schiavi d'Africa e d'Asia».
Nel primo dopoguerra, dunque, il nazionalismo si diffuse nelle colonie. Tuttavia, la decolonizzazione vera e propria si sarebbe realizzata solo dopo la seconda guerra mondiale.

La crisi del dopoguerra provocò una ristrutturazione dell'immenso impero coloniale inglese: nella sostanza, la Gran Bretagna rinunciò a parte del controllo politico per garantirsi invece un dominio economico.
Le colonie britanniche vennero organizzate in forme diverse. I dominions, le colonie con una forte componente di popolazione bianca - cioè Canada, Australia, Nuova Zelanda e Sudafrica - ottennero nel dopoguerra una crescente autonomia politica.
Nel 1931, con lo Statuto di Westminster, il Parlamento inglese li riconobbe come Stati sovrani.
I dominions entrarono quindi a far parte del Commonwealth, cioè di una libera associazione di comunità autonome senza alcun rapporto di subordinazione, unite dalla comune fedeltà alla corona britannica e legate all'ex madrepatria da forti vincoli di carattere economico.
Oltre al Commonwealth, la Gran Bretagna deteneva altri possedimenti in Africa, in Asia e nel Pacifico: si trattava di colonie vere e proprie, di protettorati o di mandati. Su questi territori vi fu soprattutto un controllo economico finalizzato essenzialmente a creare un'area commerciale privilegiata all'interno dell'impero coloniale.
In Egitto, ad esempio, nacque un regno autonomo, ma la Gran Bretagna controllava il Canale di Suez e si riservò il diritto di mantenere delle truppe. In Iraq (su cui aveva il mandato della Società delle
Nazioni) e in Arabia Saudita, gli Inglesi mantennero il controllo dei pozzi petroliferi. Il punto critico era rappresentato dall'India, dove nel dopoguerra si sviluppò un consistente movimento nazionalista guidato da un uomo di grande prestigio, Mohandas Karamchand Gandhi, che iniziò una lunga lotta, all'insegna della «non violenza», per l'indipendenza indiana.
Fra i territori che la Gran Bretagna ottenne in mandato rientrava anche la Palestina. In quest'area s'andavano ponendo le basi dei drammatici conflitti arabo-israeliani che sono giunti sino ai giorni nostri. Cresceva infatti il numero dei coloni ebrei che emigravano in Palestina con l'obiettivo di fondarvi uno Stato ebraico (sionismo).

La politica attuata dai governi francesi verso le colonie fu molto diversa da quella britannica. L'atteggiamento del governo mirava infatti ad assimilare le colonie in una «grande Francia».
Questa politica centralistica generò numerose opposizioni sia in Medio Oriente, dove la Francia aveva ottenuto il mandato dalla Società delle Nazioni sulla Siria e il Libano, sia in Africa settentrionale.
In Marocco, in Tunisia e soprattutto in Algeria si diffusero movimenti anticolonialisti di vario orientamento: sia democratico-socialista, sia religioso (di matrice islamica), sia nazionalista. Alle richieste di autonomia il governo francese reagì sempre con una dura repressione.
Anche in Indocina, negli anni Venti, si formò un movimento che rivendicava maggiore partecipazione alla vita politica.

Negli anni della prima guerra mondiale l'America Latina passò sotto l'influenza degli Stati Uniti.
Durante la guerra, infatti, i Paesi europei ridussero i loro investimenti, lasciando spazio a quelli statunitensi. Si trattava di finanziamenti ai governi e alle banche o di investimenti diretti in imprese industriali nel settore ferroviario, minerario, petrolifero.
Anche negli scambi commerciali gli Stati Uniti soppiantarono l'Europa; in alcuni settori operarono addirittura in regime di monopolio.
Tra i Paesi latinoamericani e gli Stati Uniti si instaurò un rapporto di forte dipendenza economica che condizionò anche i sistemi politici.
In alcuni casi, nell'area centramericana, gli Stati Uniti ricorsero anche all'intervento militare per proteggere i loro interessi.
Di maggiore autonomia godevano invece gli Stati più ricchi del Sud America - come il Brasile, l'Argentina e il Cile - che nel corso della guerra avevano avviato un processo di industrializzazione e di sviluppo economico. Era però uno sviluppo fragile perché poggiava essenzialmente su investimenti stranieri.
La grande crisi economica del 1929 evidenziò la fragilità dell'area latinoamericana. Il protezionismo degli Stati Uniti e dell'Europa rallentò notevolmente le importazioni di prodotti dall'America del Sud. Le difficoltà economiche crearono tensioni sociali e condizioni di instabilità politica che nel corso degli anni Trenta favorirono, anche in quest'area, l'affermazione di regimi autoritari.
Si trattava di governi dittatoriali e populisti, simili ai fascismi europei, che si insediarono in Argentina, Brasile, Cile.

Un caso particolare di populismo è rappresentato dal Messico dove nel 1910 scoppiò una rivoluzione che pose termine alla quarantennale dittatura del generale Porfirio Díaz. Nel novembre del 1910, infatti, un proprietario liberale del Nord, Francisco Madero, si mise alla testa di un movimento insurrezionale a cui si unirono gruppi di contadini guidati da Pancho Villa ed Emiliano Zapata.
Fu l'inizio della rivoluzione messicana che, un anno dopo, costrinse all'esilio il dittatore Díaz e portò alla presidenza della Repubblica Madero.
Gli anni successivi furono segnati così dalla guerra civile tra conservatori e radicali; questi ultimi erano sostenuti dai contadini. Uccisioni, colpi di Stato e rivalità fra i diversi leader politici caratterizzarono questa fase della rivoluzione fino alla sconfitta di Villa e di Zapata.
Alla presidenza fu allora eletto Venustiano Carranza, un militare, già seguace di Madero, che nel 1917 promulgò la Costituzione. Si trattava di una Costituzione molto avanzata, democratica, fondata sulla laicità dello Stato e sul riformismo sociale, destinata però a essere completamente disattesa: nel 1920, infatti, Carranza fu deposto e ucciso da uno dei suoi generali.
Fino al 1934 così il Messico fu retto da governi militari e autoritari.
In questo modo si consolidò nel Paese il modello populista, caratterizzato dal partito unico al potere e dalla tendenza a manipolare dall'alto la partecipazione popolare.

---

# Il primo dopoguerra

## 📍1. I problemi del dopoguerra

Il nuovo assetto geopolitico creò in molti paesi europei una diffusa insoddisfazione.
La Germania si sentiva umiliata da una pace che aveva ridotto notevolmente il suo territorio.
Anche l’Italia riteneva di non essere stata ripagata a sufficienza poiché non le erano state riconosciute Fiume e la Dalmazia.
Questo bastò ai nazionalisti per parlare di vittoria mutilata.

La società delle nazioni fu fondata a Ginevra nel 1920 e l’obiettivo era quello di costituire un’organizzazione in grado di risolvere attraverso la diplomazia i contrarsi tra gli Stati.

Chi non avesse rispettato le decisioni prese avrebbe subito sanzioni economiche o militari.

La Società delle Nazioni però non riuscì a garantire una pace duratura, per due cause:

- Gli Stati Uniti rifiutarono di prenderne parte
- Mancanza di una propria forza militare

La guerra aveva causato oltre 8 milioni di morti, ai quali vanno aggiunte le vittime di una terribile epidemia di influenza: la Spagnola.
Tutto ciò determino un grave calo demografico.

Da un punto di vista economico l’Europa dovette affrontare una gravissima crisi.
Un primo importante problema riguardava le strutture produttive, infatti la guerra aveva mobilitato l’intero sistema industriale dei Paesi coinvolti: la produzione di armi, navi, aerei e cannoni aveva richiesto uno sforzo senza precedenti negli investimenti economici e tecnologici.
A guerra finita si trattava di realizzare la riconversione industriale, cioè di ritornare al normale tipo di produzione del tempo di pace.
Non tutte le imprese però potevano permettersi questa riconversione e, per questo motivo, iniziarono a licenziare o a mantenere i salari bassi: si diffusero così povertà e disoccupazione.
I debiti per le spese di guerra indussero i governi del conflitto a stampare nuova carta moneta, con la quale si innescò rapidamente l’inflazione.
I prezzi aumentavano erodendo i risparmi e i salari di tutti i lavoratori dipendenti e di chi viveva con un reddito fisso.
Fu in particolare il ceto medio a soffrire di questa situazione. L’economia europea era in ginocchio.

## 📍2. Il disagio sociale

La guerra aveva trasformato radicalmente anche la società. La generazione che aveva combattuto aveva vissuto un’esperienza senza eguali nella storia.

In Italia, per la prima volta, i ragazzi del sud si sono incontrati con quelli del nord, ritrovandosi a combattere nelle trincee. La guerra aveva causato la mobilitazione di milioni di uomini.

In questo senso aveva contribuito a creare una coscienza collettiva e aveva segnato il vero ingresso delle masse nella storia.

Il ritorno alla vita civile portò nuovi e aspri conflitti sociali: i sindacati e i partiti, consapevoli della propria forza, si organizzarono; i reduci di guerra chiesero un riconoscimento al loro impegno e un reinserimento nella società.

Inoltre:

- Gli operai volevano aumenti di salario e più potere nelle fabbriche.
- I contadini chiedevano la proprietà della terra che lavoravano
- Il ceto medio manifestava il proprio disagio economico avvicinandosi ai movimenti più autoritari.

La prima guerra mondiale influì anche sulla condizione sociale ed economica delle donne.
Lo spostamento degli uomini al fronte portarono grandi cambiamenti nella struttura sociale offrendo nuove possibilità alle donne.
Esse infatti entrarono nel mondo del lavoro in modo non paragonabile ai decenni precedenti: sostituirono gli uomini nelle fabbriche, negli uffici, alla guida dei trasporti e nei campi spesso con ruoli rilevanti e di responsabilità
Oltre a svolgere lavori tradizionalmente destinati agli uomini, le donne poterono godere di migliori condizioni economiche: durante il periodo bellico, ad esempio, le fabbriche di armi corrispondevano alle donne un salario pari anche al doppio di quello che le lavoratrici ricevevano in tempo di pace.
Il grande mutamento della figura femminile nella società influenzò anche la politica.
Questo generale processo di emancipazione dal passato e dal ruolo passivo imposto dai maschi si concretizzò ad esempio nella conquista del diritto di voto alle donne. In molti Paesi il voto alle donne non venne concesso.

Il ritorno alla vita civile per coloro che avevano combattuto nell'inferno delle trincee non fu facile: i reduci passarono dalle immani privazioni e sofferenze subite nel corso del conflitto a uno stato di disoccupazione ed emarginazione sociale, giacché i sistemi produttivi nazionali erano in crisi e non più in grado di offrire lavoro a tutti.
Molti giovani combattenti avevano trovato nel contesto della guerra un senso per la loro vita, forse anche qualche soddisfazione militare e un po' di prestigio.
Il rientro a casa fu traumatico: trovarono una società cambiata, molti non ebbero più il lavoro e mal si adattarono alla piatta quotidianità civile. L'idea di aver rischiato la vita per la patria senza ottenere nulla in cambio creava insoddisfazione e risentimento in quei giovani che avevano passato anni in trincea.
Il reinserimento dei reduci nella vita ordinaria fu così un problema di tutti i Paesi, e in genere le difficoltà finanziarie impedirono una soluzione soddisfacente.

I reduci erano uomini che avevano conservato la mentalità combattentistica, la fierezza del soldato, il cameratismo militare.
Ovunque si riunirono in associazioni che assunsero un importante ruolo sociale e politico nel dopoguerra.

Nella società l'insoddisfazione era diffusa e molti aspiravano a un nuovo sistema politico che ponesse termine alla situazione di crisi.
Tra il 1919 e il 1920, il disagio della popolazione si tradusse in tutta Europa in una lunga serie di scontri sociali.
Gli operai nelle industrie, i contadini nelle campagne, i ceti medi nelle città avviarono una stagione di lotte e manifestazioni. I borghesi moderati erano preoccupati di una rottura rivoluzionaria del sistema vigente.
La democrazia liberale vacillò, attaccata contemporaneamente dall'estrema sinistra e dall'estrema destra.
Il disprezzo per le istituzioni parlamentari, giudicate troppo deboli, raggiunse un livello allarmante. Solo nei Paesi di antica tradizione liberale, come la Francia e l'Inghilterra, il sistema politico resse.
Negli altri Stati dell'Europa, la crisi del dopoguerra aprì la strada a governi di tipo autoritario e alle dittature.

## 📍3. Il biennio rosso

Dopo la rivoluzione bolscevica del 1917, una nuova preoccupazione rese ancora più pesante il clima delle democrazie europee.
Il mito della rivoluzione, infatti, si diffuse e il modello del nuovo Stato comunista diventò per gli operai e i contadini europei un sogno realizzabile. Molti volevano «fare come in Russia»: abolire la proprietà privata e istituire la dittatura del proletariato.
I conservatori di tutta Europa temevano il contagio rivoluzionario, considerando anche che il nuovo governo della Russia era attivamente impegnato nella diffusione del comunismo.
Lenin e i bolscevichi, infatti, promuovevano la formazione di partiti comunisti in tutto il mondo.
Questi partiti dovevano prendere le distanze dai socialisti democratici, rifiutare il sistema parlamentare-democratico e impegnarsi a realizzare una rivoluzione come quella russa.
Lenin riteneva necessario riunire in un'unica organizzazione internazionale i «veri» socialisti rivoluzionari.
Nel marzo 1919, quindi, sorse a Mosca la Terza Internazionale detta anche Comintern, cioè Internazionale Comunista.
Lenin era convinto che in Europa ci fossero le condizioni per avviare una rivoluzione da estendere al mondo intero. Il Comintern avrebbe avuto il compito di coordinare e controllare il movimento comunista internazionale.
Nel luglio 1920, si tenne a Mosca il Il Congresso dell'Internazionale Comunista.
Lenin elaborò un documento in cui fissava in ventuno punti le condizioni per poter aderire al Comintern.
L'adesione ai ventuno punti implicava una totale subordinazione dei comunisti europei al partito sovietico. Iniziò così una forte contrapposizione fra socialisti riformisti e comunisti che produsse la scissione all'interno di molti partiti socialisti. Tra il 1920 e il 1921, infatti, i socialisti rivoluzionari fondarono dei partiti comunisti in molti Paesi europei.

L'esperienza di massa della guerra, la crisi economica, il mito della rivoluzione, il desiderio di una società più giusta furono gli aspetti che contribuirono al rafforzamento delle organizzazioni del movimento operaio di tutta Europa.
L'impegno nella vita politica, prima limitato a ristrette élites di notabili borghesi, si allargò alle masse di lavoratori, sempre più consapevoli della loro forza.
I lavoratori europei si aspettavano un cambiamento radicale e soluzioni nuove. La partecipazione diretta acquistava maggior peso con le frequenti manifestazioni pubbliche, i comizi, le adunate, i cortei.
Il movimento operaio chiedeva una società più giusta è più equa, rivendicava salari più alti, case a prezzi accettabili.
I contadini volevano terre da coltivare.
I partiti socialisti ottennero importanti successi elettorali mentre i sindacati raccoglievano il consenso dei lavoratori.

Tra il 1919 e il 1920 l'Europa fu toccata da un'ondata di scioperi e agitazioni operaie per l'aumento del salario e la giornata lavorativa di otto ore; quest'ultimo obiettivo venne raggiunto quasi ovunque.
Questo periodo di lotte, chiamato biennio rosso, non si limitò a semplici rivendicazioni sindacali.
Si voleva andare oltre: era in gioco il potere nello Stato e nelle fabbriche. Sorsero spontaneamente i consigli operai che, sul modello dei soviet russi, si presentavano come i rappresentanti del proletariato nella futura società comunista.
L'intensità e le conseguenze delle lotte operaie di questi anni furono diverse nei singoli Paesi europei.
In Germania, ancora prima della fine della guerra, i consigli degli operai e dei soldati avevano occupato le fabbriche e le sedi dei giornali.
L'estrema sinistra della Lega di Spartaco, guidata da Karl Liebknecht e Rosa Luxemburg, non accettava la linea moderata del Partito socialdemocratico. Anche dopo la proclamazione della repubblica, le proteste continuarono in modo violento e giunsero ad autentici tentativi rivoluzionari.
La disgregazione dell'Impero asburgico aveva ridotto l'Austria a un piccolo Stato dove nel 1919 venne proclamata la repubblica retta da un governo socialdemocratico.
I comunisti, anche qui, tentarono di spingere il popolo alla rivoluzione, ma senza successo.
In Ungheria, nel marzo 1919, socialisti e comunisti diedero vita a una Repubblica dei Consigli sul modello sovietico guidata dal comunista Bela Kun. Il progetto era di allargare quell'esperienza all'Austria, ma i comunisti ungheresi si trovarono isolati e il disegno fallì.
Anche in Italia il biennio rosso mise in crisi il vecchio sistema politico; ma portò anche alla divisione del movimento operaio con la scissione del Partito socialista.

In Germania intervenne l'esercito, che arrestò e uccise i principali responsabili delle insurrezioni.
In Italia l'iniziativa rivoluzionaria rifluì per lasciare progressivamente spazio all'affermazione del fascismo.
In Austria la vittoria elettorale andò a conservatori e clericali, forti del sostegno delle masse contadine più reazionarie.
In Ungheria, il fallimento della repubblica sovietica lasciò il potere alla controrivoluzione guidata da Miklós Horthy. Horthy eliminò fisicamente l'opposizione comunista e instaurò il primo regime autoritario dell'Europa del dopoguerra (agosto 1919).

## 📍4. Dittature, democrazie e nazionalismo

La crisi politica ed economica degli anni Venti e Trenta apri la strada a cambiamenti politici radicali in gran parte del mondo.
In Europa la crisi del dopoguerra contribuì alla nascita e alla diffusione di dittature e di regimi totalitari. Tra gli Stati più importanti, solo Francia e Gran Bretagna ressero alla crisi: in questi Paesi le classi dirigenti riuscirono a controllare il pericolo rappresentato dalle frange massimaliste dei partiti socialisti, che prospettavano rivoluzioni imminenti, e a garantire la stabilità politica entro il sistema parlamentare e democratico.
Anche in questi Stati, tuttavia, vi fu una forte affermazione delle forze moderate e conservatrici.
Nel resto d'Europa, invece, la fragilità del sistema parlamentare non resse alla spinta delle forze che premevano per una svolta autoritaria. Come abbiamo visto, l'Ungheria fu il primo Paese in cui si sperimentò l'autoritarismo di destra.
Nel 1922, Mussolini andò al governo in Italia e in pochi anni organizzò un regime dittatoriale che fu assunto come modello da molti altri Paesi.

Nel primo dopoguerra, la Francia fu guidata da governi di centro-destra. Solo nel 1924 la vittoria del «cartello delle sinistre» portò al governo, per un breve periodo, i radicalsocialisti.
Dal 1926 al 1929 il Paese fu guidato da Raymond Poincaré, capo dei moderati.
Alla fine della guerra, anche la Gran Bretagna attraversò una crisi economica e sociale molto grave. Il tradizionale primato economico inglese era passato agli Stati Uniti.
Inoltre, le nuove tecnologie e l'uso del petrolio avevano ridotto il consumo di carbone di cui la Gran Bretagna aveva il monopolio produttivo in Europa. Le conseguenze di questa situazione furono circa 2 milioni di disoccupati e un impero coloniale che cominciava a vacillare.
Negli anni Venti, i lavoratori dell'industria e del settore minerario avviarono una lunga fase di agitazioni sindacali e politiche.
Nel 1924 ci fu anche una prima esperienza di governo laburista (guidato cioè dal partito inglese di ispirazione socialista).
I conservatori, tuttavia, conquistarono il potere e attuarono una politica di rigore finanziario e di contenimento dei salari che scatenò la protesta dei lavoratori.
Nel 1926 ci fu infatti una grande ondata di scioperi. In particolare furono i minatori a condurre una lotta sindacale che si protrasse per molti mesi senza ottenere risultati a causa dell'irrigidimento del governo.

Il 29 ottobre 1923 in Turchia venne proclamata la repubblica. Kemal ne divenne il presidente e la capitale fu trasferita ad Ankara.
Il prestigio di Kemal era immenso, per questo venne soprannominato Atatürk, il «padre dei Turchi».
Secondo Atatürk, uno Stato civilizzato era innanzitutto uno Stato laico: per questo voleva liberare la Turchia dall'islam, che considerava in parte responsabile del ritardo nella modernizzazione del Paese. Atatürk chiuse le scuole religiose e le comunità monastiche a cui confiscò i beni.
A queste iniziative si accompagnò uno sforzo per laicizzare la società e la cultura. Soppresse la poligamia e assicurò alle donne l'uguaglianza completa in materia ereditaria. Nel 1934 le donne ottennero il diritto di voto e molte entrarono in Parlamento.
L'insegnamento religioso scomparve a poco a poco dal sistema scolastico controllato dallo Stato. Infine Atatürk sostituì i caratteri arabi con l'alfabeto latino, il calendario dell'egira con quello gregoriano; il giorno di riposo settimanale divenne la domenica al posto del venerdì musulmano.

## 📍5. Le colonie e i movimenti indipendentisti

Francia e Inghilterra dovettero fronteggiare anche la crescita dei movimenti indipendentisti e nazionalisti nelle colonie, in Africa e in Asia. Le popolazioni coloniali rivendicarono una maggiore autonomia e una partecipazione nell'amministrazione dei rispettivi Paesi.
L'estensione dei movimenti anticolonialisti fu determinata essenzialmente da questi motivi:
-reparti militari coloniali avevano partecipato alla guerra a fianco dell'Intesa, dando prova di lealtà: a guerra finita si aspettavano come ricompensa una maggiore autonomia;

- durante la guerra in Occidente, i combattenti avevano conosciuto le idee democratiche e quando ritornarono nelle loro terre si impegnarono a lottare per l'emancipazione della loro patria;
- la pubblicazione nel 1919 dei Quattordici punti di Wilson, due dei quali facevano riferimento alle questioni coloniali riconoscendo i diritti delle popolazioni indigene, aveva creato qualche illusione;
- l'Unione Sovietica e il Comintern svolsero un'azione a favore dei movimenti anticolonialisti, nell'ottica di liberare gli «schiavi d'Africa e d'Asia».
Nel primo dopoguerra, dunque, il nazionalismo si diffuse nelle colonie. Tuttavia, la decolonizzazione vera e propria si sarebbe realizzata solo dopo la seconda guerra mondiale.

La crisi del dopoguerra provocò una ristrutturazione dell'immenso impero coloniale inglese: nella sostanza, la Gran Bretagna rinunciò a parte del controllo politico per garantirsi invece un dominio economico.
Le colonie britanniche vennero organizzate in forme diverse. I dominions, le colonie con una forte componente di popolazione bianca - cioè Canada, Australia, Nuova Zelanda e Sudafrica - ottennero nel dopoguerra una crescente autonomia politica.
Nel 1931, con lo Statuto di Westminster, il Parlamento inglese li riconobbe come Stati sovrani.
I dominions entrarono quindi a far parte del Commonwealth, cioè di una libera associazione di comunità autonome senza alcun rapporto di subordinazione, unite dalla comune fedeltà alla corona britannica e legate all'ex madrepatria da forti vincoli di carattere economico.
Oltre al Commonwealth, la Gran Bretagna deteneva altri possedimenti in Africa, in Asia e nel Pacifico: si trattava di colonie vere e proprie, di protettorati o di mandati. Su questi territori vi fu soprattutto un controllo economico finalizzato essenzialmente a creare un'area commerciale privilegiata all'interno dell'impero coloniale.
In Egitto, ad esempio, nacque un regno autonomo, ma la Gran Bretagna controllava il Canale di Suez e si riservò il diritto di mantenere delle truppe. In Iraq (su cui aveva il mandato della Società delle
Nazioni) e in Arabia Saudita, gli Inglesi mantennero il controllo dei pozzi petroliferi. Il punto critico era rappresentato dall'India, dove nel dopoguerra si sviluppò un consistente movimento nazionalista guidato da un uomo di grande prestigio, Mohandas Karamchand Gandhi, che iniziò una lunga lotta, all'insegna della «non violenza», per l'indipendenza indiana.
Fra i territori che la Gran Bretagna ottenne in mandato rientrava anche la Palestina. In quest'area s'andavano ponendo le basi dei drammatici conflitti arabo-israeliani che sono giunti sino ai giorni nostri. Cresceva infatti il numero dei coloni ebrei che emigravano in Palestina con l'obiettivo di fondarvi uno Stato ebraico (sionismo).

La politica attuata dai governi francesi verso le colonie fu molto diversa da quella britannica. L'atteggiamento del governo mirava infatti ad assimilare le colonie in una «grande Francia».
Questa politica centralistica generò numerose opposizioni sia in Medio Oriente, dove la Francia aveva ottenuto il mandato dalla Società delle Nazioni sulla Siria e il Libano, sia in Africa settentrionale.
In Marocco, in Tunisia e soprattutto in Algeria si diffusero movimenti anticolonialisti di vario orientamento: sia democratico-socialista, sia religioso (di matrice islamica), sia nazionalista. Alle richieste di autonomia il governo francese reagì sempre con una dura repressione.
Anche in Indocina, negli anni Venti, si formò un movimento che rivendicava maggiore partecipazione alla vita politica.

Negli anni della prima guerra mondiale l'America Latina passò sotto l'influenza degli Stati Uniti.
Durante la guerra, infatti, i Paesi europei ridussero i loro investimenti, lasciando spazio a quelli statunitensi. Si trattava di finanziamenti ai governi e alle banche o di investimenti diretti in imprese industriali nel settore ferroviario, minerario, petrolifero.
Anche negli scambi commerciali gli Stati Uniti soppiantarono l'Europa; in alcuni settori operarono addirittura in regime di monopolio.
Tra i Paesi latinoamericani e gli Stati Uniti si instaurò un rapporto di forte dipendenza economica che condizionò anche i sistemi politici.
In alcuni casi, nell'area centramericana, gli Stati Uniti ricorsero anche all'intervento militare per proteggere i loro interessi.
Di maggiore autonomia godevano invece gli Stati più ricchi del Sud America - come il Brasile, l'Argentina e il Cile - che nel corso della guerra avevano avviato un processo di industrializzazione e di sviluppo economico. Era però uno sviluppo fragile perché poggiava essenzialmente su investimenti stranieri.
La grande crisi economica del 1929 evidenziò la fragilità dell'area latinoamericana. Il protezionismo degli Stati Uniti e dell'Europa rallentò notevolmente le importazioni di prodotti dall'America del Sud. Le difficoltà economiche crearono tensioni sociali e condizioni di instabilità politica che nel corso degli anni Trenta favorirono, anche in quest'area, l'affermazione di regimi autoritari.
Si trattava di governi dittatoriali e populisti, simili ai fascismi europei, che si insediarono in Argentina, Brasile, Cile.

Un caso particolare di populismo è rappresentato dal Messico dove nel 1910 scoppiò una rivoluzione che pose termine alla quarantennale dittatura del generale Porfirio Díaz. Nel novembre del 1910, infatti, un proprietario liberale del Nord, Francisco Madero, si mise alla testa di un movimento insurrezionale a cui si unirono gruppi di contadini guidati da Pancho Villa ed Emiliano Zapata.
Fu l'inizio della rivoluzione messicana che, un anno dopo, costrinse all'esilio il dittatore Díaz e portò alla presidenza della Repubblica Madero.
Gli anni successivi furono segnati così dalla guerra civile tra conservatori e radicali; questi ultimi erano sostenuti dai contadini. Uccisioni, colpi di Stato e rivalità fra i diversi leader politici caratterizzarono questa fase della rivoluzione fino alla sconfitta di Villa e di Zapata.
Alla presidenza fu allora eletto Venustiano Carranza, un militare, già seguace di Madero, che nel 1917 promulgò la Costituzione. Si trattava di una Costituzione molto avanzata, democratica, fondata sulla laicità dello Stato e sul riformismo sociale, destinata però a essere completamente disattesa: nel 1920, infatti, Carranza fu deposto e ucciso da uno dei suoi generali.
Fino al 1934 così il Messico fu retto da governi militari e autoritari.
In questo modo si consolidò nel Paese il modello populista, caratterizzato dal partito unico al potere e dalla tendenza a manipolare dall'alto la partecipazione popolare.

---

# L’Italia tra le due guerre: il fascismo

## 📍1.

Il 18 gennaio 1919 nella reggia di Versailles si apri la conferenza di pace tra le potenze vincitrici della prima guerra mondiale. La posizione dell'Italia era particolarmente delicata e causò aspri contrasti, Secondo il Patto di Londra l'Italia avrebbe dovuto ottenere la Dalmazia, lasciando la città di Fiume agli Austriaci. Il nuovo Stato iugoslavo però rivendicò la regione dalmata, in nome del principio di nazionalità.
La delegazione italiana guidata dal presidente del Consiglio Vittorio Emanuele Orlando e dal ministro degli Esteri Sidney Sonnino mantenne un atteggiamento incerto e ambiguo. Il governo italiano pretese con forza il rispetto del Patto di Londra, ma contemporaneamente, proprio in base al principio di nazionalità, cercò di ottenere anche l'annessione di Fiume, città abitata in prevalenza da Italiani.
Gli alleati contrastarono queste prese di posizione. Fu particolarmente intransigente il presidente americano Wilson che non era vincolato da nessun patto.
Il 24 aprile l'Italia lasciò la riunione per protestare contro l'arroganza del leader americano.
Wilson decise allora di rivolgersi direttamente agli Italiani facendo pubblicare un appello per sostenere la soluzione proposta dagli Americani, minacciando altrimenti di far cadere l'intero Patto di Londra.
Il 29 maggio la delegazione italiana fu costretta a ritornare al tavolo del negoziato per non rischiare di perdere anche quel poco che le spettava.

Il governo Orlando si dimise a metà giugno e fu eletto presidente del Consiglio Francesco Saverio Nitti, un economista di orienamento liberale democratico. Nitti si trovò immediatamente ad affrontare il malcontento dell'opinione pubblica borghese che fu rappresentato dalle sempre più frequenti manifestazioni dei nazionalisti e dagli atteggiamenti provocatori di Gabriele D'Annunzio.
Il governo fu accusato di incapacità nel tutelare gli interessi nazionali e lo stesso D'Annunzio fu l'artefice di un'impresa clamorosa: l'occupazione della città di Fiume nel settembre del 1919. Il governo Nitti, dopo una prima reazione, si limitò a deplorare a parole l'impresa e fece assai poco per sedare la ribellione.
Anche a causa delle incertezze di Nitti, nel 1920 tornò al governo Giolitti che s'impegnò da subito per risolvere la crisi iugoslava.
Infatti, firmò il Trattato di Rapallo: la Iugoslavia ottenne la Dalmazia, all'Italia fu assegnata l'Istria.
Fiume divenne uno Stato libero e indipendente.

Le conseguenze sociali ed economiche della guerra furono particolarmente pesanti per uno Stato giovane e fragile come quello italiano:

- il debito pubblico passò dai circa 14 miliardi di lire del 1910 ai circa 95 miliardi del 1920;
- svalutazione della lira e inflazione galoppante.

Le prime vittime di questa situazione furono proprio quei ceti sociali che avevano costituito fino ad allora la struttura portante dello Stato italiano: la piccola e media borghesia e i piccoli proprietari terrieri.

La lira perse quasi il 40% del suo valore, mentre il costo della vita aumentò di tre volte.

Questa situazione causò risentimento e malcontento soprattutto in quei piccoli e medi borghesi che in guerra avevano ricoperto ruoli di comando e speravano di ottenere in patria maggior prestigio sociale.

Durante la guerra più volte era stata utilizzata la promessa della «terra ai contadini» per incitare le masse rurali a resistere.
Nel 1914 l'Italia era un Paese ancora prevalentemente agricolo: il 55% della popolazione lavorava la terra.
Per comprendere la drammatica situazione delle campagne, bisogna avere ben presente la struttura della proprietà agraria.
I 9/10 dei proprietari possedevano soltanto un ettaro di terreno, un'estensione troppo piccola anche per un'agricoltura di sussistenza. Molti piccoli proprietari quindi erano costretti ad affittare i fondi dai medi e grandi proprietari, oppure a lavorare come braccianti. Questa attività in particolare era molto faticosa, mal retribuita e caratterizzata da una continua precarietà. Era dunque diffusa una gran fame di terra da coltivare, soprattutto da parte di chi, tornato a casa, aveva trovato i propri terreni ormai improduttivi perché trascurati a causa della lunga assenza.

Grazie alle commesse di guerra l'apparato industriale italiano aveva incrementato la produzione. Lo dimostra chiaramente la crescita del numero dei lavoratori impiegati.
Era cambiata anche la fisionomia del vecchio Stato liberale, divenuto il primo cliente delle grandi industrie siderurgiche e meccaniche e allo stesso tempo un importante distributore di impieghi.
La nuova ricchezza era finita soprattutto nelle mani di pochi speculatori che avevano vissuto la guerra come un grande affare.
Chi aveva rischiato la vita nelle trincee, invece, fu in prima linea anche nel subire le pesanti conseguenze economiche della guerra: in Italia come altrove, infatti, la necessità della riconversione della produzione determinò una crescente disoccupazione.
In un simile contesto divennero sempre più aspre le lotte sociali.
Tra il 1918 e il 1920 la Confederazione Generale dei Lavoratori (CGL) aumentò considerevolmente il numero dei propri iscritti passando da 250 000 a 2200 000. Nel 1918 venne fondata la CIL (Confederazione Italiana dei Lavoratori), sindacato d'ispirazione cattolica.
Per la prima volta si poteva parlare in Italia della presenza di masse operaie, in buona parte specializzate, consapevoli del proprio ruolo sociale e agguerrite nel portare avanti le rivendicazioni sindacali.

La situazione sociale ed economica italiana divenne esplosiva. Gli scioperi si moltiplicarono con una crescita esponenziale di adesioni

In questo movimento molto composito si affacciò anche il cosiddetto «bolscevismo bianco», rappresentato da gruppi di militanti cattolici che proponevano soluzioni non molto diverse da quelle dei socialisti.

Le lotte ottennero qualche risultato sia per i contadini sia per gli operai che scioperavano per il carovita:

- aumenti salariali per i braccianti;
- parziale redistribuzione delle terre incolte occupate;
- giornata lavorativa di otto ore;

Nel 1919 la scena politica italiana fu caratterizzata da importanti elementi di novità.
Don Luigi Sturzo fondò il Partito Popolare Italiano (PPI) che segnò il coinvolgimento diretto dei cattolici nella vita politica dell'Italia.
Il PPI riuscì in poco tempo a proporsi come partito di massa, saldamente ancorato alla realtà sociale.
Laico, non confessionale, costituzionale e non classista: questi furono i pilastri su cui don Sturzo fece crescere il PPI, secondo lo spirito della dottrina sociale della Chiesa.
E inizialmente non mancò l'appoggio delle gerarchie ecclesiastiche che temevano l'avanzata del Partito socialista.

L'altro importante fatto politico avvenuto nel 1919 fu la nascita del movimento chiamato Fasci di combattimento, fondato da Benito Mussolini.
Si collocò politicamente a sinistra, battendosi per radicali riforme sociali.
Il manifesto politico dei Fasci fu chiamato programma di San Sepolcro.
In campo sociale i fascisti proposero il minimo salariale, la giornata lavorativa di otto ore e la gestione dell'impresa estesa anche ai rappresentanti dei lavoratori.
Inoltre si battevano per un'imposta progressiva sul capitale e per l'estensione del voto alle donne.
In breve tempo, però, Mussolini si sbarazzò di questo programma e il movimento si caratterizzò soprattutto per l'aggressività verbale dei suoi membri e la violenza della loro condotta, sia nei confronti dei socialisti che della classe dirigente liberale.

## 📍2. Il biennio rosso in Italia

Nel novembre del 1919 si tennero delle elezioni che rivoluzionarono il quadro politico italiano. Innanzitutto venne utilizzato per la prima volta il sistema proporzionale voluto dai socialisti e dai popolari per una maggiore democratizzazione della vita politica.

Ebbero la meglio quindi i due grandi partiti di massa, meglio organizzati e radicati nella società italiana:

- il Partito socialista si affermò come primo partito, con il 32% dei voti e 156 seggi, il triplo rispetto al 1913;
- secondo per consensi fu il Partito popolare che, alla prima prova elettorale, ottenne ben 100 deputati;
- i vecchi gruppi liberal-democratici subirono un drastico ridimensionamento, passando dai 300 seggi del 1913 a circa 200.

Questi risultati elettorali non riuscirono a dare stabilità al Paese, anzi ne acuirono le difficoltà.

Nel 1920 la protesta fece un ulteriore salto di qualità passando all'occupazione delle fabbriche.
La loro intransigenza provocò un crescendo di tensione: i sindacati proclamarono uno sciopero bianco, gli operai cioè entravano in fabbrica ma non lavoravano; gli industriali allora dichiararono la chiusura degli stabilimenti.
In agosto scattò infine l'occupazione delle fabbriche, guidata dai sindacati rossi mentre i sindacati cattolici, poco organizzati nel settore metallurgico, rimasero estranei alla protesta.
Tra i gruppi rivoluzionari più attivi e preparati si distinse quello torinese raccolto intorno alla rivista «l'Ordine Nuovo», tra i cui fondatori vi fu anche Antonio Gramsci. La rivista aveva più volte indicato agli operai lo strumento rivoluzionario dei consigli di fabbrica per acquistare maggiore potere nel controllo delle aziende e nella società.

Nel giugno 1920 fu chiamato l'ormai ottantenne Giovanni Giolitti a sostituire il dimissionario governo Nitti, indebolito dalle lotte sociali e soprattutto dalla vicenda di Fiume.
Nonostante le pressioni degli industriali, si rifiutò di utilizzare la forza per far sgombrare gli stabilimenti. Realizzò invece un'intelligente opera di mediazione e di riconciliazione tra CGL e industriali; gli operai ottennero aumenti salariali e la promessa, mai realizzata, di un possibile controllo sulla gestione delle aziende; in cambio sgomberarono le fabbriche.

Nonostante il successo elettorale e i risultati ottenuti con le lotte sindacali, il socialismo italiano era molto diviso al proprio interno.
Per i massimalisti guidati da Giacinto Menotti Serrati la rivoluzione russa del 1917 divenne il modello da seguire, anche se la strategia per arrivare a un autentico moto rivoluzionario non era per nulla chiara.
I riformisti contavano nelle proprie file personalità come Filippo Turati e Claudio Treves, in minoranza nel partito ma maggioritari nella CGL e nei comuni amministrati dai socialisti.
Al Congresso di Livorno del gennaio 1921 le contraddizioni esplosero. Lenin stesso esercitò delle pressioni affinché fossero applicati i ventuno punti approvati dal Comintern nel 1920: in particolare chiese a Serrati di estromettere i riformisti.
I massimalisti però non volevano giungere fino a questo punto; in tale contesto la corrente guidata da Gramsci e Bordiga si staccò dal Partito socialista e fondò il Partito Comunista d'Italia.

## 📍3. La marcia su Roma

Mentre le durissime lotte sociali del biennio 1919-20 avevano indebolito e deluso la maggior parte degli operai delle fabbriche, nelle campagne i contadini erano riusciti a ottenere risultati significativi.
Le associazioni, contrattavano direttamente con i proprietari il numero di giornate lavorative necessarie per ogni campo e poi distribuivano il lavoro tra i loro iscritti. Questo sistema, all'apparenza solido, era caratterizzato in realtà da profonde divisioni tra i salariati, da una parte, che miravano alla socializzazione della terra e i mezzadri e i piccoli affittuari, dall'altra, che speravano invece di riuscire a diventare, prima o poi, proprietari terrieri.

Alla fine del 1920 Bologna era diventata il centro propulsore del movimento sindacale tanto che, alle elezioni amministrative del Comune, i socialisti ottennero una schiacciante vittoria. Il 21 novembre 1920, giorno dell'insediamento del Consiglio comunale a Palazzo d'Accursio, quando il sindaco si affacciò sulla piazza per salutare, partirono dalla folla dei colpi di pistola.
I fatti di Palazzo d'Accursio segnarono la nascita del fascismo agrario.
Fino all'autunno del 1920 il movimento fondato da Mussolini aveva avuto un ruolo ininfluente nelle vicende politiche nazionali.
Tra la fine del 1920 e l'inizio del 1921 avvenne la svolta: fu accantonato il programma di San Sepolcro e vennero costituite formazioni paramilitari (le squadre d'azione) per intimidire e colpire duramente il movimento socialista.
Lo squadrismo ottenne immediatamente l'appoggio finanziario della borghesia terriera desiderosa di una rivalsa, ma raccolse militanti soprattutto:

- tra gli ex combattenti che faticavano a reinserirsi nella vita civile;
- tra i giovani che volevano impegnarsi contro i nuovi presunti «nemici della patria»;
- nelle file della piccola borghesia che cercava spazi per affermare l'orgoglio della propria diversità nei confronti delle masse socialiste.

La tolleranza mostrata da molti politici liberali verso il fascismo fu dovuta soprattutto alla speranza di potersene servire per arginare le pretese del movimento socialista, innanzitutto, ma anche dei popolari.
In questo senso si può comprendere la decisione di Giolitti di indire nuove elezioni il 15 maggio 1921 e di accettare la composizione di liste comuni (i blocchi nazionali) formate da liberali, gruppi di centro e fascisti.
Giolitti puntava a un netto ridimensionamento dei socialisti e dei popolari ma i risultati elettorali non gli diedero ragione: il Partito socialista subì una lieve flessione (da 156 a 122 seggi), considerando anche la scissione del Partito comunista che ottenne 16 seggi; i popolari addirittura aumentarono i consensi (da 100 a 107 seggi). I blocchi nazionali ottennero 275 seggi, 35 dei quali andarono ai fascisti.
La speranza dei liberali di riconquistare un saldo controllo del Parlamento fu delusa. Giolitti ne prese atto e rinunciò a guidare il governo che venne invece formato dall'ex socialista Ivanoe Bonomi.
A questo punto al Congresso dei Fasci del novembre 1921 Mussolini decise di trasformare il movimento nel Partito Nazionale Fascista (PNF): era un altro passaggio della svolta moderata con cui cercava di proporsi sempre più come leader politico credibile e affidabile.
Mussolini riuscì a limitarne la libertà d'azione, ma si rese anche conto di non poter fare a meno della capacità di proselitismo dei militanti più intransigenti.

Luigi Facta sostituì Bonomi dopo solo sei mesi di governo instabile e inconcludente. Il nuovo presidente del Consiglio avrebbe guidato il Paese fino all'ottobre 1922, appoggiato da una coalizione di liberali e popolari. Si trattava di un governo molto debole sia per la scarsa determinazione di Facta, sia per l'assenza di una profonda intesa tra le forze che componevano la maggioranza.
Mussolini nel frattempo rimodellò abilmente il Partito fascista, modificandone significativamente il programma:

- abbandonò le posizioni repubblicane e si dichiarò favorevole alla monarchia;
- accantonò la critica del capitalismo e sostenne l'opportunità di una politica economica liberista;
- abbandonò l'anticlericalismo e attaccò il Partito popolare di don Sturzo come se fosse espressione di una sorta di «bolscevismo bianco», rivoluzionario e pericoloso per le campagne.

Queste nuove posizioni resero più presentabile e credibile il PNF come forza di governo. Mussolini comprese che era venuto il suo momento e decise di forzare i tempi. Il 24 ottobre 1922 riunì a Napoli migliaia di camicie nere in vista della marcia su Roma per assumere il potere con la forza.
Quando venne informato dell'evento, Facta chiese al re Vittorio Emanuele III di firmare la proclamazione dello stato d'assedio che avrebbe permesso l'intervento dell'esercito. Il re, dopo qualche esitazione, rifiuto; il 28 ottobre le colonne fasciste entrarono nella capitale il 30 ottobre del 1922 Mussolini, giunto da Milano, dove si era trattenuto attendendo gli sviluppi della situazione, ricevette ufficialmente dal sovrano l'incarico di formare il
nuovo governo.

## 📍4. La dittatura fascista

il 1922 e il 1924 Mussolini guidò un governo di coalizione costituito da fascisti, liberali, popolari (benché Sturzo fosse contrario) e altre componenti.
Forte di questi appoggi, il 16 novembre 1922 Mussolini si presentò al Parlamento con un discorso arrogante che gli valse comunque 306 voti favorevoli.
Per realizzare ciò che aveva promesso ai gruppi politici conservatori che lo avevano appoggiato, Mussolini abbandonò la politica economica di Giolitti che colpiva i profitti di guerra e sciolse le amministrazioni comunali in mano a socialisti e popolari;
Ma tutte le opposizioni e una parte degli alleati chiedevano a Mussolini soprattutto la fine della violenza come arma di lotta politica e lo scioglimento delle squadre fasciste.
A tale prospettiva si oppose con forza l'ala radicale del partito guidata da Roberto Farinacci. Mussolini decise allora di creare la Milizia Volontaria per la Sicurezza Nazionale, legalizzando di fatto lo squadrismo e trasformandolo in forza armata del regime.
Nel 1923 il governo Mussolini perse l'appoggio dei popolari che nel Congresso di Torino dello stesso anno approvarono la posizione antifascista di don Sturzo.

Negli anni 1922-24 Mussolini alternò un atteggiamento moderato, a richiami minacciosi verso una possibile seconda ondata rivoluzionaria.
Tra i provvedimenti assunti in questo periodo merita ricordare:

- la riforma della scuola varata dal governo il 27 aprile 1923, sotto la responsabilità del ministro della Pubblica Istruzione, il filosofo Giovanni Gentile;
- la legge Acerbo approvata dal Parlamento il 14 novembre 1923, che riformava il sistema elettorale in senso fortemente maggioritario, assegnando alla lista che conquistava la maggioranza relativa (con almeno il 25% dei voti) due terzi dei seggi alla Camera.
Le forze d'opposizione, tra cui l'anziano Giolitti, si presentarono profondamente divise, condannandosi inevitabilmente alla sconfitta.

Il 30 maggio del 1924 il deputato Giacomo Matteotti, segretario del Partito Socialista unitario, pronunciò un coraggioso discorso alla Camera, denunciando i brogli e le violenze compiute dalle squadre fasciste in molti seggi elettorali.
Il 10 giugno Matteotti venne rapito a Roma da un gruppo di squadristi e ucciso in auto a pugnalate. Il suo cadavere fu ritrovato solo due mesi dopo, in una macchia a pochi chilometri dalla capitale.
Improvvisamente gran parte dell'opinione pubblica si risvegliò dal torpore degli anni precedenti e si rese conto delle responsabilità fasciste. Gli esecutori del delitto furono arrestati dopo pochi giorni, ma i mandanti non furono mai scoperti. Vi fu un crollo della popolarità di Mussolini e del suo partito, ma le opposizioni non riuscirono ad approfittarne, sia perché fortemente ridimensionate dalle elezioni, sia per le divisioni interne.
Si formò così la cosiddetta secessione dell'Aventino: di fatto l'opposizione sperava che il re intervenisse ritirando la fiducia a Mussolini, ma il sovrano non assunse alcuna iniziativa.

Dopo pochi mesi l'ondata antifascista cominciò a placarsi e Mussolini comprese che era giunto il momento di contrattaccare. Il 3 gennaio 1925 in un discorso alla Camera, il duce si assunse la responsabilità «politica, morale e storica» di quanto era avvenuto, gettando le basi per l'instaurazione della dittatura: «Se il fascismo è stato un'associazione a delinquere, io sono il capo di questa associazione a delinquere! Era l'annuncio degli arresti e delle restrizioni che in pochi giorni resero impossibile la vita dei partiti d'opposizione e dei loro organi di stampa. L'assassinio di Giacomo Matteotti segnò dunque la morte della democrazia liberale e l'affermazione della dittatura fascista.

## 📍5. L’Italia fascista

A partire dal 1925 il fascismo fece approvare una serie di leggi (dette «fascistissime») che segnarono formalmente la definitiva trasformazione del fascismo in una dittatura. Fu il giurista Alfredo Rocco a ispirare il nuovo quadro legislativo.
Furono eliminate le autonomie locali e le elezioni comunali: la carica di sindaco fu abolita e sostituita da quella di podestà, nominato direttamente dal governo. Fu limitata la libertà di stampa e di associazione, mentre nel 1926 vennero sciolti tutti i partiti di opposizione e chiusi i giornali antifascisti. Vennero quindi dati ampi poteri alla polizia segreta, incaricata di individuare e arrestare gli oppositori.
Fu istituito il Tribunale speciale per la difesa dello Stato (novembre 1926) che comminò decine di condanne a morte e oltre 28 000 anni di carcere.

Contemporaneamente alla riorganizzazione dello Stato, Mussolini si preoccupò anche della normalizzazione del partito.
Fu tolta così la direzione del partito a Roberto Farinacci, squadrista della prima ora, tra i più radicali e violenti, e le cariche gerarchiche vennero assegnate direttamente da Mussolini.
Il Partito fascista si riorganizzò in una struttura burocratica sottoposta localmente ai prefetti. Il vertice era rappresentato dal Gran Consiglio del fascismo, affidato alla presidenza di Mussolini, unico organo del partito in cui si discuteva collegialmente di linea politica.
Nel 1928 la trasformazione dello Stato liberale in Stato totalitario fu completata con una nuova legge elettorale.

Il nuovo ruolo del partito può essere colto appieno nell'impegno profuso per organizzare il consenso nella società italiana, cercando di influire sui costumi, sulla mentalità e sulle attività quotidiane delle masse. Innanzitutto divenne obbligatorio possedere la tessera del partito per ottenere un posto nell'amministrazione pubblica o per conquistare promozioni e privilegi.
l'Opera Nazionale Dopolavoro si occupava del tempo libero dei lavoratori proponendo gite, gare sportive e altre forme di animazione, mentre il Comitato Olimpico Nazionale Italiano (CONI) stimolava e allo stesso tempo controllava le attività sportive, fino ad allora affidate a società private. Ma le organizzazioni più importanti furono i Fasci giovanili, i Gruppi Universitari Fascisti (GUF) e soprattutto l'Opera Nazionale Balilla (ONB). A quest'ultima associazione appartenevano i ragazzi fra gli 8 e 14 anni (detti balilla) e quelli fra i 14 e 18 anni (detti avanguardisti). I ragazzi venivano educati alla dottrina fascista e al culto di Mussolini con esercitazioni, marce e parate militari.

Il controllo dell'informazione fu attuato in maniera capillare. La stampa fu sottoposta a censura; i direttori di giornale non graditi al governo furono sostituiti. Nel 1927 venne fondato un ente radiofonico, l'EIAR (antenato della RAI) che si occupò della gestione di questo nuovo potentissimo mezzo di comunicazione. La radio si rivelò infatti uno strumento molto efficace per la diffusione delle informazioni che il regime voleva far conoscere agli Italiani. I discorsi di Mussolini furono ascoltati dai cittadini nei locali pubblici, nei luoghi d'incontro e nelle case proprio grazie alla radio.
Dal 1926 i gestori delle sale cinematografiche vennero obbligati a proiettare i cinegiornali dell'Istituto LUCE, casa di produzione alle dirette dipendenze di Mussolini.
Nel 1937 fu infine istituito il Ministero della Cultura Popolare (MINCULPOP) con l'obiettivo di controllare e orientare tutti gli aspetti della vita culturale italiana.

Le gerarchie ecclesiastiche pensarono fosse giunto il momento di chiudere lo storico contrasto che aveva segnato i rapporti fra lo Stato e la Chiesa fin dalla nascita del Regno d'Italia. Le trattative fra governo e Santa Sede cominciarono nel 1926 e si conclusero I'11 febbraio 1929 con la firma dei Patti lateranensi.

Il documento si componeva di tre parti:

- un trattato internazionale col quale la Chiesa riconosceva ufficialmente lo Stato italiano e la sua capitale, ottenendo la sovranità sullo Stato della Città del Vaticano (comprendente la basilica di San Pietro e i palazzi circostanti);
- una convenzione finanziaria che impegnava l'Italia a versare un'indennità al Vaticano per la perdita dello Stato pontificio;
- un concordato che doveva regolare i rapporti tra lo Stato e la Chiesa: esso stabili, fra l'altro, che quella cattolica era la religione di Stato e ne regolamentò l'insegnamento nelle scuole, riconoscendo nella dottrina cattolica il «fondamento e coronamento» dell'istruzione pubblica.

Pio XI espresse soddisfazione per l'accordo raggiunto, riconoscendo che era stato «nobilmente assecondato» dal governo e pronunciando un giudizio su Mussolini di cui il Vaticano si sarebbe dovuto pentire: «E forse ci voleva anche un uomo come quello che la Provvidenza Ci ha fatto incontrare; un uomo che non avesse le preoccupazioni della scuola liberale».

Don Sturzo, invece, commentò con amarezza la conciliazione tra Stato e Chiesa: Il sacerdote siciliano aveva ragione.

Nel 1931, infatti, il regime tentò di esautorare completamente l'Azione Cattolica dal compito di educare i giovani.

La prima fase (1922-1925) della politica economica fascista fu di stampo decisamente liberista, sotto la guida del ministro delle Finanze Alberto De Stefani. Furono concessi sgravi fiscali alle imprese e stimolata l'iniziativa privata con incentivi.
I buoni risultati raggiunti però non furono sufficienti a fermare l'inflazione e a stabilizzare la moneta, uno dei fattori di maggior preoccupazione sia per il ceto medio risparmiatore, sia per gli investitori esteri.
Così nel 1926 Mussolini decise di cambiare linea politica: nominò ministro delle Finanze Giuseppe Volpi e impostò la nuova politica economica sulla stabilizzazione della lira, adottando misure protezionistiche.
Rimase famoso il discorso tenuto a Pesaro il 18 agosto 1926 sulla rivalutazione della lira: venne fissato l'obiettivo del cambio con la sterlina a 90 lire (nel 1925 ci volevano 150 lire per una sterlina), obiettivo raggiunto in poco più di un anno.

Uno dei primi importanti provvedimenti economici fu l'aumento del dazio sui cereali, accompagnato da una enfatica e insistente campagna propagandistica, la cosiddetta battaglia del grano. Questa avrebbe dovuto portare l'Italia a raggiungere l'autosufficienza nel settore dei cereali, aumentando la superficie coltivabile e migliorando le tecniche di coltivazione.
In questo senso nel 1928 venne iniziato il progetto di bonifica integrale delle maggiori zone paludose italiane.
Il progetto riuscì solo in parte, ma furono significativi gli interventi realizzati nell'Agro Pontino dove venne costruita la città di Littoria (oggi Latina). Fu questo il primo passo della politica dell'autarchia che caratterizzerà il fascismo degli anni Trenta, soprattutto a livello ideologico. La parola autarchia è di origine greca e significa «autosufficienza»: l'Italia, dunque, avrebbe dovuto essere in grado di produrre autonomamente ciò di cui aveva bisogno, evitando di dipendere dalle importazioni estere. In realtà tutte queste misure economiche ebbero costi sociali molto alti.

Per quanto riguarda i rapporti tra operai e imprenditori, il fascismo condannò lo sciopero e la lotta di classe, abolendo anche ogni libertà di contrattazione. Nell'ottobre del 1925 i sindacati fascisti e la Confindustria raggiunsero un'intesa che divenne poi legge nel 1926 e che prevedeva validità giuridica ai soli accordi stipulati dai sindacati fascisti.
Questa posizione ideologica propagandata come «nuova» e distinta sia dalle idee socialiste sia da quelle liberali fu chiamata corporativismo.
L'ordinamento corporativo fu enunciato in modo ufficiale dalla Carta del lavoro del 1927: tutti i settori della produzione avrebbero dovuto organizzarsi in corporazioni, ovvero organizzazioni composte da lavoratori e padroni appartenenti allo stesso settore economico, inquadrati comunque all'interno dello Stato e soggetti a un apposito ministero.

L'intervento dello Stato in campo economico divenne sempre più massiccio negli anni Trenta. Anche per fronteggiare gli effetti della crisi economica del 1929, nel 1931 fu istituito l'Istituto Mobiliare Italiano (IMI), un istituto di credito pubblico capace di sostituirsi alle banche nel sostegno alle industrie in difficoltà. Nel 1933, inoltre, fu creato l'Istituto per la Ricostruzione Industriale (IRI) che divenne azionista di maggioranza di banche in crisi e acquistò il controllo di alcune grandi aziende italiane (Ilva, Terni e Ansaldo). Nella sostanza, decine di imprese furono salvate grazie ai finanziamenti pubblici.

Sin dalle origini il fascismo fu caratterizzato ideologicamente da una forte componente nazionalista. La propaganda presentava Mussolini come alfiere della riscossa nazionale, l'uomo che sarebbe stato capace di far rivivere la gloria dell'antica Roma imperiale e di riscattare il Paese dalle penalizzazioni subite.
Fino agli anni Trenta, però, i proclami nazionalisti rimasero vaghi e velleitari e il duce preferì mantenere la tradizionale amicizia con Francia e Inghilterra. Le cose cambiarono nel 1934, quando Mussolini decise di conquistare l'Etiopia. Il duce intendeva dare all'Italia un impero, ampliando i possedimenti coloniali già acquisiti.

Le truppe italiane invasero l'Etiopia il 3 ottobre 1935, senza nemmeno una dichiarazione di guerra. Grazie all'abbondanza di uomini e mezzi, Addis Abeba fu conquistata il 5 maggio 1936. Il re etiope Hailè Selassiè fu costretto alla fuga, ma iniziò una logorante guerriglia che i fascisti non riuscirono mai a sconfiggere completamente.
Mussolini era convinto che la conquista dell'Etiopia avrebbe ottenuto il tacito assenso di Francia e Gran Bretagna e che la comunità internazionale non sarebbe intervenuta. Invece, pochi giorni dopo l'inizio dell'invasione, la Società delle Nazioni condannò l'Italia in quanto aggressore di un altro Paese membro dell'associazione. Nel novembre 1935 la Società delle Nazioni decretò anche delle sanzioni economiche, vietando la vendita all'Italia di beni di interesse militare.
In realtà, le sanzioni non indebolirono in nessun modo il potenziale bellico italiano perché non comprendevano le materie prime, ma soprattutto perché di fatto non vennero rispettate neanche dagli Stati che le avevano imposte. In compenso fornirono a Mussolini l'opportunità di assumere atteggiamenti vittimistici, denunciando l'ennesimo tentativo di «strangolare» l'Italia e di impedirle di conquistare il suo «posto al sole». Un ottimo argomento propagandistico che garantì al regime il consenso dell'opinione pubblica nazionale, unita nella volontà di resistere alle sanzioni: vi furono manifestazioni entusiaste di sostegno al governo e contro gli Inglesi; milioni di sposi donarono l'oro delle proprie fedi nuziali «alla patria»; i giornali denigrarono gli Etiopi come «selvaggi» da civilizzare e ogni pur timida voce d'opposizione sembrò sparire. Fu probabilmente questo il periodo in cui Mussolini e il fascismo godettero del maggior consenso.

Il 9 maggio 1936 Mussolini annunciò la fondazione dell'Impero dell'Africa Orientale Italiana (AOI) e offrì a Vittorio Emanuele III la corona di imperatore d'Etiopia.
Nell'estate del 1936 le sanzioni furono ritirate e Gran Bretagna e Francia riconobbero l'impero italiano d'Africa, lasciando così la sensazione che il fascismo fosse riuscito a imporre la propria volontà a tutta l'Europa.

La conseguenza più grave della guerra d'Etiopia fu l'avvicinamento di Mussolini a Hitler.
La Germania infatti aveva appoggiato la conquista coloniale italiana garantendo rifornimenti di armi e di materie prime.
Nell'ottobre del 1936 fu dunque firmato un patto di amicizia tra Italia e Germania (detto Asse Roma-Berlino). Non si trattava ancora di un'alleanza militare vera e propria, anche perché Mussolini voleva utilizzare questo accordo soprattutto per fare pressione sulle altre potenze europee affinché gli venissero concessi maggiori vantaggi in campo coloniale.
In quest'epoca l'Italia giunse anche a condividere le aberranti discriminazioni contro gli Ebrei che già caratterizzavano il nazismo. Nel 1938, infatti, il regime fascista promulgò le leggi razziali contro gli Ebrei, a imitazione di quelle già introdotte in Germania dal 1935. Queste leggi vietavano i matrimoni misti tra Ebrei e non Ebrei; impedivano agli Ebrei di frequentare la scuola pubblica, di fare il servizio militare, di svolgere determinate professioni. In Italia però non esisteva una forte tradizione antisemita e queste discriminazioni suscitarono molte perplessità nell'opinione pubblica e la dura condanna della Chiesa cattolica.
Le leggi contro gli Ebrei, dunque, indebolirono il consenso degli Italiani verso il fascismo e prepararono la crisi del regime che sarebbe stata determinata dalla seconda guerra mondiale.

## 📍6. L’Italia antifascista

A partire dal 1926 l'opposizione al fascismo divenne un reato, punito con il carcere o il confino. Per sottrarsi a queste persecuzioni molti scelsero di emigrare, come l'ex presidente del Consiglio Francesco Saverio Nitti che si rifugiò a Parigi.
Numerosi intellettuali si ritirarono negli studi, approfittando dei piccoli spazi di autonomia culturale che era possibile ritagliarsi nell'Italia fascista.
Un’eccezione importante fu rappresentata dal filosofo Benedetto Croce, intellettuale stimato in tutta Europa e per questo tollerato dal regime che non voleva danneggiare la propria immagine internazionale. Croce, dopo un'iniziale simpatia per il fascismo, nel 1925 dichiarò il proprio dissenso attraverso il Manifesto degli intellettuali antifascisti in cui condannò l'ideologia mussoliniana.

Giustizia e Libertà fu un movimento antifascista fondato a Parigi nel 1929 da un gruppo di profughi italiani, tra i quali Carlo Rosselli, Emilio Lussu ed Ernesto Rossi. Vi aderirono giovani di formazione liberale che si rifacevano alle idee di Piero Gobetti, nuclei di laici repubblicani e uomini di cultura socialista vicini a Gaetano Salvemini.
Nel 1937 Rosselli venne assassinato da sicari fascisti insieme al fratello Nello. Il movimento si dissolse nel 1940, quando la Francia venne occupata dai Tedeschi. Ma molti dei suoi uomini si riunirono nella Resistenza contro l'occupazione nazista in Italia, fondando il Partito d'Azione.

Il Partito comunista fu la forza politica che meglio seppe organizzare un rete di opposizione clandestina in Italia. Questa scelta costò enormi sacrifici umani: più di tre quarti dei condannati dal Tribunale speciale fascista furono infatti militanti comunisti.
La direzione del partito stabili la sua sede a Parigi, sotto la guida di Palmiro Togliatti divenuto segretario generale del partito nel 1926; in Italia i militanti diffondevano giornali, opuscoli, volantini di propaganda antifascista e s'infiltravano nelle organizzazioni giovanili, nei sindacati fascisti e nel dopolavoro.
Solo nel 1934, di fronte alla crescita e diffusione del fascismo in tutta Europa, l'Internazionale Comunista cambiò linea politica, invitando a unire le forze per sconfiggere il nemico. In diversi Stati così si realizzarono accordi politici tra socialisti e comunisti.

Altri gruppi antifascisti erano composti da repubblicani, socialisti, come Filippo Turati, Giuseppe Saragat e Pietro Nenni, cattolici come Giuseppe Donati e Alcide De Gasperi.
A Parigi gli esuli italiani, soprattutto gli esponenti di ispirazione repubblicana e socialista, fondarono nel 1927 un'organizzazione unitaria, la Concentrazione antifascista: essa si impegnò attivamente in un'opera di propaganda internazionale contro il regime.

---

# Il Fascismo in sintesi

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20131.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20132.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20133.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20134.png)

---

# La crisi del 1929

## 📍1.

Tra il 1922 e il 1929 gli Stati Uniti conobbero una forte crescita economica dovuta all'aumento della produzione industriale e dei consumi di massa. Grazie alla pubblicità, ai pagamenti rateali e alla nascita di nuove forme di distribuzione come i grandi magazzini, si diffusero nuovi prodotti destinati a rivoluzionare la vita quotidiana.

Il desiderio di difendere il benessere raggiunto e impedire la diffusione di idee sovversive portò all'isolazionismo, alla xenofobia contro gli immigrati e i neri e al proibizionismo che però, invece di eliminare il consumo di alcol, ne favorì il commercio illegale. L'orientamento isolazionista fu sostenuto dal Partito Repubblicano, che governò gli USA per tutti gli anni Venti: si decise di non intervenire nelle questioni di politica internazionale e di non aderire alla Società delle Nazioni che era stata promossa dall'ex presidente democratico Woodrow Wilson.

I repubblicani adottarono una politica liberista: ridussero le imposte dirette e la spesa pubblica e cercarono di favorire gli investimenti tenendo basso il tasso di interesse. La scelta di rinunciare a qualsiasi forma di intervento nell'economia permise la formazione di monopoli e oligopoli,

Nel corso degli anni Venti l'investimento in Borsa divenne un fenomeno di massa e il valore delle azioni raddoppiò con facili guadagni per gli investitori.

Malgrado il boom della Borsa, la situazione dell'economia reale era differente: il potere di acquisto dei consumatori era molto diminuito e, quando il mercato dei beni di consumo durevoli raggiunse la saturazione, l'economia americana andò incontro a una crisi di sovrapproduzione. La bolla speculativa si gonfiò improvvisamente e, quando gli investitori cercarono di vendere i loro titoli, il valore delle azioni crollò.

La crisi borsistica produsse una serie di effetti a catena. I risparmiatori che avevano acquistato a credito i pacchetti azionari, confidando nelle opportunità offerte dal gioco speculativo, non poterono più far fronte agli impegni. Gli agenti di Borsa, a loro volta, si erano indebitati con le banche, e dovettero denunciare la propria insolvibilità.
Gli effetti del crollo di Wall Street, dunque, si trasmisero al sistema creditizio. Molte banche dovettero chiudere, scatenando il panico tra i risparmiatori. I correntisti, temendo l'azzeramento dei propri depositi, si affrettarono a ritirarli, riducendo così ancor più la liquidità a disposizione degli istituti di credito. Questi d'altronde, in previsione di tempi difficili, tentavano di trattenere le proprie riserve e concedevano prestiti solo in casi eccezionali. Il risultato fu una gigantesca diminuzione della liquidità, con una serie di gravi conseguenze sul piano dell'economia reale. Le aziende, non potendo più accedere al credito per gli investimenti, riducevano la produzione, tagliavano i salari e licenziavano.
Nel 1932 la produzione industriale scese di 10 punti percentuali rispetto a tre anni prima, mentre il numero dei disoccupati giunse alla cifra esorbitante di quasi 14 milioni. La disponibilità finanziaria delle famiglie americane subì dunque una caduta verticale, aggravata dall'impossibilità di accedere ai mutui edilizi e di realizzare acquisti a rate.
Il crollo della domanda complessiva che ne conseguì determinò un'ulteriore contrazione della produzione industriale.

Ben presto la crisi coinvolse anche le banche; non riuscendo più ad accedere ai prestiti, le aziende cominciarono a tagliare i salari e a licenziare i dipendenti. La disoccupazione toccò livelli altissimi e i consumi crollarono, di conseguenza anche la produzione. La crisi economica americana (detta Big Crash) coinvolse anche l'Europa. In particolare, ebbe conseguenze pesantissime sull'economia tedesca, gravata dai debiti contratti per sostenere le spese di riparazione della prima guerra mondiale.

Nelle elezioni del 1932 il democratico Franklin Delano Roosevelt sconfisse il presidente repubblicano Hoover, considerato troppo legato agli interessi della finanza. Roosevelt abbandonò il dogma liberista secondo cui il mercato ha la capacità di riequilibrarsi spontaneamente e inaugurò un nuovo corso, detto appunto «New Deal», basato sull'intervento dello Stato per contrastare la crisi economica.

Lo Stato intervenne sul sistema finanziario per svalutare il dollaro e favorire le esportazioni; intervenne sul sistema fiscale per ridurre le sperequazioni; limitò la sovrapproduzione per contrastare la caduta dei prezzi; finanziò grandi opere pubbliche per creare nuovi posti di lavoro; garantì sussidi ai disoccupati.

Il New Deal incontrò le resistenze delle lobby conservatrici (in particolare di imprenditori e finanzieri), che si appellarono alla Corte suprema per mettere in discussione la costituzionalità delle leggi proposte da Roosevelt. Il presidente si appellò al popolo americano e riuscì a far sostituire alcuni giudici della Corte.
Il New Deal gettò le basi del Welfare State, che assicura assistenza sociale ai cittadini; inoltre, l'espansione dell'amministrazione pubblica e della burocrazia creò nuovi posti di lavoro. La ripresa fu lenta e non toccò tutti i lavoratori, ma la politica di Roosevelt ebbe un grande successo perché seppe infondere speranza e ottimismo.

---

# Il nazismo e la crisi delle relazione internazionali

## 📍1. La repubblica di Weimar

L'ultimo anno di guerra fu per la Germania particolarmente difficile. La popolazione, ma anche l'esercito, erano ormai certi della sconfitta. Il malcontento era diffuso e le istituzioni non erano più in grado di contenere un'opposizione sempre più decisa. I Tedeschi chiedevano pace e democrazia, mentre la monarchia dimostrava tutta la sua debolezza e non aveva più il controllo della situazione.
Intanto la propaganda socialista e il mito della rivoluzione bolscevica riscuotevano successo.
Il 9 novembre 1918 la monarchia fu travolta: a Berlino fu proclamata la repubblica, mentre il kaiser Guglielmo II fuggiva in Olanda.
Fu formato un governo provvisorio composto da esponenti socialdemocratici e sostenuto anche dallo stato maggiore dell'esercito che intendeva impedire un'ulteriore radicalizzazione della situazione. Il presidente di questo governo, il socialdemocratico Friedrich Ebert, si impegnò a riportare il Paese alla normalità e alla legalità.

La componente maggioritaria del movimento socialista era il Partito Socialdemocratico Tedesco, I'SPD, che sosteneva posizioni riformiste e democratiche. Questo partito era contrario a esiti rivoluzionari e intendeva costruire in Germania un sistema parlamentare. I socialdemocratici consideravano i consigli degli operai e dei soldati un'istituzione solo transitoria, da smantellare nel momento in cui gli organismi democratici del Paese fossero stati pienamente operativi.
La linea della socialdemocrazia tedesca era dunque moderata e inevitabilmente portò allo scontro e alla divisione con l'ala estrema del movimento socialista che sosteneva il potere dei consigli degli operai e dei soldati ed era contraria all'Assemblea Costituente.
Questa posizione era rappresentata da due soggetti:

- il Partito Socialdemocratico Indipendente, I'USPD, una formazione nata nel 1917;
- i rivoluzionari della Lega di Spartaco, guidati da Rosa Luxemburg e Karl Liebknecht. Gli spartachisti, in origine una corrente interna all'USPD, nel dicembre 1918 diedero vita al Partito Comunista Tedesco, il KPD.

Il dissenso sull'orientamento del governo e del Partito socialdemocratico portò i rivoluzionari in piazza. A Berlino la protesta fu violentissima: nella settimana fra il 5 e il 13 gennaio 1919 gli spartachisti tentarono di boicottare le elezioni per la Costituente e di rovesciare il governo; occuparono edifici pubblici e sedi di giornali.

Le elezioni per l'Assemblea Costituente, le prime a suffragio universale, si tennero il 19 Gennaio 1919. I risultati premiarono I'SPD che fu il partito di maggioranza, ma non assoluta. Si formò quindi un governo di coalizione con le forze moderate del Zentrum, il partito Cattolico, e con i liberali democratici (DDP).
L’assemblea si mise al lavoro nella cittadina di Weimar, più tranquilla della capitale, e fu in grado nel mese di agosto di dare al Paese la Costituzione. La Germania divenne una repubblica federale (divisa in 17 Länder); il potere legislativo andò al Reichstag (il Parlamento) eletto a suffragio universale e con sistema proporzionale; il Reichsrat (Consiglio federale) aveva potere di veto legislativo; il potere esecutivo fu affidato al governo presieduto da un cancelliere (Primo ministro) responsabile di fronte al Parlamento.
Il presidente della Repubblica era eletto direttamente dal popolo ogni sette anni e deteneva ampi poteri.

Nello stesso periodo in cui veniva elaborata la Costituzione di Weimar, si perveniva all'ultimo atto della guerra con i trattati di pace elaborati dalla Conferenza di Parigi. A Versailles il 28 giugno 1919 fu firmato quello tra la Germania e le nazioni vincitrici. Il trattato riconosceva la Germania unica responsabile della guerra e di tutte le conseguenze da essa provocate.
L'umiliazione del Trattato di Versailles rafforzò il nazionalismo tedesco e lo spirito di rivincita delle forze più reazionarie che accentuarono la loro campagna antisocialista e antidemocratica.
Soprattutto il problema delle riparazioni dovute ai vincitori, fissate nella cifra astronomica di 132 miliardi di marchi d’oro, suscitò un'infinità di polemiche e di risentimento. Era una pretesa assurda: nella sostanza, la Germania avrebbe dovuto pagare ogni anno una rata pari a circa un quarto del suo prodotto nazionale; e in questo modo avrebbe esaurito il suo debito all'inizio degli anni Sessanta!
La destra accusò socialisti e democratici di avere tradito il Paese firmando la pace.

## 📍2. Dalla crisi economica alla stabilità

Le condizioni di pace imposte alla Germania e le difficoltà nel pagamento delle riparazioni di guerra generarono una profonda crisi economica. La Francia, inoltre, nel 1923, colse l'occasione del mancato pagamento di una rata delle riparazioni, per occupare militarmente la ricca zona industriale della Ruhr come garanzia di pagamento. I Tedeschi risposero con la resistenza passiva: lavoratori e imprenditori lasciarono le fabbriche e si rifiutarono di collaborare con gli invasori.
Per garantire un sostegno ai lavoratori e alle imprese, la banca tedesca stampò carta moneta in quantità crescente, inasprendo ulteriormente un'inflazione senza precedenti. La svalutazione del marco raggiunse il fondo quando, nel novembre 1923, il rapporto di cambio fra dollaro e marco fu di 1 dollaro per 4200 miliardi di marchi.
L'economia fu travolta, la moneta divenne carta straccia, i salari dei lavoratori vennero ridotti a spiccioli.

Gli anni tra il 1919 e il 1923 furono segnati da gravi tensioni sociali e politiche.
Il più attivo tra i gruppi estremisti era il Partito Nazionalsocialista Tedesco dei Lavoratori (NSDAP), fondato a Monaco nel 1920 da Adolf Hitler. Proprio a Monaco, nel novembre 1923, si verificò un nuovo tentativo di sovvertire le istituzioni democratiche con la forza, il cosiddetto putsch di Monaco.
Anche in questo caso Hitler e il generale Ludendorff, responsabili del complotto, furono arrestati e venne ristabilito l'ordine.

Il crollo dell'economia e l'inflazione contribuivano dunque ad alimentare gli estremismi e ciò rendeva ancora più urgente l'esigenza di guidare la Germania fuori dalla crisi.

Nel 1923 si assunse questo compito Gustav Stresemann, il leader del Partito Popolare Tedesco, una formazione di ispirazione democratico-liberale.

Stresemann formò un governo di grande coalizione con il Zentrum e con i socialisti.

Importante in questa prospettiva fu soprattutto la riforma monetaria che sostituì il vecchio e deprezzato marco con il Rentenmark.

Il governo cercò anche di risolvere il conflitto con la Francia e pose fine alla resistenza passiva nella Ruhr.

L'aiuto decisivo alla politica di Stresemann venne dagli Stati Uniti. L'economista americano Charles Gates Dawes elaborò un piano per il risanamento economico della Germania.

Nel 1924, dopo complesse trattative, il piano Dawes venne accettato. Si basava essenzialmente su due punti:

- la Germania non sarebbe stata in grado di pagare le riparazioni fino a quando la sua macchina produttiva industriale non fosse stata messa in condizione di riprendersi:
- si dovevano perciò fornire alla Germania capitali, sotto forma di investimenti e prestiti agevolati.

I provvedimenti presi dal governo per il risanamento economico e finanziario furono efficaci e già dal 1925 se ne constatarono i buoni risultati.

La ripresa fu ininterrotta ma dipendeva totalmente da finanziamenti stranieri. Così nel 1929, quando la depressione americana determinò la fine dei finanziamenti, la crisi ricomparve più terribile di prima.

Nel 1925 l'economia e il sistema finanziario tedeschi sembravano dunque aver superato il peggio. Nello stesso periodo, anche i rapporti internazionali della Germania si avviarono verso la stabilizzazione. Superata la spinosa questione della Ruhr, Stresemann strinse con il ministro degli Esteri francese Aristide Briand una serie di patti che normalizzarono i rapporti fra le due nazioni.
Nell'ottobre 1925, Germania e Francia giunsero così agli Accordi di Locarno, sottoscritti anche dall'Inghilterra, dall'Italia, dal Belgio e dalla Polonia. Si parlò di spirito di Locarno, intendendo cioè un nuovo periodo di distensione e di convivenza pacifica in Europa.
Fu un successo diplomatico per il governo tedesco, confermato l'anno seguente dalla decisione di ammettere la Germania nella Società delle Nazioni. Ci fu un riavvicinamento anche con la Russia bolscevica con la quale il governo tedesco firmò accordi diplomatici e commerciali.
La stabilizzazione delle relazioni internazionali fu infine sancita da un nuovo accordo in continuità con lo spirito di Locarno: il Patto Briand-Kellogg entrò in vigore il 24 luglio 1929, coinvolgendo tutte le principali nazioni del mondo.

## 📍3. La fine della repubblica di Weimar

Tra il 1925 e il 1928 la Germania attraversò un periodo di relativa stabilità e ripresa economica. Restavano, comunque, gravi problemi:

- la ripresa economica era in realtà determinata in gran parte dai finanziamenti esteri;
- il nazionalismo continuava a diffondersi nell'opinione pubblica;
- i ceti medi erano costretti a sacrifici economici non indifferenti;
- le forze politiche democratiche non riuscivano a trovare una salda intesa.

Un primo segno della fragilità della democrazia tedesca si manifestò al momento delle elezioni presidenziali, che si tennero nel febbraio del 1925, quando morì il socialdemocratico Ebert.

Alla carica di presidente venne eletto il vecchio maresciallo Paul von Hindenburg, ciò accadde perché i comunisti, invece di far convergere i loro voti sul candidato del «blocco popolare», preferirono sostenere un loro candidato.

Nel 1928 si tennero le elezioni politiche. La sinistra si rafforzò ma non conquistò una solida maggioranza.

Ne assunse la guida il socialdemocratico Hermann Müller, appoggiato da cattolici, popolari e democratici.

Nel novembre 1929 gli effetti del crollo di Wall Strett iniziarono a farsi sentire in Germania. I crediti statunitensi cessarono e l'economia tedesca precipitò rapidamente in una grave crisi.
Il governo Müller non rappresentava, agli occhi dell'opinione pubblica, un'autorità credibile, in grado di affrontare la situazione.
Sia a destra che a sinistra vi fu un processo di radicalizzazione delle opposizioni. I nazionalisti predicavano apertamente l'abbattimento della repubblica per sostituirla con un forte potere conservatore di carattere dittatoriale.
Nel 1930 il cancelliere socialdemocratico Müller fu costretto alle dimissioni. Era la rottura tra i socialdemocratici e i partiti di centro. Il governo passò in mano al cattolico Heinrich Brüning, politicamente vicino al presidente Hindenburg.

Sotto la cancelleria di Brüning, con i socialdemocratici all'opposizione e con le tensioni provocate dalle forze politiche dell'estrema destra e dell'estrema sinistra, la Repubblica di Weimar si avviò inesorabilmente verso il suo disfacimento.
Brüning puntò soprattutto a contenere le spese sociali e a risanare le finanze pubbliche. Per realizzare questa politica esautorò sempre più il Reichstag, ricorrendo sistematicamente a decreti-legge. L'articolo 48 della Costituzione, infatti, consentiva al presidente della Repubblica di emanare in casi eccezionali disegni di legge senza il concorso del Parlamento.
Sperando di rafforzare la sua maggioranza, nel 1930 Brüning decise di sciogliere il Reichstag e di indire nuove elezioni politiche. Le elezioni si svolsero in un clima di violenze e scontri fra nazisti e comunisti e i risultati furono lo specchio della radicalizzazione politica di quegli anni.

Tra il 1930 e il 1932 Brüning restò al potere grazie all'appoggio della SPD che decise di sostenere il governo per difendere le istituzioni democratiche dall'attacco dei nazisti e dei comunisti. Il cancelliere restò fedele alla sua politica di austerità e continuò, grazie all'appoggio di Hindenburg, ad approfittare dell'articolo 48, indebolendo sempre più il Parlamento.
Ma con il successo elettorale del 1930 Hitler era ormai diventato un importante interlocutore politico anche per la destra «rispettabile», non estremista. Nel marzo 1932, infatti, quando si tennero le elezioni presidenziali, fu proprio Hitler il candidato della destra contrapposto a Hindenburg. Il presidente uscente venne riconfermato grazie all'unione dei voti cattolici e socialdemocratici, ma Hitler ottenne più di 13 milioni di voti: un grande successo personale.
In un clima da guerra civile, i Tedeschi andarono alle urne due volte (luglio e novembre 1932), ma in entrambi i casi il governo non ne usci rafforzato. Si rafforzarono, invece, i nazisti che divennero il primo partito della Germania, ottenendo nelle elezioni di luglio il 37,4% dei voti.
Hitler ormai rivendicava la Cancelleria del Reich. Anche la grande industria, gli agrari e l'esercito fecero la loro scelta definitiva: tutto il loro appoggio, soprattutto economico, si concentrò sui nazisti, considerati l'unica forza capace di restaurare e imporre un potere forte. Di fronte a questa situazione, Hindenburg fini per cedere e il 30 gennaio 1933 affidò a Hitler l'incarico di formare il nuovo governo.
La Repubblica di Weimar era morta.

## 📍4. Il nazismo

Il Partito Nazionalsocialista Tedesco dei Lavoratori (NSDAP) nacque a Monaco nel 1920, nel clima di delusione e rabbia per gli esiti della pace di Versailles. Il nazismo, infatti, può essere ricondotto nel più generale panorama della destra tedesca, nazionalista e militarista, che rifiutava gli esiti della prima guerra mondiale e considerava il Trattato di Versailles un puro e semplice diktat imposto alla Germania.
Secondo questi ambienti, la sconfitta era da attribuirsi non alla forza militare dell'Intesa ma al tradimento di marxisti e pacifisti che avevano sabotato la guerra all'interno del Paese, pugnalando alle spalle l'esercito non ancora sconfitto sul campo di battaglia.

Nelle premesse ideologiche del Partito nazista era centrale il concetto di purezza della razza tedesca, il mito dell'arianesimo. La razza ariana (termine con cui si faceva riferimento al tipo etnico nordeuropeo) era intesa come unità di sangue e spirito germanico ed era la stirpe eletta. Occorreva sottomettere le razze inferiori di «sottouomini», creando una comunità purificata da ogni elemento estraneo. Il razzismo era dunque l'elemento coesivo dell'ideologia nazista. Muovendo dalle tradizioni antisemite delle Chiese cristiane, il nazismo, come altri movimenti, identificò nell'ebraismo la fonte di tutti i mali che affliggevano la Germania. Ma la difesa della purezza della razza doveva essere esercitata anche contro gli zingari, i portatori di handicap, gli omosessuali i malati di mente, tutti colpevoli di «contaminare» il popolo tedesco. Antisemitismo e razzismo si tradussero in un delirante progetto politico. Strumento di questa rigenerazione doveva essere un nuovo Reich («impero»), monolitico, autoritario, che educasse la popolazione alla disciplina e alla lotta. Confluivano nell'ideologia razzista le interpretazioni deformate di filosofi come Hegel o Nietzsche, il pensiero di teorici del razzismo europeo come Gobineau o Chamberlain, la scienza darwininana trasferita sul piano sociale.

Prima di dedicarsi all'attività politica, Adolf Hitler era un uomo dalle modeste qualità: pessimo studente, mediocre pittore, viveva di lavoretti senza prospettive. Fu la guerra a farne un piccolo eroe e a convincerlo della sua missione di rendere grande la Germania dopo l'«ingiusta sconfitta».

Nel dopoguerra iniziò a frequentare un piccolo gruppo di estrema destra all'interno del quale iniziò la sua attività politica e che lui stesso rifondò nel 1920 con il nome di Partito Nazionalsocialista Tedesco dei Lavoratori. Nel 1923, durante la sua carcerazione per il putsch di Monaco, scrisse il Mein Kampf («La mia battaglia»), base teorica del nazismo. I cardini del pensiero di Hitler erano:

- la lotta contro il liberalismo e il disprezzo per la democrazia e il parlamentarismo, ritenuti segni di decadenza morale rispetto all'unità del corpo sociale;
- la lotta al marxismo materialista: la lotta di classe era giudicata un elemento disgregatore della società e quindi il comunismo era il nemico più temibile;
- la lotta contro gli Ebrei, accusati di incarnare e controllare la finanza e lo sfruttamento economico della Germania.

La volontà unificatrice di Hitler si traduceva nella volontà di creare una società compatta e strutturata in una rigida gerarchia. Al vertice di ogni scala gerarchica, in ogni settore della società, dell'economia o della politica, doveva esservi un capo: era il Führerprinzip, «il principio del capo».

All'inizio il Partito nazista si presentava come un piccolo gruppo eversivo che appariva scarsamente credibile all'elettorato tedesco. Dopo il 1924 Hitler decise di dare al suo movimento una veste legalitaria che permettesse di conquistare maggiore consenso nel ceto medio e nella destra tradizionale. Ma non rinunciò per questo a utilizzare il braccio armato del suo partito, le SA (truppe d'assalto), per colpire le organizzazioni comuniste.
Il Partito nazista si servì inoltre di una intensa propaganda basata su concetti semplici come la nazione, la razza, la grandezza tedesca, la punizione dei nemici.
Con il preciso intento di affossare la Repubblica, nel 1931 Hitler unì tutte le forze conservatrici in un fronte reazionario, il Fronte di Harzburg. Con il volto rispettabile della destra legale riuscì quindi a conquistare anche la simpatia determinante dei grandi capitalisti tedeschi, degli agrari, dell'esercito.

## 📍5. Il terzo Reich

Hitler andò al governo il 28 gennaio 1933 e lanciò subito una dura offensiva contro gli oppositori: iniziò l'epurazione dall'amministrazione pubblica di ogni soggetto poco fidato; decine di giornali, accusati di fomentare disordini, vennero soppressi; le SA si accanirono contro i militanti politici di sinistra. Il 27 febbraio 1933 un incendio distrusse il Reichstag. Probabilmente furono gli stessi nazisti ad appiccare il fuoco al Parlamento, ma vennero additati come responsabili i comunisti: fu l'occasione che Hitler sfruttò per scatenare una spietata lotta contro di loro e per introdurre nel Paese misure eccezionali.
Hindenburg sciolse il Parlamento e vennero fissate nuove elezioni per il 5 marzo.
Il Partito nazionalsocialista ottenne il 44,9% dei consensi che, uniti ai voti dei tedesco-nazionali, garantivano a Hitler la maggioranza assoluta del Parlamento. In modo formalmente legale, con l'approvazione del Parlamento, in Germania iniziava la «nazificazione» dello Stato.

In soli sei mesi Hitler stravolse le istituzioni dello Stato democratico e edificò uno Stato totalitario. Alla prima seduta del Parlamento, il 23 marzo 1933, Hitler chiese una legge che gli assegnasse pieni poteri: nella sostanza, il Parlamento fu chiamato a esautorare se stesso dalla propria funzione, delegando al governo il potere legislativo. I comunisti erano già stati epurati; solo i 94 deputati socialdemocratici votarono contro, tutti gli altri partiti si piegarono alla volontà di Hitler.
Iniziava così la dittatura del führer.
Il 14 luglio 1933 una legge sancì l'instaurazione dello Stato totalitario a partito Unico.
I sindacati furono soppressi e sostituiti con un'organizzazione corporativa, il Fronte del lavoro, controllata dallo Stato.
Fu creata una polizia segreta, la Gestapo, controllata da Himmler, il capo delle SS. La magistratura fu posta sotto il controllo del governo, il criterio di legalità divenne la volontà del führer.
Eliminata ogni possibile opposizione esterna, Hitler affronto il problema del dissenso interno al Partito nazista. Il legame sempre più stretto che univa il führer al mondo dell'industria e della grande finanza veniva infatti contestato dalla sinistra del partito, che restava fedele all'impostazione rivoluzionaria e anticapitalistica delle origini. Questa componente del nazismo, guidata da Ernst Röhm, era rappresentata soprattutto dalle SA.
Hitler si decise infine per l'epurazione: nella notte del 30 giugno 1934 - la famosa notte dei lunghi coltelli - le SS e la Gestapo uccisero Röhm e moltissimi rappresentanti delle SA. Vi furono complessivamente oltre mille morti.
L'ultimo passaggio nella costruzione del regime avvenne il 2 agosto 1934, quando Hindenburg mori. Hitler assunse subito le funzioni di presidente che si aggiungevano a quelle di cancelliere. A partire da questo momento egli assunse ufficialmente il titolo di führer e divenne il capo assoluto del Terzo Reich.

La Chiesa cattolica, con Pio XI, firmò il 20 luglio 1933 un Concordato con lo Stato tedesco che le garantiva la libertà nel culto e nell'organizzazione ecclesiastica. I cattolici in genere non manifestarono alcuna opposizione al regime, nonostante anche il partito cattolico del Zentrum fosse stato sciolto. Solo nel 1937 di fronte alle azioni del führer che ledevano la Chiesa e i principi del cristianesimo, Pio XI condannò il governo tedesco per la violazione del Concordato, per il razzismo e per la divinizzazione dello Stato e del suo capo.
La Chiesa protestante si piegò al regime prestando giuramento al führer nel 1938.

Giunto al potere, Hitler fece dell'odio razziale il cemento del «nuovo ordine». Dapprima gli Ebrei vennero colpiti con la diffamazione, l'aggressione, la discriminazione nell'economia; poi vennero completamente esclusi dalla vita politica e sociale con appositi provvedimenti legislativi;

La persecuzione, dunque, si articolò in tre fasi distinte.

- Dal 1933 al 1935 i nazisti scatenarono una violenta propaganda per diffondere tra i Tedeschi l'ostilità verso la comunità ebraica.

Il 7 aprile 1933 il governo emanò un decreto che imponeva il licenziamento di tutti i dipendenti della pubblica amministrazione «non ariani». Era da considerarsi non ariano chiunque discendesse da genitori o nonni (anche uno solo) non ariani.

- Nel 1935 la persecuzione venne legalizzata. Il 15 settembre il governo nazista emanò le leggi di Norimberga che, su basi biologico-razziali, escludevano gli Ebrei dalla «Comunità nazionale». Essi perdevano quindi la cittadinanza tedesca e i diritti politici e civili, La vita per gli Ebrei divenne impossibile; molti emigrarono, dirigendosi soprattutto in Palestina o negli Stati Uniti. Il 7 novembre 1938 un ebreo polacco uccise un diplomatico tedesco a Parigi. L'assassinio scatenò in tutta la Germania un vero e proprio pogrom, ossia una serie di violenze su larga scala contro la popolazione ebraica. Tra il 9 e il 10 novembre 1938, la cosiddetta notte dei cristalli, vennero infrante le vetrine dei negozi degli Ebrei, distrutte le sinagoghe, incendiate le abitazioni, arrestati, feriti e uccisi Ebrei in tutta la Germania.
- La decisione definitiva di procedere allo sterminio della popolazione ebraica venne presa da Hitler quando la seconda guerra mondiale era già cominciata, nel 1941. Lo sterminio si articolò in due grandi operazioni. La prima iniziò con l'invasione dell'URSS del giugno del 1941. Vennero organizzate delle piccole unità di SS e polizia che seguirono l'avanzata nei territori sovietici e che avevano il compito di uccidere sul posto tutta la popolazione ebraica. Nel corso del 1942, invece, si avviò la deportazione nei lager degli Ebrei dell'Europa occidentale, centrale e sud-orientale. Era l'attuazione della cosiddetta «soluzione finale della questione ebraica».

circa 6 milioni sarebbero morti in campi di sterminio: ad Auschwitz, Treblinka, Mauthausen, Buchenwald, per citare solo i più noti.

La società che Hitler aveva in mente era una società senza gli Ebrei e con gli Slavi ridotti in schiavitù. Una società in cui non ci fosse dissenso politico, senza criminali, malati di mente, persone con la Sindrome di Down, omosessuali, zingari, testimoni di Geova: tutti soggetti che vennero rinchiusi nei lager.
A conferma dell'ordinarietà dello sterminio nel Terzo Reich è significativo notare che il primo campo di concentramento, quello di Dachau, fu istituito poche settimane dopo l'ascesa al potere di Hitler, nel 1933.
Nel 1933 venne emanata la prima legge demografica che introdusse la sterilizzazione «eugenetica», cioè il progetto scientifico di migliorare la razza consentendo le riproduzioni solo ai soggetti portatori di caratteri geneticamente favorevoli.

Negli anni del regime nazista la politica repressiva fu costantemente accompagnata da una vasta opera di propaganda dell'ideologia nazionalsocialista. L'apparato propagandistico venne affidato a Joseph Goebbels, il ministro per l'Educazione e la Propaganda. La ricerca del consenso si fondava sulla diffusione del mito della razza pura, dell'uomo bello e sano, legato alla terra in una società di contadini guerrieri.
La manipolazione delle coscienze fu costruita con i più moderni strumenti a disposizione: la radio, il cinema, le adunate oceaniche.

## 📍6. Economia e società

La crisi economica e la lotta alla disoccupazione furono i principali problemi che il Partito nazionalsocialista dovette affrontare appena giunto al potere.
Nel settore agricolo, per esempio, fin dal 1933, la produzione, il mercato e il consumo vennero sottoposti al controllo della Corporazione alimentare del Reich. In questo settore, l'obiettivo era il raggiungimento dell'autosufficienza alimentare: la Germania doveva produrre tutto il necessario senza ricorrere a importazioni da altri Paesi.

Gli sforzi maggiori del regime furono rivolti a risollevare il settore industriale. Di qui infatti giunse la ripresa economica, dovuta fondamentalmente alla politica di riarmo.
Dal 1935 fu introdotta nuovamente la leva obbligatoria e dal 1936 le commesse militari garantirono un forte incremento della produzione industriale. In questo anno Hitler iniziò a preparare il Paese alla guerra con iniziative di largo respiro: fu varato il «piano quadriennale» per l'economia; lo Stato avviò imponenti lavori pubblici (autostrade, strade, canali) che consentirono di riassorbire la disoccupazione, fino a raggiungere la piena occupazione nel 1938.

Il successo della politica economica del Reich dipese in parte dal totale controllo sui lavoratori e sulle loro organizzazioni. I sindacati furono eliminati e sostituiti con il Fronte tedesco del lavoro, un'organizzazione corporativa che avrebbe dovuto conciliare gli interessI dei lavoratori con quelli degli imprenditori. Tra il 1934 e 1935 il regime varò leggi che:

- impedirono la libertà di scelta del posto di lavoro: il lavoratore così poteva essere assegnato dalle autorità a una fabbrica e a una determinata funzione senza che potesse rifiutare: tutta la vita economica venne militarizzata;
- istituirono il servizio di lavoro obbligatorio per i giovani tra i 18 e 125 anni, rendendo disponibile una gran quantità di manodopera a basso costo che poteva essere utilizzata dalle autorità per lavori di pubblico interesse.

Lo Stato esercitò il suo controllo anche sulla società e sulla famiglia. La difesa della famiglia era uno dei temi più cari al regime, in funzione della difesa della razza e del popolo.

Furono prese, quindi, iniziative a sostegno della natalità e delle giovani coppie.

L'obiettivo della politica sociale era l'educazione nazionalsocialista delle masse fondata sull'istruzione militare e sulla gestione del tempo libero.

## 📍7. Gli anni Trenta: nazionalismo, autoritarismo e dittature. La politica estera di Hitler.

Dal 1933, il successo di Hitler apri la strada alla diffusione di movimenti di estrema destra ispirati al nazismo. In Ungheria fin dal 1932 si era affermato il movimento filonazista delle Croci frecciate, un'organizzazione militare estremamente spietata. In Romania si impose un analogo movimento fascista e antisemita, fondato nel 1926 e chiamato Guardia di ferro. Nei Paesi dell'Est europeo, in cui già si erano insediati dei governi autoritari, negli anni Trenta si assistette a una svolta propriamente dittatoriale di stampo fascista.
Dal 1933, il successo di Hitler apri la strada alla diffusione di movimenti di estrema destra ispirati al nazismo. In Ungheria fin dal 1932 si era affermato il movimento filonazista delle Croci frecciate, un'organizzazione militare estremamente spietata. In Romania si impose un analogo movimento fascista e antisemita, fondato nel 1926 e chiamato Guardia di ferro. Nei Paesi dell'Est europeo, in cui già si erano insediati dei governi autoritari, negli anni Trenta si assistette a una svolta propriamente dittatoriale di stampo fascista.
L'espansione delle dittature fasciste riguardò infine l'area slava e dei Balcani: regimi nazionalisti e autoritari si instaurarono anche in Bulgaria, in Albania, in Iugoslavia, in Grecia. Il modello fascista fu imitato in Polonia, nei Paesi baltici e in Finlandia. Anche nella penisola iberica, una zona ancora arretrata nello sviluppo economico, la crisi degli anni Trenta sfociò in una dittatura militare, con António de Oliveira Salazar in Portogallo e Francisco Franco in Spagna.

Anche in Asia i trattati di pace che chiusero la prima guerra mondiale concorsero a creare instabilità: la Conferenza di Parigi non aveva soddisfatto né il Giappone né la Cina. E anche qui la crisi del 1929 esasperò la situazione, con gravi conseguenze sia all'interno dei Paesi sia nei rapporti tra gli Stati. La partecipazione alla guerra a fianco dell'Intesa aveva accresciuto il prestigio internazionale del Giappone, che aveva guadagnato il controllo su alcuni territori strategici. La guerra aveva favorito anche la crescita economica, stimolando la produzione dell'industria pesante e navale, ma tutto questo venne meno nel dopoguerra, con la ripresa della concorrenza occidentale sui mercati internazionali. La crisi del '29, come ovunque, determinò una contrazione del commercio internazionale e accentuò le difficoltà economiche. Il governo ritenne che la soluzione fosse in una politica espansionistica ai danni della Cina, trovando in questo progetto l'appoggio dei grandi gruppi industriali e delle gerarchie militari.
Si rafforzarono quindi i gruppi politici di matrice nazionalista e fascista e si affermò un governo autoritario, sotto la tutela dell'imperatore Hirohito.
In Cina, per far fronte all'espansione nipponica, si rafforzò il fronte nazionalista che doveva però anche combattere l'opposizione interna del Partito comunista di Mao Zedong. Nel 1936 comunque tutte le forze politiche cinesi si unirono per respingere l'occupazione giapponese.

Dopo il 1929 la crisi economica aveva piegato la Germania e affossato la democrazia. L'obiettivo fondamentale per il governo nazista era assorbire la disoccupazione e rilanciare l'economia della Germania. Il progetto espansionistico di Hitler, oltre gli aspetti ideologici e politici, era anche funzionale a una nuova crescita economica che gli avrebbe garantito il consenso popolare.
Avviò quindi il riarmo e indirizzò l'intera economia tedesca alla produzione bellica. Nel 1935 inoltre, reintrodusse la coscrizione obbligatoria e costruì una flotta navale.

La politica espansionistica del nazismo mise subito in discussione l'equilibrio internazionale stabilito dai trattati di Versailles. La prima mossa, nel 1934, fu il tentativo di annettere l'Austria, per inglobarla nel disegno della Grande Germania, ma si concluse con l'assassinio del presidente Dollfuss e con la forte reazione di Londra, Parigi e soprattutto dell'Italia che schierò addirittura le proprie truppe ai confini.
La continua violazione dei trattati internazionali da parte della Germania nazista venne discussa alla Conferenza di Stresa dai rappresentanti della Francia, della Gran Bretagna e dell'Italia che però si limitarono a una prudente e formale condanna.
I generici impegni per la pace, senza prendere alcun provvedimento concreto verso la Germania, lasciarono di fatto Hitler libero di procedere con nuove azioni. Nel 1936 infatti Hitler mosse l'esercito tedesco per occupare la Renania, che secondo il Trattato di Versailles doveva restare smilitarizzata.
Il successo di questa iniziativa rafforzò ulteriormente il consenso al governo di Hitler che continuò, pressoché indisturbato, nella sua politica aggressiva e tra l'indifferenza delle democrazie europee e la debolezza della Società delle Nazioni.
Consapevole dell'impotenza della Società delle Nazioni e dell'arrendevolezza della Gran Bretagna, nel 1936 Hitler trovò un alleato nell'Italia fascista, che nel 1935 aveva occupato con successo l'Etiopia. Firmò quindi con Mussolini un accordo, l'Asse Roma-Berlino, in funzione antibolscevica e per il comune interesse sui Balcani.

L'Unione Sovietica, preoccupata dalla politica estera della Germania e del Giappone, cercò di difendersi entrando nella Società delle Nazioni e stringendo un patto di alleanza con la Francia.
Stalin sostenne quindi una nuova linea politica: si trattava di combattere i fascismi in un unico fronte, alleandosi con i partiti democratici e costituendo i cosiddetti «Fronti popolari» nei diversi Paesi.
In Francia e in Spagna la coalizione delle forze antifasciste, dai cattolici ai socialisti, ottenne la vittoria elettorale nel 1936, ma in politica estera neppure questa scelta servi ad arginare l'avanzare del nazismo in Europa. La Francia infatti, come la Gran Bretagna, continuò a tentare di contenere le pretese tedesche, puntando a mantenere la pace a ogni costo (appeasement), senza avere la forza di adottare una chiara e autonoma linea antifascista.
In Spagna invece la destra militarista non accettò la svolta democratica e diede inizio à una lunga guerra civile.

## 📍8. La guerra civile spagnola

Agli inizi del Novecento, le condizioni economiche e sociali della Spagna erano di estrema arretratezza. L'economia era dominata da un'agricoltura basata in gran parte sul latifondo.
La Chiesa cattolica, inoltre, aveva un enorme potere culturale e controllava in gran parte l'istruzione.

Nel 1923 re Alfonso XIII di Borbone, di fronte alla crisi sociale, preferì esautorare il Parlamento e favori la dittatura militare di Miguel Primo de Rivera. Il governo di Primo de Rivera si ispirava al fascismo italiano e rimase in carica fino al 1930. Nell'aprile del 1931 si tennero le elezioni amministrative: i partiti repubblicani ebbero un clamoroso successo. Il re scelse la via dell'esilio e fu proclamata la repubblica.
Anche in Spagna, dunque, si profilava un regime dittatoriale: in questo contesto le forze della sinistra riuscirono a superare le tradizionali divisioni e unirsi in un Fronte unico «per sbarrare la strada al fascismo». Seguendo le direttive di Stalin, anche i comunisti entrarono nella coalizione del Fronte popolare con i liberali, i democratici, i socialisti, gli anarchici, gli autonomisti.
Nel febbraio del 1936 il Fronte popolare vinse le elezioni e diede vita a un difficile governo liberaldemocratico moderato, con l'appoggio esterno dei socialisti. La vittoria delle sinistre aveva suscitato molte aspettative di riforme sociali, ostacolate però dalla componente più moderata della coalizione.
La tensione sociale cresceva e sembrava sfociare in una rivoluzione sociale.
Di fronte a tale timore la destra reazionaria e militare rispose con un colpo di Stato: nel luglio 1936 alcuni reparti delle truppe stanziate nel Marocco spagnolo guidate dal generale Francisco Franco (1892-1975) e aiutate dalla aviazione italiana e tedesca, sbarcarono nel Sud della Spagna. Iniziò così la guerra civile: contro l'esercito della Repubblica si schierarono varie organizzazioni filofasciste che si riunirono nella Falange nazionalista, sotto la guida del caudillo Francisco Franco.

La guerra civile in Spagna si configurò subito come una questione internazionale. Consapevole della propria debolezza militare, il governo repubblicano chiese aiuto alla Francia, guidata nel 1936 da un governo socialista.
Per evitare polemiche con il governo inglese, la Francia negò l'intervento di truppe in aiuto ai repubblicani spagnoli. Francia e Inghilterra decisero quindi di promuovere un patto internazionale di non intervento nella guerra spagnola, sottoscritto anche dall'Italia e dalla Germania che tuttavia non lo rispettarono. Hitler e Mussolini infatti inviarono al caudillo spagnolo Francisco Franco uomini e mezzi bellici che rafforzarono la capacità militare della Falange nazionalista.
Solo l'Unione Sovietica, attraverso il Comintern, inviò aiuti militari ai repubblicani spagnoli: furono organizzate le Brigate internazionali, reparti di volontari antifascisti provenienti da tutti i Paesi. Migliaia di giovani antifascisti, molto motivati politicamente, partirono per la Spagna in nome della libertà democratica e per combattere la dittatura.
Ad accrescere la debolezza dell'esercito repubblicano concorsero anche le divisioni interne alla sinistra: i contrasti politici fra comunisti filosovietici, socialisti e anarchici sfociarono addirittura nello scontro armato.
Più unito e dotato di mezzi migliori, l'esercito di Franco ottenne così la vittoria: tra gennaio e marzo del 1939 occupò Barcellona e Madrid. La democrazia era finita anche in Spagna. La dittatura di Franco sarebbe durata fino al 1975.

## 📍9. Verso la guerra

Durante gli ultimi due anni che precedono la guerra l'obiettivo di Hitler era ormai chiaro anche se le potenze europee sottovalutarono il pericolo e dimostrarono debolezza di fronte all'aggressività della Germania.
Il tentativo di annessione (Anschluss) dell'Austria fallito nel 1934, riuscì nel marzo del 1938 con una occupazione militare preceduta da una vasta campagna filonazista. Subito dopo Hitler si diresse verso la Cecoslovacchia occupando la regione di confine dei Sudeti, dove viveva in maggioranza popolazione di lingua tedesca e dove era stanziata buona parte del sistema difensivo cecoslovacco.
In base al principio della naturale appartenenza al «mondo tedesco», i nazionalisti rivendicavano la ricongiunzione di quell'area alla Germania, ma il governo ceco non era disposto a cedere.
Per risolvere la questione dei Sudeti, il 29 e 30 settembre 1938, Mussolini, Hitler, il premier britannico Chamberlain e il Primo ministro francese Daladier si incontrarono nella Conferenza di Monaco. In questa occasione fu scritta la pagina più vergognosa del cedimento delle democrazie occidentali alla politica nazista. Mussolini, già legato alla Germania con l'Asse Roma-Berlino, aveva espresso parere favorevole al progetto di annessione di Hitler. Francia e Inghilterra, nell'intento di scongiurare il conflitto, non fecero che accettare la situazione di fatto, dietro la promessa che fosse garantita l'indipendenza del resto della Cecoslovacchia.

Nel marzo 1939, non rispettando gli accordi appena stipulati, i nazisti completarono lo smembramento della Cecoslovacchia: la Boemia e la Moravia furono occupate e sottoposte a protettorato tedesco.
Ormai la politica di aggressione all'Est europeo era iniziata e il 21 marzo 1939, infatti, la Germania chiese alla Polonia la città di Danzica e la disponibilità della striscia di terra che univa quella città alla Polonia (il corridoio polacco).
Nel 1939, anche l'Italia fascista si allineò alla politica aggressiva della Germania: in aprile le truppe italiane occuparono l'Albania che venne annessa all'impero; contemporaneamente Mussolini rivendico Tunisi, Gibuti, Nizza, la Savoia, la Corsica.
Il rapporto di amicizia fra Italia e Germania venne rafforzato con un'alleanza militare: il 22 maggio 1939 venne firmato il Patto d'acciaio che sanciva l'impegno a fornirsi reciproco aiuto in caso di guerra, sia offensiva che difensiva.

Nella prospettiva di iniziare la guerra, Hitler però voleva garantirsi la neutralità dell'Unione Sovietica. In caso di attacco alla Polonia, infatti, l'intervento di Stalin sul fronte orientale poteva rivelarsi pericoloso. Il cinismo politico prevalse sull'ideologia: nonostante l'odio feroce, i due dittatori strinsero un accordo diplomatico. Tra lo sbigottimento degli antifascisti europei, il 23 agosto 1939 i ministri degli Esteri dei due Paesi, von Ribbentrop e Molotov, firmarono un patto di non aggressione della durata di dieci anni.
A questo patto ufficiale si univa un protocollo segreto che precisava:

- le modalità per la spartizione della Polonia;
- le sfere di influenza di Germania e URSS nella regione baltica: la frontiera settentrionale della Lituania era il limite della zona assegnata alla Germania; Finlandia, Estonia e Lettonia erano indicate come aree di espansione per l'URSS;
all'influenza sovietica era assegnata anche la Bessarabia, nell'Europa sudorientale.
Con il Patto Molotov-Ribbentrop tutto era pronto per l'invasione della Polonia (1 settembre 1939) che avrebbe segnato l'inizio della seconda guerra mondiale.

---

# La Seconda guerra mondiale

<aside>
💡 **L’1 settembre 1939** la Germania attaccò la Polonia e la costrinse alla resa nel giro di sole tre settimane.

</aside>

Il **3 settembre** la Francia e la Gran Bretagna dichiararono guerra alla Germania.

Il **17 settembre** anche l’Unione Sovietica, rivendicando i diritti derivanti dal Patto Molotov - Ribebentrop iniziò l’occupazione della parte orientale della Polonia.

Nei mesi successivi sul fronte occidenatale le operazioni militari attraversarono una fase di stallo.

---

Nella fase di stallo i Tedeschi ebbero modo di riorganizzare le proprie forze e in primavera ripresero le operazioni.

Il **9 aprile 1940** la Germani attaccò la *Danimarca* e la *Norvegia*.

La prima venne subito occupata senza difficoltà, la seconda si arrese due mesi dopo.

> La Germania sembrava davvero in grado di realizzare una **guerra lampo.**
> 

D’altra parte era l0uinca strategia che offrisse possibilità di successo alla Germania.

---

Mentre l’esercito tedesco stava ancora completando l’invasione della Norvegia, il **10 maggio 1940** Hitler decise di attaccare a sorpresa la *Francia.*

L’esercito tedesco occupò rapidamente il Nord della Francia e raggiunse *Parigi* il 14 giugno.

Per la Francia ora si aprivano due strade: o continuare il conflitto con la Germania o scendere a patti con essa.

Precalse la seconda ipotesi.

L’armistizio tra Francia e Germania fu concluso il **22 giugno 1940** e il territorio francese venne diviso in due parti:

- La francia centro - nord sotto l’occupazione tedesca;
- La Francia centro - sud istituì un **governo collaborazionista** con sede a V**ichy** e guidato da Pétain.

Il generale **Charles de Gaulle**, rifugiatosi a Londra, lanciò attraverso la radio inglese un invito ai Francesi affichè resistessero agli invasori.

---

Nel 1939 l’Italia si trovò in una posizione difficile.

Mussolini si era impegnato con il ***Patto d’acciaio*** ad aiutare la Germania in caso di guerra.

Però non era pronta ad affrontare un conflitto poichè la guerra di Etiopia e quella di Spagna avevano gravemente compromesso sia le finanze che l’esercito.

I successi della Germania e soprattutto il crollo della Francia indussero Mussolini a pensare che la guerra si sarebbe risolta in fretta a vantaggio dei Tedeschi e che per l’Italia sarebbe stato uno smacco non partecipare ai profitti della vittoria.

<aside>
💡 Il **10 giugno 1940** l’Italia entrò in guerra contro la Francia e l’Inghilterra.

</aside>

---

Dopo la sconfitta della Francia, solo la Gran Bretagna poteva continuare la guerra contro la Germania.

Nel **maggio 1940** divenne Primo ministro **Winston Churchill,** che aveva disapprovato la politica di *appeasement*.

Hitler cercò di aprire le trattative con la Gran Bretagna, mostrandosi disposto a firmare la pace purchè gli venissero riconosciute le conquiste.

Ma nessuno era d’accorrdo.

Tra **agosto** e **settembre** i Tedeschi tentarono la mossa decisiva: lo sbarco sulle coste britanniche.

Per due mesi la **RAF** inglese e l’aviazione Tedesca si scontrarono nella **“battaglia d’Inghilterra**”.

Ma la RAF riuscì a infliggere ai Tedeschi pesanti perdite.

Perciò il **17 settembre** Hitler dovette rinunciare all’invasione della Gran Bretagna.

Erano stati rafforzati anche i legami con il **Giappone**, giungendo alla firma del **Patto tripartito (**Germania, Italia, Giappone).

---

## 📍2. 1941: la guerra mondiale.

Nella **primavera** del **1941** la Germania fu costretta a intervenire a sostegno dell’Italia, che stava rischiando una pericolosa disfatta militare:

- nel **Nord Africa**
- nei **Balcani.**

L’Italia rinunciò così a qualsiasi illusione di poter svolgere un ruolo autonomo nella guerra.

Hitler aveva sconfitto tutti i rivali in Europa e poteva puntare all’estensione delle conquiste del Reich.

---

Il progetto di hitler era quello di conquistare lo “spazio vitale” per la Germania occupando le regioni dell’Est europeo.

In questa prospettiva era evidente che il patto tra URSS e Germania per la sprtizione della Polonia aveva un carattere solo temporaneo.

I motivi che inducevano Hitler alla conquista dell’Unione Sovietica erano molteplici:

- i popoli slavi erano ritenuti inferiori;
- L’Unione Sovietica era la patria del comunismo;
- La Russia era un territorio ricchissimo di materie prime.

Il **22 giugno 1941** la Germania invase la Russia seguendo il *piano Barbarossa.*

All’impresa partecipò anche l’Italia inviando il CSIR (Corpo Spedizione Italiano in Russia).

Alla fine dell’autunno l’avanzata si arrestò, anche se non definitivamente, Col sopraggiungere del lungo e freddo inverno russo, si passò anche qui dalla “guerra lampo” alla guerra di logoramento.

---

Nel corso degli anni Trenta, il Giappone aveva intrapreso a spese della Cina una aggresiva politica espansionistica.

Le conquiste misero il Giappone in contrasto con la Gran Bretagna, la Francia e soprattutto gli Stati Uniti.

Nel quadro di questa politica espansionistica, nel **luglio 1941**, approfittando della situazione di debolezza della Francia, i Giapponesi occuparono l’indocina francese.

Il **7 dicembre 1941** i Giapponesi attaccarono, senza formale dichiarazione di guerra, la flotta degli Stati Uniti ancorata a *Pearl Harbor* (FILM).

Il giorno dopo, l’**8 dicembre 1941,** gli Stati Uniti e la Gran Bretaga dichiararono guerra al Giappone, che veniva subito sostenuto dalla Germania e dall’Italia.

---

Negli anni Trenta gli Stati Uniti avevano proseguito la propria politica di isolamento intrapresa alla fine della prima guerra mondiale e accentuata in seguito alla crisi del 1929.

Il presidente **Roosvelt** si impegnò invece in senso opposto.

L’avvicinamento fra la Gran Bretagna e gli USA si concretizzò nella redazione della **Carta Atlantica (1941).**

L’attaccio giapponese di Pearl Harbor indusse gli Stati uniti ad abbandonare definitivamente l’isolazionismo.

---

## 📍3. Il dominio nazista in Europa.

Nel **1942** il dominio della Germania nazista in Europa rraggiunse la sua massima espansione.

Il nazismo intendeva costruire una **“nuova Europa”** basata sulla supremazia della Germania.

I popoli slavi dovevano semplicemente fornire la manodopera e le risorse necessarie a sostenere l’economia del Reich. Per questo il dominio nazista fu particolarmente brutale in Polonia e in Unione Sovietica.

Se gli Slavi dovevano essere tenuti in condizione di schiavità, gli Ebrei andavano completamente sterminati. Perciò i nazisti crearono i **lager**, cioè campi di concentramento e di sterminio.

In Germani gli Ebrei erano già stati sottoposti a discriminazioni e persecuzioni, poi, nel 1938, dopo la “notte dei cristalli” iniziò la deportazione.

Nel **1942** Hitler decise di mettere in atto la **“soluzione finale**”, cioè lo sterminio organizzato di tutti gli Ebrei d’Europa.

Si realizzò così l’Olocausto, oppure, come preferiscono dire gli Ebrei stessi, la *Shoah.*

Si tratta di un vero e proprio **genocidio.**

Questo termine venne usato per la prima volta al processo di Norimberga, in cui i capi nazisti vennero condannati.

---

In tutti i Paesi occupati dall’esercito nazista si sviluppavano movimenti di opposizione e di liberazione.

La **resistenza** al nazismo ebbe modalità, tempi ed esiti molto diversi.

In **Francia** la resistenza venne guidata da *de Gaulle.*

In **Iugoslavia** da *Tito.*

Nella stessa Germania una parte dell’esercito si oppose al regime, arrivando a organizzare un **attentato a Hitler.**

In **Italia** la Resistenza fu un fenomeno complesso al cui interno si manifestarono profondi contrasti politici.

---

Fenomeno opposto alla resistenza fu il **collaborazionismo**.

In tutti i Paesi ci furono persone o gruppi che appoggiarono gli invasori, in modo diverso e secondo le proprie possibilità.

il primo clamoroso esempio al riguardo fu quello del norvegese **Vidkun Quisling.**

---

## 📍4. 1942-43: la svolta.

L’entrata in guerra degli Stati Uniti determinò le prime sconfitte per gli eserciti del Patto Tripartito.

Tra il l1942-43 il l’andamento del conflitto subì una svolta decisiva a vantaggio degli Alleati, cioè degli Anglo - Americani.

Anche nell’area dell’Atlantico si manifestò la superiorità degli Alleati.

Gli Anglo Americani riuscirono a difendere efficacemente la propria flotta e a spezzare l’accerchiamento die Tedeschi.

Dopo aver vinto i nazisti nella “battaglia dell’Atlantico”, gli Alleati volsero il loro impegno in Africa.

---

Sul fronte orientale, lo scontro tra Russi e Tedeschi diventava molto più lungo e difficile.

Nel **giugno 1942** la Germania lanciò un’offensiva con l’oviettivo di conquistare le regioni del Caucaso, ricche di petrolio.

Le forze dell’Asse riportarono alcuni iniziali successi, ma poi i Sovietici passarono al contrattacco.

Nel **luglio 1942** iniziò la **battaglia di Stalingrado.**

La città venne assediata per sette mesi, Hitler ordinò la resistenza a oltranza, ma nel **febbraio 1943** i Sovietici costrinsero i Tedeschi alla resa.

A Stalingrado i Tedeschi subirono la più grande sconfitta, una sconfitta che mostrò chiaramente come le sorti del conflitto si fossero ormai capovolte.

---

Dopo la vittoria in Africa, gli Anglo-Americani avevano assunto il controllo del Mediterraneo e poterono rivolgersi all’Italia.

Il **10 luglio 1943** gli Alleati sbaracono in *Sicilia*.

Il **23 luglio** occuparono Palermo e nel giro di un mese si impadronirono di tutta l’isola.

Gli Alleati vennero accolti come liberatori.

La guerra voluta da Mussolini aveva portato alla popolazione sofferenze enormi.

---

La caduta del fascismo non fu determinata però dalle proteste popolari né dalle forze politiche antifasciste.

Mussolini fu esautorata dalla monarchia, che intedeva a quel punto dissociarsi dalla prevedibile disfatta del regime.

Nella notte tra il **24 e il 25 luglio 1943** il duce venne messo in minoranza dal Gran Consiglio del fascismo.

Il re Vittorio Emanuele III esonerò Mussolini dalla carica di Primo Ministro e lo fece arrestare.

L’incarico di formare un nuovo governo venne affidato a **Pietro Badoglio.**

Badoglio prese contatto con gli Alleati e il **3 settembre 1943** a Cassibile firmò l’**armistizio** che fu reso **pubblico** solo l’**8 settembre**.

Il **9 settembre** gli Alleati sbarcarono a Salerno, la loro avanzata venne fermata dai Tedeschi che si attestarono lungo la *linea Gustav**.***

Il **12 settembre** i tedeschi liberarono Mussolini, pochi giorni dopo il duce costituì al Nord un uovo stato fascista sottomesso alla Germania, la **Repubblica Sociale Italiana (RSI)** con capitale a Salò.

---

## 📍5. 1944-45: la vittoria degli Alleati.

Nel **1944** gli eserciti anglo - americani proseguirono la loro avanzata.

In Italia gli Alleati sfondarono la linea Gustav e liberarono Roma.

I tedeschi furono costretti a ritirarsi verso nord e si attestarono lungo la linea gotica.

Dopoa ver liberato tutto il territorio russo, l’Armata Rossa si spinse verso l’Europa centrale puntando sulla Germania.

---

Il **2944** per gli Alleati fu l’anno dell’apertura in Europa di un **“secondo fronte**”.

I tre alleati scelsero di attuare uno **sbarco in Normandia**, nel Nord della Francia.

Nella notte tra il **5 e il 6 giugno,** sotto il comando del generale **Eisenhower** un esercito iniziò a invadere la Normandia.

I Tedeschi resistettero accanitamente.

Ma dopo due mesi di combattimenti gli Alleati riuscirono a sfondare le difese.

Il **26 agosto 1944** gli Alleati e il generale de Gaulle entravano a Parigi.

---

il **25 aprile 1945** le avanguardie americane si incontrarono con le avanguardie sovietiche.

Negli stessi giorni l’Italia veniva liberata e i Tedeschi iniziavano la ritirata.

Il **30 aprile** Hitler si suicidò.

Il suo successore, **Karl Donitz**, firmò **il 7 maggio 1945** la **resa senza condizinoi.**

---

Nella primavera del 1945 la guerra era ormai finita in Europa, ma continuava nell’Oceano pacifico.

I Giapponesi resistevano accanitamente affidandosi anche ai *kamikaze*.

Il Giappone era ormai militarmente sconfitto, la resa appariva inevitabile ma no nimminente,

Il presidente americano Roosvelt morì e gli succedette **Harry Truman**, che decise di piegare definitivamente il Giappone usando la **bomba atomica.**

Il **6 agosto 1945** una bomba rase quasi completamente al suolo la città di **Hiroshima**.

Il **9 agosto 1945** fu la volta di **Nagasaki.**

Al Giappone non restava che chiedere la **resa senza condizioni,** che venne firmata il **2 settembre 1945.**

---

## 📍6. Dalla guerra totale ai progetti di pace.

Con la prima guerra mondiale si affermò un nuovo tipo di conflitto: la **guerra totale**.

Con il secondo conflitto mondiale l’umanità sperimentò l’esasperazione di tale motivo.

Fu una **guerra tecnologica**: vennero utilizzato strumenti nuovi e nuove armi e tecniche d’attacco sempre più distruttive.

---

Le potenze alleate raggiunsero progressivamente l’accordo di massima che avrebbe poi caratterizzato le soluzioni post-belliche.

Il primo passo al riguardo fu la firma da parte di *Roosvelt e Churchill*, nell’**agosto del 1941**, della **Carta Atlantica**, che san la solidarietà ideale e politica tra gli Stati Uniti e la Gran Bretagna.

---

**Conferenza di Teheran**

Verso la fine del 1943 apparve chiaro che la guerra era giunta a una svolta favorevole per gli Alleati.

Nel **novembre-dicembre 1943** si svolse a **Teheran** un importante incontro a cui parteciparono i “tre grandi” (Roosvelt, Churchill, Stalin).

Concordarono l’apertura di un nuovo fronte in Francia, che sarebbe poi diventato lo sbarco in Normandia.

---

**Conferenza di Yalta**

I “tre grandi” si incontrarono a Yalta nel **febbraio 1945**.

in questa occasione l’URSS si impegnò a entrare in guerra contro il Giappone.

La **Germania** venne divisa in **quattro zone di occupazione** controllate da **Stati Uniti, Unione Sovietica, Gran Bretagna e Francia.**

Vennero prese anche importanti decisioni riguardanti lo scioglimento dell’esercito tedesco e la “denazificazione” del Paese e il pagamento da parte della Germania dei danni di guerra.

---

**La conferenza di Potsdam**

Roosvelt, già malato e prossimo alla morte, venne sostituito da *Harry Truman*, che assunse un atteggiamento ben più rigido alla conferenza di Potsdam, nel **luglio-agosto 1945.**

Il disaccordo tra Stati Uniti e Unione Sovietica determinò un certo stallo nelle trattative.

Venne comunque deciso di non procedere, per il momento, allo smembramento della Germania.

Era l’inizio dell’esplodere di quella rivalità internazionale che avrebbe portato le due superpotenze alla “guerra fredda”.

---

## 📍7. La guerra e la Resistenza in Italia dal 1943 al 1945.

L’**8 settembre 1943** fu dato l’annuncio dell’armistizio che l’Italia aveva concluso con gli Anglo Americani, ma nessuno si preoccupò di chiarire come i soldati dovessero comportarsi nei confronti dei vecchi alleati tedeschi.

I Tedeschi catturarono migliaia di militari, inviandoli nei campi di prigionia in Germania.

Alla fine di settembre il Paese era diviso in due:

- Centro Nord governato dalla **Repubblica di Salò**, fondata da Mussolini.
- Centro Sud sotto il **Regno d’Italia**, appoggiato dagli Alleati.

Il Regno d’Italia il **13 settembre** dichiarò guerra alla Germania, da questo nacque la Resistenza.

Alcuni italiano, specie tra i giovani, giudicarono un “tradimento” il voltafaccia della monarchia e la rottura dell’alleanza con i Tedeschi e si schierarono dalla parte di Mussolini.

Altri scelsero di schierarsi contro i fascisti e contro i Tedeschi, divenendo “partigiani”.

Così anche in Italia iniziò la **Resistenza.**

---

Fra il **settembre e dicembre 1943** diverse bande partigiane entrarono in azione al Centro e al Nord.

I partigiani agivano con sabotaggi, azioni di disturbo, attentati a cui i Tedeschi spesso risposero con feroci rappresaglie.

---

Si costituì a Roma il **Comitato di Liberazione Nazionale (CLN)** che cercò soprattutto di coordinare l’azione dei partigiani.

ADerirono al CLN il Partito ocmunista e quello socialista, il Partito liberale, il Partito d’Azione, la Democrazia Cristiana e la Democrazia del Lavoro.

Queste forze politiche era accomunate dal’idele antifascista ma erano molto eterogenee per altri aspetti.

---

Gli esponenti del CLN erano divisi anche sulla questione *istituzionale*, cioè sulla sorte della monarchia italiana.

La situazione si sblocco nel **marzo 1944**, quando il segretario del partito comunista **Palmiro Togliatti** dichiarò in un celebre discorso tenuto a **Salerno** che per il momento era necessario unire tutte le forze per librerare l’Italia dai nazisti.

---

Nel **giugno 1944** Roma venne liberata dagli Alleati.

Badoglio si dimise e venne affidato a **Ivanoe Bonomi** l’incarico di formare un nuovo governo.

La repubblica di Salò inasprì la persecuzione nei confronti degli **Ebrei**, il **30 novembre 1943** venne ordinato che tutti gli Ebrei fossero internati in campi di concentramento nazionali.

---

Con la caduta del fascismo, si aprì il periodo più buio per gli Ebrei italiani.

Gli ebrei italiani deportati furono più di ottomila, e solo mille fecero ritorno.

---

Nel **1944** il numero dei partigiani aumentò e la loro azione divenne particolarmente incisiva.

Alcune città, come **Firenze**, vennero liberate senza l’intervento Anglo Americano.

→ Episodio delle **fosse ardeatine**.

---

La Resistenza visse il suo momento più difficile fra il 1944 e il 1945.

La situazione si fece estremamente difficile, sia perchè gli aiuto inviati dagli Alleati non sempre erano sufficienti, sia perchè i Tedeschi attuarono una violenta controffensiva.

---

Nella **primavera del 1945** gli Alleati ripresero l’offensiva e aumentarono in qualità e quantità i rifornimenti ai partigiani.

A metà aprile gli Anglo Americani sfondarono la linea gotica e, *Genova e Milano* il **25 aprile 1945** insorsero e si liberarono.

A **Mussolini** non restava che la fuga.

Cercò di fuggire vestito da soldato Tedecso, ma venne riconosciuto e fucilato da una formazione partigiana.

Il 30 aprile moriva suicida anche Hitler.

---

→ Sogno di un’Unione Europea, *Manifesto di Ventotene ***(Rossi, Spinelli).**

---

# Cronologia essenziale della Seconda Guerra Mondiale

| Data | Evento |
| --- | --- |
| 1 settembre 1939 | La Germania invade la Polonia. Inizia la Seconda Guerra Mondiale. |
| 3 settembre 1939 | Francia e Gran Bretagna dichiarano guerra alla Germania.
Mussolini dichiara la «non belligeranza» dell'Italia. |
| novembre 1939 | Attacco sovietico alla Finlandia. |
| apr.-giu. 1940 | La Germania occupa la Danimarca e la Norvegia. |
| 10 maggio 1940 | La Germania attacca la Francia. |
| 13 maggio 1940 | In Gran Bretagna Winston Churchill diventa primo ministro. |
| 10 giugno 1940 | L'Italia entra in guerra a fianco della Germania. |
| 14 giugno 1940 | I Tedeschi entrano a Parigi. Armistizio e Governo di Vichy. |
| estate 1940 | Offensiva italiana in Africa. |
| ago.-set. 1940 | Battaglia aerea d'Inghilterra («Operazione Leone Marino»). |
| 27 settembre 1940 | Patto tripartito tra Germania, Italia e Giappone. |
| 28 ottobre 1940 | L'Italia attacca la Grecia, senza successo. |
| ott. '40-feb. '41 | Controffensiva inglese in Africa. |
| aprile 1941 | L'esercito tedesco interviene nei Balcani e in Africa.
Italiani e Tedeschi occupano la Jugoslavia, la Grecia e riconquistano parte della Libia. Fine della “guerra parallela”. |
| maggio 1941 | Gli Inglesi occupano Addis Abeba (Etiopia), sottraendola agli Italiani. |
| 22 giugno 1941 | I Tedeschi invadono l'URSS («Operazione Barbarossa»). |
| 7 dicembre 1941 | Il Giappone attacca la flotta americana a Pearl Harbor. Gli Stati Uniti entrano in guerra. |
| 11 dicembre 1941 | Germania e Italia dichiarano guerra agli Stati Uniti d'America. |
| 20 gennaio 1942 | Conferenza di Wannsee: i nazisti decidono la soluzione finale del problema ebraico. |
| gen.-mag. 1942 | Avanzata giapponese in Asia. |
| gen.-giu. 1942 | Avanzata italo-tedesca in Africa. |
| mag.-giu. 1942 | Battaglie navali nell'Oceano Pacifico (Mar dei Coralli e Midway). Prime sconfitte del Giappone. |
| set. '42-feb. '43 | Battaglia di Stalingrado. Sconfitta dell'esercito tedesco. |
| 23 ott.-3 nov. 1942 | Battaglia di El Alamein. Sconfitta italo-tedesca. |
| 8 novembre 1942 | Sbarco anglo-americano in Marocco. |
| 23 gennaio 1943 | Conferenza di Casablanca (Inglesi e Americani decidono lo sbarco in Italia e il principio della resa incondizionata da imporre agli avversari) |
| 15 maggio 1943 | Resa italo-tedesca in Tunisia. Gli Anglo-Americani preparano lo sbarco in Italia. |
| 10 luglio 1943 | Sbarco anglo-americano in Sicilia («Operazione Husky») |
| 25 luglio 1943 | Il Gran consiglio del fascismo destituisce Mussolini, il Re lo fa imprigionare e affida il governo al Generale Badoglio. |
| 3 settembre 1943 | A Cassibile (Siracusa) firma segreta dell'armistizio “corto” dell'Italia con gli anglo-americani. |
| 8 settembre 1943 | Proclamazione alla radio dell'armistizio. Fuga del Re e di Badoglio a Brindisi.
Nasce il “Regno del Sud”. Sbarco a Salerno degli anglo-americani. I Tedeschi occupano l'Italia
fino a Salerno. Circa 800.000 soldati italiani, lasciati senza direttive, vengono deportati nei Lager nazisti. |
| 9 settembre 1943 | Nasce a Roma il C.L.N. (Comitato di Liberazione Nazionale) organismo politico della Resistenza italiana. |
| 12 settembre 1943 | Mussolini liberato dai Tedeschi a Campo Imperatore sul Gran Sasso. |
| 23 settembre 1943 | Nasce la Repubblica Sociale Italiana (R.S.I.) con capitale a Salò. |
| 29 settembre 1943 | Firma a Malta dell'armistizio “lungo” (strumento di resa incondizionata dell'Italia). |
| 13 ottobre 1943 | L'Italia dichiara guerra alla Germania. Formazione del Corpo di liberazione italiano. |
| gennaio 1944 | Gli Alleati sbarcano ad Anzio. |
| marzo 1944 | Svolta di Salerno (Togliatti convince i membri del C.L.N. ad entrare nel governo Badoglio; la questione istituzionale viene rimandata alla fine della guerra). |
| 4 giugno 1944 | Liberazione di Roma. Formazione del governo del C.L.N. presieduto da Ivanoe Bonomi. |
| 6 giugno 1944 | Sbarco degli Alleati in Normandia («Operazione Overlord»). |
| 10 giugno 1944 | Comando unificato delle forze partigiane. Nasce il C.V.L. |
| 24 agosto 1944 | Liberazione di Parigi. |
| set.-ott. 1944 | Le truppe sovietiche avanzano nell'Europa orientale. |
| febbraio 1945 | Conferenza di Yalta. |
| 25 aprile 1945 | Insurrezione generale proclamata dal C.L.N.A.I
I partigiani liberano Milano |
| 28 aprile 1945 | Fucilazione di Mussolini a Giulino di Mezzegra (Como) |
| 29 aprile 1945 | Resa dei tedeschi in Italia (effettiva dal 2 maggio). |
| 30 aprile 1945 | Adolf Hitler si suicida nel suo bunker a Berlino. |
| 2 maggio 1945 | I Russi entrano a Berlino. |
| 8 maggio 1945 | Resa incondizionata della Germania. |
| 17 lug.-2 ago. 1945 | Conferenza di Potsdam. |
| 6 agosto 1945 | Bomba atomica su Hiroshima (Giappone). |
| 9 agosto 1945 | Bomba atomica su Nagasaki (Giappone). |
| 2 settembre 1945 | Resa del Giappone. Fine della Seconda Guerra Mondiale. |

---

# La Seconda Guerra Mondiale in Sintesi

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20135.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20136.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20137.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20138.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20139.png)

![Untitled](Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%20140.png)

---

# Le origini della Guerra fredda

L’Europa uscì dalla guerra in condizioni disastrose:

- **L’economia** aveva subito danni incalcolabili;
- Molte **città** erano state devastate dai bombardamenti;
- Anche **l’agricoltura** era in ginocchio.

---

Stati Uniti e Unione Sovietica erano le due **superpotenze** e sovrastavano tutte le altre per forza economica e militare.

Venne decisa la costituzione di una nuova organizzazione internazionale, fondata il **24 giugno 1945** fu chiamata **ONU**.

L’ONU si proponeva lo stesso obiettico della Società delle Nazioni, nata alla fine della prima guerra mondiale: un futuro di pace e prosperità.

---

Lo Statuto dell’ìOnu fu l’espressione di due diverse concezioni: quella **utopistica** che richiamava i principi di libertà dei popoli di Wilson; e quella **realistica,** espressione della visione di Roosevelt.

Ispirato al principio di solidarietà è il lavoro svolto dalle agenzie dell’ONU, come **l’UNESCO.**

---

Fra il luglio el ‘ottobre del **1946** si svolse a Parigi la *Conferenza di pace*.

A Parigi non fu neanche possibile trovare un’intesa per definire la nuova sistemazione della Germania, il Paese così venne diviso in due parti, che corrispondevano ai territori occupati dagli eserciti:

- A Ovest, controllato dagli Anglo Americani, sorse la **Repubblica Federale Tedesca.**
- A Est, controllato dall’Armata Rossa, nacque la **Repubblica Democratica Tedesca:** uno stato comunista.

Anche Berlino venne divisa in due parti:

- Berlino Est controllata dai Sovietici;
- Berlino Ovest controllata dagli Americani, Inglesi e Francesi.

---

L’Austria tornò a essere indipendente.

L’Unione Sovietica recuperò alcuni territori che aveva perso con la prima guerra mondiale.

L’Italia perse tutte le colone.

Il Giappone restò sotto l’occupazione militare americana fino al 1951.

---

## 📍2. La divisione del mondo

**Dottrina Truman**: “La nascita dei regimi totalitari è favorita dalla miseria e dalla privazione. Essa si sviluppa al massimo quando è morta la speranza del popolo in una vita migliore”.

Gli Americani dovevano appoggiare i partiti anticomunisti e aiutare l’Europa nella difficile ricostruzione della loro economia.

---

Per sostenere i paesi Europei, Truman fece organizzare un grande programma di aiuti.

Noto come **piano Marshall**, il programma di aiuti americani, entrò in funzione nel **1948**.

Sempre nel 1947, **Andrej Zdanov**, ideologo di Stalin, rispose alla dtorrina Truman e al piano Marshall con un discorso in cui denunciava l’espansionismo degli Stati Uniti e concludeva affermando la necessità che i Paesi comunisti costituissero tra loro un blocco in grado di contrapporsi.

Nel 1949 l’Unione Sovietica promosse la costituzione del **COMECON.**

Sempre il 1949 è l’anno di fondazione della **Repubblica popolare Cinese.**

La cina si alleò inizialmente con l’Unione Sovietica, ma non durò a lungo questa alleanza.

---

Nel **1949** gli Stati Uniti, la Gran Bretagna, la Francia, il Beglio, i Paesi Bassi, il Lussemburgo, il Canada, la Norvegia, la Danimarca, l’Islanda, il Portogallo e l’Italia firmarono il **Patto Atlantico.**

Con tale patto tutti questi Stati si organizzavano in un’alleanza militare: la **NATO.**

Nel **1955** anche i Paesi comunisti si unirono in un’alleanza militare: il **Patto di Varsavia.**

---

Il mondo ormai era diviso in due **blocchi** contrapposti:

- Quello **occidentale** guidato dagli Stati Uniti, con un’economia capitalista.
- Quello **comunista**, guidato dall’Unione Sovietica, con un’economia controllata dallo stato.

---

## 📍3. La grande competizione

Il primo passo concreto in direzione dell’unità europea fu la costituzione della **CECA** (Comunità Europa Carbone e Acciaio) nel 1951.

Nel **1957** venne firmato tra sei Stati europe il **Trattato di Roma** che istituiva la **CEE** (Comunità Economica Europea).

---

Negli anni della guerra fredda USA e URSS cercarono di estendere le proprie zone di influenza, sostenendo governi a loro favorevoli in diverse parti del mondo.

La prima grave cristi riguardà **Berlino**.

Una parte della città era controllata dalle potenze occidentali, ma Berlino si trovava interamente nella Germania comunista.

Nel **giugno 1948** i Sovietici decisero di bloccare ogni via d’accesso alla città.

L’Europa sembrò sull’orlo di una nuova guerra.

Ma la crisi si risolse senza conseguenze militari.

---

## 📍4. La comunità Europea

Il piano Marshall fu di grande stimolo per l’Europa che venne spronata dagli Stati Uniti all’unità per favorire la circolazione delle merci.

Il progetto di un’unione europea venne portato avanti da uomini di diverso orientamento politico.

Il primo passo concreto fu la costituzione della **CECA** nel 1951.

Il successo della CECA stimolò i governi a una soluzione di più ampio respiro: nel **1957** venne firmato il **Trattato di Roma** che istituiva la **CEE**.

Si formava intanto il **MEC** (Mercato Comune Europeo), con il graduale abbattimento delle tariffe doganali e di tutto ciò che era di ostacolo alla libera circolazione delle persone e delle merci.

---

# La decolonizzazione

## 📍1. Il processo di decolonizzazione

Dopo la seconda guerra mondiale le potenze europee che avevano costruito i loro imperi coloniali in Africa e in Asia non furono più in grado di mantenerne il controllo.

Il conflitto mondiale aveva dato la spinta decisiva alla fine degli imperi coloniali.

Tra le due guerre erano sorti i primi **movimenti**  o **partiti indipendentisti:** il conflitto generalizzò questa situazione suscitando nelle colonie il sentimento nazionale e il desiderio di indipendenza.

Così già nel 1941 la Francia fu costretta a riconoscere, almeno formalmente, l’indipendenza di Libano e Siria. Nel 1942 Gandhi incitò gli Indiani a cacciare gli Inglesi e nel 1943 il leader nazionalista algerino Ferhat Abbas lanciò il *Manifesto del popolo algerino*  con la richiesta dell’abolizione della colonizzazione. 

Infine, nel 1944, al Congresso panafricano di Manchester i delegati rivendicarono l’indipendenza dei Paesi africani, da ottenere anche con la forza.

La decolonizzazione è il processo storico che ha portato alla fine degli imperi coloniali e all’indipendenza dei popoli afroasiatici.

Il processo di decolonizzazione durò circa quarant’anni (dagli anni **Quaranta** agli anni **Ottanta**).

In alcuni casi l’indipendenza fu raggiunta per **via pacifica,** con trattative tra la madrepatria e i gruppi dirigenti locali; in altri casi avvenne per **via violenta,**  con una guerra di liberazione.

La *Gran Bretagna *****per esempio, avviò gradualmente all’indipendenza le colonie, trasformando l’impero nel *Commonwealth* (libera associazione di popoli uniti nella ricerca del “bene comune” sotto l’egida di Sua Maestà britannica).

La *****Francia* invece oppose una dura resistenza ai movimenti di liberazione*.*

Fattore decisivo per lo smantellamento degli imperi coloniali fu la pressione degli Stati Uniti e dell’Unione Sovietica.

I due vincitori del secondo conflitto mondiale erano contrati al colonialismo: gli USA in nome della **libertà dei popoli,**  l’URSS in nome del **comunismo.**

Fin dal 1919 il presidente americano Wilson aveva dichiarato la necessità di una libera sistemazione di tutte le rivendicazioni coloniali, con attenzione alle esigenze delle popolazioni interessate.

La **Carta Atlantica** del 1941 aveva proclamato il “diritto di tutti i popoli a scegliere la forma di governo da cui intendevano essere retti”.

Da parte sua l’URSS tendeva a mostrarsi come il nemico numero uno del colonialismo.

Entrambe le superpotenze in realtà avevano l’obiettivo di allargare le loro zone d’influenza e fecero pesare in seguito la loro egemonia economica e politica nei Paesi dell’Africa e dell’Asia.

Il principio di **autodeterminazione dei popoli** ispirò poi le attività dell’Organizzazione delle Nazioni Unite.

Di fatto l’ONU non riuscì a imporre ovunque il rispetto dei princìpi di uguaglianza dei diritti, ma ricoprì comunque un ruolo importante nella lotta al colonialismo.

Critiche al colonialismo vennero infine anche dall’opinione pubblica e in particolare dalle Chiese.

Da parte dei paesi colonizzatori non mancarono anche motivi di semplice interesse.

Mantenere un controllo politico sulle colonie comportava costi assai consistenti. Decisamente più conveniente era infatti abbandonare il controllo politico diretto della colonia e mantenere quello economico: il colonialismo si trasformava così in **neocolonialismo.**

Dal punto di vista politico la democrazia di tipo europeo si affermò solo raramente. Spesso prevalsero regimi autoritari di destra o di sinistra: vere e proprie **dittature militari.**

## 📍2. La decolonizzazione nel Medio Oriente

Nei primi decenni del Novecento si sviluppò nel Medio Oriente un **movimento nazionale arabo** che si rivolse prima contro la dominazione ottomana e in seguito contro le potenze colonialiste.

Alla fine della prima guerra mondiale, Francia e Gran Bretagna si erano accordate per spartirsi i territori mediorientali: la Francia aveva ottenuto il mandato in Siria e Libano, la Gran Bretagna in Iraq e Palestina. 

I mandanti dovevano avviare all’indipendenza i popoli sottomessi, ma solo l’Iraq raggiunse presto l’indipendenza (1931), gli altri Paesi dovettero attendere la seconda guerra mondiale.

Durante il conflitto il premier inglese Churchill appoggiò decisamente le rivendicazioni nazionalistiche arabe, con l’obiettivo di estendere l’influenza britannica in Medio Oriente.

La pressione inglese indusse la Francia a riconoscere formalmente l’indipendenza di **Libano e Siria;** Il processo si completò nel 1946 quando i Francesi furono costretti a ritirare definitivamente le truppe. 

Nel frattempo, il 22 marzo 1945 era nata la **Lega Araba,** che raggruppava Libano, Siria, Iraq, Egitto e Arabia Saudita. Unita da scopi di cooperazione economica e politica, la Lega Araba sul piano politico si pose come obiettivo la nascita di un nuovo Stato arabo in Palestina, contro la volontà di creare uno Stato ebraico.

La scoperta degli orrori dei campi di sterminio nazisti aveva creato a livello internazionale un movimento di opinione pubblica favorevole alla nascita di uno Stato ebraico, che fosse anche un rifugio per sopravvissuti.

La causa **sionista**, ovvero della dottrina politica che afferma il diritto degli Ebrei ad avere uno Stato in Palestina, aveva forti alleati negli Stati Uniti, dove la comunità ebraica godeva di grande prestigio, ma fu ostacolata dall’Inghilterra e soprattutto dalla Lega Araba.

Incitate anche dal leader ebreo **David Ben Gurion** le organizzazioni militari ebraiche passarono allo scontro armato anche contro gli inglesi.

Il 22 novembre 1947 l’ONU propose di dividere la Palestina in due Stati, uno ebraico e uno arabo, con Gerusalemme come zona internazionale.

Gli Ebrei accettarono la spartizione, ma la Lega Araba rifiutò e si dichiarò pronta a combattere.

Il 14 maggio del **1948,** alla partenza degli inglesi, Ben Gurion proclamò la nascita dello **Stato di Israele.**

La Lega Araba il giorno successivo attaccò.

La **prima guerra arabo-israeliana** si risolse con la sconfitta delle truppe arabe e l’affermazione definitiva dello Stato d’Israele.

Al termine del conflitto i confini israeliani si espansero del 40% e lo Stato arabo non potè vedere la luce e la **questione palestinese** emerse in tutta la sua gravità.

Un milione di profughi arabi fuggirono dai territori conquistati dagli Israeliani per rifugiarsi nei Paesi vicini.

Le conseguenze del conflitto trasformarono l’area in un teatro di guerra che dura fino ai nostri giorni.

Nel **1964** nacque l’Organizzazione per Liberazione della Palestina (**OLP**), con lo scopo di addestrare i Palestinesi a combattere Israele per la nascita di uno Stato palestinese.

## 📍3. La decolonizzazione in Asia

L’India era da più di un secolo il fulcro dell’Impero britannico.

Tra la prima e la seconda guerra mondiale la richiesta di indipendenza da parte indiana divenne sempre più pressante. La lotta era sostenuta dal Partito del Congresso, espressione della borghesia indù, ma coinvolse ben presto l’intera popolazione, grazie all’influenza del **Mahatma Gandhi.**

Nel 1915 divenne una delle figure centrali del Partito del Congresso e impostò la lotta per l’indipendenza sulla **non-violenza.**

Tra il **1941 e il 1942** promosse un movimento di resistenza non violenta alla guerra e agli Inglesi.

Così, anche per timore che l’India potesse schierarsi col nemico giapponese, il governo britannico promise la concessione dell’indipendenza.

Alla fine della guerra, la Gran Bretagna aprì i negoziati per trattare il trasferimento del potere.

Il problema più grave indiano era rappresentato dalla difficile coesistenza delle comunità religiose induista e musulmana.

Mentre Gandhi sosteneva la necessità di creare un unico Stato laico, dove potessero convivere le due comunità, la lega musulmana reclamava la separazione del Paesi in due Stati.

il 15 agosto **1947** nacquero l’**Unione indiana,** a maggioranza indù, e il **Pakistan,** musulmano.

Con la nascita dei due Stati i conflitti non cessarono, lo stesso Gandhi fu vittima di quel clima di odio, venne infatti assassinato da un fanatico che gli rimproverava di credere ancora nella riconciliazione.

Durante la seconda guerra mondiale il Giappone aveva occupato le colonie inglesi, francesi e olandesi del Sud-Est asiatico.

L’arrivo dei Giapponesi rappresentò un duro colpo per il colonialismo europeo: molte popolazioni locali vissero il fatto come una liberazione. 

Il 17 agosto **1945** i nazionalisti indonesiani giunsero a un’intesa con l’Olanda e proclamarono la Repubblica indipendente con presidente Sukarno.

L’anno successivo gli Olandesi tentarono di riprendere il controllo ma, per volontà di USA, URSS e India, il Consiglio di Sicurezza dell’ONU impose all’Olanda il cessate il fuoco e la riapertura dei negoziati: la **Repubblica degli Stati Uniti d’Indonesia** fu riconosciuta ufficialmente nel **1949.**

Nell’ex Indocina francese era sorta la Lega per l’indipendenza guidata dal leader comunista HO Chi Minh.

Ho Chi Minh proclamò ad Hanoi la Repubblica Democratica del **Vietnam**.

I Francesi non riconobbero il nuovo Stato e l’anno seguente rioccuparono la parte meridionale del Paese.

La guerra divampò in tutto il Paese.

Nel luglio del **1954** gli Accordi di Ginevra stabilirono il ritiro dei Francesi da tutta la penisola indocinese e decretarono la nascita dello Stato vietnamita.

Il Vietnam fu diviso in **Vietnam del Sud**  a regime filoccidentale, e **Vietnam del Nord** a regime comunista. Questa separazione determinerà una guerra cruenta che coinvolgerà anche gli Stati Uniti.

## 📍4. La decolonizzazione nel Maghreb

Con il termine *Maghreb* si intende l’occidente della nazione araba.

Il primo stato del Maghreb a ottenere l’indipendenza fu la colonia italiana della **Libia.**

Fin dal **1947** con la firma del Trattato di pace di Parigi, l’Italia aveva dovuto rinunciare a tutti i suoi possedimenti in Africa.

Nel dicembre **1951** la Libia ottenne l’indipendenza e venne istituita la monarchia.

Nel **1969** un colpo di Stato di militari guidati dal colonnello **Gheddafi** depose la monarchia per instaurare la repubblica.

Il regime di Gheddafi si schierò con l’URSS, chiudendo le basi militari inglesi e americane.

In **Marocco e Tunisia** la Francia cercò di domare il movimento nazionalista arabo, alternando repressione militare e proposte di parziale autogoverno.

Infine nel **1956** la Francia concesse ufficialmente la piena indipendenza a tutti i Paesi.

L’indipendenza dell’**Algeria** fu al ungo ostacolata da circa un milione di coloni francesi insediati nel Paese. Il movimento nazionalista algerino si era sviluppato negli anni Trenta e dopo la seconda guerra mondiale.

A partire dagli anni Cinquanta il movimento nazionalista algerino si riogranizzò costituendo il **Fronte di Liberazione Nazionale (FLN).**

La lotta contro i francesi si fece più cruenta, ne derivò una guerra aspra e violenta destinata a durare per otto anni.

Nel **1957** la **battaglia di Algeri** segnò il culmine dello scontro: per nove mesi l’intera città fu coinvolta nella guerriglia urbana.

Nella stessa Francia la guerra d’Algeria aveva creato una gravissima frattura politica, destinata a generare la cristi della Repubblica.

La crisi si concluse nel 1958 con il ritorno al potere di **Charles de Gaulle.**

Fu proprio de Gaulle a porre fine al conflitto. Le trattative con l’FNL portarono nel **1959** al riconoscimento del diritto dell’Algeria all’autodeterminazione.

## 📍5. La decolonizzazione nell’Africa Nera

Nel dopoguerra la sorte dell’ex colonia italiana dell’**Eritrea** fu affidata all’ONU, ma decidere del suo futuro non fu facile, a causa delle rivendicazione dell’Etiopia.

Nel **1991** la lotta si concluse con la vittoria dell’Eritrea che ottenne la piena indipendenza.

Meno drammatico fu invece il processo di decolonizzazione della **Somalia.**

Nel **1949** l’Italia ricevette dall’ONU l’incarico di amministrare l’ex colonia per avviarla alla completa autonomia.

Nel **1960** la Somalia italiana e la Somalia inglese divennero indipendenti e si unificarono per formare un unico stato.

Nel **1977** anche la Somalia francese ottenne l’indipendenza con il nome di **Repubblica di Gibuti.**

Il processo di emancipazione dei Paesi a sud del Sahara cominciò più tardi rispetto a quelli dell’Africa mediterranea, ma fu più rapido e meno violento.

Cominciò nell’Africa occidentale nel **1957** con l’indipendenza del **Ghana.**

Per quanto riguarda l’Africa nero francofona, nel **1958** tutte le colonie francesi accettarono con referendum locali di entrare a far parte della **Comunità franco-africana** proposta dal generale de Gaulle.

La prima colonia francese ad affrancarsi fu la **Guinea.**

Il **1960** vide la nascita di diciassette Stati africani indipendenti, tra cui **Nigeria e Congo belga,** per questo venne definito “Anno dell’Africa”.

IL processo di decolonizzazione fu pacifico ma spesso pilotato dalle potenze europee, in modo da trasmettere il potere ai gruppi politici più disposti a mantenere legami economici con loro, senza intaccare le vecchie strutture coloniali.

Nel 1960 ottenne l’indipendenza il **Congo belga**, ma il processo fu particolarmente drammatico.

I moti d’indipendenza guidati dal leader nazionalista convinsero il re del Belgio a concedere l’indipendenza, ma subito dopo scoppiò una sanguinosa guerra civile e vi fu un tentativo di secessione della regione mineraria del Katanga.

La guerra civile caratterizzò anche i primi anni della decolonizzazione in **Nigeria** divenuta indipendente alla fine del 1960.

Il Sudafrica rimase l’unico Stato del continente in cui i bianchi riuscirono a mantenere il pieno potere.

Il regime di **apartheid,** cioè di separazione razziale tra cinque milioni di bianchi e oltre venti milioni di neri, si inasprì tra gli anni Cinquanta e Sessanta.

A nulla valsero le proteste dell’opinione pubblica internazionale, né le rivolte della comunità nera.

Il partito guidato da **Nelson Mandela** si batté con forza per i diritti civili dei neri, ma ogni rivendicazione fu puntualmente repressa dal regime.

Mandela fu arrestato e rinchiuso fino al **1990,** anno in cui vennero abolite le leggi di segregazione razziale.

## 📍6. I problemi dell’America Latina

I Paesi dell’America Latina, già indipendenti da lunga data, non dovettero affrontare i problemi legati alla decolonizzazione e, negli anni del dopoguerra, poterono godere di un favorevole contesto politico.

Tuttavia, la condizione generale del continente era di **arretratezza** e soprattutto di **dipendenza** dagli Stati Uniti.

Nel 1948 venne creata, dietro iniziativa degli USA, l’**Organizzazione degli Stati Americani** che aveva lo scopo di rafforzare la cooperazione economica fra gli Stati del continente.

Nel periodo della seconda guerra mondiale i Paesi dell’America Latina avevano tratto importanti vantaggi economici dall’accresciuta richiesta di materie prime e di prodotti agricoli.

Fu soprattutto il **ceto medio urbano** a rafforzarsi.

Sensibili alle istanze del **nazionalismo** gli appartenenti ai ceti medi si opponevano al predominio delle oligarchie tradizionali ma anche ai tentativi di riscossa delle classi più povere.

Per questo in America Latina si verificarono soluzioni politiche di stampo sia **liberale,** sia **populista**, sia apertamente **dittatoriale.**

La costante presenza americana nell’ambito economico, le opposte volontà di cambiamento e di conservazione dei ceti più poveri e delle oligarchie dominanti, il crescente ruolo dell’esercito sono alla base dei frequenti e spesso violenti cambiamenti politici nei Paesi dell’America Latina.

Anche un grande Paese come il **Brasile** fu sconvolto da lotte civili.

Nel 1945 l’esercito rovesciò il governo.

Negli anni successivi i governi brasiliani avviarono una politica di **industrializzazione e modernizzazione** che ebbe il simbolo più significativo nella nuova capitale **Brasilia.**

Il Paese però non riuscì a liberarsi dalla dipendenza economica, né dalle evidenti disparità sociali e dagli squilibri interni.

L’economia brasiliana conobbe un notevole miglioramento ma gli squilibri sociali divennero ancora più drammatici.

Anche in **Venezuela e Colombia** si instaurarono regimi militari.

Sull’isola di Cuba si verificò un evento destinato a segnare profondamente la politica non soltanto latinoamericana.

Nel **gennaio 1959** la dittatura reazionaria venne abbattuta da un movimento rivoluzionario guidato da **Fidel Castro**, dopo tre anni di guerriglia iniziata sulla Sierra Maestra.

Subito Castro, che si ispirava a ideali democratici e riformisti, iniziò una riforma agraria.

IL che spinse gli Stati Uniti, dopo l’iniziale riconoscimento della rivoluzione, ad assumere una posizione sempre più rigida, anche nel timore che l’esempio cubano potesse essere seguito altrove in Sudamerica.

Il presidente Eisenhower impose il **boicottaggio economico** impedendo a Cuba qualsiasi forma di commercio con i Paesi capitalisti.

Castro perciò ruppe le relazioni diplomatiche con gli Stati Uniti e chiese il sostengo dell’**Unione Sovietica**, che si impegnò ad acquistare lo zucchero cubano a prezzi superiori a quelli del mercato.

Il regime cubano così si radicalizzò, adottando il **comunismo.**

Castro e i suoi collaboratori, tra cui **Ernesto “Che” Guevara,** dichiararono apertamente la loro intenzione di esportare il modello rivoluzionario cubano nel resto dell’America latina e nel Terzo Mondo: un’aperta sfida agli Stati Uniti e al loro concetto di ordine mondiale. 

---

# La distensione

Il **5 marzo 1953** morì Stalin e ciò favorì una nuova fase: il cosiddetto **disgelo.**

Al Cremlino si insediò **Nikita Kruscev.**

Diventato segretario del Partito Comunista dell’Unione Sovietica, Kruscev dimostrò subito di voler chiudere l’epoca oscura dello stalinismo.

Nel frattempo negli Stati Uniti era diventato presidente **Eisenhower**, il generale dello sbarco in Normandia.

Eisenhower sostenne la necessità di irrigidire ancor di più la condotta americana nei confronti dell’Unione Sovietica, passando da una politica di contenimento del comunismo a una che mirava a farlo arretrare.

Ma di fatto l’amministrazione mostrò attenzione ai segnali di apertura che provenivano dall’Unione Sovietica.

Queste posizioni resero possibile la **Conferenza di Ginevra nel 1955..**

<aside>
💡 Iniziò così la fase della **distensione:** il contrasto e la competizione tra USA e URSS restarono ma senza le tensioni e gli eccessi degli anni precedenti.

</aside>

---

Nel **1956** Kruscev denunciò i crimini di Stalin.

Tra i comunisti occidentali, che consideravano Stalin un eroe, il disorientamento fu grande.

Nei *Paesi del blocco comunista*, invece si sviluppò la speranza di una vera svolta verso un regime meno oppressivo.

In **Ungheria** si fece il tentativo più ambizioso: il capo del governo voleva concedere la libertà di stampa e portare l’Ungheria fuori dal Patto di Varsavia.

Ma l’Unione Sovietica fece intervenire l’Armata Rossa e soffocò nel sangue il tentativo riformatore (**1956**).

La repressione ungherese destò grande scalpore in Occidente. Alcuni comunisti presero le distanze dall’Unione Sovietica.

La repressione aveva dimostrato anche che gli Stati comunisti dell’Europa orientale erano degli **Stati satelliti:** non contavano nulla perchè dipendevano completamente dalla volontà di Mosca.

Altre brutali repressioni confermarono la totale sottomissione all’URSS degli Stati del blocco comunista.

<aside>
🪖 Il caso più grave si verificò in **Cecoslovacchia:** il partito comuinsta tentò di dar vita a un processo riformatore ma l’Unione Sovietica, preoccupata che questa iniziativa si estendesse a tutti gli altri Paesi del blocco sovietico, decise di intervenire.

Nell’agosto del **1968** carri armati dell’Armata Rossa entrarono in Praga, ponendo fine alla “Primavera di Praga”.

</aside>

La giustificazione di questo intervento è passata alla storia come la teoria della **sovranità limitata.**

---

I cambiamenti avvenuti in Unione Sovietica negli anni Cinquanta ebbero importanti ripercussioni anche nei rapporti con la Cina.

Dopo alcuni anni di collaborazione con la Cina del tutto allineata all’URSS, alla fine del decennio fra i due Stati emersero contrasti sulle questioni di **politica internazionale** ma anche riguardo alle scelte di **politica interna** dei rispettivi governi.

L’URSS intendeva assumere la **guida esclusiva** del mondo comunista, mentre la Cina intendeva contestare questo bipolarismo, mettendosi alla guida dei movimenti rivoluzionari del Terzo Mondo in vista di una più decisa lotta contro l’imperialismo capitalista.

Dopo la proclamazione della Repubblica popolare nel 1949, la Cina aveva iniziato un grande sforzo di industrializzazione, soprattutto nell’ambito dell’**industria pesante,** grazie anche all’aiuto di tecnici sovietici: i risultati furono soddisfacenti.

Per rilanciare la produzione agricola, Mao Zedong e i vertici del partito lanciarono la campagna utpistica del “**grande balzo in avanti**”.

Le comuni popolari, che riunirono forzatamente le piccole cooperative, divennero l’unità di base amministrativa ed conomica della Cina: avrebbero dovuto diventare autosufficienti in tutti i settori e per questo la popolazione subì controlli sempre più rigidi e una propaganda martellante.

Un altro fronte di contrasto fu la scelta russa di non fornire assistenza alla Cina in ambito nucleare, per mantenere la supremazia in quel settore nel mondo comunista: la Cina riuscì a dotarsi comunque della **bomba atomica** nel 1964, ma i rapporti fra le due nazioni erano ormai incrinati.

Il fallimento del “grande balzo in avanti” diede forza ai settori più moderati del gruppo dirigente comunista.

La reazione di Mao fu durissima e inedita nei regimi comunisti: grazie all’appoggio dell’esercito e del ministro della Difesa, vennero mobilitati i Cinesi più giovani in una ribellinoe contro i fautori della “via capitalistica”.

Questa mobilitazione culminò nella “**rivoluzione culturale**”: negli ambienti di laboro, nelle scuole, le giovani **Guardie rosse** contestavano e rovesciavano ogni autorità.

La rivoluzione culturale avrebbe dovuto portare a un rovesciamento radicale nella cultura e nella mentalità del popolo cinese per una rapida realizzazione del comunismo, ma fu anche un vero e proprio **Colpo di Stato.**

In molte parti del mondo, e in particolare in Europa occidentale, la rivoluzione culturale divenne fonte di ispirazione per molti gruppi e movimenti giovanili: il loro riferimento era il **“libretto rosso”**, un’antologia di scritti di Mao Zedong.

La rivoluzione culturale aveva causato profonde fratture all’interno del movimento comunista cinese e portato l’economia nazionale sull’orlo del caos,

Le Guardie rosse furono allontanate dalle città e nel partito gli elementi più radicali furono posti ai margini, sostituiti da tecnici ed esperti.

Fu preziosa in questo momento l’opera di **Zhou Enali**, che segnò una sostanziale continuità durante un periodo di grandi cambiamenti.

A lui si deve anche una nuova linea in **politica estera**: per sfuggire all’isolamente in cui l’ostilità dell’URSS l’aveva lasciata, la Cine aprì clamorosamente agli Stati Uniti.

Nel 1972 la Cina comunista venne ammessa all’ONU.

Mao Zedong e Zhou Enali morirono entrambi nel 1976: la Cina comunista si avviava verso un **radicale cambiamento.**

---

Nel **gennaio 1961** divenne presidente degli Stati Uniti **John Fitzgerald Kennedy**.

Ebbe subito grande popolarità per il suo stile personale e si impegnò in una battaglia per rinnvoare la società americana e per favorire la distensione internazionale.

Dopo la conquista dell’Ovest compiuta nell’Ottocento ora bisognava oltrepassare una “nuova frontiera”, non più materiale, ma culturale e scientifica.

Nel **1961** Kennedy incontrò per la prima volta Kruscev: il problema da risolvere era quello di Berlino Ovest che i Sovietici avrebbero voluto trasformare in “città libera”, mentre per gli Americani faceva parte a tutti gli effetti della Germania federale.

La risposta sovietica non si fece attendere: due mesi dopo, venne costruito un **muro** che attraversava la città di Berlino così da dividere il settore orientale da quello occidentale.

Da allora il Muro di Berlino divenne il **simbolo della guerra fredda.**

Intanto a Cuba una rivoluzione aveva portato al potere un governo di tendenze marxiste guidato da **Fidel Castro**; numerose pressione furono esercitate su Kennedy affinché fosse eliminato un pericolo comunista così vicino.

Il presidente diede il suo avallo a una spedizione di esuli cubani appoggiati dai servizi segreti americani; riuscirono a sbarcare sull’isola ma ebbero la peggio nello scontro con l’esercito cubano.

Questa sconfitta gravò pesantemente sulla popolarità di Kennedy.

Invece Castro, sempre più osteggiato dagli USA, che bloccarono le importazioni di zucchero da Cuba, proseguì l’avvicinamento al blocco sovietico, il quale ne approfittò per impiantare **basi missilistiche** in grado di colpire qualunque parte degli Stati Uniti.

Kennedy ordinò un **blocco navale** dell’isola; l’Unione Sovietica fece marcia indietro e smantellò i missili da Cuba.

Nel **1963** Kennedy firmò con kruscev un importante trattato che per la prima volta limitava gli esperimenti atomici.

In politica interna Kennedy si impegnò soprattutto per superare le gravi discriminazioni che ancora colpivano i neri.

Ma il 22 novembre **1963** fu assassinato in circostanze che non sono state ancora completamente chiarite.

Un altro importante protagonista della distensione fu **papa Giovanni XXIII**.

Nel **1963** il papa pubblicò l’enciclica *Pacem in terris* con cui raccomandava al mondo e alle superpotenze la scelta della pace.

---

La lotta per l’indipendenza del Vietnam aveva allontanato i Francesi dalla penisola indocinese.

Si era conclusa nel 1954 con gli Accordi di Ginevra, che avevano diviso il Paese in due: la Repubblica comunista del **nord** e quella del **Sud.**

Contro il governo del Sud, la protesta si organizzò in un movimento cmounista di guerriglia, chiamato **Vietcong**, appoggiato dal Vietnam del Nord.

Per paura che l’intero paese divenisse comunista, gli Stati Uniti decisero di intervenire con un contingente di “consiglieri militari”.

Dal 1956 in poi gli Stati Uniti sfruttarono ogni pretesto per accrescere la loro presenza in Vietnam al fine di impedire al comunismo di espandersi in quell’area.

Nel **1956** il nuovo presidente, **Johnson**, decise di intervenire massicciamente, dando il via a una serie di bombardamenti su tutto il territorio del Vietnam del Nord, senza che vi fosse stata alcuna dichiarazione di guerra.

Nel **1968** i Vietcong lanciarono nel Vientam del Sud una grande offensiva, questa, anche se non ottenne significativi risultati militari, fece comprendere agli Americani l’impossiblità di giungere a una rapida vittoria.

Nel marzo del 1968 Johnson ordinò la sospensione dei bombardamenti e annunciò contemporaneamente che non si sarebbe presentato alle elezioni di quell’anno.

Il suo successore, **Nixon**, avviò le trattative di pace e ridusse l’impegno militare americano in Vietnam.

La guerra si concluse nel **1973** con un armistizio firmato a **Parigi** che prevedeva il graduale ritiro del contingente americano.

La riunificazione del paese avvenne il 30 aprile del **1975.**

L’opinione pubblica americana manifestò progressivamente la propria ostilità alla guerra, anche a causa del crescente numero di morti e feriti.

La sconfitta americana portò come contraccolpo alla costituzione di regimi comunisti anche in Laos e in Cmabogia: in quest’ultimo andarono al potere i cosiddetti **Khmer Rossi**, un gruppo di guerriglieri comunisti.

Dopo la fine della guerra il Vietnam si era legato strettamente all’Unione Sovietica.

I Khmer Rossi diedero il via a durissime misure di repressione: un vero e proprio sterminio.

---

Contrò la guerra del Vietnam polemizzò duramente il **Sessantotto**: il movimento internazionale che esplose nel 1968 con una serie di grandi agitazioni nelle università, nelle scuole secondarie, nelle fabbriche e nelle piazze.

Ne furono protagonisti i **giovani**: uno scontro generazionale senza precedenti nella storia.

Per la prima volta dunque i giovani avevano una loro indipendenza economica e formavano una **nuova categoria di consumatori**.

Ai giovani statunitensi si affiancarono quelli europei nel manifestare un’**insofferenza generale** per il modno degli adulti ritenuto nevrotico e falso.

Si respirava un’atmosfera di rottura con il passato che si esprimeva anche visivamente: la moda propose la **minigonna;** i ragazzi incominciarono a farsi cresere i capelli e la barda, la “pillola” rivoluzionò i comportamenti sessuali.

Fu allora che milioni di giovani scesero in piazza per “contestare il sistema” e sottoporre a critica radicale le istituzione e i fondamenti stessi della società in cui vivevano.

Tutti i grandi centri universitari europei vennero toccati, ma anche l’altra parte del mondo, quella comunista, venne attraversata in molti punti dalla volontà di cambiamento: la Primavera di Praga e la rivoluzione culturale cinese furono eventi che fecero sentire ai giovani un senso di solidarietà cosmopolita.

Se in America la contestazione ebbe come obiettivi il modello di vita occidentale e la partecipazione degli Stati Uniti alla guerra del **Vietnam**, in Europa la presenza di forti partiti di sinistra spinse il movimento giovanile a sostenere le lotte sindacali.

---

Il confronto tra USA e URSS, pur senza mai sfociare in guerra aperta, si sviluppò prospettando comunque questa eventualità.

Fino a quando solo gli Stati Uniti erano in possesso di bombe atomiche, pareva non ci fossero da temere iniziative d’aggressione da parte sovietica.

Ma questa riuscì ben presto a dotarsi di bombe atomiche.

La superiorità americana nel settore nucleare portò gli esperti della Difesa del Paese a elaborare la dottrina detta della “**rappresaglia totale**”: gli Stati Uniti avrebbero risposto con massicci attacchi atomici, in qualunque zona del blocco comunista, a ogni aggressione, manovrata dai Sovietici.

L’Unione Sovietica lentamente riuscì a diminuire il distacco dal potenziale nucleare americano.

Una nuova strategia fu allora escogitata, la **MAD:** entrambe le parti dovevano mantenere una forza nuclerare sufficiente e invulnerabile per infliggere un danno inevitabile e insopportabile all’avversario che avrebbe dato il via a una guerra nucleare.

Si instaurò così “**l’equilibrio del terrore**”.

Gli Americani, pertanto, elaborarono una strategia alternativa: la “**risposta flessibile**”, secondo la quale ogni attacco sovietico si sarebbe scontrato con una risposta armata dello stesso livello.

La consapevolezza della “**paralisi nucleare**” indusse USA e URSS a impegnarsi, sia pure lentamente, in vista di una diminuzione o di una più remota scomparsa delle armi nucleari.

Nel **1969** Breznev e Nixon diedero il via a incontri che culminarono nei colloqui **SALT**, che avevano come obiettivo la **limitazione** reciproca delle testate nucleari.

In questo contesto grande eco suscitò nel **1975** la **conferenza di Helsinki** sulla sicurezza e la cooperazione in Europa.

Nella prima metà degli anni Ottanta il filo del dialogo sembrò interrompersi: sotto la presidenza del repubblicano **Reagan,** gli USA intrapresero un grande sforzo per potenziare il loro apparato difensivo progettando un sistema di difesa chiamato “**scudo spaziale**”.

Per qualche anno sembrò di essere tornati al clima degli anni Cinquanta.

In seguito la svolta politica in URSS favorì il riavvicinamento tra le due superpotenze.

Dopo una serie di colloqui nel **1986** **Reagan e Gorbacev** firmarono un accordo che prevedeva il ritiro delle testate nucleari presenti in Europa.

Nel **1988** Gorbacev annunciò di fronte all’ONU la riduzione delle truppe russe nell’Est Europeo.

L’anno dopo crollava il muro di Berlino (**1989**): il simbolo della Guerra Fredda.

Nel **1991** cessava di esistere la stessa Unione Sovietica.

Il mondo era entrato in una nuova epoca: quella del **terzo dopoguerra.**

---

# L’Italia repubblicana

*Ricostruire:* è il titolo che compare a caratteri cubitali sulle prime pagine dei giornali italiani all’indomani della fine della guerra.

Ora bisognava affrontare enormi sacrifici per la ricostruzione morale e materiale del Paese. Si trattava anzitutto di rifare ciò che era stato distrutto dalle vicende belliche.

Ricostruire significava anche rimetter ein moto la vita economica e restituire alla popolazione un’esistenza dignitosa.

I primi governi dell’Italia liberata vararono specifici programmi che prevedevano interventi di soccorso alla popolazione e l’avvio di lavori pubblici.

Nel **1946** l’**UNRRA** (Amministrazione delle Nazioni Unite per il Soccorso e la Ricostruzione) s’impegnò a fornire all’Italia aiuti per combattere il pericolo della fame, oltre a materie prime e macchinari per la ripresa delle attività industriali.

Gli aiuti non furono comunque sufficienti a sanare la situazione e, negli anni seguenti, fu il **piano Marshall** a far confluire in Italia centinaia e centiaia di milioni di dollari.

Oltre che dagli aiuti americani un apporto tutt’altro che trascurabile alla ricostruzione venne dato dalle **rimesse degli emigrati**, ovvero il denaro che gli Italiano all’estero mandavano ai propri cari.

Fino al **maggio 1947** i governi italiani si ispirarono all’unità antifascista e compresero, oltre alla DC e alle forze minori di centro - sinistra, anche i socialisti e i comunisti.

Solo su un punto le forze di governo erano unanimi: l’abbandono del modello autarchico fascista e la conseguente liberalizzazione degli scambi commerciali con l’estero.

Si affermò la linea politica economica di **Luigi Einaudi**.

Einaudi puntò tutte le sue carte sulla stabilità monetaria e sul contenimento dell’inflazione, anche a costo di sacrificare l’occupazione.

Inoltre svalutò la lira in modo da favorire un forte aumento delle esportazioni.

In questo momento Einaudi gettò le basi di quel “miracolo economico” che si sarebbe prodotto negli anni Cinquanta.

---

<aside>
🇮🇹 Nel giugno del **1945** nacque il primo governo del dopoguerra, presieduto da **Ferruccio Parri**, uno dei capi della Resistenza.

</aside>

Sembrava un governo destinato ad avviare importanti riforme economiche e sociali sotto la spinta del movimento partigiano e invece cadde dopo soli cinque mesi.

Si stavano delineando **due schieramenti opposti**: da una parte la DC, i ceti medi, la borghesia, il mondo imprenditoriali e gli Stati Uniti; dall’altra il Partito comunista, la classe operaia, il proletariato, la CGIL, l’Unione Sovietica.

La tensione era alta, c’era il timore che lo scontro sociale potesse trasformarsi in una guerra civile.

Nell’estate del 1945 l’Italia sembrava quindi sull’orlo di una guerra civile fra comunisti e anticomunisti.

In realtà la tensione si stemperò rapidamente nei mesi successivi.

Lo stesso PCI, benchè strettamente legato all’URSS, non operò concretamente per la rivoluzione socialista.

Anche il suo segretario, **Palmiro Togliatti**, temeva il rischio di una drammatica guerra civile.

Per questo motivo, sia Togliatti che Pietro Nenni, leader dei socialisti, richiedevano con forza le elezioni a breve termine per l’**Assemblea Costituente** che avrebbe dovuto disegnare la nuova forma dello Stato italiano.

Ma su questo punto ebbe la meglio il leader della DC, **Alcide De Gasperi**, che convinse le Sinistre a rimandare le elezioni alla primavera del 1946.

<aside>
🇮🇹 Dopo la caduta del governo Parri, il **10 dicembre 1945 De Gasperi** divenne presidente del Consiglio.

</aside>

De Gasperi fu il primo esponente di un partito dei cattolici a guidare un esecutivo nella storia d’italia.

Avrebbe governato sino al **1953.**

Il dibattito tra i partiti antifascisti fu molto aspro.

Lo scontro verteva in particolare sui poteri da conferire all’Assemblea Costituente: De Gasperi temeva che una Costituente “sovrana”, cioè con ampi poteri, avrebbe finito per assomiglaire alla Convenzione Nazionale della Rivoluzione Francese.

Si oppose con tutte le sue forze e ottenne che la scelta istituzionale fosse affidata a un **referendum** popolare e che la costituente si limitasse a elaborare e approvare la nuova Costituzione.

<aside>
🗳️ Il **2 giugno 1946** gli Italiani si recarono in massa alle urne per scegliere tra monarchia e repubblica e, contemporaneamente, eleggere i deputati della Costituente.

</aside>

Si trattò delle prime elezioni a **suffragio universale** della storia d’Italia.

Nel referendum istituzionale prevalse, seppur di poco, la **repubblica.**

La costituente designò come suo presidente il socialista **Giuseppe Saragat.**

Come capo provvisorio dello Stato l’assemblea elesse **Enrico de Nicola.**

<aside>
🇮🇹 La Costituente nei diciotto mesi successivi si dedicò con fervore alla stesura della Costituzione della Repubblica Italiana, che venne approvata nel 1947 ed entrò in vigore **1 gennaio 1948**

</aside>

Gli **organi dello Stato** sono:

- il **Parlamento**, che esercita il potere legislativo, si compone di due camere, dei deputati e il senato.
- il **Governo**, formato dal presidente del Consiglio dei ministri, con il potere esecutivo
- la **Magistratura** ha il potere giudiziario.

A capo dello stato c’è il **presidente della Repubblica.**

La **forma di governo** è dunque rappresentativa e parlamentare:

- *rappresentativa *****perchè i cittadini non esercitano direttamente il potere decisionale ma delegano il compito ai propri rappresentanti
- *parlamentare* perchè il Governo risponde del suo operato alle Camere.

Nel **1955** venne istituita la **Corte Costituzionale**, organo che soprattutto deve verificare se e leggi varate dai governi siano o meno *costituzionali.*

Tra le questioni più delicate che il governo De Gasperi dovette affrontare nell’autunno del 1946 vi fu quella del **trattato di pace**.

L’atteggiamento delle potenze vincitrici non fu tenero verso l’Italia, perchè questa era comunque considerata responsabile dei misfatti del fascismo.

Il trattao di pace venne firmato nel **1947** e le condizioni per l’Italia furono molto dure.

Sempre nei primi mesi del 1947 De Gasperi si recò negli Stati Uniti e tornò con un prestito all’Italia  del valore di 100 milioni di dollari, ma con la certezza di aver consolidato l’amicizia con l’America.

Quando il presidente Truman tenne al Congresso il famoso discorso nel quale espirmeva la preoccupazione per la crescente influenza sovietica sui Paesi dell’Europa orientale, divenne per tutti chiaro che la collaborazione tra DC e Sinistre era ormai impossibile.

Nel **maggio 1947** De Gasperi varò un nuovo governo del quale non facevano più parte le Sinistre. Iniziò così una nuova fase politica, detta del **centrismo** perchè caratterizzata da governi impreniati sulla DC con la partecipazione di partiti minori di centro.

Nel **1949** l’Italia entrò nella **NATO**, l’alleanza militare di cui facevano parte gli Stati Uniti.

<aside>
🇮🇹 In un clima di grande passione e di dura contrapposizione ideologica il **18 aprile 1948** si svolsero le elezioni politiche.

Le votazioni assegnaro alla **DC** una vittoria clamorosa.

</aside>

La guerra tra antifascismo e fascismo era ormai del tutto conclusa, ma cedeva il passo alla “guerra di religione” tra comunismo e anticomunismo.

La tensione di questi mesi trova conferma nell’**attentato** del **14 luglio 1948:** un fanatico, Antonio Pallante, sparò a Palmiro Togliatti mentre usciva dal Parlamento.

A Torino gli operai occuparo la FIAT e presero in ostaggio l’amministratore delegato.

Ma Togliatti e il gruppo dirigente comunista scoraggiarono l’insurrezione armata ritenendola unt ragico errore che avrebbe condotto il Paese alla guerra civile.

---

<aside>
🇮🇹 A metà degli anni Cinquanta l’Italia era ancora un Paese arretrato.

Ma nel periodo **1958 - 1963** si verificò un eccezionale *boom *****economico: è il cosiddetto *miracolo italiano*, grazie al quale il nostro paese diventò in tempo record uno dei più industrializzati del mondo.

La data iniziale del “miracolo” corrisponde all’**ingresso dell’Italia nella CEE**

</aside>

Il cambiamento venne prodotto dall’inventiva di tanti imprenditori, piccoli e grandi, così come dal sacrificio degli immigrati e dal lavoro degli operai.

> Enrico Mattei → AGIP
> 

L’italia trasse beneficio dalla più **generale espansione dell’economia mondiale.**

Inoltre i suoi settori industriali più avanzati poterono competere sul mercato europeo grazie al **basso costo della manodopera.**

In tale contesto, i governi centristi favorirono la nascita delle **infrastrutture** necessarie allo sviluppo attraverso le industrie pubbliche.

L’Italia si dotò di linee ferroviarie e soprattutto di autostrade, la cui costruzione spinse ancor più le famiglie all’acquisto di automobili.

Proprio i **veicoli a motore** furono i segni più evidenti del nuovo benessere prodotto dal *boom:* prima gli *scooter*, poi la mitica **seicento.**

Nelle case degli italiani l’ambiente che cambiò di più fu la cucina. Vi entrarono i nuovi **elettrodomestici.**

Anche fare la spesa divenne più semplice: nel **1957,** a Roma, aprì il primo supermercato.

Gli italiani stavano meglio e volevano divertirsi, scoprirono così il grande **cinema** americano, proibito durante gli anni del fascismo.

Un altro fondamentale cambiamento nella vita degli Italiani fu rappresentato dalla **televisione**, la quale ha contribuito alla diffusione della lingua italiana e perciò all’unificazione culturale del Paese.

Ma non tutta l’Italia conobbe in quegli anni i benefici del *boom*.

Anzi si acrebbe in misura drammatica lo **squilibrio** già esistente tra il **Nord** e il **Sud** abbandonato alla sua condizione di secolare arretratezza.

Molte famiglie del Sud si videro costrette a **emigrare**, questa volta non all’estero, ma soprattutto verso le grandi città industriali del Nord.

Si sentiva l’esigenza di governare gli effetti di una trasformazione così tumultuosa, regolando i processi di sviluppo e correggendo gli squilibri economici e sociali.

Fu questa la sfida affrontata dai **governi di centro - sinistra**, basati cioè sulla collaborazione tra DC e PSI.

<aside>
👤 Nella DC si affermò la figura di **Aldo Moro**, segretario del partito che fu il principale interlocutore dei socialisti e il più deciso artefice del centro - sinistra.

</aside>

---

Il congresso DC che si svolse a *Napoli* nel **1962** vide affermarsi definitivamente la linea di Aldo Moro favorevole alla collaborazione con i socialisti nel governo del Paese.

**Amintore Fanfani** potè così costituire il suo IV governo.

Pur nella sua breve vita, il governo Fanfani riuscì a varare la **riforma della scuola** che istituì l’istruzione unificata ed elevò l’obbligo scolastico a 14 anni.

Nel **1963, Aldo Moro** formò il primo governo di cui facevano parte organicamente anche i socialisti.

Col passare degli anni lo slancio riformatore del centro - sinistra si venne sempre più attenuando, anche perchè crescevano i contrasti tra ip artiti di centro e il PSI sul modo di affrontare le difficoltà economiche.

In Italia la contestazione studentesca del 1968 passò dalle scuoole alle fabbriche, dando vita alle lotte operarie del cosiddetto “autunno caldo” che prese il via nel **settembre** del **1969** con lo sciopero nazionale dei metalmeccanici.

Si concluse in **dicembre** con la firma del nuovo contratto dei metlmeccanici, che rappresentava un’obiettiva vittoria per gli operai.

Praticamente tutte le richieste dei sindacati furono accolte.

Nel complesso le maggiori **organizzazione sindacali** riuscirono a dirigere le lotte e uscirono rafforzate da questa stagione.

La richiesta espressa dagli operai di una profonda trasformazione dei rapporti di lavoro nelle fabbriche venne accolta anche dal Parlamento.

Nel **maggio 1970** venne approvato lo **Statuto dei lavoratori:** una serie di articoli che riconsocevano i diritti fondamentali dei lavoratori.

---

il **12 dicembre 1969** a **Milano**, in **Piazza Fontana** scoppiò una bomba.

Iniziò con questo attentato il cupo periodo del **terrorismo politico** che insaguinò il Paese per tutti gli anni **Settanta.**

In quest’epoca la DC subì l’attacco contemporaneo dell’estremismo di destra e di quello di sinistra:

- **i terroristi di destra** si sentivano gli eredi della Repubblica di Salò: volevano riscattare la nazione che consideravano tradita da un falso parlamentarismo.
- **i terroristi di sinistra** invece si proclamavano eredi dei partigiani.

I **primi anni Settanta** furono dominati dalla violenza nera.

Senza dubbio le iniziative del terrorismo nero che hanno avuto maggiore impatto sull’opinione pubblica sono state le **stragi.** D’altronde proprio questo era l’obiettivo: seminare il terrore tra la gente.

Ricordiamo in particolare:

- Brescia, una bomba esplode durante un comizio
- Stazione di Bologna.

Gli attacchi terroristici si sommarono a violenti conflitti sociali.

I terroristi non hanno raggiunto il loro obiettivo finale: quello di spostare su posizioni autoritarie e antidemocratiche gli Italiani.

M anon si può dimenticare che m olte di queste stragi restano tuttora impunite.

Tra la fine degli anni Sessanta e i primi anni Settanta, nacquero in Italia vari gruppi di estrema sinistra che accusavano il PCI di aver runinciato alla prospettiva di una rivoluzione comunista.

Ritenevano che la rivoluzione fosse di fatto impedita dalle organizzazioni tradizionali della sinistra, tutte chiuse in una logica riformistica, burocratica.

Sono queste le idee di cui si nutrì il **terrorismo rosso;** coloro che scelsero la lotta armata provenivano del resto proprio dai gruppi politici più radicali.

Il gruppo più importante e tristemente famoso del terrorismo di sinistra furono le **Brigate Rosse.**

Nell’autunno del **1973** il segretario del PCI, Enrico Berlinguer pubblicò tre articoli che muovevano una riflessione articolata sul golpe cileno.

Le situazioni del Cile e dell’italia erano evidentemente molto diverse.

Tuttavia, secondo Berlinguer, anche in Italia esistevano forze che puntavano a risolvere la crisi del Paese attraverso una soluzione autoritaria.

Berlinguer conclude sostenendo che per affrontare i gravi problemi del Paese era urgente un “**compromesso storico”** tra i partiti che rappresentavano la grande maggioranza del popolo italiano.

La nuova strategia del “compromesso storico” mirava alla collaborazione di governo tra DC e PCI per superare la crisi della democrazia italiana.

Non si trattava solo di contrastare la violenza del **terrorismo** e il pericolo di una possibile **svolta autoritaria;** era anche necessario far fronte alla **crisi economica** che nel frattempo era maturata.

La proposta di Berlinguer trovò disponibilità in quella parte della DC che faceva capo ad **Aldo Moro**.

La politica moderata di Berlinguer portò nuovi consensi al PCI.

Nel **1975** le Sinistre ottennero un notevole successo e conquistarono il governo delle pricnipali città italiane.

Nel **1976** il PCI conseguì il risultato elettroale più significativo della sua storia.

La DC restò comuqnue il partito più forte con il 38,9% dei voti.

Nel **marzo 1978** Andreotti costituì un governo di **solidarietà nazionale** che godeva del voto favorevole del PCI e degli altri partiti di centro - sinistra.

Ma proprio nel giorno in cui il nuovo governo doveva ottenere la fiducia delle Camere, **16 marzo 1978**, le BR rapirono **Aldo Moro**.

Il cadavere venne ritrovato il **9 maggio**, 55 giorni dopo di prigionioa.

L’assassinio di Aldo Moro rappresentò il punto più alto dell’attacco terroristico alla democrazia.

Ma di fatto il terrorismo entrò in una fase di declino.
Meriti speciali ebbe in queste operazioni il generale *Carlo Alberto Dalla Chiesa.*
Ma il merito più grande fu del popolo italiano che non concesse il suo appoggio al terrorismo.

I terroristi così restarono isolati dalla popolazione.

La collaborazione tra DC e PCI declino rapidamente.

Il governo Andreotti infatti cadde nel **gennaio 1979**. 

Il PCI chiedeva di partecipare pienamente al governo con suoi ministri, ma la DC non accolse la richiesta comunista.

I governi ottennero importanti successi nella lotta contro il terrorismo e riuscirono anche a migliorare la situazione economica.

Altri provvedimenti non diedero invece i risultati sperati.

Tra questi la **riforma sanitaria del 1978** che garantì a tutti gli Italiani l’assistenza medica gratuita ma si rivelò costosa e poco efficiente.

La “solidarietà nazionale” terminò senza raggiungere l’obiettivo indicato con chiarezza da Moro: trasformare l’Italia in una democrazia pienamente occidentale, nella quale due schieramenti potessero liberamente alternarsi al governo.

La solidarietà nazionale terminò senza sbloccare la democrazione italiana e ciò condizionerà la vita politica del nostro Paese negli anni Ottanta.

---

# La crisi della prima Repubblica

Un altro pesante condizionamento sulla vita democratica italiana era imposto da potenti organizzazione criminali, come *Cosa Nostra*, la *camorra,* e la ‘*ndragheta*.

Per realizzare i loro affari queste associazioni mafiose intossicano tutti gli aspetti della vita democratica: ricorrono sistematicamente alla sopraffazione, calpestando idiritti dei cittadini: alterano i meccanismi del mercato, pretendendo il *pizzo.*

Questa era la situazione alla fine degli anni Settanta, quando la mafia scatenò un’offensiva terroristica senza precedenti contro le autorità dello Stato, una vera e propria intimidazione che culminò il **3 settembre 1982** con l’assassinio del generale **Dalla Chiesa.**

La reazione dello Stato fu incarnata dalla magistratura palermiatan, in particolare dal **pool antimafia** costituito dai giudici Giovanni Falcone e Paolo Borsellino.

Grazie alle rivelazioni di **Tommaso Buscetta** i giudici riuscirono a istruire il cosidetto **maxi processo** che si aprì a Palermo e che coinvolse 474 imputati.

Il 16 dicembre **1987** la sentenza deide loro ragione: oltre a 2000 anni di reclusione e multe per 11 miliardi di euro.

il **23 maggio 1992** il giudice **Giovanni Falcone** rimase vittima della **strage di Capaci**, a neanche due mesi di distanza toccò a **Paolo Borsellino.**

---

# Il mondo, l’Europa e l’Italia oggi

Con il crollo del comunismo e dell’Unione Sovietica la geurra fredda è veramente finita.

Ma la pace resta in molti casi un obiettivo ancora lontano.

Per questo vari commentatori hanno parlato del terzo dopoguerra come dell’**epoca del dirsordine mondiale.**

Il XXI secolo si apre con una guerra: l’11 settembre 2001 l’attacco alle Torri Gemelle di New York.

Molte delle guerre che si combattono oggi non sono guerre tradizionali.

Le guerre di oggi sono definite **guerre asimmetriche**.

Per definire quei conflitti in cui le forze che si combattono non sono simettriche, nel senso che non sono confrontabili per **strategie, organizzazioni militari, obiettivi** e **valori.**

Inoltre si tratta di **conflitti etnici**, per rivendicare il riconoscimento del proprio territorio, sono **guerre civili**, di stampo **politico-religiosoo**, coinvolgono più stati, sono combattute ad **armi impari** e anche da eserciti costituiti da civili o da **combattenti stranieri**, utilizzano il **terrorismo e la guerriglia**, si servono della **propaganda** o di interventi psicologici.

---

Dopo il crollo dell’URSS, gli Stati Uniti sono rimasti l’unica superpotenza del mondo non solo sotto il profilo militare ma anche per quanto riguarda l’economia.

Gli elettori statunitensi hanno espresso la loro volontò di cambiar pagina eleggendo nel 2008 il democratico **Barack Obama** che tra le varie riforme ha attuato quella sanitaria.

Tuttavia Obama non ha saputo risolvere la crisi meridionale e le eleizoni presidenziali del 2016 hanno così visto il ritorno alla presidenza dei repubblicani, con **Donald Trump**.

---

## L’unione Europea

Fino al **1973** facevano parte della CEE sei paesi, si parlava di **Europa dei Sei.**

Lo stesso anno si aggiunsero altri 3 paesi, divenne **l’Europa dei nove.**

Negli anni successivi sempre più paesi si unirono, fino al 2004, quando l’Unione Europa arrivò a contare **28 paesi membri.**

Nel febbraio **1992** è stato firmato il **Trattato di Maastricht.**

Questo trattato ha istituito l’**Unione Europea** grazie alla uqale tutti i cittadini degli Stati membri sono diventati cittadini europei.

Inoltre questo trattato ha deciso **interventi comuni** in campo culturale, educativo e sanitario.

Dal 1999 l’europa ha una moneta unica: l’Euro.

L’euro è stata una grande scommessa, non solo **economica** ma anche politica, per la prima volta nella storia una moneta non è stata coniata da uno stato ma è la strada con cui si cerca di “coniare uno Stato”.

Insieme alla grave crisi economica attraversa tra il 2008 e il 2014, gli Stati europei sono stati costretti ad affrontare anche il problema dell’immigrazione.
Dal 2011 milioni di **profughi** e persone in fuga dalla povertà hanno raggiunto l’Europa.

Di fronte a questa tragedia gli stati Europei hanno preso iniziative piuttosto contradittorie:

Italia e Grecia hanno accolto gli emigrati sul loro territorio.

I Paesi del Nord Europa hanno alternato una politica di accoglienza a rifiuti perentori e sistemi detentivi.

L’effetto combinato della crisi economica e dei nuovi flussi migratori ha messo a dura prova l’esperimento dell’Unione Europea.

Nel giugno **2016** il governo conservatore del **Regno Unito** ha dato ai cittadini la possibilità di esprimersi sulla permanenza nell’Unione Europea della monrachia britannica.

Il 51,9% degli elettori ha votato per la **Brexit**, sancendo il primo caso di uscita dall’Unione Europea.