# 2.9 Käyttäjät, solmut ja louhijat

Bitcoin toimii, koska eri osallistujat hoitavat eri tehtäviä.

* **Käyttäjät** vastaanottavat, säilyttävät ja lähettävät bitcoineja. Käyttäjä voi hallita itse lompakossa olevia avaimiaan tai käyttää [säilytyspalvelua](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Käyttäjät antavat verkolle taloudellisen merkityksen valitsemalla, hyväksyvätkö he bitcoineja ja mihin sääntöihin tai palveluihin he luottavat.
* [**Solmut**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ajavat Bitcoin-ohjelmistoa ja tarkistavat itsenäisesti sääntöjen noudattamisen. [Täyssolmu](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) tarkistaa, että [transaktioilla](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) on kelvolliset allekirjoitukset, että bitcoineja ei ole jo käytetty, että lohkot täyttävät [työtodistevaatimukset](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ja että uusien bitcoinien liikkeeseenlasku noudattaa [liikkeeseenlaskuaikataulua](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) jakavat kelvollista dataa vertaissolmuille ja hylkäävät virheellisen datan.
* [**Louhijat**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) keräävät odottavia [transaktioita](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), rakentavat [lo候koehdokkaita](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) ja kilpailevat [työtodisteen avulla](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Onnistunut [louhija](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [lähettää koko verkolle](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) lohkon ja voi saada sallitun [lohkon luontipalkkion](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) ja [transaktiomaksut](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Louhijat](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) auttavat järjestämään [transaktiot](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ja tekevät [tilikirjan](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) uudelleenkirjoittamisesta kallista.
* **Kehittäjät** tarkastavat, kirjoittavat ja ehdottavat ohjelmistomuutoksia. He eivät omista Bitcoinin sääntöjä. Ohjelmistomuutoksella on merkitystä vain, jos osallistujat päättävät ajaa kyseisiä sääntöjä noudattavaa ohjelmistoa.


<!-- micrographic: bitcoin-participant-roles-01 -->


Nämä roolit rajoittavat toisiaan:

* käyttäjä ei voi käyttää bitcoineja ilman vaadittua kelvollista allekirjoitusta
* yksittäinen [louhija](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) voi ehdottaa lohkoa, mutta [solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) päättävät, noudattaako se sääntöjä
* eräs [solmu](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tekee tarkistukset omien sääntöjensä mukaisesti, mutta [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) edellyttää yhteensopivia sääntöjä koko verkossa
* kehittäjät voivat ehdottaa ohjelmistoja, mutta osallistujat päättävät, ottavatko he ne käyttöön

Jotkut ihmiset toimivat useissa rooleissa. [Louhija](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) voi ylläpitää [solmua](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ja olla myös käyttäjä. Aloittelijan ei tarvitse toimia kaikissa rooleissa voidakseen selittää, miten roolit tasapainottavat toisiaan.

**Pikakysymys:** Miksi [solmu](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tarkistaa [transaktioita](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Nimetkää vähintään yksi sääntö, jonka [solmu](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tarkistaa.

![Opettaja opastaa tekniikkaan perehtyvää opiskelijaa solmutietokoneen ääressä. Näyttö on heitä kohti, ja sen takakotelo näkyy katsojalle.](https://cdn.sanity.io/images/vje9ehw2/production/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
