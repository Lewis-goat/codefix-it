---
title: Breville/Sage Oracle: vapore e codici, cosa controllare per primo
description: Guasti del vapore su Breville/Sage Oracle: cosa significano i codici lato vapore, lo spurgo da provare subito e quando il vero colpevole è il calcare.
---

Il reparto vapore di una Breville Oracle è il più indaffarato della macchina: caldaia in acciaio, lancia a montatura automatica, sonde di livello e pompa di carico, tutte in temperatura ogni giorno. Ed è anche la fabbrica di gran parte dei codici d'errore. La famiglia Oracle adotta una tabella di servizio da 32 voci che Breville non pubblica, mentre in Europa la stessa macchina esce con il badge **Sage** — codici identici. Prima di pensare a un componente rotto, esaurisci i controlli economici: la maggior parte degli stop lato vapore è una punta della lancia intasata, uno spurgo mancato o calcare su una sonda.

## Dove stanno i codici vapore nella tabella Oracle

Oracle (BES980) e Oracle Touch (BES990) condividono la stessa tabella; la BES980 mostra le voci come "Error 1"-"Error 32", la BES990 con il prefisso ER. Le voci legate al vapore si addensano in cinque punti:

- **Error 1-4** — la sonda di temperatura della caldaia vapore nei quattro stati possibili: circuito aperto all'avvio, sonda persa durante il funzionamento, cortocircuito in entrambe le situazioni. Una sonda sola, quattro modi di segnalarla.
- **Error 13-16** — lo stesso quartetto per la sonda della lancia vapore, quella che interrompe la montatura automatica alla giusta temperatura del latte. Vive nel punto più bagnato della macchina.
- **Error 18** — la caldaia vapore non si riscalda come dovrebbe.
- **Error 20 e 21** — livello dell'acqua in caldaia o guasti della pompa di carico, e una lettura della sonda di livello che non combacia con ciò che la scheda si aspetta.
- **Error 26** — la caldaia vapore ha superato la temperatura di consigna; l'**Error 32** indica una perdita dalla caldaia o il fallimento della ricarica.

Non tutto ciò che sta vicino alla lancia è lato vapore: i codici 5-8 appartengono alla sonda della caldaia caffè, e l'[Error 8](https://it.codefixcoffee.com/breville/oracle-bes980/error-8/) è la sua variante cortocircuito durante il funzionamento. Il registro memorizzato aiuta a distinguere le famiglie: sulla BES980 tieni premuti insieme 1 CUP, 2 CUP e POWER con la macchina spenta per aprire Error Storage e scorrere tutti e 32 i codici con i relativi conteggi.

## Il primo controllo: la procedura di spurgo

Vapore debole o sputacchiante, oppure un codice subito dopo una bevanda al latte, puntano quasi sempre alla punta della lancia più che alla caldaia:

1. Scola la spina e lascia raffreddare la lancia.
2. Svita la punta della lancia e mettila in ammollo in acqua calda con un po' di decalcificante; libera ogni foro con lo spillone dell'attrezzo di pulizia.
3. Esegui lo spurgo — una decina di secondi di vapore nel vassoio gocce con la punta smontata, poi di nuovo con la punta montata.
4. Da qui in poi spurga la lancia dopo ogni sessione di latte: il latte secco nella punta è l'innesco della maggior parte di questi stop.

Se la macchina controlla anche la pressione del vapore, come fa l'Oracle Jet con il suo codice E16, una punta incrostata può far scattare l'allarme prima ancora che tu ti accorga che il vapore si è indebolito.

## Durezza dell'acqua, calcare e sonde di livello

Dove l'acqua è dura, il calcare scrive codici d'errore in prima persona. Le sonde di livello della caldaia vapore vivono immerse in acqua calda in continuo, e una patina calcarea le isola elettricamente: la scheda legge "manca acqua" con la caldaia piena — la strada classica verso Error 20 o 21, e verso il fallimento di ricarica dell'Error 32. Il calcare colonizza anche il percorso della lancia e l'ingresso della pompa di carico. Una decalcificazione completa, ciclo caldaia vapore incluso, è la diagnosi più economica che si possa fare e da sola risolve una parte sorprendente di questi codici.

La macchina sorella della gamma conferma la regola: la Dual Boiler tiene i propri codici da 00 a 12 nascosti in un menu di self-check, e il [codice 00](https://it.codefixcoffee.com/breville/dual-boiler-bes920/00/) — sonda della caldaia vapore non rilevata — apre una tabella le cui voci di livello e riempimento reagiscono all'acqua dura esattamente nello stesso modo.

### Il caso italiano: acqua durissima e filtri

In molte zone d'Italia — Roma e gran parte di Lazio, Lombardia e Puglia — l'acqua di rete è tra le più dure d'Europa, e su un Oracle questo si traduce in decalcificazioni più frequenti di quante ne lasci intuire il manuale. Sul [sito Sage Appliances](https://www.sageappliances.co.uk) trovi le cartine indicatore di durezza e i filtri originali compatibili con l'Oracle: usarne uno, oppure partire da acqua a basso residuo fisso, riduce sensibilmente la probabilità di incappare nei codici 20, 21 e 32. Chi monta il latte ogni giorno dovrebbe abbinare al filtro anche lo spurgo quotidiano della lancia: è la coppia di abitudini che allunga la vita delle sonde.

## Quando decalcificare e quando smontare

Prima la decalcificazione, poi il cacciavite — ma conviene sapere dove la decalcificazione smette di essere utile:

- **Decalcifica prima** davanti ai codici di livello, sonda e ricarica (20, 21, 32), davanti a vapore debole senza alcun codice, e su ogni macchina a cui mancano più di tre mesi dall'ultimo ciclo. Costo: una bottiglia di decalcificante.
- **La decalcificazione non risolve** un codice sensore che ricompare subito su macchina appena decalcificata e calda — che sia una voce caldaia vapore da 1 a 4 o l'[Error 8](https://it.codefixcoffee.com/breville/oracle-bes980/error-8/) sul lato caffè. Un codice che sopravvive a una decalcificazione indica la sonda, il suo cablaggio o un connettore.
- **Fermati e controlla le guarnizioni** se Error 26 si ripete: una o-ring della sonda che perde vapore scalda il cavo della sonda e imita una caldaia fuori controllo. Le o-ring nuove costano poco; un triac che non spegne la resistenza no.
- **Error 18** su una macchina che non produce più vapore affatto è quasi sempre lato riscaldatore — fusibile termico, resistenza o scheda — non calcare: trattalo come una riparazione, non come una pulizia.

## Quanto costano i ricambi

I gruppi sonda originali stanno tra 25 e 95 € secondo il sensore coinvolto; i gruppi lancia vapore, sonda inclusa, attorno ai 60-95 €; un kit sonda e o-ring sui 85 € e una pompa di carico tra 30 e 60 €. Sullo sfondo, i preventivi fuori garanzia del produttore per guasti interni viaggiano di norma tra 300 e 500 €: prima la bottiglia di decalcificante e poi un intervento a livello di sensore restano quasi sempre il conto migliore. La copertura dei codici con badge Sage si trova nella [versione britannica del sito](https://it.codefixcoffee.com/uk/).
