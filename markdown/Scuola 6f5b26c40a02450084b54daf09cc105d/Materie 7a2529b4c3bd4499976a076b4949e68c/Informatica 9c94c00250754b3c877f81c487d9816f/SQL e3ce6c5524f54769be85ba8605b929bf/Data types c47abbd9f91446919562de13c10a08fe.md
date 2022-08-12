# Data types

- `CHAR(n)`
    
    Stringhe a lunghezza fissa `n` max 255
    
- `VARCHAR(n)`
    
    Stringhe a lunghezza variabile, max `n`
    
- `TEXT`
    
    Stringhe più lunghe
    
- `BLOB`
    
    Era usato per i file ad esempio
    
- `INT(n)`
    
    `n` sta per la lunghezza in byte dell'intero
    
- `DATE`
- `TIME`
- `DATETIME`
    
    Serve anche il fusorario
    
- `TIMESTAMP`
    
    

---

## Note

- Differenza tra `VARCHAR` E `CHAR`:
    - `VARCHAR` definisce una stringa di un numero variabile di caratteri
    - `CHAR` definisce una stringa di un numero fisso di caratteri, quindi anche inserendo 4 caratteri in un `CHAR(10)` il dato occuperà 10 caratteri in memoria (Max 255).
    
    Se mischiamo i due tipi di variabili allora si perde l’ottimizzazione fornita dal `CHAR`.
    Esiste anche `TEXT` per testi lunghi.