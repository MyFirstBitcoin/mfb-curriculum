# 3.14 Pagamenti on-chain e Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Pagamenti on-chain e Lightning**
>
> [I pagamenti on-chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) sono registrati nella [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) di Bitcoin e ottengono [conferme](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning è una rete di pagamento costruita su Bitcoin che può supportare pagamenti rapidi e frequenti. Un pagamento Lightning può completarsi rapidamente o fallire, e il relativo wallet può comunque essere custodial o self-custodial.



> **Dark – Il percorso di pagamento non determina la custodia**
>
> I pagamenti on-chain e Lightning comportano diversi [compromessi](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Un wallet Lightning può essere custodial o self-custodial, e un pagamento rapido andato a buon fine non dimostra che un servizio sia adatto a saldi più elevati o a ogni situazione.



<!-- micrographic: onchain-lightning-table-01 -->


Quale percorso si aspetta il destinatario? Prima di pagare, verifichi se Le ha fornito un indirizzo on-chain oppure una [fattura Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) o una richiesta di pagamento. Un wallet on-chain non può pagare direttamente ogni [fattura Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), e un wallet Lightning potrebbe non supportare ogni operazione on-chain. Alcune applicazioni supportano entrambi i percorsi, ma possono aggiungere commissioni o dipendenze da servizi. La configurazione dettagliata di Lightning, i canali, l'instradamento e la [liquidità](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) fanno parte dell'[Apprendimento avanzato](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); la pratica dal vivo in ambito locale rientra nel **Modulo 4**, quando è sicura e appropriata.

Immagini che uno scenario predisposto offra entrambi i percorsi di pagamento. Quale richiesta può utilizzare il wallet previsto, e che cosa verificherebbe prima di approvarla? La risposta dipende dalla richiesta di ricezione, dal wallet e dalla situazione, non da un percorso “migliore” universale.

![L'educatore indica su una lavagna due diversi percorsi di pagamento geometrici, mentre lo studente principiante e quello con competenze tecniche li esaminano.](https://cdn.sanity.io/images/vje9ehw2/production/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
