[[content/index]]


Perché un processo possa risiedere in memoria centrale è necessario che lo spazio libero in
memoria sia:
- sufficientemente grande

- contiguo

Osservazioni:

- Oggi i programmi hanno dimensioni notevoli che superano la dimensione stessa della RAM

- Nei sistemi multiprocessing (sistemi che eseguono più processi usando due o più processori simultaneamente), il continuo caricamento e scaricamento dei programmi produce una frammentazione della memoria

- Non tutte le istruzione di un programma necessitano di essere caricate in memoria in quanto una buona parte di queste potrebbe non essere mai eseguita


