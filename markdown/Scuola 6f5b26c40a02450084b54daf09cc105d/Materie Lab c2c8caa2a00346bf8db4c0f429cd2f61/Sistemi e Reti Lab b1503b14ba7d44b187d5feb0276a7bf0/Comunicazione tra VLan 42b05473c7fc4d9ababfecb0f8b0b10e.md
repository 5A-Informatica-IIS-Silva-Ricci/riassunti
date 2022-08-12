# Comunicazione tra VLan

Vi sono due modalità

- Router on a stick
- Inter VLan routing

# Router on a stick

### Configurazione interfaccia router

`enable`

`conf t`

`interface fastEthernet 0/0`

`no ip address` 

`no shutdown` → accendo la porta

`exit`

### Configurazione subinterface

`enable`

`conf t`

`interface fastEthernet 0/0.10` → selezione l'interfaccia virtuale (subinterface)

`encapsulation dot1Q 10` → specifica che deve supportare lo standard 802.1Q

`ip address 192.168.10.254 255.255.255.0` → specifico l'ip nella subinterface mentre l'interface 0/0 accetta tutti i pacchetti

*Per cancellare i setting di un interfaccia → **`no interface fastEthernet {numero}`***