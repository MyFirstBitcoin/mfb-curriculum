# 2.9 Uporabniki, vozlišča in rudarji

Bitcoin deluje, ker različni udeleženci opravljajo različne vloge.

* **Uporabniki** prejemajo, hranijo in pošiljajo bitcoine. Uporabnik lahko nadzoruje svoje ključe, shranjene v denarnici, ali uporablja [skrbnika](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Uporabniki dajejo omrežju ekonomski pomen z odločitvami o tem, ali bodo sprejemali bitcoine ter katerim pravilom ali storitvam bodo zaupali.
* [**Vozlišča**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) poganjajo programsko opremo Bitcoin in neodvisno preverjajo pravila. [Polno vozlišče](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) preverja, ali [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) imajo veljavne podpise, ali bitcoini še niso bili porabljeni, ali bloki izpolnjujejo zahteve za [dokaz o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) in ali novi bitcoini sledijo [urniku izdajanja](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Vozlišča](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) delijo veljavne podatke z drugimi vozlišči in zavračajo neveljavne podatke.
* [**Rudarji**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) zbirajo čakajoče [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), sestavljajo [kandidatne bloke](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) in tekmujejo z [dokazom o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Uspešen [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [razpošlje](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok in lahko prejme dovoljeno [subvencijo za blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) in [transakcijske provizije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Rudarji](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pomagajo določati vrstni red [transakcij](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) in poskrbijo, da je [glavno knjigo](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) drago prepisati.
* **Razvijalci** pregledujejo, pišejo in predlagajo spremembe programske opreme. Niso lastniki pravil Bitcoina. Sprememba programske opreme ima pomen le, če se udeleženci odločijo poganjati programsko opremo, ki sledi tem pravilom.


<!-- micrographic: bitcoin-participant-roles-01 -->


Te vloge druga drugo omejujejo:

* uporabnik ne more porabiti bitcoinov brez zahtevanega veljavnega podpisa
* posamezen [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) lahko predlaga blok, vendar [vozlišča](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) odločijo, ali je skladen s pravili
* posamezno [vozlišče](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) preverja po lastnih pravilih, vendar [konsenz](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) zahteva združljiva pravila v celotnem omrežju
* razvijalci lahko predlagajo programsko opremo, vendar se udeleženci sami odločijo, ali jo bodo uporabljali

Nekateri ljudje opravljajo več vlog. Posamezen [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) lahko upravlja [vozlišče](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) in je hkrati tudi uporabnik. Začetniku ni treba opravljati vseh vlog, da bi pojasnil, kako se vloge medsebojno uravnovešajo.

**Kratko vprašanje:** Zakaj posamezno [vozlišče](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) preverja [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Navedite vsaj eno pravilo, ki ga [vozlišče](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) preverja.

![Izobraževalec usmerja tehnično usmerjenega udeleženca pri računalniku, na katerem deluje vozlišče; zaslon je obrnjen proti njima, gledalec pa vidi zadnjo stran njegovega ohišja.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
