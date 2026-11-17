# Changelog

What changed in each edition of the My First Bitcoin curriculum, newest first. It is written for **translators** working from this repository and for **educators** teaching from it.

Each edition has a Git tag (`26.04`, `26.10`…), so you can compare any two editions yourself, for example `git diff 26.04 26.10 -- programs/introduction-to-bitcoin`. Past editions as PDFs stay on the [Archive page](https://curriculum.myfirstbitcoin.org/archive/).

Each entry is drafted with AI by comparing the edition with the previous one, then reviewed by the Education team.

---

## 26.10

Released on 26 October 2026, compared with 26.04. The `26.10` tag points at this repository on 13 November 2026, which includes the corrections made after the release.

### At a glance

- **The Bitcoin Diploma was rebuilt.** Eleven chapters became four modules (Understanding money, How Bitcoin works, Using Bitcoin safely, Bitcoin in your community), with a review at the end of each module, a short quiz after Modules 1 to 3, seven assessed competencies and a practical check observed by an educator.
- **One program, several books.** The Bitcoin Diploma now has a Student Guide, an Educator Guide, an Educator Quick Start, an Activity Guide and slides. The separate "Educator Guide" program of 26.04 is now the Diploma's Educator Guide.
- **A more neutral, safety-first approach.** Texts explain trade-offs and Bitcoin's own risks instead of arguing a case, name no wallets or other products, and never ask learners to buy bitcoin or use their own funds.
- **Local adaptation is built in.** Module 4 is chosen by the educator for the learners' own community.
- **Bitcoin for Juniors** keeps its activities in a single lesson format, with a new Parent Guide and an overview per chapter. **Introduction to Bitcoin** keeps its six questions, rewritten for balance, and gains a slide deck.
- **Bitcoin for Organizations was retired.** Its 26.04 edition stays on the Archive page and under the `26.04` tag.

### For translators

- **New folder layout.** Files moved from `programs/<program>/<language>/` to `programs/<program>/<book>/<language>/`, for example `programs/bitcoin-diploma/student-guide/en/`. The 26.04 Markdown stays under the [`26.04` tag](https://github.com/MyFirstBitcoin/mfb-curriculum/tree/26.04).
- **Most of the Diploma text is new.** A 26.04 translation cannot be carried over file by file. Use the [section-by-section tables](#2610-section-by-section) to find which 26.04 file a 26.10 section draws on: rows marked "Mostly unchanged" or "Rewritten, same ideas" are where earlier work is most reusable. Bitcoin for Juniors changed the least: same activities, new format.
- **Some file names do not match their titles or order:**
  - Bitcoin for Juniors, chapter 1: the sections now run Going, What is value, Ship Rekt, Worth It (1.2 to 1.5), and some files keep their old number (`1-ship-rekt.md` is section 1.4).
  - Bitcoin Diploma Educator Guide: `9-module-3.../18-acquiring-and-exchanging-as-pathway-awareness.md` holds 9.3 (competencies), `24-module-3-evidence-panel.md` holds 9.19 (acquiring and exchanging), `16-after-the-course/3-offer-the-optional-four-week-recall.md` holds 16.4 (testimonials), and the back-matter files `appendix-g-...` and `appendix-h-...` hold "Continue learning" and "Help improve".
  Follow the title and number inside the file, not the file name.

### For educators

- **The Bitcoin Diploma takes at least eight hours**, over four modules. The Activity Guide holds the classroom games, discussions and videos that used to sit inside the chapters.
- **Assessment is new.** Learners show seven competencies (C1 to C7, five theory and two practical), each recorded as "Yes" or "Not yet", with reassessment possible. These are not numerical grades.
- **You issue the certificate.** A completion certificate is certification by the named educator or organization; My First Bitcoin does not centrally evaluate learners.
- **Practice is safe by default:** training wallets, simulations and printed screens, no real secrets in class, and no learner ever needs to buy bitcoin or own a device.
- **New to the Diploma?** Start with the Educator Quick Start, then the full Educator Guide.
- 26.04 materials stay on the [Archive page](https://curriculum.myfirstbitcoin.org/archive/) if you are part-way through teaching them.

### Bitcoin Diploma: Student Guide and Activity Guide

- **Eleven chapters became four modules.** The 26.04 Diploma had ten numbered chapters plus front and back matter. The 26.10 Student Guide has four modules that follow one arc: Problem (Understanding Money), Solution (How Bitcoin Works), Action (Using Bitcoin Safely) and Connect (Bitcoin in Your Community). Old chapters 1 to 4 are merged into Module 1, old chapters 5, 8 and 9 into Module 2, old chapters 6 and 7 into Module 3, and old chapter 10 is mostly dropped. Module 4 is new.
- **Activities moved out of the student text.** Classroom games, discussions and videos that sat inside 26.04 chapters (barter game, auction, fractional reserve, consensus, transactions in action, mempool, Lightning relay race, final discussion) now live in a separate **Activity Guide** with objectives, materials, steps, key points and discussion questions. Several new activities and videos were added there.
- **New learning and assessment elements.** Each of Modules 1 to 3 ends with a short multiple-choice quiz ("quick check"), and every module ends with a review section with key takeaways and a reflection question. The front matter now sets out seven competencies (C1 to C7), explains how an educator assesses them, and Module 3 adds a practical competency check observed by an educator. The back matter explains the two certificate types and who issues them.
- **New topics.** Why money exists, subjective value, liquidity versus solvency risk, why the US dollar is a reserve currency, alternatives for saving (metals, real estate, stocks), digital scarcity, satoshis and unit bias, Bitcoin compared with stablecoins and other digital assets, learning versus trading or promotion, address checks, hot and cold wallets, scam red flags, block explorers, KYC trade-offs, on-ramps and off-ramps, and merchant and community use cases.
- **Removed.** The UTXO model, hashing detail, the "philosophy" and "benefits" (hyperbitcoinization) sections of old chapter 10, global debt figures, "who controls the fiat system", named tools such as BTCPay Server and BTCMap, gift cards, the case studies, the long reading list, the per-module key concepts and the glossary (the new text links terms to an online lexicon instead).
- **Shift in tone and approach.** The 26.04 text often argued a position (fiat as a "trust game" run by "puppeteers", Bitcoin as a "revolution"). The 26.10 text explains trade-offs, separates facts from judgments, names Bitcoin's own risks (volatility, irreversible payments, key loss) and says plainly that the course is not financial advice. Practical work is safety-first: learners never need to buy bitcoin, use personal funds or own a device, and practice uses simulations or training wallets.
- **Local adaptation is built in.** Module 4 is curated by the educator for the learners' community, with worksheets for local needs, tools, pathways and scenarios, instead of a fixed set of global examples.

**Module 1 Understanding money.** Covers why money exists, its functions and properties, barter, scarcity and value, a short history of money, fiat money, fractional reserve banking, inflation, the US dollar as reserve currency, saving alternatives and CBDCs. It merges old chapters 1 to 4 (and the CBDC section from chapter 10) into one shorter, more neutral module, with the stories and polemic replaced by definitions, local exercises and balanced risk language.

**Module 2 How Bitcoin works.** Covers why Bitcoin was created, the Cypherpunks and early digital money, the double-spend problem, digital scarcity, the blockchain, decentralization, signatures, users, nodes and miners, proof of work, the 21 million supply, sats, Bitcoin as sound money, and how Bitcoin differs from stablecoins and other assets. It replaces old chapters 5, 8 and 9 (and the end of chapter 4), keeps the technical ideas at a beginner level, drops UTXOs and most hashing detail, and adds the trade-offs and limits of each claim.

**Module 3 Using Bitcoin safely.** Covers wallets, addresses, keys, seed phrases, custody, hot and cold wallets, recovery practice, receiving, sending, verification, a safety checklist, acquiring bitcoin, and on-chain versus Lightning, ending with an observed competency check. It replaces old chapters 6 and 7, turns step-by-step "set up your wallet" instructions into guided safety practice with training materials, and removes the expectation that learners use real funds.

**Module 4 Bitcoin in your community.** Covers the educator-chosen local module, workshops, local tools, Lightning payments, daily-life uses, local scenarios, on-ramps and off-ramps, KYC trade-offs, circular economies, merchant and community use cases, and resource maps. It is mostly new; it partly replaces old 7.5 (buying coffee and groceries, circular economies) but asks learners to start from a local need and compare Bitcoin with a realistic alternative, rather than presenting named tools and success stories.

### Bitcoin Diploma: Educator Guide and Educator Quick Start

- **The Educator Guide is now part of the Bitcoin Diploma.** In 26.04 it was a separate program (`programs/educator-guide/`) with one lesson plan per Diploma chapter. In 26.10 it lives inside the Bitcoin Diploma (`programs/bitcoin-diploma/educator-guide/`) and follows the new four-module course: Understanding Money, How Bitcoin Works, Using Bitcoin Safely, Bitcoin in Your Community.
- **From ten 90-minute lesson scripts to one teaching handbook.** The ten chapter guides become four module companions. Around them sit new general parts: the educator's role, what stays fixed, a safe learning culture, planning, facilitation methods, safe practical teaching, localization, activities, visuals, closing the course and after the course. The course is now at least eight hours in total, with no upper limit.
- **Assessment is new.** The old guide had learning objectives and wrap-up questions, but no assessment. 26.10 adds seven assessed competencies (C1 to C7), sample tasks, a "Yes" or "Not yet" result per competency, reassessment, and two certificate types (participation and completion). The educator assesses and issues the certificate; My First Bitcoin does not.
- **Safe practical teaching is new.** Training wallets, simulations and printed screens are the default. The guide adds a demonstration safety protocol, universal stop conditions, a "no real secrets in class" rule, and rules for shared devices. Learners are never asked to buy bitcoin or show a seed phrase.
- **Localization and Module 4 are new.** Educators check local facts (banking, inflation, CBDC status, tools, law) and record the source and date. Module 4 is a required local task that the educator chooses and checks with a seven-step builder and a readiness gate. A translation workflow and delivery advice (in person, online, self-paced, mobile only, large groups) are also new.
- **After the course is new.** Records and reassessment, learner feedback and the exit survey, an educator self-review, educator testimonials, and keeping local content up to date.
- **What was dropped.** Most technical depth (hashing, the UTXO model, the mempool, difficulty adjustment details, Lightning channels and routing) moves to Advanced Learning. The Bitcoin philosophy and "benefits of Bitcoin" sections, the Cypherpunks story, named tools (for example Blue Wallet, Muun, BTCPay Server, BTCMap, mempool.space) and country case studies are gone. The per-chapter "Online Teaching", "What Good Looks Like" and "If Students Struggle" blocks are replaced by general sections.
- **Change of approach.** 26.04 often argued a case (fiat is broken, CBDCs extend control, Bitcoin brings freedom). 26.10 is neutral and evidence-based: claims need evidence and a trade-off, slogans must be unpacked, CBDC designs differ, and a learner can pass while staying critical of Bitcoin. Module 4 may conclude that Bitcoin is not the right tool for a local need.

**Educator Quick Start.** A new short companion (seven pages) for a person preparing to teach the Bitcoin Diploma for the first time. It gives the learning path, what stays fixed, safety rules, how assessment works and a first-course checklist, then points to the full Educator Guide for detail.

### Other programs

#### Bitcoin for Juniors

- **New place, new name for the folder.** The English files moved from `programs/bitcoin-for-juniors/en/` to `programs/bitcoin-for-juniors/educator-guide/en/`. The program is now one educator guide.
- **New pages.** Each of the six chapters now opens with an **Overview** page (foreword, overarching objectives, what to look forward to, why it matters for Bitcoin). A new **Parent Guide** was added to the front matter.
- **One lesson format for every activity.** Each activity now starts with one facts line (activity types, participation, duration), then: Objectives, Materials, Setup, Procedure in numbered steps, Key points, Discussion questions, Notes and a new **Suggested assignment** (a small, non-graded task to do at home with a parent or caregiver). "Equipment" is merged into Materials, "Opening" becomes Setup, "Follow-up" becomes Discussion questions, "Close" becomes Wrap up. The procedures are shorter and easier to scan; the activities themselves are the same.
- **Glossary links.** Key words (value, price, scarcity, barter, Proof of Work, privacy, hash, halving and others) now link to the My First Bitcoin lexicon at curriculum.myfirstbitcoin.org.
- **Removed.** The 18 files in the old `resources/` folder are not carried over. They were written for a 10-chapter adult program (wallets, fees, Lightning, mining economics), not for this 6-chapter children's program.

#### Introduction to Bitcoin

- **New place.** The six sections moved from `programs/introduction-to-bitcoin/en/` to `programs/introduction-to-bitcoin/student-guide/en/`. Same six questions, same order.
- **Rewritten for balance and accuracy.** Strong claims are softened and made checkable (for example "Fiat money is broken by design" becomes "Money depends on rules and trust"). Unsourced figures (dollar losing "over 96%" since 1913, the cheeseburger prices) and the Henry Ford quote are gone. Bitcoin's trade-offs (price swings, permanent mistakes, personal responsibility) are now stated.
- **More active learning.** Learners now start with five questions and come back to them at the end, practise telling fact from opinion, and do a "purchasing-power check" in their own community.
- **Safety first, no product names.** The wallet tables (seven named wallets) are replaced by a checklist for judging any wallet, a custodial vs self-custodial table, three safety rules and a scam warning. The guide now says that My First Bitcoin does not recommend specific wallets.
- **New slide deck.** A presenter deck now sits next to the student guide in `programs/introduction-to-bitcoin/slides/en/`.

#### Bitcoin for Organizations

- **Retired on 2026-10-15.** The program has no folder in 26.10.
- Its 26.04 PDFs stay available at https://curriculum.myfirstbitcoin.org/archive/ and its Markdown stays in the repository under the `26.04` tag.

## 26.10 section by section

How to read the tables: **Comes from (26.04)** names the 26.04 file a 26.10 section draws on, or **New** when nothing in 26.04 covered it. **What changed** is a short note based on reading both texts. "Partly" means only some of the 26.04 text was reused.

### Bitcoin Diploma: Student Guide and Activity Guide

#### Front matter

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| Welcome to the Bitcoin Diploma | `0-front-matter/1-the-bitcoin-diploma-story` + `0-front-matter/2-foreword` | Rewritten and expanded: about us, mission, values, why the Diploma exists; history kept but without the old figures |
| How the Bitcoin Diploma works | Partly `README` (objectives, audience, no prior knowledge) | New: competencies C1 to C7, assessment, discussion and privacy rules, materials, safety rules, four-module arc |
| README (Student Guide) | `README` | Replaced by a generated structure table; objectives moved to front matter |

#### Module 1 Understanding money

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 1.1 Opening questions about money | `1-what-is-money/0-introduction` + `1-what-is-money/1-discussions-about-money` | Shorter; same opening questions (one changed to purchasing power); adds fact versus opinion; group work and candy exercise moved to Activity Guide |
| 1.2 Why money exists | `1-what-is-money/2-definition-of-money` | Rewritten: specialization and coordination; new definition of money |
| 1.3 Functions and properties of money | `1-what-is-money/3-functions-of-money` + `1-what-is-money/4-properties-of-money` | Merged from two sections, shorter; adds verifiability and "sound money is a judgment"; price table and scoring exercise dropped |
| 1.4 Barter and the double coincidence of wants | `2-the-history-of-money/1-from-barter-to-modern-currency` (barter part) | Rewritten with a new example (Amina, Luis, Mei); adds other problems of barter |
| 1.5 Scarcity, value, and exchange | `1-what-is-money/6-the-psychology-of-money` | Much shorter; desert story replaced by a water example; adds subjective value; keeps opportunity cost and time preference |
| 1.6 Beginner monetary history from barter to digital money | `2-the-history-of-money/1-from-barter-to-modern-currency` + `1-what-is-money/5-types-of-money` + `2-the-history-of-money/2-digital-currency` | Merged and much shorter; neutral list of stages; adds debasement and bank deposits as claims; "you" story and "paper to plastic" dropped |
| 1.7 Fiat money | `3-what-is-fiat-money/1-brief-history-of-fiat-money` + `3-what-is-fiat-money/2-the-fiat-system` | Rewritten, much shorter and more balanced; "who controls the fiat system" and policy lists dropped; new local payment exercise |
| 1.8 Fractional reserve banking | `3-what-is-fiat-money/2-the-fiat-system` (fractional reserve part) | Rewritten: loans create deposits, liquidity versus solvency risk; bikes story, boom and bust, bailouts dropped |
| 1.9 Inflation and purchasing power | `4-how-problems-lead-to-solutions/1-money-buys-less` + `4-how-problems-lead-to-solutions/1-the-global-debt-burden-and-social-inequality` | Rewritten, shorter; separates price inflation from monetary expansion; Alex, Bob, Charlie and Jaime stories dropped; local price check added |
| 1.10 Why the US dollar is a world reserve currency | Partly `2-the-history-of-money/1-from-barter-to-modern-currency` + `3-what-is-fiat-money/0-introduction` | Partly: Bretton Woods and 1971 carried over; new explanation of why the dollar became the reserve currency |
| 1.11 Alternatives for saving and holding value | **New** | New: metals, real estate, stocks and their trade-offs; tax note |
| 1.12 Central Bank Digital Currencies (CBDCs) | `3-what-is-fiat-money/3-central-bank-digital-currencies` + `10-what-future-can-bitcoin-build/1-what-are-central-bank-digital-currencies-cbdcs` | Merged from two sections; more neutral; design questions replace tracker figures and scenarios |
| 1.13 Review: How can money break? | **New** | New: module review, key takeaways, reflection |
| Quiz: Understanding Money quick check | **New** | New: four multiple-choice questions |

#### Module 2 How Bitcoin works

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 2.1 Why Bitcoin was created | Partly `4-how-problems-lead-to-solutions/3-the-quest-for-a-decentralized-currency` (problems of central systems) | Mostly new: risks of intermediaries, the copying problem, Bitcoin / bitcoin / BTC naming |
| 2.2 The search for digital and decentralized money | `4-how-problems-lead-to-solutions/3-the-quest-for-a-decentralized-currency` (Cypherpunks) | Shorter; names, manifesto and PGP dropped; adds a cryptography definition |
| 2.3 Early digital-money attempts and the double-spend problem | `4-how-problems-lead-to-solutions/3-the-quest-for-a-decentralized-currency` (digital cash) + `5-what-is-bitcoin/0-the-creation-of-bitcoin` (whitepaper) | Expanded: DigiCash, Hashcash, Bit Gold, b-money, RPoW, BitTorrent; double spending defined; whitepaper's five parts |
| 2.4 Digital scarcity and independently verifiable supply | **New** | New: digital scarcity and supply you can check |
| 2.5 The Blockchain: Bitcoin's Public Ledger | Partly `8-how-bitcoin-works/0-introduction` + `9-how-does-bitcoin-mining-work/1-bitcoin-nodes-and-miners` (linked blocks) | Short new definition plus a note on how nodes reach consensus |
| 2.6 Decentralization | `4-how-problems-lead-to-solutions/3-the-quest-for-a-decentralized-currency` + `5-what-is-bitcoin/1-how-does-bitcoin-work` | Rewritten, more balanced: decentralization is not equal influence; costs named; "symphony" dropped |
| 2.7 Digital signatures | `8-how-bitcoin-works/1-security-through-cryptography` (key part) | Much shorter; links to self-custody |
| 2.8 Peer-to-peer transfer | Partly `5-what-is-bitcoin/2-bitcoin-as-sound-digital-money` (peer-to-peer principle) + `6-how-to-use-bitcoin/4-receiving-and-sending-transactions` | Mostly new: what peer-to-peer means; services remain optional |
| 2.9 Users, nodes, and miners | `5-what-is-bitcoin/1-how-does-bitcoin-work` (players) + `9-how-does-bitcoin-mining-work/0-introduction` + `9-how-does-bitcoin-mining-work/1-bitcoin-nodes-and-miners` | Rewritten, shorter; "projects" role dropped; adds how the roles limit each other |
| 2.10 Proof of work | `9-how-does-bitcoin-mining-work/1-bitcoin-nodes-and-miners` + `8-how-bitcoin-works/1-security-through-cryptography` (hash function) | Rewritten, shorter; adds confirmations and the energy debate |
| 2.11 Finite supply | `9-how-does-bitcoin-mining-work/1-bitcoin-nodes-and-miners` (halvings) + `5-what-is-bitcoin/1-how-does-bitcoin-work` (21 million rule) | Rewritten; halving table by block height; adds "a network rule, not a price promise" |
| 2.12 Satoshis and unit bias | Partly `7-using-bitcoin-in-daily-life/0-introduction` (satoshi box) | Mostly new: unit bias and converting BTC to sats |
| 2.13 Bitcoin as sound digital money | `5-what-is-bitcoin/2-bitcoin-as-sound-digital-money` | Rewritten, more balanced: benefits and trade-offs; "digital gold" stages, gold and fiat table and large-transfer example dropped |
| 2.14 Bitcoin, stablecoins, and other crypto-assets | Partly `1-what-is-money/5-types-of-money` (one-line definitions) | New: comparison of Bitcoin, stablecoins and other assets, with their risks |
| 2.15 Learning and responsible use are not trading or promotion | **New** | New: the line between learning and speculation or promotion |
| 2.16 Bitcoin origin timeline | `5-what-is-bitcoin/0-the-creation-of-bitcoin` | Rewritten as a dated timeline with source links; adds first transaction and Pizza Day; less heroic tone |
| 2.17 Empowerment, risk, and responsibility | `5-what-is-bitcoin/2-bitcoin-as-sound-digital-money` (personal responsibility part) | Shorter, softer: responsibility includes asking for help |
| 2.18 Review: How Does Bitcoin Address Monetary Flaws? | **New** | New: module review, key takeaways, reflection |
| Quiz: How Bitcoin Works quick check | **New** | New: four multiple-choice questions |

#### Module 3 Using Bitcoin safely

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 3.1 Using Bitcoin Safely | `6-how-to-use-bitcoin/0-introduction` | Rewritten: three safety rules; no personal funds needed |
| 3.2 Wallets | `6-how-to-use-bitcoin/2-introduction-to-wallets` | Rewritten, shorter; adds learning wallet versus personal wallet; open source kept as one factor |
| 3.3 Addresses | Partly `6-how-to-use-bitcoin/4-receiving-and-sending-transactions` (receiving note) | Mostly new: where an address comes from, checks after copying, address reuse, Lightning invoice |
| 3.4 Keys | `6-how-to-use-bitcoin/2-introduction-to-wallets` + `8-how-bitcoin-works/1-security-through-cryptography` (key part) | Rewritten around what to share and what to keep secret |
| 3.5 Seed phrases | `6-how-to-use-bitcoin/3-setting-up-a-mobile-wallet` + `7-using-bitcoin-in-daily-life/3-setting-up-a-bitcoin-lightning-wallet` | Expanded: storage rules and what to do if a phrase is exposed |
| 3.6 Custodial and non-custodial use | `6-how-to-use-bitcoin/2-introduction-to-wallets` + `7-using-bitcoin-in-daily-life/2-types-of-lightning-wallets` | Rewritten, more neutral; adds "a custodial balance is a promise" |
| 3.7 Hot and cold wallets | `6-how-to-use-bitcoin/2-introduction-to-wallets` (wallet types table) | Rewritten: hot, cold and hardware definitions replace the four-type table |
| 3.8 Wallet recovery and seed phrase testing | `6-how-to-use-bitcoin/3-setting-up-a-mobile-wallet` (restore option) | Rewritten: recovery practice only with training materials |
| 3.9 Receiving bitcoin | `6-how-to-use-bitcoin/4-receiving-and-sending-transactions` (receiving) | Rewritten as guided safety practice; "sent" message is not proof |
| 3.10 Sending bitcoin | `6-how-to-use-bitcoin/4-receiving-and-sending-transactions` (sending) | Rewritten as a pre-send checklist; fee explained by data, not amount |
| 3.11 Verification, block explorers, and irreversible transactions | `6-how-to-use-bitcoin/5-don-t-trust-verify` + partly `9-how-does-bitcoin-mining-work/2-what-is-the-mempool` | Mostly new: transaction IDs, explorers and their privacy cost, confirmation nuance |
| 3.12 Safety checklist | Partly `6-how-to-use-bitcoin/5-don-t-trust-verify` | New: scam red flags and a safe response |
| 3.13 Acquiring and exchanging bitcoin | `6-how-to-use-bitcoin/1-acquiring-bitcoin` | Rewritten, neutral; adds ATMs and a KYC definition; "exchanges are like banks" dropped |
| 3.14 On-chain and Lightning payments | `7-using-bitcoin-in-daily-life/1-the-lightning-network` + `7-using-bitcoin-in-daily-life/0-introduction` | Much shorter; café tab analogy and comparison tables dropped; channels moved to Advanced Learning |
| 3.15 Practical competency check observed by an educator | **New** | New: observed practical check |
| 3.16 Review: What does self-custody responsibility mean? | **New** | New: module review, key takeaways, reflection |
| Quiz: Using Bitcoin Safely quick check | **New** | New: four multiple-choice questions |

#### Module 4 Bitcoin in your community

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 4.1 Bitcoin in Your Community | **New** | New: the Connect stage and a local focus worksheet |
| 4.2 Your local Module 4 | **New** | New: educator-chosen local module and example questions |
| 4.3 Practical workshops and demonstrations | **New** | New: presentation, practice, production; live demo safety checks |
| 4.4 Local Bitcoin tools and resources | Partly `7-using-bitcoin-in-daily-life/5-buying-coffee-and-groceries-with-bitcoin` (named tools) | New: tool checklist; named tools no longer listed |
| 4.5 Lightning payments | `7-using-bitcoin-in-daily-life/4-sending-and-receiving-lightning-transactions` + partly `7-using-bitcoin-in-daily-life/3-setting-up-a-bitcoin-lightning-wallet` | Rewritten as a demonstration checklist; adds invoices and Lightning addresses; Marcia and Mina examples dropped |
| 4.6 Daily-life Bitcoin use | Partly `7-using-bitcoin-in-daily-life/5-buying-coffee-and-groceries-with-bitcoin` | New: seven uses of Bitcoin as money and three questions to ask |
| 4.7 Local spending and receiving scenarios | Partly `7-using-bitcoin-in-daily-life/5-buying-coffee-and-groceries-with-bitcoin` | New: five scenarios with questions |
| 4.8 Local on-ramp and off-ramp pathways | Partly `6-how-to-use-bitcoin/1-acquiring-bitcoin` | New: compare the full route; in-person safety |
| 4.9 KYC and no-KYC trade-offs | Partly `6-how-to-use-bitcoin/1-acquiring-bitcoin` (identity risk) | New: KYC versus no-KYC comparison |
| 4.10 Circular economies | `7-using-bitcoin-in-daily-life/5-buying-coffee-and-groceries-with-bitcoin` (circular economies) | Rewritten: historic examples dropped; adds mapping a local cycle and failure risks |
| 4.11 Merchant or community use cases | Partly `7-using-bitcoin-in-daily-life/5-buying-coffee-and-groceries-with-bitcoin` (payment processing) | New: merchant decisions and community custody |
| 4.12 Local resource maps and community discovery | Partly `7-using-bitcoin-in-daily-life/5-buying-coffee-and-groceries-with-bitcoin` (map) | Short; points to the Resources Hub; meetup safety |
| 4.13 Review: Connect this to your community | **New** | New: module review, key takeaways, reflection |

#### Back matter

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| Optional next steps | Partly `11-back-matter/2-additional-resources` + `10-what-future-can-bitcoin-build/4-an-empowered-future` (next step) | New: surveys and forms, safety reminder, adapting the curriculum, certificate types, donations; reading list removed |

#### Activity Guide

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| README (Activity Guide) | **New** | New: structure table and editing notes |
| How to use this guide | **New** | New: choosing activities and safety rules |
| 1.1 Why Do We Need Money? | `1-what-is-money/1-discussions-about-money` | Expanded: barter and play-money rounds before the five questions |
| 1.2 What Is Money? | `1-what-is-money/1-discussions-about-money` (candy and bill discussion) | Moved from the student text, same activity |
| 1.3 Barter Game | **New** | New in the text (26.04 key concepts named a barter game, no instructions) |
| 1.4 Iterative Barter Game | `2-the-history-of-money/0-introduction` | Full instructions added; key points unchanged |
| 1.5 Auction | `4-how-problems-lead-to-solutions/1-money-buys-less` | Rewritten: stresses model limits; claims about manipulated CPI dropped |
| 1.6 Time Preference | `1-what-is-money/6-the-psychology-of-money` (candy activity) | Moved, same steps and questions |
| 1.7 Alternative Time Preference Questions for Discussion | **New** | New discussion |
| 1.8 Bank balance sheets and lending | `3-what-is-fiat-money/2-the-fiat-system` (fractional reserve activity) | Rewritten as a balance-sheet model; moral hazard points dropped |
| 1.9 Consequences of the Fiat System | `4-how-problems-lead-to-solutions/1-the-global-debt-burden-and-social-inequality` (discussion) | Moved, same questions |
| 1.10 Watch: How Money & Banking Work | **New** | New video |
| 2.1 Watch: Explain Bitcoin to Complete Beginners | **New** | New video |
| 2.2 Consensus | `5-what-is-bitcoin/1-how-does-bitcoin-work` (consensus activity) | Full instructions; more careful key points |
| 2.3 Consensus Building in a Peer-to-Peer Network | **New** | New in the text (26.04 key concepts named it, no instructions) |
| 2.4 Bitcoin transactions in action | `6-how-to-use-bitcoin/4-receiving-and-sending-transactions` (activity) | Rewritten as a role play with dice for proof of work |
| 2.5 Generate SHA-256 Hash | `8-how-bitcoin-works/1-security-through-cryptography` (activity) | Same activity; uses a My First Bitcoin tool; safety note added |
| 2.6 Watch: Blockchain 101 – A Visual Demo | **New** | New video |
| 2.7 Verification | **New** | New: dice model of mining and checking |
| 2.8 Watch: How Bitcoin Works under the Hood | `8-how-bitcoin-works/2-the-utxo-model` (video) | Video moved into an activity |
| 2.9 Watch: Why Every Bitcoiner Should Run Their Own Node | **New** | New video |
| 2.10 Watch: How To Setup Bitcoin Core | `9-how-does-bitcoin-mining-work/3-how-transactions-work` (video) | Video moved; no installation required |
| 2.11 Is Bitcoin Sound Money? | `5-what-is-bitcoin/2-bitcoin-as-sound-digital-money` + `1-what-is-money/4-properties-of-money` (comparison table) | Moved; some items in the table changed |
| 3.1 Evaluate Bitcoin Wallets | `6-how-to-use-bitcoin/2-introduction-to-wallets` (activity) | Rewritten: criteria-based, no single recommendation |
| 3.2 Creating Your First Bitcoin Wallet | `6-how-to-use-bitcoin/3-setting-up-a-mobile-wallet` | Rewritten as a no-funds simulation; no real seed phrase |
| 3.3 Transactions in action | Partly `6-how-to-use-bitcoin/4-receiving-and-sending-transactions` (activity) | New version: a small real on-chain payment with checks |
| 3.4 Exploring the mempool | `9-how-does-bitcoin-mining-work/2-what-is-the-mempool` (activity) | Rewritten: prepared public examples, privacy |
| 3.5 Watch: Future of Bitcoin: Lightning Network | **New** | New video |
| 3.6 Lightning payment relay | `7-using-bitcoin-in-daily-life/4-sending-and-receiving-lightning-transactions` (relay race) | Rewritten with checks and stop conditions |
| 4.1 Watch: Bitcoin Is Generational Wealth | `10-what-future-can-bitcoin-build/4-an-empowered-future` (video) | Same video; adds "not financial advice" note |
| 4.2 Additional Socratic Questions | **New** | New discussion |
| 4.3 Final Class Discussion: How Did Your Perspective Change? | `10-what-future-can-bitcoin-build/4-an-empowered-future` (activity) | Moved, same questions |

#### Removed or not carried over

| 26.04 file | What it covered |
| --- | --- |
| `4-how-problems-lead-to-solutions/0-introduction` | Chapter intro: the fiat system benefits a few |
| `8-how-bitcoin-works/2-the-utxo-model` | UTXOs as coins and change (only its video moved to the Activity Guide) |
| `10-what-future-can-bitcoin-build/0-introduction` | Chapter intro: Bitcoin as a peaceful revolution |
| `10-what-future-can-bitcoin-build/2-the-philosophy-of-bitcoin` | Philosophy of Bitcoin and twelve reflection questions (some ideas echoed in 2.17) |
| `10-what-future-can-bitcoin-build/3-the-benefits-of-bitcoin` | Hyperbitcoinization and its benefits (remittances, energy, transparency) |
| `10-what-future-can-bitcoin-build/4-an-empowered-future` | Partly: closing text dropped; its video and final discussion moved to the Activity Guide |
| `11-back-matter/1-real-world-case-studies` | Education Network case studies (Bitcoin Indonesia, The Core) |
| `11-back-matter/2-additional-resources` | Reading list, courses, authors, websites (Next steps keeps only My First Bitcoin links) |
| `11-back-matter/3-key-concepts` | Key concepts per chapter (replaced by key takeaways in each review) |
| `11-back-matter/4-glossary` | Glossary of terms (replaced by links to the online lexicon) |

Parts dropped from files that were otherwise carried over:

- `3-what-is-fiat-money/2-the-fiat-system`: who controls the fiat system, policy targets, fiscal policy lists, "too big to fail".
- `4-how-problems-lead-to-solutions/1-the-global-debt-burden-and-social-inequality`: Jaime's ledger, global debt figures, wealth inequality and superpowers.
- `2-the-history-of-money/2-digital-currency`: its three videos.
- `8-how-bitcoin-works/0-introduction` and `8-how-bitcoin-works/1-security-through-cryptography`: list of protocol mechanics, hashing properties and examples.
- `9-how-does-bitcoin-mining-work/3-how-transactions-work`: step-by-step transaction lifecycle (partly spread across 2.9, 2.10 and 3.11).
- `7-using-bitcoin-in-daily-life/5-buying-coffee-and-groceries-with-bitcoin`: card fee breakdown, BTCPay Server, BTCMap, gift cards, Arnhem and Bitcoin Beach.
- `7-using-bitcoin-in-daily-life/1-the-lightning-network` and `4-sending-and-receiving-lightning-transactions`: café tab analogy, comparison and capacity tables.
- Opening quotes from most chapters, and the videos in old 1.6, 4.3, 5.2 and 7.5.

### Bitcoin Diploma: Educator Guide and Educator Quick Start

#### Front matter (Educator Guide, part 0)

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| About this guide | Partly `educator-guide/en/README` (intro) | Now tied to the 26.10 Diploma, Student Guide, Quick Start, Assessment Grid and Activity Library; adds learner registration and a release-status note |
| Assessment at a glance | **New** | Two completion gates: theory (C1 to C5) and practical (C6, C7); "Yes" or "Not yet", not grades |
| How to use this guide | `educator-guide/en/how-to-use-this-guide` ("How to Read This Guide", "Understanding the Module Structure") | Three reading passes and one fixed page order replace the old lesson template; adds safe phrases for when you are unsure |
| Operational assessment protocol | **New** | Source of truth for the seven competencies, sample tasks (T1 to T3, P6a, P6b, P7), permitted support, reassessment and calibration examples |
| Purpose | Partly `educator-guide/en/README` ("Purpose", "Notes") | Longer list (safety, localization, assessment, privacy); keeps the "no financial advice" statement |
| Quick start: ten non-negotiables | **New** (idea of fixed goals from `how-to-use-this-guide`, "Adapt the How, Not the What") | Ten fixed rules on sequence, evidence, secrets, advice and certification |
| Start here: your first teaching route | Partly `educator-guide/en/faq` ("Before You Start") | Step-by-step first route and a "what to read when" table; no need to read the whole guide first |
| The Bitcoin Diploma at a glance | Partly `educator-guide/en/README` ("Contents") | Four modules with guiding question, competency and evidence, instead of ten chapters |

#### Parts 1 and 2: the educator's role, what stays fixed

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 1.1 More than presenting information | `educator-guide/en/foreword-teaching-beyond-the-script` | Same idea (not a lecturer), shorter; adds safeguarding and assessing |
| 1.2 The Bitcoin Diploma purpose and your responsibility | Partly `how-to-use-this-guide` ("Learning Objectives") | Educator must assess each learner individually; learners do not have to agree to pass |
| 1.3 Course roles | **New** | Defines learner, educator, cohort and the Diploma |
| 1.4 The learning ecosystem | **New** | What the Student Guide, Educator Guide, Activity Library and Grid each do and cannot replace |
| 1.5 The pathway from learner to educator | Partly `foreword` and `README` (Education Network) | Optional path: Introduction to Bitcoin, Diploma, Educator Training Program, Bitcoin Education Network |
| 1.6 Educator support | Partly `foreword` (Education Network) | Adds the Educator Training Program and local experts, with a no-promotion rule |
| 2.1 What stays fixed and what can change | `how-to-use-this-guide` ("Adapt the How, Not the What"), `faq` ("About Adaptability") | Fixed / adaptable / flexible table and "may" and "may not" lists; the old freedom to remix module order is gone |
| 2.2 Four-module Bitcoin Diploma and Advanced Learning boundaries | **New** | Module 4 is required; deep topics (mining, transaction mechanics, Lightning operations) go to Advanced Learning |

#### Part 3: build a safe and active learning culture

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 3.1 Open the course with clear expectations | Partly `README` ("Notes": not advice) | New participation rules; no one is asked about their holdings |
| 3.2 Teach how to think, not what to think | `foreword` ("how to think, not what to think") | Now an eight-step reasoning sequence; slogans such as "not your keys, not your coins" must be explained |
| 3.3 Welcome disagreement and correct error | Partly "What Good Looks Like" in chapters 3 and 10 ("reasonable people disagree") | Six-step method; correct errors clearly; neutral does not mean all claims are equal |
| 3.4 Protect participation without forcing disclosure | **New** | Three routes (own, observed or invented example); 26.04 chapter 3 suggested asking about learners' own salary |
| 3.5 Support multilingual discussion | **New** | Agree local terms, avoid idioms, rules for interpreters |
| 3.6 Support accessibility without lowering the competency | **New** | Accommodations allowed if the competency stays the same |

#### Part 4: plan the complete learning experience

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 4.1 Start with the learner and the evidence | Partly `faq` ("What should I do before class?") | Planning questions on language, devices, safety and observation time |
| 4.2 The minimum eight-hour pathway | `how-to-use-this-guide` ("Duration & Core Idea": ten 90-minute lessons) | At least eight hours in total, no upper limit; four delivery models |
| 4.3 A repeatable two-hour module rhythm | Partly each chapter's "Procedure" timings | One 120-minute pattern for every module |
| 4.4 What to protect when time is tight | Each chapter's "Time Management"; `faq` ("short on time") | One priority list for the whole course, safety first |
| 4.5 Suggested preparation timeline | Each chapter's "Preparation" | General timeline (weeks, days, just before class) instead of per-chapter lists |
| 4.6 Minimum materials | Each chapter's "Tools & Resources" | Generic list; adds "SAMPLE: DO NOT PAY" labels; Support Library items no longer listed |
| 4.7 Local verification record | **New** (partly chapter 4 "Preparation": local inflation data) | Table to record each local fact with source and date |

#### Part 5: facilitation methods that work across all modules

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 5.1 The learning rhythm | Partly `how-to-use-this-guide` ("Purpose", "Method", "Mid-Lesson Check") | Nine-step rhythm for any concept |
| 5.2 Think-pair-share | `how-to-use-this-guide` ("Structure" names it) | Now a step-by-step method |
| 5.3 Claim, evidence, reasoning, and trade-off | **New** | Method for testing claims about inflation, energy, privacy, CBDCs |
| 5.4 Scenario analysis | **New** | Seven questions, then change one condition |
| 5.5 Misconception check | Partly `how-to-use-this-guide` ("Common Misconceptions") | New three-statement method |
| 5.6 Demonstration with prediction | Partly chapter 6 "Online Teaching" (pause after each step) | Learners predict before each demo step |
| 5.7 Exit explanation | Each chapter's "Wrap-Up and Check for Understanding" | Sentence starters; can count as evidence only in some cases |
| 5.8 Light module-closing reflection | **New** | One short closing question per module; never collected or scored |
| 5.9 Debrief every activity | Partly `how-to-use-this-guide` ("Activities") | Four debrief questions; name what the game gets wrong |
| 5.10 Handle rabbit holes | Partly each chapter's "If ahead, take time on" | Visible "Later / Advanced" list |
| 5.11 Low-tech teaching: focus on interaction | **New** | Low-tech can be the first choice, not only a backup |
| 5.12 Media and tool fallbacks | Partly chapters' "Online Teaching" and "Preparation" | Table of offline equivalents; no required step depends on a website or video |

#### Part 6: safe practical teaching

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 6.1 Use Presentation, Practice, Production | **New** | Three-stage model for every practical skill |
| 6.2 Demonstration safety protocol | Partly chapter 6 "Preparation" (test the wallet first) | Ten-step check before any live demo |
| 6.3 Universal stop conditions | **New** | List of situations that stop an activity at once |
| 6.4 No real secrets in class | Partly chapter 6 seed phrase warnings | Strict rule: only training material, never a learner's real wallet |
| 6.5 Shared devices | **New** | Turns, resets and individual observation |

#### Part 7: Module 1 companion (Understanding Money)

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 7.1 Purpose of the module | Core ideas of chapters 1 to 4 | Four chapters become one module with a guiding question and learner promise; warns against a long argument against fiat |
| 7.2 Assessed competencies and competency criteria | "Learning Objectives" of chapters 1 to 4 | Becomes competency C1 with three criteria; F1 is formative |
| 7.3 Prepare before class | "Preparation" of chapters 1 to 4 | Adds checks of local banking rules, official inflation measure and local CBDC status |
| 7.4 Suggested two-hour flow | "Procedure" of chapters 1 to 4 | One 120-minute flow instead of four 90-minute lessons |
| 7.5 Opening questions about money | `1-what-is-money` ("1.0 Introduction", "1.1 Discussions about Money") | Same five questions (no longer printed twice); no personal finance disclosure |
| 7.6 Why money exists | `1-what-is-money` ("1.2 Definition of Money") | Grounded in coordination; no single origin story |
| 7.7 Functions and properties of money | `1-what-is-money` ("1.3", "1.4") | Seven properties (adds verifiability); comparison activity reused in Module 2 |
| 7.8 Barter and the double coincidence of wants | `2-the-history-of-money` ("Barter and Its Limitations") | New three-person example; barter can work in some settings |
| 7.9 Scarcity, value, and exchange | `1-what-is-money` ("1.6 The Psychology of Money") | Delayed-reward (candy) activity gone; no moral judgment on time preference |
| 7.10 Beginner monetary history | `2-the-history-of-money` ("2.1"), `3-what-is-fiat-money` ("3.1") | Layered timeline; 1971 is not the start of all fiat; detail goes to Advanced Learning |
| 7.11 Fiat money and the local system | `3-what-is-fiat-money` ("What the Fiat System Is", "Who Controls the Fiat System") | Trace one local payment; "who benefits" framing dropped; avoid "fiat is fake money" |
| 7.12 Fractional-reserve banking, liquidity, and solvency | `3-what-is-fiat-money` ("Fractional Reserve Banking") | Balance-sheet view (loans create deposits); bikes analogy and boom-bust cycle dropped; adds liquidity versus solvency |
| 7.13 Inflation and purchasing power | `4-how-problems-lead-to-solutions` ("4.1 Decreasing Purchasing Power") | Inflation as a rise in general prices with many causes; official-basket investigation replaces the water-bottle and Jaime examples |
| 7.14 Why the US dollar is a reserve currency | Partly `2-the-history-of-money` and `3-what-is-fiat-money` (Bretton Woods) | Mostly new; no prediction of collapse or dominance |
| 7.15 Why people look for alternatives | Partly `4-how-problems-lead-to-solutions` ("4.2", "4.3") | Compare several alternatives by the same criteria; no recommendation |
| 7.16 CBDCs as digital fiat | `3-what-is-fiat-money` ("3.3"), `10-what-future-can-bitcoin-build` ("10.1") | Moved to Module 1; five neutral questions; designs differ, no blanket surveillance claim |
| 7.17 Strong Module 1 questions | Wrap-up questions of chapters 1 to 4 | New question list |
| 7.18 Common misconceptions and responses | Chapters 2 to 4 "Misconceptions Libraries" (referenced only) | Corrections now written in the guide |
| 7.19 Module 1 educator-led theoretical touchpoint | **New** | Assessment task for C1 |
| 7.20 Review and bridge to Module 2 | Wrap-ups of chapters 1 to 4 | Sentence frame and closing question; bridge to the double-spend problem |

#### Part 8: Module 2 companion (How Bitcoin Works)

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 8.1 Purpose of the module | Core ideas of `5-what-is-bitcoin`, `8-how-bitcoin-works`, `9-how-does-bitcoin-mining-works` | One beginner story: copying problem, shared rules, independent checking |
| 8.2 Assessed competencies and competency criteria | "Learning Objectives" of chapters 5, 8, 9 | Becomes C2 and C3 |
| 8.3 Prepare before class | "Preparation" of chapters 5, 8, 9 | Role cards and node rule card; no price charts; no browsing of tokens |
| 8.4 Suggested two-hour flow | "Procedure" of chapters 5, 8, 9 | One 120-minute flow |
| 8.5 Why Bitcoin was created | `5-what-is-bitcoin` ("5.0 Satoshi Nakamoto and the Creation of Bitcoin") | Framed as the double-spend problem; 2008 crisis, Satoshi and genesis-block dates not mentioned |
| 8.6 Earlier digital-money context | `4-how-problems-lead-to-solutions` ("Early Digital Currency Attempts"), chapter 5 timeline | Kept short; Cypherpunks section dropped |
| 8.7 Explain the combined response | `5-what-is-bitcoin` ("How Bitcoin Works and the Nakamoto Consensus"), `9-how-does-bitcoin-mining-works` ("9.3") | Five-part map; the term "Nakamoto Consensus" and the Monopoly analogy are gone |
| 8.8 Digital signatures | `8-how-bitcoin-works` ("Digital Signatures and Transaction Authorization") | Beginner level only; a signature is not encryption; no cryptography demos |
| 8.9 Decentralization and peer-to-peer transfer | `4-how-problems-lead-to-solutions` ("Centralized vs. Decentralized Systems"), partly `10-...` ("10.2") | Narrow definition with limits (influence is uneven); Canada and Tor examples dropped |
| 8.10 Users, nodes, miners, developers, and services | `5-what-is-bitcoin` ("The Participants"), `9-...` ("Nodes and Miners, Different Roles") | "Does not mean" table; adds services; invalid-block activity |
| 8.11 Proof of work | `9-...` ("Valid Block Hash, Proof of Work, and Difficulty Adjustment") | Relationship, not maths; energy treated as claim and evidence; 2,016-block detail dropped |
| 8.12 Finite supply and halving | `9-...` ("What Miners Actually Do": rewards, halvings), `5-...` (scarcity) | No link to price; issuance-rounds activity |
| 8.13 Sats and unit bias | Partly `5-what-is-bitcoin` ("Divisibility") | Conversion examples and unit bias are new |
| 8.14 Bitcoin as sound digital money | `5-what-is-bitcoin` ("5.2 Bitcoin as Sound Digital Money") | Each property has a qualification; "sound money" is a judgment; store-of-value stages claim dropped |
| 8.15 Bitcoin, stablecoins, and other crypto-assets | Partly `6-how-to-use-bitcoin` ("6.5 Don't Trust, Verify": copycat projects) | New guided comparison for C3, with no named tokens |
| 8.16 Responsible learning versus speculation | Partly chapter 4 "What Good Looks Like" ("not a get-rich scheme"), chapter 6 "easy profits" | Clear boundary between education, trading and promotion |
| 8.17 Bitcoin-properties FAQs | **New** (topics from chapter 5 properties) | Learner questions with beginner-safe answers |
| 8.18 Misconception bank | Chapters 5, 8, 9 "Misconceptions Libraries" (referenced); chapter 9 "If Students Struggle" | Full table, including energy, bans, CBDCs and "too slow" |
| 8.19 Strong Module 2 activities | "Activities" of chapters 5, 8, 9 (Consensus, Transactions in Action) | Choose two or three; consensus and hashing games only with a strong debrief |
| 8.20 Module 2 educator-led theoretical touchpoint | **New** | Assessment task for C2 and C3 |
| 8.21 Review and bridge to Module 3 | Wrap-ups of chapters 5, 8, 9 | Fiat issue / Bitcoin response / new responsibility table |

#### Part 9: Module 3 companion (Using Bitcoin Safely)

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 9.1 Purpose of the module | Core ideas of `6-how-to-use-bitcoin`, `7-use-bitcoin-in-daily-life` | Safe beginner practice; does not make learners ready for high-value self-custody |
| 9.2 Separate training wallets from personal wallets | Partly `6-...` ("6.3 Setting Up a Mobile Bitcoin Wallet") | Training wallets are the default; personal wallet help is optional, private and outside assessment |
| 9.3 Assessed competencies and competency criteria | "Learning Objectives" of chapters 6, 7 | Becomes C4, C5, C6 |
| 9.4 Time and educator capacity | **New** | Plan observation time per learner |
| 9.5 Prepare before class | "Preparation" of chapters 6, 7 | Named wallets (Blue Wallet, Muun) gone; sample data marked "do not pay"; scam scenarios |
| 9.6 Recommended delivery sequence | "Procedure" of chapters 6, 7 | Two learning parts plus a separate assessment window |
| 9.7 Wallets are interfaces | `6-...` ("What a Bitcoin Wallet Actually Is", "Different Types of Wallets") | Comparison criteria; open source as a qualified preference; online, desktop and paper wallet list dropped |
| 9.8 Addresses and payment requests | Partly `6-...` ("6.4 Receiving and Sending") | Address-checking habits and a public-or-secret card sort |
| 9.9 Address history and reuse lookup | **New** | Privacy activity with a prepared public address |
| 9.10 Keys and digital authorization | `8-how-bitcoin-works` ("Public and Private Keys"), `6-...` (email analogy) | Practical rule; a key proves authorization, not identity; email analogy dropped |
| 9.11 Seed phrases and recovery | `6-...` ("6.3"), `7-...` ("7.3") seed phrase warnings | "Never do this in class" list; recovery practice with fake material only |
| 9.12 Custodial and self-custodial use | `6-...` ("Self-Custodial vs Custodial Wallets"), `7-...` ("7.2") | Scenario-based; self-custody is not a moral test; an account balance is a promise |
| 9.13 Hot, cold, hardware, and custodial are different dimensions | Partly `6-...` (wallet types) | New: four separate questions |
| 9.14 Receiving bitcoin | `6-...` ("6.4", receiving) | Adds checking receipt in your own wallet, not a screenshot |
| 9.15 Sending bitcoin | `6-...` ("6.4", sending) | Ten-step pause-and-check; clipboard substitution activity |
| 9.16 Fees, confirmations, and finality | Partly `6-...` ("6.4": fees), `9-...` ("9.2 What Is the Mempool?") | Fees depend on data size and demand; no universal confirmation count; mempool detail dropped |
| 9.17 Block explorers and verification | Partly chapter 5 and 9 "Preparation" (blockchain.com, mempool.space) | Explorer is only an interface; searches reveal interest; no named explorer |
| 9.18 Scam recognition and safe response | Partly chapter 6 "What Good Looks Like" (phishing) | Scam patterns, default response, scam stations |
| 9.19 Acquiring and exchanging: awareness, not financial advice | `6-...` ("6.1 Acquiring and Exchanging Bitcoin") | Neutral comparison questions; adds ATMs; no recommendation |
| 9.20 On-chain and Lightning payments | `7-...` ("7.1 On-chain vs Lightning") | Payment path kept separate from custody; channels and routing moved to Advanced Learning |
| 9.21 Supported first access | Partly `6-...` ("6.3", "6.4") | No purchase required; simulated or low-stakes receipt |
| 9.22 Integrated Module 3 practice circuit | Partly `6-...` ("Transactions in Action and Role-Based Practice") | Eight practice stations |
| 9.23 Common misconceptions and responses | Chapters 6, 8 "If Students Struggle" and "Misconceptions Libraries" | Full table with check questions |
| 9.24 Module 3 practical evidence | Partly chapter 6 "What Good Looks Like" (learning outcomes) | Observable checklist; a safety error means "Not yet" |
| 9.25 Review and bridge to Module 4 | Wrap-ups of chapters 6, 7 | Integrated scenario and bridge |

#### Part 10: Module 4 companion (Bitcoin in Your Community)

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 10.1 Purpose of the module | Partly `7-use-bitcoin-in-daily-life` ("7.5") | New required Connect module, chosen locally; a simulation is a valid lesson |
| 10.2 Assessed competency and competency criteria | **New** | Competency C7 |
| 10.3 Begin with a need, not a tool | **New** | Bitcoin may not be the best option, and that is a valid result |
| 10.4 The seven-step module builder | **New** | From local context to a checked, safe, assessed task |
| 10.5 Module 4 readiness gate | **New** | Eight checks before any live activity |
| 10.6 Module 4 planning record | **New** | Planning form |
| 10.7 Suggested two-hour Module 4 flow | **New** | 120-minute flow |
| 10.8 Local Bitcoin tool review | Partly chapters 6, 7 (open-source wallets, merchant tools) | Generic review table; no named tool |
| 10.9 Lightning module checklist | `7-...` ("7.2" to "7.4") | Checklist; one payment proves only one route |
| 10.10 Module option A: local payment-path comparison | Partly `7-...` ("On-chain vs Lightning") | New comparison task with existing method |
| 10.11 Module option B: small purchase | `7-...` ("Everyday Use Cases": coffee, groceries) | Simulated purchase, including a failed request |
| 10.12 Module option C: payment for work or family remittance | Partly `7-...` ("7.5"), `10-...` ("A revolution in remittances") | Neutral map of the full route; invented cases only |
| 10.13 Module option D: merchant payment and refund flow | `7-...` ("Merchant Tools": BTCPay Server) | Generic merchant operations and refunds; BTCPay Server not named |
| 10.14 Module option E: community donation | **New** | Safe donation route, usually simulated |
| 10.15 Module option F: on-ramp, off-ramp, KYC, and no-KYC comparison | `6-...` ("6.1 Acquiring and Exchanging Bitcoin") | Adds KYC trade-offs; no real cash trades as a default exercise |
| 10.16 Module option G: circular economy and local resource map | `7-...` ("Circular Economies", BTCMap) | Test whether a local loop solves a real need; Arnhem and Bitcoin Beach examples dropped |
| 10.17 Community custody and shared funds | **New** | Responsibilities when one person holds funds for others |
| 10.18 Strong Module 4 discussion questions | **New** | Question list |
| 10.19 Common Module 4 trouble spots | **New** | Common planning mistakes |
| 10.20 Module 4 evidence | **New** | What to observe for C7 |
| 10.21 Review and course bridge | Partly `10-...` ("Final Class Discussion") | Team presentations do not count as individual evidence |

#### Parts 11 and 12: optional resources, localization and delivery

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 11.1 Use optional learning resources appropriately | **New** | Optional resources never count as assessment |
| 12.1 Localize examples, not truth standards | `how-to-use-this-guide` ("Adapt the How, Not the What"), `faq` ("Can I adapt this for my country") | Seven-question checklist; record changes |
| 12.2 Separate stable concepts from changing facts | **New** | Table of stable ideas versus local facts; AI assistant only to find what to check |
| 12.3 Legal, tax, accounting, and regulatory context | Partly `README` ("Notes": not advice) | "Do not" list and sample wording |
| 12.4 Named tools, services, and resources | **New** | Rules for naming tools; 26.04 named tools as defaults |
| 12.5 Translation workflow | Partly `faq` ("localise the material") | Nine-step workflow with review and testing |
| 12.6 Difficult terms to check locally | **New** | Term list; also states a preference for in-person delivery |
| 12.7 In-person delivery | Partly `faq` ("online or in person") | Room and station tips |
| 12.8 Online cohort delivery | Each chapter's "Online Teaching" | One general list; no screen-sharing of real wallets |
| 12.9 Self-paced learners | **New** | Cannot replace educator assessment |
| 12.10 Mobile-only and shared-device delivery | **New** | Phone-readable materials and device resets |
| 12.11 Large cohorts | **New** | Peer learning, not peer certification |
| 12.12 Mixed prior knowledge | Partly `faq` ("younger, older, quieter, stronger, or weaker") | Experienced learners still need evidence |

#### Parts 13 and 14: activities and visuals

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 13.1 Activity purpose comes first | `how-to-use-this-guide` ("Activities"), each chapter's "Activities" | Each activity is labelled as learning or assessment |
| 13.2 Assessment activity crosswalk | Each chapter's "Activities" (Iterative Barter Game, Consensus, Transactions in Action, Exploring the Mempool, Lightning Relay Race) | Maps activities to competencies; Auction and Fractional Reserve Banking not listed |
| 13.3 Activity selection questions | **New** | Ten questions before choosing |
| 13.4 Required activity information | **New** | Fields to record for an adapted activity |
| 13.5 Choose activities deliberately | **New** | Keep an activity only for a clear reason |
| 13.6 Adapt an ordinary learning activity | `how-to-use-this-guide` ("Create new activities"), `faq` ("shorten or extend activities") | What may change and what must stay |
| 13.7 Adapt a practical activity for assessment | **New** | Keep competency, evidence and safety when adapting |
| 14.1 Use visuals as teaching tools | Each chapter's "Visual Aids" and "most useful visuals" | General rules; never show real data; visuals must not imply price growth |

#### Parts 15 and 16: closing the course, after the course

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 15.1 Capstone discussion | `10-...` ("Final Class Discussion and Course Reflection") | New questions on responsibility, safety and limits |
| 15.2 Final personal learning reflection (F2) | `10-...` ("Suggested reflection prompts") | Formative; right to remain uncertain; no commitment to use bitcoin |
| 15.3 Confirm what the certificate means | **New** | Participation versus completion certificates; educator issues them; Certificate Tool |
| 15.4 Final safety reminders | **New** | Short safety list |
| 16.1 Complete records and reassessment | **New** | Combine results, reassess, issue certificates |
| 16.2 Ask learners about the learning experience | Partly `faq` ("share feedback") | Feedback questions and the exit survey |
| 16.3 Reflect as an educator | `how-to-use-this-guide` ("After class", "Ongoing: annotate this guide") | Review table |
| 16.4 Share an educator testimonial | **New** | Optional testimonial form |
| 16.5 Maintain local content | Partly `README` ("Contributing"), `faq` ("What if I notice something unclear") | Recheck local facts before reuse; stop unsafe activities |

#### Parts 17 and 18: terminology and back matter

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 17.1 Quick terminology and misconception-sensitive distinctions | Partly each chapter's "Vocabulary Reference Card" (referenced only) | Distinctions table in the guide; full definitions in the Lexicon |
| Appendix A: one-page course preparation checklist | Partly each chapter's "Preparation" | One checklist for the whole course |
| Appendix B: module lesson-plan template | Partly `how-to-use-this-guide` (module template) | Blank planning form |
| Appendix C: practical demonstration safety plan | **New** | Planning form for live demos |
| Appendix D: local expert briefing | Partly `how-to-use-this-guide` ("Add resources from your community") | Rules and form for guests |
| Appendix E: discussion cue card | Partly chapter 1 "Discussion Prompts Library" (referenced only) | Prompts for slow, dominated or heated discussion |
| Appendix F: sample delivery maps | Partly `README` ("Contents": ten modules) | Four-session, eight-session and one-day plans |
| Working principle | Partly `foreword` | Short closing statement |
| Continue learning | **New** | Points to the AI assistant, with limits |
| Help improve this Educator Guide | `README` ("Contributing"), `faq` | Feedback, proofreading and GitHub links |

#### Educator Quick Start (new book)

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| Start here | **New** (partly `foreword`, `faq` "Before You Start") | Five steps for a first course; educator issues certificates |
| The learning path | **New** | Four modules in one table |
| What stays fixed, and what you bring | `how-to-use-this-guide` ("Adapt the How, Not the What"), `foreword` | Short version of the fixed and adaptable lists |
| Create a safe, active classroom | **New** | Short safety rules |
| Assess learning fairly | **New** | Two assessment parts, theory and practical |
| Your first-course checklist | **New** | Six-item checklist |
| Pick up the mantle | Partly `foreword` (closing tone) | Links to Educator Training Program, network, feedback and repository |

#### Removed or not carried over

| 26.04 content | What happened |
| --- | --- |
| Separate Educator Guide program and `README` contents table | Replaced by the guide inside the Bitcoin Diploma |
| Ten chapter lesson plans with 90-minute timings | Replaced by four module companions and one two-hour rhythm |
| Per-chapter "Online Teaching", "What Good Looks Like", "If Students Struggle" blocks | Not kept per chapter; partly covered by general parts 4, 5, 12 |
| Support Library references (Vocabulary Reference Card, Misconceptions Libraries, Comparison Charts, Technical Explainers, adoption stories) | Not referenced; replaced by in-guide tables and the Lexicon |
| `1-what-is-money` "1.5 Types of Money" | No separate section; partly in 7.10 history |
| `1-what-is-money` delayed-reward (candy) activity | Dropped |
| `2-the-history-of-money` "2.2 Digital Currency" | Reduced to one line in 7.10 |
| `3-what-is-fiat-money` boom-bust cycle, "Dax and the Imaginary Bikes", Monopoly analogy, "who benefits" four actors | Dropped |
| `4-how-problems-lead-to-solutions` monetary versus price inflation, water-bottle and Jaime examples | Dropped; 7.13 uses an official-basket investigation |
| `4-...` "4.2 The Global Debt Burden and Social Inequality" | Dropped |
| `4-...` "The Cypherpunks and the Search for a Solution" | Dropped |
| `4-...` Canadian account freeze and Tor examples | Dropped |
| `5-what-is-bitcoin` Satoshi, 2008 crisis and genesis-block milestones | Dropped |
| `5-...` "Nakamoto Consensus" term and "symphony" analogy | Dropped |
| `5-...` store of value, medium of exchange, unit of account progression | Dropped |
| `6-how-to-use-bitcoin` named wallets (Blue Wallet, Muun) and step-by-step mobile wallet setup | Dropped; training wallets and simulations instead |
| `6-...` wallet type list (online, desktop, paper) | Dropped; replaced by four dimensions in 9.13 |
| `6-...` in-person peer-to-peer cash trades as an option | Now not to be run as a default class exercise (10.15) |
| `7-use-bitcoin-in-daily-life` café-tab analogy, Marcia/Jeff/Eve routing, Mina channel funding | Moved to Advanced Learning (Lightning operations) |
| `7-...` BTCPay Server, BTCMap, gift cards and vouchers | Not named; generic merchant and map options in Module 4 |
| `7-...` El Salvador, Austin, Arnhem, Bitcoin Beach examples | Dropped |
| `8-how-bitcoin-works` hashing, hash function properties, smoothie and fingerprint analogies | Dropped; "hashing activities" mentioned once as optional |
| `8-...` "8.2 The UTXO Model" and change outputs; Merkle trees | Dropped (transaction mechanics are Advanced Learning) |
| `8-...` claim that Bitcoin "cannot be hacked because it is protected by mathematics" | Dropped |
| `9-how-does-bitcoin-mining-works` "9.2 What Is the Mempool?" and reasons a transaction stays unconfirmed | Dropped; only a "pending pool" label in one diagram |
| `9-...` node function list, "haystack" analogy, difficulty adjustment every 2,016 blocks, 51% attack | Dropped or reduced to one line in 8.11 |
| `9-...` full transaction life-cycle steps | Reduced to the five-part map in 8.7 |
| `10-what-future-can-bitcoin-build` "10.2 The Philosophy of Bitcoin" | Dropped |
| `10-...` "10.3 The Benefits of Bitcoin" (self-sovereign future, remittance revolution, abundant energy) | Dropped |
| `10-...` "10.4 An Empowered Future" and revisiting the chapter 1 questions | Dropped; 15.1 uses new questions |
| Activities "Auction" and "Fractional Reserve Banking" | Not listed in 26.10 (a "token bank-run game" is mentioned once in 5.9) |
| `faq` "About Open Source" questions | Dropped |
| `how-to-use-this-guide` freedom to reorder or remix modules | Removed; the four-module order is fixed |
| `how-to-use-this-guide` "Mid-Lesson Check" | Not kept as a named step; partly in 5.1 "Check" |
| `foreword` closing lines ("This is serious work", "Trust the process") | Not kept; tone moved to 1.1 and Working principle |

### Bitcoin for Juniors

Note for translators: some 26.10 file names keep their 26.04 slug, so the number in the file name does not always match the section number (for example `1-ship-rekt.md` is section 1.4).

#### Front matter

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| Foreword | `0-front-matter/1-foreword.md` | Same text; glossary links added. |
| FAQ | `0-front-matter/2-faq.md` | Same text; glossary links added. |
| Introduction | `0-front-matter/3-introduction.md` | Rewritten to explain the new lesson format (facts line, single objective, Setup, numbered steps, Key points, Suggested assignment). |
| A Parent Guide to Bitcoin for Juniors | **New** | Explains the course to families: no money, wallets or devices, no tests, open-source materials. |
| README (program page) | `README.md` | Now a generated table of contents plus a note on how activities are structured; the objectives, audience and notes text was dropped. |

#### Chapter 1: Exchange, Value, and Price

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 1.1 Overview | **New** | Chapter introduction. |
| 1.2 Going, Going, Gone! | `1-exchange-value-and-price/2-going-going-gone.md` | New format, steps condensed; same auction. |
| 1.3 What is value? | `1-exchange-value-and-price/3-what-is-value.md` (was numbered 1.4) | Moved earlier; steps condensed; the gratitude moment in the close is gone. |
| 1.4 Ship Rekt | `1-exchange-value-and-price/1-ship-rekt.md` (was 1.1) | Moved later; timing table with a 60-minute core route and a 70-minute auction route; long shipwreck script replaced by a short story; Day 7 is now optional. |
| 1.5 Worth It | `1-exchange-value-and-price/4-worth-it.md` (was 1.3) | Moved last; steps condensed; gratitude moment gone. |

#### Chapter 2: Time, Energy, and Reward

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 2.1 Overview | **New** | Chapter introduction. |
| 2.2 Work, Rest & Play | `2-time-energy-and-reward/1-work-rest-and-play.md` | New format; empty opening step removed; memory-matching variant dropped. |
| 2.3 Energy Economy | `2-time-energy-and-reward/2-energy-economy.md` | New format; the empty warm-up prompts are now one clear question. |
| 2.4 That's Not Fair! | `2-time-energy-and-reward/3-that-s-not-fair.md` | New format; named physical challenges (push-ups, arm wrestling) replaced by "a physical or mental challenge"; materials made precise (five dice per student). |
| 2.5 That's Not Fair (Story Time) | `2-time-energy-and-reward/4-that-s-not-fair-story-time.md` | New format, steps condensed. |
| 2.6 Time Preference | `2-time-energy-and-reward/5-time-preference.md` | New format; comparison sheet added to materials; reference now under Additional resources. |
| 2.7 Smart Choices | `2-time-energy-and-reward/6-smart-choices.md` | New format, steps condensed; Marshmallow Test reference kept. |

#### Chapter 3: Analog vs. Digital

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 3.1 Overview | **New** | Chapter introduction. |
| 3.2 Back In My Day | `3-analog-vs-digital/1-evolution-of-technology.md` | New format; the 26.04 contents table called it "Evolution of Technology", now titled as in the lesson. |
| 3.3 Vote With Your Feet | `3-analog-vs-digital/2-vote-with-your-feet.md` | New format; zone signs now required, not optional. |
| 3.4 Invent The Future | `3-analog-vs-digital/3-invent-the-future.md` | New format; mention of assessing pitches removed; optional prompt cards added. |

#### Chapter 4: Safety, Security, and Privacy

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 4.1 Overview | **New** | Chapter introduction. |
| 4.2 Gatekeepers | `4-safety-security-and-privacy/1-gatekeepers.md` | New format, steps condensed. |
| 4.3 Wire Tap | `4-safety-security-and-privacy/2-wire-tap.md` | New format, rounds condensed; same five rounds and locked-message twist. |
| 4.4 Cypherpunks Write Code | `4-safety-security-and-privacy/3-cypherpunks-write-code.md` | New format; split pins now a required material. |
| 4.5 Nostr | `4-safety-security-and-privacy/4-nostr.md` | New format, steps condensed; the prerequisites list moved under Notes (see the note below the tables). |

#### Chapter 5: Money Matters

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 5.1 Overview | **New** | Chapter introduction. |
| 5.2 Money Matters | `5-money-matters/1-money-matters.md` | New format; empty and repeated lines removed; materials list much fuller (station signs, bank slips, movement card). |

#### Chapter 6: Bitcoin Basics

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 6.1 Overview | **New** | Chapter introduction. |
| 6.2 From Problem to Protocol | `6-bitcoin-basics/1-from-problem-to-protocol.md` | New format, steps condensed; same story and pause points. |
| 6.3 Satoshi, Where Are You? | `6-bitcoin-basics/2-satoshi-where-are-you.md` | New format; drawing materials added for the final draft. |
| 6.4 It's Mine! | `6-bitcoin-basics/3-it-s-mine.md` | New format, steps condensed; same mining game. |

#### Removed or not carried over

| 26.04 file | What it was | In 26.10 |
| --- | --- | --- |
| `resources/Bitcoin Adoption Stories Library.md` | Stories of people, merchants, countries and companies adopting Bitcoin | Not carried over |
| `resources/Bitcoin Properties Deep-Dive.md` | Bitcoin against six properties of good money | Not carried over |
| `resources/Comparison Charts & Reference Sheets.md` | Side-by-side charts (fiat vs sound money, wallets, Lightning, mining) | Not carried over |
| `resources/Discussion Prompts Library.md` | Reusable "talk moves" for teachers | Not carried over |
| `resources/Fee & Speed Comparison Tool.md` | Payment methods compared by fee and speed | Not carried over |
| `resources/Lightning Network Simplified Explainer.md` | How Lightning works | Not carried over |
| `resources/Misconceptions Libraries.md` | Common learner confusions by chapter | Not carried over |
| `resources/Network Participants Role Guide.md` | Users, miners, nodes, developers and others | Not carried over |
| `resources/Participation Formats Library.md` | Think-pair-share, small group and whole-class formats | Not carried over |
| `resources/Payment Scenario Walkthroughs.md` | Step-by-step sending and receiving scenarios | Not carried over |
| `resources/Private Key Security Deep-Dive.md` | Keys, seed phrases, hardware wallets | Not carried over |
| `resources/Real-World Examples & Case Studies Library.md` | Case studies by chapter | Not carried over |
| `resources/Satoshi White Paper Summary Guide.md` | Plain summary of the white paper | Not carried over |
| `resources/Security Best Practices Checklist.md` | Safe-use checklist | Not carried over |
| `resources/` support resources matrix (all chapters) | Which resource goes with which chapter | Not carried over |
| `resources/Technical Explainers & Deep-Dives.md` | Fractional reserve, hashes, keys, UTXO, Proof of Work | Not carried over |
| `resources/Transaction Anatomy Guide.md` | Inside a Bitcoin transaction | Not carried over |
| `resources/` vocabulary reference cards (chapters 1 to 10) | Key terms for chapters 1 to 10 | Not carried over; key terms now link to the lexicon instead (Partly: the lexicon is not a one-to-one copy) |
| Lesson parts "Equipment", "Appendix" headings, "Grouping" | Separate headings in each lesson | Merged into Materials and the facts line; appendix labels remain where a lesson uses them |
| README sections "Educational objectives", "Target audience", "Notes", "Contributing" | Program page text | Dropped from the generated README |

Note on 4.5 Nostr: in 26.10 the "Pre-requisites" heading is joined to the end of the description paragraph, and its list ("4.3 - Telephone", "4.4 - Cypherpunks Write Code") sits under Notes. "Telephone" is the old name of the Wire Tap activity. This looks like a conversion glitch, not an intended change.

### Introduction to Bitcoin

#### Student guide

| 26.10 section | Comes from (26.04) | What changed |
| --- | --- | --- |
| 1 Why Does Money Matter? | `en/1-why-does-money-matter.md` | Henry Ford quote removed; five starting questions, fact vs opinion, and an education-only disclaimer added. |
| 2 What is Money? | `en/2-what-is-money.md` | Opens with "money is a tool for exchange"; adds the "double coincidence of wants"; gold standard and 1971 explained more precisely; fiat defined, with legal tender and taxes. |
| 3 What's Wrong With Our Money? | `en/3-what-s-wrong-with-our-money.md` | Inflation and purchasing power defined; several causes named; the 1913 and cheeseburger figures removed; new "Try it" price check; bank balance explained as a promise; fiat's benefits acknowledged. |
| 4 What is Bitcoin? | `en/4-what-is-bitcoin.md` | Adds the double-spend problem and the 2008 white paper; "finite, independent" becomes "limited supply, peer to peer" with caveats; sats, spelling note (Bitcoin and bitcoin) and trade-offs added. |
| 5 How Do You Use Bitcoin? | `en/5-how-do-you-use-bitcoin.md` | Named wallet tables removed; key-control table, wallet checklist, on-chain vs Lightning, three safety rules and a scam warning added. |
| 6 What's Next? | `en/6-what-s-next.md` | Takeaways reworded with trade-offs and safety; learners revisit the five questions; Bitcoin Diploma link now points to curriculum.myfirstbitcoin.org and names its four modules. |
| README (program page) | `en/README.md` | Now a generated table of contents only; objectives, audience and notes dropped (the disclaimer moved into section 1). |

#### Removed or not carried over

| 26.04 content | In 26.10 |
| --- | --- |
| Henry Ford quote (section 1) | Removed |
| "Nixon Shock" name and "money has no intrinsic value" opening (section 2) | Removed; the 1971 event is described without the name |
| "Over 96% since 1913" and cheeseburger price figures (section 3) | Removed |
| Self-custodial and custodial wallet tables with seven named wallets (section 5) | Removed; replaced by a checklist and the statement that My First Bitcoin does not recommend specific wallets |
| "Fiat money is broken by design" heading (section 6) | Reworded as "Money depends on rules and trust" |
| README "Educational objectives", "Target audience", "Notes", "Contributing" | Dropped from the generated README |

#### Slides folders

- `programs/introduction-to-bitcoin/slides/en/`: **New.** `slides.md` is a presenter deck (Marp Markdown) that follows the six sections of the student guide, with speaker notes on many slides; `README.md` explains which parts are text open to corrections (title, slide text, speaker notes) and which are set in the Studio (layout, image, number of slides).
- `programs/bitcoin-diploma/slides/en/`: **New.** `slides.md` is a presenter deck (Marp Markdown) for the Bitcoin Diploma, in four modules (Understanding Money, How Bitcoin Works, Using Bitcoin Safely, Bitcoin in Your Community), with speaker notes; `README.md` is the same kind of guide to what can be corrected.

### Bitcoin for Organizations

Retired on 2026-10-15. Nothing replaces it in 26.10. The 26.04 PDFs are at https://curriculum.myfirstbitcoin.org/archive/ and the Markdown is under the `26.04` tag in `programs/bitcoin-for-organizations/en/`.

What it covered in 26.04 (eight modules, for leaders and teams in organizations):

1. **Bitcoin and Risk Management**: treating Bitcoin as an emerging risk, like the internet in 1995; identifying risks and impacts, rating them, and finding mitigations and opportunities.
2. **Dispelling Misconceptions**: ten common objections (intrinsic value, energy use, speed, innovation, government bans, other coins, decentralization, use as money, CBDCs, being overtaken).
3. **Bitcoin Technical History**: the ideas Bitcoin built on, from TCP/IP and public key systems to DigiCash, Hashcash, BitTorrent and Reusable Proof of Work.
4. **Impact on Industry Verticals**: energy, investment management, banking and payments, technology, professional services, government, and charities and nonprofits.
5. **Impact on Internal Functions**: what Bitcoin means for IT leaders, and what a Bitcoin treasury is.
6. **Adopting Bitcoin**: the discovery of digital scarcity and the Bitcoin adoption cycle.
7. **Bitcoin's Possible Future**: renewable energy grids, banking the unbanked and underbanked, and Bitcoin and artificial intelligence.
8. **The Open Ledger: Analyzing the Bitcoin Economy**: the public ledger, metrics for reading it, the future of on-chain metrics, and the Pizza Day transaction.
