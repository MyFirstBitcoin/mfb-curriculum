# 2.9 Korisnici, čvorovi i rudari

Bitcoin funkcionira jer različiti sudionici obavljaju različite uloge.

* **Korisnici** primaju, drže i šalju bitcoin. Korisnik može upravljati vlastitim ključevima pohranjenima u novčaniku ili koristiti usluge [skrbnika](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Korisnici daju mreži ekonomski smisao odabirom hoće li prihvaćati bitcoin te kojim pravilima ili uslugama vjeruju.
* [**Čvorovi**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) pokreću softver za Bitcoin i neovisno provjeravaju pravila. Jedan [puni čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) provjerava imaju li [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) valjane potpise, je li bitcoin već potrošen, zadovoljavaju li blokovi uvjete [dokaza rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) te slijede li novi bitcoini [raspored izdavanja](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) dijele valjane podatke s drugim čvorovima i odbacuju nevaljane podatke.
* [**Rudari**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) prikupljaju nepotvrđene [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), izrađuju [kandidatske blokove](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) i natječu se putem [dokaza rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Uspješan [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [odašilje](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok i može primiti dopuštenu [subvenciju za blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) i [transakcijske naknade](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pomažu odrediti redoslijed [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i čine [glavnu knjigu](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) skupom za prepravljanje.
* **Programeri** pregledavaju, pišu i predlažu izmjene softvera. Oni nisu vlasnici pravila Bitcoina. Izmjena softvera ima značaj samo ako sudionici odluče pokretati softver koji slijedi ta pravila.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Četiri uloge u Bitcoinu: korisnici primaju, čuvaju i šalju bitcoin, čvorovi neovisno provjeravaju pravila, rudari sastavljaju blokove kandidate uz dokaz rada, a razvojni programeri predlažu softver. Nijedna uloga sama ne kontrolira mrežu.](/micrographics/bitcoin-participant-roles-01/hr.md)


Ove se uloge međusobno ograničavaju:

* korisnik ne može potrošiti bitcoin bez potrebnog valjanog potpisa
* jedan [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) može predložiti blok, ali [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) odlučuju slijedi li on pravila
* jedan [čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) provjerava prema vlastitim pravilima, ali [konsenzus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) zahtijeva usklađena pravila u cijeloj mreži
* razvojni programeri mogu predložiti softver, ali sudionici biraju hoće li ga pokrenuti

Neki ljudi obavljaju više uloga. Jedan [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) može pokretati [čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) i ujedno biti korisnik. Početnik ne mora obavljati svaku ulogu da bi objasnio kako se te uloge međusobno uravnotežuju.

**Kratko pitanje:** Zašto [čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) provjerava [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Navedite barem jedno pravilo koje [čvor](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) provjerava.

![Edukator vodi polaznika tehničkog usmjerenja za računalom na kojem je pokrenut čvor, pri čemu je monitor okrenut prema njima, a gledatelju je vidljiva stražnja strana njegova kućišta.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
