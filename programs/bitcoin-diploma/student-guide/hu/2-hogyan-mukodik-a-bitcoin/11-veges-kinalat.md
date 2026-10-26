# 2.11 Véges kínálat

A Bitcoin szabályai kiszámítható [kibocsátási ütemtervet](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule) és [maximális készletet](https://curriculum.myfirstbitcoin.org/lexicon/en/#maximum-supply) határoznak meg: 21 millió bitcoin (21 000 000 BTC). Az új bitcoinok a [blokktámogatás](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) révén kerülnek forgalomba, amelyet a [bányászoknak](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) fizetnek az érvényes blokkok létrehozásáért.


> **Definition – Felezés**
>
> A támogatás 210 000 blokkonként a felére csökken. Ennek az eseménynek a neve: [felezés](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving). Mivel átlagosan körülbelül tízpercenként jön létre egy blokk, a [felezés](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving) nagyjából négyévente következik be. A pontos naptári dátum nincs előre rögzítve.



| A felezés éve | Blokkmagasság | Támogatás a felezés után |
| --- | --- | --- |
| 2012 | 210 000 | 25 BTC |
| 2016 | 420 000 | 12,5 BTC |
| 2020 | 630 000 | 6,25 BTC |
| 2024 | 840 000 | 3,125 BTC |
| Várhatóan 2028 | 1 050 000 | 1,5625 BTC |


A támogatás kezdetben blokkonként 50 BTC volt. Újra és újra a felére csökken, amíg túl kicsivé nem válik a folytatáshoz. [A bányászok](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) emellett kapnak [tranzakciós díjakat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). Idővel a díjak várhatóan egyre fontosabb szerepet töltenek be a [bányászok](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bevételében.


<!-- micrographic: bitcoin-issuance-schedule-01 -->


A 21 milliós korlát betartását biztosítják a [csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node). Ha egy [bányász](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) több bitcoint hoz létre, mint amennyit a szabályok megengednek, az [ellenőrző csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) elutasítják a blokkot. Egy szoftverfejlesztő írhat eltérő kódot, de nem kényszeríthet másokat annak futtatására.


> **Dark – A rögzített kínálat hálózati szabály, nem árfolyamígéret**
>
> A Bitcoin kínálati szabálya nyilvános, függetlenül ellenőrizhető, és egyetlen szereplő nehezen tudja megváltoztatni, mert [az érvényesítő csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) érvényesítik. Ez nem fizikai törvény: addig marad érvényben, amíg a résztvevők továbbra is érvényesítik. A korlátozott kínálat nem garantál emelkedő piaci [árat](https://curriculum.myfirstbitcoin.org/lexicon/en/#price); [az ár](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) a kereslettől is függ.
>
> Számos [digitális eszköz](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-asset) esetében állíthatják, hogy korlátozott a kínálata. Vizsgálja meg, hogy a korlát a gyakorlatban is hiteles-e, ne csak azt, hogy szerepel-e egy dokumentumban vagy egy weboldalon.


**Ellenőrző kérdés:** Milyen előnyei vannak annak, hogy a Bitcoin kínálata korlátozott? Milyen hatással lenne a Bitcoin kínálatának növelése a [vásárlóerőre](https://curriculum.myfirstbitcoin.org/lexicon/en/#purchasing-power)? Ki utasítaná el a kínálat növelését?


> **Light**
>
> A véges kínálat azt sem jelenti, hogy minden bitcoin eladó; egyes bitcoinokat hosszú távon tarthatnak, mások pedig hozzáférhetetlenné válhatnak az elveszett kulcsok miatt.


![](https://cdn.sanity.io/images/vje9ehw2/staging/04f25cd9a85bf20081aaefaf24cb8b6da98f5332-1536x1024.svg)
