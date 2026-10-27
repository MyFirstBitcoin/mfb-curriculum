# 2.5 De blockchain: het openbare grootboek van Bitcoin

<!-- card: definition -->
> **Definition – Blockchain**
>
> De Bitcoin-[blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) is een openbaar [transactie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)register dat wordt gerepliceerd op vele onafhankelijke computers. Een block bundelt een reeks geldige [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tot het volgende voorgestelde deel van dat register. Elk geldig block is gekoppeld aan het vorige, waardoor het netwerk een geordende, gedeelde geschiedenis heeft om te verifiëren.



<!-- card: light -->
> **Hoe nodes consensus bereiken**
>
> [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) controleren onafhankelijk van elkaar dezelfde regels en komen uit bij de geldige geschiedenis met de meeste geaccumuleerde [Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Het wijzigen van een eerder record verandert het bijbehorende block en verbreekt de koppelingen met latere blocks, dus een concurrerende geschiedenis moet dat werk opnieuw verrichten en de achterstand inhalen voordat [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) deze accepteren. Dit kostbare ordeningsproces helpt het netwerk [consensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) te bereiken zonder een centrale registerhouder. Kopieën veranderen niet gelijktijdig; [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ontvangen en valideren gegevens onafhankelijk van elkaar. Bitcoin streeft naar gemiddeld ongeveer één nieuw block per tien minuten. De geschiedenis is moeilijk en kostbaar om te herschrijven, maar niet letterlijk onmogelijk om te veranderen: tijdelijke concurrerende geschiedenissen en reorganisaties kunnen voorkomen.
