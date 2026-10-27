# 2.5 Lohkoketju: Bitcoinin julkinen tilikirja

<!-- card: definition -->
> **Definition – Lohkoketju**
>
> Bitcoinin [lohkoketju](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) on julkinen [siirtojen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) rekisteri, jota kopioidaan monille toisistaan riippumattomille tietokoneille. Lohko kokoaa joukon kelvollisia [siirtoja](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tämän rekisterin seuraavaksi ehdotetuksi osaksi. Jokainen kelvollinen lohko linkittyy edelliseen ja muodostaa näin verkolle järjestetyn, yhteisen historian tarkistettavaksi.



<!-- card: light -->
> **Miten solmut saavuttavat konsensuksen**
>
> [Solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tarkistavat itsenäisesti samojen sääntöjen noudattamisen ja päätyvät samaan kelvolliseen historiaan, jolla on eniten kertynyttä [työtodistetta](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Aiemman merkinnän muuttaminen muuttaa sen lohkoa ja rikkoo linkit myöhempiin lohkoihin, joten kilpailevan historian on tehtävä tuo työ uudelleen ja kurottava etumatka umpeen, ennen kuin [solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) hyväksyvät sen. Tämä kallis järjestämisprosessi auttaa verkkoa saavuttamaan [konsensuksen](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) ilman keskitettyä rekisterinpitäjää. Kopiot eivät muutu samanaikaisesti; [solmut](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) vastaanottavat ja validoivat tietoja itsenäisesti. Bitcoinin tavoitteena on yksi uusi lohko keskimäärin noin kymmenen minuutin välein. Historian uudelleenkirjoittaminen on vaikeaa ja kallista, mutta sen muuttaminen ei ole kirjaimellisesti mahdotonta: tilapäisiä kilpailevia historioita ja ketjun uudelleenjärjestelyjä voi esiintyä.
