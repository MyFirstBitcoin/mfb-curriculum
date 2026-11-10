# 2.10 Preuve de travail

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Preuve de travail**
>
> [La preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) est le processus que les [mineurs](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) utilisent pour se disputer le droit de proposer le prochain bloc.


Une [fonction de hachage](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) transforme des données en un résultat de longueur fixe. Une petite modification des données d’entrée produit un nouveau résultat imprévisible. Un [mineur](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) modifie une petite partie des données d’un bloc proposé et le hache à répétition. Un résultat n’est valide que si sa valeur numérique est inférieure à celle que le réseau fixe comme [cible](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), un seuil défini par les règles ; une [cible](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) plus basse signifie moins de [résultats valides](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) et davantage de tentatives. Il n’existe aucun raccourci, les [mineurs](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) peuvent donc devoir effectuer de nombreuses tentatives.

Lorsqu’un [mineur](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) trouve un [résultat valide](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), il [diffuse](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) le bloc. [Les nœuds](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) peuvent vérifier la preuve rapidement, même si sa recherche a nécessité d’importantes ressources de calcul et d’énergie. Si le bloc contient une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), cette [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) reçoit sa [première confirmation](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) : son enregistrement a été inclus dans un bloc valide. Chaque bloc valide ajouté à sa suite apporte une [confirmation](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) supplémentaire, ce qui rend la place de la [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dans la [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) plus coûteuse à réécrire. Cette différence est importante : le travail est coûteux à produire et facile à vérifier.


<!-- micrographic: proof-of-work-process-01 -->


[La preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) remplit plusieurs fonctions :

* elle donne aux [mineurs](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) indépendants un moyen de se faire concurrence sans ordonnanceur central
* elle rend l’ordre des [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) coûteux à réécrire
* elle lie la sécurité du réseau à des équipements et à de l’énergie du monde réel
* elle permet de choisir publiquement entre plusieurs historiques valides concurrents : la chaîne ayant le plus de [travail cumulé](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Le minage](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ne résout pas d’équations utiles à des fins externes. Son objectif est de sécuriser, sur Bitcoin, l’ordre des [transactions](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Le réseau ajuste périodiquement la cible : lorsque les blocs arrivent trop rapidement, il abaisse la cible, et lorsqu’ils arrivent trop lentement, il la relève, afin de maintenir un rythme moyen d’environ un bloc toutes les dix minutes malgré les variations de la puissance de calcul.

[La preuve de travail](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) implique un coût énergétique réel. Ses partisans soutiennent que ce coût constitue le fondement de la sécurité de Bitcoin et peut créer une demande d’énergie dont la consommation peut être modulée ou qui resterait autrement inutilisée. Ses détracteurs remettent en question la quantité et la provenance de l’énergie utilisée. Une évaluation responsable consiste à se demander quelle énergie est utilisée, d’où elle provient, quelle sécurité elle assure et quelles solutions alternatives sont comparées.

![La personne qui enseigne, la personne qui débute et la personne au profil technique discutent d’un appareil de minage posé sur une table, doté d’un ventilateur et d’une alimentation séparée.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
