# FARE LA SPESA SEGUENDO UNA LISTA

Fatti mandare dalla mamma a prendere il latte

## Traccia

Nel frigo si inizia a sentire l’eco, perciò è ora di fare rifornimenti!
Visto che dimentico sempre qualcosa, decido di appuntarmi tutto ciò che manca in una lista, così una volta al supermercato, girando tra gli scaffali, posso verificare di aver preso tutto e Ricky non rimane senza crocchette come l’ultima volta, povero! Devo ricordarmi di usare il coupon che scade a fine mese, per il resto dovrebbero bastarmi i contanti che ho in portafogli, sempre se non mi faccio prendere la mano con gli snack extra!

## Seguenza

- Frigo
- Lista
- supermercato
- check
- coupon prima fine del mese altrimenti
- contanti nel portafogli
- snack extra?

## Svolgimento

- Verifico gli alimenti presenti nel frigo

- Scrivo una lista della spesa degli alimenti mancanti

  - **PER OGNI** alimento della lista verifico importanza

    - **SE** L'ALIMENTO è IMPORTANTE
      - Assegno valore "importante"
    - **ALTRIMENTI**
      - Assegno valore "non_importante"

- Controllo disponibilità economica

- Segno il valore su "portafoglio"

- Aggiungo il valore del coupon a "portafoglio"

- Mi dirigo al supermercato

- **FINCHè** ci sono elementi nella lista della spesa con valore "importante" **E** ho disponibilità economica **E** **NON** hanno valore "troppo_costoso"

  - cerco gli alimenti mancanti nella lista della spesa con valore "importante"
    - **SE** tovo alimenti con valore "importante" **E** ho disponibilità economica maggiore del costo dell'alimento
      - metto nel carrello
      - elimino dalla lista
      - sottraggo il costo dal valore "portafoglio"
    - **ALTRIMENTI**
      - Segna prodotto come "troppo_costoso"

- **SE** "portafoglio" ha ancora disponibilità

  - **FINCHè** ci sono elementi nella lista della spesa con valore "non_importante" **E** ho disponibilità economica **E** **NON** hanno valore "troppo_costoso"

  - cerco gli alimenti mancanti nella lista della spesa con valore "non_importante"
    - **SE** tovo alimenti con valore "non_importante"
      - metto nel carrello
      - elimino dalla lista
      - sottraggo il costo dal valore "portafoglio"
    - **ALTRIMENTI**
      - Segna prodotto come "troppo_costoso"

- Vai alla cassa e PAGA !
