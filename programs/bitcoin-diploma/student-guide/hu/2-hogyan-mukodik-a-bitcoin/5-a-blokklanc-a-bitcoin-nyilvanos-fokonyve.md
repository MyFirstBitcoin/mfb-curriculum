# 2.5 A blokklánc: a Bitcoin nyilvános főkönyve

<!-- card: definition -->
> **Definition – Blokklánc**
>
> A Bitcoin [blokklánca](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) egy nyilvános [tranzakciós](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) nyilvántartás, amelynek másolata számos független számítógépen megtalálható. Egy blokk érvényes [tranzakciókat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) fog össze e nyilvántartás következő javasolt részeként. Minden érvényes blokk az előzőhöz kapcsolódik, így a hálózat számára rendezett, közös előzményeket biztosít az ellenőrzéshez.



<!-- card: definition -->
> **Definition – Csomópont**
>
> [A csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) egymástól függetlenül ugyanazokat a szabályokat ellenőrzik, és közös álláspontra jutnak arról, melyik érvényes előzmény mögött áll a legtöbb felhalmozott [munkabizonyíték](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Egy korábbi bejegyzés módosítása megváltoztatja az azt tartalmazó blokkot, és megszakítja a későbbi blokkokhoz vezető kapcsolatokat, ezért egy versengő előzmény létrehozásához újra el kell végezni ezt a munkát, és utol kell érni az elfogadott előzményt, mielőtt a [csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) elfogadják azt. Ez a költséges sorrendbe rendezési folyamat segíti a hálózatot a [konszenzus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) elérésében, központi nyilvántartó nélkül. A másolatok nem egyszerre változnak; a [csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) egymástól függetlenül fogadják és érvényesítik az adatokat. A Bitcoin célja, hogy átlagosan körülbelül tízpercenként jöjjön létre egy új blokk. Az előzmények átírása nehéz és költséges, de módosításuk nem szó szerint lehetetlen: átmenetileg versengő előzmények és átszerveződések is előfordulhatnak.
