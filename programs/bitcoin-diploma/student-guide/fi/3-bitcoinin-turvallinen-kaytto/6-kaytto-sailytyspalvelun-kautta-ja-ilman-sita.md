# 3.6 Käyttö säilytyspalvelun kautta ja ilman sitä

<!-- card: definition -->
> **Definition – Säilytys**
>
> [Säilytys](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) vastaa käytännön kysymykseen: kuka hallitsee bitcoinien käyttämiseen tarvittavia avaimia?


Kun kyseessä on **säilytyspalvelullinen** palvelu, yritys tai toinen henkilö hallitsee avaimia. Teille näytettävä saldo on lupaus, jonka antaa [säilyttäjä](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Tavallisesti kirjaudutte sisään käyttäjätilillä ja pyydätte palvelua käsittelemään noston tai maksun.

Tämä ero on tärkeä todentamisen kannalta. Bitcoinin säännöt ja kokonaismäärän voi tarkistaa riippumattomasti, mutta jos ette hallitse avaimia, ette voi itsenäisesti tarkistaa, vastaako tilillänne näkyvä saldo bitcoineja, joita palvelu pitää hallussaan ja antaa käyttöönne. Julkinen lohkoketju voi näyttää avaimilla hallittavat bitcoinit, mutta se ei voi osoittaa, että palvelu on tietylle asiakkaalle velkaa tilillä näkyvän saldon verran. Ennen kuin voitte nostaa bitcoinit ja hallita avaimia, saldonne on palvelun lupaus toimittaa bitcoineja, ei bitcoineja, jotka voitte itse suoraan todentaa ja käyttää.

Kun käytätte **ei-säilytyspalvelullista** eli **itsehallinnoitua** lompakkoa, TE hallitsette avaimia. Lompakko allekirjoittaa [siirrot](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) valtuutuksellanne. Ohjelmistoihin, laitteistoihin, palvelimiin tai verkkoon liittyviä riippuvuuksia voi silti olla, mutta yhdenkään [säilyttäjän](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) ei tarvitse hyväksyä kelvollista lohkoketjussa tehtävää siirtoa.

![](https://cdn.sanity.io/images/vje9ehw2/production/f93df0cc4a2ad82b3410a9ad4c3273d1b760f8ea-1774x887.svg)


<!-- micrographic: who-controls-keys-01 -->
[Palvelun hallinnoimassa käytössä palvelu hallitsee avaimia ja hyväksyy varojen käytön, joten saldo on palvelun antama lupaus. Itse hallinnoidussa käytössä käyttäjä hallitsee avaimia ja varmuuskopioita; kumpaankin tapaan liittyy riippuvuuksia ja epäonnistumisen riskejä.](/micrographics/who-controls-keys-01/fi.md)



<!-- micrographic: custody-comparison-table-01 -->
[Taulukko, jossa verrataan käyttöä säilytyspalvelun kautta ja omassa säilytyksessä: kuka hallitsee avaimia, kuka huolehtii palautuksesta ja mikä on kummankin keskeinen kompromissi. Kumpikaan malli ei ole riskitön.](/micrographics/custody-comparison-table-01/fi.md)


[Säilytys](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) ei aina käy selvästi ilmi käyttöliittymästä. Jos ette voi hallita palautusmenetelmää ja tarvitsette yrityksen hyväksynnän nostolle, käytätte todennäköisesti [säilyttäjää](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). [Itsehallinta](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody) ei ole ihmisarvon mittari; tärkeintä on tunnistaa siihen liittyvä luottamuksen tarve ja riskit.

**Kokeilkaa:** Lukekaa kaksi valmiiksi laadittua lompakkokuvausta. Kertokaa kummastakin, kuka hallitsee avaimia, kuka voisi palauttaa pääsyn lompakkoon ja mikä yksi riski tulisi selvittää ennen sen käyttöä.
