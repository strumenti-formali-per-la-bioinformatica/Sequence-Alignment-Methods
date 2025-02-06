Gli algoritmi di allineamento delle sequenze biologiche, come DNA, RNA e proteine, sono fondamentali per identificare somiglianze e differenze genetiche. Algoritmi come Needleman-Wunsch, Smith-Waterman e Hirschberg utilizzano la programmazione dinamica per confrontare sequenze proteiche e trovare l'allineamento ottimale dividendo il problema in sottoproblemi indipendenti. Mentre Needleman-Wunsch è adatto per allineamenti globali, Smith-Waterman eccelle negli allineamenti locali, ma entrambi richiedono molta memoria. Hirschberg riduce il consumo di memoria per sequenze lunghe grazie a un approccio divide-et-impera. L'implementazione parallela su GPU e IPU offre un'efficienza computazionale superiore, riducendo i tempi di esecuzione e migliorando la gestione della memoria per dataset genomici complessi. Un nuovo algoritmo basato su GPU e IPU utilizza due matrici principali (Foundation Metric e Traceback Matrix) per ottimizzare il calcolo e ridurre i tempi di trasferimento dati.


Gruppo composto da:
-Marco Fusco|
-Marco Palmisciano:
-Vittorio Ciancio
