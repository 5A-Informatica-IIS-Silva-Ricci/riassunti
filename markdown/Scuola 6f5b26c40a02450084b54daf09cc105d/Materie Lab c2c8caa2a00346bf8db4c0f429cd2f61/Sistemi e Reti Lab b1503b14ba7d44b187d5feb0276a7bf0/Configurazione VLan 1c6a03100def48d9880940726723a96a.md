# Configurazione VLan

# Passi operativi creazione e configurazione VLan

1. Assegnare gli IP ai diversi host (configurazione di rete completa)
2. Accedere allo switch (in CLI) modalità Administrator
3. Entrare nella modalità di configurazione dello switch
4. Creazione delle diverse VLan
5. Assegnare alle diverse porte la giusta configurazione (access [ indicando la VLan di appartenenza ] oppure trunk per altri utilizzi)
6. Test di funzionamento

### 2. Entrare in modalità administrator

`enable` —> In mod admin il nome dispositivo è seguito da #

### 3. Entrare in modalità configurazione

`conf t`

### 4. Creazione VLan

`vlan {VID}` (VID è il numero o ID della VLan)

`name {name}` (name è il nome della VLan)

`exit`

### 4b. Visualizzazione lista vlan

`exit` —> `show vlan` || `sh vlan`

### 4c. Eliminazione vlan

`no vlan {VID}`

### 4d. Modifica vlan

`vlan {VID} name {name}`

### 5. Configurare porte

Due tipi di configurazione:

- **Access** (usiamo questa)
- **Trunk**
- **Transparent**

Esempio configurazione porta

1. `interface fastEthernet 0/1` || `int fa 0/1`
2. `switchport access vlan 10`
3. `exit` || `ex`

Configurazione di un range di interfacce

1. `interface range fastEthernet 0/2-9` || `int range fa 0/2-9`
2. `switchport access vlan 10` (se la vlan 10 non esiste la crea in automatico con nome `VLAN00{numero}` [VLAN0010] )
3. `ex`

### 5b. Configurare porte in trunk

La configurazione trunk permette di far passare qualsiasi pacchetto dalla porta.

1. `interface fastEthernet 0/24`
2. `switchport mode trunk`

Quando impostiamo una porta trunk su uno switch viene impostata su trunk anche la porta collegata dell'altro switch.