# 10.9 Lightning-moduulin tarkistuslista

Varmistakaa ja selittäkää ennen Lightning-työpajaa:

* onko lompakko palveluntarjoajan hallinnoima vai käyttäjän omassa hallinnassa
* miten siihen siirretään varoja
* käytetäänkö varojen siirtämiseen tai nostamiseen lohkoketjutapahtumaa tai palvelua
* palautuminen ja toiminnan jatkuvuus, jos palveluntarjoajan toiminta lakkaa tai laite vikaantuu
* onko pyyntö lasku, tuettu [Lightning-osoite](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address), vai muuntyyppinen pyyntö
* summa, yksikkö, vastaanottaja, vanheneminen, maksu, rajat ja [likviditeettiin](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) liittyvät seikat
* miten onnistuminen, odotustila, vanheneminen tai epäonnistuminen ilmenee
* miten kumpikin osapuoli vahvistaa tuloksen itsenäisesti; ja
* ilman verkkoyhteyttä tehtävä simulaatio.


<!-- card: dark -->
> **Yksi onnistunut Lightning-maksu osoittaa vain, että tämä reitti toimi kerran**
>
> Se ei osoita, että lompakko soveltuu turvallisesti suurempien saldojen säilyttämiseen tai että sama reitti toimii kaikkialla.



<!-- micrographic: lightning-payment-sequence-01 -->
[Lightning-maksu kuudessa vaiheessa: vastaanottaja luo maksupyynnön, lähettäjä skannaa sen, tarkistaa vastaanottajan, summan, yksikön, voimassaoloajan ja siirtomaksun sekä hyväksyy maksun, maksu reititetään ja molemmat lompakot näyttävät tuloksen. Kumpikin lompakko voi olla säilytyspalvelun hallinnoima tai itsehallinnoitu, ja epäonnistuneen tai vanhentuneen maksun jälkeen aloitetaan alusta uudella maksupyynnöllä.](/micrographics/lightning-payment-sequence-01/fi.md)
