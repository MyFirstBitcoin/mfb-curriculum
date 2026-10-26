# 2.3 Frühe Versuche mit digitalem Geld und das Problem der Doppelausgabe

Bitcoin war nicht der erste Versuch, digitales Geld zu schaffen. Es baute auf vier Jahrzehnten des Experimentierens auf und griff Ideen aus vielen früheren Projekten auf, die zu seinem erfolgreichen Design beitrugen.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) nutzte [Kryptografie](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography), um private digitale Zahlungen zu ermöglichen. Es war von einem zentralen Unternehmen und Bankbeziehungen abhängig. Als das Unternehmen scheiterte, konnte das System nicht als unabhängiges Geldnetzwerk weiterbestehen.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) nutzte [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), um unerwünschte E-Mails kostspielig zu machen. Der Computer eines Absenders musste Arbeit verrichten, bevor er eine Nachricht versenden konnte. Die Idee zeigte, wie Rechenaufwand Missbrauch eindämmen kann.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) beschrieb ein vorgeschlagenes System, in dem Rechenarbeit knappe digitale Einträge erzeugen konnte. Es wurde nie als vollständiges dezentrales Geldsystem gestartet, entwickelte aber wichtige Ideen zu digitaler [Knappheit](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) und Nachweisbarkeit.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) und [**Reusable Proof of Work (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) erkundeten Wege, wie Teilnehmer knappe digitale [Werte](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) erzeugen oder übertragen können, ohne sich ausschließlich auf eine zentrale Datenbank zu verlassen. Sie waren unvollständig, halfen aber zu klären, was ein funktionierendes System benötigen würde.
* Obwohl [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) kein Geld war, zeigte es, dass ein [Peer-to-Peer-Netzwerk (P2P)](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) es vielen unabhängigen Computern ermöglichen kann, Informationen auszutauschen, ohne dass ein zentraler Server das gesamte System kontrolliert.

Zusammen lieferten diese Experimente nützliche Teile des Puzzles. Sie machten zugleich deutlich, welches Problem noch ungelöst war.


> **Definition – Doppelausgaben**
>
> [Doppelausgabe (Double Spending)](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) ist der Versuch, dieselbe digitale Einheit an zwei Empfänger zu senden. Digitale Daten lassen sich perfekt kopieren, daher braucht ein digitales Geldsystem eine Möglichkeit festzustellen, welche [Transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) gültig ist.


[Zentralisierte Systeme](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) verhindern dies, indem eine einzige vertrauenswürdige Datenbank entscheidet, welche Zahlung zuerst erfolgte. Am 31. Oktober 2008 erläuterte das Whitepaper von [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto), „[_Bitcoin: A Peer-to-Peer Electronic Cash System_](https://bitcoin.org/bitcoin.pdf)“, einen anderen Ansatz: ein öffentliches System, das ohne Bank, Unternehmen oder eine andere zentrale Instanz eine gemeinsame Zahlungshistorie festlegen kann.

Das Whitepaper vereinte die für diesen Ansatz erforderlichen Merkmale:

1. **Ein [Peer-to-Peer-Netzwerk (P2P)](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) werden direkt an ein Netzwerk von Teilnehmern übermittelt.
1. **[Digitale Signaturen](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** Ein [Privater Schlüssel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ist eine geheime Information, mit der eine Signatur erzeugt wird, um eine Ausgabe zu autorisieren; nur sein Inhaber kann dies tun.
1. **Blöcke und [Mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [Miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) fassen [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) zu Blöcken zusammen und nutzen [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), um im Wettbewerb den nächsten Block hinzuzufügen.
1. **Unabhängige [Überprüfung](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) prüfen [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) und Blöcke anhand der Regeln von Bitcoin.
1. **Eine gemeinsame Historie mit akkumuliertem [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** Die Teilnehmer erkennen die [gültige Kette](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) von [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mit der meisten [akkumulierten Arbeit](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) als gemeinsames Register an.


<!-- micrographic: five-part-response-01 -->


Dieses Modul erklärt diese Konzepte ausführlicher. Gemeinsam lieferten sie eine praktische Antwort auf das [Double-Spend-Problem](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): Das Netzwerk kann einen zweiten Versuch, denselben bitcoin auszugeben, ablehnen, ohne auf eine zentrale Instanz angewiesen zu sein. Bitcoin bot die fehlende Kombination, nach der jahrzehntelange Experimente mit digitalem Geld gesucht hatten.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
