[[Paginazione]]

Il SO mantiene una tabella delle pagine dove il numero di frame è
usato come indice della tabella.
Nella tabella sono memorizzate:
-  indirizzi fisici iniziali di tutti i frame presenti nella memoria fisica
- indicazione di pagina occupata / libera
- eventuale ID del processo caricato
Anche al processo è associata una tabella delle pagine, dove sono indicati quali segmenti di codice sono caricati in RAM e quali su disco. Tale informazione nella tabella è riportata attraverso l’uso di un bit, detto bit di validità, il cui valore è 1 se la pagina è in memoria, 0 altrimenti