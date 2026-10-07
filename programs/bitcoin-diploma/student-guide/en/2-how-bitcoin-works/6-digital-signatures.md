# 2.7 Digital signatures

Digital signatures are one of the key parts of Bitcoin's design described in the whitepaper. In Bitcoin, a wallet uses a private key to create a digital signature that authorizes a transaction. A wallet is usually an application that manages the keys and creates these signatures for the user. Only the holder of the required private key can authorize the spend; the network can verify the signature without learning the private key itself.

This allows a person to control bitcoin without asking a bank or other central operator for permission. It also means that control of the private key is critical: anyone who obtains it can usually authorize a spend, while a lost key may make the bitcoin irretrievable.
