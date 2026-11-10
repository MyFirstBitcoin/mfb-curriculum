# 10.9 Checklist voor de Lightning-module

Controleer en leg vóór een Lightning-workshop het volgende uit:

* of de wallet custodial of self-custodial is
* hoe er saldo op wordt gezet
* of storten of opnemen via een on-chaintransactie of een dienst verloopt
* herstel en continuïteit als de aanbieder of het apparaat uitvalt
* of het verzoek een invoice, een ondersteund [Lightning-adres](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) of een ander type is
* bedrag, eenheid, ontvanger, vervaltijd, kosten, limieten en [liquiditeit](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) als aandachtspunten
* hoe een geslaagde, lopende, verlopen of mislukte betaling eruitziet
* hoe beide partijen het resultaat onafhankelijk van elkaar bevestigen; en
* de offlinesimulatie.


<!-- card: dark -->
> **Eén geslaagde Lightning-betaling bewijst alleen dat deze route één keer heeft gewerkt**
>
> Het bewijst niet dat de wallet veilig is voor grotere saldi of dat hetzelfde pad overal zal werken.



<!-- micrographic: lightning-payment-sequence-01 -->
[Een Lightning-betaling in zes stappen: de ontvanger maakt een verzoek aan, de verzender scant het, controleert ontvanger, bedrag, eenheid, vervaltijd en kosten, en keurt het goed, de betaling wordt gerouteerd en beide Wallets tonen het resultaat. Elke Wallet kan custodial of self-custodial zijn, en een mislukte of verlopen betaling begint opnieuw met een nieuw verzoek.](/micrographics/lightning-payment-sequence-01/nl.md)
