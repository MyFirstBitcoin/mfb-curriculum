# 2.1 Miért jött létre a Bitcoin

Digitális fizetések már a Bitcoin előtt is léteztek. Az emberek bankokon, kártyahálózatokon és online fizetési szolgáltatókon keresztül küldhettek pénzt. Ezek a rendszerek megkönnyítették a kereskedelmet, de mindegyik egy megbízható szervezetre támaszkodott a [főkönyv](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) vezetésében, a számlák jóváhagyásában, az átutalások elszámolásában és a viták rendezésében.

Ez a függőség hatalmat és kockázatot teremt. Egy [közvetítő](https://curriculum.myfirstbitcoin.org/lexicon/en/#intermediary) késleltethet egy fizetést, díjat számíthat fel, személyes adatokat gyűjthet és visszaélhet velük, korlátozhat egy számlát, visszafordíthat egy átutalást, vagy működésképtelenné válhat. A [kibocsátó](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer) a [pénznem](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency) kínálatát is megváltoztathatja.

Az informatikusok hosszú éveken át próbáltak olyan digitális pénzt létrehozni, amelyhez nem szükséges központi [kibocsátó](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer) vagy fizetési szolgáltató. Ez nehéz feladat volt. A digitális információ könnyen másolható. Ha egy digitális érme lemásolható és kétszer elkölthető lenne, nem működhetne pénzként. Ha egyetlen vállalat akadályozta meg a másolást, akkor ez a vállalat lett az ellenőrzés központja és a rendszer gyenge pontja.

A Bitcoint azért hozták létre, hogy megoldja ezt a problémát egy [egyenrangú felek közötti hálózattal](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network). Felépítése lehetővé teszi, hogy a résztvevők megállapodjanak egyetlen közös [tranzakciós](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) előzményben egy központi [főkönyv](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) vezetője nélkül. Egyesíti a nyilvános [főkönyvet](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) ([blokkláncot](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain)), [digitális aláírásokat](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature), az [érvényesítő csomópontok hálózatát](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node), [munkabizonyítékot](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), valamint a gazdasági ösztönzőket.


<!-- micrographic: central-ledger-vs-bitcoin-01 -->
[Pénzforgalmi szolgáltató esetén egyetlen szervezet vezeti a főkönyvet és hagy jóvá minden átutalást. A Bitcoin esetében a küldő aláír egy tranzakciót, a független csomópontok ellenőrzik, a bányászok pedig hozzáadják egy közös főkönyvhöz, így a fogadó kevésbé függ egy központi hatóságtól.](/micrographics/central-ledger-vs-bitcoin-01/hu.md)


![](https://cdn.sanity.io/images/vje9ehw2/production/ff5854ad760ecdb1b1cdb024b46098be0212f47e-1536x1024.svg)



A Bitcoin nem szünteti meg a bizalom szükségességét az élet minden területén. Csökkenti annak szükségességét, hogy saját pénzének kibocsátása és elszámolása tekintetében egy központi hatóságban kelljen megbízni.

Ebben a könyvben a **Bitcoin** nagy B-vel írva általában a hálózatot, a protokollt vagy a tágabb rendszert jelenti. A **bitcoin** kis b-vel írva pedig a pénzegységet vagy a [vagyoneszközt](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset). **BTC** a bitcoinban megadott mennyiség szokásos rövidítése, különösen az [árak](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) vagy konkrét mennyiségek leírásakor. Egy tárca vagy tőzsde olyan szolgáltatás, amely kapcsolódhat a Bitcoinhoz; nem maga a [Bitcoin-hálózat](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network).
