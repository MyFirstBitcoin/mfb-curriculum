# 3.14 On-chain and Lightning payments

Bitcoin has more than one payment path. **On-chain** payments are recorded in Bitcoin's blockchain and gain confirmations. **Lightning** is a payment network built on Bitcoin that can support fast, frequent payments. A Lightning payment may complete quickly or fail, and its wallet can still be custodial or self-custodial.


| Question | On-chain Bitcoin | Lightning |
| --- | --- | --- |
| Receiving information | Bitcoin address or on-chain payment request | Lightning invoice, offer, or supported Lightning address |
| Payment result | Broadcast first, then confirmations | Usually completes or fails quickly |
| Common use | Base-layer settlement or less frequent transfer | Fast, smaller, or frequent payment |
| Beginner checks | Correct address, network, amount, fee, and confirmation status | Correct invoice or request, amount, expiry, custody, and payment result |


Which path does the recipient expect? Confirm whether they have provided an on-chain address or a Lightning invoice or request before paying. An on-chain wallet cannot directly pay every Lightning invoice, and a Lightning wallet may not support every on-chain action. Some applications support both paths but may add fees or service dependencies. Detailed Lightning setup, channels, routing, and liquidity are Advanced learning; live local practice belongs in Module 4 when it is safe and appropriate.

Imagine that a prepared scenario offers both payment paths. Which request can the intended wallet use, and what would you check before approving it? The answer depends on the receiving request, the wallet, and the situation—not on a universal “best” path.
