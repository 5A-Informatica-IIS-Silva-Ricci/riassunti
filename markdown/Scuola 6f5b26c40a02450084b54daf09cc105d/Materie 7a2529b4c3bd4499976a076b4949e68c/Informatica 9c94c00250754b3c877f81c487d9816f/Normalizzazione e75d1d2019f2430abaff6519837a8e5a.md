# Normalizzazione

## 1a Forma Normale (1NF)

Ogni attributo è espresso in forma atomica, non ulteriormente scomponibile.

## 2a Forma Normale (2NF)

→ Prerequisito 1NF

Ogni attributo non chiave dipendono funzionalmente dalla chiave intera e non da una parte di essa.

= attributi che dipendono da una parte della chiave soltanto e non da essa intera

## 3a Forma Normale (3NF)

→ Prerequisito 2NF

Ogni attributo non chiave dipende dalla chiave in forma diretta e non transitiva.

## Normalizzazione di Boyce-Codd

> Dipendenza funzionale: vincolo di integrità che esprime una dipendenza di tipo funzionale tra attributi di una relazione (relazione = tabella generica)
> 

| Matr | Nome | Cognome | Materia | Docente | Vot |
| --- | --- | --- | --- | --- | --- |

**Dipendenze**:

- Matr → nome + cognome
- Materia → docente
- Matr, materia → voto

> Una relazione r è nella forma normale di Boyce-Codd se per ogni dipendenza funzionale
x → y, x è chiave
>