# 10.9 Checklist del modulo Lightning

Prima di un workshop su Lightning, verifichi e spieghi:

* se il wallet è custodial o in autocustodia
* come viene finanziato
* se il finanziamento o il prelievo avvengono tramite una transazione on-chain o tramite un servizio
* il recupero e la continuità in caso di guasto del fornitore o del dispositivo
* se la richiesta è una invoice, un [indirizzo Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) supportato o un altro tipo
* importo, unità, destinatario, scadenza, commissione, limiti e aspetti di [liquidità](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) da considerare
* come si presentano un esito riuscito, in sospeso, scaduto o fallito
* come entrambe le parti confermano il risultato in modo indipendente; e
* la simulazione offline.


<!-- card: dark -->
> **Un pagamento Lightning riuscito dimostra soltanto che questo percorso ha funzionato una volta**
>
> Non dimostra che il wallet sia sicuro per saldi più elevati né che lo stesso percorso funzionerà ovunque.



<!-- micrographic: lightning-payment-sequence-01 -->
[Un pagamento Lightning in sei passaggi: il destinatario crea una richiesta, il mittente la scansiona, controlla destinatario, importo, unità, scadenza e commissione, la approva, il pagamento viene instradato ed entrambi i wallet mostrano l'esito. Ciascun wallet può essere custodial o self-custodial e un pagamento non riuscito o scaduto ricomincia con una nuova richiesta.](/micrographics/lightning-payment-sequence-01/it.md)
