# 3.4 Exploring the mempool

_Experiential · Whole class, Small groups, Pairs · 30 min_

Participants examine an educator-prepared public block, transaction, or screenshot. They identify confirmation status, inputs, outputs, fee information, and block information without using personal financial data. A live explorer can support the activity, but the printed route is equivalent and should be the default when connectivity, devices, or privacy are a concern.

#### Objectives

* Participants distinguish a node's mempool from a block explorer and interpret basic, deliberately public block or transaction information.

#### Materials

* A printed screenshot or worksheet for one deliberately public block or transaction.
* A board or paper for recording observations.
* Optional: a shared, educator-operated block explorer that has been checked immediately before class.

#### Setup

Choose one public example with no connection to learners. Label the example's source, date, and network. If a live explorer is used, prepare the same screenshot or worksheet as the no-internet route.

Explain that each node has its own mempool, which is the set of unconfirmed transactions that node has received and accepted under its current policy. A block explorer is a separate service that makes some network data easier to view. Neither an explorer nor its display is the Bitcoin network itself.

#### Procedure

##### Step 1: Identify the example

Give participants the prepared example. Ask them to find the transaction or block identifier, confirmation status, time shown, and any fee information. Ask what information the page does not prove about the people behind the transaction.

##### Step 2: Trace a transaction carefully

Ask participants to identify inputs and outputs. Explain that an input spends a prior output and that an output specifies conditions for later spending. Do not describe an address history as a person's complete financial history.

##### Step 3: Read a block summary

Use the prepared block example to identify its height, transaction count, and displayed fee information. Explain that Bitcoin limits block weight to 4,000,000 weight units. Do not treat a visual display or a simple megabyte label as a complete explanation of that limit.

##### Step 4: Compare mempool and explorer

Ask learners to sort these statements into “node mempool,” “block explorer,” or “both”: receives unconfirmed transactions, has a chosen display interface, may differ from another node, and can be used to view a prepared public example. Discuss why different nodes may not have exactly the same unconfirmed-transaction set.

##### Step 5: Discuss verification and privacy

Ask when an explorer is useful, what privacy trade-off a public query can create, and what a person would need to do to check Bitcoin's rules more independently. Keep the answer proportionate: a beginner can learn from a public example without being expected to run software or use a personal wallet.

#### Key points

1. A mempool is maintained by an individual node. There is no single universal mempool.
1. A block explorer is a third-party viewing tool, not the Bitcoin network or a substitute for independent validation.
1. Public ledger information can reveal links and patterns. Use only educator-prepared public examples in class.
1. Live interfaces, fees, and displayed network data change. Check them immediately before use.

#### Discussion questions

1. What is the difference between a node's mempool and a block explorer?
1. What did the prepared example show, and what could it not tell us?
1. Why might two nodes have different unconfirmed-transaction sets?
1. What privacy risks can arise when someone searches an address or transaction?

#### Notes

> **Callout – Use prepared public examples only**
>
> Do not search a learner's or another person's address, transaction, balance, or payment history on a public explorer. Public searches can expose financial information and reveal interest in that data to the explorer operator.


**Bitcoin Diploma assessment link:** May provide the individual-response context for `T3` / `C5`, especially on-chain confirmation and verification. Use the approved protocol and record individual evidence; otherwise, this activity is formative.

#### Additional resources

* [Bitcoin Developer Guide: Block Chain explains blocks, proof of work, and validation rules.](https://developer.bitcoin.org/devguide/block_chain.html)
* [Mempool.space is one possible block explorer. Treat its interface and live data as changing information that an educator must check before class.](https://mempool.space/)
