---
title: Breville Dual Boiler 00–12: i codici a due cifre
description: La Dual Boiler BES920 usa i codici da 00 a 12 in un menu nascosto: cosa significa ogni famiglia, guasti lato vapore o erogazione e come risolverli.
---

Le macchine da espresso Breville annunciano quasi tutte i guasti sul display ordinario: la Barista Touch usa codici ER, l'Oracle scrive "Error", l'Oracle Jet adotta numeri E. La **Dual Boiler BES920** fa eccezione. La sua tabella guasti è un elenco spoglio di codici a due cifre, **dal 00 al 12**, che vive in un menu di autotest nascosto, non sullo schermo di tutti i giorni. Osservando il pannello frontale durante il funzionamento normale non li vedrai mai: serve la combinazione di tasti giusta.

La numerazione merita due minuti di attenzione, perché è costruita con ordine: il blocco in cui cade un codice rivela la natura del guasto, e dentro ogni blocco il numero indica il componente che si sta lamentando.

## Come leggere il registro errori

Il registro si raggiunge dal menu di autotest:

1. Spegni la macchina dall'interruttore a muro.
2. Tieni premuti **EXIT** e **MANUAL** mentre riaccendi l'alimentazione: compare il menu di autotest.
3. Premi **MENU** fino alla voce 3, il registro errori. La voce 4 mostra lo stato del livello delle caldaie, indicato come LLL (basso) o HHH (alto).
4. Nel registro errori, **MENU** scorre i codici da 00 a 12, ciascuno con il contatore memorizzato.
5. Alla voce "ErSt", tieni premuto **MANUAL** fino al beep per azzerare i codici salvati; il contatore delle bevande non si azzera.

I contatori contano quanto i codici. Un guasto con contatore uno, risalente a un anno prima, è storia passata; un guasto il cui contatore sale ogni settimana è un problema vivo in costruzione.

## La famiglia 00: le tre sonde di temperatura

I codici **dal 00 al 05** formano il blocco delle sonde di temperatura, organizzato in tre coppie. In ogni coppia il numero più basso significa sonda **non riconosciuta** — la scheda la legge come circuito aperto — e il numero più alto la segnala in **cortocircuito**:

- **00 e 01** — sonda della temperatura della caldaia vapore, prima non riconosciuta poi in cortocircuito.
- **02 e 03** — sonda della temperatura della caldaia caffè, stessa logica.
- **04 e 05** — sonda della temperatura del riscaldatore del gruppo di erogazione, stessa logica.

La BES920 monta due caldaie in acciaio più un gruppo di erogazione riscaldato, quindi le tre sonde coprono le tre zone calde della macchina. La [pagina del codice 00](https://it.codefixcoffee.com/breville/dual-boiler-bes920/00/) tratta la sonda della caldaia vapore, ma il suo consiglio pratico si trasferisce alle altre cinque: riseda e ispeziona il connettore della sonda prima di comprare pezzi, e cerca umidità, perché l'acqua che fa ponte su un connettore viene letta come circuito aperto o cortocircuito a seconda di come si posa. Le sonde NTC originali costano dai 25 ai 90 € a seconda di quale delle tre è; i kit di guarnizioni O-ring stanno tra 10 e 20 € e sono spesso il vero colpevole.

## Lato vapore contro lato erogazione

Il resto della tabella si divide lungo la stessa linea hardware delle coppie di sonde:

- **Caldaia vapore:** 06 (problema di pompa durante l'avvio), 07 (livello acqua o guasto pompa) e 11 (surriscaldamento rilevato).
- **Caldaia caffè, cioè il lato erogazione:** 08 (problema di pompa o di flusso), 09 (guasto del livello acqua) e 10 (surriscaldamento rilevato).
- **Gruppo di erogazione:** 12 (surriscaldamento rilevato).

### I codici che viaggiano in compagnia

Questi guasti sono concatenati, ed è per questo che leggere l'intero registro batte il leggere un solo codice. Il codice 08 dice che la pompa ha girato e il flussometro non ha visto passare nulla — il più delle volte calcare sulla paletta del flussometro, oppure una piccola pompa che ronza senza muovere acqua, e in entrambi i casi la decalcificazione è la prima mossa. Il codice 11, il surriscaldamento della caldaia vapore, segue di solito una caldaia che non viene rabboccata — controlla se anche 07 o 08 hanno un contatore attivo — perché la resistenza continua a scaldare una caldaia semivuota; l'altra causa è la guarnizione della sonda che perde. Prima di ordinare qualsiasi cosa, leggi la voce 4 del menu di autotest: uno stato del livello in contraddizione con ciò che senti quando la macchina si riempie ti dice da che parte sta davvero il guasto.

Il codice 12, il surriscaldamento del gruppo di erogazione, è l'estremo raro della tabella e quello in cui la ricorrenza pesa di più: un surriscaldamento che continua a ripresentarsi punta a una scheda di alimentazione che tiene agganciato il riscaldatore, più che a una deriva della sonda. La [pagina del codice 12](https://it.codefixcoffee.com/breville/dual-boiler-bes920/12/) la analizza nel dettaglio.

## Quanto costano i pezzi

- Decalcificante per i codici di flusso e livello: una decina di euro, e risolve una fetta reale dei casi.
- Pompa di carico: da 30 a 60 €.
- Sonda della caldaia vapore e kit O-ring: circa 85 €; i soli kit O-ring da 10 a 20 €.
- Fusibile termico: da 10 a 20 € — ma prima capisci perché è saltato.
- Triac o scheda di alimentazione: da 80 a 150 €.

I preventivi Breville fuori garanzia per guasti interni partiscono comunemente da 300–500 € e oltre, quindi per una pompa o una sonda conviene arrangiarsi; per una scheda su una macchina datata conviene prima chiedere un preventivo. Acqua e corrente di rete condividono la parte alta della caldaia: stacca la spina prima di toccare le sonde. Per lavorare in sicurezza su connettori e sonde, [iFixit](https://www.ifixit.com/) raccoglie guide di riparazione per macchine da caffè che coprono apertura e gestione dei cablaggi.

### In Italia questa macchina si chiama Sage

Sul mercato italiano, come nel resto d'Europa, le macchine Breville vengono vendute con il marchio Sage: manuali, ricambi e assistenza si trovano più facilmente cercando "Sage the Dual Boiler BES920" anziché "Breville". La [sezione supporto di Sage Appliances](https://www.sageappliances.co.uk/) pubblica manuali e indicazioni ufficiali per questo modello, utili anche solo per confermare la procedura del menu di autotest. Gli interni sono identici: cambia solo il nome sul catalogo, quindi ogni guida BES920 resta valida.

Per come formulano i propri codici le altre macchine della gamma, vedi la [sezione Breville](https://it.codefixcoffee.com/breville/): le macchine della famiglia ER condividono idee di diagnosi ma non la numerazione.
