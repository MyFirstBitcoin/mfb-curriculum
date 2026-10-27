# 2.11 Rajallinen tarjonta

Bitcoinin säännöt määrittävät ennustettavan [liikkeeseenlaskuaikataulun](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule) ja [enimmäismäärän](https://curriculum.myfirstbitcoin.org/lexicon/en/#maximum-supply) eli 21 miljoonaa bitcoinia (21 000 000 BTC). Uusia bitcoineja tulee kiertoon [lohkotukena](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy), jota maksetaan [louhijoille](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner), jotka tuottavat kelvollisia lohkoja.


<!-- card: definition -->
> **Definition – Puolittuminen**
>
> Lohkotuki puolittuu 210 000 lohkon välein. Tätä tapahtumaa kutsutaan [puolittumiseksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving). Koska lohkoja tuotetaan keskimäärin noin kymmenen minuutin välein, [puolittuminen](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving) tapahtuu noin neljän vuoden välein. Tarkka kalenteripäivä ei ole ennalta määrätty.



| Puolittumisvuosi | Lohkokorkeus | Lohkotuki puolittumisen jälkeen |
| --- | --- | --- |
| 2012 | 210 000 | 25 BTC |
| 2016 | 420 000 | 12,5 BTC |
| 2020 | 630 000 | 6,25 BTC |
| 2024 | 840 000 | 3,125 BTC |
| Arviolta 2028 | 1 050 000 | 1,5625 BTC |


Lohkotuki oli aluksi 50 BTC lohkoa kohden. Se puolittuu toistuvasti, kunnes se on liian pieni jaettavaksi edelleen. [Louhijat](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) saavat myös [siirtomaksuja](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). Ajan myötä maksujen odotetaan muodostavan yhä merkittävämmän osan [louhijoiden](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) tuloista.


<!-- micrographic: bitcoin-issuance-schedule-01 -->
[Lohkotuki on aluksi 50 bitcoinia ja puolittuu 210 000 lohkon välein, kun taas liikkeeseen laskettujen bitcoinien kokonaismäärä kasvaa kohti 21 miljoonan enimmäismäärää. Siirtomaksut maksetaan tämän lisäksi, eivätkä ne ole uusia bitcoineja; kuvaus ei sisällä hintaennustetta.](/micrographics/bitcoin-issuance-schedule-01/fi.md)


21 miljoonan rajan noudattamista valvovat [solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node). Jos [louhija](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) luo enemmän bitcoineja kuin säännöt sallivat, [validointia tekevät solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) hylkäävät lohkon. Ohjelmistokehittäjä voi kirjoittaa erilaista koodia, mutta ei voi pakottaa muita käyttämään sitä.


<!-- card: dark -->
> **Kiinteä tarjonta on verkon sääntö, ei lupaus hinnasta**
>
> Bitcoinin tarjontaa koskeva sääntö on julkinen ja riippumattomasti todennettavissa, ja yksittäisen osapuolen on vaikea muuttaa sitä, koska [tapahtumia tarkistavat solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) valvovat sen noudattamista. Se ei ole luonnonlaki: se pysyy voimassa niin kauan kuin osallistujat valvovat sen noudattamista. Rajallinen tarjonta ei takaa nousevaa markkinoiden [hintaa](https://curriculum.myfirstbitcoin.org/lexicon/en/#price); [hinta](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) riippuu myös kysynnästä.
>
> Monien [digitaalisten omaisuuserien](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-asset) tarjonnan voidaan väittää olevan rajallinen. Pohtikaa, onko raja uskottava käytännössä, älkää vain sitä, onko se kirjattu asiakirjaan tai esitetty verkkosivustolla.


**Pikakysymys:** Mitä etuja Bitcoinin rajallisesta tarjonnasta on? Miten Bitcoinin tarjonnan lisääminen vaikuttaisi [ostovoimaan](https://curriculum.myfirstbitcoin.org/lexicon/en/#purchasing-power)? Ketkä torjuisivat tarjonnan lisäämisen?


<!-- card: light -->
> Rajallinen tarjonta ei myöskään tarkoita, että jokainen bitcoin olisi myytävänä; joitakin saatetaan pitää hallussa pitkään, ja toisiin voidaan menettää pääsy avainten katoamisen vuoksi.


![](https://cdn.sanity.io/images/vje9ehw2/staging/04f25cd9a85bf20081aaefaf24cb8b6da98f5332-1536x1024.svg)
