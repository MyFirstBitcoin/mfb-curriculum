# 2.9 Korisnici, čvorovi i rudari

Bitcoin funkcioniše zato što različiti učesnici obavljaju različite uloge.

* **Korisnici** primaju, čuvaju i šalju bitcoin. Korisnik može samostalno upravljati svojim ključevima koji se čuvaju u novčaniku ili koristiti usluge [čuvara sredstava](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Korisnici daju mreži ekonomski smisao time što biraju da li će prihvatati bitcoin i kojim pravilima ili uslugama veruju.
* [**Čvorovi**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) pokreću softver za Bitcoin i nezavisno proveravaju pravila. Jedan [puni čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) proverava da li [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) imaju važeće potpise, da bitcoin nije već potrošen, da blokovi ispunjavaju uslove [dokaza rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) i da se novi bitcoin izdaje u skladu sa [rasporedom izdavanja](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) dele ispravne podatke sa drugim čvorovima i odbacuju neispravne podatke.
* [**Rudari**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) prikupljaju nepotvrđene [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), grade [kandidatske blokove](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) i takmiče se putem [dokaza rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Uspešan [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [emituje](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok i može dobiti dozvoljenu [subvenciju za blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) i [naknade za transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pomažu u određivanju redosleda [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i čine [glavnu knjigu](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) skupom za naknadno prepravljanje.
* **Programeri** pregledaju, pišu i predlažu izmene softvera. Oni nisu vlasnici pravila Bitcoin-a. Izmena softvera ima značaj samo ako učesnici odluče da pokreću softver koji sledi ta pravila.


<!-- micrographic: bitcoin-participant-roles-01 -->


Ove uloge međusobno se ograničavaju:

* korisnik ne može potrošiti bitcoin bez potrebnog važećeg potpisa
* jedan [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) može predložiti blok, ali [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) odlučuju da li je on u skladu sa pravilima
* jedan [čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) proverava prema sopstvenim pravilima, ali [konsenzus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) zahteva usklađena pravila širom mreže
* programeri mogu da predlože softver, ali učesnici biraju da li će ga pokrenuti

Neki ljudi obavljaju više uloga. Jedan [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) može da pokreće jedan [čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) i da istovremeno bude korisnik. Početnik ne mora da obavlja svaku ulogu da bi objasnio kako se te uloge međusobno uravnotežuju.

**Kratko pitanje:** Zašto jedan [čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) proverava [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Navedite bar jedno pravilo koje jedan [čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) proverava.

![Predavač usmerava učenika zainteresovanog za tehniku za računarom na kojem radi čvor, pri čemu je monitor okrenut ka njima, a zadnja strana njegovog kućišta vidljiva posmatraču.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
