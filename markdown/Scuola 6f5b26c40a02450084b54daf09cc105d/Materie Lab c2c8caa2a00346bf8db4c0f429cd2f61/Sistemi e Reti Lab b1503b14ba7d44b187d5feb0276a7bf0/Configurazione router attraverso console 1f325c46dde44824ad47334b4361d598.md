# Configurazione router attraverso console

Innanzitutto collegare con un **cavo console** (blu curvo) la porta **RS 232**del PC e la porta **console** del router.
Aprire poi il terminale dal PC, utilizzando le configurazioni di default, e si entrerà nella CLI del router.

## Comandi per la configurazione del router

E’ necessario usare il comando `enable` per entrare nella modalità **administrator**.

### Cambiare il nome

```bash
conf t
hostname nome_router
```

### Password per la console

```bash
conf t
line console 0
password password_console
login
```

### Password per la console in modalità administrator

```bash
conf t
enable password password_admin
enable secret password_crittografata
```

### Password per telnet

```bash
conf t
line vty 0 4 # Indica la quantità di host che possono connettersi tramite telnet contemporaneamente, in questo caso 5 utenti, da 0, 1, 2, 3, 4
password password_telnet
login
```

*ll telnet riesce a gestire al massimo 16 utenti in contemporanea.
Per accettare una sola connessione usare `0`.*

### Salvataggio configurazione

```bash
copy running-config startup-config
# oppure
write
```

### Visualizzare configurazione corrente

```bash
show running-config
```

### Impostare banner di accesso al router

```bash
conf t
banner motd $ messaggio
anche su
più linee
$
```