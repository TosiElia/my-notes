[[Segmentazione]]

La memoria centrale fisica è divisa in segmenti fisici (frame) di dimensioni diverse, ognuno con un nome che lo individua (spesso un numero).
Lo spazio degli indirizzi di un processo è diviso in segmenti logici (segmenti):

-  un segmento è caricato in un frame di pari dimensione
-  i segmenti di un processo possono essere caricati in frame non contigui, mentre quelli non caricati sono conservati nell’area di swap (su disco)
- 
La traduzione degli indirizzi logici in fisici avviene attraverso la tabella dei segmenti dove:
- il numero di segmento è usato come indice
-  ogni voce contiene:
	– l’indirizzo base di segmento (indirizzo fisico di partenza)
	– limite del segmento (scostamento massimo nel segmento)
	
Segmentation fault: si verifica se un indirizzo fisico calcolato punta ad un segmento diverso dal segmento in uso.