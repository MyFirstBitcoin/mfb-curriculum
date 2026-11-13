# 4.7 Scenariji trošenja i primanja u lokalnoj zajednici

![](https://cdn.sanity.io/images/vje9ehw2/staging/fa265ee4b78004e155781ac30066875cd39cc983-1536x1024.svg)


<!-- micrographic: coffee-shop-payment-01 -->
[Plaćanje u kafiću u četiri koraka: kupac naručuje, konobar šalje račun, kupac plaća u bitcoinima sa svog telefona, a konobar predaje kafu.](/micrographics/coffee-shop-payment-01/sr-Latn.md)


Koristite lokalno poznatu robu i usluge. Nije važan konkretan proizvod, već logika plaćanja.

###### Scenario 1: Mala kupovina

Kupac želi da kupi svakodnevni proizvod. Trgovac prihvata Lightning i Bitcoin plaćanja na lancu.

* Koji način bi verovatno bio prikladan za malo, trenutno plaćanje?
* Ko kreira zahtev za plaćanje?
* Kako kupac proverava iznos i jedinicu?
* Kako trgovac zna da je plaćanje uspelo?
* Šta se dešava ako kupčev novčanik prikazuje „poslato“, ali trgovac ne vidi „primljeno“?

###### Scenario 2: Plaćanje za rad

Radnik pristaje da deo naknade primi u bitcoinu.

* Da li je [cena](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) fiksirana u lokalnoj [valuti](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency), bitcoinu ili [satošijima](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi)?
* U kom trenutku se [devizni kurs](https://curriculum.myfirstbitcoin.org/lexicon/en/#exchange-rate) određuje?
* Ko plaća eventualnu naknadu?
* Da li primalac koristi [samostalno čuvanje sredstava](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody)?
* Kakva je evidencija o prihodima ili porezima potrebna?
* Može li radnik bezbedno da upravlja tim iznosom?

###### Scenario 3: Prenos između članova porodice

Jedna osoba želi da pošalje [vrednost](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) članu porodice u drugom mestu.

* Koji su troškovi i koliko traje prenos trenutnim načinom?
* Kako će svaka osoba nabaviti ili koristiti bitcoin?
* Da li primalac želi bitcoin ili lokalnu [valutu](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency)?
* Koji se rizici pri razmeni i [čuvanju sredstava](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) javljaju u svakom koraku?
* Da li se celim postupkom štedi vreme ili novac kada se uračunaju sve naknade?

###### Scenario 4: Povraćaj sredstava

Trgovac treba da vrati [vrednost](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) nakon [plaćanja na lancu](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment).

* Zašto bi trgovac trebalo da zatraži novu adresu za povraćaj sredstava?
* Kako trgovac može da proveri da li je zahtev zaista došao od kupca?
* Ko plaća [naknadu za povratnu transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee)?
* Kakvu evidenciju treba da vode obe strane?

###### Scenario 5: Donacija zajednici

Lokalna organizacija želi da prima podršku u bitcoinima.

* Kako će donatori proveriti autentičnost zahteva za plaćanje?
* Ko kontroliše novčanik za prijem sredstava i njegovu rezervnu kopiju?
* Da li će se donacije primati na lancu, putem Lightning mreže ili na oba načina?
* Koje informacije treba da budu javne radi transparentnosti, a koje treba da ostanu privatne radi bezbednosti donatora?
* Koja evidencija je potrebna prema lokalnim pravilima o računovodstvu, porezima ili izveštavanju?

Za praktičnu vežbu koristite predmet male vrednosti ili simulaciju. Polaznik treba da bude u stanju da objasni ceo tok pre nego što odobri plaćanje.
