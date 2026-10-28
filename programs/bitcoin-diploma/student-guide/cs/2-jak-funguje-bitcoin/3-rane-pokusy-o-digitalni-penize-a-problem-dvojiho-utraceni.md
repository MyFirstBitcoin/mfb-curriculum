# 2.3 Rané pokusy o digitální peníze a problém dvojího utrácení

Bitcoin nebyl prvním pokusem o digitální peníze. Vycházel ze čtyř desetiletí experimentování a čerpal z myšlenek mnoha dřívějších projektů, které pomohly utvářet jeho úspěšný návrh.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) používal [kryptografii](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) k zajištění soukromí při digitálních platbách. Závisel na jedné centrální společnosti a vztazích s bankami. Když společnost zkrachovala, systém nemohl pokračovat jako nezávislá peněžní síť.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) používal [důkaz prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ke zvýšení nákladů na odesílání nevyžádaných e-mailů. Počítač odesílatele musel před odesláním zprávy vykonat práci. Tato myšlenka ukázala, jak mohou výpočetní náklady odrazovat od zneužívání.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) popisoval návrh systému, v němž by výpočetní práce mohla vytvářet vzácné digitální záznamy. Nebyl spuštěn jako úplný decentralizovaný peněžní systém, ale rozvinul důležité myšlenky o digitální [vzácnosti](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) a dokazování.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) a [**opakovaně použitelný důkaz prací (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) zkoumaly způsoby, jak by účastníci mohli vytvářet nebo převádět vzácnou digitální [hodnotu](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) bez spoléhání pouze na jednu centrální databázi. Nebyly úplné, ale pomohly objasnit, co by funkční systém potřeboval.
* Přestože [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) nebyl penězi, ukázal, že [síť peer-to-peer](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) může mnoha nezávislým počítačům umožnit sdílet informace, aniž by celý systém řídil jeden centrální server.

Tyto experimenty společně ukázaly užitečné dílky skládačky. Také objasnily zbývající problém.


<!-- card: definition -->
> **Definition – Dvojí utrácení**
>
> [Dvojí utrácení](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) je pokus o odeslání téže digitální jednotky dvěma příjemcům. Digitální data lze dokonale kopírovat, a proto systém digitálních peněz potřebuje způsob, jak určit, která [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) je platná.


[Centralizované systémy](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) tomu brání tím, že nechávají jednu důvěryhodnou databázi rozhodnout, která platba přišla jako první. Dne 31. října 2008 [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) ve svém whitepaperu [_Bitcoin: elektronický peněžní systém typu peer-to-peer_](https://bitcoin.org/bitcoin.pdf) vysvětlil jiný přístup: veřejný systém, který by mohl vytvořit sdílenou historii plateb bez banky, společnosti nebo jiné centrální autority.

Whitepaper spojil vlastnosti potřebné pro tento přístup:

1. **Jedna [síť peer-to-peer](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) jsou oznamovány přímo síti účastníků.
1. **[Digitální podpisy](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** jeden [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) je tajná informace, která vytváří podpis pro schválení utracení prostředků; provést to může pouze jeho držitel.
1. **Bloky a [těžba](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [těžaři](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) shromažďují [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) do bloků a pomocí [důkazu prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) soutěží o přidání dalšího bloku.
1. **Nezávislé [ověřování](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrolují [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) a bloky podle pravidel Bitcoinu.
1. **Sdílená historie s nahromaděným [důkazem prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** účastníci uznávají [platný řetězec](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) tvořený [transakcemi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) s největším množstvím [nahromaděné práce](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) jako sdílený záznam.


<!-- micrographic: five-part-response-01 -->
[Pět prvků společně řeší problém dvojího utracení: síť typu peer-to-peer, digitální podpisy, bloky a těžba, nezávislé ověřování a sdílená historie s největším množstvím nahromaděné práce doložené důkazem prací. Společně umožňují síti odmítnout opětovné utracení stejných prostředků bez centrální autority.](/micrographics/five-part-response-01/cs.md)


Tento modul vysvětluje tyto pojmy podrobněji. Společně přinesly praktické řešení [problému dvojího utrácení](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): síť může odmítnout druhý pokus utratit tentýž bitcoin, aniž by se spoléhala na centrální autoritu. Bitcoin nabídl chybějící kombinaci, kterou se po desetiletí snažily najít experimenty s digitálními penězi.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
