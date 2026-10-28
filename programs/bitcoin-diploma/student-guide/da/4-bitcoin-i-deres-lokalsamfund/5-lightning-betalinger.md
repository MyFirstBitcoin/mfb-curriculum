# 4.5 Lightning-betalinger

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Modtageren opretter en Lightning-betalingsanmodning med beløbet angivet på sin telefon, afsenderen scanner den og betaler, og betalingen når frem til modtagerens telefon et øjeblik senere.](/micrographics/lightning-phone-payment-01/da.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[En Lightning-betaling i seks trin: Modtageren opretter en anmodning, afsenderen scanner den, kontrollerer modtager, beløb, enhed, udløbstidspunkt og gebyr og godkender betalingen, som sendes gennem netværket, og begge wallets viser resultatet. Hver wallet kan være tredjepartsforvaltet eller selvforvaltet, og ved en mislykket eller udløbet betaling begynder forløbet igen med en ny anmodning.](/micrographics/lightning-payment-sequence-01/da.md)


Lightning kan gøre hurtige, små Bitcoin-betalinger praktisk anvendelige. Det kan være velegnet ved en butiks kasse, til gentagne lokale betalinger, onlinetjenester eller overførsler, hvor et on-chain-gebyr ville være for stort i forhold til betalingen.

En lokal demonstration af Lightning bør afklare:

* om en tredjepart eller brugeren selv har kontrollen over walletens midler
* hvordan der tilføres midler til walleten
* om tilførsel af midler kræver en on-chain [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) eller en tjeneste
* hvilken sikkerhedskopiering eller gendannelse der beskytter saldoen
* hvilken type betalingsanmodning der bruges
* hvilke gebyrer eller grænser der gælder
* hvad der sker, når en betaling mislykkes
* hvordan modtageren bekræfter betalingen

En [**Lightning-faktura**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) er en betalingsanmodning, der er oprettet til en bestemt betaling. Den kan indeholde et beløb, oplysninger om destinationen og et udløbstidspunkt. Læs walletens [bekræftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) på skærmen, før De betaler.

En [**Lightning-adresse**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) er en identifikator, som mennesker kan læse, og som understøttes af nogle tjenester. Den kan ligne en e-mailadresse, men den er en praktisk hjælp til at dirigere betalinger, ikke en e-mailkonto. Den afhænger af den udbyder eller det domæne, der understøtter den.

Ved en betaling under vejledning:

1. Modtageren opretter den korrekte anmodning.
1. Afsenderen scanner eller kopierer den.
1. Afsenderen kontrollerer modtageren, beløbet, enheden og gebyret.
1. Afsenderen godkender først, når oplysningerne er korrekte.
1. Begge parter bekræfter resultatet i deres egne wallets.
1. Gruppen forklarer [opbevaringsrisici](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) og risici ved betalingsfejl.

Antag ikke, at en vellykket Lightning-betaling beviser, at walleten er sikker til større saldi. Betalingsbekvemmelighed og [opbevaringens](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) sikkerhed er to forskellige spørgsmål.
