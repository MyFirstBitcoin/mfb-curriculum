# 2.5 Veriga blokov: Bitcoinova javna glavna knjiga

<!-- card: definition -->
> **Definition – Veriga blokov**
>
> Bitcoinova [veriga blokov](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) je javni [transakcijski](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) zapis, ki je podvojen na številnih neodvisnih računalnikih. Blok združi nabor veljavnih [transakcij](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) v naslednji predlagani del tega zapisa. Vsak veljaven blok je povezan s prejšnjim, kar omrežju zagotavlja urejeno skupno zgodovino, ki jo lahko preverja.



<!-- card: light -->
> **Kako vozlišča dosežejo soglasje**
>
> [Vozlišča](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) neodvisno preverjajo ista pravila in se uskladijo glede veljavne zgodovine z največ zbranimi [dokazi o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Sprememba prejšnjega zapisa spremeni njegov blok in prekine povezave s poznejšimi bloki, zato mora konkurenčna zgodovina ponoviti to delo in nadoknaditi zaostanek, preden jo [vozlišča](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) sprejmejo. Ta drag postopek urejanja pomaga omrežju doseči [soglasje](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) brez osrednjega skrbnika evidence. Kopije se ne spreminjajo sočasno; [vozlišča](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) neodvisno prejemajo in preverjajo podatke. Bitcoin si prizadeva za en nov blok v povprečju približno vsakih deset minut. Zgodovino je težko in drago prepisati, ni pa je dobesedno nemogoče spremeniti: pojavijo se lahko začasne konkurenčne zgodovine in reorganizacije.
