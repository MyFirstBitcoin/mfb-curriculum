# 3.11 Verifizierung, Block-Explorer und unumkehrbare Transaktionen

<!-- card: definition -->
> **Definition – Transaktions-ID (TXID) und Block Explorer**
>
> Eine [Transaktions-ID](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_TXID_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identifiziert eine On-Chain-[Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Ein [Block Explorer](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) zeigt öffentliche Bitcoin-Daten an, etwa bei einer [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) den Status und die Anzahl der [Bestätigungen](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Er bietet eine nützliche Ansicht, ist aber keine Autorität über Bitcoin und kein Beweis für die Identität oder Ehrlichkeit des Empfängers.


Was können diese öffentlichen Informationen zeigen, und was nicht? Sie können bei einer [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) den Status, das Ziel, den Betrag, die Gebühr und die Anzahl der [Bestätigungen](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) zeigen; sie können jedoch nicht beweisen, warum eine Zahlung erfolgt ist oder ob eine Person vertrauenswürdig ist. Eine On-Chain-[Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ist unbestätigt, nachdem sie [im Netzwerk verbreitet](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) wurde, und erhält ihre [erste Bestätigung](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation), sobald sie in einen gültigen Block aufgenommen wird. Spätere Blöcke erhöhen die Sicherheit ihres Platzes im Verzeichnis, korrigieren aber weder ein falsches Ziel noch einen Betrug. Es gibt keine für jede Zahlung gültige Anzahl an [Bestätigungen](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation); die geeignete Prüfung hängt vom Betrag und vom Risiko ab.

Um eine vorbereitete [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) zu prüfen, beschaffen Sie sich ihre [_TXID_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), öffnen einen vertrauenswürdigen Explorer für das vorgesehene [Bitcoin-Netzwerk](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) und prüfen Status, Ziel, Betrag, Gebühr und [Bestätigungen](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Ein Explorer ist nur eine Oberfläche. Die Suche nach einer Adresse oder [_TXID_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) kann dessen Betreiber verraten, dass sich Ihr Gerät für diese Informationen interessiert. Verwenden Sie zum Üben eine von der Lehrkraft vorbereitete [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) oder einen ausgedruckten Screenshot. Suchen Sie nicht bei einem öffentlichen Dienst nach der persönlichen Adresse oder [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) einer lernenden Person. Wenn Sie später eine persönliche Zahlung recherchieren, machen Sie sich mit den [Privatsphäre](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy)- und Sicherheits[kompromissen](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) Ihrer Verbindung vertraut, bevor Sie einen öffentlichen Dienst nutzen.


<!-- card: callout -->
> **Öffentliche Daten sind kein Beweis für Identität oder Ehrlichkeit**
>
> Ein [Block Explorer](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) kann öffentliche Daten zu [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) anzeigen, aber nicht beweisen, wer eine Adresse kontrolliert, warum eine Zahlung erfolgt ist oder ob ein Empfänger vertrauenswürdig ist. Nutzen Sie zum Üben vorbereitete Beispiele und schützen Sie Ihre [Privatsphäre](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy), wenn Sie öffentliche Dienste für Suchanfragen nutzen.



<!-- micrographic: confirmation-timeline-01 -->
[Eine Transaktion wartet unbestätigt in der Warteschlange, wird dann in Block N als erste Bestätigung aufgenommen, und jeder weitere Block fügt eine weitere Bestätigung hinzu.](/micrographics/confirmation-timeline-01/de.md)


![Die Lehrkraft und ein älterer Lernender besprechen ein vorbereitetes Beispiel auf einem Monitor, der zur Gruppe ausgerichtet ist, während der technikaffine Lernende die Maus bedient; der Betrachter sieht die Rückseite des Gehäuses.](https://cdn.sanity.io/images/vje9ehw2/staging/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
