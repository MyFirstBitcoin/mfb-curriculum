# 2.3 Rani pokušaji stvaranja digitalnog novca i problem dvostruke potrošnje

Bitcoin nije bio prvi pokušaj stvaranja digitalnog novca. Nastao je na osnovu četiri decenije eksperimentisanja, oslanjajući se na ideje iz mnogih ranijih projekata koji su pomogli u oblikovanju njegovog uspešnog dizajna.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) je koristio [kriptografiju](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) za omogućavanje privatnih digitalnih plaćanja. Zavisio je od jedne centralne kompanije i saradnje sa bankama. Kada je kompanija propala, sistem nije mogao da nastavi da funkcioniše kao nezavisna novčana mreža.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) je koristio [dokaz o radu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) kako bi slanje neželjene elektronske pošte učinio skupim. Računar pošiljaoca morao je da obavi rad pre slanja poruke. Ova ideja je pokazala kako trošak računarske obrade može da obeshrabri zloupotrebu.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) je opisivao predloženi sistem u kojem bi računarski rad mogao da stvara oskudne digitalne zapise. Nije pokrenut kao potpun decentralizovani novčani sistem, ali je razvio važne ideje o digitalnoj [oskudici](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) i dokazivanju.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) i [**višekratni dokaz o radu (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) istraživali su načine na koje bi učesnici mogli da stvaraju ili prenose oskudnu digitalnu [vrednost](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) bez oslanjanja isključivo na jednu centralnu bazu podataka. Bili su nepotpuni, ali su pomogli da se razjasni šta bi bilo potrebno za funkcionalan sistem.
* Iako [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) nije bio novac, pokazao je da [mreža ravnopravnih učesnika](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) može da omogući mnogim nezavisnim računarima da razmenjuju informacije bez jednog centralnog servera koji kontroliše ceo sistem.

Zajedno, ovi eksperimenti su pokazali korisne delove slagalice. Takođe su razjasnili preostali problem.


<!-- card: definition -->
> **Definition – Dvostruko trošenje**
>
> [Dvostruko trošenje](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) je pokušaj slanja iste digitalne jedinice dvama primaocima. Digitalni podaci mogu se savršeno kopirati, pa je sistemu digitalnog novca potreban način da utvrdi koja [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) je važeća.


[Centralizovani sistemi](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) sprečavaju ovo tako što prepuštaju jednoj pouzdanoj bazi podataka da odredi koje je plaćanje bilo prvo. Dana 31. oktobra 2008. godine, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) je u svom belom papiru, [_Bitcoin: Elektronski gotovinski sistem ravnopravnih učesnika_](https://bitcoin.org/bitcoin.pdf), objasnio drugačiji pristup: javni sistem koji bi mogao da uspostavi zajedničku istoriju plaćanja bez banke, kompanije ili drugog centralnog autoriteta.

Beli papir je objedinio karakteristike potrebne za taj pristup:

1. **Jedna [mreža ravnopravnih učesnika](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) se objavljuju direktno mreži učesnika.
1. **[Digitalni potpisi](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** jedan [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) je tajna informacija kojom se kreira potpis za odobravanje trošenja; samo njegov vlasnik to može da uradi.
1. **Blokovi i [rudarenje](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) prikupljaju [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) u blokove i koriste [dokaz rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) da bi se nadmetali za dodavanje sledećeg bloka.
1. **Nezavisna [provera](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) proveravaju [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i blokove prema pravilima Bitcoin mreže.
1. **Zajednička istorija sa akumuliranim [dokazom rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** učesnici prepoznaju [važeći lanac](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) sastavljen od [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sa najviše [akumuliranog rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) kao zajedničku evidenciju.


<!-- micrographic: five-part-response-01 -->
[Pet delova zajedno rešava problem dvostrukog trošenja: mreža ravnopravnih učesnika, digitalni potpisi, blokovi i rudarenje, nezavisna provera i zajednička istorija sa najviše akumuliranog dokaza o radu. Zajedno omogućavaju mreži da odbaci ponovno trošenje istih sredstava bez centralnog autoriteta.](/micrographics/five-part-response-01/sr-Latn.md)


Ovaj modul detaljnije objašnjava ove pojmove. Zajedno su pružili praktičan odgovor na [problem dvostruke potrošnje](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): mreža može da odbije drugi pokušaj trošenja istog bitcoina bez oslanjanja na centralni autoritet. Bitcoin je ponudio kombinaciju koja je nedostajala i za kojom se tragalo tokom decenija eksperimenata sa digitalnim novcem.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
