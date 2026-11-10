# 3.4 Nøkler

Eierskap til bitcoin håndheves gjennom kryptografiske nøkler.


<!-- card: definition -->
> **Definition – Privat nøkkel**
>
> En [privat nøkkel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) er hemmelig informasjon som gjør det mulig for en lommebok å opprette gyldige [digitale signaturer](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). En signatur godkjenner bruk av bitcoin som kontrolleres av den tilhørende nøkkelen. Alle som får tak i den [private nøkkelen](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) kan vanligvis bruke disse midlene.


En [**offentlig nøkkel**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) utledes matematisk fra den [private nøkkelen](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Den gjør det mulig å verifisere en signatur uten å avsløre den [private nøkkelen](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adresser opprettes fra [offentlig nøkkelbasert](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) informasjon.

Den grunnleggende regelen er enkel:

**Offentlig mottaksinformasjon kan deles. Privat informasjon som gir tilgang til å bruke midler, må holdes hemmelig.**

En [digital signatur](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) beviser at den nødvendige [private nøkkelen](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) godkjente en [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Den legger ikke den [private nøkkelen](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) inn i [transaksjonen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifiserer signaturen før de godtar bruken av midlene.

De fleste lommebøker for nybegynnere bruker [enkeltsignatur](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): én privat nøkkel godkjenner en transaksjon. Moderne lommebøker håndterer mange nøkler automatisk. Nybegynnere bør ikke kopiere eller håndtere individuelle [private nøkler](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) som tekststrenger. Beskytt lommebokens godkjente sikkerhetskopi og følg gjenopprettingsprosedyren.

Ingen legitim underviser, lommebokleverandør, børsansatt, teknisk støttemedarbeider eller Bitcoin-utvikler trenger Deres [private nøkkel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) eller [gjenopprettingsfrase](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Alle som ber om dette, bør betraktes som en trussel.


<!-- card: light -->
> **Prøv selv:** Sorter ferdiglagde eksempler i tre grupper: informasjon som trygt kan deles for å motta midler, hemmelig informasjon som gir tilgang til å bruke midler, og informasjon som kan være offentlig, men som likevel bør holdes privat når den er knyttet til en person.



<!-- micrographic: private-key-public-info-01 -->
[En hemmelig privat nøkkel, som aldri må deles, danner grunnlaget for offentlig informasjon som kan deles: en offentlig nøkkel avledet fra den og en mottaksadresse opprettet fra denne. Den samme private nøkkelen oppretter signaturer som noder verifiserer uten noen gang å få kjennskap til den private nøkkelen.](/micrographics/private-key-public-info-01/nb.md)
