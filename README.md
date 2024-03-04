## PROGETTO D1 – PHM Asia Pacific 2023

I dati di telemetria che possono essere acquisiti in orbita sono ridotti a causa della limitazione nell'installazione di sensori e della capacità di downlink. Per ovviare a ciò la Japan Aerospace Exploration Agency (JAXA) ha sviluppato un simulatore numerico per prevedere la risposta dinamica di un sistema di propulsione di un veicolo spaziale con elevata precisione per generare un set di dati che copra le condizioni normali e tutti gli scenari di guasto previsti nelle apparecchiature reali.

L'obiettivo del progetto è sviluppare un modulo di diagnosi in grado di classificare anomalie, bolle, guasti alle elettrovalvole e casi anomali sconosciuti partendo dai dati generati dal simulatore semplificato del sistema di propulsione sviluppato con la collaborazione di JAXA.

Il progetto si svolgerà, indicativamente, secondo i seguenti punti:

- Leggere la documentazione disponibile nel sito di riferimento.
- Comprendere il dataset e importarlo in MATLAB.
- Strutturare il dataset affinché sia utilizzabile all’interno di Diagnostic Feature Designer, considerando le etichette che dovranno essere strutturate come richiesto dalla competizione.
- Selezionare un’eventuale frame policy.
- Calcolare lo spettro del segnale.
- Selezionare e calcolare le feature diagnostiche da utilizzare.
- Selezionare i classificatori da addestrare.
- Addestrare i classificatori con apposito dataset (“Training”).
- Testare il modulo di diagnosi con apposito dataset (“Testing”).
- Determinare le prestazioni usando una metrica opportuna.

Il materiale di riferimento iniziale consiste in:

- Sito di riferimento: [PHM Asia Pacific](https://phmap.jp/program-data/)
- Dataset