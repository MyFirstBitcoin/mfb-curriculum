# 2.5 Die Blockchain: Das öffentliche Hauptbuch von Bitcoin

<!-- card: definition -->
> **Definition – Blockchain**
>
> Die Bitcoin-[Blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) ist ein öffentliches Verzeichnis von [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), das auf vielen unabhängigen Computern repliziert wird. Ein Block fasst eine Reihe gültiger [Transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) zum nächsten vorgeschlagenen Teil dieses Verzeichnisses zusammen. Jeder gültige Block ist mit dem vorherigen verknüpft, wodurch das Netzwerk eine geordnete gemeinsame Historie erhält, die es überprüfen kann.



<!-- card: definition -->
> **Definition – Node**
>
> [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) prüfen unabhängig voneinander dieselben Regeln und einigen sich auf die gültige Historie mit dem meisten angesammelten [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Wird ein früherer Eintrag geändert, ändert sich sein Block, und die Verknüpfungen zu späteren Blöcken brechen. Eine konkurrierende Historie muss diese Arbeit daher erneut leisten und aufholen, bevor [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) sie akzeptieren. Dieser kostspielige Ordnungsprozess hilft dem Netzwerk, einen [Konsens](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) ohne zentrale Registerführung zu erreichen. Die Kopien ändern sich nicht gleichzeitig; [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) empfangen und validieren Daten unabhängig voneinander. Bitcoin strebt im Durchschnitt etwa alle zehn Minuten einen neuen Block an. Die Historie ist schwer und kostspielig umzuschreiben, aber nicht buchstäblich unveränderlich: Vorübergehende konkurrierende Historien und Reorganisationen können vorkommen.
