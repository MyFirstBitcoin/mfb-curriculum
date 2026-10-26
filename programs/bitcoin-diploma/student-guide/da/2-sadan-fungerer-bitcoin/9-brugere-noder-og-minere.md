# 2.9 Brugere, noder og minere

Bitcoin fungerer, fordi forskellige deltagere udfører forskellige roller.

* **Brugere** modtager, opbevarer og sender bitcoin. En bruger kan selv kontrollere sine nøgler i en wallet eller benytte en [depotudbyder](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Brugere giver netværket økonomisk betydning ved at vælge, om de vil acceptere bitcoin, og hvilke regler eller tjenester de har tillid til.
* [**Noder**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kører Bitcoin-software og verificerer reglerne uafhængigt. En [fuld node](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) kontrollerer, at [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) har gyldige signaturer, at bitcoin ikke allerede er blevet brugt, at blokke opfylder kravene til [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), og at nye bitcoin følger [udstedelsesplanen](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) deler gyldige data med andre noder og afviser ugyldige data.
* [**Minere**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) samler ventende [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), bygger [kandidatblokke](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) og konkurrerer gennem [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). En succesfuld [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [udsender](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) en blok og kan modtage det tilladte [bloktilskud](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) og [transaktionsgebyrer](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Minere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) hjælper med at fastlægge rækkefølgen af [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) og gør [hovedbogen](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) dyr at omskrive.
* **Udviklere** gennemgår, skriver og foreslår softwareændringer. De ejer ikke Bitcoins regler. En softwareændring har kun betydning, hvis deltagerne vælger at køre software, der følger disse regler.


<!-- micrographic: bitcoin-participant-roles-01 -->


Disse roller begrænser hinanden:

* en bruger kan ikke bruge bitcoin uden den påkrævede gyldige signatur
* en [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan foreslå en blok, men [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) afgør, om den følger reglerne
* en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verificerer ud fra sine egne regler, men [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) kræver kompatible regler på tværs af netværket
* udviklere kan foreslå software, men deltagerne vælger selv, om de vil køre den

Nogle personer varetager flere roller. En [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan køre en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) og samtidig være bruger. En begynder behøver ikke at varetage alle roller for at forklare, hvordan rollerne afbalancerer hinanden.

**Kontrolspørgsmål:** Hvorfor skal en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verificere [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Nævn mindst én regel, som en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerer.

![Underviseren vejleder den teknisk orienterede kursist ved en nodecomputer, med skærmen vendt mod dem og skærmens bagside synlig for beskueren.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
