# How Transations Work

## Alt text

A vertical seven-step flow showing a bitcoin payment from Alice to Bob: creating and signing a transaction, broadcasting it, node verification, the mempool, mining into a block, and the block being added to the blockchain as confirmations accumulate.

## Texts

### s1-label

Alice creates a transaction

### s1-desc

She specifies who receives the coins, how much, and a fee for miners.

### r-to

To

### r-to-v

Bob&#8217;s address

### r-amount

Amount

### r-fee

Network fee

### s2-label

She signs it with her private key

### s2-desc

The digital signature proves the coins are hers to spend.

### s3-label

Broadcast to the network

### s3-desc

The signed transaction is sent to nodes, which check that it follows the rules.

### chip-sig

Valid signature

### chip-bal

Enough bitcoin

### chip-rules

Follows the rules

### s4-label

It waits in the mempool

### s4-desc

Valid transactions wait in a pool of pending payments.

### s5-label

Miners include it in a block

### s5-desc

Miners pick transactions and compete to mine a block.

### s6-label

The block joins the blockchain

### s6-desc

Other nodes verify the block, then chain it on permanently.

### s7-label

Bob receives the bitcoin

### s7-desc

The transaction is now confirmed. Alice can&#8217;t spend those coins again, and Bob can spend what he received.

### foot

<strong>Each new block deepens the transaction.</strong> With every block added on top, reversing it becomes exponentially harder &#8212; that is what makes bitcoin final.
