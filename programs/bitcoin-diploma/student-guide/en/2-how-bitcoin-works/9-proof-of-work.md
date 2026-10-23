# 2.10 Proof of work

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Proof of work**
>
> [Proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) is the process [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) use to compete for the right to propose the next block.


A [hash function](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) turns data into a fixed-length result. A small change to the input produces an unpredictable new result. A [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) changes a small piece of data in a proposed block and hashes it repeatedly. A result is valid only when its number is below the network's [target](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), a threshold set by the rules; a lower [target](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) means fewer [valid results](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) and more attempts. There is no shortcut, so [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) may need to make many attempts.

When a [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) finds a [valid result](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), it [broadcasts](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) the block. [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) can check the proof quickly, even though finding it required significant computation and energy. If the block includes a [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), that [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) receives its [first confirmation](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): its record has been included in one valid block. Each valid block added after it adds another [confirmation](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), making the [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)'s place in the [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) more costly to rewrite. This difference is important: work is costly to produce and easy to verify.


<!-- micrographic: proof-of-work-process-01 -->


[Proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) serves several purposes:

* it gives independent [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) a way to compete without a central scheduler
* it makes the ordering of [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) costly to rewrite
* it links network security to real-world equipment and energy
* it supports a public method for choosing between competing valid histories: the chain with the most [accumulated work](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) does not solve useful equations for an outside purpose. Its purpose is to secure the ordering of Bitcoin [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). The network periodically adjusts the target: when blocks arrive too quickly it lowers the target, and when they arrive too slowly it raises it, aiming for about one block every ten minutes on average as computing power changes.

[Proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) involves a real energy cost. Supporters argue that this cost is what anchors Bitcoin's security and can create demand for flexible or otherwise unused energy. Critics question the amount and source of energy used. A responsible evaluation asks what energy is used, where it comes from, what security it provides, and what alternatives are being compared.

![The educator, beginner learner, and technical learner discuss a tabletop mining unit with a fan and separate power supply.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
