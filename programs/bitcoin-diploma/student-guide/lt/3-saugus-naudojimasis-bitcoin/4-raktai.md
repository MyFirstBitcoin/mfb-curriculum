# 3.4 Raktai

Bitcoin nuosavybė užtikrinama kriptografiniais raktais.


> **Definition – Privatusis raktas**
>
> Toks [privatusis raktas](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) yra slapta informacija, leidžianti piniginei sukurti galiojančius [skaitmeninius parašus](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Parašas suteikia leidimą išleisti atitinkamu raktu valdomus bitkoinus. Bet kas, gavęs [privatųjį raktą](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key), paprastai gali išleisti tas lėšas.


Toks [**viešasis raktas**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) matematiškai išvedamas iš [privačiojo rakto](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Jis padeda patikrinti parašą neatskleidžiant [privačiojo rakto](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adresai kuriami iš [viešojo rakto](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) informacijos.

Pagrindinė taisyklė paprasta:

**Vieša informacija, skirta lėšoms gauti, galima dalytis. Privati informacija, skirta lėšoms išleisti, turi likti slapta.**

Toks [skaitmeninis parašas](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) įrodo, kad reikiamas [privatusis raktas](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) suteikė leidimą vykdyti [sandorį](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Jis neįtraukia [privačiojo rakto](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) į [sandorį](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Mazgai](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) patikrina parašą prieš patvirtindami lėšų išleidimą.

Dauguma pradedantiesiems skirtų piniginių naudoja [vieno parašo schemą](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): vienas privatusis raktas suteikia leidimą vykdyti sandorį. Šiuolaikinės piniginės automatiškai valdo daugybę raktų. Pradedantieji neturėtų kopijuoti ar tvarkyti atskirų [privačiųjų raktų](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) simbolių eilučių. Saugokite piniginės patvirtintą atsarginę kopiją ir laikykitės jos atkūrimo procedūros.

Jokiam sąžiningai veikiančiam pedagogui, piniginės paslaugų įmonei, keityklos darbuotojui, techninės pagalbos specialistui ar Bitcoin kūrėjui nereikia jūsų [privačiojo rakto](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ar [atkūrimo frazės](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Bet ką, kas prašo šios informacijos, reikėtų laikyti grėsme.


> **Light**
>
> **Išbandykite:** Suskirstykite parengtus pavyzdžius į tris grupes: informacija, kuria saugu dalytis norint gauti lėšų, slapta informacija, skirta lėšoms išleisti, ir informacija, kuri gali būti vieša, bet susieta su asmeniu vis tiek turėtų būti laikoma privačia.



<!-- micrographic: private-key-public-info-01 -->
