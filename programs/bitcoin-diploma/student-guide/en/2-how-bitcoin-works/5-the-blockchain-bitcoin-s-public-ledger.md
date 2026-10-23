# 2.5 The Blockchain: Bitcoin’s Public Ledger

> **Definition – Blockchain**
>
> Bitcoin's [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) is a public [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) record replicated across many independent computers. A block groups a set of valid [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) into the next proposed part of that record. Each valid block links to the previous one, giving the network an ordered shared history to verify.



> **Definition – Node**
>
> [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) independently check the same rules and converge on the valid history with the most accumulated [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Changing an earlier record changes its block and breaks the links to later blocks, so a competing history must redo that work and catch up before [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) accept it. This costly ordering process helps the network reach [consensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) without a central record keeper. Copies do not change simultaneously; [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) receive and validate data independently. Bitcoin targets one new block about every ten minutes on average. The history is difficult and costly to rewrite, not literally impossible to change: temporary competing histories and reorganizations can occur.
