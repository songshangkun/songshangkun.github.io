---
title: Informativa sulla privacy
---

# Informativa sulla privacy

**Ultimo aggiornamento:** 2026-11-12 · **In vigore dal:** 2026-11-12

## 1. Chi siamo

RomeoAI (l'«App») è un'app di lettura e studio che funziona in locale. Il titolare del trattamento dei tuoi dati personali è **songshangkun** («noi»), contattabile all'indirizzo: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Per qualsiasi domanda, richiesta o reclamo in materia di privacy, scrivici a **13808875@qq.com**.

## 2. In breve

- La tua libreria di lettura, i documenti importati, le note, i riassunti e le impostazioni restano **sul tuo dispositivo**. Non gestiamo account né server che memorizzano i tuoi dati di lettura.
- **Non vendiamo** i tuoi dati personali e **non** li usiamo per pubblicità comportamentale.
- Questa versione dell'App **non contiene SDK pubblicitari né di analisi** e **non prevede acquisti in-app**.
- L'App **richiede solo il permesso del microfono**, usato esclusivamente per l'input vocale facoltativo e le registrazioni delle note, trascritte **sul tuo dispositivo** dal modello di riconoscimento vocale in streaming. L'audio non viene mai caricato. Non vengono richiesti permessi per fotocamera, libreria foto o posizione. I documenti e le immagini vengono importati solo tramite il selettore file di sistema e l'OCR viene eseguito **interamente sul tuo dispositivo**.
- Le funzioni di IA vengono eseguite su un **endpoint LLM che configuri tu stesso** oppure con un **modello locale che scarichi sul tuo dispositivo** — vedi la sezione 4.

## 3. Informazioni che trattiamo

Poiché l'App funziona in locale, quasi tutte le informazioni non lasciano il tuo dispositivo.

### 3.1 Informazioni memorizzate sul dispositivo

| Contenuto | Finalità | Dove resta |
|---|---|---|
| Documenti importati (PDF, EPUB, Office, testo, immagini) e il testo estratto | Aprirli, impaginarli di nuovo e rileggerli | Sandbox dell'App (cartella di supporto) |
| Voci della libreria: titoli, formati, data di importazione, posizione di lettura | Mostrare la libreria e riprendere da dove avevi lasciato | Database sul dispositivo |
| Indice locale full-text/di ricerca e cache dei risultati IA (spiegazioni, riassunti, domande e risposte) | Cercare nei documenti ed evitare chiamate IA ripetute | Database e cartella degli indici sul dispositivo |
| Impostazioni di lettura e aspetto (tema, lingua, carattere, modalità di sfoglio, azioni rapide) | Ricordare le tue preferenze | Preferenze del dispositivo |
| Modelli vocali (TTS) scaricati | Leggere i documenti ad alta voce offline | Sandbox dell'App (cartella dei modelli) |
| Indirizzo dell'endpoint LLM, nome del modello e chiave API, se li configuri | Chiamare le funzioni di IA che attivi | Sul dispositivo, memorizzati in forma offuscata; non possiamo leggerli |
| Modelli di riconoscimento vocale (ASR), LLM locale ed embedding scaricati | Input vocale, domande e risposte offline e ricerca semantica | Sandbox dell'App (cartella dei modelli) |
| Registrazioni delle note, cronologia chat, riassunti e note condivise | Riascoltare le registrazioni e continuare a studiare | Database sul dispositivo e sandbox dell'App |

Non conserviamo copie di quanto sopra sui nostri server e non possiamo ripristinarlo per te. Effettua i tuoi backup.

### 3.2 Informazioni trattate solo quando usi una funzione specifica

- **File / Documenti (facoltativo).** Quando importi un documento o un'immagine, l'App legge solo i file che scegli nel selettore di sistema. Nulla viene caricato su un server da noi gestito.
- **Riconoscimento del testo sul dispositivo (OCR).** Le immagini e le pagine PDF scansionate vengono riconosciute localmente dal componente di riconoscimento testo di ML Kit sul dispositivo. Le immagini non lasciano mai il tuo dispositivo.
- **Sintesi vocale sul dispositivo (TTS).** I documenti vengono letti da modelli vocali che scarichi ed esegui localmente. Il testo non viene inviato da nessuna parte.
- **Input vocale e registrazioni delle note (facoltativo).** Quando detti testo o alleghi una registrazione a una nota, l'App usa il microfono e un modello di riconoscimento vocale in streaming che viene eseguito **interamente sul tuo dispositivo**. L'audio viene convertito in testo localmente e non viene caricato. Puoi rifiutare il permesso del microfono; lettura, IA e le altre funzioni continuano a funzionare.
- **Modelli sul dispositivo (facoltativo).** Puoi scaricare modelli di riconoscimento vocale, sintesi vocale, embedding e piccoli modelli linguistici (GGUF). Questi file sono memorizzati nella sandbox dell'App e vengono eseguiti localmente; il tuo testo e l'audio non vengono inviati a noi né a un fornitore di modelli.

### 3.3 Informazioni che lasciano il dispositivo

Solo nei seguenti casi:

1. **Elaborazione con IA (facoltativo).** Quando usi spiegazioni, riassunti, domande di approfondimento o azioni rapide con IA, il testo selezionato o l'estratto pertinente viene inviato all'**endpoint LLM che hai configurato** in Impostazioni → Servizio IA. Il destinatario è il fornitore che scegli; non lo gestiamo, non possiamo leggere l'indirizzo o la chiave che configuri e non conserviamo copia di ciò che invii. Consulta l'informativa sulla privacy di quel fornitore.
2. **Configurazione remota e distribuzione dei documenti.** L'App scarica file di configurazione, testi legali e l'elenco facoltativo di app consigliate dalle GitHub Pages dello sviluppatore, e modelli vocali, di riconoscimento vocale, di embedding e linguistici locali dal repository dei modelli (Hugging Face / hf-mirror). Queste richieste non contengono il contenuto dei tuoi documenti, la cronologia di lettura, audio o identificatori personali.
3. **Accessi di rete avviati da te.** Aprire un'immagine o un link all'interno di un documento non carica nulla di per sé; l'App non include componenti di navigazione, tracciamento o pubblicità.

## 4. Funzioni di IA, in parole semplici

- **Endpoint LLM configurato dall'utente (BYOK):** spiegazioni, riassunti, traduzioni e domande e risposte vengono prodotti inviando il testo selezionato all'**indirizzo e alla chiave LLM che inserisci tu stesso**. Il fornitore lo scegli tu: non lo gestiamo e non possiamo leggere l'indirizzo o la chiave che configuri. Consulta l'informativa sulla privacy e sulla conservazione di quel fornitore e non inviare tramite questo canale informazioni che ritieni riservate.
- **Modello LLM locale (facoltativo):** spiegazioni, riassunti e domande e risposte possono essere prodotti anche da un piccolo modello GGUF che scarichi ed esegui localmente. In questa modalità il testo resta sul tuo dispositivo e non viene inviato da nessuna parte.
- **Elaborazione sul dispositivo:** estrazione del testo, OCR, indicizzazione full-text e semantica, sintesi vocale, riconoscimento vocale e inferenza di modelli locali vengono eseguite localmente sul tuo dispositivo. **Queste funzioni non caricano i tuoi documenti, le tue immagini né il tuo audio.**

Puoi disattivare le funzioni di IA in qualsiasi momento; lettura, ricerca e ascolto offline continuano a funzionare.

## 5. Perché trattiamo le informazioni

Trattiamo le informazioni solo per: importare e mostrare i tuoi documenti; estrarre e impaginare il testo; consentirti di cercare, annotare e organizzare la libreria; eseguire l'OCR e la sintesi vocale che richiedi sul dispositivo; chiamare l'endpoint di IA che configuri; e mantenere l'App funzionante e sicura.

Non usiamo i tuoi documenti o la cronologia di lettura per addestrare modelli, profilarti o indirizzare pubblicità.

## 6. Terze parti che possono ricevere informazioni

| Destinatario | Riceve | Finalità |
|---|---|---|
| Il fornitore LLM che configuri | Il testo che invii per spiegazioni, riassunti o domande e risposte | L'elaborazione IA che richiedi |
| GitHub Pages / GitHub (sviluppatore) | Richieste di configurazione, testi legali e app consigliate (senza contenuto dei documenti) | Configurazione remota, distribuzione dei documenti e promozione delle app |
| Hugging Face / hf-mirror | Richieste di download di modelli vocali, di riconoscimento vocale, di embedding e LLM locali (senza contenuto dei documenti) | Distribuzione dei modelli per il dispositivo |

Ciascun destinatario è soggetto alla propria informativa sulla privacy. Non vendiamo né affittiamo dati personali a nessuno.

## 7. Per quanto tempo conserviamo le informazioni

I tuoi documenti, indici, note, cache IA e impostazioni restano sul dispositivo finché non li elimini, non rimuovi il documento dalla libreria o non disinstalli l'App. Eliminare un documento dalla libreria rimuove la sua voce, il file originale e le voci dell'indice. La disinstallazione rimuove tutto definitivamente; non conserviamo copie e non possiamo recuperare nulla.

Il contenuto che invii al fornitore LLM configurato viene conservato secondo la politica di conservazione di quel fornitore.

## 8. Sicurezza

I tuoi dati sono memorizzati nella sandbox dell'App, protetti dalla sicurezza del dispositivo (codice di accesso, cifratura del disco). L'indirizzo e la chiave del LLM sono memorizzati in forma offuscata sul dispositivo e non vengono mai trasmessi a noi. Nessun metodo di conservazione è perfettamente sicuro: proteggi il dispositivo ed effettua backup.

## 9. Minori

L'App non è destinata ai minori. Non raccogliamo consapevolmente dati personali di minori al di sotto dell'età del consenso digitale prevista nella loro giurisdizione (13 anni negli Stati Uniti, 16 in gran parte del SEE e secondo le norme locali altrove). Se ritieni che un minore ci abbia fornito informazioni, contattaci e ti aiuteremo a rimuoverle.

## 10. I tuoi diritti

I tuoi diritti dipendono dal luogo in cui risiedi. Ovunque tu sia, puoi in qualsiasi momento: rifiutare o revocare i permessi facoltativi; eliminare documenti e i loro dati dall'App; smettere di usare le funzioni di IA; o inviarci una richiesta.

Poiché i tuoi dati sono locali, il modo più rapido per esercitare accesso, rettifica, portabilità o cancellazione è direttamente nell'App.

## 11. Modifiche a questa informativa

Possiamo aggiornare questa informativa. In tal caso modifichiamo la data sopra indicata e, per modifiche sostanziali, ti informiamo nell'App. Continuare a usare l'App dopo un aggiornamento significa accettare l'informativa revisionata.

## 12. Contatti

Domande e richieste sulla privacy: **13808875@qq.com**
Indirizzo postale: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**
