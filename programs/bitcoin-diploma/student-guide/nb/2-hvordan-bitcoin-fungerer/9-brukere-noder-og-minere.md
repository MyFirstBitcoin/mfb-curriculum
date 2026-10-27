# 2.9 Brukere, noder og minere

Bitcoin fungerer fordi ulike deltakere utfører ulike roller.

* **Brukere** mottar, oppbevarer og sender bitcoin. En bruker kan kontrollere sine egne nøkler som er lagret i en lommebok, eller bruke en [forvalter](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Brukere gir nettverket økonomisk betydning ved å velge om de vil godta bitcoin, og hvilke regler eller tjenester de stoler på.
* [**Noder**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kjører Bitcoin-programvare og verifiserer reglene uavhengig av andre. En [fullnode](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) kontrollerer at [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) har gyldige signaturer, at bitcoin ikke allerede er brukt, at blokker oppfyller kravene til [arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), og at nye bitcoin følger [utstedelsesplanen](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) deler gyldige data med andre noder og avviser ugyldige data.
* [**Ut vinnere**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) samler ventende [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), bygger [kandidatblokker](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) og konkurrerer gjennom [arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). En vellykket [utvinner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [kringkaster](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) en blokk og kan motta det tillatte [blokktilskuddet](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) og [transaksjonsgebyrene](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Utvinnere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bidrar til å bestemme rekkefølgen på [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) og gjør [hovedboken](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) kostbar å skrive om.
* **Utviklere** gjennomgår, skriver og foreslår endringer i programvaren. De eier ikke reglene til Bitcoin. En programvareendring har bare betydning hvis deltakerne velger å kjøre programvare som følger disse reglene.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Fire roller i Bitcoin: Brukere mottar, oppbevarer og sender bitcoin, noder kontrollerer uavhengig at reglene følges, utvinnere bygger kandidatblokker med arbeidsbevis, og utviklere foreslår programvare. Ingen enkeltrolle kontrollerer nettverket.](/micrographics/bitcoin-participant-roles-01/nb.md)


Disse rollene begrenser hverandre:

* en bruker kan ikke bruke bitcoin uten den nødvendige gyldige signaturen
* en [utvinner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan foreslå en blokk, men [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) avgjør om den følger reglene
* en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifiserer etter sine egne regler, men [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) krever kompatible regler i hele nettverket
* utviklere kan foreslå programvare, men deltakerne velger om de vil kjøre den

Noen personer har flere roller. En [utvinner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan kjøre en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) og også være bruker. En nybegynner trenger ikke å ha alle rollene for å forklare hvordan rollene balanserer hverandre.

**Kontrollspørsmål:** Hvorfor utfører en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifisering av [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Oppgi minst én regel som en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerer.

![Læreren veileder den teknisk orienterte eleven ved en datamaskin som kjører en node, med skjermen vendt mot dem og baksiden av skjermen synlig for betrakteren.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
