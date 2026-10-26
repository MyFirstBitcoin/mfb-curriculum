# 3.4 Klucze

Własność bitcoinów jest zabezpieczana za pomocą kluczy kryptograficznych.


> **Definition – Klucz prywatny**
>
> Taki [klucz prywatny](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) to tajna informacja, która umożliwia portfelowi tworzenie prawidłowych [podpisów cyfrowych](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Podpis autoryzuje wydanie bitcoinów kontrolowanych przez odpowiedni klucz. Każdy, kto uzyska [klucz prywatny](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key), może zazwyczaj wydać te środki.


Taki [**klucz publiczny**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) jest wyprowadzany matematycznie z [klucza prywatnego](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Pomaga zweryfikować podpis bez ujawniania [klucza prywatnego](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adresy tworzy się na podstawie [klucza publicznego](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) i zawartych w nim informacji.

Podstawowa zasada jest prosta:

**Publiczne informacje służące do otrzymywania środków można udostępniać. Prywatne informacje umożliwiające wydawanie środków muszą pozostać tajne.**

Taki [podpis cyfrowy](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) dowodzi, że wymagany [klucz prywatny](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) autoryzował [transakcję](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Nie umieszcza on [klucza prywatnego](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) wewnątrz [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) weryfikują podpis przed zaakceptowaniem wydania środków.

Większość portfeli dla początkujących wykorzystuje [pojedynczy podpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): jeden klucz prywatny autoryzuje transakcję. Nowoczesne portfele automatycznie zarządzają wieloma kluczami. Początkujący nie powinni kopiować ani obsługiwać pojedynczych [kluczy prywatnych](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) w postaci ciągów znaków. Proszę chronić kopię zapasową zalecaną przez portfel i postępować zgodnie z jego procedurą odzyskiwania.

Żaden rzetelny edukator, firma tworząca portfele, pracownik giełdy, pracownik pomocy technicznej ani deweloper Bitcoina nie potrzebuje Państwa [klucza prywatnego](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ani [frazy odzyskiwania](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Każdego, kto o nie prosi, należy traktować jako zagrożenie.


> **Light**
>
> **Ćwiczenie:** Proszę podzielić przygotowane przykłady na trzy grupy: informacje, które można bezpiecznie udostępniać w celu otrzymywania środków, tajne informacje umożliwiające wydawanie środków oraz informacje, które mogą być publiczne, ale powinny pozostać prywatne, gdy są powiązane z konkretną osobą.



<!-- micrographic: private-key-public-info-01 -->
