# 3.14 On-chain- og Lightning-betalinger

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Betalinger på kjeden og via Lightning**
>
> [Betalinger på kjeden](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) registreres i Bitcoins [blokkjede](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) og får [bekreftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning er et betalingsnettverk bygget på Bitcoin som kan støtte raske, hyppige betalinger. En Lightning-betaling kan fullføres raskt eller mislykkes, og lommeboken som brukes, kan likevel være forvaltet av en tredjepart eller selvforvaltet.



> **Dark – Betalingsveien avgjør ikke hvem som har kontroll over midlene**
>
> Betalinger på kjeden og via Lightning innebærer ulike [avveininger](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). En Lightning-lommebok kan være forvaltet av en tredjepart eller selvforvaltet, og en rask, vellykket betaling beviser ikke at en tjeneste er egnet for større saldoer eller enhver situasjon.



<!-- micrographic: onchain-lightning-table-01 -->


Hvilken betalingsvei forventer mottakeren? Bekreft om mottakeren har oppgitt en adresse på kjeden eller en [Lightning-faktura](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) eller betalingsforespørsel før De betaler. En lommebok for betalinger på kjeden kan ikke betale enhver [Lightning-faktura](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) direkte, og en Lightning-lommebok støtter ikke nødvendigvis alle handlinger på kjeden. Noen applikasjoner støtter begge betalingsveiene, men kan medføre ekstra gebyrer eller avhengighet av tjenester. Detaljert oppsett av Lightning, kanaler, ruting og [likviditet](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) hører til [fordypning](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); praktiske øvelser med reelle betalinger lokalt hører hjemme i **modul 4** når det er trygt og hensiktsmessig.

Forestill Dem at et forberedt scenario tilbyr begge betalingsveiene. Hvilken betalingsforespørsel kan den tiltenkte lommeboken bruke, og hva ville De kontrollert før De godkjenner den? Svaret avhenger av betalingsforespørselen fra mottakeren, lommeboken og situasjonen — ikke av en universelt «beste» betalingsvei.

![Underviseren peker på to forskjellige geometriske betalingsveier på en tavle mens nybegynneren og de teknisk kyndige deltakerne vurderer dem.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
