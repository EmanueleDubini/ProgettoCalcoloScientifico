# Progetto Calcolo Scientifico

Questo progetto ha lo scopo di studiare e confrontare l'implementazione del metodo di Choleski per la risoluzione di sistemi lineari su matrici sparse, simmetriche e definite positive. Il confronto avverrà tra l'implementazione in MATLAB e in ambienti open source su Windows e Linux.

## Contenuto delle Sottocartelle

### 1. ProgettoCalcoloScientifico_Matlab
Questa cartella contiene i file delle matrici e gli script necessari per eseguire il progetto utilizzando MATLAB.

### 2. ProgettoCalcoloScientifico_EJML
Questa cartella conterrà l'implementazione del progetto utilizzando una libreria open source EJML, in ambiente Windows e Linux.

### 3. ProgettoCalcoloScientifico_Python
In questa cartella troverai l'implementazione del progetto in Python, utilizzando una libreria open source di tua scelta.

### 4. ProgettoCalcoloScientifico_R
Qui saranno presenti i file necessari per eseguire il progetto in R, utilizzando una libreria open source a tua scelta.

## Matrici Analizzate
Le matrici simmetriche e definite positive considerate per questo progetto provengono dalla SuiteSparse Matrix Collection. Puoi trovare tutte le matrici collegandoti a [questa pagina](https://sparse.tamu.edu/). Le matrici specifiche che analizzeremo sono:
- Flan 1565
- StocF-1465
- cfd2
- cfd1
- G3 circuit
- parabolic fem
- apache2
- shallow water1
- ex15

## Confronto
Il confronto tra MATLAB e la libreria open source selezionata avverrà in termini di tempo, accuratezza, utilizzo della memoria, facilità d'uso e documentazione. Sarà effettuato su entrambe le architetture Windows e Linux sulla stessa macchina.