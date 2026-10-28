# 2.9 Users, nodes, and miners

Bitcoin works because different participants perform different roles.

* **Users** receive, hold, and send bitcoin. A user may control their own keys held in a wallet or use a [custodian](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Users give the network economic meaning by choosing whether to accept bitcoin and which rules or services they trust.
* [**Nodes**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) run Bitcoin software and independently verify the rules. A [full node](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) checks that [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) have valid signatures, that bitcoin have not already been spent, that blocks satisfy [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), and that new bitcoin follow the [issuance schedule](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) share valid data with peers and reject invalid data.
* [**Miners**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gather pending [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), build [candidate blocks](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block), and compete through [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). A successful [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [broadcasts](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) a block and may receive the allowed [block subsidy](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) and [transaction fees](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) help order [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) and make the [ledger](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) costly to rewrite.
* **Developers** review, write, and propose software changes. They do not own Bitcoin's rules. A software change matters only if participants choose to run software that follows those rules.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Four roles in Bitcoin: users receive, hold and send bitcoin, nodes independently verify the rules, miners build candidate blocks with proof of work, and developers propose software. No single role controls the network.](/micrographics/bitcoin-participant-roles-01/en.md)


These roles limit one another:

* a user cannot spend bitcoin without the required valid signature
* a [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) can propose a block, but [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) decide whether it follows the rules
* a [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifies using its own rules, but [consensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) requires compatible rules across the network
* developers can propose software, but participants choose whether to run it

Some people perform several roles. A [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) can run a [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) and also be a user. A beginner does not need to perform every role to explain how the roles balance one another.

**Spot question:** Why does a [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verify [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Name at least one rule that a [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) checks.

![The educator guides the technical learner at a node computer, with the monitor facing them and its rear casing visible to the viewer.](https://cdn.sanity.io/images/vje9ehw2/production/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
