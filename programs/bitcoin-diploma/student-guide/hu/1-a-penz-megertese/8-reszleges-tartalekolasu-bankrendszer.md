# 1.8 Részleges tartalékolású bankrendszer

Amikor Ön készpénzt helyez el egy bankban, a bank egy [kötelezettséget](https://curriculum.myfirstbitcoin.org/lexicon/en/#liability) tart nyilván Önnel szemben: a számlaegyenleg összegével tartozik Önnek. A bank általában nem tartja minden betét teljes összegét fizikai készpénzben. Ehelyett [likvid tartalékokat](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity) tart — készpénzt vagy [eszközöket](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset), amelyeket gyorsan felhasználhat fizetések teljesítésére —, és a mérlegére támaszkodva hiteleket nyújt és más befektetéseket hajt végre.

Amikor egy kereskedelmi bank jóváhagy egy hitelt, általában új betétet hoz létre a hitelfelvevő számláján. Ez növeli a banki [számlapénz mennyiségét](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-deposit). A tőketartozás visszafizetésekor ez a [számlapénz](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-deposit) csökken. A bankok működését korlátozzák a [tőkére](https://curriculum.myfirstbitcoin.org/lexicon/en/#capital) vonatkozó szabályok, a [likviditási](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity) igények, a [hitelkockázat](https://curriculum.myfirstbitcoin.org/lexicon/en/#credit-risk), a szabályozás, a forrásbevonás költségei, valamint a hitelkereslet a [hitelképes hitelfelvevők részéről](https://curriculum.myfirstbitcoin.org/lexicon/en/#qualified-borrower).


<!-- micrographic: bank-loan-deposit-01 -->
[A banki hitelezés egyszerűsített folyamata: a hitelfelvevő hitelt igényel, a bank jóváhagyja a hitelt, és új betétet ír jóvá a hitelfelvevő számláján, majd a hitelfelvevő később visszafizeti a banknak a tőkét és a kamatot.](/micrographics/bank-loan-deposit-01/hu.md)


A bankok általában [nyereségre](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-profit) törekednek: kamataik és díjbevételeik származnak a hitelekből és befektetésekből, miközben fedezik működési, forrásbevonási és szabályozási költségeiket, és viselik a veszteségeket, ha a hitelfelvevők nem fizetnek. Ezek a tevékenységek és korlátok bankonként és joghatóságonként eltérnek.


<!-- card: definition -->
> **Definition – Részleges tartalékolású bankrendszer**
>
> [A részleges tartalékolású bankrendszer](https://curriculum.myfirstbitcoin.org/lexicon/en/#fractional-reserve-banking) olyan banki működést jelent, amelyben a bankok a betéti kötelezettségeiknek csak egy részét tartják azonnal hozzáférhető tartalékként, miközben hiteleket nyújtanak és más [eszközöket tartanak](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset). Az előírt tartalékszint és az egyéb korlátok országonként eltérnek, és idővel változhatnak.


Ez két fontos kockázatot teremt:

* **[Likviditási kockázat](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity-risk):** Egy bank rendelkezhet hosszú lejáratú hitelekkel, amelyek várhatóan megtérülnek, mégis előfordulhat, hogy nincs elegendő készpénze vagy gyorsan felhasználható [eszköze](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) ahhoz, hogy ma sok pénzkivételi igényt teljesítsen.
* **[Fizetőképességi kockázat](https://curriculum.myfirstbitcoin.org/lexicon/en/#solvency-risk):** A nem teljesítő hitelek vagy az [eszközök](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) [értékének csökkenése](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) miatt a bank teljes [eszközállománya](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) kevesebbet érhet, mint amennyivel a bank tartozik. Ebben az esetben a bank akkor sem tudja maradéktalanul teljesíteni kötelezettségeit, ha van ideje eladni az [eszközeit](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset).


<!-- micrographic: liquidity-vs-solvency-01 -->
[Likviditási kockázat: sok betétes áll sorban, hogy még ma kivegye a pénzét, és a banknak jelenleg nincs elég készpénze, bár az általa nyújtott hiteleket később még visszafizethetik. Fizetőképességi kockázat: a hitelfelvevők nem törlesztik a lakáshiteleiket, és a bank eszközei kevesebbet érnek, mint amennyivel tartozik.](/micrographics/liquidity-vs-solvency-01/hu.md)


![](https://cdn.sanity.io/images/vje9ehw2/production/f5f7999af936541b5928421cac58b3e5c7abd428-1536x1024.svg)



A [**bankroham**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-run) akkor következik be, amikor sok betétes egyszerre próbálja kivenni a pénzét vagy a számlaegyenlegét, mert attól tart, hogy a bank csődbe mehet. [A betétbiztosítás](https://curriculum.myfirstbitcoin.org/lexicon/en/#deposit-insurance) és a [jegybanki](https://curriculum.myfirstbitcoin.org/lexicon/en/#central-bank) hitelezés csökkentheti a pánikot, de a biztosításra való jogosultság és a fedezeti limitek joghatóságonként eltérnek. Ezek a védelmi intézkedések intézményektől és szabályoktól függenek, és egyes veszteségeket vagy kockázatokat az adott bankról a tágabb rendszerre háríthatnak át.

A szabályozás és a felügyelet csökkentheti a kockázatot, de nem előzheti meg a csalás, a rossz vezetés, a politikai visszaélés vagy az egyszerű hiba minden esetét. Ezek olyan lehetséges problémák, amelyeket mérlegelni kell, nem pedig minden bankrendszer szükségszerű velejárói.

A legfontosabb tanulság nem az, hogy minden bank a csőd szélén áll, hanem az, hogy a bankszámlaegyenleg a bank ígérete arra, hogy fizet Önnek. Ez nem azonos az elszámolási [eszköz](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) közvetlen birtoklásával.
