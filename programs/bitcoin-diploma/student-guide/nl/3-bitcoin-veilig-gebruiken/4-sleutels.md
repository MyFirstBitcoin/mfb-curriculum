# 3.4 Sleutels

Eigendom van bitcoin wordt afgedwongen via cryptografische sleutels.


<!-- card: definition -->
> **Definition – Privé sleutel**
>
> Een [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) is geheime informatie waarmee een wallet geldige [digitale handtekeningen](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) kan aanmaken. Een handtekening autoriseert het uitgeven van bitcoin die door de bijbehorende sleutel wordt beheerd. Iedereen die de [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) in handen krijgt, kan die tegoeden doorgaans uitgeven.


Een [**publieke sleutel**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) wordt wiskundig afgeleid van de [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Hiermee kan een handtekening worden geverifieerd zonder de [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) prijs te geven. Adressen worden gemaakt op basis van [publieke sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key)-informatie.

De essentiële regel is eenvoudig:

**Openbare ontvangstinformatie mag worden gedeeld. Privé-informatie om uit te geven moet geheim blijven.**

Een [digitale handtekening](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) bewijst dat de vereiste [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) een [transactie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) heeft geautoriseerd. De [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) wordt daarbij niet in de [transactie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) geplaatst. [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifiëren de handtekening voordat zij de uitgave accepteren.

De meeste wallets voor beginners gebruiken [single-signature](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): één privé sleutel autoriseert een transactie. Moderne wallets beheren automatisch veel sleutels. Beginners mogen geen afzonderlijke [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key)-reeksen kopiëren of hanteren. Bescherm de goedgekeurde back-up van de wallet en volg de bijbehorende herstelprocedure.

Geen enkele bonafide docent, wallet-aanbieder, medewerker van een exchange, technische ondersteuner of Bitcoin-ontwikkelaar heeft uw [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) of [seed phrase](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase) nodig. Iedereen die erom vraagt, moet als een bedreiging worden beschouwd.


<!-- card: light -->
> **Probeer het zelf:** Sorteer de voorbereide voorbeelden in drie groepen: veilig om te delen voor ontvangst, geheime informatie om uit te geven, en informatie die openbaar mag zijn maar toch privé moet blijven wanneer deze aan een persoon is gekoppeld.



<!-- micrographic: private-key-public-info-01 -->
[Een geheime privésleutel, die nooit gedeeld mag worden, leidt tot publieke informatie die wel gedeeld kan worden: een publieke sleutel die ervan is afgeleid en een ontvangstadres dat daarop is gebaseerd. Dezelfde privésleutel maakt handtekeningen aan die Nodes verifiëren zonder de privésleutel ooit te leren kennen.](/micrographics/private-key-public-info-01/nl.md)
