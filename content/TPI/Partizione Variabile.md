[[Allocazione in memoria]]
Il partizionamente variabile è soggetto alla frammentazione esterna.
È possibile modificare dinamicamente sia il numero sia la dimensione di ogni singola partizione, ad esempio unendo blocchi contigui precedentemente distinti o suddividendone uno particolarmente sovradimensionato, a seconda delle richieste di spazio all’atto del caricamento dei processi Strategie di  allocazione dinamica della memoria centrale:

- First-fit: il gestore della memoria scandisce la tabella delle partizioni finché trova la prima zona libera abbastanza grande per contenere il processo. Metodo più veloce

- Best-fit: il gestore della memoria scandisce tutta la tabella delle partizioni e sceglie la zona libera più piccola sufficientemente grande da contenere il processo. Metodo più lento del first-fit e tende a lasciare zone di memoria troppo piccole per essere usate

- Worst-fit: sceglie la zona libera più grande

- Next-fit: cerca il primo spazio libero in grado di accogliere il processo partendo dallo spazio libero successivo all’ultimo processo allocato. Questo evita di allocare i processi tutti all’inizio della RAM