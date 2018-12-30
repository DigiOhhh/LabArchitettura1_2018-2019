# Sequenza di gray a 3 bit

*nome del file sorgente gray.circ*

Realizzare un contatore che segua ciclicamente una sequenza di Gray a 3 bit.

Nella sequenza di Gray ogni parola differisce dalla precedente per un solo bit. Ecco la sequenza su 3 bit.

	000 -> 001 -> 011 -> 010 -> 110 -> 111 -> 101 -> 100

- Stesso principio dei contatori modulo n: le transizioni da stato corrente a stato prossimo
condificheranno la sequenza di Gray

- Ad ogni cicli di clock, il registro a 3 bit passa dal valore i-esimo della sequenza al valore i+1-
esimo (tranne alla fine, dove dall’ottavo valore si ritorna al primo)
