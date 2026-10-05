---
title: Come trovare e verificare un codice guasto di un elettrodomestico
description: Il codice sul display è metà della risposta. Dove i produttori nascondono le tabelle e come incrociare forum e documentazione di servizio.
---

Il codice sul display è soltanto metà della risposta: conferma che la macchina ha rilevato un'anomalia, ma dice raramente quale pezzo comprare. Un codice è la descrizione di un sintomo scritta dal programmatore della scheda di controllo, e la stessa scheda che individua un guasto può anche riferirlo in modo fuorviante. Prima di ordinare alcunché ti serve il significato per marca, tipo di elettrodomestico e modello esatti, ricavato da più di una fonte.

## Gli elenchi ufficiali esistono, ma sono sepolti o assenti

La prima sorpresa è scoprire quanto spesso un elenco ufficiale non esista affatto, oppure sia nascosto dove nessun proprietario guarda.

- Certi marchi non pubblicano nulla. Le lavastoviglie GE mostrano codici C, H2O e 888, ma GE non ospita una pagina ufficiale dei codici errore e il vuoto lo riempiono i siti di riparazione: il codice 888 su una lavastoviglie GE indica un guasto alla scheda di controllo, cosa che dal sito del produttore non scoprirai.

- Certi marchi dividono l'informazione in due strati. Le macchine De'Longhi mostrano per lo più parole come General Alarm, mentre i modelli più recenti registrano anche codici numerici come 1101 o 1512 che normalmente vedono soltanto i tecnici; i due livelli stanno insieme nella [pagina De'Longhi sul General Alarm e i codici numerici](https://it.codefixcoffee.com/delonghi/magnifica-dinamica/general-alarm-code-1101-1512/).

- Certi marchi pubblicano solo il sottoinsieme gentile. Philips elenca per le proprie macchine da caffè un piccolo gruppo di codici risolvibili dall'utente e instrada tutto il resto verso il supporto, anche quando le cause dei codici di servizio sono identificabili.

- Quando un manuale contiene una tabella, di solito sta in fondo, nel capitolo sulla risoluzione dei problemi: una riga per codice, senza nomi di componenti e senza procedure di riparazione.

L'informazione quasi sempre esiste: bisogna solo andare oltre al pieghevole di avvio rapido.

## Verificare un codice come farebbe un tecnico

### Trascrivi esattamente ciò che compare sul display

Annota la stringa esatta, il tipo di elettrodomestico, il numero di modello completo letto dalla targhetta e il momento in cui il codice compare. Una sola cifra letta male ti spedisce nel sottosistema sbagliato. Su un piano cottura o un forno Samsung, per esempio, SE indica un tasto bloccato nella membrana del touchpad, come spiega la [nostra pagina sull'errore SE Samsung](https://it.codefixcoffee.com/samsung/range-wall-oven/se/); stringhe simili su altri tipi di elettrodomestico puntano tutt'altra parte.

Osserva se il codice compare all'avvio o a metà ciclo: l'autoverifica di accensione scopre i guasti presenti fin dal via, mentre le anomalie a metà ciclo riguardano di norma ciò che era in attività, cioè pompa, resistenza o valvola. Annota anche cosa lo fa scomparire: i forni Samsung, per fare un esempio, tengono il codice sul display finché la causa non viene risolta o l'alimentazione non viene tolta per tre minuti al salvavita, e tutti i codici del marchio sono indicizzati nella [pagina dei codici forno Samsung](https://it.codefixcoffee.com/samsung-oven-error-codes/).

### Prima il significato del produttore

Prima di toccare i forum, passa in rassegna il capitolo sulla risoluzione dei problemi del manuale, il portale ricambi e assistenza del marchio ed eventuali bollettini di servizio in formato PDF per il tuo modello. Per due dei marchi più diffusi, i [manuali pubblicati da De'Longhi](https://www.delonghi.com) e il [supporto Philips](https://www.philips.com) sono il punto di partenza naturale. Il significato ufficiale è la base di partenza; tutto il resto è commento.

### Incrocia i forum con la documentazione di servizio

Nei forum scopri che cosa si rompe davvero. Una tabella di servizio dice che un codice significa guasto al gruppo di erogazione; un thread dice che sul tuo modello si tratta quasi sempre di un panetto di caffè incastrato e di un quarto d'ora di pulizia. Tratta i thread come prove, non come verità:

- Dai peso ai post che nominano il tuo modello esatto e descrivono una riparazione ancora funzionante a settimane di distanza.

- Diffida di qualunque thread che consiglia lo stesso pezzo per ogni codice su ogni macchina.

- Quando una fonte forum e un documento di servizio sono in disaccordo, il documento vince sul significato; il forum vince sulla probabilità.

## La trappola: stesso codice, significato diverso

Qui va a finire la maggior parte delle autodiagnosi, perché i codici errore non sono standardizzati: né tra marchi diversi, e a volte nemmeno dentro la gamma di un solo marchio.

- Lo stesso numero può indicare cose non imparentate. Su una Jura l'[errore 2](https://it.codefixcoffee.com/jura/automatic-machines/error-2/) è un guasto della sonda del termoblocco del caffè, oppure semplicemente una macchina troppo fredda per scaldare; su una Philips o Saeco l'errore 02 è un guasto interno che va dritto in assistenza. Stesso numero, stessa categoria, sottosistemi e spese completamente diversi.

- Le parole possono nascondere codici. Un General Alarm De'Longhi ha un gemello numerico registrato per i tecnici: ripararlo bene significa conoscere entrambi i livelli.

- La categoria conta quanto la marca. Una stringa valida su un piano cottura significa tutt'altro sulla lavastoviglie o sulla lavatrice dello stesso marchio: filtra prima per tipo di elettrodomestico, poi per modello.

Fai un controllo di coerenza tra significato e sintomo: un codice della resistenza su una macchina che scalda ancora, o un codice di scarico su una che scarica regolarmente, suggeriscono quasi sempre che stai leggendo la voce sbagliata — o la voce del modello sbagliato.

### Acqua dura e codici idrici: il caso italiano

In buona parte d'Italia, dal Lazio alla Puglia, l'acqua del rubinetto è molto calcarea, e il calcare è tra le cause più frequenti dei codici legati ad acqua e riscaldamento sulle macchine da caffè. Imposta il livello di durezza con la striscia test fornita a corredo e rispetta la cadenza di decalcificazione consigliata dal manuale: molti codici che sembrano guasti, nelle cucine italiane, nascono da cicli di manutenzione saltati. Nella stessa logica, un filtro dell'acqua mantenuto correttamente riduce la frequenza con cui certi errori tornano a comparire.

## Una checklist di verifica in cinque passi

1. Fotografa il display e annota il numero di modello completo letto dalla targhetta.

2. Ricava il significato ufficiale del produttore dal manuale o dalla documentazione di servizio.

3. Conferma con almeno due thread di forum che nominano il tuo modello e riportano una riparazione duratura.

4. Controlla il significato su una pagina di riferimento indipendente: l'[errore 11 o 19 Philips](https://it.codefixcoffee.com/philips-saeco/espresso-machines/error-11-or-19/) deve leggersi allo stesso modo ovunque lo trovi; se due fonti discordano, dai fiducia a quella che cita la documentazione di servizio.

5. Resetta la macchina una volta, poi decidi: se il codice ricompare subito, consideralo reale e scegli tra un ricambio economico, una pulizia o un tecnico.

## Quando smettere di cercare

Chiudi le schede del browser quando due fonti indipendenti concordano sul significato e il sintomo combacia. Nessuna lettura ulteriore cambia un codice che ricompare subito dopo il reset: da quel punto in poi la decisione è pratica, e mette sul piatto il prezzo del pezzo contro l'età della macchina.
