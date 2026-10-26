# 3.14 On-chain and Lightning payments

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – On-chain and Lightning payments**
>
> [On-chain payments](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) are recorded in Bitcoin's [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) and gain [confirmations](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning is a payment network built on Bitcoin that can support fast, frequent payments. A Lightning payment may complete quickly or fail, and its wallet can still be custodial or self-custodial.



> **Dark – Payment path does not determine custody**
>
> On-chain and Lightning payments make different [trade-offs](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). A Lightning wallet can be custodial or self-custodial, and a fast successful payment does not prove that a service is suitable for larger balances or every situation.



<!-- micrographic: onchain-lightning-table-01 -->


Which path does the recipient expect? Confirm whether they have provided an on-chain address or a [Lightning invoice](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) or request before paying. An on-chain wallet cannot directly pay every [Lightning invoice](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), and a Lightning wallet may not support every on-chain action. Some applications support both paths but may add fees or service dependencies. Detailed Lightning setup, channels, routing, and [liquidity](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) are [Advanced Learning](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); live local practice belongs in **Module 4** when it is safe and appropriate.

Imagine that a prepared scenario offers both payment paths. Which request can the intended wallet use, and what would you check before approving it? The answer depends on the receiving request, the wallet, and the situation — not on a universal “best” path.

![The educator points to two different geometric payment paths on a board while the beginner and technical learners consider them.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
