# 2.5 Blockchainen: Bitcoins offentlige hovedbog

<!-- card: definition -->
> **Definition – Blockchain**
>
> Bitcoins [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) er et offentligt [transaktionsbaseret](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) register, der er kopieret på tværs af mange uafhængige computere. En blok samler et sæt gyldige [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i den næste foreslåede del af dette register. Hver gyldig blok er knyttet til den foregående, hvilket giver netværket en fælles historik i fast rækkefølge, som det kan verificere.



<!-- card: light -->
> **Sådan opnår knudepunkter konsensus**
>
> [Knudepunkter](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerer uafhængigt af hinanden de samme regler og samler sig om den gyldige historik med mest akkumuleret [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). En ændring af en tidligere registrering ændrer dens blok og bryder forbindelserne til senere blokke, så en konkurrerende historik skal gentage dette arbejde og indhente den eksisterende historik, før [knudepunkter](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) accepterer den. Denne omkostningskrævende proces med at fastlægge rækkefølgen hjælper netværket med at opnå [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) uden en central registerfører. Kopierne ændres ikke samtidig; [knudepunkter](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) modtager og validerer data uafhængigt af hinanden. Bitcoin sigter mod én ny blok cirka hvert tiende minut i gennemsnit. Historikken er vanskelig og omkostningskrævende at omskrive, men det er ikke bogstaveligt talt umuligt at ændre den: Midlertidige konkurrerende historikker og reorganiseringer kan forekomme.
