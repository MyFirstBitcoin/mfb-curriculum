# 2.5 Lanac blokova: Bitcoinova javna glavna knjiga

<!-- card: definition -->
> **Definition – Lanac blokova**
>
> Bitcoinov [lanac blokova](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) javni je [transakcijski](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) zapis koji se replicira na mnogim neovisnim računalima. Blok grupira skup valjanih [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) u sljedeći predloženi dio tog zapisa. Svaki valjani blok povezuje se s prethodnim, čime mreža dobiva uređenu zajedničku povijest koju može provjeriti.



<!-- card: light -->
> **Kako čvorovi postižu konsenzus**
>
> [Čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) neovisno provjeravaju ista pravila i usuglašavaju se oko valjane povijesti s najviše akumuliranog [dokaza rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Promjena ranijeg zapisa mijenja njegov blok i prekida veze s kasnijim blokovima, pa konkurentska povijest mora ponoviti taj rad i sustići postojeću prije nego što je [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) prihvate. Taj skup postupak uspostavljanja redoslijeda pomaže mreži da postigne [konsenzus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) bez središnjeg voditelja evidencije. Kopije se ne mijenjaju istodobno; [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) neovisno primaju i provjeravaju podatke. Bitcoin cilja na jedan novi blok otprilike svakih deset minuta u prosjeku. Povijest je teško i skupo prepisati, ali nije je doslovno nemoguće promijeniti: mogu se pojaviti privremene konkurentske povijesti i reorganizacije.
