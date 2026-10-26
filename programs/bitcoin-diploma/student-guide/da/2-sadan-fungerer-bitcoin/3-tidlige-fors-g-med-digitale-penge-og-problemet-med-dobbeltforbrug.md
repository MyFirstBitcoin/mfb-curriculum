# 2.3 Tidlige forsøg med digitale penge og problemet med dobbeltforbrug

Bitcoin var ikke det første forsøg på at skabe digitale penge. Det byggede på fire årtiers eksperimenter og trak på idéer fra mange tidligere projekter, som var med til at forme dets vellykkede design.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) brugte [kryptografi](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) til at understøtte private digitale betalinger. Det var afhængigt af en central virksomhed og forbindelser til banker. Da virksomheden gik konkurs, kunne systemet ikke fortsætte som et uafhængigt pengenetværk.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) brugte [arbejdsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) til at gøre det dyrt at sende uønsket e-mail. Afsenderens computer skulle udføre arbejde, før den kunne sende en besked. Idéen viste, hvordan beregningsomkostninger kunne modvirke misbrug.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) beskrev et foreslået system, hvor beregningsarbejde kunne skabe digitale registreringer i begrænset mængde. Det blev ikke lanceret som et fuldt udviklet decentraliseret pengesystem, men det udviklede vigtige idéer om digital [knaphed](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) og bevisførelse.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) og [**genanvendeligt arbejdsbevis (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) undersøgte metoder, der kunne lade deltagere skabe eller overføre knap digital [værdi](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) uden udelukkende at være afhængige af én central database. De var ufuldstændige, men var med til at tydeliggøre, hvad et fungerende system ville kræve.
* Selvom [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) ikke var penge, viste det, at et [peer-to-peer-netværk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) kunne lade mange uafhængige computere dele information, uden at én central server styrede hele systemet.

Tilsammen viste disse eksperimenter nyttige brikker i puslespillet. De tydeliggjorde også det problem, der stadig manglede at blive løst.


> **Definition – Dobbeltforbrug**
>
> [Dobbeltforbrug](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) er et forsøg på at sende den samme digitale enhed til to modtagere. Digitale data kan kopieres nøjagtigt, så et digitalt pengesystem har brug for en metode til at fastslå, hvilken [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) der er gyldig.


[Centraliserede systemer](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) forhindrer dette ved at lade én betroet database afgøre, hvilken betaling der kom først. Den 31. oktober 2008 forklarede [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto)s hvidbog, [_Bitcoin: Et elektronisk peer-to-peer-kontantsystem_](https://bitcoin.org/bitcoin.pdf), en anden tilgang: et offentligt system, der kunne etablere en fælles betalingshistorik uden en bank, en virksomhed eller en anden central myndighed.

Hvidbogen samlede de egenskaber, der var nødvendige for denne tilgang:

1. **Et [peer-to-peer-netværk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) meddeles direkte til et netværk af deltagere.
1. **[Digitale signaturer](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** en [privat nøgle](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) er hemmelig information, der skaber en signatur for at godkende et forbrug; kun indehaveren kan gøre dette.
1. **Blokke og [mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [minere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) samler [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i blokke og bruger [arbejdsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) til at konkurrere om at tilføje den næste blok.
1. **Uafhængig [verifikation](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerer [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) og blokke i forhold til Bitcoins regler.
1. **En fælles historik med akkumuleret [arbejdsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** deltagerne anerkender den [gyldige kæde](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) af [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) med mest [akkumuleret arbejde](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) som den fælles historik.


<!-- micrographic: five-part-response-01 -->


Dette modul forklarer disse begreber mere detaljeret. Tilsammen gav de en praktisk løsning på [dobbeltforbrugsproblemet](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): netværket kan afvise et nyt forsøg på at bruge den samme bitcoin uden at være afhængigt af en central myndighed. Bitcoin tilbød den manglende kombination, som årtiers eksperimenter med digitale penge havde søgt efter.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
