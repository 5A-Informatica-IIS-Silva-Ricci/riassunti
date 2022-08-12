# Esercitazione

> Il direttore di un’azienda di pubblicità, favorevolmente colpito dal successo delle
applicazioni di “social network” (FaceBook, MySpace, Twitter...) desidera creare una
comunità virtuale rivolta a dipendenti e collaboratori esterni, accessibile via web, di
supporto alla gestione di diversi progetti di marketing, basata su un sintetico e
immediato scambio di informazioni di tipo testuale.
Ogni progetto è caratterizzato da una descrizione sintetica, dalla data di inizio del
progetto e da un responsabile.
Dipendenti e collaboratori esterni sono associati a un certo progetto dal suo
responsabile, che attribuisce a ciascuno di essi una mansione (consulenza per il logo,
per lo slogan, per il testo, per la musica, per la grafica... oppure generica, intesa come
non specializzata).
Oltre ai consueti dati anagrafici, e ai recapiti telefonici e di e-mail, i dipendenti sono
caratterizzati da una matricola, mentre i collaboratori dalla loro Partita Iva.
Ogni utente della comunità ha una pagina personale cui accede dalla home page
dell’azienda, previa autenticazione.
Una pagina personale è costituita dall’elenco dei link dei progetti cui l’utente è stato
assegnato, ciascuno accompagnato dalla mansione che egli ricopre nel progetto.
Nella pagina personale è inoltre visibile la rassegna degli ultimi 10 messaggi ricevuti
relativi a qualsiasi progetto cui l'utente è associato, in ordine di data.
I messaggi hanno una dimensione massima fissata in 256 caratteri.
Cliccando sul link di un progetto si accede alla pagina con tutti i messaggi di quel
progetto. Questa pagina contiene un’area in cui è possibile scrivere un messaggio per
il progetto corrispondente.
> 

### Richieste

Il candidato, formulate opportune ipotesi, realizzi:

1. ** Un progetto di massima, che preveda l’acceso al sito sia dall’interno
dell’azienda sia dall’esterno, con indicazioni sulle misure di sicurezza da attuare;
2. Il disegno dei dati

(analisi, schema concettuale secondo il modello E/R e relativa documenta-
zione, eventuale trasformazione dello schema);

1. Uno schema logico relazionale del DB accompagnato da una istanza
(traduzione dello schema concettuale in uno schema relazionale equivalente, con
alcune righe significative per ogni tabella);
2. Uno schema fisico del DB
(creazione in SQL delle tabelle più significative);
3. L’implementazione in linguaggio SQL delle seguenti query:
a. Elenco degli utenti di un progetto dato, in ordine alfabetico
b. Elenco dei progetti di appartenenza di un utente dato
c. Elenco degli utenti di tutti i progetti di appartenenza di un utente dato,
in ordine di progetto e, all’interno di uno stesso progetto, in ordine
alfabetico.
d. Elenco dei progetti con il numero di utenti che ne fanno parte
4. Il progetto delle seguenti pagine web:
(disegno grafico della pagina con indicazione dei link
e delle eventuali query per ottenere i dati necessari)
6.1) Home page dell’azienda con login alla pagina riservata;
6.2) Pagina personale con l’elenco degli ultimi 10 messaggi provenienti da tutti i
progetti di cui fa parte, in ordine di data e ora;
6.3) Pagina del singolo progetto, accessibile da quella precedente, contenente
tutti i messaggi del progetto e una casella di testo per mandare un
messaggio al progetto stesso.
5. ** La codifica delle porzioni più significative di una delle pagine web (lato
server) descritte ai punti 6.2 e 6.3 e della relativa risposta.

# Documentazione

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| Login | E | Elenco di tutte le username e pw, che è presente in forma crittografata. |
| Lavoratore | E | Elenco di tutti i componenti che lavorano al progetto. Possono essere persone fisiche o società, collaboratori esterni o interni. Fanno parte anche i lavoratori che non fanno più parte dell’azendia. |
| Progetto | E | Progetti attivi e passati; il campo chiave a autoincrementale e la data di inizio è la data operativa del progetto, presa da sistema. |
| partecipano | R |  |
| Messaggio | E | Contiene tutti i messaggi relativi ai progetti, identificati da un campo autoincrementante, con data dal sistema. |
| Email | E |  |
| Telefono | E | Elenco dei numeri di telefono, senza distinzione tra cellulari e numeri fissi. |

# Interrogazioni SQL

```sql
SELECT l.codF, l.cognome, l.nome
FROM Progetto P JOIN partecipazione pa on p.codP=pa.codP JOIN Lavoratore l ON pa.cf = l.cf
WHERE pa.codP='input'
ORDER BY(l.cognome, l.nome)
```