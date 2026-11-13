# 3.14 Płatności on-chain i Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->
[Płatności on-chain są zapisywane bezpośrednio w łańcuchu bloków Bitcoina, natomiast Lightning to sieć płatnicza zbudowana na Bitcoinie, umożliwiająca szybkie i częste płatności, które mogą się również nie powieść. Oba rozwiązania mogą działać z udziałem powiernika lub z samodzielnym zarządzaniem środkami.](/micrographics/on-chain-and-lightning-01/pl.md)



<!-- card: definition -->
> **Definition – Płatności on-chain i Lightning**
>
> [Płatności on-chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) są zapisywane w sieci Bitcoin w jej [łańcuchu bloków](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) i uzyskują [potwierdzenia](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning to sieć płatnicza zbudowana na bazie sieci Bitcoin, która umożliwia szybkie, częste płatności. Płatność Lightning może zostać szybko zrealizowana lub zakończyć się niepowodzeniem, a obsługujący ją portfel może być zarówno powierniczy, jak i niepowierniczy.



<!-- card: dark -->
> **Sposób płatności nie określa, kto sprawuje kontrolę nad środkami**
>
> Płatności on-chain i Lightning wiążą się z różnymi [kompromisami](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Portfel Lightning może być powierniczy lub niepowierniczy, a szybka i udana płatność nie dowodzi, że dana usługa nadaje się do przechowywania większych kwot lub sprawdzi się w każdej sytuacji.



<!-- micrographic: onchain-lightning-table-01 -->
[Tabela porównująca Bitcoin on-chain i Lightning: dane do odbioru płatności, wynik płatności, typowe zastosowanie i kwestie do sprawdzenia na początek. W obu przypadkach środki mogą być przechowywane przez pośrednika lub samodzielnie.](/micrographics/onchain-lightning-table-01/pl.md)


Jakiego sposobu płatności oczekuje odbiorca? Przed dokonaniem płatności proszę sprawdzić, czy podał adres on-chain, czy [fakturę Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) lub żądanie płatności. Portfel on-chain nie może bezpośrednio opłacić każdej [faktury Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), a portfel Lightning może nie obsługiwać wszystkich operacji on-chain. Niektóre aplikacje obsługują oba sposoby płatności, ale mogą naliczać dodatkowe opłaty lub wymagać korzystania z dodatkowych usług. Szczegółowa konfiguracja Lightning, kanały, routing i [płynność](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) to tematy z zakresu [Nauki zaawansowanej](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); ćwiczenia praktyczne na żywo w lokalnych warunkach są częścią **Modułu 4**, o ile są bezpieczne i odpowiednie.

Proszę sobie wyobrazić, że przygotowany scenariusz oferuje oba sposoby płatności. Które żądanie płatności może obsłużyć wybrany portfel i co sprawdziliby Państwo przed jego zatwierdzeniem? Odpowiedź zależy od żądania płatności wystawionego przez odbiorcę, portfela i sytuacji — nie od uniwersalnego „najlepszego” sposobu płatności.

![Osoba prowadząca zajęcia wskazuje na tablicy dwie różne geometryczne ścieżki płatności, a osoby początkujące i osoby o przygotowaniu technicznym je analizują.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
