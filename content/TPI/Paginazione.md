[[Memoria Virtuale]]

-  La memoria fisica viene suddivisa in blocchi di dimensione fissa detti frame pagine fisiche
-  Il programma è suddiviso in blocchi di uguale dimensione detti pagine o pagine logiche
-  Il numero di pagine logiche può differire dal numero di pagine fisiche
-  Se il numero di pagine logiche è minore del numero di pagine fisiche il programma potrebbe essere caricato tutto in memoria
-  Se la pagine logiche sono di più di quelle fisiche il programma viene caricato parzialmente

Per eseguire un programma, all’atto del caricamento iniziale, serve che nella memoria fisica venga caricata la prima pagina logica contenente la prima istruzione da eseguire. Quindi è sufficiente che nella memoria fisica
sia libera una sola pagina.

-[[Tabella delle pagine]]
-[[Rilocazione dei processi]]
-[[Page Fault]]