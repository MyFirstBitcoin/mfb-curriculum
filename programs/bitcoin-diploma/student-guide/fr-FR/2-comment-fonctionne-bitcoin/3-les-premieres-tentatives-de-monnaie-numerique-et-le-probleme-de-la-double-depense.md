# 2.3 Les premières tentatives de monnaie numérique et le problème de la double dépense

Bitcoin n’était pas la première tentative de création d’une monnaie numérique. Sa conception s’est appuyée sur quatre décennies d’expérimentation, en reprenant des idées issues de nombreux projets antérieurs qui ont contribué à sa réussite.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) utilisait la [cryptographie](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) pour permettre des paiements numériques confidentiels. Il dépendait d’une entreprise centrale et de relations bancaires. Lorsque l’entreprise a fait faillite, le système n’a pas pu continuer à fonctionner comme un réseau monétaire indépendant.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) utilisait la [preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) pour rendre coûteux l’envoi de courriels indésirables. L’ordinateur de l’expéditeur devait effectuer un travail avant d’envoyer un message. Cette idée montrait comment le coût des calculs pouvait décourager les abus.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) décrivait une proposition de système dans lequel un travail de calcul pouvait créer des enregistrements numériques rares. Il n’a pas été lancé sous la forme d’un système monétaire décentralisé complet, mais il a développé des idées importantes sur la dimension numérique de la [rareté](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) et sur la preuve.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) et la [**preuve de travail réutilisable (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) exploraient des moyens permettant aux participants de créer ou de transférer, sous forme numérique et en quantité limitée, de la [valeur](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) sans dépendre uniquement d’une base de données centrale. Ces projets étaient incomplets, mais ils ont aidé à préciser ce dont un système fonctionnel aurait besoin.
* Bien que [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) ne soit pas une monnaie, il a montré qu’un [réseau pair à pair](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) pouvait permettre à de nombreux ordinateurs indépendants de partager des informations sans qu’un serveur central contrôle l’ensemble du système.

Ensemble, ces expériences ont apporté des pièces utiles au puzzle. Elles ont aussi permis de préciser le problème qui restait à résoudre.


> **Definition – Double dépense**
>
> [La double dépense](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) consiste à tenter d’envoyer la même unité numérique à deux destinataires. Les données numériques peuvent être copiées à l’identique : un système de monnaie numérique doit donc disposer d’un moyen de déterminer quelle [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) est valide.


[Les systèmes centralisés](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) empêchent cela en laissant une base de données de confiance unique déterminer quel paiement a eu lieu en premier. Le 31 octobre 2008, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto), dans son livre blanc, [_Bitcoin : un système de paiement électronique pair à pair_](https://bitcoin.org/bitcoin.pdf), expliquait une approche différente : un système public capable d’établir un historique partagé des paiements sans banque, entreprise ou autre autorité centrale.

Le livre blanc réunissait les caractéristiques nécessaires à cette approche :

1. **Un [réseau pair à pair](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) :** [les transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sont annoncées directement à un réseau de participants.
1. **[Signatures numériques](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) :** une [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) est une information secrète qui permet de créer une signature pour autoriser une dépense ; seul son détenteur peut le faire.
1. **Blocs et [minage](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) :** [les mineurs](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) regroupent des [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) en blocs et utilisent la [preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) pour rivaliser afin d’ajouter le bloc suivant.
1. **Indépendance de la [vérification](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification) :** [les nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) vérifient la conformité des [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) et des blocs aux règles de Bitcoin.
1. **Un historique commun avec une accumulation de [preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) :** les participants reconnaissent la [chaîne valide](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) de [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ayant le plus de [travail accumulé](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) comme le registre commun.


<!-- micrographic: five-part-response-01 -->


Ce module explique ces concepts plus en détail. Ensemble, ils ont apporté une réponse concrète au [problème de la double dépense](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) : le réseau peut rejeter une seconde tentative de dépenser le même bitcoin sans dépendre d’une autorité centrale. Bitcoin a apporté la combinaison manquante que des décennies d’expérimentations en matière de monnaie numérique avaient cherché à mettre au point.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
