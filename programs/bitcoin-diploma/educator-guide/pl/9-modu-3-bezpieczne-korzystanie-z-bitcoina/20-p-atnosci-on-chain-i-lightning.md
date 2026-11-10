# 9.20 Płatności on-chain i Lightning

Proszę zastosować porównanie, które oddziela ścieżkę płatności od [sposobu przechowywania środków](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody).


| Pytanie | On-chain | Lightning |
| --- | --- | --- |
| Gdzie zapisywane jest rozliczenie? | Bezpośrednio w łańcuchu bloków Bitcoina | Aktualizacje płatności odbywają się w sieci zbudowanej na Bitcoinie; kanały ostatecznie opierają się na Bitcoinie |
| Typowe dane do odbioru płatności dla początkujących | Adres on-chain | Faktura, obsługiwany adres Lightning lub inny zatwierdzony typ żądania płatności |
| Typowe zastosowanie | Rozliczenia w warstwie bazowej, często większe lub rzadsze przelewy | Często małe lub częste płatności, jeśli pozwalają na nie lokalne narzędzia i dostępna płynność |
| Czas realizacji | Pierwsze potwierdzenie zależy od uwzględnienia transakcji w bloku | Często szybko, ale płatności mogą się nie powieść |
| Opłaty i przepustowość | Zależą od danych transakcji i popytu na miejsce w blokach | Zależą od portfela, trasy, płynności, usługi i warunków płatności |
| Przechowywanie środków | Środki mogą być przechowywane przez powiernika lub samodzielnie | Środki mogą być przechowywane przez powiernika lub samodzielnie |
| Najważniejsze elementy do sprawdzenia przez początkujących | Prawidłowy adres, sieć, kwota, opłata i potwierdzenie | Prawidłowa faktura lub miejsce docelowe, kwota, termin ważności, opłata i wynik płatności |


Lightning nie jest odrębną monetą. Udana płatność Lightning nie dowodzi, że portfel jest bezpieczny do przechowywania większej kwoty. Obsługa kanałów, infrastruktura routingu oraz [płynność](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) i zarządzanie nią to [zagadnienia zaawansowane](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) wykraczające poza program Bitcoin Diploma.


<!-- micrographic: on-chain-and-lightning-01 -->
