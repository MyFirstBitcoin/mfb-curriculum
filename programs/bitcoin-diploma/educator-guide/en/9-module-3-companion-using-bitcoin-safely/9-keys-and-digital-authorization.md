# 9.10 Keys and digital authorization

Keep the practical rule central:

> Public receiving information may be shared. Private spending information must remain secret.

Teach:

* a [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) authorizes spending through a [digital signature](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature)
* a [public key](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) supports verification without revealing the [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key)
* modern wallets manage many keys automatically; and
* beginners should not copy or handle raw [private-key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) strings.

Do not use “the [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) proves who you are.” It proves authorization by the key, not a legal identity.

No legitimate educator, wallet company, exchange employee, developer, support worker, or public figure needs a learner's [private key](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) or [seed phrase](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase).


<!-- micrographic: private-key-public-info-01 -->
[A secret private key, which must never be shared, leads to public information that can be shared: a public key derived from it and a receiving address created from that. The same private key creates signatures that nodes verify without ever learning the private key.](/micrographics/private-key-public-info-01/en.md)
