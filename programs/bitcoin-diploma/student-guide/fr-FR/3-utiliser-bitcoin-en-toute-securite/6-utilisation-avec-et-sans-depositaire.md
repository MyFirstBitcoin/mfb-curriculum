# 3.6 Utilisation avec et sans dépositaire

<!-- card: definition -->
> **Definition – Garde**
>
> [La garde](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) répond à une question pratique : qui contrôle les clés nécessaires pour dépenser les bitcoins ?


Dans le cadre d’une **garde par un tiers** assurée par un service, une entreprise ou une autre personne contrôle les clés. Le solde affiché est une promesse du [dépositaire](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). En général, vous vous connectez à un compte et demandez au service d’effectuer un retrait ou un paiement.

Cette différence est importante pour la vérification. Les règles de Bitcoin et sa masse monétaire totale peuvent être vérifiées de manière indépendante, mais si vous ne contrôlez pas les clés, vous ne pouvez pas vérifier vous-même que le solde affiché sur votre compte correspond à des bitcoins que le service détient et mettra à votre disposition. La blockchain publique permet de voir les bitcoins contrôlés par des clés ; elle ne permet pas de voir qu’un service doit à un client donné le solde affiché sur son compte. Tant que vous ne pouvez pas effectuer de retrait et contrôler les clés, votre solde reste une promesse du service de vous fournir des bitcoins, et non des bitcoins que vous pouvez vérifier directement et dépenser vous-même.

Dans le cadre d’une utilisation **sans garde par un tiers** ou **en autogarde** d’un portefeuille, VOUS contrôlez les clés. Le portefeuille signe les [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sous votre autorité. Il peut subsister des dépendances à des logiciels, à du matériel, à des serveurs ou au réseau, mais aucun [dépositaire](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) n’a à approuver une dépense valide sur la blockchain.

![](https://cdn.sanity.io/images/vje9ehw2/staging/f93df0cc4a2ad82b3410a9ad4c3273d1b760f8ea-1774x887.svg)


<!-- micrographic: who-controls-keys-01 -->
[Dans le cas de la garde par un tiers, un service contrôle les clés et approuve les dépenses : le solde représente donc sa promesse. Dans le cas de la garde autonome, vous contrôlez les clés et les sauvegardes ; les deux modes présentent des dépendances et des risques de défaillance.](/micrographics/who-controls-keys-01/fr-FR.md)



<!-- micrographic: custody-comparison-table-01 -->
[Un tableau comparant l’utilisation avec garde par un tiers et l’utilisation en garde autonome : qui détient les clés, qui gère la récupération et le principal compromis de chaque modèle. Aucun des deux modèles n’est sans risque.](/micrographics/custody-comparison-table-01/fr-FR.md)


[Le mode de garde](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) n’est pas toujours évident à déterminer à partir de l’interface. Si vous ne pouvez pas contrôler la méthode de récupération et avez besoin de l’approbation d’une entreprise pour effectuer un retrait, vous faites probablement appel à un [dépositaire](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). [L’autogarde](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody) n’est pas une épreuve qui mesure votre valeur personnelle ; l’essentiel est de déterminer la confiance requise et les risques encourus.

**À vous de jouer :** Lisez les deux descriptions de portefeuilles préparées pour cet exercice. Pour chacune, indiquez qui contrôle les clés, qui pourrait rétablir l’accès et un risque à examiner avant d’utiliser le portefeuille.
