# 8.10 Użytkownicy, węzły, górnicy, programiści i usługi

Proszę stosować dokładnie te rozgraniczenia ról dla początkujących:


| Rola | Główna funkcja w ujęciu dla początkujących | Nie oznacza to, że |
| --- | --- | --- |
| Użytkownik | Decyduje się odbierać, przechowywać, wysyłać, weryfikować i akceptować bitcoiny, bezpośrednio lub za pośrednictwem usług | Automatycznie obsługuje każdą część sieci |
| Węzeł | Niezależnie sprawdza transakcje i bloki pod kątem zgodności ze swoimi zasadami i przekazuje dalej poprawne dane | Tworzy nowe bloki lub narzuca wszystkim zasady |
| Górnik | Buduje bloki kandydujące i wykonuje dowód pracy, aby zaproponować ich kolejność | Może sprawić, że nieprawidłowa emisja lub nieprawidłowe transakcje zostaną uznane za poprawne przez uczciwe węzły |
| Programista | Przegląda, pisze i proponuje oprogramowanie | Może zmusić uczestników do przyjęcia zmiany zasad |
| Usługa związana z Bitcoinem | Udostępnia portfel, giełdę, eksplorator, interfejs płatności lub inny interfejs | Jest samym protokołem Bitcoin |



<!-- micrographic: bitcoin-participant-roles-01 -->


#### Ćwiczenie: nieprawidłowy blok

Proszę przekazać jednemu uczestnikowi odgrywającemu rolę [górnika](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pewien [blok kandydujący](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) tworzący większe subsydium, niż dopuszcza karta zasad [węzła](https://curriculum.myfirstbitcoin.org/lexicon/en/#node). Uczestnicy odgrywający role [węzłów](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) sprawdzają go i odrzucają.

Omówienie:

* Ten [górnik](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) wykonał rzeczywistą pracę, ale mimo to nie uzyskał prawa do łamania zasad.
* [Węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) niezależnie stosują zasady, ale rzeczywista sieć opiera się na oprogramowaniu i komunikacji, a nie na głosowaniu w klasie.
* Programista może napisać inne zasady, ale ich przyjęcie jest dobrowolne, a niezgodne ze sobą zasady mogą doprowadzić do powstania odrębnej sieci.

Proszę zapytać:

> Dlaczego [węzeł](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) weryfikuje transakcje? Proszę wymienić przynajmniej jedną zasadę, której przestrzeganie sprawdza.
