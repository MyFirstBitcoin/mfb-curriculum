# 9.20 On-chain- en Lightning-betalingen

Gebruik een vergelijking die de betaalroute scheidt van de [bewaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody).


| Vraag | On-chain | Lightning |
| --- | --- | --- |
| Waar wordt de afwikkeling vastgelegd? | Rechtstreeks in de blockchain van Bitcoin | Betalingsupdates verlopen via een netwerk dat bovenop Bitcoin is gebouwd; kanalen zijn uiteindelijk afhankelijk van Bitcoin |
| Gangbare ontvangstgegevens voor beginners | On-chain adres | Invoice, ondersteund Lightning-adres of een ander goedgekeurd type betaalverzoek |
| Typisch gebruik | Afwikkeling op de basislaag, vaak grotere of minder frequente overboekingen | Vaak kleine of frequente betalingen waar lokale tools en liquiditeit dit ondersteunen |
| Timing | De eerste bevestiging hangt af van opname in een block | Vaak snel, maar betalingen kunnen mislukken |
| Kosten en capaciteit | Hangen af van de transactiegegevens en de vraag naar blockruimte | Hangen af van de Wallet, de route, de liquiditeit, de dienst en de betalingsomstandigheden |
| Bewaring | Kan bij een bewaarder of in eigen beheer zijn | Kan bij een bewaarder of in eigen beheer zijn |
| Belangrijkste controle voor beginners | Juist adres, netwerk, bedrag, kosten en bevestiging | Juiste invoice of bestemming, bedrag, vervaldatum, kosten en betalingsresultaat |


Lightning is geen aparte munt. Een geslaagde Lightning-betaling bewijst niet dat de Wallet veilig is voor een groter saldo. Kanaalbeheer, routeringsinfrastructuur en het beheer van [liquiditeit](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) behoren tot [Advanced Learning](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) buiten het Bitcoin Diploma.


<!-- micrographic: on-chain-and-lightning-01 -->
[On-chain-betalingen worden rechtstreeks vastgelegd in de blockchain van Bitcoin, terwijl Lightning een betaalnetwerk is dat op Bitcoin is gebouwd voor snelle, frequente betalingen die ook kunnen mislukken. Beide routes kunnen custodial (bewaring door een derde partij) of self-custodial (in eigen beheer) zijn.](/micrographics/on-chain-and-lightning-01/nl.md)
