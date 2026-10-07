# Exploring the Mempool

_Experiential, Discussion · Whole class · 30 min_

This activity exposes students to a free and open-source tool that does not require technical skills to use. It is useful for Bitcoiners at all levels, from beginner to experienced.

In this activity you walk students through basic Bitcoin information available at mempool.space.

Time permitting, you can show them other tools available, like the mining or Lightning features.

Artistic blocks are a way to make the discussion more interesting for your non-technical students. A few options are included in this guide.

#### Materials

* You will need a screen and access to the internet so you can project mempool.space for the entire class to watch and use together.
* Alternatively, you can direct students to access mempool.space on their personal phones or computers.

#### Preparation notes

Preparation time: 15 minutes.

Familiarize yourself with mempool.space. Ensure you can answer all the activity questions. For bonus discussions, explore the other sections of mempool.space (e.g., "mempool goggles," difficulty adjustment, hashrate, Lightning, etc.)

Another idea for bonus discussions is to find special blocks. Several examples are listed in this guide. It is important to test these before class because you may need to adjust settings within mempool.space, like toggling to "audit" view.

This activity takes about 30 minutes for a typical class.

Because mempool.space has added new tools and views, there are many ways to extend the class by diving deep into the details.

Conversely, you can shorten the duration of the activity by skipping those extra features.

#### Setup

If you are projecting using a screen, connect your device. Navigate to mempool.space and ensure it is displaying properly.

If students are using their own phones or computers, they can go to [https://mempool.space/](https://mempool.space/) or scan this QR.

#### Procedure

##### Step 1: Introduction to the Dashboard

Mempool.space has added many features since it was first created. The first thing you see at the top of the site, the blocks, is arguably the most critical to understand.

Ask questions to start the overview:

* "What's the difference between the green and purple blocks?"
* "What was the last block mined?"
* "How many transactions were in the block?"
* "How long ago was it added to the timechain?"
* "Who mined it?"

##### Step 2: Diving Deeper… Blockchain (All Blocks) One Block

Explain to students that by clicking on a block you can explore more details.

When you do this, students can see details: e.g., transaction fees paid to the miner, on the left-hand side.

On the right side is the block visualizer, which gives a sense of how much "space" each transaction takes up of the 4MB block limit. Larger cubes mean bigger transactions.

Quick breakdown:

* Cubes = Transactions: Each cube is one transaction, arranged in a grid based on their order in the block (x-y plane shows the sequence and packing).
* Height = Size in vB: Taller cubes = larger transactions, e.g., those with many inputs/outputs.
* Color = Fee Rate: Blues/greens = low fees, e.g., <1 sat/vB; yellows/oranges = medium, reds = high fees, e.g., >10+ sat/vB.
* Other Dimensions: Width/depth might be normalized or fixed for the grid, but height scales directly with vB to show relative sizes.

##### Step 3: Going Deeper… One Block (Many Transactions) One Transaction

Explain to students that by clicking on a transaction you can explore more details. If you have a specific transaction, you can also use the search tool.

The example below is block 800,000. You can further drill down by selecting a specific input, or specific output.

Questions for discussion:

* What is significant about block 800,000? (Trick question… it is not a halving! One epoch = 210,000 blocks.)
* How does this diagram of inputs and outputs relate to UTXO's?
* Why might someone overpay a transaction fee?

Remind students that a halving occurs every 210,000 blocks. A group of 210,000 blocks is also called an epoch. The 4th halving occurred at the 840,000th block. Go to the search tool and type "840000".

Questions:

* Why would this block have so many high transaction fees?
* What was the total block reward (subsidy + transaction fees) paid to the miner?

##### Step 4: Optional: Mempool Art

This section adds some fun to learning the tool. Miners can intentionally arrange transactions by their fee rates and/or sizes to form visual patterns using mempool.space's visualization tool.

You can navigate to these blocks by putting the block height in the search tool or by following the links.


| Block height | Miner | Date | Link |
| --- | --- | --- | --- |
| 836361 | MARA Pool | 26-Mar-24 | https://mempool.space/block/836361 |
| 879613 | MARA Pool | 17-Jan-25 | https://mempool.space/block/879613 |
| 880512 | SEC Pool | 24-Jan-25 | https://mempool.space/block/880512 |


What each block shows:

* Block 836361: A large, bold letter "M" (for Marathon) formed by clustering low-fee transactions into a pixelated shape across the block's transaction grid. This was one of the first high-profile examples of intentional block art.
* Block 879613: A pixelated portrait of Donald Trump (labeled "Trump 47"), created by precise transaction ordering. It cost over 1.2 BTC in fees to curate, highlighting the economic creativity in Bitcoin mining.
* Block 880512: A stylized image of Satoshi Nakamoto's photo alongside the Genesis Block declaration ("The Times 03/Jan/2009 Chancellor on brink of second bailout for banks"). Includes OP_RETURN messages emphasizing Bitcoin's origins; the pattern uses transaction clusters for contrast.

Note, you may have to adjust some of mempool.space's settings to see the images clearly.

First try toggling the "Audit" button.

If this does not work, consider asking a technical Bitcoiner or using an AI tool to troubleshoot.

##### Step 5: Optional: Exploring Other Areas

There are other tools that relate to earlier subjects: e.g., Lightning, mining, hashrate, difficulty adjustment, UTXO visualization, and others.

#### Key points

1. **Mempool** refers to the list of unconfirmed transactions maintained by each Bitcoin node, not a specific service or platform.
1. This is no single, universal mempool. Mempool.space is one of many.
1. [Mempool.space](https://mempool.space) is open-sourced and well known for being an easy-to-use visual block explorer. It provides real time data on unconfirmed transactions, fee rates, and other network activity.

#### Discussion questions

Wrap up the activity with a class discussion.

* Is there only one mempool?
* Who manages mempools?
* Can you have your own mempool?

Yes! When you run your own full Bitcoin node, you have a memory pool of unconfirmed transactions that the node has received, validated, and is holding until they are included in a block by miners. This is a core part of how nodes contribute to Bitcoin's decentralization and security. Some companies can and do have their own mempools too, e.g., MARA or Braiins. There are other mempools available for those who do not run a node, e.g., [https://blockstream.info](https://blockstream.info)

* What are potential benefits of having your own node? Hint: "Don't trust. Verify."

#### Notes

Mempool.space does much more than visualize blocks. Explore other parts of the Bitcoin ecosystem: e.g., Lightning, mining, the hash rate, pools, and block space "goggles".

#### Additional resources

* ["How to explore the Bitcoin Blockchain Mempool.space Tutorial" on the YouTube channel Crypto Trading Guides covers transaction fees, difficulty adjustment, checking addresses, checking transactions.](https://youtu.be/ZQZJI0R79sM?si=FkZf8WiH2xVvsBi4)
