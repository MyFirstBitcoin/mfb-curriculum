# 2.9 Użytkownicy, węzły i górnicy

Bitcoin działa, ponieważ różni uczestnicy pełnią różne role.

* **Użytkownicy** otrzymują, przechowują i wysyłają bitcoiny. Użytkownik może samodzielnie kontrolować swoje klucze przechowywane w portfelu lub korzystać z usług [powiernika](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Użytkownicy nadają sieci znaczenie gospodarcze, decydując, czy akceptować bitcoiny oraz którym zasadom i usługom ufać.
* [**Węzły**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) uruchamiają oprogramowanie Bitcoin i niezależnie weryfikują przestrzeganie zasad. [Pełny węzeł](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) sprawdza, czy [transakcje](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mają prawidłowe podpisy, czy bitcoiny nie zostały już wydane, czy bloki spełniają wymogi [dowodu pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) oraz czy nowe bitcoiny są emitowane zgodnie z [harmonogramem emisji](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) udostępniają prawidłowe dane innym węzłom i odrzucają nieprawidłowe dane.
* [**Górnicy**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) zbierają oczekujące [transakcje](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), budują [bloki kandydujące](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) i rywalizują poprzez [dowód pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Zwycięski [górnik](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [rozgłasza](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok i może otrzymać dozwolone [subsydium blokowe](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) oraz [opłaty transakcyjne](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Górnicy](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pomagają ustalać kolejność [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i sprawiają, że [rejestr](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) można przepisać jedynie dużym kosztem.
* **Programiści** przeglądają, opracowują i proponują zmiany w oprogramowaniu. Nie są właścicielami zasad Bitcoina. Zmiana w oprogramowaniu ma znaczenie tylko wtedy, gdy uczestnicy zdecydują się uruchomić oprogramowanie przestrzegające tych zasad.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Cztery role w sieci Bitcoin: użytkownicy odbierają, przechowują i wysyłają bitcoin, węzły niezależnie sprawdzają zgodność z regułami, górnicy tworzą bloki kandydujące z dowodem pracy, a programiści proponują oprogramowanie. Żadna pojedyncza rola nie kontroluje sieci.](/micrographics/bitcoin-participant-roles-01/pl.md)


Te role wzajemnie się ograniczają:

* użytkownik nie może wydać bitcoinów bez wymaganego prawidłowego podpisu
* każdy [górnik](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) może zaproponować blok, ale to [węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) decydują, czy jest on zgodny z zasadami
* dany [węzeł](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) weryfikuje według własnych reguł, ale [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) wymaga zgodnych reguł w całej sieci
* programiści mogą proponować oprogramowanie, ale to uczestnicy decydują, czy je uruchomić

Niektóre osoby pełnią kilka ról. [Górnik](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) może prowadzić [węzeł](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) i jednocześnie być użytkownikiem. Osoba początkująca nie musi pełnić każdej z tych ról, aby wyjaśnić, jak role te wzajemnie się równoważą.

**Pytanie kontrolne:** Dlaczego [węzeł](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) weryfikuje [transakcje](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Proszę podać przynajmniej jedną regułę, którą [węzeł](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) sprawdza.

![Osoba prowadząca zajęcia udziela wskazówek osobie uczącej się zagadnień technicznych przy komputerze pełniącym funkcję węzła. Ekran monitora jest zwrócony w ich stronę, a jego tylna obudowa jest widoczna dla oglądającego.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
