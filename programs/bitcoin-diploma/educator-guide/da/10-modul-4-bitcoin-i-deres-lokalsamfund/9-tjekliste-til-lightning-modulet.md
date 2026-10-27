# 10.9 Tjekliste til Lightning-modulet

Før en Lightning-workshop skal De kontrollere og forklare:

* om tegnebogen forvaltes af en tredjepart eller er selvforvaltet
* hvordan der indsættes midler i den
* om indbetaling eller udbetaling sker via en on-chain-transaktion eller en tjeneste
* gendannelse og fortsat brug, hvis udbyderen eller enheden svigter
* om anmodningen er en faktura, en understøttet [Lightning-adresse](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) eller en anden type
* beløb, enhed, modtager, udløbstidspunkt, gebyr, grænser og [likviditetsmæssige](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) hensyn
* hvordan det vises, at en betaling er gennemført, afventer, er udløbet eller er mislykkedes
* hvordan begge parter uafhængigt af hinanden bekræfter resultatet; og
* offline-simuleringen.


<!-- card: dark -->
> **Én vellykket Lightning-betaling beviser kun, at denne rute virkede én gang**
>
> Det beviser ikke, at tegnebogen er sikker til større saldi, eller at den samme rute vil fungere alle steder.



<!-- micrographic: lightning-payment-sequence-01 -->
[En Lightning-betaling i seks trin: Modtageren opretter en anmodning, afsenderen scanner den, kontrollerer modtager, beløb, enhed, udløbstidspunkt og gebyr og godkender betalingen, som sendes gennem netværket, og begge wallets viser resultatet. Hver wallet kan være tredjepartsforvaltet eller selvforvaltet, og ved en mislykket eller udløbet betaling begynder forløbet igen med en ny anmodning.](/micrographics/lightning-payment-sequence-01/da.md)
