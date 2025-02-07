La bioinformatica è un campo interdisciplinare che fonde biologia e scienze computazionali per analizzare grandi quantità di dati biologici. L'**allineamento di sequenze** (SA) è uno strumento cruciale in questo campo per confrontare sequenze biologiche come DNA, RNA e proteine, al fine di identificare similarità strutturali e funzionali.

Gli algoritmi di allineamento possono essere classificati in base alla loro estensione come **allineamento globale**, che confronta l'intera lunghezza delle sequenze, e **allineamento locale**, che si concentra su regioni altamente simili.

Tra gli algoritmi classici di allineamento delle sequenze troviamo:

*   **Needleman-Wunsch**, per l'allineamento globale, utilizza la programmazione dinamica per trovare l'allineamento ottimale tra due sequenze.
*   **Smith-Waterman**, per l'allineamento locale, si concentra su segmenti altamente simili, ignorando le regioni meno rilevanti.
*   **Hirschberg**, una variante ottimizzata di Needleman-Wunsch, riduce il consumo di memoria, rendendolo adatto per sequenze molto lunghe.

Gli approcci algoritmici includono la **programmazione dinamica** e il **divide et impera**. La programmazione dinamica costruisce una matrice di punteggio per trovare l'allineamento ottimale. Divide et impera, utilizzato nell'algoritmo di Hirschberg, divide il problema in sottoproblemi per ridurre l'uso della memoria.

Le **penalità per i gap** sono importanti per l'accuratezza dell'allineamento. Le penalità affini, che distinguono tra l'apertura e l'estensione di un gap, offrono risultati più realistici rispetto alle penalità lineari.

Per migliorare l'efficienza computazionale, si utilizzano acceleratori hardware come **GPU** e **IPU**. Le GPU, con architettura CUDA, eseguono operazioni in parallelo. Le IPU, con architettura MIMD e memoria SRAM, migliorano l'efficienza nei calcoli irregolari.

Un algoritmo proposto utilizza GPU per ridurre la complessità temporale e spaziale, con una Foundation Matrix (FM) e una Traceback Matrix (TM) per memorizzare punteggi e direzioni. L'implementazione su IPU, come dimostrato dalle pipeline ELBA e PASTIS, offre accelerazioni significative nell'assemblaggio genomico e nella ricerca di omologia proteica.


Gruppo composto da:

-Marco Fusco

-Marco Palmisciano

-Vittorio Ciancio
