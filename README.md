# turingmachine-nondeterministic-simulator

Implementazione in linguaggio C standard (con la sola libc) di un interprete di Macchine di Turing non-deterministiche, nella variante a nastro singolo e solo accettori.

Struttura del file di ingresso: prima viene fornita la funzione di transizione, quindi gli stati di accettazione e un limite massimo sul numero di passi da effettuare per una singola computazione (per evitare in maniera banale il problema delle macchine che non terminano), infine una serie di stringhe da far leggere alla macchina.

In uscita ci si attende un file contenente 0 per le stringhe non accettate e 1 per quelle accettate; essendoci anche un limite sul numero di passi, il risultato può anche essere U se non si è arrivati ad accettazione.
