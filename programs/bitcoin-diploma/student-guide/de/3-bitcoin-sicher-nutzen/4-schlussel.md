# 3.4 Schlüssel

Bitcoin-Eigentum wird durch kryptografische Schlüssel durchgesetzt.


> **Definition – Privater Schlüssel**
>
> Ein [privater Schlüssel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ist eine geheime Information, mit der eine Wallet gültige [digitale Signaturen](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) erstellen kann. Eine Signatur autorisiert das Ausgeben von bitcoin, die durch den zugehörigen Schlüssel kontrolliert werden. Wer den [privaten Schlüssel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) erlangt, kann diese Mittel in der Regel ausgeben.


Ein [**öffentlicher Schlüssel**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) wird mathematisch aus dem [privaten Schlüssel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) abgeleitet. Er hilft, eine Signatur zu überprüfen, ohne den [privaten Schlüssel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) preiszugeben. Adressen werden aus Informationen des [öffentlichen Schlüssels](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) erstellt.

Die wesentliche Regel ist einfach:

**Öffentliche Empfangsinformationen dürfen weitergegeben werden. Private Informationen zum Ausgeben müssen geheim bleiben.**

Eine [digitale Signatur](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) beweist, dass der erforderliche [private Schlüssel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) eine [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) autorisiert hat. Dabei wird der [private Schlüssel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) nicht in die [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) eingefügt. [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) prüfen die Signatur, bevor sie die Ausgabe akzeptieren.

Die meisten Wallets für Einsteiger verwenden [Single-Signature](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): Ein privater Schlüssel autorisiert eine Transaktion. Moderne Wallets verwalten viele Schlüssel automatisch. Einsteiger sollten keine einzelnen Zeichenfolgen von [privaten Schlüsseln](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) kopieren oder handhaben. Schützen Sie das vorgesehene Backup der Wallet und befolgen Sie deren Wiederherstellungsverfahren.

Keine seriöse Lehrkraft, kein Wallet-Unternehmen, kein Mitarbeiter einer Börse, kein technischer Support und kein Bitcoin-Entwickler braucht Ihren [privaten Schlüssel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) oder Ihre [Seed-Phrase](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Jede Person, die danach fragt, sollte als Bedrohung behandelt werden.


> **Light**
>
> **Probieren Sie es aus:** Ordnen Sie vorbereitete Beispiele drei Gruppen zu: unbedenklich zum Empfangen weiterzugeben, geheime Informationen zum Ausgeben sowie Informationen, die zwar öffentlich sein können, aber dennoch privat gehalten werden sollten, wenn sie mit einer Person verknüpft sind.



<!-- micrographic: private-key-public-info-01 -->
