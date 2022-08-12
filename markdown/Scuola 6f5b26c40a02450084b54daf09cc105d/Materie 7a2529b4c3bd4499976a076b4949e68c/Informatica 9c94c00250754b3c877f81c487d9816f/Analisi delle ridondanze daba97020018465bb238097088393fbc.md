# Analisi delle ridondanze

Ridondanza = presenza di un dato derivabile

## Tipologia ridondanze

- derivabile da operazioni tra attributi della stessa entità/relazione
    
    ![Untitled-2021-12-14-0956.png](Analisi%20delle%20ridondanze%20daba97020018465bb238097088393fbc/Untitled-2021-12-14-0956.png)
    
- derivabile da operazioni tra entità/relazioni diverse
    
    ![Untitled-2021-12-14-1000.png](Analisi%20delle%20ridondanze%20daba97020018465bb238097088393fbc/Untitled-2021-12-14-1000.png)
    
- derivabile da operazioni di conteggio
    
    ![Untitled-2021-12-14-1004.png](Analisi%20delle%20ridondanze%20daba97020018465bb238097088393fbc/Untitled-2021-12-14-1004.png)
    

## Presenza di ridondanze

**Vantaggi**: riduce al minimo gli accessi necessari per calcolare la variabile ridondante

**Svantaggi**: occupazione di memoria e aumento degli accessi per aggiornare il dato ridondante

---

# Esempio

![FC025F13-E855-4DA1-8AC4-BB30BC0D8866.jpeg](Analisi%20delle%20ridondanze%20daba97020018465bb238097088393fbc/FC025F13-E855-4DA1-8AC4-BB30BC0D8866.jpeg)

Op1: inserimento articolo venduto in presenza (500 volte al giorno)

Op2: stampa dati di tutte le fatture (totale compreso) (1 volta al giorno)

**Tavola dei valori**

| Fattura | E | 200 |
| --- | --- | --- |
| presenza | r | 50000 |
| Articolo | E | 10000 |

### Con ridondanza

**Op1**

| Tabella | Tipo | Frequenza | Accesso |
| --- | --- | --- | --- |
| presenza | r | 1 | W |
| Articolo | E | 1 | R |
| Fattura | E | 1 | R |
| Fattura | E | 1 | W |

**Op2**

| Tabella | Tipo | Frequenza | Accesso |
| --- | --- | --- | --- |
| Fattura | E | 200 | R |

**Totale → $(500*6R)+200R = 3200R$**

### Senza ridondanza

**Op1**

| Tabella | Tipo | Frequenza | Accesso |
| --- | --- | --- | --- |
| presenza | r | 1 | W |

**Op2**

| Tabella | Tipo | Frequenza | Accesso |
| --- | --- | --- | --- |
| Fattura | E | 200 | R |
| presenza | r | 50000 | R |
| Articolo | E | 10000 | R |

**Totale → $(500*2R)+60000R\approx61000$**

[Login](Analisi%20delle%20ridondanze%20daba97020018465bb238097088393fbc/Login%207d0132cd42fc4d94ae7f11cd27db36d7.md)