# 3.11 Vérification, explorateurs de blocs et transactions irréversibles

> **Definition – Identifiant de transaction et explorateur de blocs**
>
> Un [identifiant de transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identifie, sur la blockchain, une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Un [explorateur de blocs](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) affiche des données publiques de Bitcoin, comme le statut d’une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) et son nombre de [confirmations](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Il offre une vue utile, mais ne constitue ni une autorité sur Bitcoin ni une preuve de l’identité ou de l’honnêteté du destinataire.


Que peuvent montrer ces informations publiques, et que ne peuvent-elles pas montrer ? Elles peuvent montrer le statut d’une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), sa destination, son montant, ses frais et son nombre de [confirmations](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) ; elles ne peuvent pas prouver pourquoi un paiement a eu lieu ni si une personne est digne de confiance. Sur la blockchain, une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) est non confirmée après sa [diffusion](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) et obtient sa [première confirmation](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) lorsqu’elle est incluse dans un bloc valide. Les blocs suivants renforcent la confiance dans sa place dans l’historique, mais ne corrigent ni une destination erronée ni une escroquerie. Il n’existe pas de nombre universel de [confirmations](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) valable pour tous les paiements ; la vérification appropriée dépend du montant et du risque.

Pour examiner une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) préparée à l’avance, obtenez son [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), ouvrez un explorateur fiable pour le [réseau Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) visé, puis vérifiez le statut, la destination, le montant, les frais et les [confirmations](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Un explorateur n’est qu’une interface. La recherche d’une adresse ou d’un [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) peut révéler à son opérateur que votre appareil s’intéresse à ces informations. Pour vous exercer, utilisez une [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) préparée par un enseignant ou une capture d’écran imprimée. Ne recherchez pas l’adresse personnelle ou la [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) d’un apprenant sur un service public. Si vous faites ensuite des recherches sur un paiement personnel, comprenez, en matière de [confidentialité](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) et de sécurité, les [compromis](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) qu’implique votre connexion avant d’utiliser un service public.


> **Callout – Les données publiques ne prouvent ni l’identité ni l’honnêteté**
>
> Un [explorateur de blocs](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) peut afficher des données publiques de [transaction](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mais il ne peut pas prouver qui contrôle une adresse, pourquoi un paiement a eu lieu ou si un destinataire est digne de confiance. Utilisez des exemples préparés pour vous entraîner et protégez votre [vie privée](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) lorsque vous effectuez des recherches sur des services publics.



<!-- micrographic: confirmation-timeline-01 -->


![L’enseignant et l’apprenant plus âgé discutent d’un exemple préparé sur un écran tourné vers le groupe tandis que l’apprenant au profil technique manipule la souris ; l’écran est vu de dos.](https://cdn.sanity.io/images/vje9ehw2/staging/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
