[[Partizione Fissa]]

Supponendo di dover schedulare un job piccolo, se ogni partizione piccola ma suffientemente grande da contenerlo avesse la coda piena, mentre la coda di una partizione più grande fosse vuota, il job verrebbe assegnato ad una partizione grande determinando così uno spreco di memoria

Per risolvere questo problema si fa uso di una singola coda di ingresso. Strategie possibili:
- si percorre la coda dall’inizio fino a individuare un job che possa essere contenuto nellapartizione libera
- si percorre tutta la coda individuando il più grande job che possa essere contenuto nella partizione libera. Inconveniente: i job più piccoli rischiano di essere discriminati.