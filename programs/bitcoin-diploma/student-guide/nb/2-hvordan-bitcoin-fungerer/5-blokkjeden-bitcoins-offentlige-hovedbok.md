# 2.5 Blokkjeden: Bitcoins offentlige hovedbok

<!-- card: definition -->
> **Definition – Blokkjede**
>
> Bitcoins [blokkjede](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) er en offentlig [transaksjonslogg](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) som kopieres til mange uavhengige datamaskiner. En blokk samler et sett med gyldige [transaksjoner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i den neste foreslåtte delen av denne loggen. Hver gyldige blokk er koblet til den forrige, noe som gir nettverket en felles, ordnet historikk som kan verifiseres.



<!-- card: light -->
> **Hvordan noder oppnår konsensus**
>
> [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerer de samme reglene uavhengig av hverandre og samler seg om den gyldige historikken med mest akkumulert [arbeidsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Å endre en tidligere oppføring endrer blokken den inngår i, og bryter koblingene til senere blokker. En konkurrerende historikk må derfor gjøre dette arbeidet på nytt og ta igjen forspranget før [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) godtar den. Denne kostbare prosessen med å ordne historikken hjelper nettverket med å oppnå [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) uten en sentral loggfører. Kopiene endres ikke samtidig; [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) mottar og validerer data uavhengig av hverandre. Bitcoin sikter mot én ny blokk omtrent hvert tiende minutt i gjennomsnitt. Historikken er vanskelig og kostbar å skrive om, men ikke bokstavelig talt umulig å endre: midlertidige konkurrerende historikker og omorganiseringer kan forekomme.
