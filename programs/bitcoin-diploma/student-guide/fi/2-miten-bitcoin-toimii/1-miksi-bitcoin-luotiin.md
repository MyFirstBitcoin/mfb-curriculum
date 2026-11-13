# 2.1 Miksi Bitcoin luotiin

Digitaalisia maksuja oli olemassa jo ennen Bitcoinia. Ihmiset pystyivät lähettämään rahaa pankkien, korttiverkostojen ja verkkomaksuyritysten kautta. Nämä järjestelmät helpottivat kaupankäyntiä, mutta jokainen niistä oli riippuvainen luotetusta organisaatiosta, jonka tehtävänä oli pitää [tilikirjaa](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger), hyväksyä tilejä, selvittää siirtoja ja ratkaista riitoja.

Tämä riippuvuus luo valtaa ja riskejä. [Välikäsi](https://curriculum.myfirstbitcoin.org/lexicon/en/#intermediary) voi viivästyttää maksua, periä maksun, kerätä ja väärinkäyttää henkilötietoja, rajoittaa tilin käyttöä, perua siirron tai lakata toimimasta. [Liikkeeseenlaskija](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer) kyseisen [valuutan](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency) osalta voi myös muuttaa sen tarjontaa.

Tietojenkäsittelytieteilijät yrittivät vuosien ajan luoda digitaalista rahaa, joka ei tarvitsisi keskitettyä [liikkeeseenlaskijaa](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer) tai maksuyritystä. Haaste oli vaikea. Digitaalista tietoa on helppo kopioida. Jos digitaalisen kolikon voisi kopioida ja käyttää kahdesti, se ei voisi toimia rahana. Jos yksi yritys esti kopioinnin, siitä tuli sekä vallankäytön keskus että järjestelmän heikko kohta.

Bitcoin luotiin ratkaisemaan tämä ongelma [vertaisverkon avulla](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network). Sen rakenne mahdollistaa sen, että osallistujat voivat päästä yhteisymmärrykseen yhdestä [tapahtumien](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) historiasta ilman keskitettyä [tilikirjan](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) ylläpitäjää. Se yhdistää julkisen [tilikirjan](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) ([lohkoketjun](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain)), [digitaaliset allekirjoitukset](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature), [tietoja tarkistavien solmujen](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) verkoston, [työtodisteen](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ja taloudelliset kannustimet.


<!-- micrographic: central-ledger-vs-bitcoin-01 -->
[Maksuyhtiötä käytettäessä yksi organisaatio ylläpitää tilikirjaa ja hyväksyy jokaisen siirron. Bitcoinia käytettäessä lähettäjä allekirjoittaa tapahtuman, riippumattomat solmut tarkistavat sen ja louhijat lisäävät sen yhteen yhteiseen tilikirjaan, joten vastaanottaja on vähemmän riippuvainen keskitetystä tahosta.](/micrographics/central-ledger-vs-bitcoin-01/fi.md)


![](https://cdn.sanity.io/images/vje9ehw2/staging/ff5854ad760ecdb1b1cdb024b46098be0212f47e-1536x1024.svg)



Bitcoin ei poista luottamuksen tarvetta kaikilta elämän osa-alueilta. Se vähentää tarvetta luottaa keskitettyyn tahoon sen oman rahan liikkeeseenlaskussa ja siirtojen selvityksessä.

Tässä kirjassa **Bitcoin** isolla B-kirjaimella tarkoittaa yleensä verkkoa, protokollaa tai laajempaa järjestelmää. Vastaavasti **bitcoin** pienellä b-kirjaimella tarkoittaa rahayksikköä tai [omaisuuserää](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset). **BTC** on yleinen lyhenne bitcoinmäärälle, erityisesti kirjoitettaessa [hintoja](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) tai tarkkoja määriä. Lompakko tai pörssi on palvelu, joka voi olla yhteydessä Bitcoiniin; se ei ole [Bitcoin-verkko](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) itsessään.
