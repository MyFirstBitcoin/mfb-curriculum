# 3.2 Lompakot

<!-- card: definition -->
> **Definition – Bitcoin-lompakko**
>
> Eräs [Bitcoin-lompakko](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-wallet) on työkalu, joka hallinnoi Bitcoin-verkossa tehtävien [siirtojen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) vastaanottamiseen ja hyväksymiseen tarvittavia tietoja. Se voi olla sovellus, erillinen laite tai palvelu. Bitcoin kirjataan [siirtojen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) historiana yhteiseen [tilikirjaan](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger); lompakko hallinnoi varojen käyttöä ohjaavia avaimia sen sijaan, että se säilyttäisi bitcoinia puhelimessa tai muussa laitteessa.


Mitä tapahtuisi, jos puhelimenne lakkaisi toimimasta? Bitcoinin kirjanpito olisi yhä olemassa, mutta pääsy varoihin riippuisi lompakon käyttämistä avaimista ja palautusmenetelmästä. Lompakko auttaa luomaan vastaanottotietoja, näyttämään saldot ja [siirtojen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) historian sekä hyväksymään varojen käytön. Se ei poista tarvetta ymmärtää, kuka hallitsee pääsyä varoihin.

![](https://cdn.sanity.io/images/vje9ehw2/production/887310fc77a85254db64aa7a92458a7aaf228b13-1536x1024.svg)


<!-- card: dark -->
> **Lompakko hallinnoi pääsyä varoihin; se ei säilytä bitcoinia**
>
> Bitcoin kirjataan yhteiseen [tilikirjaan](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger), ei puhelimenne sisälle. Ennen kuin käytätte lompakkoa, selvittäkää, kuka hallitsee avaimia, miten pääsy varoihin palautetaan ja mitä tapahtuisi, jos laite tai palvelu lakkaisi toimimasta.



<!-- micrographic: wallet-manages-keys-01 -->
[Lompakko sisältää avaimet. Niiden avulla voitte vastaanottaa ja lähettää bitcoinia, mutta itse bitcoinit pysyvät kirjattuina yhteiseen tilikirjaan, eivät puhelimen tai laitteen sisälle.](/micrographics/wallet-manages-keys-01/fi.md)


Ensimmäinen kysymys minkä tahansa lompakon kohdalla on: **kuka hallitsee avaimia?** Ennen kuin käytätte työkalua, tarkistakaa, kuka voi hyväksyä maksun, miten pääsy varoihin palautetaan ja mitä maksutapoja työkalu tukee. [**Avoimen lähdekoodin ohjelmiston**](https://curriculum.myfirstbitcoin.org/lexicon/en/#open-source-software) koodi julkaistaan kaikkien tarkasteltavaksi ja arvioitavaksi. Tämä voi parantaa läpinäkyvyyttä ja helpottaa virheiden löytämistä, mutta se on vain yksi hyödyllinen tekijä: se ei todista, että työkalu on turvallinen, ylläpidetty, oikein asennettu tai tarpeisiinne sopiva.

Vertailkaa [varojen hallintaa](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody), pääsyn palauttamista, koodin julkista tarkasteltavuutta, yhteensopivuutta, [yksityisyyttä](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy), kustannuksia, ylläpitoa ja saatavilla olevaa tukea pitämättä mitään lompakkoa kaikille sopivana valintana. Aloittakaa opettajan valmistelemasta ympäristöstä; älkää valitko työkalua siksi, että tuntematon henkilö suosittelee sitä.


<!-- card: callout -->
> **Harjoittelulompakot ja henkilökohtaiset lompakot**
>
> Diploma-kurssin aikana saatatte luoda lompakon tai kirjoittaa muistiin [palautussanat](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase) osana harjoittelua. Luokkahuone on oppimisympäristö: tietoja voidaan vahingossa nähdä, kopioida tai jakaa, tai niiden turvallisuus voi vaarantua. Siksi harjoittelulompakon tulisi tavallisesti olla tyhjä tai simuloitu, eikä sitä tulisi käyttää merkittävien varojen turvaamiseen. Mahdollisuuksien mukaan se suljetaan, nollataan tai palautetaan Diploma-kurssin päättyessä. Opettajanne voi valita oikeilla varoilla tehtävän harjoituksen, jossa mahdollinen menetys on pieni, mutta hänen tulisi selittää sen tarkoitus sekä siihen liittyvät yksityisyyttä, turvallisuutta ja varojen menettämistä koskevat lisäriskit ennen kenenkään osallistumista. Merkittävien varojen turvaamiseen tarkoitettu lompakko on otettava käyttöön alusta asti yksityisesti, ja sitä varten tarvitaan uudet palautustiedot. Opettajanne voi selittää eron, mutta henkilökohtaisen lompakon käyttöönottoa ei koskaan edellytetä Diploma-kurssin suorittamiseksi.


![Opettaja esittelee harjoittelupuhelinta samalla, kun aloittelija ja vanhemmat oppijat tutkivat omia laitteitaan.](https://cdn.sanity.io/images/vje9ehw2/production/229bbb2a2acdd2c137c9789d90e246381a660e22-1054x1492.png)
