# 3.4 Avaimet

Bitcoinin omistajuus varmistetaan kryptografisilla avaimilla.


> **Definition – Yksityinen avain**
>
> Yksittäinen [yksityinen avain](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) on salainen tieto, jonka avulla lompakko voi luoda kelvollisia [digitaalisia allekirjoituksia](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Allekirjoitus valtuuttaa vastaavan avaimen hallinnassa olevien bitcoinien käytön. Kuka tahansa, joka saa haltuunsa [yksityisen avaimen](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key), voi yleensä käyttää kyseiset varat.


Yksittäinen [**julkinen avain**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) johdetaan matemaattisesti [yksityisestä avaimesta](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Sen avulla allekirjoitus voidaan tarkistaa paljastamatta [yksityistä avainta](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Osoitteet luodaan [julkisen avaimen](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) tietojen pohjalta.

Keskeinen sääntö on yksinkertainen:

**Julkiset vastaanottotiedot voi jakaa. Varojen käyttöön tarvittavat yksityiset tiedot on pidettävä salassa.**

Yksittäinen [digitaalinen allekirjoitus](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) osoittaa, että vaadittu [yksityinen avain](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) on valtuuttanut [siirron](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Se ei sisällytä [yksityistä avainta](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) itse [siirtoon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tarkistavat allekirjoituksen ennen varojen käytön hyväksymistä.

Useimmat aloittelijoille tarkoitetut lompakot käyttävät [yhden allekirjoituksen mallia](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): yksi yksityinen avain valtuuttaa siirron. Nykyaikaiset lompakot hallitsevat useita avaimia automaattisesti. Aloittelijoiden ei pidä kopioida tai käsitellä yksittäisiä [yksityisen avaimen](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) merkkijonoja. Suojatkaa lompakon hyväksytty varmuuskopio ja noudattakaa sen palautusmenettelyä.

Yksikään asianmukaisesti toimiva kouluttaja, lompakkoyritys, vaihtopalvelun työntekijä, teknisen tuen työntekijä tai Bitcoin-kehittäjä ei tarvitse [yksityistä avaintanne](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) tai [palautuslausettanne](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Jokaiseen, joka pyytää jompaakumpaa, on suhtauduttava uhkana.


> **Light**
>
> **Kokeilkaa:** Lajitelkaa valmiit esimerkit kolmeen ryhmään: vastaanottamista varten turvallisesti jaettavat tiedot, salaiset varojen käyttötiedot sekä tiedot, jotka voivat olla julkisia mutta jotka tulisi silti pitää yksityisinä, kun ne liittyvät henkilöön.



<!-- micrographic: private-key-public-info-01 -->
