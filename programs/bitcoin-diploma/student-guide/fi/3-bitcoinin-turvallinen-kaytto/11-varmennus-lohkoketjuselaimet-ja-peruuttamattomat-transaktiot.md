# 3.11 Varmennus, lohkoketjuselaimet ja peruuttamattomat transaktiot

<!-- card: definition -->
> **Definition – Siirtotunniste ja lohkoketjuselain**
>
> Yksittäinen [siirtotunniste](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) yksilöi lohkoketjuun tallennettavan [siirron](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Lohkoketjuselain](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) näyttää julkisia Bitcoin-tietoja, kuten [siirron](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tilan ja [vahvistusten](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) määrän. Se on hyödyllinen näkymä, ei Bitcoinia hallitseva auktoriteetti eikä todiste vastaanottajan henkilöllisyydestä tai rehellisyydestä.


Mitä nämä julkiset tiedot voivat näyttää ja mitä eivät? Ne voivat näyttää [siirron](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tilan, kohteen, summan, siirtomaksun ja [vahvistusten](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) määrän; ne eivät voi todistaa, miksi maksu tapahtui tai onko henkilö luotettava. Lohkoketjuun tallennettava [siirto](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) on vahvistamaton sen jälkeen, kun se on [lähetetty verkkoon](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast), ja se saa [ensimmäisen vahvistuksensa](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation), kun se sisällytetään kelvolliseen lohkoon. Myöhemmät lohkot lisäävät varmuutta sen paikasta kirjanpidossa, mutta ne eivät korjaa väärää kohdetta tai huijausta. Ei ole olemassa yhtä yleispätevää [vahvistusten](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) määrää kaikille maksuille; sopiva tarkistus riippuu summasta ja riskistä.

Tarkastellaksenne valmiiksi valmisteltua [siirtoa](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), hankkikaa sen [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), avatkaa luotettu lohkoketjuselain haluttua [Bitcoin-verkkoa](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) varten ja tarkistakaa tila, kohde, summa, siirtomaksu ja [vahvistukset](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lohkoketjuselain on vain käyttöliittymä. Osoitteen tai [_txid:n_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) hakeminen voi paljastaa palvelun ylläpitäjälle, että laitteenne on kiinnostunut kyseisistä tiedoista. Käyttäkää harjoitteluun opettajan valmistelemaa [siirtoa](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tai tulostettua kuvakaappausta. Älkää hakeko opiskelijan henkilökohtaista osoitetta tai [siirtoa](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) julkisesta palvelusta. Jos myöhemmin tutkitte henkilökohtaista maksua, selvittäkää [yksityisyyteen](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) ja turvallisuuteen liittyvät [kompromissit](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) käyttämässänne yhteydessä ennen julkisen palvelun käyttöä.


<!-- card: callout -->
> **Julkiset tiedot eivät todista henkilöllisyyttä tai rehellisyyttä**
>
> Eräs [lohkoketjuselain](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) voi näyttää julkisia [transaktio](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)tietoja, mutta se ei voi todistaa, kuka hallitsee osoitetta, miksi maksu tehtiin tai onko vastaanottaja luotettava. Käyttäkää harjoitteluun valmiiksi laadittuja esimerkkejä ja suojatkaa [yksityisyyttä](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) tehdessänne hakuja julkisissa palveluissa.



<!-- micrographic: confirmation-timeline-01 -->
[Siirto odottaa vahvistamattomana odottavien siirtojen varannossa, minkä jälkeen se sisällytetään lohkoon N ja saa ensimmäisen vahvistuksensa. Jokainen myöhempi lohko lisää yhden vahvistuksen.](/micrographics/confirmation-timeline-01/fi.md)


![Opettaja ja iäkkäämpi oppija keskustelevat valmiiksi laaditusta esimerkistä, joka näkyy ryhmään päin suunnatulla näytöllä, samalla kun tekniikkaan perehtynyt oppija käyttää hiirtä; katsojalle näkyy näytön takakuori.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
