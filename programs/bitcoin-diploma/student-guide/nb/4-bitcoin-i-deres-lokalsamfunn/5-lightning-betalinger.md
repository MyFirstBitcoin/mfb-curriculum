# 4.5 Lightning-betalinger

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Mottakeren oppretter en Lightning-betalingsforespørsel med beløpet angitt på telefonen sin, avsenderen skanner den og betaler, og betalingen kommer frem til mottakerens telefon et øyeblikk senere.](/micrographics/lightning-phone-payment-01/nb.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[En Lightning-betaling i seks trinn: Mottakeren oppretter en forespørsel, avsenderen skanner den, kontrollerer mottaker, beløp, enhet, utløpstidspunkt og gebyr og godkjenner betalingen. Betalingen rutes, og begge lommebøkene viser resultatet. Hver lommebok kan være tredjepartsforvaltet eller selvforvaltet, og ved en mislykket eller utløpt betaling starter prosessen på nytt med en ny forespørsel.](/micrographics/lightning-payment-sequence-01/nb.md)


Lightning kan gjøre raske, små Bitcoin-betalinger praktiske. Det kan være egnet ved en butikkdisk, til gjentatte lokale betalinger, nettjenester eller overføringer der et gebyr på kjeden ville vært for stort i forhold til betalingen.

En lokal Lightning-demonstrasjon bør avklare:

* om lommeboken forvaltes av en tredjepart eller av brukeren selv
* hvordan lommeboken fylles opp
* om påfylling krever en kjedebasert [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) eller en tjeneste
* hvilken sikkerhetskopiering eller gjenopprettingsmulighet som beskytter saldoen
* hvilken type betalingsforespørsel som brukes
* hvilke gebyrer eller begrensninger som gjelder
* hva som skjer når en betaling mislykkes
* hvordan mottakeren bekrefter betalingen

En [**Lightning-faktura**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) er en betalingsforespørsel opprettet for en bestemt betaling. Den kan inneholde et beløp, opplysninger om mottaker og et utløpstidspunkt. Les lommebokens [bekreftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) på skjermen før De betaler.

En [**Lightning-adresse**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) er en identifikator som er lesbar for mennesker og støttes av enkelte tjenester. Den kan se ut som en e-postadresse, men er en praktisk måte å rute betalinger på, ikke en e-postkonto. Den er avhengig av leverandøren eller domenet som støtter den.

For en veiledet betaling:

1. Mottakeren oppretter den riktige forespørselen.
1. Avsenderen skanner eller kopierer den.
1. Avsenderen kontrollerer mottakeren, beløpet, enheten og gebyret.
1. Avsenderen godkjenner først når opplysningene er riktige.
1. Begge parter bekrefter resultatet i sine egne lommebøker.
1. Gruppen forklarer risikoene knyttet til [oppbevaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) og betalingsfeil.

Ikke anta at en vellykket Lightning-betaling beviser at lommeboken er trygg for større saldoer. Enkle betalinger og [oppbevaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) med god sikkerhet er to forskjellige spørsmål.
