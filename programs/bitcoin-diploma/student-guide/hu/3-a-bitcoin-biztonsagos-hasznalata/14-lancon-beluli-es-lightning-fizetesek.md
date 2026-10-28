# 3.14 Láncon belüli és Lightning-fizetések

![](https://cdn.sanity.io/images/vje9ehw2/production/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->
[A láncon belüli fizetéseket közvetlenül a Bitcoin blokkláncán rögzítik, míg a Lightning a Bitcoinra épülő fizetési hálózat, amely gyors, gyakori fizetésekre szolgál, de ezek sikertelenek is lehetnek. Mindkét megoldás használható letétkezelővel vagy saját kezelésben.](/micrographics/on-chain-and-lightning-01/hu.md)



<!-- card: definition -->
> **Definition – On-chain és Lightning-fizetések**
>
> [Az on-chain fizetések](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) rögzítésre kerülnek a Bitcoin [blokkláncán](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) és [megerősítéseket kapnak](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). A Lightning a Bitcoinra épülő fizetési hálózat, amely gyors, gyakori fizetéseket tesz lehetővé. Egy Lightning-fizetés gyorsan teljesülhet, de sikertelen is lehet, a hozzá használt tárca pedig lehet letétkezelői vagy saját kezelésű.



<!-- card: dark -->
> **A fizetés útvonala nem határozza meg a letétkezelés módját**
>
> Az on-chain és a Lightning-fizetések eltérő [kompromisszumokkal járnak](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Egy Lightning-tárca lehet letétkezelői vagy saját kezelésű, és egy gyors, sikeres fizetés nem bizonyítja, hogy a szolgáltatás nagyobb egyenlegek tárolására vagy minden helyzetben megfelelő.



<!-- micrographic: onchain-lightning-table-01 -->
[A láncon belüli Bitcoint és a Lightningot összehasonlító táblázat: a fogadáshoz szükséges adatok, a fizetés eredménye, jellemző felhasználás és ellenőrizendők kezdőknek. Mindkét megoldás használható letétkezelővel vagy saját letétkezeléssel.](/micrographics/onchain-lightning-table-01/hu.md)


Melyik útvonalat várja a címzett? Ellenőrizze fizetés előtt, hogy on-chain címet vagy [Lightning-számlát](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) vagy fizetési kérelmet adott-e meg. Egy on-chain tárca nem tud közvetlenül kiegyenlíteni minden [Lightning-számlát](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), és egy Lightning-tárca sem feltétlenül támogat minden on-chain műveletet. Egyes alkalmazások mindkét útvonalat támogatják, de további díjakkal vagy más szolgáltatásoktól való függőséggel járhatnak. A Lightning részletes beállítása, a csatornák, az útválasztás és a [likviditás](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) a [haladó tananyag része](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); az élő, helyi gyakorlat a **4. modulhoz** tartozik, amennyiben biztonságos és helyénvaló.

Képzelje el, hogy egy előre elkészített forgatókönyv mindkét fizetési útvonalat felkínálja. Melyik kérelmet tudja használni a kiválasztott tárca, és mit ellenőrizne a jóváhagyás előtt? A válasz a fogadáshoz megadott kérelemtől, a tárcától és a helyzettől függ — nem egy általánosan „legjobb” útvonaltól.

![Az oktató két különböző, geometriai alakzatokkal ábrázolt fizetési útvonalra mutat a táblán, miközben a kezdő és a műszaki beállítottságú tanulók ezeket mérlegelik.](https://cdn.sanity.io/images/vje9ehw2/production/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
