# Versioni di Edge Journal

Ogni aggiornamento lascia una copia completa del journal nella cartella [`versioni/`](versioni/), così si può sempre tornare a una versione precedente.
I dati (trade, impostazioni, screenshot) stanno su Supabase e non cambiano quando si cambia versione del codice.

## v1.5 — 25 novembre 2026 · [`versioni/index-v1.5.html`](versioni/index-v1.5.html)
- Nuova barra dei filtri sempre visibile su Dashboard, Trade, Report e Insights: periodo con un tocco (questa settimana, questo mese, ultimi 3 mesi, tutto, date a scelta), filtri attivi come etichette che si tolgono con la ×, numero di trade sempre in vista
- "+ Aggiungi filtro" con i filtri divisi per gruppo: Quando (giorno, sessione, ora), Setup (griglia, conferme, tipo di target, ingresso, direzione), Esecuzione (regole, errori, voto), Testa (check pre-sessione, emozione, news), Risultato, Versione. Più valori dello stesso filtro valgono come "oppure"
- Filtri salvati con un nome, sincronizzati su tutti i dispositivi; ogni dispositivo ricorda gli ultimi filtri usati, separati per Live e Backtest
- Report unificato al posto dei riquadri: Sintesi in parole, mappa "Dove rendi meglio e peggio" (verde/grigio/corallo rispetto alla tua media, più tenue se ci sono pochi trade, tocca per i dettagli e "Vedi questi trade"), barre "Le tue scelte di gestione e le regole" (a sinistra ti costa, a destra ti aiuta)
- Nuova scheda Confronto nei Report: scegli due casistiche (A e B, oppure A contro il resto dei trade) e vedi trade, win rate, risultato medio, R totali, profit factor, quote a breakeven, a stop e con errori, con un verdetto in parole e la sua affidabilità
- Clic su un giorno del calendario: apre i trade di quel giorno usando il filtro per date

## v1.4 — 25 novembre 2026 · [`versioni/index-v1.4.html`](versioni/index-v1.4.html)
- Nuova icona: "E" con una linea che sale (logo, icona della Home dell'iPhone e della scheda del browser). La vecchia icona è salvata in `versioni/icon-v1.3.png`
- Ottimizzato per il computer: usa tutta la larghezza fino a 2200 pixel; sopra i 1600 pixel gli 8 indicatori stanno su una riga e i grafici sono più alti
- Lista dei trade come tabella sugli schermi da 1000 pixel in su (lista attuale sul telefono)
- Form del trade più largo (fino a 1060 pixel) sopra i 1280 pixel, con la griglia su due colonne e le sezioni corte affiancate
- Telefono invariato

## v1.3 — 25 novembre 2026 · [`versioni/index-v1.3.html`](versioni/index-v1.3.html)
- Tolta l'azione della settimana dai Report
- Tolto il campo Regime (form, filtri, report, scheda del trade)
- Checklist diventata "Regole di esecuzione": 5 regole tecniche con casella, più 2 controlli automatici (rischio entro il limite, stop uguale al piano). Nei Report, regola per regola, se rispettarla ti fa rendere di più
- Errori ridotti a 8, in italiano semplice; i vecchi errori dei trade salvati vengono tradotti nei nuovi nomi
- Regole ed errori mostrati come righe con casella, leggibili anche con frasi lunghe

## v1.2 — 24 novembre 2026 · [`versioni/index-v1.2.html`](versioni/index-v1.2.html)
- Report a verdetti: il tuo vantaggio, cosa fare di più, cosa evitare, come gestisci il trade, la tua testa, azione della settimana. Ogni verdetto ha un'etichetta di affidabilità (Indizio, Probabile, Confermato); i numeri sono nei "Dettagli"
- Confronto con l'alternativa per breakeven dopo il TP1, chiusure manuali e trailing, parziali o tenere tutto, stop troppo stretto
- Tipo di target per ogni TP (struttura, liquidità responsabili, primo arrivo) e verdetto su quale viene raggiunto più spesso
- Tipo di ingresso (pendente sulla zona o a mercato sul trigger)
- Domanda facoltativa "dopo la tua uscita" con regola fissa: si guarda solo quale livello il prezzo tocca per primo
- Escursione dei trade in pips da MAE e MFE (valori tipici, cioè mediane), con il valore del pip nelle Impostazioni
- I vecchi report con i numeri restano in "Tutti i dettagli con i numeri"

## v1.1 — 23 novembre 2026 · [`versioni/index-v1.1.html`](versioni/index-v1.1.html)
- Bozze automatiche del form, con "Riprendi / Scarta"
- Modulo rapido per il backtest (risultato dai prezzi in R, "Salva e nuovo")
- Simulazione Monte Carlo nei Report, con rischio massimo consigliato
- Tabella mese per mese nei Report
- Check pre-sessione giornaliero collegato alla conferma "Stato personale conforme"

## v1.0 — 23 novembre 2026 · [`versioni/index-v1.0.html`](versioni/index-v1.0.html)
- Prima versione online con Supabase: login con email e password, database privato, screenshot privati
- Tutte le funzioni dell'artefatto fino alla griglia delle 8 conferme
