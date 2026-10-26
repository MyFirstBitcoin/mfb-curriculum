# 2.3 A digitális pénz korai kísérletei és a kettős költés problémája

A Bitcoin nem az első kísérlet volt a digitális pénz létrehozására. Négy évtizednyi kísérletezésre épült, számos korábbi projekt ötleteiből merítve, amelyek hozzájárultak sikeres kialakításához.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) használt [kriptográfiát](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) a bizalmas digitális fizetések támogatására. Egy központi vállalattól és banki kapcsolatoktól függött. Amikor a vállalat csődbe ment, a rendszer nem tudott független pénzhálózatként tovább működni.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) használt [munkabizonyítást](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) a kéretlen e-mailek küldésének költségessé tételére. A küldő számítógépének munkát kellett végeznie az üzenet elküldése előtt. Az ötlet megmutatta, hogyan tarthatja vissza a visszaéléseket a számítási költség.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) egy olyan javasolt rendszert írt le, amelyben számítási munkával szűkösen rendelkezésre álló digitális bejegyzéseket lehetett volna létrehozni. Nem indult el teljes értékű, decentralizált pénzrendszerként, de fontos elképzeléseket dolgozott ki a digitális [szűkösségről](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) és a bizonyításról.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) és az [**újrafelhasználható munkabizonyítás (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) azt vizsgálták, hogyan hozhatnak létre vagy ruházhatnak át a résztvevők szűkösen rendelkezésre álló digitális [értéket](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) anélkül, hogy kizárólag egyetlen központi adatbázisra támaszkodnának. Nem voltak teljesen kidolgozottak, de segítettek tisztázni, mire lenne szüksége egy működő rendszernek.
* Bár a [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) nem pénz volt, megmutatta, hogy egy [egyenrangú hálózat](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) lehetővé teheti számos független számítógép számára az információmegosztást anélkül, hogy egyetlen központi szerver irányítaná az egész rendszert.

Ezek a kísérletek együttesen a kirakós hasznos darabjait mutatták meg. Egyúttal a még megoldásra váró problémát is tisztázták.


> **Definition – Kettős költés**
>
> [A kettős költés](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) kísérlet ugyanannak a digitális egységnek két címzett részére történő elküldésére. A digitális adatok tökéletesen másolhatók, ezért egy digitális pénzrendszernek szüksége van egy módszerre annak megállapításához, hogy melyik [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) érvényes.


[A központosított rendszerek](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) ezt úgy akadályozzák meg, hogy egyetlen megbízható adatbázisra bízzák annak eldöntését, melyik fizetés történt előbb. 2008. október 31-én [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) fehér könyve, a [_Bitcoin: Egy egyenrangú elektronikus készpénzrendszer_](https://bitcoin.org/bitcoin.pdf), más megközelítést ismertetett: egy nyilvános rendszert, amely bank, vállalat vagy más központi hatóság nélkül képes közös fizetési előzményeket létrehozni.

A fehér könyv egyesítette az ehhez a megközelítéshez szükséges jellemzőket:

1. **Egy [egyenrangú hálózat](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [a tranzakciókat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) közvetlenül a résztvevők hálózatában teszik közzé.
1. **[Digitális aláírások](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** a [privát kulcs](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) olyan titkos információ, amellyel aláírás hozható létre egy költés engedélyezéséhez; erre csak a birtokosa képes.
1. **Blokkok és [bányászat](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [a bányászok](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gyűjtik a [tranzakciókat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) blokkokba, és [munkabizonyítékot](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) használva versenyeznek a következő blokk hozzáadásáért.
1. **Független [ellenőrzés](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [a csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ellenőrzik a [tranzakciókat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) és a blokkokat a Bitcoin szabályai alapján.
1. **Közös előzménytörténet felhalmozott [munkabizonyítékkal](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** a résztvevők az [érvényes láncot](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) az azt alkotó [tranzakciókkal](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) és a legtöbb [felhalmozott munkával](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) tekintik közös nyilvántartásnak.


<!-- micrographic: five-part-response-01 -->


Ez a modul részletesebben ismerteti ezeket a fogalmakat. Együttesen gyakorlati választ adtak a [kettős költés problémájára](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): a hálózat központi hatóságra való támaszkodás nélkül is elutasíthatja az ugyanazon bitcoin elköltésére tett második kísérletet. A Bitcoin biztosította azt a hiányzó kombinációt, amelyet a digitális pénzzel folytatott kísérletek évtizedeken át kerestek.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
