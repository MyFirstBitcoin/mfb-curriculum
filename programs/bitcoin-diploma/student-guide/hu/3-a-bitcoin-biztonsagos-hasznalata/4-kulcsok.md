# 3.4 Kulcsok

A Bitcoin esetében a tulajdonjogot kriptográfiai kulcsok biztosítják.


> **Definition – Privát kulcs**
>
> A [privát kulcs](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) olyan titkos információ, amely lehetővé teszi, hogy egy tárca érvényes [digitális aláírásokat](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) hozzon létre. Az aláírás engedélyezi a hozzá tartozó kulcs által ellenőrzött bitcoin elköltését. Bárki, aki megszerzi a [privát kulcsot](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key), általában elköltheti ezeket az összegeket.


A [**nyilvános kulcs**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) matematikai úton származtatható a [privát kulcsból](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Segít ellenőrizni az aláírást anélkül, hogy felfedné a [privát kulcsot](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). A címek a [nyilvános kulcs](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) adataiból jönnek létre.

Az alapvető szabály egyszerű:

**A fogadáshoz szükséges nyilvános adatok megoszthatók. A költéshez szükséges titkos adatoknak titokban kell maradniuk.**

A [digitális aláírás](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) bizonyítja, hogy a szükséges [privát kulcs](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) engedélyezett egy [tranzakciót](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Nem helyezi a [privát kulcsot](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) a [tranzakcióba](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [A csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ellenőrzik az aláírást, mielőtt elfogadják a költést.

A legtöbb kezdőknek szánt tárca [egyetlen aláírást](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature) használ: egy privát kulcs engedélyez egy tranzakciót. A modern tárcák automatikusan sok kulcsot kezelnek. A kezdők ne másoljanak és ne kezeljenek egyedi [privát kulcsot tartalmazó](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) karakterláncokat. Védje a tárca által jóváhagyott biztonsági mentést, és kövesse a tárca helyreállítási eljárását.

Egyetlen hiteles oktatónak, tárcaszolgáltatónak, tőzsdei alkalmazottnak, műszaki ügyfélszolgálati munkatársnak vagy Bitcoin-fejlesztőnek sincs szüksége az Ön [privát kulcsára](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) vagy [helyreállító kifejezésére](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Bárkit, aki ezt kéri, fenyegetésként kell kezelni.


> **Light**
>
> **Próbálja ki:** Sorolja az előkészített példákat három csoportba: fogadáshoz biztonságosan megosztható adatok, költéshez szükséges titkos adatok, valamint olyan adatok, amelyek lehetnek nyilvánosak, de egy személyhez kapcsolva mégis bizalmasan kezelendők.



<!-- micrographic: private-key-public-info-01 -->
