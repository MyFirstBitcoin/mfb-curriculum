# 2.5 Blockchain: publiczna księga rachunkowa Bitcoina

> **Definition – Łańcuch bloków**
>
> Bitcoinowy [łańcuch bloków](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) to publiczny [transakcyjny](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) rejestr powielany na wielu niezależnych komputerach. Blok grupuje zbiór prawidłowych [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) w kolejną proponowaną część tego rejestru. Każdy prawidłowy blok jest powiązany z poprzednim, dzięki czemu sieć ma wspólną, uporządkowaną historię, którą może weryfikować.



> **Definition – Węzeł**
>
> [Węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) niezależnie sprawdzają przestrzeganie tych samych reguł i uzgadniają prawidłową historię o największej skumulowanej wartości [dowodu pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Zmiana wcześniejszego zapisu zmienia jego blok i zrywa powiązania z późniejszymi blokami, więc konkurencyjna historia musi ponownie wykonać tę pracę i nadrobić zaległości, zanim [węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ją zaakceptują. Ten kosztowny proces porządkowania pomaga sieci osiągnąć [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) bez centralnego podmiotu prowadzącego rejestr. Kopie nie zmieniają się jednocześnie; [węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) niezależnie odbierają i weryfikują dane. Docelowo w sieci Bitcoin nowy blok powstaje średnio co około dziesięć minut. Zmiana zapisanej historii jest trudna i kosztowna, ale nie jest dosłownie niemożliwa: mogą występować tymczasowe konkurencyjne historie i reorganizacje.
