# 9.20 Paiements on-chain et Lightning

Utilisez une comparaison qui distingue le parcours du paiement de la [garde des fonds](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody).


| Question | On-chain | Lightning |
| --- | --- | --- |
| Où le règlement est-il enregistré ? | Directement dans la blockchain de Bitcoin | Les mises à jour des paiements s’effectuent sur un réseau construit au-dessus de Bitcoin ; les canaux dépendent en dernier ressort de Bitcoin |
| Informations courantes pour recevoir un paiement lorsqu’on débute | Adresse on-chain | Facture, adresse Lightning prise en charge ou autre type de demande approuvé |
| Usage courant | Règlement sur la couche de base, souvent pour des transferts plus importants ou moins fréquents | Souvent des paiements de faible montant ou fréquents, lorsque les outils locaux et la liquidité le permettent |
| Délais | La première confirmation dépend de l’inclusion dans un bloc | Souvent rapide, mais les paiements peuvent échouer |
| Frais et capacité | Dépendent des données de la transaction et de la demande d’espace dans les blocs | Dépendent du portefeuille, de l’itinéraire, de la liquidité, du service et des conditions de paiement |
| Garde des fonds | Peut être confiée à un tiers ou assurée par l’utilisateur | Peut être confiée à un tiers ou assurée par l’utilisateur |
| Principaux points à vérifier lorsqu’on débute | Adresse, réseau, montant, frais et confirmation corrects | Facture ou destination, montant, expiration, frais et résultat du paiement corrects |


Lightning n’est pas une monnaie distincte. Un paiement Lightning réussi ne prouve pas que le portefeuille est sûr pour un solde plus élevé. Le fonctionnement des canaux, l’infrastructure de routage et la [liquidité](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) et sa gestion relèvent de l’[Apprentissage avancé](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) en dehors du cadre du diplôme Bitcoin.


<!-- micrographic: on-chain-and-lightning-01 -->
