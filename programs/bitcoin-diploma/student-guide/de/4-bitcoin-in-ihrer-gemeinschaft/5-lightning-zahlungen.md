# 4.5 Lightning-Zahlungen

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning kann schnelle, kleine Bitcoin-Zahlungen praktikabel machen. Es eignet sich zum Beispiel für die Ladenkasse, wiederkehrende lokale Zahlungen, Online-Dienste oder Überweisungen, bei denen eine On-Chain-Gebühr im Verhältnis zur Zahlung zu hoch wäre.

Eine lokale Lightning-Vorführung sollte Folgendes klären:

* ob die Wallet verwahrt (custodial) oder selbstverwahrt (self-custodial) ist
* wie die Wallet aufgeladen wird
* ob für die Aufladung eine On-Chain-[Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) oder ein Dienst erforderlich ist
* welche Sicherung oder Wiederherstellung das Guthaben schützt
* welche Art von Zahlungsanforderung verwendet wird
* welche Gebühren oder Limits gelten
* was passiert, wenn eine Zahlung fehlschlägt
* wie der Empfänger die Zahlung bestätigt

Eine [**Lightning-Rechnung**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) ist eine Zahlungsanforderung, die für eine bestimmte Zahlung erstellt wird. Sie kann einen Betrag, Angaben zum Ziel und eine Ablaufzeit enthalten. Lesen Sie vor dem Bezahlen den Bildschirm zur [Bestätigung](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) in der Wallet.

Eine [**Lightning-Adresse**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) ist eine für Menschen lesbare Kennung, die von einigen Diensten unterstützt wird. Sie kann wie eine E-Mail-Adresse aussehen, ist aber eine Erleichterung für die Weiterleitung von Zahlungen und kein E-Mail-Konto. Sie hängt vom Anbieter oder von der Domain ab, die sie unterstützt.

Für eine angeleitete Zahlung:

1. Der Empfänger erstellt die richtige Zahlungsanforderung.
1. Der Sender scannt oder kopiert sie.
1. Der Sender prüft Empfänger, Betrag, Einheit und Gebühr.
1. Der Sender gibt die Zahlung erst frei, wenn alle Angaben stimmen.
1. Beide Seiten bestätigen das Ergebnis in ihrer eigenen Wallet.
1. Die Gruppe erläutert die Risiken bei der [Verwahrung](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) und bei fehlgeschlagenen Zahlungen.

Gehen Sie nicht davon aus, dass eine erfolgreiche Lightning-Zahlung beweist, dass die Wallet auch für größere Guthaben sicher ist. Bequemes Bezahlen und die Sicherheit der [Verwahrung](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) sind zwei getrennte Fragen.
