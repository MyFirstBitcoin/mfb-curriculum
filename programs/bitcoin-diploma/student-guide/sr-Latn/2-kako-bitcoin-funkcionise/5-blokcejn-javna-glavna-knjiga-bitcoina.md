# 2.5 Blokčejn: javna glavna knjiga Bitcoina

<!-- card: definition -->
> **Definition – Blokčejn**
>
> Bitcoin [blokčejn](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) je javna [transakciona](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) evidencija čije se kopije čuvaju na mnogim nezavisnim računarima. Blok grupiše skup važećih [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) u sledeći predloženi deo te evidencije. Svaki važeći blok povezan je sa prethodnim, čime mreža dobija uređenu zajedničku istoriju koju može da proveri.



<!-- card: light -->
> **Kako čvorovi postižu konsenzus**
>
> [Čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) nezavisno proveravaju ista pravila i usaglašavaju se oko važeće istorije sa najviše akumuliranog [dokaza rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Promena ranijeg zapisa menja njegov blok i prekida veze sa kasnijim blokovima, pa konkurentska istorija mora ponovo da obavi taj rad i sustigne postojeću istoriju pre nego što je [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) prihvate. Ovaj skupi proces utvrđivanja redosleda pomaže mreži da postigne [konsenzus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) bez centralnog subjekta koji vodi evidenciju. Kopije se ne menjaju istovremeno; [čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) nezavisno primaju i proveravaju podatke. Bitcoin ima za cilj da se u proseku formira jedan novi blok otprilike svakih deset minuta. Prepravljanje istorije je teško i skupo, ali nije doslovno nemoguće: mogu se pojaviti privremene konkurentske istorije i reorganizacije.
