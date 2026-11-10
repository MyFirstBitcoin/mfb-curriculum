# 2.3 Vroeë pogings met digitale geld en die dubbelbestedingsprobleem

Bitcoin was nie die eerste poging tot digitale geld nie. Dit het voortgebou op vier dekades van eksperimentering en het geput uit idees van talle vroeëre projekte wat gehelp het om die suksesvolle ontwerp daarvan te vorm.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) het [Kriptografie](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) gebruik om private digitale betalings te ondersteun. Dit was van ’n sentrale maatskappy en bankverhoudings afhanklik. Toe die maatskappy misluk het, kon die stelsel nie as ’n onafhanklike geldnetwerk voortbestaan nie.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) het [Bewys van werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) gebruik om ongewenste e-pos duur te maak. ’n Afsender se rekenaar moes werk verrig voordat dit ’n boodskap kon stuur. Die idee het getoon hoe berekeningskoste misbruik kon ontmoedig.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) het ’n voorgestelde stelsel beskryf waarin berekeningswerk skaars digitale rekords kon skep. Dit is nie as ’n volledige gedesentraliseerde geldstelsel bekendgestel nie, maar dit het belangrike idees oor digitale [skaarsheid](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) en bewys ontwikkel.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) en [**herbruikbare Bewys van werk (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) het maniere ondersoek waarop deelnemers skaars digitale [waarde](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) kon skep of oordra sonder om slegs op een sentrale databasis staat te maak. Hulle was onvolledig, maar het help verduidelik wat ’n werkende stelsel sou benodig.
* Hoewel [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) nie geld was nie, het dit getoon dat ’n [Eweknie (P2P)-netwerk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) talle onafhanklike rekenaars kon toelaat om inligting te deel sonder dat een sentrale bediener die hele stelsel beheer.

Saam het hierdie eksperimente nuttige stukkies van die legkaart getoon. Hulle het ook die oorblywende probleem duideliker gemaak.


<!-- card: definition -->
> **Definition – Dubbelbesteding**
>
> [Dubbelbesteding](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) is ’n poging om dieselfde digitale eenheid aan twee ontvangers te stuur. Digitale data kan presies gekopieer word, dus het ’n digitale geldstelsel ’n manier nodig om vas te stel watter [Transaksie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) geldig is.


[Gesentraliseerde stelsels](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) voorkom dit deur een vertroude databasis te laat besluit watter betaling eerste gekom het. Op 31 Oktober 2008 het [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) se Witskrif, [_Bitcoin: ’n Elektroniese kontantstelsel vir Eweknie (P2P)_](https://bitcoin.org/bitcoin.pdf), ’n ander benadering verduidelik: ’n openbare stelsel wat ’n gedeelde betalingsgeskiedenis kon vasstel sonder ’n bank, maatskappy of ander sentrale gesag.

Die Witskrif het die kenmerke saamgebring wat vir daardie benadering nodig was:

1. **’n [Eweknie (P2P)-netwerk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transaksies](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) word direk aan ’n netwerk van deelnemers aangekondig.
1. **[Digitale handtekeninge](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** ’n [Privaat sleutel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) is geheime inligting wat ’n handtekening skep om ’n besteding te magtig; slegs die houer daarvan kan dit doen.
1. **Blokke en [Mynbou](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [myners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) versamel [transaksies](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) in blokke en gebruik [Bewys van werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) om mee te ding om die volgende blok by te voeg.
1. **Onafhanklike [verifiëring](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [nodusse](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) toets [transaksies](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) en blokke aan Bitcoin se reëls.
1. **’n Gedeelde geskiedenis met opgehoopte [Bewys van werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** deelnemers erken die [geldige ketting](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) van [transaksies](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) met die meeste [opgehoopte werk](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) as die gedeelde rekord.


<!-- micrographic: five-part-response-01 -->
[Vyf dele vorm saam die oplossing vir die dubbelbestedingsprobleem: 'n eweknienetwerk, digitale handtekeninge, blokke en mynbou, onafhanklike verifikasie, en 'n gedeelde geskiedenis met die meeste opgehoopte bewys van werk. Saam stel hulle die netwerk in staat om 'n tweede besteding sonder 'n sentrale gesag te verwerp.](/micrographics/five-part-response-01/af.md)


Hierdie module verduidelik hierdie begrippe in meer besonderhede. Saam het hulle ’n praktiese antwoord gebied op die [probleem van Dubbele besteding](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): die Netwerk kan ’n tweede poging om dieselfde bitcoin te bestee, verwerp sonder om op ’n sentrale gesag staat te maak. Bitcoin het die ontbrekende kombinasie gebied waarna dekades se eksperimente met digitale geld gesoek het.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
