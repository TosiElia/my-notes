[[Gestione Memoria]]

Quando un programma sta per diventare processo, ossia richiede di essere caricato in memoria centrale (RAM) per essere eseguito, viene messo in una coda di entrata dalla quale verrà prelevato per essere collocato nella Reading List.
Perciò, durante la generazione del file eseguibile di un programma, il compilatore ed il linker che non sanno dove il programma o i dati verranno caricati, generano all’interno del programma dei collegamenti tra istruzioni e indirizzi relativi (indirizzi logici), mentre all’atto del caricamento vero e
proprio del programma questi indirizzi vengono trasformati in indirizzi assoluti.
Un codice con tali caratteristiche si chiama codice rilocabile