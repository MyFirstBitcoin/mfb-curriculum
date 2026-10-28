# 3.14 Betalningar på kedjan och via Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->
[Betalningar på kedjan registreras direkt i Bitcoins blockkedja, medan Lightning är ett betalningsnätverk byggt på Bitcoin för snabba, frekventa betalningar som också kan misslyckas. Båda alternativen kan användas med antingen tredjepartsförvaring eller egen förvaring.](/micrographics/on-chain-and-lightning-01/sv.md)



<!-- card: definition -->
> **Definition – Betalningar på kedjan och via Lightning**
>
> [Betalningar på kedjan](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) registreras i Bitcoins [blockkedja](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) och får [bekräftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning är ett betalningsnätverk byggt ovanpå Bitcoin som kan stödja snabba, frekventa betalningar. En Lightning-betalning kan genomföras snabbt eller misslyckas, och plånboken som används kan fortfarande vara förvaltad av en tredje part eller självförvaltad.



<!-- card: dark -->
> **Betalningsvägen avgör inte vem som har förvaringsansvaret**
>
> Betalningar på kedjan och via Lightning innebär olika [avvägningar](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). En Lightning-plånbok kan vara förvaltad av en tredje part eller självförvaltad, och en snabb, lyckad betalning bevisar inte att en tjänst är lämplig för större saldon eller alla situationer.



<!-- micrographic: onchain-lightning-table-01 -->
[En tabell som jämför Bitcoin på kedjan och Lightning: mottagningsuppgifter, betalningsresultat, vanlig användning och kontroller för nybörjare. Båda alternativen kan användas med tredjepartsförvaring eller egen förvaring.](/micrographics/onchain-lightning-table-01/sv.md)


Vilken betalningsväg förväntar sig mottagaren? Kontrollera om mottagaren har angett en adress för betalning på kedjan eller en [Lightning-faktura](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) eller betalningsbegäran innan ni betalar. En plånbok för betalningar på kedjan kan inte direkt betala alla [Lightning-fakturor](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), och en Lightning-plånbok stöder kanske inte alla åtgärder på kedjan. Vissa appar stöder båda betalningsvägarna men kan medföra extra avgifter eller beroenden av tjänster. Detaljerad konfigurering av Lightning, kanaler, dirigering och [likviditet](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) ingår i [Fördjupning](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); praktiska övningar på plats hör hemma i **Modul 4** när det är säkert och lämpligt.

Föreställ er att ett förberett scenario erbjuder båda betalningsvägarna. Vilken betalningsbegäran kan den avsedda plånboken använda, och vad skulle ni kontrollera innan ni godkänner den? Svaret beror på mottagarens betalningsbegäran, plånboken och situationen – inte på en universellt ”bästa” betalningsväg.

![Läraren pekar på två olika geometriska betalningsvägar på en tavla medan nybörjaren och de tekniskt kunniga deltagarna funderar över dem.](https://cdn.sanity.io/images/vje9ehw2/production/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
