# 2.11 Ograničena ponuda

Pravila Bitcoin mreže definišu predvidiv [raspored izdavanja](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule) i [maksimalnu ponudu](https://curriculum.myfirstbitcoin.org/lexicon/en/#maximum-supply) od 21 milion bitcoina (21.000.000 BTC). Novi bitcoini ulaze u opticaj putem [subvencije za blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) koja se isplaćuje [rudarima](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) koji stvaraju važeće blokove.


<!-- card: definition -->
> **Definition – Prepolovljavanje**
>
> Na svakih 210.000 blokova subvencija se smanjuje za polovinu. Ovaj događaj se naziva [prepolovljavanje](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving). Pošto se blokovi stvaraju u proseku približno svakih deset minuta, [prepolovljavanje](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving) se dešava otprilike svake četiri godine. Tačan kalendarski datum nije unapred određen.



| Godina prepolovljavanja | Visina bloka | Subvencija nakon prepolovljavanja |
| --- | --- | --- |
| 2012 | 210.000 | 25 BTC |
| 2016 | 420.000 | 12,5 BTC |
| 2020 | 630.000 | 6,25 BTC |
| 2024 | 840.000 | 3,125 BTC |
| Očekuje se 2028 | 1.050.000 | 1,5625 BTC |


Početna subvencija iznosila je 50 BTC po bloku. Ona se uzastopno smanjuje za polovinu sve dok ne postane premala da bi se smanjivanje nastavilo. [Rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) takođe dobijaju [naknade za transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). Očekuje se da će vremenom naknade postati važniji deo [rudarskih](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) prihoda.


<!-- micrographic: bitcoin-issuance-schedule-01 -->
[Subvencija za blok počinje od 50 bitcoina i prepolovljava se na svakih 210.000 blokova, dok ukupna količina emitovanih bitcoina raste ka ograničenju od 21 milion. Naknade za transakcije plaćaju se dodatno i ne predstavljaju nove bitcoine; time se ne podrazumeva nikakva prognoza cene.](/micrographics/bitcoin-issuance-schedule-01/sr-Latn.md)


Ograničenje od 21 milion sprovode [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node). Ako [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) stvori više bitcoina nego što pravila dozvoljavaju, [čvorovi koji vrše validaciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) odbacuju blok. Programer može da napiše drugačiji kod, ali ne može da natera druge ljude da ga pokrenu.


<!-- card: dark -->
> **Fiksna ponuda je pravilo mreže, a ne obećanje o ceni**
>
> Pravilo o ponudi u Bitcoin mreži je javno, može se nezavisno proveriti i teško ga je jednostrano promeniti jer ga [čvorovi koji vrše validaciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) sprovode. To nije fizički zakon: ono ostaje na snazi dok god učesnici nastavljaju da ga sprovode. Ograničena ponuda ne garantuje rast tržišne [cene](https://curriculum.myfirstbitcoin.org/lexicon/en/#price); [cena](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) zavisi i od potražnje.
>
> Mnoga [digitalna sredstva](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-asset) mogu se predstavljati kao sredstva sa ograničenom ponudom. Zapitajte se da li je to ograničenje verodostojno u praksi, a ne samo da li je zapisano u dokumentu ili prikazano na veb-sajtu.


**Pitanje za razmišljanje:** Koje su prednosti ograničene ponude u Bitcoin mreži? Kakav bi uticaj povećanje ponude u Bitcoin mreži imalo na [kupovnu moć](https://curriculum.myfirstbitcoin.org/lexicon/en/#purchasing-power)? Ko bi odbio povećanje ponude?


<!-- card: light -->
> Konačna ponuda takođe ne znači da je svaki bitcoin dostupan za prodaju; neki se mogu dugoročno čuvati ili postati nedostupni zbog izgubljenih ključeva.


![](https://cdn.sanity.io/images/vje9ehw2/production/04f25cd9a85bf20081aaefaf24cb8b6da98f5332-1536x1024.svg)
