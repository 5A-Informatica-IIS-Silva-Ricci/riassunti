# ACL (Access Control List)

## Cosa sono

Vengono usate sui router Cisco per l'implementazione delle tecnologie di firewalling.
Le ACL sono definite come insiemi di una o più regole, ognuna delle quali consente o nega il traffico in base ai parametri indicati.

Non appena un pacchetto in transito soddisfa una regola, le successive vengono scartate.
**L'ultima istruzione di una ACL è sempre una negazione implicita**: `deny ip any` per le ACL standard oppure `deny ip any any` per le estese che negano qualsiasi tipo di traffico.

## Applicazione su un interfaccia

Le ACL vanno applicate ad un interfaccia e va successivamente specificata una direzione:

- **Ingresso**: riferita al traffico in entrata sul router
- **Uscita**: riferita al traffico in uscita dal router

## Identificazione

Vi sono due tipologie di ACL a seconda di come vengono identificate:

- **Numbered**: con identificativo basato sui numeri
    - [ACL Standard](ACL%20(Access%20Control%20List)%200cbe0c1a1e5b45ea963a0f8e987e8c17/Tipologie%20di%20ACL%20db6f9228f30d405382276ba5faef1378/ACL%20Standard%20030b0281b6de4de683c62d3e6c9f4c06.md) : `1 → 99` e `1300 → 1999`
    - [ACL Estese](ACL%20(Access%20Control%20List)%200cbe0c1a1e5b45ea963a0f8e987e8c17/Tipologie%20di%20ACL%20db6f9228f30d405382276ba5faef1378/ACL%20Estese%20098b4b59babe4fd6a7e8863247c637a4.md) : `100 → 199` e `2000 → 2699`

## Wildcard mask

Una wildcard mask è formata da **32 bit** (come gli indirizzi IP).
Con `0` vengono indicati i bit da esaminare mentre con `1` quelli da ignorare.
Ad esempio, una wildcard mask `255.255.255.254` analizza solo l'ultimo bit degli IP.

Alcune wildcard mask particolari:

- `0.0.0.0` può essere sostituita con la parola `host`
- `255.255.255.255` può essere sostituita con `any`

In genere la WCM è la negazione della subnet mask, ad esempio se volessimo selezionare tutti gli host della rete `192.168.0.0/24` allora dovremmo usare come WCM `0.0.0.255`.

[Tipologie di ACL](ACL%20(Access%20Control%20List)%200cbe0c1a1e5b45ea963a0f8e987e8c17/Tipologie%20di%20ACL%20db6f9228f30d405382276ba5faef1378.csv)