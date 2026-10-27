# 3.3 Transactions in action

_Experiential · Whole class · 30 min_

Participants use real Bitcoin wallets to create a fresh on-chain receiving address, check the payment details, approve a small real payment, and check its status. The educator connects the observed wallet steps to the distinct roles of a sender, recipient, node, and miner. Learners do not try to create invalid transactions or expose wallet information in order to learn why those transactions are rejected.

#### Objectives

* Participants use real Bitcoin wallets and a low-stakes on-chain payment to practise verifying a destination, amount, network, fee, and payment result.
* Participants distinguish wallet authorization, recipient verification, node validation, and a miner's candidate-block role while observing an actual transaction.

#### Materials

* An educator-checked on-chain Bitcoin wallet and connection for each participating sender and receiver.
* A small amount of real bitcoin that the educator has approved for the activity, including enough for the expected network fee.
* A planned payment order and final return destination.
* A whiteboard or projected screen for the educator's general role explanation. Do not display learner wallet details.

#### Setup

Before class, test the exact wallet, source, network, amount, expected fee, payment destination, and receipt path. State who provides the funds, the planned payment order, the final return destination, the expected result, and when to stop. Do not screen-share or collect a learner's wallet details.

#### Procedure

##### Step 1: Create and check receiving information

The receiver creates a fresh on-chain receiving address for the educator-approved amount. The sender checks the destination, amount, unit, network, expected fee, and final summary before approving. Stop if anything is unclear or does not match.

##### Step 2: Authorize and broadcast the transaction

The sender approves the transaction on their own device. Explain that the wallet signs under the sender's authority and broadcasts the transaction; the recipient does not approve it for the Bitcoin network. The learner's approval screen is not evidence that all network checks have already occurred.

##### Step 3: Check the payment status

The receiver checks the result on their own device. Explain the difference between broadcast, pending, and confirmed status. Do not ask either learner to show a seed phrase, private key, password, balance, transaction history, or other unnecessary personal information.

##### Step 4: Connect the live transaction to Bitcoin roles

Explain that nodes independently validate transactions and blocks against Bitcoin's rules. Miners may choose valid transactions for candidate blocks and attempt proof of work; nodes decide whether to accept the resulting block. The live payment can show a wallet approval and payment status, but it does not expose every signature, input, or network check.

##### Step 5: Return funds and debrief

Where the planned route permits, return the funds to the educator's final destination. Discuss the actual fee, status, relevant privacy considerations, and why a successful low-stakes payment does not make a learner ready to hold or use significant funds. If the payment fails, pause to understand the message; do not retry by guessing.

#### Key points

1. A sender authorizes a transaction with a signature. A recipient can provide a destination and check for a payment, but recipient approval is not a consensus rule.
1. Nodes independently validate transactions and blocks against Bitcoin's rules.
1. Miners build candidate blocks from transactions and try to find proof of work. They do not set the validation rules.
1. A confirmation means that a transaction appears in a block that a node accepts. Confirmation and finality involve risk and context, not an absolute promise that nothing can change.
1. A carefully supervised low-stakes real payment can make verification concrete, but it is not a test of readiness to hold or use significant funds.

#### Discussion questions

* Which role authorizes the transaction?
* Which role checks the stated transaction rules?
* Which parts of the live payment are visible to the sender and receiver, and which happen elsewhere in the network?
* Why does Bitcoin use cryptography to sign transactions?

#### Notes

<!-- card: callout -->
> **Use real wallets and funds only for this learning activity**
>
> Before beginning, follow the Educator Guide's live-practice guidance. Explain the route and risks in advance; use an amount whose loss is not significant; make participation voluntary; protect all secrets and unnecessary payment information; and define stop conditions. Use educator-prepared funds where possible. Do not pressure learners to use their own funds or recommend a wallet or service.


**Bitcoin Diploma assessment link:** May provide the individual-response context for `T2` / `C2` and direct practical learning where an approved route calls for it. Use the approved protocol and record only the individual evidence needed for the relevant criteria; otherwise, this activity is formative. It is not an assessment route for significant funds.

Invite learners to explain the checks they made before approval and the difference between wallet authorization, recipient verification, node validation, and mining.

**Tip:** Rotate learners through sending and receiving roles where the planned funds and available time allow.

**Video**

**Book**

#### Additional resources

* [“Blockchain 101 – A Visual Demo” by Anders Brownworth and posted through MIT.](https://blockchain.mit.edu/how-blockchain-works)
  “Inventing Bitcoin: The Technology Behind the First Truly Scarce and Decentralized Money Revealed” by Yan Pritzker provides a high-level overview of Bitcoin's inner workings, including how consensus achieves scarcity.
