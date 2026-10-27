# 2.9 Naudotojai, mazgai ir kasėjai

Bitcoin veikia, nes skirtingi dalyviai atlieka skirtingus vaidmenis.

* **Naudotojai** gauna, laiko ir siunčia bitkoinus. Naudotojas gali pats valdyti savo piniginėje laikomus raktus arba naudotis [saugotojo paslaugomis](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Naudotojai suteikia tinklui ekonominę prasmę pasirinkdami, ar priimti bitkoinus ir kuriomis taisyklėmis ar paslaugomis pasitikėti.
* [**Mazgai**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) vykdo Bitcoin programinę įrangą ir savarankiškai tikrina, ar laikomasi taisyklių. [Visavertis mazgas](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) tikrina, ar [sandoriai](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) turi galiojančius parašus, ar bitkoinai dar nebuvo išleisti, ar blokai atitinka [darbo įrodymo reikalavimus](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ir ar nauji bitkoinai išleidžiami pagal [emisijos grafiką](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Mazgai](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) dalijasi tinkamais duomenimis su kitais mazgais ir atmeta netinkamus duomenis.
* [**Kasėjai**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) surenka laukiančius patvirtinimo [sandorius](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), sudaro [kandidatinius blokus](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) ir varžosi pasitelkdami [darbo įrodymą](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Sėkmingas [kasėjas](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [išplatina](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) bloką ir gali gauti leistiną [bloko subsidiją](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) bei [sandorių mokesčius](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Kasėjai](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) padeda nustatyti [sandorių](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) eiliškumą ir padidina [apskaitos registro](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) perrašymo sąnaudas.
* **Kūrėjai** peržiūri, rengia ir siūlo programinės įrangos pakeitimus. Bitcoin taisyklės jiems nepriklauso. Programinės įrangos pakeitimas turi reikšmės tik tuomet, jei dalyviai pasirenka vykdyti tas taisykles atitinkančią programinę įrangą.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Keturi vaidmenys „Bitcoin“ tinkle: naudotojai gauna, laiko ir siunčia bitkoinus, mazgai savarankiškai tikrina, ar laikomasi taisyklių, kasėjai kuria blokus kandidatus atlikdami darbo įrodymo skaičiavimus, o programuotojai siūlo programinę įrangą. Nė vienas vaidmuo atskirai nekontroliuoja tinklo.](/micrographics/bitcoin-participant-roles-01/lt.md)


Šie vaidmenys riboja vienas kitą:

* naudotojas negali išleisti bitkoinų be reikiamo galiojančio parašo
* vienas [kasėjas](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gali pasiūlyti bloką, tačiau [mazgai](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) nusprendžia, ar jis atitinka taisykles
* tinklo [mazgas](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tikrina pagal savo taisykles, tačiau [konsensusui](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) reikia suderinamų taisyklių visame tinkle
* kūrėjai gali siūlyti programinę įrangą, tačiau dalyviai patys sprendžia, ar ją naudoti

Kai kurie žmonės atlieka kelis vaidmenis. [Kasėjas](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gali paleisti [mazgą](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ir kartu būti naudotoju. Pradedančiajam nebūtina atlikti visų vaidmenų, kad galėtų paaiškinti, kaip šie vaidmenys atsveria vienas kitą.

**Trumpas klausimas:** Kodėl [mazgas](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tikrina [sandorius](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Įvardykite bent vieną taisyklę, kurios laikymąsi [mazgas](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tikrina.

![Mokytojas padeda techninių dalykų besimokančiam dalyviui prie mazgo kompiuterio; monitorius atsuktas į juos, o žiūrovui matoma galinė jo korpuso dalis.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
