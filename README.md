# Tirocinio_Triennale
Progetto di tirocinio svolto durante la Triennale di Elettronica all'Univpm seguita dalla prof. Falaschetti.

## ***Ottimizzazione di una rete neurale ricorrente per la classificazione di pazienti affetti da Alzheimer tramite pre-processamento del segnale EEG***

## Obiettivo
L’attività principale del tirocinio è stata quella di analizzare l’architettura di una rete neurale già implementata, per aggiungere un ulteriore preprocessing dei dati al fine di migliorare i risultati del modello. La rete è stata addestrata a distinguere un paziente sano da uno malato utilizzando un dataset ottenuto dalle analisi EEG di 35 pazienti, 20 affetti da Alzheimer e 15 sani. Questi dati provengono dal Dipartimento di Medicina Sperimentale e Clinica di Ancona. 

## Strumenti Utilizzati
- EDFbrowser: software che permette di visualizzare graficamente ed analizzare i file di archiviazione di serie temporali come EEG, EMG, ECG, ecc. In questo caso l’ho utilizzato per visualizzare i segnali EEG in formato EDF.  Una volta caricato il segnale EEG, l'applicazione offre informazioni sul soggetto, la data di registrazione e la durata, e consente di selezionare, aggiungere o rimuovere segnali. 
- Google Collaboratory: è un IDE che consente a qualsiasi utente di scrivere codice sorgente nel suo editor ed eseguirlo dal browser. Nello specifico, supporta il linguaggio di programmazione Python ed è orientato a compiti di machine learning. 
- Librerie di Python:
  - Numpy per eseguire calcoli numerici e manipolare array multidimensionali e matrici;
  - Matplotlib per la creazione di grafici; SciPy per il calcolo scientifico;
  - Scikit-learn per la realizzazione di modelli predittivi di machine learning. 
- EEGLAB 
