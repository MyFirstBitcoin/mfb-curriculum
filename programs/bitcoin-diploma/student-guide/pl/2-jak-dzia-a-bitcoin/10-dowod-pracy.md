# 2.10 Dowód pracy

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Dowód pracy**
>
> [Dowód pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) to proces, który [górnicy](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) wykorzystują do rywalizacji o prawo do zaproponowania następnego bloku.


Każda [funkcja skrótu](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) przekształca dane w wynik o stałej długości. Niewielka zmiana danych wejściowych daje nowy, nieprzewidywalny wynik. [Górnik](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) zmienia niewielki fragment danych w proponowanym bloku i wielokrotnie oblicza jego skrót. Wynik jest prawidłowy tylko wtedy, gdy jego wartość liczbowa jest niższa od ustalonej w sieci [wartości docelowej](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), czyli progu określonego przez reguły; niższa [wartość docelowa](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) oznacza mniej [prawidłowych wyników](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) i więcej prób. Nie ma drogi na skróty, więc [górnicy](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mogą potrzebować wielu prób.

Gdy [górnik](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) znajdzie [prawidłowy wynik](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), wówczas [rozgłasza](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok. [Węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) mogą szybko sprawdzić dowód, mimo że jego znalezienie wymagało znacznych obliczeń i nakładów energii. Jeśli blok zawiera [transakcję](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), ta [transakcja](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) otrzymuje swoje [pierwsze potwierdzenie](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): jej zapis został uwzględniony w jednym prawidłowym bloku. Każdy prawidłowy blok dodany po nim stanowi kolejne [potwierdzenie](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), co sprawia, że [transakcja](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ma w [łańcuchu bloków](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) miejsce, którego zmiana jest bardziej kosztowna. Ta różnica jest istotna: wykonanie pracy jest kosztowne, a jej weryfikacja — łatwa.


<!-- micrographic: proof-of-work-process-01 -->


[Dowód pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) służy kilku celom:

* daje niezależnym [górnikom](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) możliwość rywalizacji bez centralnego koordynatora
* sprawia, że zmiana kolejności [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) jest kosztowna
* wiąże bezpieczeństwo sieci z fizycznym sprzętem i energią
* zapewnia publiczną metodę wyboru między konkurującymi prawidłowymi historiami: wybierany jest łańcuch z największą ilością [skumulowanej pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Wydobywanie](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) nie służy rozwiązywaniu równań przydatnych do celów zewnętrznych. Jego celem jest zabezpieczenie ustalanej w sieci Bitcoin kolejności [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Sieć okresowo dostosowuje wartość docelową: gdy bloki pojawiają się zbyt szybko, obniża ją, a gdy pojawiają się zbyt wolno, podwyższa ją, dążąc do utrzymania średniego tempa około jednego bloku na dziesięć minut mimo zmian mocy obliczeniowej.

[Dowód pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) wiąże się z rzeczywistym kosztem energetycznym. Zwolennicy twierdzą, że to właśnie ten koszt stanowi podstawę bezpieczeństwa sieci Bitcoin i może tworzyć popyt na energię, której pobór można elastycznie dostosowywać, lub energię, która w przeciwnym razie pozostałaby niewykorzystana. Krytycy kwestionują ilość i źródła zużywanej energii. Rzetelna ocena wymaga postawienia pytań o to, jaka energia jest wykorzystywana, skąd pochodzi, jakie bezpieczeństwo zapewnia i jakie alternatywy są porównywane.

![Nauczyciel, początkujący uczeń i uczeń o wiedzy technicznej omawiają stołową koparkę z wentylatorem i oddzielnym zasilaczem.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
