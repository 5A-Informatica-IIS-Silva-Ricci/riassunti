# ACL Estese

Created: December 13, 2021 6:04 PM

### Come lavorano

Individuano il traffico in base ai **protocolli** TCP e UDP e ai **numeri di porta** sorgente e destinazione.

### Posizionamento

Il più vicino possibile alla sorgente da filtrare.

### Comandi

```bash
enable
conf t
# Creo le regole acl
access-list {id_acl} {permit/deny} {protocollo(TCP/UDP/IP)} IP_mittente WCM_mittente IP_destinatario WCM_destinatario {comando} (eq {numero_porta})
# setto l'acl sull'interfaccia
interface fa{numero}
ip access-group {id_acl} {in/out}
```