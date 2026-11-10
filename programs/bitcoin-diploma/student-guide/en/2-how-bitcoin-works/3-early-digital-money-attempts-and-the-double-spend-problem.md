# 2.3 Early digital-money attempts and the double-spend problem

Bitcoin was not the first attempt at digital money. It was built on four decades of experimentation, drawing on ideas from many earlier projects that helped shape its successful design.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) used [cryptography](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) to support private digital payments. It depended on a central company and banking relationships. When the company failed, the system could not continue as an independent money network.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) used [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) to make unwanted email costly. A sender's computer had to perform work before sending a message. The idea showed how computational cost could discourage abuse.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) described a proposed system in which computational work could create scarce digital records. It was not launched as a complete decentralized money system, but it developed important ideas about digital [scarcity](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) and proof.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) and [**reusable proof of work (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) explored ways for participants to create or transfer scarce digital [value](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) without relying only on one central database. They were incomplete, but they helped clarify what a working system would need.
* Although [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) was not money, it showed that a [peer-to-peer network](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) could let many independent computers share information without one central server controlling the whole system.

Together, these experiments showed useful pieces of the puzzle. They also clarified the remaining problem.


> **Definition – Double spending**
>
> [Double spending](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) is an attempt to send the same digital unit to two recipients. Digital data can be copied perfectly, so a digital money system needs a way to establish which [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) is valid.


[Centralized systems](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) prevent this by letting one trusted database decide which payment came first. On 31 October 2008, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto)'s whitepaper, [_Bitcoin: A Peer-to-Peer Electronic Cash System_](https://bitcoin.org/bitcoin.pdf), explained a different approach: a public system that could establish a shared payment history without a bank, company, or other central authority.

The whitepaper brought together the features needed for that approach:

1. **A [peer-to-peer network](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) are announced directly to a network of participants.
1. **[Digital signatures](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** a [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) is secret information that creates a signature to authorize a spend; only its holder can do this.
1. **Blocks and [mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) collect [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) into blocks and use [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) to compete to add the next block.
1. **Independent [verification](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) check [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) and blocks against Bitcoin's rules.
1. **A shared history with accumulated [proof of work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** participants recognize the [valid chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) of [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) with the most [accumulated work](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) as the shared record.


<!-- micrographic: five-part-response-01 -->


This module explains these concepts in more detail. Together, they gave a practical answer to the [double-spend problem](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): the network can reject a second attempt to spend the same bitcoin without relying on a central authority. Bitcoin offered the missing combination that decades of digital-money experiments had been seeking.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
