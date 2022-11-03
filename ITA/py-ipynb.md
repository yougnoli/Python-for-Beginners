Python e' uno tra i linguaggi piu' utilizzati al mondo per moltissimi scopi:
- sviluppo applicazioni desktop
- calcolo scientifico
- machine learning

Python e' un linguaggio **interpretato** che ,a differenza di un linguaggio compilato, il codice non viene direttamente compilato in un file eseguibile (file *.exe* di Windows), ma viene interpretato da un altro software detto **interprete**, che poi lo esegue. Questo vuol dire che qualsiasi codice Python puo' essere eseguito su qualsiasi sistema operativo ameno che sia presente l'interprete.

**Python** e' un linguaggio creato alla fine degli anni '80 da Guido van Rossum. Uno script Python ha estensione *.py* e contiene una lista di comandi eseguiti in ordine. Viene eseguito dall'inizio alla fine e mostra l'output.

**IPython** e' un terminale di linea di comando interattivo per Python, creato nel 2001 da Fernando Perez. IPython e' una comoda interfaccia al linguaggio Python. Con IPython generalmente si scrive un comando alla volta e si ha il risultato istantaneamente. 
Nel 2011 IPython ha introdotto un nuovo strumento chiamato **Notebook**. I Notebook offrono la possibilita' di scrivere codice dentro alle celle e di salvare in memoria le variaibili create. 

Il modo piu' semplice per iniziare con i Jupiter Notebook e' di installare **Anaconda**. Anaconda è la distribuzione Python più utilizzata per l’analisi dei dati e viene fornita con tutte le librerie e gli strumenti più popolari, tra cui le librerie Python NumPy, Pandas e Matplotlib. 

### Interpretato vs Compilato
Affinche' le istruzioni di un programma scritto possono essere comprese da un computer o da un processore, il *codice sorgente* deve essere prima convertito in una forma *leggibile* dalla macchina. A seconda del linguaggio di programmazione questa operazione viene eseguita da un **compilatore** o da un **interprete**.

- **Interprete**: programma che elabora il codice sorgente mentre questo e' in esecuzione e funge da **interfaccia** tra quel codice e la macchina. Un interprete procede riga per riga del codice in modo tale che tutte le istruzioni siano lette e preparate una dopo l'altra per la macchina. Gli interpreti utilizzano delle **librerie** per elaborare il codice sorgente: una volta che una riga del codice sorgente e' stata convertita nelle corrispondenti istruzioni leggibili dalla macchina, viene inviata alla macchina stessa. Il processo di **conversione** non e' completato fino a quando *tutto* il codice non e' stato interpretato ed e' **interrotto** solo quando si verifica un errore durante l'**elaborazione** (cosa che semplifica la gestione degli errori, perche' la linea di codice che contiene gli errori vine identificata non appena si verifica l'errore). L'esecuzione del codice e' strettamente dipendente dalla presenza dell'interprete.

- **Compilatore**: programma che traduce l'intero codice sorgente nel linguaggio macchina (eseguibile), *prima* che questo sia eseguito. La procedura di traduzione e' dell'intero codice cosi' come la visualizzazione degli errori avviene dopo la compilazione completa. L'eseguibile prodotto dal compilatore puo' essere trasferito da una macchina all'altra (a parita' di sistema operativo) e l'esecuzione e' molto veloce.


#### IDLE
Lanciare un comando Pyton dalla linea di comando equivale ad utilizzare l'**interprete interattivo** (3 caratteri di maggiore >>>). L'interprete interattivo e'in grado di leggere e valutare le espressioni inserite dall'utente, ma anche di eseguire script (*.py*) contenenti istruzioni Python.

**Cosa succede quando viene eseguito uno script?** Il codice sorgente viene trasformato in *bytecode* (file con estensione *.pyc* o *.pyo*) utilizzando un apposito interprete noto come Python Virtual Machine.
![image](https://user-images.githubusercontent.com/77077281/199716524-a7e2c3c0-bdb0-4c7b-a55c-ac8f12f706bd.png)

Gli IDLE (**Integrated Development and Learning Environment**) sono degli ambienti dove e' possibile modificare, eseguire e debuggare programmi Python in un'unica interfaccia. E' quindi un ambiente dove e' presente sia l'editor che l'interprete.
