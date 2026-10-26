# 2.10 Työtodiste

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Työntodiste**
>
> [Työntodiste](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) on prosessi, jota [louhijat](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) käyttävät kilpaillakseen oikeudesta ehdottaa seuraavaa lohkoa.


Eräs [tiivistefunktio](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) muuntaa datan kiinteänpituiseksi tulokseksi. Pieni muutos syötteessä tuottaa uuden, ennalta arvaamattoman tuloksen. [Louhija](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) muuttaa pientä osaa ehdotetun lohkon datasta ja laskee siitä tiivisteen yhä uudelleen. Tulos on kelvollinen vain, kun sen lukuarvo alittaa verkon [tavoitearvon](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) eli sääntöjen asettaman kynnysarvon; matalampi [tavoitearvo](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) tarkoittaa vähemmän [kelvollisia tuloksia](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) ja enemmän yrityksiä. Oikotietä ei ole, joten [louhijat](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) saattavat joutua tekemään monia yrityksiä.

Kun [louhija](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) löytää [kelvollisen tuloksen](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), se [lähettää](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) lohkon verkkoon. [Solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) voivat tarkistaa todisteen nopeasti, vaikka sen löytäminen vaati huomattavasti laskentaa ja energiaa. Jos lohkoon sisältyy [transaktio](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), kyseinen [transaktio](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) saa [ensimmäisen vahvistuksensa](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): sitä koskeva tietue on sisällytetty yhteen kelvolliseen lohkoon. Jokainen sen jälkeen lisätty kelvollinen lohko lisää yhden [vahvistuksen](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), mikä tekee [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) paikan muuttamisesta [lohkoketjussa](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) kalliimpaa. Tämä ero on tärkeä: työn tekeminen on kallista ja sen todentaminen helppoa.


<!-- micrographic: proof-of-work-process-01 -->


[Työntodiste](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) palvelee useita tarkoituksia:

* se antaa riippumattomille [louhijoille](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) tavan kilpailla ilman keskitettyä työnjakoa
* se tekee [transaktioiden](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) järjestyksen muuttamisesta kallista
* se kytkee verkon turvallisuuden fyysisiin laitteisiin ja energiaan
* se tukee julkista menetelmää, jolla valitaan kilpailevien kelvollisten tapahtumahistorioiden välillä: ketju, jolla on eniten [kertynyttä työtä](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Louhinta](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ei ratkaise yhtälöitä, joista olisi hyötyä jossakin ulkopuolisessa käyttötarkoituksessa. Sen tarkoituksena on varmistaa oikea järjestys Bitcoin-verkon [siirroille](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Verkko säätää tavoitearvoa säännöllisesti: kun lohkoja syntyy liian nopeasti, se laskee tavoitearvoa, ja kun niitä syntyy liian hitaasti, se nostaa sitä. Tavoitteena on, että laskentatehon muuttuessakin syntyy keskimäärin noin yksi lohko kymmenessä minuutissa.

[Työtodiste](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) aiheuttaa todellisia energiakustannuksia. Kannattajien mukaan juuri nämä kustannukset muodostavat Bitcoinin turvallisuuden perustan ja voivat luoda kysyntää joustavasti käytettävälle tai muuten käyttämättä jäävälle energialle. Kriitikot kyseenalaistavat käytetyn energian määrän ja alkuperän. Vastuullisessa arvioinnissa kysytään, mitä energiaa käytetään, mistä se tulee, millaista turvallisuutta sillä saadaan aikaan ja mitä vaihtoehtoja vertaillaan.

![Opettaja, aloitteleva oppija ja teknisesti perehtynyt oppija keskustelevat pöydälle sijoitettavasta louhintalaitteesta, jossa on tuuletin ja erillinen virtalähde.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
