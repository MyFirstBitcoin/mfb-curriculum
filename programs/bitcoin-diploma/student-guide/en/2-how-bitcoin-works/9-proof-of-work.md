# 2.10 Proof of work

**Proof of work** is the process miners use to compete for the right to propose the next block.

A miner repeatedly changes data in a candidate block and passes it through a mathematical hash function. The result is unpredictable. The miner is searching for a result below a target set by the network's difficulty rule. There is no shortcut; miners must perform many attempts.

When a miner finds a valid result, it broadcasts the block. Nodes can check the proof quickly, even though finding it required significant computation and energy. If the block includes a transaction, that transaction receives its first **confirmation**. Each valid block added after it adds another confirmation, making the transaction's place in the blockchain more costly to rewrite. This difference is important: work is costly to produce and easy to verify.

Proof of work serves several purposes:

* it gives independent miners a way to compete without a central scheduler;
* it makes the ordering of transactions costly to rewrite;
* it links network security to real-world equipment and energy;
* it supports a public method for choosing between competing valid histories: the chain with the most accumulated work.

Mining does not solve useful equations for an outside purpose. Its purpose is to secure the ordering of Bitcoin transactions. The network adjusts mining difficulty so that blocks continue to arrive about every ten minutes on average as computing power changes.

Proof of work involves a real energy cost. Supporters argue that this cost is what anchors Bitcoin's security and can create demand for flexible or otherwise unused energy. Critics question the amount and source of energy used. A responsible evaluation asks what energy is used, where it comes from, what security it provides, and what alternatives are being compared.
