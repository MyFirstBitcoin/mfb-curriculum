# 2.3 Early digital-money attempts and the double-spend problem

Bitcoin was not the first attempt at digital money. It was built on four decades of experimentation, drawing on ideas from many earlier projects that helped shape its successful design.

**DigiCash** used cryptography to support private digital payments. It depended on a central company and banking relationships. When the company failed, the system could not continue as an independent money network.

**Hashcash** used proof of work to make unwanted email costly. A sender's computer had to perform work before sending a message. The idea showed how computational cost could discourage abuse.

**Bit Gold** described a proposed system in which computational work could create scarce digital records. It was not launched as a complete decentralized money system, but it developed important ideas about digital scarcity and proof.

**B-money** and **reusable proof of work** explored ways for participants to create or transfer scarce digital value without relying only on one central database. They were incomplete, but they helped clarify what a working system would need.

**BitTorrent** was not money. It showed that a peer-to-peer network could let many independent computers share information without one central server controlling the whole system.

Together, these experiments showed useful pieces of the puzzle. They also clarified the remaining problem.

The central problem was **double spending**. A paper note cannot be given to two people at the same time. However, digital data can be copied perfectly. A dishonest user could try to send the same digital unit to two recipients.

Centralized systems prevent this by letting one trusted database decide which payment came first. On 31 October 2008, Satoshi Nakamoto's whitepaper, _Bitcoin: A Peer-to-Peer Electronic Cash System_, explained a different approach: a public system that could establish a shared payment history without a bank, company, or other central authority.

The whitepaper brought together the features needed for that approach:

1. **A peer-to-peer network:** transactions are announced directly to a network of participants.
1. **Digital signatures:** only the holder of the relevant private key can authorize a spend.
1. **Blocks and mining:** miners collect transactions into blocks and use proof of work to compete to add the next block.
1. **Independent verification:** nodes check transactions and blocks against Bitcoin's rules.
1. **A shared history with accumulated proof of work:** participants recognize the valid chain of transactions with the most accumulated work as the shared record.

This module explains these concepts in more detail. Together, they gave a practical answer to the double-spend problem: the network can reject a second attempt to spend the same bitcoin without relying on a central authority. Bitcoin offered the missing combination that decades of digital-money experiments had been seeking.
