# 3.14 On-chain platby a platby přes Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – On-chain platby a platby přes Lightning**
>
> [On-chain platby](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) se v síti Bitcoin zapisují do [blockchainu](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) a získávají [potvrzení](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning je platební síť postavená na Bitcoinu, která umožňuje rychlé a časté platby. Platba přes Lightning může proběhnout rychle, nebo selhat, a peněženka pro tyto platby může být s úschovou u poskytovatele i s vlastní úschovou.



> **Dark – Způsob platby neurčuje způsob úschovy**
>
> On-chain platby a platby přes Lightning obnášejí různé [kompromisy](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Peněženka pro Lightning může být s úschovou u poskytovatele i s vlastní úschovou a rychlá úspěšná platba nedokazuje, že je služba vhodná pro větší zůstatky nebo pro každou situaci.



<!-- micrographic: onchain-lightning-table-01 -->


Jaký způsob platby příjemce očekává? Před zaplacením si ověřte, zda poskytl on-chain adresu, nebo [fakturu sítě Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) či platební požadavek. On-chain peněženka nemůže přímo zaplatit každou [fakturu sítě Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) a peněženka pro Lightning nemusí podporovat všechny on-chain operace. Některé aplikace podporují oba způsoby platby, ale mohou přidávat poplatky nebo závislost na dalších službách. Podrobné nastavení sítě Lightning, kanály, směrování a [likvidita](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) jsou součástí [rozšiřujícího studia](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); praktický nácvik se skutečnými platbami v místním prostředí patří do **modulu 4**, pokud je to bezpečné a vhodné.

Představte si, že připravený scénář nabízí oba způsoby platby. Který požadavek lze v zamýšlené peněžence použít a co byste před schválením platby zkontrolovali? Odpověď závisí na platebním požadavku příjemce, peněžence a situaci — nikoli na nějakém univerzálně „nejlepším“ způsobu platby.

![Vyučující ukazuje na tabuli dvě různé geometricky znázorněné platební cesty, zatímco je začátečníci a technicky zaměření studenti zvažují.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
