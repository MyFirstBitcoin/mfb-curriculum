# 10.9 Checkliste für das Lightning-Modul

Prüfen und erläutern Sie vor einem Lightning-Workshop:

* ob die Wallet verwahrt (custodial) oder selbstverwahrt (self-custodial) ist
* wie sie aufgeladen wird
* ob für das Aufladen oder Abheben eine On-Chain-Transaktion oder ein Dienst genutzt wird
* Wiederherstellung und Kontinuität, falls der Anbieter oder das Gerät ausfällt
* ob es sich bei der Anforderung um eine Invoice, eine unterstützte [Lightning-Adresse](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) oder einen anderen Typ handelt
* Betrag, Einheit, Empfänger, Ablaufzeit, Gebühr, Limits und [Liquidität](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) als zu berücksichtigende Punkte
* wie Erfolg, ausstehender Status, Ablauf oder Fehlschlag aussehen
* wie beide Parteien das Ergebnis unabhängig voneinander bestätigen; und
* die Offline-Simulation.


<!-- card: dark -->
> **Eine erfolgreiche Lightning-Zahlung beweist nur, dass diese Route einmal funktioniert hat.**
>
> Sie beweist nicht, dass die Wallet für größere Guthaben sicher ist oder dass derselbe Weg überall funktionieren wird.



<!-- micrographic: lightning-payment-sequence-01 -->
[Eine Lightning-Zahlung in sechs Schritten: Der Empfänger erstellt eine Anfrage, der Absender scannt sie, prüft Empfänger, Betrag, Einheit, Ablaufzeit und Gebühr und bestätigt sie, die Zahlung wird weitergeleitet, und beide Wallets zeigen das Ergebnis an. Jede Wallet kann verwahrt oder selbstverwahrt sein, und eine fehlgeschlagene oder abgelaufene Zahlung beginnt mit einer neuen Anfrage von vorn.](/micrographics/lightning-payment-sequence-01/de.md)
