# 8.10 Uživatelé, uzly, těžaři, vývojáři a služby

Používejte pro začátečníky přesně toto vymezení rolí:


| Role | Hlavní funkce pro začátečníky | Neznamená to, že |
| --- | --- | --- |
| Uživatel | Rozhoduje se přijímat, držet, posílat a ověřovat bitcoin a akceptovat jej jako platbu, přímo nebo prostřednictvím služeb | Automaticky provozuje všechny části sítě |
| Uzel | Nezávisle kontroluje transakce a bloky podle svých pravidel a předává dál platná data | Vytváří nové bloky nebo všem diktuje pravidla |
| Těžař | Sestavuje kandidátské bloky a provádí důkaz prací, aby navrhl jejich pořadí | Může zařídit, aby poctivé uzly považovaly neplatnou emisi nebo transakce za platné |
| Vývojář | Kontroluje, píše a navrhuje software | Může účastníky donutit přijmout změnu pravidel |
| Služba pro Bitcoin | Poskytuje peněženku, burzu, průzkumník bloků, platební nebo jiné rozhraní | Je samotným protokolem Bitcoinu |



<!-- micrographic: bitcoin-participant-roles-01 -->


#### Aktivita: neplatný blok

Dejte jednomu studentovi v roli [těžaře](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) jeden [kandidátský blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) s vyšší blokovou dotací, než dovoluje kartička pravidel [uzlu](https://curriculum.myfirstbitcoin.org/lexicon/en/#node). Studenti v roli [uzlů](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) jej zkontrolují a odmítnou.

Závěrečná reflexe:

* Tento [těžař](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) vykonal skutečnou práci, ale ani tak nezískal oprávnění porušovat pravidla.
* [Uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) nezávisle uplatňují pravidla, ale skutečná síť je založena na softwaru a komunikaci, nikoli na hlasování ve třídě.
* Vývojář může napsat jiná pravidla, ale jejich přijetí je dobrovolné a nekompatibilní pravidla mohou vést ke vzniku samostatné sítě.

Zeptejte se:

> Proč [uzel](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ověřuje transakce? Uveďte alespoň jedno pravidlo, které kontroluje.
