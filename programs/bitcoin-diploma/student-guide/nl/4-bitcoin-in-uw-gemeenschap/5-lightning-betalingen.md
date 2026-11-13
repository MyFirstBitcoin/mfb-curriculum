# 4.5 Lightning-betalingen

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[De ontvanger maakt op zijn telefoon een Lightning-betaalverzoek aan met het bedrag, de verzender scant het en betaalt, en de betaling komt een ogenblik later binnen op de telefoon van de ontvanger.](/micrographics/lightning-phone-payment-01/nl.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[Een Lightning-betaling in zes stappen: de ontvanger maakt een verzoek aan, de verzender scant het, controleert ontvanger, bedrag, eenheid, vervaltijd en kosten, en keurt het goed, de betaling wordt gerouteerd en beide Wallets tonen het resultaat. Elke Wallet kan custodial of self-custodial zijn, en een mislukte of verlopen betaling begint opnieuw met een nieuw verzoek.](/micrographics/lightning-payment-sequence-01/nl.md)


Lightning kan snelle, kleine Bitcoin-betalingen praktisch maken. Het kan geschikt zijn voor een winkelbalie, herhaalde lokale betalingen, onlinediensten of overboekingen waarbij een on-chain transactiekosten te hoog zouden zijn in verhouding tot de betaling.

Bij een lokale Lightning-demonstratie moet worden vastgesteld:

* of de wallet door een derde wordt beheerd (custodial) of in eigen beheer is (self-custodial)
* hoe de wallet van saldo wordt voorzien
* of daarvoor een on-chain [transactie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) of een dienst nodig is
* welke back-up of herstelmethode het saldo beschermt
* welk type betaalverzoek wordt gebruikt
* welke kosten of limieten gelden
* wat er gebeurt als een betaling mislukt
* hoe de ontvanger de betaling bevestigt

Een [**Lightning-invoice**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) is een betaalverzoek dat voor een specifieke betaling wordt aangemaakt. Het kan een bedrag, informatie over de bestemming en een vervaltijd bevatten. Lees vóór het betalen het [bevestigingsscherm](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) van de wallet.

Een [**Lightning-adres**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) is een voor mensen leesbare identificatie die door sommige diensten wordt ondersteund. Het kan eruitzien als een e-mailadres, maar het is een hulpmiddel voor het routeren van betalingen, geen e-mailaccount. Het is afhankelijk van de aanbieder of het domein dat het ondersteunt.

Voor een begeleide betaling:

1. De ontvanger maakt het juiste verzoek aan.
1. De verzender scant of kopieert het.
1. De verzender controleert de ontvanger, het bedrag, de eenheid en de kosten.
1. De verzender keurt de betaling pas goed als de gegevens kloppen.
1. Beide partijen bevestigen het resultaat in hun eigen wallet.
1. De groep legt de risico's rond [bewaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) en mislukte betalingen uit.

Ga er niet van uit dat een geslaagde Lightning-betaling bewijst dat de wallet veilig is voor grotere saldi. Betaalgemak en de veiligheid van de [bewaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) zijn twee afzonderlijke vragen.
