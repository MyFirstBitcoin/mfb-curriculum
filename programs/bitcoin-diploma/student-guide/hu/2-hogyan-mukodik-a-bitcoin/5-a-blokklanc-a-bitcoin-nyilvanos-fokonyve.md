# 2.5 A blokklánc: a Bitcoin nyilvános főkönyve

<!-- card: definition -->
> **Definition – Blokklánc**
>
> A Bitcoin [blokklánca](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) egy nyilvános [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)-nyilvántartás, amelynek másolata számos független számítógépen megtalálható. Egy blokk az érvényes [tranzakciók](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) egy csoportját foglalja össze a nyilvántartás következő javasolt részeként. Minden érvényes blokk az előzőhöz kapcsolódik, így a hálózat számára rendezett, közös előzményt biztosít, amelyet ellenőrizni lehet.



<!-- card: light -->
> **Hogyan jutnak konszenzusra a csomópontok?**
>
> [A csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) egymástól függetlenül ellenőrzik ugyanazokat a szabályokat, és azt az érvényes előzményt fogadják el, amely mögött a legtöbb felhalmozott [munkabizonyíték áll](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Egy korábbi bejegyzés megváltoztatása módosítja az azt tartalmazó blokkot, és megszakítja a későbbi blokkokhoz vezető kapcsolatokat, ezért egy versengő előzménynek újra el kell végeznie ezt a munkát, és be kell hoznia a lemaradását, mielőtt a [csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) elfogadnák. Ez a költséges sorrendbe rendezési folyamat segíti a hálózatot abban, hogy [konszenzusra](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) jusson központi nyilvántartó nélkül. A másolatok nem egyszerre változnak; a [csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) egymástól függetlenül fogadják és érvényesítik az adatokat. A Bitcoin célja, hogy átlagosan körülbelül tízpercenként jöjjön létre egy új blokk. Az előzmény átírása nehéz és költséges, de a megváltoztatása nem szó szerint lehetetlen: átmenetileg versengő előzmények és láncátszerveződések is előfordulhatnak.
