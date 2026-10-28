# 3.10 bitcoinin lähettäminen

**Harjoitus 2: pysähtykää ja tarkistakaa ennen lähettämistä**

Lähettäminen vaatii erityistä huolellisuutta, koska kelvollisen Bitcoin-verkon [siirron](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) peruuttaminen on yleensä vaikeaa tai mahdotonta. Osaatteko kertoa ennen hyväksymispainikkeen painamista, kuka saa maksun ja miksi?


<!-- card: callout -->
> **Pysähtykää ja varmistakaa tiedot ennen lähettämistä**
>
> Varmistakaa vastaanottaja, maksutapa, kohde, summa ja yksikkö, siirtomaksu tai vanhenemisaika sekä viimeisen näkymän tiedot. Jos jokin poikkeaa luotettavasta maksupyynnöstä tai joku luo kiireen tuntua tai pyytää palautustietoja, pysähtykää ja varmistakaa tiedot riippumattomasti. Tehkää ensin pieni testimaksu, jos toimintatapa on vieras.


1. Varmistakaa vastaanottaja ja maksun tarkoitus luotettavan kanavan kautta.
1. Varmistakaa maksutapa: lohkoketjumaksu vai Lightning.
1. Skannatkaa tai syöttäkää kohde ja verratkaa sitä sitten luotettavaan vastaanottonäkymään.
1. Tarkistakaa summa, yksikkö, siirtomaksu- tai vanhenemistiedot sekä lopullinen yhteenveto.
1. Tehkää ensin pieni testimaksu, jos toimintatapa on vieras.
1. Hyväksykää vasta, kun kaikki tiedot täsmäävät, ja tarkistakaa sitten maksun tulos.

![Vanhempi oppija esittelee harjoituspuhelinta, kun aloittelija tarkistaa toista puhelinta ja opettaja ohjaa vertailua.](https://cdn.sanity.io/images/vje9ehw2/production/8ce88167dc1b3c490b69bd8e045d32add1ce975d-1054x1492.png)


<!-- micrographic: pre-send-checklist-01 -->
[Ennen maksun hyväksymistä lähettäjä tarkistaa vastaanottajan ja maksun tarkoituksen, maksutavan, kohteen sekä summan, yksikön, siirtomaksun tai vanhenemisajan ja tekee pienen testimaksun, jos menettely on vieras. Jos jokin poikkeaa, hän pysähtyy ja varmistaa tiedot. Hän hyväksyy maksun vasta, kun kaikki tiedot täsmäävät, ja tarkistaa sitten tuloksen.](/micrographics/pre-send-checklist-01/fi.md)


Kun kyseessä on [lohkoketjumaksu](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment), **verkkomaksu** maksetaan siitä, että [siirto](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sisällytetään lohkoon. Se riippuu pääasiassa [siirron](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tiedoista ja kysynnästä, joka kohdistuu [lohkotilaan](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-space), ei pelkästään lähetettävästä summasta. Maksuarviot ja ajoitus voivat muuttua, joten lukekaa lopullinen yhteenveto sen sijaan, että olettaisitte pienen maksusumman tarkoittavan pientä siirtomaksua.

Mitä teidän pitäisi tehdä, jos kohde muuttuu odottamatta, maksupyynnöstä tulee kiireellinen tai joku pyytää palautustietoja? Pysähtykää. Varmistakaa maksupyyntö riippumattomasti tai pyytäkää apua paljastamatta salaisia tietoja.

![Opettaja ohjaa aloittelevaa oppijaa, kun he vertaavat puhelinta yrittäjän vastaanottolaitteeseen ennen maksun hyväksymistä.](https://cdn.sanity.io/images/vje9ehw2/production/2a3f35ea865512968fcaeb22e3c6fd06985394c5-1055x1491.png)
