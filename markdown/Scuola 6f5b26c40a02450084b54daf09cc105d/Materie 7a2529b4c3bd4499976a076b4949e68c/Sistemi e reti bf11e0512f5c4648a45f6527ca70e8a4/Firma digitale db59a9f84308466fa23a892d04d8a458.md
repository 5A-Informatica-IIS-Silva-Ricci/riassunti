# Firma digitale

La firma digitale garantisce le seguenti caratteristiche:

- **integrità** → assicura che il documento digitale non abbia subito modifiche successive alla sottoscrizione
- **autenticità** → garantisce l'identità del firmatario
- **non ripudio** → impedisce al sottoscrittore di negare la paternità del documento, dato che la firma digitale gli attribuisce piena validità legale

# Funzionamento

![Screenshot 2021-11-19 at 16.11.25.png](Firma%20digitale%20db59a9f84308466fa23a892d04d8a458/Screenshot_2021-11-19_at_16.11.25.png)

1. Si genera, attraverso funzioni hash, un riassunto del documento digitale chiamato *finger-print*
2. Viene crittografata la *finger-print* attraverso la chiave privata del mittente ottenendo la *firma digitale.*
3. Si allega la firma digitale al documento originale ed il tutto viene crittografato con la chiave pubblica del destinatario
4. Il destinatario decripta il messaggio con la sua chiave privata ottenendo il documento originale e la firma
5. Il destinatario utilizza la chiave pubblica del mittente per ricavare l'impronta digitale
6. Viene confrontata la finger-print con quella calcolata in modo autonomo dal destinatario

In genere per eseguire tutto ciò si viene forniti di un kit per la firma digitale composto da:

- dispositivo di generazione delle firme (smart card o pen drive)
- lettore di smart card / pen drive
- software di firma e verifica

Con il software di firma sarà possibile scegliere il certificato con il quale si intende firmare e selezionare il documento elettronico da sottoporre a firma digitale.
Al momento della firma del documento il software richiederà l'inserimento di un codice di protezione del dispositivo (PIN).

## Certificati

Il certificato di sottoscrizione rappresenta l'elemento chiave della firma digitale, non è altro che un file rilasciato dall'ente certificatore contenente tutti i dati identificativi del titolare.

L'Agenzia per l'Italia Digitale (AGID) si occupa di:

- offrire l'elenco di certificatori accreditati a cui si può richiedere la firma digitale
- sottoscrivere una lista dei certificati delle chiavi di certificazione
- definire le linee guida per la vigilanza sui gestori qualificati
- autorizza i certificatori a svolgere la propria attività conferendogli il ruolo di *certificatori accreditati*
- effettua vigilanza sui certificatori accreditati

### Il problema della condivisione della chiave pubblica

È necessario infatti certificare il mittente della chiave pubblica attivando una particolare procedura per la consegna della chiave pubblica: essa viene racchiusa all'interno di un certificato digitale che oltre a essa contiene le informazioni sul mittente. Questo certificato deve essere a sua volta validato da un ente certificatore (CA, Certification Authority) che garantisce l'identità del proprietario del certificato firmandone la chiave pubblica e privata con la propria chiave privata.

Il Certificato Digitale è quindi un documento informatico contenuto nella smartcard del titolare e firmato digitalmente dal certificatore ed i dati contenuti all'interno di esso sono i seguenti:

- dati del proprietario
- dati del certificato → data di scadenza e numero di serie del certificato
- dati della Certification Authority → ragione sociale certificatore, codice identificativo del titolare presso il certificatore e la firma digitale

Vi sono quindi due enti:

1. Registration Authority che identifica il richiedente di un certificato
2. Certification Authority che si occupa di gestire il ciclo di vita del certificato

Entrambi visto il loro ruolo chiave sono enti pubblici o privati accreditati.

### Richiedere un certificato digitale

1. Generazione della coppia di chiavi asimmetriche → le comunicazione tra CA e richiedente devono essere protette
2. Il richiedente comunica informazioni circa la propria identita1 alla CA
3. La Registration Authority inizia la verifica dei dati ricevuti
4. La CA genera il certificato e lo firma digitalmente con la propria chiave privata
5. Il certificato firmato viene inviato al richiedente