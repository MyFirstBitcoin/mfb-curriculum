# 3.6 Lightning payment relay

_Experiential · Whole class, Small groups · 30–45 min_

Participants create fresh Lightning invoices, receive a small real payment, and relay the funds to the next participant. Before every payment, they check the invoice, amount, unit, destination, expiry, and status. The activity supports a discussion of routing, fees, and payment failure through the actual payment experience.

#### Objectives

* Participants use real Lightning wallets and a low-stakes real payment to practise the information checks involved in a Lightning payment relay.

#### Materials

* An educator-checked Lightning wallet and connection for each participating sender and receiver.
* A small amount of real bitcoin that the educator has approved for the activity, including enough for any expected fees.
* A planned relay order and a final return destination.
* A paper tracking sheet and pencils for learning observations, not wallet or personal financial information.

#### Setup

Test the exact wallet, network, invoice process, amount, and receipt path before class. State who provides the funds, whether any fee applies, the relay order, the intended final destination, the expected result, and when to stop. Do not screen-share or collect a learner's wallet details.

#### Procedure

##### Step 1: Create and check the first Lightning invoice

The first receiver creates a fresh Lightning invoice for the educator-approved amount. The sender checks the destination, amount, unit, expiry, and network before approving. If any required detail is unclear or mismatched, stop.

##### Step 2: Send and confirm receipt

The sender approves the payment on their own device. The receiver checks the result on their own device. Neither learner needs to show a seed phrase, private key, password, full balance, or payment history. Record only the learning observation needed for the activity.

##### Step 3: Relay the real payment

The receiver becomes the next sender. Continue until every planned participant has received and sent the educator-approved amount. The final participant returns the funds to the planned destination. If a payment fails, pause to understand the message; do not retry by guessing or changing details without understanding why.

##### Step 4: Debrief the live payment

Discuss the actual result, any fee, the information checked before approval, the limits of what the wallet display shows, and why a successful small payment does not make a wallet suitable for significant funds. Compare a Lightning payment path with an on-chain confirmation without claiming that one is always better.

#### Key points

1. A payment request needs careful checks before action, including destination, amount, unit, network, and status.
1. Lightning payments can fail for reasons such as an expired request or an unavailable route. A failure is a reason to pause and understand the message, not to guess.
1. A carefully supervised low-stakes live payment can teach checks and trade-offs. It does not make a learner ready to use a wallet with significant funds.

#### Discussion questions

1. Which details did your group check before approving the payment?
1. What did the actual payment result show, and what did it not show?
1. What should someone do when a payment request is unclear or fails?
1. Which questions would need local, current information before a future real payment is considered?

#### Notes

<!-- card: callout -->
> **Use real wallets and funds only for this learning activity**
>
> Before beginning, follow the Educator Guide's live-practice guidance: make the route and risks clear, use an amount whose loss is not significant, make participation voluntary, protect every secret and unnecessary payment detail, and define stop conditions. Use educator-prepared funds where possible. Do not pressure learners to use their own funds or turn this into a recommendation of a wallet or service.


**Bitcoin Diploma assessment link:** This activity is formative unless the educator has selected an approved practical route. It may support discussion of payment-path trade-offs for `T3` / `C5`, and it may support directly observed practical learning, only when the educator uses the approved protocol and records an individual explanation or performance. It is not an assessment route for significant funds.

#### Additional resources

* [Lightning Network overview is background reading for educators. Verify current technical and local-service information before any live activity.](https://lightning.network/)
