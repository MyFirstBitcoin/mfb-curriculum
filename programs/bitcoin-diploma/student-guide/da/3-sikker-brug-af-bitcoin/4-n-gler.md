# 3.4 Nøgler

Ejerskab af Bitcoin sikres gennem kryptografiske nøgler.


> **Definition – Privat nøgle**
>
> En [privat nøgle](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) er hemmelig information, der gør det muligt for en wallet at oprette gyldige [digitale signaturer](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). En signatur godkender brugen af de bitcoin, der kontrolleres af den tilhørende nøgle. Enhver, der får fat i den [private nøgle](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) kan som regel bruge disse midler.


En [**offentlig nøgle**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) udledes matematisk af den [private nøgle](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Den hjælper med at verificere en signatur uden at afsløre den [private nøgle](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adresser oprettes ud fra [offentlige nøglers](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) oplysninger.

Den grundlæggende regel er enkel:

**Offentlige oplysninger til modtagelse kan deles. Private oplysninger til brug af midler skal holdes hemmelige.**

En [digital signatur](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) beviser, at den nødvendige [private nøgle](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) har godkendt en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Den placerer ikke den [private nøgle](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) i selve [transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verificerer signaturen, før de accepterer brugen af midlerne.

De fleste wallets til begyndere bruger [enkeltsignatur](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): én privat nøgle godkender en transaktion. Moderne wallets håndterer automatisk mange nøgler. Begyndere bør ikke kopiere eller håndtere enkelte [private nøgler](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) i strengformat. Beskyt walletens godkendte sikkerhedskopi, og følg dens gendannelsesprocedure.

Ingen legitim underviser, walletvirksomhed, børsmedarbejder, teknisk supportmedarbejder eller Bitcoin-udvikler har brug for Deres [private nøgle](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) eller [seedfrase](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Enhver, der beder om disse oplysninger, bør betragtes som en trussel.


> **Light**
>
> **Prøv selv:** Sortér de forberedte eksempler i tre grupper: oplysninger, der trygt kan deles til modtagelse, hemmelige oplysninger til brug af midler og oplysninger, der kan være offentlige, men som alligevel bør holdes private, når de er knyttet til en person.



<!-- micrographic: private-key-public-info-01 -->
