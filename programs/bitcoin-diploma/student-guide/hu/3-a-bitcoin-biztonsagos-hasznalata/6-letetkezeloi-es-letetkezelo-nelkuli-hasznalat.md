# 3.6 Letétkezelői és letétkezelő nélküli használat

<!-- card: definition -->
> **Definition – Letétkezelés**
>
> [A letétkezelés](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) arra a gyakorlati kérdésre ad választ: ki rendelkezik a bitcoin elköltéséhez szükséges kulcsokkal?


Egy **letétkezelői** szolgáltatás esetében egy vállalat vagy egy másik személy rendelkezik a kulcsokkal. A kijelzett egyenleg egy ígéret a [letétkezelőtől](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Ön általában egy felhasználói fiókkal jelentkezik be, és megkéri a szolgáltatót egy kiutalás vagy fizetés végrehajtására.

Ez a különbség fontos az ellenőrzés szempontjából. A Bitcoin szabályai és teljes kínálata függetlenül ellenőrizhetők, de ha nem Ön rendelkezik a kulcsokkal, nem tudja függetlenül ellenőrizni, hogy a fiókjában megjelenített egyenleg megfelel-e annak a bitcoinnak, amelyet a szolgáltató birtokol és az Ön rendelkezésére fog bocsátani. A nyilvános blokklánc megmutathatja, hogy mely kulcsokkal lehet rendelkezni a bitcoin felett; azt azonban nem tudja megmutatni, hogy egy szolgáltató tartozik-e egy adott ügyfélnek a fiókjában megjelenített egyenleggel. Amíg Ön nem tudja kiutalni a bitcoint és átvenni a kulcsok feletti rendelkezést, az egyenlege csupán a szolgáltató ígérete arra, hogy bitcoint bocsát a rendelkezésére, nem pedig olyan bitcoin, amelyet Ön közvetlenül ellenőrizhet és saját maga elkölthet.

Egy **nem letétkezelői** vagy **önálló kulcskezelésű** tárcában ÖN rendelkezik a kulcsokkal. A tárca az Ön felhatalmazása alapján írja alá a [tranzakciókat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Továbbra is fennállhatnak szoftveres, hardveres, szerver- vagy hálózati függőségek, de egyetlen [letétkezelőnek](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) sem kell jóváhagynia egy érvényes, blokkláncon végrehajtott költést.

![](https://cdn.sanity.io/images/vje9ehw2/staging/f93df0cc4a2ad82b3410a9ad4c3273d1b760f8ea-1774x887.svg)


<!-- micrographic: who-controls-keys-01 -->
[Letétkezelői használat esetén a szolgáltató kezeli a kulcsokat és hagyja jóvá a költést, így az egyenleg az ő ígérete. Saját kezelésű használat esetén a felhasználó kezeli a kulcsokat és a biztonsági mentéseket; mindkét megoldás függőségekkel és meghibásodási kockázatokkal jár.](/micrographics/who-controls-keys-01/hu.md)



<!-- micrographic: custody-comparison-table-01 -->
[A letétkezelői használatot és az önálló letétkezelést összehasonlító táblázat: ki birtokolja a kulcsokat, ki végzi a helyreállítást, és mi az egyes modellek fő kompromisszuma. Egyik modell sem kockázatmentes.](/micrographics/custody-comparison-table-01/hu.md)


[A letétkezelés](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) nem mindig egyértelmű a kezelőfelület alapján. Ha Ön nem rendelkezik a helyreállítás módja felett, és egy vállalat jóváhagyására van szüksége a kiutaláshoz, akkor valószínűleg igénybe vesz egy [letétkezelőt](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). [Az önálló kulcskezelés](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody) nem a személyes értékesség próbája; a fontos lépés annak felismerése, hogy miben kell megbíznia, és milyen kockázatokkal kell számolnia.

**Próbálja ki:** Olvasson el két előre elkészített tárcaleírást. Mindkettőnél nevezze meg, ki rendelkezik a kulcsokkal, ki tudná helyreállítani a hozzáférést, és említsen meg egy kockázatot, amelyet használat előtt ellenőriznie kell.
