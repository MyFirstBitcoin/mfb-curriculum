# 8.10 Brugere, noder, minere, udviklere og tjenester

Brug disse præcise afgrænsninger for begyndere:


| Rolle | Primær funktion på begynderniveau | Betyder ikke |
| --- | --- | --- |
| Bruger | Vælger at modtage, opbevare, sende, verificere og acceptere bitcoin, direkte eller gennem tjenester | Driver automatisk alle dele af netværket |
| Node | Kontrollerer selvstændigt transaktioner og blokke i forhold til sine regler og videresender gyldige data | Opretter nye blokke eller dikterer regler for alle |
| Miner | Bygger kandidatblokke og udfører proof of work for at foreslå deres rækkefølge | Kan gøre ugyldig udstedelse eller ugyldige transaktioner gyldige for ærlige noder |
| Udvikler | Gennemgår, skriver og foreslår software | Kan tvinge deltagere til at indføre en regelændring |
| Bitcoin-tjeneste | Tilbyder en wallet, en børs, en blokudforsker, en betalingsgrænseflade eller en anden grænseflade | Er selve Bitcoin-protokollen |



<!-- micrographic: bitcoin-participant-roles-01 -->
[Fire roller i Bitcoin: Brugere modtager, opbevarer og sender bitcoin, noder verificerer uafhængigt reglerne, minere opbygger kandidatblokke med proof of work, og udviklere foreslår software. Ingen enkelt rolle kontrollerer netværket.](/micrographics/bitcoin-participant-roles-01/da.md)


#### Aktivitet: ugyldig blok

Giv en kursist, der spiller rollen som [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner), en [kandidatblok](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block), der skaber et større bloktilskud, end [nodens](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) regelkort tillader. Kursister, der spiller rollen som [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node), kontrollerer den og afviser den.

Opsamling:

* Denne [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) udførte reelt arbejde, men fik alligevel ikke tilladelse til at bryde reglerne.
* [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) anvender regler selvstændigt, men det virkelige netværk består af software og kommunikation, ikke en afstemning i klassen.
* En udvikler kan skrive andre regler, men det er frivilligt at indføre dem, og uforenelige regler kan skabe et separat netværk.

Spørg:

> Hvorfor skal en [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verificere transaktioner? Nævn mindst én regel, den kontrollerer.
