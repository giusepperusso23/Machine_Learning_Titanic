# Machine_Learning_Titanic
Questo progetto mira a sviluppare un modello di machine learning capace di stimare la probabilità di sopravvivenza dei passeggeri del Titanic, basandosi sulle loro caratteristiche personali.

1. Caricamento e Analisi dei dati (EDA)
È stata condotta un’esplorazione completa del dataset per comprenderne la struttura, i tipi di variabili e la presenza di eventuali valori mancanti:
- Analisi dei valori mancanti nel dataset Titanic
- Analisi distribuzioni dei valori mancanti di "Age"
- Analisi della mortalità nel dataset Titanic
- Calcolo e stampa del numero e della percentuale di passeggeri deceduti e passeggeri sopravvissuti per ciascuna delle categorie specificate in una colonna del dataset Titanic
- Analisi della percentuale di decessi per fasce di età (ampiezza: 5 anni)
- Analisi della correlazione tra la variabile 'Survived' e alcune variabili selezionate del dataset Titanic (Age, Sex, Pclass, Embarked) e visualizza i risultati in una heatmap.
- Conclusione dell'EDA

2. Suddivisione del dataset

Successivamente, il dataset è stato suddiviso in train e test set per garantire una valutazione affidabile del modello. Il train test poi ulteriormente diviso in un nuovo train e in validation set.

4. Gestione dei valori mancanti nella feature «Age»

Fase cruciale. Riscontrati questi valori mancanti, per la variabile Age sono state confrontate diverse strategie: eliminazione dei record con valore mancante, imputazione con media, mediana e con valore arbitrario. Queste strategie sono state valutate attraverso la Logistic Regressione per definire una baseline.

6. Sostituzione dei valori mancanti

In base ai risultati della Logistic Regression sono stati sostituiti i valori mancanti nella colonna con il valore che corrisponde all’età media nel dataset.

6. Encoding variabili categoriche con One-Hot

Le variabili categoriche sono state poi codificate tramite One-Hot Encoding, rendendo il dataset pronto per l’addestramento del modello. Questo passaggio ha garantito che tutte le informazioni rilevanti fossero utilizzabili in modo coerente dall’algoritmo.

8. Implementazione Decision Tree Classifier

Infine, è stato implementato un Decision Tree Classifier. Il modello è stato addestrato e validato per determinare la profondità ottimale dell’albero, e le performance sono state valutate sul test set. I risultati finali hanno permesso di trarre conclusioni sulle capacità del modello di predire la sopravvivenza dei passeggeri:
- Conclusione








  
 
