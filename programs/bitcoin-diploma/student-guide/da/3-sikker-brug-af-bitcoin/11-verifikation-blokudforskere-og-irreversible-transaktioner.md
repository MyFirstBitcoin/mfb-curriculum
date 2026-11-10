# 3.11 Verifikation, blokudforskere og irreversible transaktioner

> **Definition – Transaktions-id og blokudforsker**
>
> Et [transaktions-id](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identificerer en on-chain [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). En [blokudforsker](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) viser offentlige Bitcoin-data, såsom en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)s status og [bekræftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) i alt. Den giver et nyttigt indblik, men er ikke en autoritet over Bitcoin og heller ikke et bevis på modtagerens identitet eller ærlighed.


Hvad kan disse offentlige oplysninger vise, og hvad kan de ikke vise? De kan vise en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)s status, destination, beløb, gebyr og [bekræftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) i alt; de kan ikke bevise, hvorfor en betaling fandt sted, eller om en person er troværdig. En on-chain [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) er ubekræftet, efter at den er [udsendt](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) og får sin [første bekræftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation), når den medtages i en gyldig blok. Senere blokke øger sikkerheden for dens plads i registreringen, men de retter ikke en forkert destination eller svindel. Der findes ikke et universelt krav til [bekræftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) i alt for enhver betaling; den passende kontrol afhænger af beløbet og risikoen.

For at undersøge en på forhånd klargjort [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) skal De skaffe dens [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), åbne en pålidelig blokudforsker til det ønskede [Bitcoin-netværk](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) og kontrollere status, destination, beløb, gebyr og [bekræftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). En blokudforsker er kun en grænseflade. En søgning på en adresse eller et [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) kan afsløre over for operatøren, at Deres enhed er interesseret i disse oplysninger. Til øvelser skal De bruge en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), som en underviser har klargjort, eller et udskrevet skærmbillede. Søg ikke efter en elevs personlige adresse eller [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) på en offentlig tjeneste. Hvis De senere undersøger en personlig betaling, skal De sætte Dem ind i de [privatlivsmæssige](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) og sikkerhedsmæssige [afvejninger](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) ved Deres forbindelse, før De bruger en offentlig tjeneste.


> **Callout – Offentlige data er ikke bevis på identitet eller ærlighed**
>
> En [blokudforsker](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) kan vise offentlige [transaktionsrelaterede](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) data, men den kan ikke bevise, hvem der kontrollerer en adresse, hvorfor en betaling fandt sted, eller om en modtager er troværdig. Brug forberedte eksempler til øvelser, og beskyt [privatlivet](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) ved søgning på offentlige tjenester.



<!-- micrographic: confirmation-timeline-01 -->


![Underviseren og den ældre kursist diskuterer et forberedt eksempel på en skærm, der vender mod gruppen, mens den teknisk kyndige kursist betjener musen; beskueren ser skærmens bagside.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
