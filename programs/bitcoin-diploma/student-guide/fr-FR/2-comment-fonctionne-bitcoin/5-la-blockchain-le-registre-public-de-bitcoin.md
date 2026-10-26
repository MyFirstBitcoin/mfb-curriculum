# 2.5 La blockchain : le registre public de Bitcoin

> **Definition – Blockchain**
>
> Bitcoin possède une [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) qui est un registre public de [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) répliqué sur de nombreux ordinateurs indépendants. Un bloc regroupe un ensemble de [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) valides dans la prochaine partie proposée pour ce registre. Chaque bloc valide est lié au précédent, ce qui fournit au réseau un historique partagé et ordonné à vérifier.



> **Definition – Nœud**
>
> [Les nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) vérifient indépendamment les mêmes règles et convergent vers l’historique valide qui cumule le plus de [preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Modifier une entrée antérieure du registre modifie son bloc et rompt les liens avec les blocs suivants. Un historique concurrent doit donc refaire ce travail et rattraper son retard avant que les [nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ne l’acceptent. Ce processus coûteux de mise en ordre aide le réseau à parvenir à un [consensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) sans responsable central du registre. Les copies ne changent pas simultanément ; les [nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) reçoivent et valident les données indépendamment. Bitcoin vise un nouveau bloc toutes les dix minutes environ, en moyenne. L’historique est difficile et coûteux à réécrire, mais il n’est pas littéralement impossible à modifier : des historiques concurrents temporaires et des réorganisations peuvent survenir.
