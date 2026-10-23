# 8.10 Käyttäjät, solmut, louhijat, kehittäjät ja palvelut

Käyttäkää täsmälleen näitä aloittelijoille tarkoitettuja roolirajauksia:


| Rooli | Keskeinen tehtävä aloittelijan näkökulmasta | Ei tarkoita, että |
| --- | --- | --- |
| Käyttäjä | Päättää vastaanottaa, säilyttää, lähettää, tarkistaa ja hyväksyä bitcoinia suoraan tai palveluiden kautta | Ylläpitää automaattisesti verkon kaikkia osia |
| Solmu | Tarkistaa itsenäisesti siirrot ja lohkot omien sääntöjensä perusteella ja välittää kelvollisia tietoja | Luo uusia lohkoja tai sanelee säännöt kaikille |
| Louhija | Rakentaa lohkoehdokkaita ja tuottaa työtodisteen ehdottaakseen niiden järjestystä | Voi saada sääntöjenvastaisen liikkeeseenlaskun tai siirrot kelpaamaan rehellisille solmuille |
| Kehittäjä | Tarkastaa ja kirjoittaa ohjelmistoja sekä tekee niitä koskevia ehdotuksia | Voi pakottaa osallistujat ottamaan sääntömuutoksen käyttöön |
| Bitcoin-palvelu | Tarjoaa lompakon, vaihtopalvelun, lohkoketjuselaimen, maksukäyttöliittymän tai muun käyttöliittymän | On itse Bitcoin-protokolla |



<!-- micrographic: bitcoin-participant-roles-01 -->


#### Harjoitus: virheellinen lohko

Antakaa yhdelle oppijalle tämän toimiessa [louhijana](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) seuraavanlainen [lohkoehdokas](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) joka luo enemmän lohkotukea kuin [solmun](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) sääntökortti sallii. Oppijat, jotka toimivat [solmuina](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tarkistavat sen ja hylkäävät sen.

Purku:

* Kyseinen [louhija](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) teki todellista työtä mutta ei silti saanut lupaa rikkoa sääntöjä.
* [Solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) soveltavat sääntöjä itsenäisesti, mutta todellinen verkko koostuu ohjelmistoista ja tiedonvälityksestä, ei luokkahuoneessa järjestettävästä äänestyksestä.
* Kehittäjä voi kirjoittaa toisenlaisia sääntöjä, mutta niiden käyttöönotto on vapaaehtoista, ja yhteensopimattomat säännöt voivat synnyttää erillisen verkon.

Kysykää:

> Miksi [solmu](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tarkistaa siirrot? Nimetkää vähintään yksi sääntö, jonka noudattamisen se tarkistaa.
