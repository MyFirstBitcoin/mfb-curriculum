# 2.3 Vroege pogingen tot digitaal geld en het probleem van dubbele uitgaven

Bitcoin was niet de eerste poging tot digitaal geld. Het bouwde voort op vier decennia aan experimenten en putte uit ideeën van vele eerdere projecten die hebben bijgedragen aan het succesvolle ontwerp.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) gebruikte [cryptografie](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) om private digitale betalingen mogelijk te maken. Het was afhankelijk van een centraal bedrijf en van bankrelaties. Toen het bedrijf failliet ging, kon het systeem niet voortbestaan als onafhankelijk geldnetwerk.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) gebruikte [Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) om ongewenste e-mail kostbaar te maken. De computer van een afzender moest werk verrichten voordat een bericht kon worden verzonden. Het idee liet zien hoe rekenkosten misbruik konden ontmoedigen.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) beschreef een voorgesteld systeem waarin rekenwerk schaarse digitale registraties kon creëren. Het werd niet gelanceerd als een volledig gedecentraliseerd geldsysteem, maar het ontwikkelde belangrijke ideeën over digitale [schaarsheid](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) en bewijs.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) en [**herbruikbare Proof-of-Work (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) verkenden manieren waarop deelnemers schaarse digitale [waarde](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) konden creëren of overdragen zonder uitsluitend op één centrale database te vertrouwen. Ze waren onvolledig, maar ze hielpen verduidelijken wat een werkend systeem nodig zou hebben.
* Hoewel [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) geen geld was, liet het zien dat een [Peer-to-Peer-netwerk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) veel onafhankelijke computers informatie kon laten delen zonder dat één centrale server het hele systeem beheerde.

Samen lieten deze experimenten nuttige stukjes van de puzzel zien. Ze maakten ook duidelijk welk probleem nog overbleef.


<!-- card: definition -->
> **Definition – Dubbel uitgeven**
>
> [Dubbel uitgeven](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) is een poging om dezelfde digitale eenheid naar twee ontvangers te sturen. Digitale gegevens kunnen perfect worden gekopieerd, dus een digitaal geldsysteem heeft een manier nodig om vast te stellen welke [transactie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) geldig is.


[Gecentraliseerde systemen](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) voorkomen dit door één vertrouwde database te laten beslissen welke betaling als eerste kwam. Op 31 oktober 2008 beschreef de whitepaper van [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto), [_Bitcoin: A Peer-to-Peer Electronic Cash System_](https://bitcoin.org/bitcoin.pdf), een andere aanpak: een openbaar systeem dat een gedeelde betalingsgeschiedenis kon vastleggen zonder bank, bedrijf of andere centrale autoriteit.

De whitepaper bracht de kenmerken samen die voor die aanpak nodig waren:

1. **Een [Peer-to-Peer-netwerk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) worden rechtstreeks aangekondigd aan een netwerk van deelnemers.
1. **[Digitale handtekeningen](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** een [privé sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) is geheime informatie die een handtekening aanmaakt om een uitgave te autoriseren; alleen de houder ervan kan dit doen.
1. **Blocks en [Mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) verzamelen [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) in blocks en gebruiken [Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) om met elkaar te concurreren om het volgende block toe te voegen.
1. **Onafhankelijke [verificatie](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) controleren [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) en blocks aan de hand van de regels van Bitcoin.
1. **Een gedeelde geschiedenis met geaccumuleerde [Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** deelnemers erkennen de [geldige keten](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) van [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) met het meeste [geaccumuleerde werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) als het gedeelde register.


<!-- micrographic: five-part-response-01 -->
[Vijf onderdelen vormen samen het antwoord op het double-spendprobleem: een peer-to-peernetwerk, digitale handtekeningen, blokken en Mining, onafhankelijke verificatie en een gedeelde geschiedenis met de meeste geaccumuleerde proof of work. Samen stellen ze het netwerk in staat een tweede uitgave te weigeren zonder centrale autoriteit.](/micrographics/five-part-response-01/nl.md)


Deze module legt deze concepten uitgebreider uit. Samen boden ze een praktisch antwoord op het [Double Spend-probleem](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): het netwerk kan een tweede poging om dezelfde bitcoin uit te geven afwijzen zonder afhankelijk te zijn van een centrale autoriteit. Bitcoin bood de ontbrekende combinatie waarnaar decennia aan experimenten met digitaal geld op zoek waren geweest.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
