# 2.10 Proof of work

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Proof-of-Work**
>
> [Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) is het proces dat [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gebruiken om te concurreren om het recht het volgende block voor te stellen.


Een [Hash-functie](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) zet gegevens om in een resultaat met een vaste lengte. Een kleine wijziging in de invoer levert een onvoorspelbaar nieuw resultaat op. Een [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) wijzigt een klein stukje gegevens in een voorgesteld block en hasht dit herhaaldelijk. Een resultaat is alleen geldig wanneer het getal ervan onder de door het netwerk gehanteerde [doelwaarde](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) ligt, een drempel die door de regels is vastgesteld; een lagere [doelwaarde](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) betekent minder [geldige resultaten](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) en meer pogingen. Er is geen kortere weg, dus [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) moeten mogelijk veel pogingen doen.

Wanneer een [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) een [geldig resultaat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) vindt, [verspreidt](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) hij het block. [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kunnen het bewijs snel controleren, ook al vergde het vinden ervan aanzienlijke rekenkracht en energie. Als het block een [transactie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) bevat, krijgt die [transactie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) haar [eerste bevestiging](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): de registratie ervan is opgenomen in één geldig block. Elk geldig block dat daarna wordt toegevoegd, voegt nog een [bevestiging](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) toe, waardoor de plaats van de [transactie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) in de [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) kostbaarder wordt om te herschrijven. Dit verschil is belangrijk: werk is kostbaar om te produceren en eenvoudig te verifiëren.


<!-- micrographic: proof-of-work-process-01 -->
[Een miner hasht een voorgesteld blok keer op keer totdat één resultaat onder de doelwaarde van het netwerk ligt, en verspreidt het blok vervolgens. Nodes controleren snel het bewijs en elke regel voordat het blok aan de blockchain wordt toegevoegd: werk is kostbaar om te produceren en eenvoudig te verifiëren.](/micrographics/proof-of-work-process-01/nl.md)


[Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) dient meerdere doelen:

* het geeft onafhankelijke [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) een manier om te concurreren zonder centrale planner
* het maakt de volgorde van [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) kostbaar om te herschrijven
* het koppelt de netwerkbeveiliging aan apparatuur en energie in de echte wereld
* het ondersteunt een openbare methode om te kiezen tussen concurrerende geldige geschiedenissen: de keten met het meeste [geaccumuleerde werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) lost geen nuttige vergelijkingen op voor een extern doel. Het doel ervan is de volgorde van Bitcoin-[transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) te beveiligen. Het netwerk past het doel periodiek aan: wanneer blocks te snel binnenkomen, verlaagt het het doel, en wanneer ze te langzaam binnenkomen, verhoogt het het, met als streven gemiddeld ongeveer één block per tien minuten terwijl de rekenkracht verandert.

[Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) brengt echte energiekosten met zich mee. Voorstanders stellen dat deze kosten de veiligheid van Bitcoin verankeren en vraag kunnen creëren naar flexibele of anderszins onbenutte energie. Critici plaatsen vraagtekens bij de hoeveelheid en de herkomst van de gebruikte energie. Een verantwoorde beoordeling vraagt welke energie wordt gebruikt, waar die vandaan komt, welke veiligheid die biedt en met welke alternatieven wordt vergeleken.

![De docent, de beginnende leerling en de technische leerling bespreken een Mining-apparaat op tafelformaat met een ventilator en een aparte voeding.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
