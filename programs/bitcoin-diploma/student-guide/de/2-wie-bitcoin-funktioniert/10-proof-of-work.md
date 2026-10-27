# 2.10 Proof of Work

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Proof of Work (PoW)**
>
> [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ist der Prozess, den [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) nutzen, um im Wettbewerb das Recht zu erlangen, den nächsten Block vorzuschlagen.


Eine [Hash-Funktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) wandelt Daten in ein Ergebnis fester Länge um. Eine kleine Änderung der Eingabe erzeugt ein unvorhersehbares neues Ergebnis. Ein [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) verändert ein kleines Datenstück in einem vorgeschlagenen Block und hasht diesen wiederholt. Ein Ergebnis ist nur dann gültig, wenn seine Zahl unter dem [Zielwert](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) des Netzwerks liegt, einem durch die Regeln festgelegten Schwellenwert; ein niedrigerer [Zielwert](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) bedeutet weniger [gültige Ergebnisse](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) und mehr Versuche. Es gibt keine Abkürzung, daher müssen [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) unter Umständen viele Versuche unternehmen.

Wenn ein [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ein [gültiges Ergebnis](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) findet, [verbreitet](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) er den Block. [Knoten](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) können den Nachweis schnell überprüfen, obwohl seine Suche erhebliche Rechenleistung und Energie erforderte. Enthält der Block eine [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), erhält diese [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ihre [erste Bestätigung](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): Ihr Eintrag wurde in einen gültigen Block aufgenommen. Jeder danach hinzugefügte gültige Block fügt eine weitere [Bestätigung](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) hinzu, wodurch es kostspieliger wird, den Platz der [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) in der [Blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) umzuschreiben. Dieser Unterschied ist wichtig: Arbeit ist kostspielig zu erzeugen und leicht zu überprüfen.


<!-- micrographic: proof-of-work-process-01 -->
[Ein Miner berechnet immer wieder den Hash eines vorgeschlagenen Blocks, bis ein Ergebnis unter dem Zielwert des Netzwerks liegt, und verbreitet den Block dann. Nodes prüfen den Nachweis und jede Regel schnell, bevor der Block Teil der Blockchain wird: Arbeit ist aufwendig zu erbringen und leicht zu überprüfen.](/micrographics/proof-of-work-process-01/de.md)


[Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) erfüllt mehrere Zwecke:

* Er bietet unabhängigen [Minern](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) eine Möglichkeit, ohne zentrale Koordinierungsstelle miteinander zu konkurrieren
* er macht es kostspielig, die Reihenfolge der [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) umzuschreiben
* er verknüpft die Netzwerksicherheit mit realer Hardware und Energie
* er unterstützt ein öffentliches Verfahren zur Wahl zwischen konkurrierenden gültigen Verläufen: die Kette mit der meisten [akkumulierten Arbeit](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) löst keine nützlichen Gleichungen für einen externen Zweck. Sein Zweck ist es, die Reihenfolge der Bitcoin-[Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) abzusichern. Das Netzwerk passt den Zielwert regelmäßig an: Wenn Blöcke zu schnell eintreffen, senkt es den Zielwert, und wenn sie zu langsam eintreffen, erhöht es ihn. So soll bei sich ändernder Rechenleistung im Durchschnitt etwa alle zehn Minuten ein Block entstehen.

[Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ist mit realen Energiekosten verbunden. Befürworter argumentieren, dass genau diese Kosten die Sicherheit von Bitcoin verankern und Nachfrage nach flexibler oder anderweitig ungenutzter Energie schaffen können. Kritiker hinterfragen die Menge und die Herkunft der verwendeten Energie. Eine verantwortungsvolle Bewertung fragt, welche Energie verwendet wird, woher sie stammt, welche Sicherheit sie bietet und mit welchen Alternativen verglichen wird.

![Die Lehrkraft, ein Lernender ohne Vorkenntnisse und ein technisch versierter Lernender besprechen ein Mining-Gerät für den Tisch mit Lüfter und separatem Netzteil.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
