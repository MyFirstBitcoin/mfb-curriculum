# 2.5 Blockchain: publiczna księga rachunkowa Bitcoina

<!-- card: definition -->
> **Definition – Łańcuch bloków**
>
> W sieci Bitcoin [łańcuch bloków](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) jest publicznym [transakcyjnym](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) rejestrem powielanym na wielu niezależnych komputerach. Blok grupuje zestaw prawidłowych [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) w kolejną proponowaną część tego rejestru. Każdy prawidłowy blok łączy się z poprzednim, zapewniając sieci uporządkowaną, wspólną historię do weryfikacji.



<!-- card: light -->
> **Jak węzły osiągają konsensus**
>
> [Węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) niezależnie sprawdzają te same reguły i dochodzą do zgodności co do prawidłowej historii z największą ilością zgromadzonego [dowodu pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Zmiana wcześniejszego wpisu zmienia jego blok i zrywa powiązania z późniejszymi blokami, więc konkurencyjna historia wymaga ponownego wykonania tej pracy i nadrobienia zaległości, zanim [węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ją zaakceptują. Ten kosztowny proces porządkowania pomaga sieci osiągnąć [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) bez centralnego podmiotu prowadzącego rejestr. Kopie nie zmieniają się jednocześnie; [węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) odbierają i weryfikują dane niezależnie. Docelowo w sieci Bitcoin nowy blok powstaje średnio co około dziesięć minut. Przepisanie historii jest trudne i kosztowne, ale jej zmiana nie jest dosłownie niemożliwa: mogą występować tymczasowe konkurencyjne historie i reorganizacje.
