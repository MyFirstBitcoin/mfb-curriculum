# 4.5 Lightning payments

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning can make fast, small Bitcoin payments practical. It may be suitable for a merchant counter, repeated local payments, online services, or transfers where an on-chain fee would be too large in relation to the payment.

A local Lightning demonstration should identify:

* whether the wallet is custodial or self-custodial
* how the wallet is funded
* whether funding requires an on-chain [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) or a service
* what backup or recovery protects the balance
* what type of payment request is being used
* what fees or limits apply
* what happens when a payment fails
* how the recipient confirms payment

A [**Lightning invoice**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) is a payment request created for a specific payment. It can include an amount, destination information, and an expiry time. Read the wallet's [confirmation](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) screen before paying.

A [**Lightning address**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) is a human-readable identifier supported by some services. It may look like an email address, but it is a payment-routing convenience, not an email account. It depends on the provider or domain that supports it.

For a guided payment:

1. The receiver creates the correct request.
1. The sender scans or copies it.
1. The sender checks the recipient, amount, unit, and fee.
1. The sender approves only after the details are correct.
1. Both sides confirm the result in their own wallets.
1. The group explains the [custody](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) and failure risks.

Do not assume that a successful Lightning payment proves the wallet is safe for larger balances. Payment convenience and [custody](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) security are separate questions.
