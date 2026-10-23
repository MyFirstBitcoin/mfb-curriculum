# 4.5 Paiements Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning peut rendre pratiques les petits paiements rapides en Bitcoin. Il peut convenir aux paiements au comptoir d’un commerce, aux paiements locaux répétés, aux services en ligne ou aux transferts pour lesquels les frais d’une transaction sur la blockchain seraient trop élevés par rapport au montant du paiement.

Une démonstration locale de Lightning doit préciser :

* si le portefeuille est avec garde par un tiers ou en autogarde
* comment le portefeuille est alimenté
* si son alimentation nécessite, sur la blockchain, une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ou un service
* quel dispositif de sauvegarde ou de récupération protège le solde
* quel type de demande de paiement est utilisé
* quels frais ou quelles limites s’appliquent
* ce qui se passe lorsqu’un paiement échoue
* comment le destinataire confirme le paiement

Une [**facture Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) est une demande de paiement créée pour un paiement précis. Elle peut inclure un montant, des informations sur la destination et une date et heure d’expiration. Consultez l’écran de [confirmation](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) du portefeuille avant de payer.

Une [**adresse Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) est un identifiant lisible par un humain, pris en charge par certains services. Elle peut ressembler à une adresse e-mail, mais elle sert à faciliter l’acheminement des paiements et n’est pas un compte de messagerie. Elle dépend du fournisseur ou du domaine qui la prend en charge.

Pour un paiement guidé :

1. Le destinataire crée la demande appropriée.
1. L’expéditeur la scanne ou la copie.
1. L’expéditeur vérifie le destinataire, le montant, l’unité et les frais.
1. L’expéditeur ne valide qu’après avoir vérifié que les détails sont corrects.
1. Les deux parties confirment le résultat dans leurs portefeuilles respectifs.
1. Le groupe explique les risques liés à la [garde](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) et aux échecs de paiement.

Ne supposez pas qu’un paiement Lightning réussi prouve que le portefeuille est sûr pour des soldes plus importants. La facilité de paiement et la sécurité de la [garde](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) sont deux questions distinctes.
