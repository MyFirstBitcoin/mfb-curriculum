# 3.4 Clés

La propriété des bitcoins est garantie par des clés cryptographiques.


<!-- card: definition -->
> **Definition – Clé privée**
>
> Une [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) est une information secrète qui permet à un portefeuille de créer des [signatures numériques](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) valides. Une signature autorise la dépense des bitcoins contrôlés par la clé correspondante. Toute personne qui obtient la [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) peut généralement dépenser ces fonds.


Une [**clé publique**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) est dérivée mathématiquement de la [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Elle permet de vérifier une signature sans révéler la [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Les adresses sont créées en utilisant la [clé publique](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) comme source d’informations.

La règle essentielle est simple :

**Les informations publiques permettant de recevoir des bitcoins peuvent être partagées. Les informations privées permettant de les dépenser doivent rester secrètes.**

Une [signature numérique](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) prouve que la [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) requise a autorisé une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Elle n’intègre pas la [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) dans la [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Les nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) vérifient la signature avant d’accepter la dépense.

La plupart des portefeuilles destinés aux débutants utilisent la [signature unique](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature) : une seule clé privée autorise une transaction. Les portefeuilles modernes gèrent automatiquement de nombreuses clés. Les débutants ne doivent pas copier ni manipuler de [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) sous forme de chaîne de caractères individuelle. Protégez la sauvegarde recommandée par le portefeuille et suivez sa procédure de récupération.

Aucun formateur, fournisseur de portefeuille, employé de plateforme d’échange, technicien d’assistance ou développeur Bitcoin légitime n’a besoin de votre [clé privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ou de votre [phrase de récupération](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Toute personne qui vous les demande doit être considérée comme une menace.


<!-- card: light -->
> **À vous de jouer :** Classez les exemples préparés en trois groupes : les informations que vous pouvez partager sans risque pour recevoir des bitcoins, les informations secrètes permettant de les dépenser et les informations qui peuvent être publiques, mais doivent tout de même rester privées lorsqu’elles sont liées à une personne.



<!-- micrographic: private-key-public-info-01 -->
[Une clé privée secrète, qui ne doit jamais être partagée, permet de produire des informations publiques qui peuvent être partagées : une clé publique qui en est dérivée et une adresse de réception créée à partir de celle-ci. Cette même clé privée crée des signatures que les nœuds vérifient sans jamais connaître la clé privée.](/micrographics/private-key-public-info-01/fr-FR.md)
