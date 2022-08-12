# Switch server e client per configurazione VLan

# Modalità degli switch

- Client
- Server
- Transparent → Ignora i server e le loro configurazioni

# Configurazione server

### 1. Visualizzo la configurazione dello switch

`show vtp status`

### 2. Configuro il server

`enable`

`conf t`

### 3. Setto il nome di dominio

`vtp domain SCUOLA`

### 4. Setto la password

`vtp password silvaricci`

### 5. Creo le VLan

[Configurazione VLan](Configurazione%20VLan%201c6a03100def48d9880940726723a96a.md)

### 6. [Imposto la modalità trunk per le porte interessate](Configurazione%20VLan%201c6a03100def48d9880940726723a96a.md)

# Configurazione client

### 1. Imposto la modalità client

`vtp mode client`

In automatico prenderà il *domain name* dallo switch server

### 2. Accedo al database del server

`vtp password silvaricci`

*Nota: il client non deve mai avere un 'configuration revision' più grande del server, in caso significa che son state fatte modifiche non dovute al client*

### 3. [Configuro le porte](Configurazione%20VLan%201c6a03100def48d9880940726723a96a.md)