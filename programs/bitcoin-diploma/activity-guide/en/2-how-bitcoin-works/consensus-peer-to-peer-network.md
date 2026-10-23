# 2.3 Consensus Building in a Peer-to-Peer Network

_Simulation_

Participants pass messages around a circle while selected participants alter or misinterpret an encrypted instruction. When the group acts on the message, the conflicting responses make the lack of consensus visible and lead to a discussion of cryptography, malicious actors, the Byzantine Generals’ Problem, and Bitcoin’s consensus layer.

#### Objectives

* Participants experience how shared verification and cryptography can help a peer-to-peer network reach consensus despite malicious participants.

#### Materials

* Messages with encrypted and unencrypted instructions for “attack” or “do not attack.”

#### Preparation notes

Select 3 or 4 participants as malicious [nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) before class and assign them a cryptographic puzzle as homework in the previous class.

#### Setup

Select an originator and form participants into a circle, separating malicious nodes.

#### Procedure

##### Step 1

Give the originator a note reading “ATTACK” and the number sequence “4-16-14-21-1-21-1-3-11-”. The originator passes it to the right.

##### Step 2

After all participants read the message, the originator says “Now.” Participants react simultaneously; “ATTACK” means taking a step forward.

##### Step 3

Observe that participants who interpreted the encrypted message correctly remain still while others act, revealing a lack of consensus.

#### Discussion questions

Why was consensus not achieved? How does this relate to the Byzantine Generals’ Problem and Bitcoin’s solution?

#### Notes

**Bitcoin Diploma assessment link:** May provide the individual-response context for `T2` / `C2`. Use the approved protocol and record an individual explanation of shared verification; otherwise, this activity is formative.
