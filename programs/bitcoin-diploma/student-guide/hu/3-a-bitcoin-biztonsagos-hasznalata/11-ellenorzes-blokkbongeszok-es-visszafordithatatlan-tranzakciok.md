# 3.11 Ellenőrzés, blokkböngészők és visszafordíthatatlan tranzakciók

<!-- card: definition -->
> **Definition – Tranzakcióazonosító és blokkböngésző**
>
> A [tranzakcióazonosító](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) egy láncon belüli [tranzakciót](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) azonosít. A [blokkböngésző](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) nyilvános Bitcoin-adatokat jelenít meg, például egy [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) állapotát és a [megerősítéseinek](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) számát. Hasznos betekintést nyújt, de nincs hatalma a Bitcoin felett, és nem bizonyítja a címzett személyazonosságát vagy becsületességét.


Mit mutathatnak meg ezek a nyilvános információk, és mit nem? Megmutathatják egy [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) állapotát, célcímét, összegét, díját és a [megerősítéseinek](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) számát; azt azonban nem bizonyíthatják, hogy miért történt egy fizetés, vagy hogy egy személy megbízható-e. Egy láncon belüli [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) még megerősítetlen, miután [közzétették a hálózaton](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) és megkapja az [első megerősítését](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) amikor bekerül egy érvényes blokkba. A későbbi blokkok növelik a bizonyosságot a nyilvántartásban elfoglalt helyét illetően, de nem orvosolják a hibás célcímet vagy a csalást. Nincs minden fizetésre általánosan érvényes [megerősítési](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) szám; a megfelelő ellenőrzés az összegtől és a kockázattól függ.

Egy előkészített [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ellenőrzéséhez szerezze be annak [_txid-jét_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), nyisson meg egy megbízható blokkböngészőt a kívánt [Bitcoin-hálózathoz](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network), és ellenőrizze az állapotot, a célcímet, az összeget, a díjat és a [megerősítéseket](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). A blokkböngésző csupán egy felület. Egy cím vagy [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) keresése felfedheti az üzemeltetője előtt, hogy az Ön eszköze az adott információ iránt érdeklődik. Gyakorláshoz használjon oktató által előkészített [tranzakciót](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) vagy kinyomtatott képernyőképet. Ne keressen rá egy tanuló személyes címére vagy [tranzakciójára](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) nyilvános szolgáltatásban. Ha később egy személyes fizetésnek jár utána, ismerje meg az [adatvédelem](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) és a biztonság terén jelentkező [kompromisszumokat](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) az Ön által használt kapcsolat esetében, mielőtt nyilvános szolgáltatást venne igénybe.


<!-- card: callout -->
> **A nyilvános adatok nem bizonyítják a személyazonosságot vagy a becsületességet**
>
> A [blokkböngésző](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) nyilvános [tranzakciós](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) adatokat jeleníthet meg, de nem tudja bizonyítani, hogy ki rendelkezik egy cím felett, miért történt egy fizetés, vagy hogy a címzett megbízható-e. A gyakorláshoz használjon előre elkészített példákat, és védje [a magánszféráját](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) a nyilvános szolgáltatásokban végzett keresések során.



<!-- micrographic: confirmation-timeline-01 -->
[Egy tranzakció megerősítés nélkül várakozik a függő tranzakciók gyűjtőhelyén, majd bekerül az N. blokkba, ami az első megerősítését jelenti, és minden későbbi blokk további egy megerősítést ad hozzá.](/micrographics/confirmation-timeline-01/hu.md)


![Az oktató és az idősebb tanuló egy előre elkészített példát beszél meg a csoport felé fordított monitoron, miközben a műszaki ismeretekkel rendelkező tanuló kezeli az egeret; a néző a monitor hátlapját látja.](https://cdn.sanity.io/images/vje9ehw2/staging/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
