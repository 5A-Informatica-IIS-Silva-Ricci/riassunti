# ACL Standard

Created: December 13, 2021 6:04 PM

### Dove lavorano

Individuano il traffico solo in base all'IP sorgente.

### Posizionamento

Il più vicino possibile alla **destinazione**.

### Comandi CLI

```bash
enable
conf t
# creo una regola
access-list {id_acl} {deny/permit} IP_sorgente WCM
# setto l'acl sull'interfaccia
interface fa{numero}
ip access-group {id_acl} {in/out}
```