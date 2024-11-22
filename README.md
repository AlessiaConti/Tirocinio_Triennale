# Tirocinio_Triennale
Progetto di tirocinio svolto durante la Triennale di Elettronica all'Univpm.

## ***Ottimizzazione di una rete neurale ricorrente per la classificazione di pazienti affetti da Alzheimer tramite pre-processamento del segnale EEG***🧠

## Obiettivo
L’attività principale del tirocinio è stata quella di analizzare l’architettura di una rete neurale già implementata, per aggiungere un ulteriore preprocessing dei dati al fine di migliorare i risultati del modello. La rete è stata addestrata a distinguere un paziente sano da uno malato utilizzando un dataset ottenuto dalle analisi EEG di 35 pazienti, 20 affetti da Alzheimer e 15 sani. Questi dati provengono dal Dipartimento di Medicina Sperimentale e Clinica di Ancona. 

## Strumenti Utilizzati
- EDFbrowser
- Google Collaboratory
- Librerie di Python:
  - Numpy
  - Matplotlib
  - SciPy 
  - Scikit-learn*
  - TensorFlow
- EEGLAB
  - BioSignal Toolbox

_*La funzione principale presa da questa libreria è FastICA: un algoritmo veloce per eseguire l'analisi indipendente dei componenti (ICA, Independent Component Analysis), utilizzata per la pre-elaborazione dei segnali_


## Formato del dataset
Il dataset a disposizione è costituito dai segnali EEG di 35 pazienti, 20 affetti da Alzheimer (AD) e 15 sani (N). 
- I dati sono stati forniti in formato **EDF** (European Data Format), un formato utilizzato in ambito medico per lo scambio e l'archiviazione di segnali biologici.
- A partire dal formato EDF iniziale, è stato fatto un preprocessing iniziale in cui i dati sono stati salvati in formato **NPY**. Un file NPY è un file di array NumPy creato con la libreria NumPy di Python. Il file NPY memorizza tutte le informazioni necessarie per ricostruire correttamente l’array.
- Per ogni segnale, inoltre, è stato creato un file in formato **NPZ** (NumPy Zipped Data), cioè un file zip contenente più file NPY, uno per ogni array.
- Il passo successivo è applicare le funzioni dell’EEGLAB ai segnali del dataset per eliminarne le distorsioni, quindi è necessario convertire il formato NPZ in formati supportati dall’EEGLAB; per questo progetto sono stati scelti i formati **MAT** e **CSV**.

## Architettura del modello
## Risultati finali
![img1](https://github.com/AlessiaConti/Tirocinio_Triennale/blob/main/tab1.png)
![img2](https://github.com/AlessiaConti/Tirocinio_Triennale/blob/main/tab2.png)
