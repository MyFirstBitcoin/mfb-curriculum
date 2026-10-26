# 2.3 Tidlige forsøk på digitale penger og problemet med dobbeltbruk

Bitcoin var ikke det første forsøket på digitale penger. Det bygget på fire tiår med eksperimentering og hentet ideer fra mange tidligere prosjekter som bidro til å forme den vellykkede utformingen.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) brukte [kryptografi](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) for å muliggjøre private digitale betalinger. Det var avhengig av et sentralt selskap og bankforbindelser. Da selskapet gikk over ende, kunne ikke systemet fortsette som et uavhengig pengenettverk.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) brukte [arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) for å gjøre uønsket e-post kostbar. Avsenderens datamaskin måtte utføre arbeid før den kunne sende en melding. Ideen viste hvordan beregningskostnader kunne motvirke misbruk.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) beskrev et foreslått system der beregningsarbeid kunne skape digitale registreringer med begrenset tilgang. Det ble ikke lansert som et fullstendig desentralisert pengesystem, men utviklet viktige ideer om digital [knapphet](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) og bevis.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) og [**gjenbrukbart arbeidsbevis (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) utforsket måter deltakerne kunne skape eller overføre digital [verdi](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) med begrenset tilgang uten å være avhengige av bare én sentral database. De var ufullstendige, men bidro til å klargjøre hva et fungerende system ville trenge.
* Selv om [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) ikke var penger, viste det at et [likemannsnettverk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) kunne la mange uavhengige datamaskiner dele informasjon uten at én sentral server kontrollerte hele systemet.

Til sammen viste disse eksperimentene nyttige brikker i puslespillet. De tydeliggjorde også problemet som gjensto.


> **Definition – Dobbeltbruk**
>
> [Dobbeltbruk](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) er et forsøk på å sende den samme digitale enheten til to mottakere. Digitale data kan kopieres helt nøyaktig, så et digitalt pengesystem trenger en måte å fastslå hvilken [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) som er gyldig.


[Sentraliserte systemer](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) forhindrer dette ved å la én betrodd database avgjøre hvilken betaling som kom først. Den 31. oktober 2008 ble det i [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto)s hvitbok, [_Bitcoin: Et elektronisk kontantsystem fra likemann til likemann_](https://bitcoin.org/bitcoin.pdf), forklart en annen tilnærming: et offentlig system som kunne etablere en felles betalingshistorikk uten en bank, et selskap eller en annen sentral myndighet.

Hvitboken samlet egenskapene som var nødvendige for denne tilnærmingen:

1. **Et [likemannsnettverk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) kunngjøres direkte til et nettverk av deltakere.
1. **[Digitale signaturer](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** en [privat nøkkel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) er hemmelig informasjon som skaper en signatur for å godkjenne bruk av midler; bare innehaveren kan gjøre dette.
1. **Blokker og [utvinning](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [utvinnere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) samler [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i blokker og bruker [arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) for å konkurrere om å legge til den neste blokken.
1. **Uavhengig [verifisering](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerer [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) og blokker opp mot Bitcoins regler.
1. **En felles historikk med akkumulert [arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** deltakerne anerkjenner den [gyldige kjeden](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) av [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) med mest [akkumulert arbeid](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) som den felles historikken.


<!-- micrographic: five-part-response-01 -->


Denne modulen forklarer disse begrepene mer detaljert. Sammen ga de et praktisk svar på [dobbeltforbruksproblemet](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): nettverket kan avvise et nytt forsøk på å bruke de samme bitcoinene uten å være avhengig av en sentral myndighet. Bitcoin tilbød den manglende kombinasjonen som flere tiår med eksperimenter med digitale penger hadde søkt etter.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
