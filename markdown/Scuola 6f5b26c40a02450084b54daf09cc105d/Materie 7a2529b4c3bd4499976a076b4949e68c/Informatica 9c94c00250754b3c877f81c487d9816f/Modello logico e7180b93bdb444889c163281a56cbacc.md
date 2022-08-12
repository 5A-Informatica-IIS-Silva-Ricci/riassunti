# Modello logico

# Passare dal modello concettuale al modello logico

1. **Entità**
Devo eliminare tutti gli attributi composti
    
    ![Screenshot 2021-12-12 at 16.49.40.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_16.49.40.png)
    
    ```jsx
    Dipendente(matricola, nome, cognome, via, numero, città)
    ```
    
2. **Relazione n:n**
    
    ![Screenshot 2021-12-12 at 16.52.11.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_16.52.11.png)
    
    ```jsx
    Studente(matricola, nome, cognome)
    Materia(nome, descrizione)
    esame(matricola, nomeM, data, voto)
    	con v.i.r. di matricola con matricola di Studente
    	con v.i.r. di nome con nome di Materia 
    ```
    
3. **Relazione 1:n**

    
    ![Screenshot 2021-12-12 at 16.55.36.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_16.55.36.png)
    
    ```jsx
    Preside(cf, nome, cognome)
    Studente(matricola, nome, cognome, cf)
    	con v.i.r. di cf con cf di Preside
    ```
    
4. **Relazione 1:1**
    - con cardinalità minima = 1
        
        ![Screenshot 2021-12-12 at 17.00.09.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_17.00.09.png)
        
        ```jsx
        Presidente(codiceP, nome, cognome)
        Stato(nome, descrizione, codiceP)
        	con v.i.r. di codiceP con codiceP di Presidente
        ```
        
    - con cardinalità minima = 0
        
        ![Screenshot 2021-12-12 at 17.01.11.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_17.01.11.png)
        
        ```jsx
        Persona(cf, nome, cognome)
        Auto(targa, modello, cf)
        	con v.i.r. di cf con cf di Persona
        ```
        
        In questo caso abbiamo messo il cf di Persona all'interno di Auto poichè un'Auto ha sempre un proprietario. Se avessimo fatto il contrario il campo targa messo dentro a Persona sarebbe potuto risultare vuoto in alcune tuple.
        
    - con entrambe le cardinalità minime = 0
        
        ![Screenshot 2021-12-12 at 17.03.10.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_17.03.10.png)
        
        ```jsx
        Impiegato(codI, nome, cognome)
        Dipartimento(codD, nome, codI)
        	con v.i.r. di codI con codI di Impiegato
        ```
        
        Inserisco la chiave dentro Dipartimento poichè ipotizzo abbia meno tuple
        
5. **Entità deboli** (con chiave esterna)
    
    ![Screenshot 2021-12-12 at 17.06.32.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_17.06.32.png)
    
    ```jsx
    Università(nome, città)
    Studente(matricola, nomeUni, nome, cognome)
    	con v.i.r. di nomeUni con nome di Università
    ```
    
6. **Relazione IS-A**
Prima di passare al modello logico bisogna ristrutturare la relazione IS-A
    
    ![Screenshot 2021-12-12 at 17.07.57.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_17.07.57.png)
    
    1. **Ristrutturazione a superclasse** (entità padre)
    In questo caso rimane solo l'entità padre che assorbe gli attributi e relazioni delle entità figlie e aggiunge un campo per distinguerle
        
        ![Screenshot 2021-12-12 at 17.09.48.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_17.09.48.png)
        
    2. **Ristrutturazione alle sottoclassi** (alle entità figlie)
    In questa ristrutturazione rimangono solo le entità figlie che assorbono chiave e attributi dell'entità padre.
    **Importante:** in questo caso non posso usare la ristrutturazione alle sottoclassi poichè la mia relazione è di tipo **parziale** e questa ristrutturazione me la trasforma a totale. **Posso applicarla a relazioni IS-A totali**.
        
        ![Screenshot 2021-12-12 at 17.12.12.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_17.12.12.png)
        
    3. **Ristrutturazione ad entità deboli**
    La ristrutturazione ad entità deboli è sempre possibile ed è consigliabile utilizzarla quando le entità figlie sono fortemente specializzate.
        
        ![Screenshot 2021-12-12 at 17.14.43.png](Modello%20logico%20e7180b93bdb444889c163281a56cbacc/Screenshot_2021-12-12_at_17.14.43.png)
        

---

### Note

- **V.I.R. = Vincolo di Integrità Referenziale**