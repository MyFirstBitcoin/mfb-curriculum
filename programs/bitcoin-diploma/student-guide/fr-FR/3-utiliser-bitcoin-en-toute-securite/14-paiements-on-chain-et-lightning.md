# 3.14 Paiements on-chain et Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Paiements on-chain et Lightning**
>
> [Les paiements on-chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) sont enregistrés sur Bitcoin dans sa [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) et reçoivent des [confirmations](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning est un réseau de paiement construit sur Bitcoin qui permet des paiements rapides et fréquents. Un paiement Lightning peut aboutir rapidement ou échouer, et le portefeuille utilisé peut être avec garde par un tiers ou en autogarde.



> **Dark – La voie de paiement ne détermine pas le mode de garde**
>
> Les paiements on-chain et Lightning impliquent différents [compromis](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Un portefeuille Lightning peut être avec garde par un tiers ou en autogarde, et un paiement rapide et réussi ne prouve pas qu’un service convient à des soldes plus importants ou à toutes les situations.



<!-- micrographic: onchain-lightning-table-01 -->


Quelle voie de paiement le destinataire attend-il ? Avant de payer, vérifiez s’il a fourni une adresse on-chain ou une [facture Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) ou une demande de paiement. Un portefeuille on-chain ne peut pas régler directement toutes les [factures Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), et un portefeuille Lightning ne prend pas nécessairement en charge toutes les opérations on-chain. Certaines applications prennent en charge les deux voies, mais peuvent ajouter des frais ou des dépendances à des services. La configuration détaillée de Lightning, les canaux, le routage et la [liquidité](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) relèvent de la section [Approfondissement](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) ; la pratique en conditions réelles, sur place, relève du **Module 4** lorsque les conditions sont sûres et appropriées.

Imaginez qu’un scénario préparé propose les deux voies de paiement. Quelle demande le portefeuille prévu peut-il utiliser, et que vérifieriez-vous avant de l’approuver ? La réponse dépend de la demande de paiement du destinataire, du portefeuille et de la situation — et non d’une voie universellement « meilleure ».

![L’enseignant montre sur un tableau deux voies de paiement représentées par des tracés géométriques différents, tandis que les apprenants débutants et techniques les examinent.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
