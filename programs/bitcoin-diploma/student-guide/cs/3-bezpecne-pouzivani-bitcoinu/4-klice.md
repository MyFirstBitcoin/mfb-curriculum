# 3.4 Klíče

Vlastnictví v síti Bitcoin je zajištěno kryptografickými klíči.


> **Definition – Soukromý klíč**
>
> Každý [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) je tajná informace, která peněžence umožňuje vytvářet platné [digitální podpisy](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Podpis opravňuje k utrácení bitcoinů ovládaných příslušným klíčem. Kdokoli získá [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key), může tyto prostředky obvykle utratit.


Každý [**veřejný klíč**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) je matematicky odvozen ze [soukromého klíče](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Pomáhá ověřit podpis, aniž by odhalil [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adresy se vytvářejí z [veřejnoklíčových](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) informací.

Základní pravidlo je jednoduché:

**Veřejné údaje pro příjem lze sdílet. Soukromé údaje pro utrácení musí zůstat v tajnosti.**

Každý [digitální podpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) dokazuje, že požadovaný [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) autorizoval [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Nevkládá [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) do [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ověřují podpis před přijetím útraty.

Většina peněženek pro začátečníky používá [jeden podpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): jeden soukromý klíč autorizuje transakci. Moderní peněženky spravují mnoho klíčů automaticky. Začátečníci by neměli kopírovat ani zpracovávat jednotlivé [soukromoklíčové](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) řetězce. Chraňte zálohu schválenou pro danou peněženku a dodržujte její postup obnovy.

Žádný důvěryhodný vzdělavatel, společnost vyvíjející peněženku, zaměstnanec burzy, pracovník technické podpory ani vývojář Bitcoinu nepotřebuje váš [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ani [obnovovací frázi](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Každého, kdo tyto údaje požaduje, byste měli považovat za hrozbu.


> **Light**
>
> **Vyzkoušejte si to:** Roztřiďte připravené příklady do tří skupin: údaje pro příjem, které lze bezpečně sdílet, tajné údaje pro utrácení a údaje, které mohou být veřejné, ale pokud jsou spojeny s konkrétní osobou, měly by přesto zůstat soukromé.



<!-- micrographic: private-key-public-info-01 -->
