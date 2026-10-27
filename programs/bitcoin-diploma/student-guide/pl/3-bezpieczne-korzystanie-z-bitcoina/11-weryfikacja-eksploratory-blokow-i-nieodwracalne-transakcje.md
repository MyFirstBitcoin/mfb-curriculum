# 3.11 Weryfikacja, eksploratory bloków i nieodwracalne transakcje

<!-- card: definition -->
> **Definition – Identyfikator transakcji i eksplorator bloków**
>
> Każdy [identyfikator transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identyfikuje zapisaną w łańcuchu bloków [transakcję](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Eksplorator bloków](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) pokazuje publiczne dane sieci Bitcoin, takie jak status [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i liczba [potwierdzeń](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Jest użytecznym narzędziem do przeglądania danych, ale nie ma władzy nad siecią Bitcoin ani nie stanowi dowodu tożsamości lub uczciwości odbiorcy.


Co mogą pokazać te publiczne informacje, a czego nie? Mogą pokazać status [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), adres docelowy, kwotę, opłatę i liczbę [potwierdzeń](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation); nie mogą udowodnić, dlaczego dokonano płatności ani czy dana osoba jest godna zaufania. Zapisywana w łańcuchu bloków [transakcja](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) pozostaje niepotwierdzona po jej [rozgłoszeniu](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) i otrzymuje [pierwsze potwierdzenie](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) po uwzględnieniu w prawidłowym bloku. Kolejne bloki zwiększają pewność co do jej miejsca w rejestrze, ale nie naprawiają błędnego adresu docelowego ani skutków oszustwa. Nie istnieje uniwersalna liczba [potwierdzeń](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) odpowiednia dla każdej płatności; właściwy sposób weryfikacji zależy od kwoty i ryzyka.

Aby sprawdzić przygotowaną [transakcję](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), należy uzyskać jej [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), otworzyć zaufany eksplorator dla właściwej [sieci Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) i sprawdzić status, adres docelowy, kwotę, opłatę oraz [potwierdzenia](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Eksplorator jest jedynie interfejsem. Wyszukiwanie adresu lub [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) może ujawnić jego operatorowi, że Państwa urządzenie jest zainteresowane tymi informacjami. Do ćwiczeń należy używać przygotowanej przez osobę prowadzącą zajęcia [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) lub wydrukowanego zrzutu ekranu. Nie należy wyszukiwać prywatnego adresu ani [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) osoby uczącej się w publicznym serwisie. Jeśli później będą Państwo sprawdzać własną płatność, przed skorzystaniem z publicznego serwisu należy poznać dotyczące [prywatności](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) i bezpieczeństwa [kompromisy](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) związane z używanym połączeniem.


<!-- card: callout -->
> **Publiczne dane nie są dowodem tożsamości ani uczciwości**
>
> Taki [eksplorator bloków](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) może wyświetlać publiczne [dane transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) — nie może jednak dowieść, kto kontroluje dany adres, dlaczego dokonano płatności ani czy odbiorca jest godny zaufania. Proszę korzystać z przygotowanych przykładów do ćwiczeń i chronić [prywatność](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) podczas wyszukiwania w publicznych serwisach.



<!-- micrographic: confirmation-timeline-01 -->
[Niepotwierdzona transakcja czeka w puli transakcji oczekujących, następnie zostaje uwzględniona w bloku N, co stanowi jej pierwsze potwierdzenie, a każdy kolejny blok dodaje jeszcze jedno.](/micrographics/confirmation-timeline-01/pl.md)


![Osoba prowadząca zajęcia i starsza osoba ucząca się omawiają przygotowany przykład na monitorze zwróconym w stronę grupy, podczas gdy osoba ucząca się mająca umiejętności techniczne obsługuje mysz; widz widzi tylną część obudowy.](https://cdn.sanity.io/images/vje9ehw2/staging/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
