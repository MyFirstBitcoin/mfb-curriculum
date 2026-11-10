# 3.11 Tikrinimas, blokų naršyklės ir neatšaukiamos operacijos

<!-- card: definition -->
> **Definition – Sandorio identifikatorius ir blokų naršyklė**
>
> Šis [sandorio identifikatorius](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identifikuoja blokų grandinėje registruotą [sandorį](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Blokų naršyklė](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) rodo viešus „Bitcoin“ duomenis, pavyzdžiui, [sandorio](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) būseną ir [patvirtinimų](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) skaičių. Tai naudinga duomenų peržiūros priemonė, o ne „Bitcoin“ valdanti institucija ir ne gavėjo tapatybės ar sąžiningumo įrodymas.


Ką ši vieša informacija gali parodyti, o ko negali? Ji gali parodyti [sandorio](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) būseną, paskirties adresą, sumą, mokestį ir [patvirtinimų](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) skaičių; ji negali įrodyti, kodėl buvo atliktas mokėjimas ir ar asmuo yra patikimas. Blokų grandinėje registruojamas [sandoris](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) lieka nepatvirtintas po jo [paskelbimo tinkle](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) ir gauna [pirmąjį patvirtinimą](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) tada, kai įtraukiamas į galiojantį bloką. Vėlesni blokai sustiprina pasitikėjimą jo vieta įrašų sekoje, tačiau neištaiso klaidingo paskirties adreso ar sukčiavimo pasekmių. Nėra universalaus [patvirtinimų](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) skaičiaus, tinkamo kiekvienam mokėjimui; tinkama patikra priklauso nuo sumos ir rizikos.

Norėdami patikrinti paruoštą [sandorį](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), gaukite jo [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), atverkite patikimą naršyklę, skirtą numatytam [„Bitcoin“ tinklui](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network), ir patikrinkite būseną, paskirties adresą, sumą, mokestį ir [patvirtinimus](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Naršyklė tėra sąsaja. Adreso ar [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) paieška gali atskleisti jos operatoriui, kad jūsų įrenginys domisi ta informacija. Praktikai naudokite mokytojo paruoštą [sandorį](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) arba atspausdintą ekrano kopiją. Neieškokite mokinio asmeninio adreso ar [sandorio](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) naudodamiesi viešąja paslauga. Jei vėliau nagrinėsite asmeninį mokėjimą, išsiaiškinkite [privatumo](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) ir saugumo [kompromisus](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off), susijusius su jūsų ryšiu, prieš naudodamiesi viešąja paslauga.


<!-- card: callout -->
> **Vieši duomenys nėra tapatybės ar sąžiningumo įrodymas**
>
> Tokia [blokų naršyklė](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) gali rodyti viešus [sandorių](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) duomenis, tačiau negali įrodyti, kas valdo adresą, kodėl buvo atliktas mokėjimas ir ar gavėjas yra patikimas. Praktikuokitės naudodami parengtus pavyzdžius ir saugokite [privatumą](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) atlikdami paiešką viešose paslaugose.



<!-- micrographic: confirmation-timeline-01 -->
[Nepatvirtinta operacija laukia laukiančių operacijų telkinyje, tada įtraukiama į bloką N ir taip gauna pirmąjį patvirtinimą, o kiekvienas vėlesnis blokas prideda dar vieną.](/micrographics/confirmation-timeline-01/lt.md)


![Dėstytojas ir vyresnio amžiaus besimokantysis aptaria parengtą pavyzdį į grupę atsuktame monitoriuje, o techninių žinių turintis besimokantysis valdo pelę; žiūrovas mato monitoriaus korpuso galinę dalį.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
