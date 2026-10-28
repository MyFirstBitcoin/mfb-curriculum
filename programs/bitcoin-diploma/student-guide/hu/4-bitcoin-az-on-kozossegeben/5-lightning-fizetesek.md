# 4.5 Lightning-fizetések

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[A fogadó fél létrehoz a telefonján egy Lightning-fizetési kérelmet a megadott összeggel, a küldő fél beolvassa és kifizeti azt, a fizetés pedig egy pillanattal később megérkezik a fogadó fél telefonjára.](/micrographics/lightning-phone-payment-01/hu.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[Lightning-fizetés hat lépésben: a fogadó fél kérelmet hoz létre, a küldő fél beolvassa azt, ellenőrzi a címzettet, az összeget, az egységet, a lejáratot és a díjat, majd jóváhagyja a fizetést; a fizetés továbbítódik, és mindkét tárca megjeleníti az eredményt. Mindkét tárca lehet letétkezelői vagy saját kezelésű, sikertelen vagy lejárt fizetés esetén pedig a folyamat új kérelemmel kezdődik elölről.](/micrographics/lightning-payment-sequence-01/hu.md)


A Lightning praktikussá teheti a gyors, kis összegű Bitcoin-fizetéseket. Alkalmas lehet üzleti pénztáraknál, rendszeres helyi fizetéseknél, online szolgáltatásoknál vagy olyan átutalásoknál, ahol a blokkláncon végrehajtott tranzakció díja túl nagy lenne a fizetett összeghez képest.

Egy helyi Lightning-bemutatón tisztázni kell:

* hogy a tárca letétkezelői vagy saját kezelésű
* hogyan töltik fel a tárcát
* hogy a feltöltéshez szükséges-e blokkláncon végrehajtott [tranzakció](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) vagy valamilyen szolgáltatás
* milyen biztonsági mentés vagy helyreállítási lehetőség védi az egyenleget
* milyen típusú fizetési kérelmet használnak
* milyen díjak vagy korlátok érvényesek
* mi történik, ha egy fizetés sikertelen
* hogyan ellenőrzi a fogadó fél a fizetés beérkezését

A [**Lightning-számla**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) egy adott fizetéshez létrehozott fizetési kérelem. Tartalmazhat összeget, a célra vonatkozó adatokat és lejárati időt. Fizetés előtt olvassa el a tárca [megerősítő](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) képernyőjét.

A [**Lightning-cím**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) egy ember által olvasható azonosító, amelyet egyes szolgáltatások támogatnak. Hasonlíthat egy e-mail-címre, de nem e-mail-fiók, hanem a fizetés célba juttatását megkönnyítő megoldás. Az azt támogató szolgáltatótól vagy domaintől függ.

Egy irányított fizetési gyakorlat lépései:

1. A fogadó fél létrehozza a megfelelő kérelmet.
1. A küldő beolvassa vagy kimásolja azt.
1. A küldő ellenőrzi a címzettet, az összeget, az egységet és a díjat.
1. A küldő csak akkor hagyja jóvá a fizetést, ha az adatok helyesek.
1. Mindkét fél ellenőrzi az eredményt a saját tárcájában.
1. A csoport ismerteti a [letétkezelés](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) és a sikertelen fizetések kockázatait.

Ne feltételezze, hogy egy sikeres Lightning-fizetés bizonyítja, hogy a tárcában nagyobb összegeket is biztonságosan lehet tartani. A fizetés kényelme és a [letétkezelés](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) biztonsága külön kérdés.
