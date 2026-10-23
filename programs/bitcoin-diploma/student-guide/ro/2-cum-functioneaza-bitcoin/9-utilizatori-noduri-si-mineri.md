# 2.9 Utilizatori, noduri și mineri

Bitcoin funcționează deoarece diferiți participanți îndeplinesc roluri diferite.

* **Utilizatorii** primesc, dețin și trimit bitcoin. Un utilizator își poate controla propriile chei păstrate într-un portofel sau poate apela la un [custode](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Utilizatorii conferă rețelei un sens economic alegând dacă acceptă bitcoin și în ce reguli sau servicii au încredere.
* [**Nodurile**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) rulează software Bitcoin și verifică independent regulile. Un [nod complet](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) verifică dacă [tranzacțiile](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) au semnături valide, dacă monedele bitcoin nu au fost deja cheltuite, dacă blocurile îndeplinesc cerințele pentru [Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) și dacă noile monede bitcoin respectă [calendarul de emisiune](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) partajează date valide cu alte noduri și resping datele nevalide.
* [**Minerii**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) adună [tranzacțiile în așteptare](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), construiesc [blocuri candidate](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) și concurează prin [Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Un câștigător din rândul [minerilor](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [difuzează](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) un bloc și poate primi [subvenția de bloc permisă](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) și [comisioanele de tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Minerii](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) contribuie la ordonarea [tranzacțiilor](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) și fac ca [registrul](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) să fie costisitor de rescris.
* **Dezvoltatorii** analizează, scriu și propun modificări ale software-ului. Ei nu dețin regulile Bitcoin. O modificare a software-ului contează doar dacă participanții aleg să ruleze software care respectă acele reguli.


<!-- micrographic: bitcoin-participant-roles-01 -->


Aceste roluri se limitează reciproc:

* un utilizator nu poate cheltui bitcoin fără semnătura validă necesară
* un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) poate propune un bloc, dar [nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) decid dacă acesta respectă regulile
* un [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifică folosind propriile reguli, dar [consensul](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) necesită reguli compatibile în întreaga rețea
* dezvoltatorii pot propune software, dar participanții aleg dacă să îl ruleze

Unele persoane îndeplinesc mai multe roluri. Un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) poate rula un [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) și poate fi, de asemenea, utilizator. Un începător nu trebuie să îndeplinească fiecare rol pentru a explica modul în care rolurile se echilibrează reciproc.

**Întrebare rapidă:** De ce un [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifică [tranzacțiile](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Numiți cel puțin o regulă pe care un [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) o verifică.

![Cadrul didactic îndrumă cursantul cu profil tehnic la un calculator care rulează un nod, cu monitorul orientat spre ei și cu partea din spate a carcasei vizibilă pentru privitor.](https://cdn.sanity.io/images/vje9ehw2/production/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
