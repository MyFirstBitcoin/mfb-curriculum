# 3.11 Verifisering, blokkutforskere og irreversible transaksjoner

<!-- card: definition -->
> **Definition – Transaksjons-ID og blokkutforsker**
>
> En [transaksjons-ID](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identifiserer en kjedebasert [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). En [blokkutforsker](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) viser offentlige Bitcoin-data, som en [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)s status og [bekreftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) totalt. Den gir nyttig innsyn, men er ikke en autoritet over Bitcoin og heller ikke et bevis på mottakerens identitet eller ærlighet.


Hva kan denne offentlige informasjonen vise, og hva kan den ikke vise? Den kan vise en [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)s status, mottakeradresse, beløp, gebyr og [bekreftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) totalt; den kan ikke bevise hvorfor en betaling fant sted, eller om en person er til å stole på. En kjedebasert [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) er ubekreftet etter at den er [kringkastet](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) og får sin [første bekreftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) når den tas med i en gyldig blokk. Senere blokker styrker tilliten til dens plass i historikken, men de retter ikke opp en feil mottakeradresse eller svindel. Det finnes ikke noe universelt krav til [bekreftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) totalt for alle betalinger; hva som er en passende kontroll, avhenger av beløpet og risikoen.

For å undersøke en klargjort [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), finn dens [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), åpne en pålitelig utforsker for det aktuelle [Bitcoin-nettverket](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network), og kontroller status, mottakeradresse, beløp, gebyr og [bekreftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). En utforsker er bare et grensesnitt. Søk etter en adresse eller [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) kan avsløre for operatøren at Deres enhet er interessert i denne informasjonen. Bruk en underviserklargjort [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) eller et utskrevet skjermbilde til øving. Ikke søk etter en elevs personlige adresse eller [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) på en offentlig tjeneste. Hvis De senere undersøker en personlig betaling, sett Dem inn i hvilke [personvern](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy)- og sikkerhetsmessige [avveininger](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) tilkoblingen Deres innebærer, før De bruker en offentlig tjeneste.


<!-- card: callout -->
> **Offentlige data er ikke bevis på identitet eller ærlighet**
>
> En [blokkutforsker](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) kan vise offentlige [transaksjonsrelaterte](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) data, men den kan ikke bevise hvem som kontrollerer en adresse, hvorfor en betaling fant sted, eller om en mottaker er pålitelig. Bruk forberedte eksempler til øving og ivareta [personvernet](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) ved søk på offentlige tjenester.



<!-- micrographic: confirmation-timeline-01 -->
[En transaksjon venter ubekreftet i transaksjonskøen, blir deretter inkludert i blokk N og får sin første bekreftelse, og hver påfølgende blokk legger til én bekreftelse til.](/micrographics/confirmation-timeline-01/nb.md)


![Læreren og den eldre deltakeren diskuterer et forberedt eksempel på en skjerm som vender mot gruppen, mens den teknisk kyndige deltakeren bruker musen; betrakteren ser baksiden av skjermen.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
