# 2.7 Verification

_Presentation · Whole class, Small groups · 10 min_

Participants roll dice to model repeated attempts by miners to find a block-header hash that meets a target. After a successful roll, the class checks the stated result. The dice exercise is an analogy only. It does not reproduce hashing, targets, difficulty adjustment, block construction, or node validation in full.

#### Objectives

* Participants experience the difference between repeated attempts to find a model proof-of-work result and the quick check needed to verify it.

#### Materials

* At least six dice (D6).
* Optional: a printed record sheet.

#### Setup

Choose a model target, such as at least three dice showing one. Explain that in Bitcoin a miner repeatedly changes a candidate block header to seek a hash at or below the current target threshold. Nodes can check the resulting proof of work and the block's rules. The difficulty adjustment periodically changes the target; it is not the value a block must be below.

#### Procedure

##### Step 1: Try the model proof of work

Participants or a designated miner roll six dice repeatedly. Each roll represents one unsuccessful or successful attempt in the model. The goal is to meet the stated dice target.

##### Step 2: Change the model target

If the model target is too easy or too difficult for the time available, change it before the next round. Explain that a lower Bitcoin target makes a successful hash less likely, but the dice rule is only a teaching comparison.

##### Step 3: Verify the result

When the dice target is met, the class checks the number of ones and confirms that the stated result follows the model rule. Explain that Bitcoin nodes also check transaction and block rules, not only proof of work.

#### Key points

1. Mining involves repeated attempts to find a block-header hash that meets the current target.
1. A valid proof-of-work result is quick to check, but Bitcoin nodes also validate the block's other rules.
1. Difficulty adjustment changes the target periodically. It is not itself the proof-of-work threshold.

#### Discussion questions

1. Why did the model require repeated attempts?
1. What did the class check after the model target was met?
1. Which parts of Bitcoin validation are missing from the dice activity?

#### Notes

**Bitcoin Diploma assessment link:** May provide the individual-response context for `T2` / `C2`. Use the approved protocol, including the required role and rules explanation; otherwise, this activity is formative.

#### Additional resources

* [Bitcoin Developer Guide: Block Chain explains proof of work, targets, difficulty adjustment, and block validation.](https://developer.bitcoin.org/devguide/block_chain.html)
* [Calculator.net Dice Roller is an optional digital substitute for physical dice when modelling repeated mining attempts and quick verification.](https://www.calculator.net/dice-roller.html)
