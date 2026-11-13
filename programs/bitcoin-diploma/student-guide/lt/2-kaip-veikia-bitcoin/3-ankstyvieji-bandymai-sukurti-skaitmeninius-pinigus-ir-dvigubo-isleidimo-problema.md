# 2.3 Ankstyvieji bandymai sukurti skaitmeninius pinigus ir dvigubo išleidimo problema

Bitcoin nebuvo pirmasis bandymas sukurti skaitmeninius pinigus. Jis buvo sukurtas remiantis keturis dešimtmečius trukusiais eksperimentais ir daugelio ankstesnių projektų idėjomis, padėjusiomis suformuoti sėkmingą jo struktūrą.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) naudojo [kriptografiją](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) privatiems skaitmeniniams mokėjimams užtikrinti. Ši sistema priklausė nuo vienos centrinės įmonės ir ryšių su bankais. Įmonei žlugus, sistema negalėjo toliau veikti kaip nepriklausomas pinigų tinklas.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) naudojo [darbo įrodymą](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) tam, kad nepageidaujamų el. laiškų siuntimas pareikalautų sąnaudų. Prieš išsiųsdamas žinutę, siuntėjo kompiuteris turėjo atlikti skaičiavimo darbą. Ši idėja parodė, kaip skaičiavimo sąnaudos galėtų atgrasyti nuo piktnaudžiavimo.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) aprašė siūlomą sistemą, kurioje skaičiavimo darbu būtų galima kurti riboto kiekio skaitmeninius įrašus. Ji nebuvo paleista kaip visavertė decentralizuotų pinigų sistema, tačiau joje buvo išplėtotos svarbios idėjos apie skaitmeninį [ribotumą](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) ir įrodymą.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) ir [**pakartotinai naudojamas darbo įrodymas (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) tyrinėjo būdus, kaip dalyviai galėtų kurti ar perduoti ribotą skaitmeninę [vertę](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) nepasikliaudami vien tik viena centrine duomenų baze. Šie projektai nebuvo užbaigti, tačiau padėjo išsiaiškinti, ko reikėtų veikiančiai sistemai.
* Nors [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) nebuvo pinigai, jis parodė, kad [lygiaverčių dalyvių tinklas](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) galėtų leisti daugeliui nepriklausomų kompiuterių dalytis informacija be vieno centrinio serverio, valdančio visą sistemą.

Visi šie eksperimentai atskleidė naudingas bendro sprendimo dalis. Jie taip pat padėjo aiškiau suprasti likusią problemą.


<!-- card: definition -->
> **Definition – Dvigubas išleidimas**
>
> [Dvigubas išleidimas](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) yra bandymas tą patį skaitmeninį vienetą nusiųsti dviem gavėjams. Skaitmeninius duomenis galima tobulai nukopijuoti, todėl skaitmeninių pinigų sistemai reikia būdo nustatyti, kuris [sandoris](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) yra galiojantis.


[Centralizuotos sistemos](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) užkerta tam kelią leisdamos vienai patikimai duomenų bazei nuspręsti, kuris mokėjimas buvo atliktas pirmas. 2008 m. spalio 31 d. [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) baltojoje knygoje „[_Bitcoin: lygiaverčių dalyvių elektroninių grynųjų pinigų sistema_](https://bitcoin.org/bitcoin.pdf)“ paaiškintas kitoks požiūris: vieša sistema, kuri galėtų nustatyti bendrą mokėjimų istoriją be banko, įmonės ar kitos centrinės institucijos.

Baltojoje knygoje buvo sujungtos šiam požiūriui įgyvendinti reikalingos savybės:

1. **Vienas [lygiaverčių dalyvių tinklas](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [sandoriai](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) skelbiami tiesiogiai dalyvių tinkle.
1. **[Skaitmeniniai parašai](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** vienas [privatusis raktas](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) yra slapta informacija, kuria sukuriamas parašas, leidžiantis išleisti lėšas; tai gali padaryti tik jo turėtojas.
1. **Blokai ir [kasyba](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [kasėjai](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) renka [sandorius](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) į blokus ir naudoja [darbo įrodymą](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) konkuruodami dėl teisės pridėti kitą bloką.
1. **Nepriklausomas [tikrinimas](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [mazgai](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tikrina [sandorius](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ir blokus pagal Bitkoino taisykles.
1. **Bendra istorija su sukauptu [darbo įrodymu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** dalyviai pripažįsta [galiojančią grandinę](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) iš [sandorių](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), turinčią daugiausia [sukaupto darbo](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) bendru įrašu.


<!-- micrographic: five-part-response-01 -->
[Penkios dalys kartu išsprendžia dvigubo lėšų panaudojimo problemą: lygiarangių tinklas, skaitmeniniai parašai, blokai ir kasimas, nepriklausomas tikrinimas ir bendra istorija, kurioje sukaupta daugiausia darbo įrodymų. Kartu jos leidžia tinklui atmesti pakartotinį tų pačių lėšų panaudojimą be centrinės institucijos.](/micrographics/five-part-response-01/lt.md)


Šiame modulyje šios sąvokos aiškinamos išsamiau. Kartu jos suteikė praktinį sprendimą, kaip išspręsti [dvigubo išleidimo problemą](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): tinklas gali atmesti antrą bandymą išleisti tą patį bitkoiną, nesiremdamas centrine institucija. Bitkoinas pasiūlė trūkstamą derinį, kurio dešimtmečius buvo ieškoma eksperimentuojant su skaitmeniniais pinigais.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
