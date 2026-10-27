# 2.9 Utilisateurs, nœuds et mineurs

Bitcoin fonctionne parce que différents participants remplissent différents rôles.

* **Les utilisateurs** reçoivent, détiennent et envoient des bitcoins. Un utilisateur peut contrôler ses propres clés conservées dans un portefeuille ou faire appel à un [dépositaire](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Les utilisateurs donnent au réseau sa dimension économique en choisissant d’accepter ou non des bitcoins et en décidant à quelles règles ou à quels services ils font confiance.
* [**Les nœuds**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) exécutent le logiciel Bitcoin et vérifient les règles de manière indépendante. Un [nœud complet](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) vérifie que les [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) possèdent des signatures valides, que les bitcoins n’ont pas déjà été dépensés, que les blocs satisfont aux exigences de la [preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) et que les nouveaux bitcoins respectent le [calendrier d’émission](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Les nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) partagent les données valides avec leurs pairs et rejettent les données invalides.
* [**Les mineurs**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) rassemblent les [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) en attente, construisent des [blocs candidats](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) et se font concurrence au moyen de la [preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). En cas de succès, un [mineur](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [diffuse](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) un bloc et peut recevoir la [subvention de bloc](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) autorisée ainsi que les [frais de transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Les mineurs](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) contribuent à ordonner les [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) et rendent le [registre](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) coûteux à réécrire.
* **Les développeurs** examinent, écrivent et proposent des modifications du logiciel. Ils ne sont pas propriétaires des règles de Bitcoin. Une modification du logiciel n’a d’effet que si les participants choisissent d’exécuter un logiciel qui suit ces règles.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Quatre rôles dans Bitcoin : les utilisateurs reçoivent, détiennent et envoient des bitcoins, les nœuds vérifient de manière indépendante le respect des règles, les mineurs construisent des blocs candidats avec la preuve de travail, et les développeurs proposent du code logiciel. Aucun rôle ne contrôle à lui seul le réseau.](/micrographics/bitcoin-participant-roles-01/fr-FR.md)


Ces rôles se limitent mutuellement :

* un utilisateur ne peut pas dépenser de bitcoins sans la signature valide requise
* un [mineur](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) peut proposer un bloc, mais les [nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) déterminent s’il respecte les règles
* un [nœud](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) effectue ses vérifications selon ses propres règles, mais [le consensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) exige des règles compatibles à travers le réseau
* les développeurs peuvent proposer des logiciels, mais les participants choisissent de les exécuter ou non

Certaines personnes remplissent plusieurs rôles. Un [mineur](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) peut faire fonctionner un [nœud](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) et être aussi un utilisateur. Un débutant n’a pas besoin de remplir tous les rôles pour expliquer comment ils s’équilibrent mutuellement.

**Question rapide :** Pourquoi un [nœud](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) vérifie-t-il les [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ? Citez au moins une règle qu’un [nœud](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) vérifie.

![L’enseignant guide l’apprenant au profil technique devant un ordinateur exécutant un nœud, avec l’écran tourné vers eux et son boîtier arrière visible pour l’observateur.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
