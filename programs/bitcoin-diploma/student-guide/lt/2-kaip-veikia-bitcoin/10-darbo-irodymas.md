# 2.10 Darbo įrodymas

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Darbo įrodymas**
>
> [Darbo įrodymas](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) – tai procesas, kurį [kasėjai](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) naudoja varžydamiesi dėl teisės pasiūlyti kitą bloką.


Duomenų [maišos funkcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) paverčia duomenis fiksuoto ilgio rezultatu. Nedidelis įvesties pakeitimas sukuria nenuspėjamą naują rezultatą. [Kasėjas](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pakeičia nedidelę duomenų dalį siūlomame bloke ir pakartotinai skaičiuoja jo maišos reikšmę. Rezultatas galioja tik tada, kai jo skaitinė reikšmė yra mažesnė už tinklo [tikslinę reikšmę](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), taisyklėmis nustatytą ribą; mažesnė [tikslinė reikšmė](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) reiškia mažiau [galiojančių rezultatų](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) ir daugiau bandymų. Trumpesnio kelio nėra, todėl [kasėjams](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gali prireikti daugybės bandymų.

Kai [kasėjas](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) randa [galiojantį rezultatą](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), jis [išplatina](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) bloką tinkle. [Mazgai](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) gali greitai patikrinti įrodymą, nors jam rasti prireikė daug skaičiavimų ir energijos. Jei į bloką įtrauktas [sandoris](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), tas [sandoris](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) gauna [pirmąjį patvirtinimą](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): jo įrašas įtrauktas į vieną galiojantį bloką. Kiekvienas po jo pridėtas galiojantis blokas suteikia dar vieną [patvirtinimą](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), todėl [sandorio](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) vietą [blokų grandinėje](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) perrašyti tampa brangiau. Šis skirtumas svarbus: atlikti darbą brangu, o jį patikrinti lengva.


<!-- micrographic: proof-of-work-process-01 -->
[Kasėjas vėl ir vėl skaičiuoja siūlomo bloko maišos reikšmę, kol vienas rezultatas tampa mažesnis už tinklo nustatytą tikslinę reikšmę, tada išplatina bloką. Prieš įtraukiant bloką į blokų grandinę, mazgai greitai patikrina įrodymą ir kiekvienos taisyklės laikymąsi: darbui atlikti reikia daug išteklių, o jį patikrinti lengva.](/micrographics/proof-of-work-process-01/lt.md)


[Darbo įrodymas](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) atlieka kelias funkcijas:

* jis suteikia nepriklausomiems [kasėjams](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) galimybę varžytis be centrinio darbų planuotojo
* jis padaro eiliškumo, kuriuo išdėstomi [sandoriai](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), perrašymą brangų
* jis susieja tinklo saugumą su fizine įranga ir energija
* jis užtikrina viešą būdą pasirinkti iš konkuruojančių galiojančių istorijų: pasirenkama grandinė, turinti daugiausia [sukaupto darbo](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Kasimas](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) nėra naudingų lygčių sprendimas siekiant kokio nors išorinio tikslo. Jo paskirtis – užtikrinti tvarką, kuria registruojami „Bitcoin“ [sandoriai](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Tinklas periodiškai koreguoja tikslinę reikšmę: kai blokai sukuriami per greitai, ją sumažina, o kai per lėtai – padidina, kad, kintant skaičiavimo galiai, vidutiniškai kas dešimt minučių būtų sukuriamas maždaug vienas blokas.

[Darbo įrodymas](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) reikalauja realių energijos sąnaudų. Šalininkai teigia, kad būtent šios sąnaudos yra „Bitcoin“ saugumo pagrindas ir gali sukurti lanksčiai tiekiamos ar kitaip nepanaudojamos energijos paklausą. Kritikai kelia klausimus dėl naudojamos energijos kiekio ir šaltinių. Atsakingai vertinant klausiama, kokia energija naudojama, iš kur ji gaunama, kokį saugumą ji užtikrina ir kokios alternatyvos lyginamos.

![Pedagogas, pradedantysis besimokantysis ir techninių žinių turintis besimokantysis aptaria stalinį kasimo įrenginį su ventiliatoriumi ir atskiru maitinimo šaltiniu.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
