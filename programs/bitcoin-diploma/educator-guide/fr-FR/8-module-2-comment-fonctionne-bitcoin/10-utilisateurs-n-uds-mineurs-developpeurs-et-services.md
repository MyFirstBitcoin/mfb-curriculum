# 8.10 Utilisateurs, nœuds, mineurs, développeurs et services

Utilisez exactement ces délimitations des rôles pour les débutants :


| Rôle | Fonction principale à retenir pour les débutants | Cela ne signifie pas que ce rôle |
| --- | --- | --- |
| Utilisateur | Choisit de recevoir, de détenir, d’envoyer, de vérifier et d’accepter du bitcoin, directement ou par l’intermédiaire de services | Exécute automatiquement toutes les fonctions du réseau |
| Nœud | Vérifie de manière indépendante que les transactions et les blocs respectent ses règles et relaie les données valides | Crée de nouveaux blocs ou impose des règles à tout le monde |
| Mineur | Construit des blocs candidats et effectue une preuve de travail pour proposer leur ordre | Peut rendre une émission monétaire ou des transactions non valides acceptables pour les nœuds honnêtes |
| Développeur | Examine, écrit et propose des logiciels | Peut forcer les participants à adopter une modification des règles |
| Service Bitcoin | Fournit un portefeuille, une plateforme d’échange, un explorateur, une interface de paiement ou une autre interface | Est le protocole Bitcoin lui-même |



<!-- micrographic: bitcoin-participant-roles-01 -->


#### Activité : bloc non valide

Donnez à un apprenant jouant le rôle de [mineur](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) un [bloc candidat](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) qui crée une subvention supérieure à ce que le [nœud](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) autorise sur sa fiche de règles. Les apprenants jouant le rôle de [nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) le vérifient et le rejettent.

Débriefing :

* Le [mineur](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) a effectué un véritable travail, mais n’a pas pour autant obtenu l’autorisation d’enfreindre les règles.
* [Les nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) appliquent les règles de manière indépendante, mais le réseau réel repose sur des logiciels et des communications, et non sur un vote en classe.
* Un développeur peut écrire d’autres règles, mais leur adoption est volontaire et des règles incompatibles peuvent créer un réseau distinct.

Posez la question :

> Pourquoi un [nœud](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) vérifie-t-il les transactions ? Citez au moins une règle dont il vérifie le respect.
