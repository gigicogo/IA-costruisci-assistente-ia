# Costruisci il tuo assistente IA

Una piccola web app per la **verifica finale del percorso formativo sull'intelligenza artificiale nella Pubblica Amministrazione**, pensata per i funzionari degli enti pubblici.

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


## Materiali didattici di riferimento

L'esercizio riprende i contenuti del percorso: scenario e limiti dell'IA, AI Act e Legge 132/2025, sicurezza e privacy, prompt engineering, checklist e tracciabilità, RAG e agenti, governance interna, oltre alle **Linee Guida AgID per l'adozione di IA nella PA (9 novembre 2026)**. I casi sono sintetici e inventati, e presuppongono sempre la verifica delle politiche e autorizzazioni dell'ente.

## Personalizzazione

Tutti i testi delle tappe sono raccolti nell'array JavaScript `stages` all'interno di `index.html`. Per modificare un caso si possono aggiornare titolo, descrizione, opzioni, soluzioni (`correct`) e punteggio (`points`). La somma dei punti delle sette tappe deve rimanere 100.

---

## 📄 Licenza e riuso

Puoi usare, copiare, modificare e condividere questo progetto, anche per attività formative, professionali e commerciali, senza chiedere un’autorizzazione preventiva.

Salvo diversa indicazione, il codice è distribuito con licenza [MIT](https://opensource.org/license/mit), mentre i testi e i materiali didattici sono distribuiti con licenza [Creative Commons Attribuzione 4.0 Internazionale](https://creativecommons.org/licenses/by/4.0/deed.it).

Nel riuso, conserva gli avvisi previsti dalla licenza MIT; per testi e materiali didattici, cita **Gianluigi Cogo**, inserisci un collegamento al progetto originale e alla licenza e indica eventuali modifiche. Gli eventuali materiali di terzi mantengono le rispettive licenze.

## 👤 Autore e contesto

**Gianluigi Cogo** — Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa, dell’innovazione e della comunicazione.

- 📮 Newsletter: [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 Blog: [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ YouTube: [youtube.com/@gigicogo](https://www.youtube.com/@gigicogo)
- 💼 LinkedIn: [linkedin.com/in/gigicogo](https://it.linkedin.com/in/gigicogo)
