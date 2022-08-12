# Datagram socket

Caratteristiche principali:

- Messaggi di dimensioni variabili
- No garanzia ordine ne arrivo di pacchetti
- Comunicazione inaffidabile

Permettono quindi di inviare da un socket a più destinazioni e ricevere su un socket da più sorgenti, viene chiamato modello "*molti a molti*" e ne fanno uso il protocollo **UDP**.

Operativamente:

- Il **server** si mette in attesa di ricevere dati
- Il **client** invia il pacchetto di dati al server e può mettersi in attesa di una risposta con le stesse primitive che ha utilizzato il server.

Il vantaggio sta nel rapido trasferimento di dati.

### Grafico

![Untitled](../../../Esame%20di%20Stato%20-%20Terza%20prova%20-%205Ai%20IIS%20Silva%20Ricci%20b95bc3258db24c59bbc78eba1beb1a1c/Untitled%2022.png)

### Implementazione in Java

[Socket/src/main/java/socket/datagram at main · 5A-Informatica-IIS-Silva-Ricci/Socket](https://github.com/5A-Informatica-IIS-Silva-Ricci/Socket/tree/main/src/main/java/socket/datagram)