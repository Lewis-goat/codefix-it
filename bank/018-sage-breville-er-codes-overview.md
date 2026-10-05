---
title: Codici ER Sage/Breville: leggere la tabella di servizio nascosta
description: Codici ER su Sage e Breville: nascono da tabelle di servizio mai pubblicate. Come sono organizzati gli ER01-ER18 e perché l'Oracle numera diversamente.
---

Se una macchina da caffè Breville si ferma di colpo mostrando ER05 sul pannello, il manuale non ti dirà che cosa significhi. Non è una svista: i codici d'errore Breville provengono dalle tabelle di servizio interne, usate dai tecnici per le riparazioni e mai diffuse agli utenti. Lo stesso hardware in Italia e nel resto d'Europa arriva con il marchio **Sage** sulla targhetta — macchine identiche — quindi un codice ER su una Sage Barista Touch significa esattamente ciò che significa sulla gemella Breville. La [sezione Breville / Sage](https://it.codefixcoffee.com/breville/) copre la gamma attuale; questo articolo spiega come è organizzata la numerazione, così anche un codice mai visto prima ti dice qualcosa di utile.

## Perché Breville non li pubblica

Il manuale utente parla di pulizia e decalcificazione, non di diagnostica. Le tabelle complete vivono nella modalità di servizio di ogni macchina: schermate protette da password e pensate per i tecnici, con contatori d'errore memorizzati e letture dei sensori in diretta. Nati come strumento di riparazione più che come funzione per il proprietario, questi codici non sono mai stati resi pubblici, e la maggior parte degli utenti vede in vita sua soltanto quello che ha causato lo spegnimento. Il contrasto con Miele è netto: i significati dei codici F sono stampati nelle istruzioni operative — verificabili anche tramite il [sito Miele](https://www.miele.com) — ed è per questo che le [pagine dei codici Miele](https://it.codefixcoffee.com/miele/) possono citare il manuale alla lettera.

## La tabella della Barista Touch: da ER01 a ER18

La Barista Touch (BES880) e la Barista Touch Impress (BES881) — che condividono la stessa famiglia di schede di controllo e quindi la stessa tabella — adoperano una lista da 18 voci. Una volta capita la struttura si legge senza fatica: i codici sensore arrivano a **gruppi di quattro**, un gruppo per sensore, e percorrono circuito aperto all'avvio, circuito aperto in esercizio, cortocircuito all'avvio e cortocircuito in esercizio.

- **ER01-ER04** — la sonda di temperatura del riscaldatore ThermoJet nei suoi quattro stati possibili; [ER01](https://it.codefixcoffee.com/breville/barista-touch-bes880/er01/) è la variante con circuito aperto all'avvio.
- **ER05-ER08** — la sonda della caraffa del latte, la piccola sonda nella zona del vassoio gocce che legge la caraffa mentre la lancia monta il latte. ER05, il circuito aperto all'avvio, è il codice Barista Touch più segnalato in assoluto, e le quattro voci condividono un unico rimedio.
- **ER09-ER12** — la sonda di temperatura in linea sull'acqua di erogazione, con lo stesso schema a quattro varianti.
- **ER13 ed ER14** — errori di conteggio del flussometro, rispettivamente all'avvio e in esercizio: la pompa girava e la macchina non riusciva a contare l'acqua che la attraversava.
- **ER15** — guasto di comunicazione tra moduli elettronici interni; spesso un flat allentatosi o un connettore bagnato più che una scheda morta.
- **ER16 ed ER17** — il macinacaffè: motore surriscaldato e fermo per autoprotezione, poi motore che non ha concluso il compito entro il tempo previsto.
- **ER18** — protezione E-fast, cioè un guasto elettrico o di sicurezza come una corrente di dispersione; è anche il codice capace di far scattare il differenziale della tua presa.

## La famiglia Oracle numera in modo diverso

Passando a un Oracle, la stessa idea richiede una tabella più lunga. Oracle (BES980) e Oracle Touch (BES990) condividono una lista da 32 voci, ma la BES980 le mostra come "Error 1"-"Error 32" mentre la BES990 le precede con ER. Le prime sedici seguono la logica dei quartetti su quattro sensori: caldaia del vapore da 1 a 4, caldaia del caffè da 5 a 8 (con l'[Error 8](https://it.codefixcoffee.com/breville/oracle-bes980/error-8/) che segnala il cortocircuito della sonda della caldaia caffè durante il funzionamento), gruppo riscaldato da 9 a 12 e lancia vapore da 13 a 16. Le restanti coprono le caldaie che non scaldano (17-19), livello e riempimento della caldaia vapore (20 e 21), i problemi di flussometro (22 e 23), sonde di livello e surriscaldamenti (24-27), un guasto di comunicazione tra schede al 28, il macinacaffè al 29 e 30, il motore della pressatura al 31 e una perdita o ricarica mancata della caldaia vapore al 32.

Due tabelle minori completano la famiglia. L'Oracle Jet (BES985) usa una lista E1-E19 tutta sua, mentre la Dual Boiler (BES920) custodisce in un menu di self-check codici a due cifre da 00 a 12 invece di mostrarli sul display normale — quindi una Dual Boiler può portarsi dietro un guasto che non hai mai visto comparire a schermo.

## Leggere da soli il registro degli errori

Essendo dati di servizio, la storia della macchina si legge attraverso le stesse schermate. I percorsi hanno un sapore da officina, ma i riparatori li hanno documentati bene:

- **Barista Touch e Oracle Touch** — spegni alla presa, tieni premuto il tasto Power frontale mentre riattivi la corrente a muro, rilascia quando compare il logo, inserisci la password di servizio 00000, poi apri Error Counter per i guasti memorizzati o Live Debug per temperature e livelli dell'acqua in tempo reale.
- **Barista Touch Impress** — identica sequenza di tasti, ma la password di servizio è 02015.
- **Oracle BES980** — con la macchina collegata ma spenta, tieni premuti insieme 1 CUP, 2 CUP e POWER per almeno un secondo; dopo il segnale acustico lungo premi la manopola SELECT per aprire Error Storage e scorrere gli errori da 1 a 32 con i relativi conteggi.

Considera queste schermate in sola lettura: annota cosa è memorizzato, non toccare le impostazioni e azzera il registro solo a riparazione avvenuta, così saprai dire se il codice ritorna.

## Quanto costano le riparazioni

Persino contro una tabella mai pubblicata, i conti tornano sempre. Un gruppo sonda temperatura costa indicativamente da 25 a 95 € secondo il sensore coinvolto (le sonde di lancia vapore e caraffa latte sono le più care) e i kit di o-ring da 10 a 20 €; un kit di riparazione per la sonda del latte sta sui 30-50 € contro gli 80-95 € del gruppo originale. I preventivi del produttore fuori garanzia per guasti interni girano di norma attorno ai 300-500 €, quindi la riparazione a livello di sensore presso un indipendente resta quasi sempre la strada migliore. La copertura dedicata ai modelli con badge Sage si trova nella [versione britannica del sito](https://it.codefixcoffee.com/uk/).

### Se la macchina è stata comprata in Italia

Da noi questi modelli arrivano con il marchio Sage sulla targhetta e i codici sono identici: questa tabella vale quindi anche per la tua Barista Touch o Oracle. Sul [sito ufficiale Sage](https://www.sageappliances.co.uk) trovi manuali d'uso, guide video alla manutenzione e i prodotti originali per la decalcificazione — e gran parte dei codici ER nasce in realtà da manutenzione saltata più che da componenti rotti. Vista la durezza dell'acqua in molte città italiane, rispettare l'avviso di pulizia del gruppo di erogazione e di decalcificazione è il modo più economico di non incontrare mai questi codici.
