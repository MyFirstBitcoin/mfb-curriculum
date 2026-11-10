# 4.5 Lightning-maksut

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning voi tehdä nopeista ja pienistä Bitcoin-maksuista käytännöllisiä. Se voi soveltua kauppiaan kassalle, toistuviin paikallisiin maksuihin, verkkopalveluihin tai siirtoihin, joissa lohkoketjusiirron maksu olisi liian suuri suhteessa maksettavaan summaan.

Paikallisessa Lightning-esittelyssä tulisi selvittää:

* onko lompakko säilytyspalvelun hallinnoima vai käyttäjän itse hallinnoima
* miten lompakkoon lisätään varoja
* edellyttääkö varojen lisääminen lohkoketjuun kirjattavaa [siirtoa](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tai jonkin palvelun käyttöä
* millainen varmuuskopiointi tai palautusmenetelmä suojaa saldoa
* minkä tyyppistä maksupyyntöä käytetään
* mitä maksuja tai rajoituksia sovelletaan
* mitä tapahtuu, jos maksu epäonnistuu
* miten vastaanottaja vahvistaa maksun

Yksittäinen [**Lightning-lasku**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) on tiettyä maksua varten luotu maksupyyntö. Se voi sisältää summan, vastaanottajan tiedot ja vanhenemisajan. Lukekaa lompakon [vahvistus](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) näytöltä ennen maksamista.

Yksittäinen [**Lightning-osoite**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) on ihmisen luettavissa oleva tunniste, jota jotkin palvelut tukevat. Se voi näyttää sähköpostiosoitteelta, mutta se on maksujen reititystä helpottava tunniste, ei sähköpostitili. Se on riippuvainen sitä tukevasta palveluntarjoajasta tai verkkotunnuksesta.

Ohjatun maksamisen vaiheet:

1. Vastaanottaja luo oikean maksupyynnön.
1. Lähettäjä skannaa tai kopioi sen.
1. Lähettäjä tarkistaa vastaanottajan, summan, yksikön ja siirtomaksun.
1. Lähettäjä hyväksyy maksun vasta, kun tiedot ovat oikein.
1. Molemmat osapuolet vahvistavat lopputuloksen omissa lompakoissaan.
1. Ryhmä selittää [säilytykseen](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) ja maksujen epäonnistumiseen liittyvät riskit.

Älkää olettako, että onnistunut Lightning-maksu todistaa lompakon olevan turvallinen suurempien saldojen säilyttämiseen. Maksamisen kätevyys ja [säilytyksen](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) turvallisuus ovat eri asioita.
