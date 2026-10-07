# 3.11 Verification, block explorers, and irreversible transactions

A **transaction ID (TXID)** identifies an on-chain transaction. A **block explorer** shows public Bitcoin data, such as a transaction's status and confirmation count. It is a useful view, not an authority over Bitcoin and not proof of the recipient's identity or honesty.

What can this public information show, and what can it not show? It can show a transaction's status, destination, amount, fee, and confirmation count; it cannot prove why a payment happened or whether a person is trustworthy. An on-chain transaction is unconfirmed after it is broadcast and gains its first confirmation when included in a valid block. Later blocks add confidence to its place in the record, but they do not fix a wrong destination or a scam. There is no universal confirmation count for every payment; the suitable check depends on the amount and risk.

To inspect a prepared transaction, obtain its TXID, open a trusted explorer for the intended Bitcoin network, and check the status, destination, amount, fee, and confirmations. An explorer is only an interface. Searching an address or TXID may reveal to its operator that your device is interested in that information. For practice, use an educator-prepared transaction or printed screenshot. Do not search a learner's personal address or transaction on a public service.
