# 2.9 Nutzer, Nodes und Miner

Bitcoin funktioniert, weil verschiedene Teilnehmer unterschiedliche Rollen übernehmen.

* **Nutzer** empfangen, verwahren und senden bitcoin. Ein Nutzer kann seine eigenen Schlüssel in einer Wallet selbst kontrollieren oder einen [Verwahrer](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) nutzen. Nutzer verleihen dem Netzwerk wirtschaftliche Bedeutung, indem sie entscheiden, ob sie bitcoin akzeptieren und welchen Regeln oder Diensten sie vertrauen.
* [**Nodes**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) betreiben Bitcoin-Software und überprüfen die Regeln unabhängig. Ein [Full Node](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) prüft, ob [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) gültige Signaturen haben, ob bitcoin nicht bereits ausgegeben wurden, ob Blöcke den [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) erfüllen und ob neue bitcoin dem [Ausgabeplan](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule) folgen. [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) teilen gültige Daten mit anderen Teilnehmern und weisen ungültige Daten zurück.
* [**Miner**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) sammeln ausstehende [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), erstellen [Kandidatenblöcke](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) und konkurrieren mittels [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Ein erfolgreicher [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [verbreitet](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) einen Block und kann die zulässige [Blocksubvention](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) sowie die [Transaktionsgebühren](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee) erhalten. [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) helfen dabei, [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) zu ordnen, und sorgen dafür, dass das [Hauptbuch](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) nur mit hohen Kosten umgeschrieben werden kann.
* **Entwickler** prüfen, schreiben und schlagen Softwareänderungen vor. Die Regeln von Bitcoin gehören ihnen nicht. Eine Softwareänderung ist nur dann von Bedeutung, wenn die Teilnehmer sich dafür entscheiden, Software zu betreiben, die diesen Regeln folgt.


<!-- micrographic: bitcoin-participant-roles-01 -->


Diese Rollen begrenzen sich gegenseitig:

* Ein Nutzer kann ohne die erforderliche gültige Signatur keine bitcoin ausgeben.
* Ein [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kann einen Block vorschlagen, aber [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) entscheiden, ob er den Regeln entspricht.
* Ein [Node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) prüft anhand seiner eigenen Regeln, aber [Konsens](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) erfordert kompatible Regeln im gesamten Netzwerk
* Entwickler können Software vorschlagen, aber die Teilnehmer entscheiden, ob sie sie ausführen

Manche Menschen übernehmen mehrere Rollen. Ein [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kann einen [Node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) betreiben und zugleich Nutzer sein. Ein Anfänger muss nicht jede Rolle selbst ausüben, um zu erklären, wie sich die Rollen gegenseitig ausbalancieren.

**Kurzfrage:** Warum verifiziert ein [Node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) die [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Nennen Sie mindestens eine Regel, die ein [Node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) überprüft.

![Die Lehrkraft leitet den technisch interessierten Lernenden an einem Node-Computer an; der Monitor ist ihnen zugewandt, sodass der Betrachter die Rückseite des Gehäuses sieht.](https://cdn.sanity.io/images/vje9ehw2/production/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
