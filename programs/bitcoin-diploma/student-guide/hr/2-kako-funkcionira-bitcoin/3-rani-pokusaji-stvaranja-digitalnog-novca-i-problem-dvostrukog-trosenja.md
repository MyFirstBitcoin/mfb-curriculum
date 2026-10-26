# 2.3 Rani pokušaji stvaranja digitalnog novca i problem dvostrukog trošenja

Bitcoin nije bio prvi pokušaj stvaranja digitalnog novca. Nastao je na temelju četiri desetljeća eksperimentiranja, oslanjajući se na ideje iz mnogih ranijih projekata koji su pomogli oblikovati njegov uspješan dizajn.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) koristio je [kriptografiju](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) kako bi omogućio privatna digitalna plaćanja. Ovisio je o središnjoj tvrtki i odnosima s bankama. Kada je tvrtka propala, sustav nije mogao nastaviti funkcionirati kao neovisna novčana mreža.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) koristio je [dokaz rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) kako bi slanje neželjene e-pošte učinio skupim. Pošiljateljevo računalo moralo je obaviti računalni rad prije slanja poruke. Ta je ideja pokazala kako računalni trošak može odvratiti od zlouporabe.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) opisivao je prijedlog sustava u kojem bi računalni rad mogao stvarati oskudne digitalne zapise. Nije pokrenut kao cjelovit decentralizirani novčani sustav, ali je razvio važne ideje o digitalnoj [oskudnosti](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) i dokazivanju.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) i [**višekratni dokaz rada (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) istraživali su načine na koje bi sudionici mogli stvarati ili prenositi oskudnu digitalnu [vrijednost](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) bez oslanjanja isključivo na jednu središnju bazu podataka. Bili su nedovršeni, ali su pomogli razjasniti što bi funkcionalnom sustavu bilo potrebno.
* Iako [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) nije bio novac, pokazao je da [mreža ravnopravnih čvorova](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) može omogućiti mnogim neovisnim računalima da dijele informacije bez jednog središnjeg poslužitelja koji upravlja cijelim sustavom.

Ti su eksperimenti zajedno pokazali korisne dijelove slagalice. Također su razjasnili preostali problem.


> **Definition – Dvostruko trošenje**
>
> [Dvostruko trošenje](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) pokušaj je slanja iste digitalne jedinice dvama primateljima. Digitalni podaci mogu se savršeno kopirati, pa sustavu digitalnog novca treba način da utvrdi koja je [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) valjana.


[Centralizirani sustavi](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) to sprječavaju tako da jednoj pouzdanoj bazi podataka prepuštaju odluku o tome koje je plaćanje stiglo prvo. Dana 31. listopada 2008., [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) u svojoj je bijeloj knjizi, [_Bitcoin: sustav elektroničkog novca s ravnopravnim čvorovima_](https://bitcoin.org/bitcoin.pdf), objasnio drukčiji pristup: javni sustav koji bi mogao uspostaviti zajedničku povijest plaćanja bez banke, tvrtke ili drugog središnjeg tijela.

Bijela knjiga objedinila je značajke potrebne za taj pristup:

1. **Jedna [mreža ravnopravnih čvorova](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) se objavljuju izravno mreži sudionika.
1. **[Digitalni potpisi](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** jedan [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) tajni je podatak kojim se stvara potpis za odobravanje trošenja; to može učiniti samo njegov vlasnik.
1. **Blokovi i [rudarenje](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) prikupljaju [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) u blokove i koriste [dokaz rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) kako bi se natjecali za dodavanje sljedećeg bloka.
1. **Neovisna [provjera](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) provjeravaju [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i blokove prema pravilima Bitcoina.
1. **Zajednička povijest s akumuliranim [dokazom rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** sudionici prepoznaju [valjani lanac](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) sastavljen od [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) s najviše [akumuliranog rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) kao zajednički zapis.


<!-- micrographic: five-part-response-01 -->


Ovaj modul detaljnije objašnjava te koncepte. Zajedno su pružili praktičan odgovor na [problem dvostruke potrošnje](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): mreža može odbiti drugi pokušaj trošenja istog bitcoina bez oslanjanja na središnje tijelo. Bitcoin je ponudio kombinaciju koja je nedostajala, a za kojom se tragalo desetljećima kroz eksperimente s digitalnim novcem.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
