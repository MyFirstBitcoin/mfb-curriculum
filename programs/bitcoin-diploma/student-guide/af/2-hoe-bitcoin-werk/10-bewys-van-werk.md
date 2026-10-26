# 2.10 Bewys van werk

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Bewys van werk**
>
> [Bewys van werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) is die proses wat [mynwerkers](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gebruik om mee te ding om die reg om die volgende blok voor te stel.


'n [hash funksie](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) omskep data in 'n resultaat van vaste lengte. 'n Klein verandering aan die invoer lewer 'n onvoorspelbare nuwe resultaat. 'n [mynwerker](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) verander 'n klein stukkie data in 'n voorgestelde blok en hash dit herhaaldelik. 'n Resultaat is slegs geldig wanneer sy getal laer as die netwerk se [teiken](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) is, 'n drempel wat deur die reëls bepaal word; 'n laer [teiken](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) beteken minder [geldige resultate](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) en meer pogings. Daar is geen kortpad nie, dus moet [mynwerkers](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) moontlik baie pogings aanwend.

Wanneer 'n [mynwerker](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) slaag met 'n [geldige resultaat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), [saai dit](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) die blok uit. [Nodusse](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kan die bewys vinnig nagaan, al het die vind daarvan aansienlike berekening en energie geverg. As die blok 'n [transaksie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) insluit, ontvang daardie [transaksie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sy [eerste bevestiging](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): die rekord daarvan is in een geldige blok ingesluit. Elke geldige blok wat daarna bygevoeg word, voeg nog 'n [bevestiging](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) by, wat dit duurder maak om die [transaksie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) se plek in die [blokketting](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) te herskryf. Hierdie verskil is belangrik: werk is duur om te verrig en maklik om te verifieer.


<!-- micrographic: proof-of-work-process-01 -->


[Bewys van werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) dien verskeie doeleindes:

* dit gee onafhanklike [mynwerkers](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) 'n manier om sonder 'n sentrale skeduleerder mee te ding
* dit maak dit duur om die volgorde van [transaksies](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) te herskryf
* dit koppel netwerksekuriteit aan toerusting en energie in die werklike wêreld
* dit ondersteun 'n openbare metode om tussen mededingende geldige geskiedenisse te kies: die ketting met die meeste [opgehoopte werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Mynbou](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) los nie nuttige vergelykings vir ’n eksterne doel op nie. Die doel daarvan is om die volgorde van Bitcoin se [transaksies](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Die Netwerk pas die teiken periodiek aan: wanneer blokke te vinnig aankom, verlaag dit die teiken, en wanneer hulle te stadig aankom, verhoog dit die teiken, met die doel om gemiddeld ongeveer een blok elke tien minute te lewer namate rekenaarkrag verander.

[Bewys van werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) behels ’n werklike energiekoste. Voorstanders voer aan dat hierdie koste die grondslag van Bitcoin se sekuriteit vorm en ’n vraag kan skep na energie wat buigsaam aangewend kan word of andersins ongebruik sou bly. Kritici bevraagteken die hoeveelheid en bron van die energie wat gebruik word. ’n Verantwoordelike evaluering vra watter energie gebruik word, waar dit vandaan kom, watter sekuriteit dit bied en watter alternatiewe vergelyk word.

![Die opvoeder, beginnerleerder en tegniese leerder bespreek ’n tafelmodel-mynbou-eenheid met ’n waaier en ’n afsonderlike kragtoevoer.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
