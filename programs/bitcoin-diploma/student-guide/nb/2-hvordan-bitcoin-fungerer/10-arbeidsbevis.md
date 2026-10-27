# 2.10 Arbeidsbevis

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Arbeidsbevis**
>
> [Arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) er prosessen [utvinnere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bruker for å konkurrere om retten til å foreslå neste blokk.


En [hashfunksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) omdanner data til et resultat med fast lengde. En liten endring i inndataene gir et uforutsigbart nytt resultat. En [utvinner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) endrer en liten del av dataene i en foreslått blokk og hasher den gjentatte ganger. Et resultat er bare gyldig når tallverdien er lavere enn nettverkets [måltall](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), en terskel fastsatt av reglene; et lavere [måltall](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) betyr færre [gyldige resultater](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) og flere forsøk. Det finnes ingen snarvei, så [utvinnere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan måtte gjøre mange forsøk.

Når en [utvinner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) finner et [gyldig resultat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), vil den [kringkaste](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blokken. [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kan kontrollere beviset raskt, selv om det krevde betydelig beregningsarbeid og energi å finne det. Hvis blokken inneholder en [transaksjon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), får denne [transaksjonen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sin [første bekreftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): den er registrert i én gyldig blokk. Hver gyldige blokk som legges til etter denne, gir enda en [bekreftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), noe som gjør [transaksjonen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)s plass i [blokkjeden](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) mer kostbar å endre. Denne forskjellen er viktig: arbeid er kostbart å utføre og lett å verifisere.


<!-- micrographic: proof-of-work-process-01 -->
[En miner beregner hasher av en foreslått blokk om og om igjen til ett resultat er under nettverkets målverdi, og kringkaster deretter blokken. Nodene kontrollerer raskt beviset og at alle reglene er fulgt før blokken blir del av blokkjeden: arbeidet er kostbart å utføre og enkelt å verifisere.](/micrographics/proof-of-work-process-01/nb.md)


[Arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) har flere formål:

* det gir uavhengige [utvinnere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) en måte å konkurrere på uten en sentral instans som fordeler arbeidet
* det gjør rekkefølgen på [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) kostbar å endre
* det knytter nettverkssikkerheten til fysisk utstyr og energi
* det støtter en offentlig metode for å velge mellom konkurrerende gyldige historikker: kjeden med mest [akkumulert arbeid](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Utvinning](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) løser ikke nyttige ligninger for et eksternt formål. Formålet er å sikre rekkefølgen på Bitcoins [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Nettverket justerer målverdien med jevne mellomrom: Når blokkene kommer for raskt, senkes målverdien, og når de kommer for sakte, heves den. Målet er i gjennomsnitt omtrent én blokk hvert tiende minutt, selv når datakraften endrer seg.

[Arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) innebærer en reell energikostnad. Tilhengere hevder at denne kostnaden er grunnlaget for Bitcoins sikkerhet og kan skape etterspørsel etter fleksibel energi eller energi som ellers ikke ville blitt brukt. Kritikere stiller spørsmål ved hvor mye energi som brukes, og hvor den kommer fra. En ansvarlig vurdering undersøker hvilken energi som brukes, hvor den kommer fra, hvilken sikkerhet den gir, og hvilke alternativer som sammenlignes.

![Underviseren, nybegynneren og den teknisk interesserte kursdeltakeren diskuterer en bordplassert utvinningsenhet med vifte og separat strømforsyning.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
