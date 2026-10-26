# 4.5 Lightning-betalningar

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning kan göra snabba, små Bitcoin-betalningar praktiskt genomförbara. Det kan vara lämpligt vid en butiksdisk, för återkommande lokala betalningar, onlinetjänster eller överföringar där en avgift för en transaktion på blockkedjan skulle vara för stor i förhållande till betalningen.

En lokal Lightning-demonstration bör klargöra:

* om plånboken förvaltas av en tredje part eller av användaren själv
* hur plånboken fylls på
* om påfyllning kräver en blockkedjebaserad [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) eller en tjänst
* vilken säkerhetskopiering eller återställningsmetod som skyddar saldot
* vilken typ av betalningsbegäran som används
* vilka avgifter eller begränsningar som gäller
* vad som händer när en betalning misslyckas
* hur mottagaren bekräftar betalningen

En [**Lightning-faktura**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) är en betalningsbegäran som skapas för en specifik betalning. Den kan innehålla ett belopp, destinationsinformation och en giltighetstid. Läs plånbokens [bekräftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) på skärmen innan ni betalar.

En [**Lightning-adress**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) är en identifierare som är läsbar för människor och stöds av vissa tjänster. Den kan se ut som en e-postadress, men är ett smidigt sätt att styra betalningar till rätt mottagare, inte ett e-postkonto. Den är beroende av den leverantör eller domän som stöder den.

Vid en handledd betalning:

1. Mottagaren skapar rätt betalningsbegäran.
1. Avsändaren skannar eller kopierar den.
1. Avsändaren kontrollerar mottagare, belopp, enhet och avgift.
1. Avsändaren godkänner först när uppgifterna är korrekta.
1. Båda parter bekräftar resultatet i sina egna plånböcker.
1. Gruppen förklarar riskerna med [förvaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) och misslyckade betalningar.

Utgå inte från att en lyckad Lightning-betalning bevisar att plånboken är säker för större saldon. Betalningarnas smidighet och [förvaringens](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) säkerhet är separata frågor.
