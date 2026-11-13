# 2.11 Ograničena ponuda

Pravila Bitcoina definiraju predvidljiv [raspored izdavanja](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule) i [maksimalnu ponudu](https://curriculum.myfirstbitcoin.org/lexicon/en/#maximum-supply) od 21 milijun bitcoina (21.000.000 BTC). Novi bitcoini ulaze u optjecaj putem [subvencije za blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) koja se isplaćuje [rudarima](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) koji stvaraju valjane blokove.


<!-- card: definition -->
> **Definition – Prepolovljavanje**
>
> Svakih 210.000 blokova subvencija se prepolovi. Taj se događaj naziva [prepolovljavanje](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving). Budući da se blokovi stvaraju u prosjeku otprilike svakih deset minuta, [prepolovljavanje](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving) se događa otprilike svake četiri godine. Točan kalendarski datum nije unaprijed određen.



| Godina prepolovljavanja | Visina bloka | Subvencija nakon prepolovljavanja |
| --- | --- | --- |
| 2012 | 210.000 | 25 BTC |
| 2016 | 420.000 | 12,5 BTC |
| 2020 | 630.000 | 6,25 BTC |
| 2024 | 840.000 | 3,125 BTC |
| Očekivano 2028 | 1.050.000 | 1,5625 BTC |


Subvencija je na početku iznosila 50 BTC po bloku. Postupno se prepolovljuje sve dok ne postane premala za nastavak. [Rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) također primaju [naknade za transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). Očekuje se da će s vremenom naknade postati važniji dio [rudarskih](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) prihoda.


<!-- micrographic: bitcoin-issuance-schedule-01 -->
[Subvencija za blok počinje s 50 bitcoina i prepolovljuje se svakih 210.000 blokova, dok se ukupna količina izdanih bitcoina približava ograničenju od 21 milijun. Naknade za transakcije plaćaju se dodatno i nisu novi bitcoini; time se ne predviđa cijena.](/micrographics/bitcoin-issuance-schedule-01/hr.md)


Ograničenje od 21 milijun provode [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node). Ako [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) stvori više bitcoina nego što pravila dopuštaju, [čvorovi koji provjeravaju valjanost](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) odbacuju blok. Razvojni programer može napisati drukčiji kod, ali ne može prisiliti druge da ga pokreću.


<!-- card: dark -->
> **Fiksna ponuda pravilo je mreže, a ne obećanje cijene**
>
> Pravilo o ponudi Bitcoina javno je, može se neovisno provjeriti i teško ga je jednostrano promijeniti jer [validacijski čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) provode to pravilo. Ono nije fizikalni zakon: ostaje na snazi dok ga sudionici nastavljaju provoditi. Ograničena ponuda ne jamči rast tržišne [cijene](https://curriculum.myfirstbitcoin.org/lexicon/en/#price); [cijena](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) ovisi i o potražnji.
>
> Mnogi [oblici digitalne imovine](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-asset) mogu tvrditi da imaju ograničenu ponudu. Zapitajte se je li to ograničenje vjerodostojno u praksi, a ne samo je li zapisano u dokumentu ili prikazano na mrežnoj stranici.


**Pitanje za razmišljanje:** Koje su prednosti ograničene ponude Bitcoina? Kakav bi učinak povećanje ponude Bitcoina imalo na [kupovnu moć](https://curriculum.myfirstbitcoin.org/lexicon/en/#purchasing-power)? Tko bi odbio povećanje ponude?


<!-- card: light -->
> Ograničena ponuda također ne znači da je svaki bitcoin dostupan za prodaju; neki se mogu dugoročno čuvati ili postati nedostupni zbog izgubljenih ključeva.


![](https://cdn.sanity.io/images/vje9ehw2/staging/04f25cd9a85bf20081aaefaf24cb8b6da98f5332-1536x1024.svg)
