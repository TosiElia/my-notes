[[Paginazione]]

Mentre il SO si occupa di gestire le pagine, l’MMU provvede alla traduzione degli indirizzi da logici a fisici.
Per ottenere un indirizzo fisico si devono avere due elementi che vanno poi sommati insieme, ossia:
-  numero di pagina fisica (p)
-  spiazzamento nella pagina o offset (d)
Dal numero di pagina la MMU preleva dalla tabella delle pagine l’indirizzo fisico
(f) al quale deve essere sommato l’offset (d) Nella fase di traduzione  ll’indirizzo logico a quello fisico viene consultata la tabella delle pagine e se il bit di alidità è uguale a 0 si ha un page fault