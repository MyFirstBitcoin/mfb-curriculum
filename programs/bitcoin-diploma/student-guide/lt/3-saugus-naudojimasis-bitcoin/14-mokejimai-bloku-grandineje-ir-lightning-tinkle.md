# 3.14 Mokėjimai blokų grandinėje ir „Lightning“ tinkle

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Mokėjimai blokų grandinėje ir „Lightning“ tinkle**
>
> [Mokėjimai blokų grandinėje](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) įrašomi į „Bitcoin“ [blokų grandinę](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) ir gauna [patvirtinimus](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). „Lightning“ yra „Bitcoin“ pagrindu sukurtas mokėjimų tinklas, leidžiantis atlikti greitus ir dažnus mokėjimus. „Lightning“ mokėjimas gali būti greitai įvykdytas arba nepavykti, o šio tinklo piniginė gali būti tiek paslaugų teikėjo valdoma, tiek savarankiškai valdoma.



> **Dark – Mokėjimo būdas nenulemia, kas valdo lėšas**
>
> Mokėjimai blokų grandinėje ir „Lightning“ tinkle reiškia skirtingus [kompromisus](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). „Lightning“ piniginė gali būti paslaugų teikėjo valdoma arba savarankiškai valdoma, o greitas ir sėkmingas mokėjimas neįrodo, kad paslauga tinka didesnėms lėšų sumoms laikyti ar kiekvienai situacijai.



<!-- micrographic: onchain-lightning-table-01 -->


Kokio mokėjimo būdo tikisi gavėjas? Prieš mokėdami patikrinkite, ar jis pateikė adresą blokų grandinėje, ar [„Lightning“ mokėjimo sąskaitą](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) arba užklausą. Naudojant blokų grandinės piniginę negalima tiesiogiai apmokėti kiekvienos [„Lightning“ mokėjimo sąskaitos](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), o „Lightning“ piniginė gali palaikyti ne visus veiksmus blokų grandinėje. Kai kurios programėlės palaiko abu mokėjimo būdus, tačiau gali taikyti papildomus mokesčius arba sukurti priklausomybę nuo paslaugų. Išsamus „Lightning“ konfigūravimas, kanalai, mokėjimų maršrutizavimas ir [likvidumas](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) priskiriami [išplėstiniam mokymuisi](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); praktiniai užsiėmimai gyvai vietoje numatyti **4 modulyje**, kai tai saugu ir tinkama.

Įsivaizduokite, kad parengtame scenarijuje siūlomi abu mokėjimo būdai. Kurią užklausą galima apmokėti numatyta pinigine ir ką patikrintumėte prieš patvirtindami mokėjimą? Atsakymas priklauso nuo gavėjo pateiktos mokėjimo užklausos, piniginės ir situacijos, o ne nuo universalaus „geriausio“ būdo.

![Dėstytojas lentoje rodo du skirtingus geometrinius mokėjimo kelius, o pradedantieji ir techninių žinių turintys besimokantieji juos nagrinėja.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
