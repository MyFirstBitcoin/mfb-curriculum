# 3.6 Brug med og uden tredjepartsopbevaring

<!-- card: definition -->
> **Definition – Opbevaring**
>
> [Opbevaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) besvarer et praktisk spørgsmål: Hvem kontrollerer de nøgler, der kræves for at bruge bitcoinene?


I en **depotbaseret** tjeneste kontrollerer en virksomhed eller en anden person nøglerne. Den viste saldo er et løfte fra [depotudbyderen](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). De logger normalt ind med en konto og beder tjenesten om at behandle en hævning eller betaling.

Denne forskel er vigtig for verificering. Bitcoins regler og samlede udbud kan kontrolleres uafhængigt, men hvis De ikke kontrollerer nøglerne, kan De ikke uafhængigt kontrollere, at saldoen på Deres konto svarer til bitcoin, som tjenesten ligger inde med og vil stille til Deres rådighed. Den offentlige blockchain kan vise bitcoin, der kontrolleres af nøgler; den kan ikke vise, at en tjeneste skylder en bestemt kunde den saldo, der vises på en konto. Indtil De kan hæve og kontrollere nøglerne, er Deres saldo tjenestens løfte om at stille bitcoin til rådighed, ikke bitcoin, som De selv kan verificere direkte og bruge.

I en **ikke-depotbaseret** eller **selvforvaltet** wallet kontrollerer DE nøglerne. Walleten underskriver [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) med Deres bemyndigelse. Der kan stadig være afhængigheder af software, hardware, servere eller netværk, men ingen [depotudbyder](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) skal godkende en gyldig anvendelse af midler på blockchainen.

![](https://cdn.sanity.io/images/vje9ehw2/production/f93df0cc4a2ad82b3410a9ad4c3273d1b760f8ea-1774x887.svg)


<!-- micrographic: who-controls-keys-01 -->
[Ved tredjepartsopbevaring kontrollerer en tjeneste nøglerne og godkender betalinger, så saldoen er tjenestens løfte. Ved egenopbevaring kontrollerer brugeren nøglerne og sikkerhedskopierne; begge fremgangsmåder indebærer afhængigheder og risiko for svigt.](/micrographics/who-controls-keys-01/da.md)



<!-- micrographic: custody-comparison-table-01 -->
[En tabel, der sammenligner brug med tredjepartsopbevaring og egenopbevaring: hvem der har nøglerne, hvem der håndterer gendannelse, og den vigtigste afvejning ved hver model. Ingen af modellerne er risikofri.](/micrographics/custody-comparison-table-01/da.md)


[Opbevaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) fremgår ikke altid tydeligt af brugergrænsefladen. Hvis De ikke kan kontrollere gendannelsesmetoden og har brug for en virksomheds godkendelse af en hævning, bruger De sandsynligvis en [depotudbyder](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). [Selvforvaltning](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody) er ikke en prøve på personligt værd; det vigtige skridt er at identificere den tillid og risiko, der er forbundet med løsningen.

**Prøv selv:** Læs to forberedte beskrivelser af wallets. Angiv for hver af dem, hvem der kontrollerer nøglerne, hvem der ville kunne gendanne adgangen, og én risiko, De bør undersøge, før De bruger den.
