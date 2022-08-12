# VTP (VLAN Trunking Protocol)

Il protocollo VTP consente di configurare le VLAN su un solo switch, che si occupa poi di distribuire le VLAN a tutti gli switch collegati

### Tipologie di switch

Si dovrà quindi creare uno switch server a cui si potranno collegare gli switch client per ricevere la configurazione delle VLAN, vi sono quindi 3 tipi di switch:

1. **Switch server** → gestisce le VLAN e le inoltra ai client
2. **Switch client** → ricevono semplicemente la configurazione o la possono richiedere
3. **Switch transparent** → ricevono la configurazione ma non la impostano su se stessi, la trasmettono ad altri switch client collegati e basta (tipo un repeater)

### Collegamento degli switch

È necessario impostare un VTP **domain** ed una VTP **password** sul server che i client dovranno utilizzare per accedere alle informazioni del server e quindi alle configurazioni delle VLAN.

### Scambio di messaggi

I message tra switch client e server vengono chiamati **VTP Advertisement** e possono essere di 3 tipi: 

1. **Summary**: contengono il VTP domain ed il config revision. Sono inviati ogni **5 minuti** o subito in seguito ad una modifica.
2. **Subset**: contengono informazioni sulle VLAN → inserimento, cancellazione, modifica
3. **Request**: invitate ad un VTP server per richiedere l'invio di un messaggio Summary ed eventuali messaggi subset

### Config Revision

È un contatore che viene incrementato di 1 ogni qual volta si verifica una modifica relativa al VTP ed è inizialmente settato a 0.

Consente agli switch di determinare se le informazioni VTP memorizzate sono o meno aggiornate ed è fondamentale per la distribuzione e la sincronizzazione delle informazioni sulle VLAN.