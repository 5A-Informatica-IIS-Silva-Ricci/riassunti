# Esercizio laboratori

Gestione PC: configurazione hardware e installazioni software

Il nostro Istituto desidera memorizzare i dati che riguardano la configurazione hardware dei diversi PC (circa 200) e del software su di essi installato. L’obiettivo è tenere sotto controllo la complessa situazione e di utilizzare le informazioni raccolte in sede di programmazione didattica, gestione delle aree di progetto, organizzazione di corsi ..., per le quali è indispensabile conoscere quali strumenti hardware e software sono disponibili.

[Per rendere accessibili a tutto il personale queste informazioni, si prevede di realizzare un’interfaccia web che permetta di consultare il database da qualunque PC in rete, utilizzando il corrispondente link, all’interno della pagina dedicata alle strutture, raggiungibile dalla home page del sito dell’Istituto. L’utente generico può solo leggere il contenuto del database, mentre l’inserimento e la modifica dei dati sono effettuati con un’apposita applicazione dal personale dell’Ufficio Tecnico e/o dal Responsabile di rete.] [in laboratorio]

Ogni PC è individuato da un numero di inventario ed è caratterizzato dalla sua configurazione che comprende le dimensioni della RAM e della memoria cache, la capacità dell’Hard Disk… Se si tratta di un PC collegato in rete, interessa l’indirizzo IP e un codice interno attribuito dal gestore di rete, entrambi unici.

Occorre registrare, inoltre, quali sono le eventuali periferiche collegate al PC (lettore CD, lettore DVD, stampante, casse, scanner...). Anche le periferiche, come i PC, sono identificate da un numero di inventario.

I PC sono ubicati in laboratori per i quali vi è un responsabile (Insegnante Teorico o Tecnico Pratico). I laboratori fanno parte di settori che sono gestiti da un Assistente Tecnico. Responsabili ed assistenti tecnici fanno parte del personale della scuola.

Per quanto riguarda il software, interessa la casa produttrice e il nome (con eventuale versione/release) e la sua classificazione come Software di Base (Sistema Operativo), Linguaggio di Programmazione (da intendersi come Compilatore e/o Ambiente di Sviluppo per quel linguaggio), Software Applicativo per l’Ufficio (Word Processor, Fogli Elettronici, Gestori di Database...), Software Didattico (Dizionari ed Enciclopedie, Ipertesti e materiale multimediale),  Altro Software.

Per ogni installazione di software si memorizza la data in cui essa è avvenuta; quando il software viene "disinstallato" da una certa macchina si registra la data di rimozione.

Realizzare un progetto che risponda alle query seguenti

- Elenco alfabetico dei software con il numero di installazioni effettuate
- Elenco dei laboratori, con il responsabile, in cui è installato un certo software
- Elenco dei PC non collegati in rete
- Elenco dei responsabili con, in ordine e per ciascuno, l’elenco dei relativi laboratori che gestiscono.

# Ipotesi

- Non è necessario creare tipologie di computer, ogni computer ha le proprie specifiche.
- La data di disinstallazione di un software è inclusa nell’installazione per evitare ridondanza
- Il software indica una versione specifica, non essendoci bisogno di molte versioni diverse non è necessario creare entità software release ad esempio

# Diagramma E-R

![er.jpeg](Esercizio%20laboratori%20d90fd40254b24be9a9322857c618d5fa/er.jpeg)

# Modello logico

```sql

```