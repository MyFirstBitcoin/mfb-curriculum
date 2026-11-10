# 2.5 A Blockchain: o livro-razão público do Bitcoin

<!-- card: definition -->
> **Definition – Blockchain**
>
> No Bitcoin, a [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) é um registro público de [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) replicado em muitos computadores independentes. Um bloco agrupa um conjunto de [transações](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) válidas na próxima parte proposta desse registro. Cada bloco válido se liga ao anterior, dando à rede um histórico compartilhado e ordenado para verificar.



<!-- card: light -->
> **Como os nós chegam ao consenso**
>
> [Os nós](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verificam de forma independente as mesmas regras e convergem para o histórico válido com a maior quantidade acumulada de [Prova de Trabalho (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Alterar um registro anterior altera o seu bloco e quebra as ligações com os blocos posteriores, de modo que um histórico concorrente precisa refazer esse trabalho e alcançá-lo antes que os [nós](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) o aceitem. Esse processo de ordenação custoso ajuda a rede a chegar ao [consenso](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) sem um responsável central pelos registros. As cópias não mudam simultaneamente; os [nós](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) recebem e validam os dados de forma independente. O Bitcoin tem como meta um novo bloco a cada dez minutos, em média. O histórico é difícil e custoso de reescrever, mas não literalmente impossível de alterar: históricos concorrentes temporários e reorganizações podem ocorrer.
