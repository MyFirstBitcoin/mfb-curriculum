# 2.5 Blockchainul: registrul public al Bitcoin

> **Definition – Blockchain**
>
> În Bitcoin, [Blockchain-ul](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) este un registru public de [tranzacții](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) replicat pe numeroase calculatoare independente. Un bloc grupează un set de [tranzacții](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) valide în următoarea parte propusă a acelui registru. Fiecare bloc valid este legat de cel precedent, oferind rețelei un istoric comun, ordonat, pe care îl poate verifica.



> **Definition – Nod**
>
> [Nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifică independent aceleași reguli și converg către istoricul valid cu cel mai mare volum acumulat de [Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Modificarea unei înregistrări anterioare îi modifică blocul și rupe legăturile cu blocurile ulterioare, astfel încât un istoric concurent trebuie să refacă acea muncă și să recupereze decalajul înainte ca [nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) să îl accepte. Acest proces costisitor de ordonare ajută rețeaua să ajungă la [consens](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) fără un administrator central al registrului. Copiile nu se modifică simultan; [nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) primesc și validează datele independent. Bitcoin urmărește adăugarea unui bloc nou aproximativ la fiecare zece minute, în medie. Istoricul este dificil și costisitor de rescris, nu literalmente imposibil de modificat: pot apărea temporar istorice concurente și reorganizări.
