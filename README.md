Ho deciso di aggiungere un dialogo all'avvio del programma per renderlo migliore, offrendo più opzioni all'utente e maggiore chiarezza su ciò che può chiedere, dato che nel codice originale non era chiaro cosa fosse in grado di fare

Successivamente, ho corretto il codice alla linea 7, cambiando oggi = datetime.datetoday() in oggi = datetime.date.today(), poiché il primo non esiste

Poi, ho migliorato le risposte per le domande sconosciute, così da aiutare l'utente

Ho corretto il ciclo while True (linea 27) aggiungendo i due punti (while True:), in modo da far funzionare il ciclo che deve continuare fino a quando non viene soddisfatta una certa condizione; 
ossia chiede ripetutamente all'utente cosa vuole sapere, gestisce le risposte in modo che possa uscire, ricevere indicazioni se non inserisce nulla e ottenere assistenza per le domande valide

Ho aggiunto nella linea 4 .lower().strip() per far capire al codice che deve considerare sia lettere maiuscole che minuscole, oltre a rimuovere eventuali spazi vuoti

Le funzioni hanno la seguente funzione:

.lower(): Converte tutte le lettere in minuscolo, rendendo il confronto case insensitive
.strip(): Rimuove gli spazi vuoti all'inizio e alla fine della stringa

Ho anche migliorato gli input vuoti, dando una risposta più chiara
