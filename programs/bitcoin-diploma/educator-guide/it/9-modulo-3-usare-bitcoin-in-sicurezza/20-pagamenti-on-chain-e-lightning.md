# 9.20 Pagamenti on-chain e Lightning

Utilizzi un confronto che distingua il percorso del pagamento dalla [custodia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody).


| Domanda | On-chain | Lightning |
| --- | --- | --- |
| Dove viene registrato il regolamento? | Direttamente nella Blockchain di Bitcoin | Gli aggiornamenti dei pagamenti avvengono tramite una rete costruita sopra Bitcoin; i canali dipendono in ultima analisi da Bitcoin |
| Informazioni di ricezione comuni per i principianti | Indirizzo on-chain | Invoice, indirizzo Lightning supportato o un altro tipo di richiesta approvato |
| Uso tipico | Regolamento sul livello di base, spesso trasferimenti più consistenti o meno frequenti | Spesso pagamenti piccoli o frequenti, dove gli strumenti locali e la liquidità li supportano |
| Tempistiche | La prima Conferma dipende dall'inclusione in un blocco | Spesso rapidi, ma i pagamenti possono fallire |
| Commissioni e capacità | Dipendono dai dati della Transazione e dalla domanda di spazio nei blocchi | Dipendono dal Wallet, dal percorso, dalla liquidità, dal servizio e dalle condizioni del pagamento |
| Custodia | Può essere custodial o in autocustodia | Può essere custodial o in autocustodia |
| Verifica principale per i principianti | Indirizzo, rete, importo, commissione e Conferma corretti | Invoice o destinazione, importo, scadenza, commissione ed esito del pagamento corretti |


Lightning non è una moneta separata. Un pagamento Lightning riuscito non dimostra che il Wallet sia sicuro per un saldo più elevato. Il funzionamento dei canali, l'infrastruttura di instradamento e la gestione della [liquidità](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) rientrano nell'[Apprendimento avanzato](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/), al di fuori del Bitcoin Diploma.


<!-- micrographic: on-chain-and-lightning-01 -->
