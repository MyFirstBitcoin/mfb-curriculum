# 10.9 Lightning module checklist

Before a Lightning workshop, verify and explain:

* whether the wallet is custodial or self-custodial
* how it is funded
* whether funding or withdrawal uses an on-chain transaction or service
* recovery and continuity if the provider or device fails
* whether the request is an invoice, supported [Lightning address](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address), or another type
* amount, unit, recipient, expiry, fee, limits, and [liquidity](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) considerations
* what success, pending, expiry, or failure looks like
* how both parties independently confirm the result; and
* the offline simulation.


<!-- card: dark -->
> **One successful Lightning payment proves only that this route worked once**
>
> It does not prove that the wallet is safe for larger balances or that the same path will work in every place.



<!-- micrographic: lightning-payment-sequence-01 -->
[A Lightning payment in six steps: the receiver creates a request, the sender scans it, checks recipient, amount, unit, expiry and fee, approves, the payment routes, and both wallets show the result. Each wallet may be custodial or self-custodial, and a failed or expired payment starts again with a new request.](/micrographics/lightning-payment-sequence-01/en.md)
