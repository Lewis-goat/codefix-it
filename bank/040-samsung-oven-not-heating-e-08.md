---
title: Forno Samsung che non scalda: E-08 e codici correlati
description: Il forno Samsung non scalda e mostra E-08? Prima il reset, poi i controlli di resistenza, sonda e relè — più la variante della serratura porta.
---

Un forno che funziona ma resta freddo si guasta in modo sorprendentemente ordinato: la scheda ha fissato una temperatura, la cavità non è salita e la macchina ha registrato il perché. Su piani cottura e forni da incasso Samsung, [E-08](https://it.codefixcoffee.com/samsung/range-wall-oven/e-08/) è il codice di testa per questa situazione — forno che non scalda, con la resistenza di cottura o di grill, la sonda di temperatura o un relè della scheda come indiziati. Attorno gravita una piccola famiglia di codici correlati che restringe ulteriormente la diagnosi. Li passiamo in rassegna nell'ordine in cui conviene controllarli, partendo dal passaggio che tutti saltano.

## Prima di tutto: il reset all'interruttore

Prima di trarre qualsiasi conclusione, togli corrente all'interruttore per tre minuti e rimettila. Non è scaramanzia: una scheda finita in uno stato anomalo può registrare un guasto di riscaldamento che altrimenti non esisterebbe, e un ciclo di alimentazione pulito lo cancella. Se E-08 ricompare al primo tentativo di cottura successivo, il guasto è reale e si prosegue. Lo stesso reset di tre minuti apre la via diagnostica a quasi tutti i codici della [lista codici forni Samsung](https://it.codefixcoffee.com/samsung-oven-error-codes/), quindi è un'abitudine che conviene prendere.

## La resistenza

La resistenza di cottura è il cavallo da battaglia sul fondo della cavità e quando cede si vede. A forno acceso, la resistenza deve risplendere in modo uniforme lungo tutta la sua lunghezza. Una rottura visibile, una bolla o una macchia bruciata sono una diagnosi che puoi fare a occhio: sostituiscila. Una resistenza costa da 30 a 60 € ed è una delle riparazioni del forno più convenienti in assoluto; per orientarti nella procedura, [iFixit](https://www.ifixit.com/) pubblica guide fotografiche per la sostituzione di resistenze e sonde su forni ed elettrodomestici simili. Se la resistenza risplende regolarmente ma il forno comunque non tiene temperatura, è scagionata e la prossima indiziata è la sonda — il percorso decisionale completo sta nella [pagina diagnostica di E-08](https://it.codefixcoffee.com/samsung/range-wall-oven/e-08/).

## La sonda NTC di temperatura

La sonda legge la temperatura della cavità e la riporta alla scheda come valore di resistenza. A temperatura ambiente una sonda sana misura circa 1080 ohm — e quel numero è l'intero test:

1. Togli corrente all'interruttore.
2. Svita la sonda dalla parete posteriore della cavità (due viti) e scollega il connettore.
3. Misurala con il multimetro: intorno a 1080 ohm a temperatura ambiente è sana.
4. Se il valore è corretto, ricollega saldamente il connettore; se è lontano dal target, sostituisci la sonda.

Due codici gemelli ti dicono in che direzione è andata la sonda anche senza multimetro. E-27 indica sonda che legge aperta — resistenza troppo alta, oltre circa 2950 ohm — quindi sonda bruciata o connettore allentato. E-28 indica sonda in cortocircuito, sotto circa 930 ohm, quindi sonda cortocircuitata o cablaggio pizzicato dietro il forno. In entrambi i casi la sonda costa da 20 a 40 € e si avvita dall'interno della cavità; per la definizione esatta del codice sul tuo modello, il [supporto Samsung](https://www.samsung.com/) mette a disposizione i manuali per modello.

## Il relè sulla scheda

Se la resistenza risplende e la sonda misura correttamente, ciò che resta è la scheda dei relè: la scheda non sta commutando l'alimentazione verso la resistenza. Un relè che non si chiude mai, visto dall'interno del forno, è indistinguibile da una resistenza morta. È l'esito da 100 a 200 € e, su una cucina datata, è il punto in cui diventa ragionevole confrontare il preventivo con il valore della macchina.

## La variante della serratura porta

Un'avvertenza prima di comprare i pezzi: su alcuni modelli le stesse pagine di assistenza Samsung elencano E-08 come guasto della serratura porta anziché del riscaldamento — la chiusura motorizzata usata per la pulizia automatica, non il circuito di cottura. Controlla il manuale del tuo modello prima di ordinare una resistenza. Il codice correlato per i problemi di serratura è E-0E (mostrato come E-0E o FL), che compare di solito dopo un ciclo di pulizia automatica quando l'interruttore della serratura si blocca o il motorino cede; il gruppo completo costa da 40 a 90 €. Non forzare mai la porta in nessuno di questi casi: lascia prima raffreddare completamente il forno, perché da caldo non si sbloccherà.

## Il codice del problema opposto

Nella stessa famiglia di guasti conviene conoscere [E-0A](https://it.codefixcoffee.com/samsung/range-wall-oven/e-0a/): il forno che surriscalda. Sembra un reclamo diverso, ma condivide due indiziati con E-08 — una sonda che legge male (stavolta per difetto) oppure un relè bloccato in chiusura che non spegne mai la resistenza. Tratta E-0A con più urgenza di un mancato riscaldamento: un relè incollato significa resistenza sempre accesa, quindi taglia subito la corrente all'interruttore e non usare il forno finché non è riparato.

## Quanto costano le riparazioni

Resistenza da 30 a 60 €, sonda da 20 a 40 €, gruppo serratura da 40 a 90 €, scheda relè da 100 a 200 €. Resistenza e sonda sono un sì convinto a qualsiasi età ragionevole della macchina; la scheda è una valutazione di giudizio. La visita a domicilio di un tecnico costa da 120 a 250 € di diagnosi più il pezzo: soldi onesti per scoprire quale dei tre ti serve davvero.

### Un consiglio pratico per l'Italia

Nelle case italiane il forno dovrebbe trovarsi su una linea dedicata da 16 A con il proprio interruttore: una linea condivisa o sovraccarica può causare cadute di tensione che confondono la diagnosi. Se nella tua zona i temporali sono frequenti, un limitatore di sovratensione da 20–40 € è un investimento sensato, perché i picchi di rete sono una delle cause ricorrenti di danni alla scheda di controllo. Ricorda infine che il valore di 1080 ohm vale per la misura a temperatura ambiente: in un locale freddo la lettura risulta un po' più alta, quindi non condannare la sonda per poche decine di ohm in più.
