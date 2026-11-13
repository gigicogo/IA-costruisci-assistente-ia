# Costruisci il tuo assistente IA

Una piccola web app per la **verifica finale del percorso formativo sull'intelligenza artificiale nella Pubblica Amministrazione**, progettata per i funzionari del Comune di Genova.

## L'idea

Invece di un test tradizionale a scelta multipla, il partecipante **assembla le condizioni per un assistente IA affidabile**. Il gioco presenta una missione unica: sperimentare un assistente che aiuti gli uffici a consultare regolamenti e circolari approvati.

Sette tappe, ciascuna con un problema concreto e un numero limitato di tessere da scegliere:

1. Obiettivi e indicatori di una sperimentazione.
2. Fonti documentali aggiornate e approccio RAG.
3. Scelta proporzionata tra assistente conversazionale, skill e agente.
4. Account autorizzati, minimizzazione, protezione dei dati.
5. Prompt strutturato, fonti e limiti.
6. Controllo umano effettivo, correzioni e verificabilità.
7. Ruoli, tracciabilità, segnalazioni e miglioramento continuo (PDCA).

## Come funziona

- Si sceglie una o due tessere per tappa, in base alla consegna.
- La verifica mostra subito **punti ottenuti, risposte corrette e una breve spiegazione**.
- Il punteggio massimo è **100**, ripartito tra le sette tappe (14+14+14+14+14+15+15).
- Le risposte sbagliate sono penalizzate: selezionare tutte le tessere non consente di ottenere punti.
- Al termine compare il riepilogo con punteggi e spiegazioni e si può scaricare un **report HTML stampabile** o un **riepilogo TXT**.
- Nome e cognome sono **facoltativi** e usati unicamente per il report sul dispositivo del partecipante.

Non è una verifica certificativa e il punteggio non è un giudizio giuridico sul caso.

## Privacy e requisiti tecnici

L'app è statica: **un solo file `index.html`**, senza dipendenze, backend, tracciamenti, cookie, API né servizi IA. Nessun dato viene trasmesso dal gioco. Funziona anche aprendo il file HTML in locale.

La grafica è responsive, le tessere sono pulsanti utilizzabili con tastiera, le scelte sono leggibili da tecnologie assistive e le risposte non richiedono drag-and-drop.

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository GitHub, per esempio `Costruisci-il-tuo-assistente-IA`.
2. Carica `index.html` e `README.md` nella radice del repository.
3. In **Settings → Pages**, scegli **Deploy from a branch**.
4. Seleziona branch `main` e cartella `/ (root)`, poi salva.
5. L'indirizzo sarà simile a `https://NOMEUTENTE.github.io/Costruisci-il-tuo-assistente-IA/`.

Non servono Node.js, build, token, chiavi API o configurazioni.

## Materiali didattici di riferimento

L'esercizio riprende i contenuti del percorso: scenario e limiti dell'IA, AI Act e Legge 132/2025, sicurezza e privacy, prompt engineering, checklist e tracciabilità, RAG e agenti, governance interna, oltre alle **Linee Guida AgID per l'adozione di IA nella PA (9 novembre 2026)**. I casi sono sintetici e inventati, e presuppongono sempre la verifica delle politiche e autorizzazioni dell'ente.

## Personalizzazione

Tutti i testi delle tappe sono raccolti nell'array JavaScript `stages` all'interno di `index.html`. Per modificare un caso si possono aggiornare titolo, descrizione, opzioni, soluzioni (`correct`) e punteggio (`points`). La somma dei punti delle sette tappe deve rimanere 100.
