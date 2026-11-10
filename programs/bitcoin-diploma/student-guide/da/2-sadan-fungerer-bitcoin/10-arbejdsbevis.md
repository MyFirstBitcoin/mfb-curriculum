# 2.10 Arbejdsbevis

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Arbejdsbevis**
>
> [Arbejdsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) er den proces, [minere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bruger til at konkurrere om retten til at foreslå den næste blok.


En [hashfunktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) omdanner data til et resultat med en fast længde. En lille ændring i inputtet giver et nyt, uforudsigeligt resultat. En [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ændrer en lille del af dataene i en foreslået blok og hasher den gentagne gange. Et resultat er kun gyldigt, når dets talværdi er under netværkets [målværdi](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), en tærskel fastsat af reglerne; en lavere [målværdi](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) betyder færre [gyldige resultater](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) og flere forsøg. Der er ingen genvej, så [minere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan være nødt til at gøre mange forsøg.

Når en [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) finder et [gyldigt resultat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), [udsender](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) den blokken. [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kan hurtigt kontrollere beviset, selv om det krævede betydelig beregningskraft og energi at finde det. Hvis blokken indeholder en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), får denne [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sin [første bekræftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): registreringen af den er blevet inkluderet i én gyldig blok. Hver gyldig blok, der tilføjes efter den, giver endnu en [bekræftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), hvilket gør [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)ens plads i [blockchainen](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) dyrere at omskrive. Denne forskel er vigtig: Arbejdet er dyrt at udføre og let at verificere.


<!-- micrographic: proof-of-work-process-01 -->
[En miner beregner hashes af en foreslået blok igen og igen, indtil et resultat er under netværkets mål, og udsender derefter blokken. Noder kontrollerer hurtigt beviset og alle regler, før blokken føjes til blockchainen: Arbejdet er dyrt at udføre og let at verificere.](/micrographics/proof-of-work-process-01/da.md)


[Arbejdsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) tjener flere formål:

* det giver uafhængige [minere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) en måde at konkurrere på uden en central instans, der fordeler arbejdet
* det gør rækkefølgen af [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dyr at omskrive
* det knytter netværkets sikkerhed til fysisk udstyr og energi
* det understøtter en offentlig metode til at vælge mellem konkurrerende gyldige historikker: kæden med mest [akkumuleret arbejde](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) løser ikke nyttige ligninger til et eksternt formål. Formålet er at sikre rækkefølgen af Bitcoin-netværkets [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Netværket justerer regelmæssigt målværdien: Når blokke kommer for hurtigt, sænker det målværdien, og når de kommer for langsomt, hæver det den. Målet er i gennemsnit cirka én blok hvert tiende minut, efterhånden som beregningskraften ændrer sig.

[Arbejdsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) indebærer et reelt energiforbrug. Tilhængere hævder, at dette forbrug er grundlaget for Bitcoins sikkerhed og kan skabe efterspørgsel efter fleksibel eller ellers uudnyttet energi. Kritikere sætter spørgsmålstegn ved mængden af energi, der bruges, og hvor den kommer fra. En ansvarlig vurdering undersøger, hvilken energi der bruges, hvor den kommer fra, hvilken sikkerhed den giver, og hvilke alternativer der sammenlignes med.

![Underviseren, begynderen og den teknisk kyndige kursist diskuterer en mining-enhed til bordbrug med en blæser og en separat strømforsyning.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
