# 2.9 Users, nodes, and miners

Bitcoin works because different participants perform different roles.

**Users** receive, hold, and send bitcoin. A user may control their own keys held in a wallet or use a custodian. Users give the network economic meaning by choosing whether to accept bitcoin and which rules or services they trust.

**Nodes** run Bitcoin software and independently verify the rules. A full node checks that transactions have valid signatures, that bitcoin have not already been spent, that blocks satisfy proof of work, and that new bitcoin follow the issuance schedule. Nodes share valid data with peers and reject invalid data.

**Miners** gather pending transactions, build candidate blocks, and compete through proof of work. A successful miner broadcasts a block and may receive the allowed block subsidy and transaction fees. Miners help order transactions and make the ledger costly to rewrite.

**Developers** review, write, and propose software changes. They do not own Bitcoin's rules. A software change matters only if participants choose to run software that follows those rules.

These roles limit one another:

* a user cannot spend bitcoin without the required valid signature;
* a miner can propose a block, but nodes decide whether it follows the rules;
* a node verifies using its own rules, but consensus requires compatible rules across the network;
* developers can propose software, but participants choose whether to run it.

Some people perform several roles. A miner can run a node and also be a user. A beginner does not need to perform every role to explain how the roles balance one another.

**Spot question:** Why does a node verify transactions? Name at least one rule that a node checks.
