# 2.11 Finite supply

Bitcoin's rules define a predictable [issuance schedule](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule) and a [maximum supply](https://curriculum.myfirstbitcoin.org/lexicon/en/#maximum-supply) of 21 million bitcoin (21,000,000 BTC). New bitcoin enter circulation through the [block subsidy](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) paid to [miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) who produce valid blocks.


<!-- card: definition -->
> **Definition – Halving**
>
> Every 210,000 blocks, the subsidy is cut in half. This event is called a [halving](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving). Because blocks are produced approximately every ten minutes on average, a [halving](https://curriculum.myfirstbitcoin.org/lexicon/en/#halving) occurs roughly every four years. The exact calendar date is not fixed.



| Halving year | Block height | Subsidy after halving |
| --- | --- | --- |
| 2012 | 210,000 | 25 BTC |
| 2016 | 420,000 | 12.5 BTC |
| 2020 | 630,000 | 6.25 BTC |
| 2024 | 840,000 | 3.125 BTC |
| Expected 2028 | 1,050,000 | 1.5625 BTC |


The subsidy began at 50 BTC per block. It falls by half in repeated steps until it becomes too small to continue. [Miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) also receive [transaction fees](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). Over time, fees are expected to become a more important part of [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) revenue.


<!-- micrographic: bitcoin-issuance-schedule-01 -->
[The block subsidy starts at 50 bitcoin and halves every 210,000 blocks, while total issued bitcoin rises toward the 21 million limit. Transaction fees are paid on top and are not new bitcoin; no price forecast is implied.](/micrographics/bitcoin-issuance-schedule-01/en.md)


The 21 million limit is enforced by [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node). If a [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) creates more bitcoin than the rules allow, [validating nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) reject the block. A software developer can write different code, but cannot force other people to run it.


<!-- card: dark -->
> **Fixed supply is a network rule, not a price promise**
>
> Bitcoin's supply rule is public, independently verifiable, and difficult for one party to change because [validating nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) enforce it. It is not a physical law: it remains effective while participants continue to enforce it. A limited supply does not guarantee a rising market [price](https://curriculum.myfirstbitcoin.org/lexicon/en/#price); [price](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) also depends on demand.
>
> Many [digital assets](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-asset) can claim a limited supply. Ask whether the limit is credible in practice, not only whether it is written in a document or displayed on a website.


**Spot question:** What are the advantages of Bitcoin having a limited supply? What would be the effect of increasing the supply of Bitcoin on [purchasing power](https://curriculum.myfirstbitcoin.org/lexicon/en/#purchasing-power)? Who would reject an increase in supply?


<!-- card: light -->
> Finite supply also does not mean every bitcoin is available for sale; some may be held long term or become inaccessible because keys were lost.


![](https://cdn.sanity.io/images/vje9ehw2/staging/04f25cd9a85bf20081aaefaf24cb8b6da98f5332-1536x1024.svg)
