# 2.2 Consensus

_Role play · Whole class, Individual · 45 min_

Participants first track simple transfers, then compare a single designated record keeper with a group in which everyone keeps a copy of the same record. The educator introduces an entry that conflicts with the scenario's initial supply rule. Learners decide what the stated rules permit and compare the two recordkeeping arrangements.

#### Objectives

* Learners practice maintaining a shared record and compare one record keeper with independent checking against stated rules.
* Learners identify both the value and limits of a classroom analogy for Bitcoin consensus.

#### Materials

* Paper and pens for every participant
* Calculators, if useful
* A whiteboard, paper chart, or projected spreadsheet

#### Setup

Prepare the tables below. Explain the rules before the role-play: each transfer changes the record only if it is permitted by the stated starting balances and rules. In the final scenario, participants should compare their records after each step; agreement is not a vote on what they prefer, but a check of whether the same stated rules and earlier entries produce the same result.

#### Procedure

##### Step 1: Track a short record

Ask participants to track these transfers. They may work from memory first and then use paper.

1. TEACHER starts with 21 widgets; RED and BLUE start with none.
1. TEACHER pays 2 widgets to RED.
1. TEACHER pays 5 widgets to BLUE.
1. BLUE pays 1 widget to RED.
1. TEACHER pays 5 widgets to RED.


|  | TEACHER | RED | BLUE |
| --- | --- | --- | --- |
| Starting balance | 21 | 0 | 0 |
| After step 2 | 19 | 2 | 0 |
| After step 3 | 14 | 2 | 5 |
| After step 4 | 14 | 3 | 4 |
| After step 5 | 9 | 9 | 4 |


Ask learners how they checked their result and what information they needed.

##### Step 2: One designated record keeper

Tell the class that a BANKER begins with 2,100 play-money units and pays 200 units to each of six participants: RED, BLUE, PURPLE, BLACK, ORANGE, and GREEN. Designate one learner as the official record keeper.

1. Record the starting balance and the six payments. The BANKER has 900 units remaining.
1. BLUE pays GREEN 200 units. Update the record.
1. BANKER pays ORANGE 800 units. Update the record. The BANKER now has 100 units.
1. Propose a new entry: BANKER adds 600 units to BLUE's balance.

Ask the class: under the initial rules, is Step 4 a valid payment, a newly authorized issuance, an error, or something else? Who has the authority to answer in this scenario? Make clear that the answer depends on the rules you gave the record keeper; the activity has not shown that all single-record systems work the same way.

##### Step 3: Independent checking of the same rules

Repeat the scenario with every participant maintaining a record. After each entry, participants compare balances and state whether the entry follows the initial rules.

At the proposed addition of 600 units, ask participants to distinguish two questions:

1. Does the entry balance mathematically?
1. Does the entry follow the supply and authorization rules the group agreed at the start?

If the group rejects the entry under its initial rules, ask what would have to change for it to be accepted: the record, the rule, the authority to change the rule, or the group’s interpretation. This helps learners see that distributed copies do not themselves create a rule; participants must also apply and enforce common rules.

##### Connect the model to Bitcoin carefully

Explain that Bitcoin users may choose to run software that independently validates transactions and blocks against Bitcoin’s rules. Many users instead rely partly on wallets or other services, so it is inaccurate to say that every user keeps a full copy of the ledger.

At beginner level, describe the process as follows: transactions are broadcast; miners propose blocks using proof of work; and nodes independently accept or reject blocks according to their validation rules. Nodes converge on a history with the most accumulated proof of work. This is a useful comparison with the classroom exercise, but the exercise omits important technical and social details.

#### Key points

1. Consensus concerns shared rules, validation, and a history of entries; it is more specific than simply agreeing by a show of hands.
1. A single record keeper and independent record checking have different dependencies and trade-offs. Neither label alone proves fairness, security, or usefulness.
1. Bitcoin combines signatures, peer-to-peer communication, proof of work, block validation, and accumulated work. The classroom model represents only a small part of that system.
1. Decentralization can reduce dependence on a single rule enforcer, but influence, infrastructure, knowledge, and access are not equally distributed. Whether this matters most depends on the purpose and criteria being evaluated.
1. Bitcoin's rules and operation can be investigated; claims about its value are judgments that need stated criteria and evidence.

#### Discussion questions

1. What could the designated record keeper do well? What risks or dependencies could arise?
1. What did independent checking reveal in the final scenario? What did it not solve?
1. Which assumptions in the classroom model differ from Bitcoin’s actual network?
1. What evidence would you need before claiming that a system is decentralized, secure, scarce, or valuable?
1. Which criteria would matter when comparing a centralized payment system and Bitcoin for a particular person or community?

**Optional money-properties comparison**

If learners compare money properties, ask them to state the criterion and evidence for each entry rather than directing them toward a preferred answer. A supply rule is one input to scarcity; credibility, enforcement, verification, history, and demand are separate questions.

#### Notes

> **This is a simplified classroom model**

> The activity represents a shared record and rule checking. It does not reproduce Bitcoin's digital signatures, peer-to-peer message propagation, mining competition, proof-of-work difficulty, forks, incentives, or security assumptions. It does not show that one form of coordination is always better than another.

Allow time for calculations and for disagreement about the scenario's rules. Keep the discussion focused on the difference between an observation from the role-play, a technical fact that can be checked, and a value judgment that requires criteria.

**Bitcoin Diploma assessment link:** This activity may provide formative practice for `T2` / `C2`. Use the approved protocol and record individual evidence for copying, verification, rules, and roles if it is used for assessment.

**Educator background and source notes**

* [Satoshi Nakamoto, ,_Bitcoin: A Peer-to-Peer Electronic Cash System_](https://bitcoin.org/bitcoin.pdf), sections 2–5, describes the proposed transaction, proof-of-work, and network process.
* [Bitcoin Developer Guide: Operating Modes](https://developer.bitcoin.org/devguide/operating_modes.html) distinguishes full validation from less independent ways of checking payments.
* [Bitcoin Developer Guide: P2P Network](https://developer.bitcoin.org/devguide/p2p_network.html) describes peer-to-peer message exchange.

These sources support the technical background only. They do not establish a universal historical claim about leaders, a causal claim about monetary systems, or a conclusion about Bitcoin’s value.
