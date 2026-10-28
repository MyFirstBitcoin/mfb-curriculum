# 2.5 Blockchainul: registrul public al Bitcoin

<!-- card: definition -->
> **Definition – Blockchain**
>
> În Bitcoin, [Blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) este un registru public de [tranzacții](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) replicat pe numeroase calculatoare independente. Un bloc grupează un set de [tranzacții valide](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) în următoarea parte propusă a acelui registru. Fiecare bloc valid este legat de cel precedent, oferind rețelei un istoric comun, ordonat, pe care îl poate verifica.



<!-- card: light -->
> **Cum ajung nodurile la consens**
>
> [Nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifică independent aceleași reguli și converg către istoricul valid cu cea mai mare cantitate acumulată de [Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Modificarea unei înregistrări anterioare îi modifică blocul și rupe legăturile cu blocurile ulterioare, astfel încât un istoric concurent trebuie să refacă acea muncă și să recupereze decalajul înainte ca [nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) să îl accepte. Acest proces costisitor de ordonare ajută rețeaua să ajungă la [consens](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) fără un administrator central al registrului. Copiile nu se modifică simultan; [nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) primesc și validează datele independent. Bitcoin urmărește generarea unui bloc nou aproximativ la fiecare zece minute, în medie. Rescrierea istoricului este dificilă și costisitoare, dar modificarea lui nu este literalmente imposibilă: pot apărea temporar istorice concurente și reorganizări.
