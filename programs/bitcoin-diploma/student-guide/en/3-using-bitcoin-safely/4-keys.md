# 3.4 Keys

Bitcoin ownership is enforced through cryptographic keys.


<!-- card: definition -->
> **Definition – Private key**
>
> A [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) is secret information that allows a wallet to create valid [digital signatures](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). A signature authorizes the spending of bitcoin controlled by the corresponding key. Anyone who obtains the [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) can usually spend those funds.


A [**public key**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) is mathematically derived from the [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). It helps verify a signature without revealing the [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Addresses are created from [public-key](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) information.

The essential rule is simple:

**Public receiving information can be shared. Private spending information must remain secret.**

A [digital signature](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) proves that the required [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) authorized a [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). It does not place the [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) inside the [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verify the signature before accepting the spend.

Most beginner wallets use [single-signature](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): one private key authorizes a transaction. Modern wallets manage many keys automatically. Beginners should not copy or handle individual [private-key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) strings. Protect the wallet's approved backup and follow its recovery procedure.

No legitimate educator, wallet company, exchange employee, technical-support worker, or Bitcoin developer needs your [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) or [seed phrase](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Anyone who asks for it should be treated as a threat.


<!-- card: light -->
> **Try it:** Sort prepared examples into three groups: safe to share for receiving, secret spending information, and information that may be public but should still be kept private when linked to a person.



<!-- micrographic: private-key-public-info-01 -->
[A secret private key, which must never be shared, leads to public information that can be shared: a public key derived from it and a receiving address created from that. The same private key creates signatures that nodes verify without ever learning the private key.](/micrographics/private-key-public-info-01/en.md)
