# 2.3 Varhaiset digitaalisen rahan kokeilut ja kaksoiskulutuksen ongelma

Bitcoin ei ollut ensimmäinen yritys luoda digitaalista rahaa. Se rakentui neljän vuosikymmenen kokeilujen varaan ja hyödynsi monien aiempien hankkeiden ideoita, jotka auttoivat muovaamaan sen onnistunutta rakennetta.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) käytti [kryptografiaa](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) yksityisyyttä suojaavien digitaalisten maksujen tukena. Se oli riippuvainen yhdestä keskeisestä yrityksestä ja pankkisuhteista. Kun yritys kaatui, järjestelmä ei voinut jatkaa itsenäisenä rahaverkkona.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) käytti [työtodistetta](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) tehdäkseen roskapostin lähettämisestä kallista. Lähettäjän tietokoneen oli tehtävä laskentatyötä ennen viestin lähettämistä. Idea osoitti, miten laskennan kustannukset voivat ehkäistä väärinkäyttöä.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) kuvasi ehdotusta järjestelmäksi, jossa laskentatyöllä voitaisiin luoda niukkoja digitaalisia tietueita. Sitä ei käynnistetty täydellisenä hajautettuna rahajärjestelmänä, mutta siinä kehitettiin tärkeitä ajatuksia digitaalisesta [niukkuudesta](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) ja todistamisesta.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) ja [**uudelleenkäytettävä työtodiste (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) tutkivat tapoja, joilla osallistujat voisivat luoda tai siirtää niukkaa digitaalista [arvoa](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) tukeutumatta vain yhteen keskitettyyn tietokantaan. Ne olivat keskeneräisiä, mutta auttoivat selventämään, mitä toimiva järjestelmä tarvitsisi.
* Vaikka [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) ei ollut rahaa, se osoitti, että [vertaisverkko](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) voisi mahdollistaa tiedon jakamisen monien itsenäisten tietokoneiden kesken ilman, että yksi keskitetty palvelin hallitsisi koko järjestelmää.

Yhdessä nämä kokeilut toivat esiin hyödyllisiä palapelin osia. Ne myös selvensivät jäljellä olevaa ongelmaa.


<!-- card: definition -->
> **Definition – Kaksoiskulutus**
>
> [Kaksoiskulutus](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) tarkoittaa yritystä lähettää sama digitaalinen yksikkö kahdelle vastaanottajalle. Digitaalista tietoa voidaan kopioida täydellisesti, joten digitaalinen rahajärjestelmä tarvitsee tavan määrittää, mikä [siirto](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) on kelvollinen.


[Keskitetyt järjestelmät](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) estävät tämän antamalla yhden luotetun tietokannan päättää, kumpi maksu tuli ensin. 31. lokakuuta 2008 [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto)n tekninen kuvaus, [_Bitcoin: sähköinen vertaisverkkoon perustuva käteisjärjestelmä_](https://bitcoin.org/bitcoin.pdf), esitteli toisenlaisen lähestymistavan: julkisen järjestelmän, joka voisi muodostaa yhteisen maksuhistorian ilman pankkia, yritystä tai muuta keskusauktoriteettia.

Tekninen kuvaus kokosi yhteen tämän lähestymistavan edellyttämät ominaisuudet:

1. **Eräs [vertaisverkko](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [siirrot](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ilmoitetaan suoraan osallistujien muodostamalle verkolle.
1. **[Digitaaliset allekirjoitukset](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** eräs [yksityinen avain](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) on salainen tieto, jolla luodaan varojen käytön valtuuttava allekirjoitus; vain avaimen haltija voi tehdä tämän.
1. **Lohkot ja [louhinta](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [louhijat](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) keräävät [siirtoja](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) lohkoihin ja käyttävät [työtodistetta](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) kilpaillakseen seuraavan lohkon lisäämisestä.
1. **Riippumaton [varmennus](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tarkistavat [siirrot](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ja lohkot Bitcoinin sääntöjen mukaisesti.
1. **Yhteinen historia, johon on kertynyt [työtodistetta](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** osallistujat tunnistavat [kelvollisen ketjun](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) siihen kuuluvine [siirtoineen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), johon liittyy eniten [kertynyttä työtä](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work), yhteiseksi tapahtumahistoriaksi.


<!-- micrographic: five-part-response-01 -->
[Viisi osaa ratkaisee yhdessä kaksoiskulutusongelman: vertaisverkko, digitaaliset allekirjoitukset, lohkot ja louhinta, riippumaton varmentaminen sekä yhteinen historia, johon on kertynyt eniten työtodistetta. Yhdessä ne mahdollistavat sen, että verkko hylkää samojen varojen toistamiseen käyttämisen ilman keskusviranomaista.](/micrographics/five-part-response-01/fi.md)


Tässä moduulissa näitä käsitteitä selitetään tarkemmin. Yhdessä ne tarjosivat käytännön ratkaisun [kaksoiskulutusongelmaan](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): verkko voi hylätä toisen yrityksen käyttää sama bitcoin turvautumatta keskitettyyn tahoon. Bitcoin tarjosi puuttuvan yhdistelmän, jota vuosikymmenten digitaalisen rahan kokeiluissa oli etsitty.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
