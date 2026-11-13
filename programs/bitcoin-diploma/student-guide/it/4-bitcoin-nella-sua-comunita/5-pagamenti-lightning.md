# 4.5 Pagamenti Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Il destinatario crea sul proprio telefono una richiesta di pagamento Lightning con l'importo, il mittente la scansiona e paga, e il pagamento arriva sul telefono del destinatario un attimo dopo.](/micrographics/lightning-phone-payment-01/it.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[Un pagamento Lightning in sei passaggi: il destinatario crea una richiesta, il mittente la scansiona, controlla destinatario, importo, unità, scadenza e commissione, la approva, il pagamento viene instradato ed entrambi i wallet mostrano l'esito. Ciascun wallet può essere custodial o self-custodial e un pagamento non riuscito o scaduto ricomincia con una nuova richiesta.](/micrographics/lightning-payment-sequence-01/it.md)


Lightning può rendere pratici i pagamenti Bitcoin rapidi e di piccolo importo. Può essere adatto per la cassa di un esercente, per pagamenti locali ripetuti, per servizi online o per trasferimenti in cui una commissione on-chain sarebbe troppo elevata rispetto all'importo del pagamento.

Una dimostrazione locale di Lightning dovrebbe chiarire:

* se il wallet è custodial o self-custodial
* come viene ricaricato il wallet
* se la ricarica richiede una [transazione](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) on-chain o un servizio
* quale backup o metodo di recupero protegge il saldo
* quale tipo di richiesta di pagamento viene utilizzato
* quali commissioni o limiti si applicano
* cosa succede quando un pagamento non va a buon fine
* come il destinatario verifica l'avvenuto pagamento

Una [**Lightning invoice**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) è una richiesta di pagamento creata per un pagamento specifico. Può includere un importo, informazioni sulla destinazione e una scadenza. Legga la schermata di [conferma](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) del wallet prima di pagare.

Un [**Lightning address**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) è un identificativo leggibile supportato da alcuni servizi. Può sembrare un indirizzo e-mail, ma è uno strumento pratico per l'instradamento dei pagamenti, non un account di posta elettronica. Dipende dal fornitore o dal dominio che lo supporta.

Per un pagamento guidato:

1. Il destinatario crea la richiesta corretta.
1. Il mittente la scansiona o la copia.
1. Il mittente controlla destinatario, importo, unità e commissione.
1. Il mittente approva solo dopo aver verificato che i dettagli siano corretti.
1. Entrambe le parti verificano il risultato nel proprio wallet.
1. Il gruppo spiega i rischi legati alla [custodia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) e al mancato completamento dei pagamenti.

Non dia per scontato che un pagamento Lightning andato a buon fine dimostri che il wallet sia sicuro per saldi più elevati. La comodità di pagamento e la sicurezza della [custodia](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) sono questioni distinte.
