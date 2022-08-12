# INSERT

```sql
INSERT INTO Studente(matricola, università, nome, cognome) VALUES ('2142AB', 'Bocconi', 'Neri');
// or
INSERT INTO Studente('2142AB', 'Bocconi', 'Neri');
```

Se non specifico i parametri che voglio inserire devo inserirli tutti nell’ordine corretto, altrimenti specifico i parametri che voglio popolare e nell’ordine che preferisco.