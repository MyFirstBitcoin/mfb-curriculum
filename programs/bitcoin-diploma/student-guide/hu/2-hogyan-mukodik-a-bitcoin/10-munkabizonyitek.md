# 2.10 Munkabizonyíték

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Munkabizonyítás**
>
> [Munkabizonyítás](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) az a folyamat, amelyet a [bányászok](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) arra használnak, hogy versengjenek a következő blokk javaslatának jogáért.


A [hashfüggvény](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) az adatokat rögzített hosszúságú eredménnyé alakítja. A bemenet kis változása kiszámíthatatlan új eredményt ad. A [bányász](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) a javasolt blokkban egy kis adatrészletet módosít, és ismételten kiszámítja a blokk hashértékét. Egy eredmény csak akkor érvényes, ha a számértéke kisebb a hálózat [célértékénél](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), amely a szabályok által meghatározott küszöbérték; az alacsonyabb [célérték](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) azt jelenti, hogy kevesebb az [érvényes eredmény](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) és több próbálkozásra van szükség. Nincs rövidebb út, ezért a [bányászoknak](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) sok próbálkozásra lehet szükségük.

Amikor egy [bányász](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) talál egy [érvényes eredményt](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), akkor [szétküldi](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) a blokkot. [A csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) gyorsan ellenőrizhetik a bizonyítékot, noha annak megtalálása jelentős számítási munkát és energiát igényelt. Ha a blokk tartalmaz egy [tranzakciót](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), az a [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) megkapja az [első megerősítését](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): a bejegyzése bekerült egy érvényes blokkba. Minden utána hozzáadott érvényes blokk újabb [megerősítést](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) ad, így a [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) helyének átírása a [blokkláncban](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) költségesebbé válik. Ez a különbség fontos: a munka elvégzése költséges, az ellenőrzése viszont egyszerű.


<!-- micrographic: proof-of-work-process-01 -->


[A munkabizonyítás](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) több célt is szolgál:

* lehetővé teszi a független [bányászok](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) számára, hogy központi ütemező nélkül versengjenek
* költségessé teszi a [tranzakciók](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sorrendjének átírását
* a hálózat biztonságát valós eszközökhöz és energiához köti
* az egymással versengő érvényes előzmények közötti választás nyilvános módszerét támogatja: a legtöbb [felhalmozott munkával](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) rendelkező lánc kiválasztását

[A bányászat](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) nem old meg külső célokat szolgáló, hasznos egyenleteket. Célja, hogy biztosítsa a Bitcoin [tranzakcióinak sorrendjét](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). A hálózat rendszeresen módosítja a célértéket: ha a blokkok túl gyorsan érkeznek, csökkenti, ha pedig túl lassan, növeli azt, hogy a számítási teljesítmény változásai mellett is átlagosan körülbelül tízpercenként érkezzen egy blokk.

[A munkavégzés igazolása](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) valós energiaköltséggel jár. Támogatói szerint ez a költség alapozza meg a Bitcoin biztonságát, és keresletet teremthet a rugalmasan rendelkezésre álló vagy egyébként kihasználatlan energia iránt. Kritikusai a felhasznált energia mennyiségét és forrását kérdőjelezik meg. A felelős értékelés azt vizsgálja, hogy milyen energiát használnak fel, honnan származik, milyen biztonságot nyújt, és milyen alternatívákkal vetik össze.

![Az oktató, a kezdő tanuló és a műszaki érdeklődésű tanuló egy ventilátorral és külön tápegységgel rendelkező asztali bányászeszközről beszélget.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
