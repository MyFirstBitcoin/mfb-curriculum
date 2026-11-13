# 3.6 Användning med och utan tredjepartsförvaring

<!-- card: definition -->
> **Definition – Förvaring**
>
> [Förvaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) besvarar en praktisk fråga: vem kontrollerar nycklarna som krävs för att spendera bitcoin?


I en **depåbaserad** tjänst kontrollerar ett företag eller en annan person nycklarna. Ert visade saldo är ett löfte från [förvararen](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Vanligtvis loggar ni in med ett konto och ber tjänsten att genomföra ett uttag eller en betalning.

Denna skillnad är viktig för verifiering. Bitcoins regler och totala utbud kan kontrolleras oberoende, men om ni inte kontrollerar nycklarna kan ni inte självständigt kontrollera att saldot som visas på ert konto motsvarar bitcoin som tjänsten innehar och kommer att göra tillgängliga för er. Den offentliga blockkedjan kan visa bitcoin som kontrolleras av nycklar; den kan inte visa att en tjänst är skyldig en viss kund det saldo som visas på ett konto. Innan ni kan göra ett uttag och kontrollera nycklarna är ert saldo tjänstens löfte om att tillhandahålla bitcoin, inte bitcoin som ni själva kan verifiera och spendera direkt.

I en **icke-depåbaserad** eller **självförvaltad** plånbok kontrollerar NI nycklarna. Plånboken signerar [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) på ert uppdrag. Det kan fortfarande finnas beroenden av programvara, hårdvara, servrar eller nätverk, men ingen [förvarare](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) behöver godkänna en giltig överföring på kedjan.

![](https://cdn.sanity.io/images/vje9ehw2/staging/f93df0cc4a2ad82b3410a9ad4c3273d1b760f8ea-1774x887.svg)


<!-- micrographic: who-controls-keys-01 -->
[Vid tredjepartsförvaring kontrollerar en tjänst nycklarna och godkänner betalningar, så saldot är dess löfte. Vid egenförvaring kontrollerar användaren nycklarna och säkerhetskopiorna; båda alternativen innebär beroenden och risker för att något går fel.](/micrographics/who-controls-keys-01/sv.md)



<!-- micrographic: custody-comparison-table-01 -->
[En tabell som jämför användning med extern och egen förvaring: vem som innehar nycklarna, vem som hanterar återställning och den huvudsakliga avvägningen för respektive modell. Ingen av modellerna är riskfri.](/micrographics/custody-comparison-table-01/sv.md)


[Förvaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) framgår inte alltid tydligt av gränssnittet. Om ni inte kan kontrollera återställningsmetoden och behöver ett företags godkännande för ett uttag använder ni förmodligen en [förvarare](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). [Egenförvaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody) är inte ett mått på ert värde som person; det viktiga steget är att identifiera vilken tillit och vilka risker som är inblandade.

**Prova själv:** Läs två förberedda plånboksbeskrivningar. Ange för var och en vem som kontrollerar nycklarna, vem som skulle kunna återställa åtkomsten och en risk att undersöka innan ni använder plånboken.
