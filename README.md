# Sound-Event-Classification

## Group:

- ####  Chiara Auriemma &nbsp;([@ChiaraAuriemma](https://github.com/ChiaraAuriemma))<br> 10722613 &nbsp;&nbsp; chiara.auriemma@mail.polimi.it

- ####  Francesca Benesso &nbsp;([@fr-bn](https://github.com/fr-bn))<br> 10700542 &nbsp;&nbsp; francesca1.benesso@mail.polimi.it

- ####  Anna Fusari &nbsp;([@AnnaFusari](https://github.com/AnnaFusari))<br> 10561236 &nbsp;&nbsp; anna.fusari@mail.polimi.it

- ####  Filippo Marri &nbsp;([@filippomarri](https://github.com/filippomarri))<br> 10110508 &nbsp;&nbsp; filippo.marri@mail.polimi.it

## Checklist

### Macrotasks
1.  Lettura papers entro venerdì 23 Maggio 2025 ✅
2.  Pronti partenza via lunedì 26 Maggio 2025 14:30 - 18:30 - Implementazione caricamento e preparazione dataset ✅
3.  Checkino todos juntos 31 Maggio 2025 9:00 - 12:00 ✅
4.  Checkino todos juntos 4 Junio 2025 14:00 - 19:00 ✅
5.  Checkino todos juntos 5 Junio 2025 9:00 - 10:00 ✅

### Microtasks Da Completare
Cose da fare:
- ⁠runnare il notebook definitivo con la cross validation (da qui in poi non lo tocchiamo più)
- ⁠Scrivere la parte del paper relativa alla pipeline creata
- Provare diversi tipi di input (quelli proposti da José nel lab 1) , così magari abbiamo nel paper una nostra tabellina con i confronti con varie prove
- ⁠⁠Raccogliere tutte  le informazioni disponibili dai paper letti e dai tentativi fatti per scrivere una parte del paper dove facciamo vari confronti con altre architetture (stato dell’arte ma anche le nostre prove )
- Sistemare il github

### Microtasks Completate
- Lavorare su data augmentation: implementare funzioni per diverse tecniche e spiegare come e perché (Felipe y Francisca) 💣 
- Aggiungere cross-validation (i risultati dell'operazione son in X_train_fold, X_val_fold, y_train_fold, y_val_fold da uasare per il training e per la validation al posto delle rispettive variabili senza _fold). Per poter implementare la valutazione, serve il modello 🔝
- Lavorare su CRNN (Clarita y Añita) 🪩
- Invertire posizione di pre-processing (Felipe y Francisca) 💣 
Modelli:
    - Modello CNN - Primo modello da Chiarina: Añita (tempi biblici) ❌
    - Modello CRNN 2: troppo lento ❌
    - Modello CRNN 3: Pre-processing troppo lento ❌
- convertire il modello in pytorch e capire se runna in locale in un tempo umano ❌
- Capire se abbandonare definitivamente tensorflow ❌
- sistemare il notebook con il modello per avere la versione definitiva con tutta la pipeline da allegare al paper ✅

## Papers

**Analisi Dataset:**
- *ESC Dataset for Environmental Sound Classification* - proposto da Filippo (l'articolo spiega com'è fatto il dataset che useremo e perché questo dataset è valido per ciò che useremo. Inoltre compara le performance umane di riconoscimento dei suoni a quelle del loro algoritmo, per quanto semplice, di SEC)

**Data Augmentation e Pre-propcessing:**
- *Deep Learning-based Environmental Sound Classification Using Feature Fusion and Data Enhancement* - proposto da Francesca (usa il nostro dataset e da data augmentation)
- *Deep Convolutional Neural Networks and Data Augmentation for Environmental Sound Classification* - proposto da Filippo (punto interessante in cui spiega che fare data augmentation su alcune classi ne peggiora le prestazioni di classificazione)
- *A Software framework for musical data augmentation* - proposto da Filippo (software usato per audio data augmentation ma il paper è dell'1 quando non c'era nessuno)

**Baseline scelta (CRNN):**
- *Sound Event Detection: A tutorial* (è possibile prendere spunto per la costruzione di una baseline)
- Attention_based_convolutional_recurrent_neural_network_for_environmental_sound_classification (fa una proposta piú avanzata che potremmo usare per migliorare la baseline)
- Convolutional Recurrent Neural Networks for Urban Sound Classification using Raw Waveforms 

**Altre architetture:**
- *Sound Events Recognition and Classification Using Machine Learning Techniques* - fra (molto sintetico, utilizza il nostro dataset)
- *SOUND CLASSIFICATION SYSTEM USING MACHINE LEARNING TECHNIQUES* - proposto da Francesca (ha una tabella dei pro e contro che mi sembra ben fatta, ossia per ogni specifico task suggerisce quale tecnica utilizzare)
- *Formula-Supervised Sound Event Detection: Pre-Training Without Real Data* - prop da fra (non c'entra ma mi ha interessata ed è 2025)
- *ENVIRONMENTAL SOUND CLASSIFICATION WITH CONVOLUTIONAL NEURAL NETWORKS* (baseline di una CNN)
- Convolutional Neural Network based Audio Event Classification (proposta una CNN, interessante perché vengono confrontate piú versioni)

**Spiegoni teorici generali sul machine learning:**
- *An overview of machine learning classification techniques* - proposto da Francesca (può tornarci utile quando scriveremo il report per argomentare come mai abbiamo scelto un metodo piuttosto che un altro)
- *A Survey of Audio Classification Using Deep Learning* - proposto da Francesca (spiega i vantaggi di varie tecniche con riferimento all'audio classification)

**Review letteratura:**
- A Systematic Literature Review on Sound Event Detection and Classification (vengono confrontate piú soluzioni, utile per la ricerca di altri paper)
- *Automatic Recognition of Urban Enviromental Sound Events* - proposto da Filippo (datato, di interessante c'è che può tornare utile trattare il silenzio delle tracce audio come noise eliminandolo)
- Environmental Sound Classification: A descriptive review of the literature

**Da leggere:**
- *Audio Classification Method Based on Machine Learning* - proposto da Anna
- *Sound Classification Using Convolutional Neural Network and Tensor Deep Stacking Network* - proposto da Anna


## Branches




