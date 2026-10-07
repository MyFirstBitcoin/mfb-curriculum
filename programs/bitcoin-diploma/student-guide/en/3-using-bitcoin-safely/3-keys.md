# 3.4 Keys

Bitcoin ownership is enforced through cryptographic keys.

A **private key** is secret information that allows a wallet to create a valid digital signature. That signature authorizes the spending of bitcoin controlled by the corresponding key. Anyone who obtains the private key can usually spend those funds.

A **public key** is mathematically related to the private key. It helps verify a signature without revealing the private key. Addresses are created from public-key information.

The essential rule is simple:

**Public receiving information can be shared. Private spending information must remain secret.**

A digital signature proves that the required private key authorized a transaction. It does not place the private key inside the transaction. Nodes verify the signature before accepting the spend.

Modern wallets manage many keys automatically. Beginners should not copy or handle individual private-key strings. Protect the wallet's approved backup and follow its recovery procedure.

No legitimate educator, wallet company, exchange employee, technical-support worker, or Bitcoin developer needs your private key or seed phrase. Anyone who asks for it should be treated as a threat.

**Try it:** Sort prepared examples into three groups: safe to share for receiving, secret spending information, and information that may be public but should still be kept private when linked to a person.
