# How Transations Work

## Alt text

Un schéma vertical en sept étapes illustrant un paiement en bitcoins d'Alice à Bob : création et signature d'une transaction, diffusion de celle-ci, vérification par les nœuds, le mempool, intégration dans un bloc via le minage, puis ajout du bloc à la blockchain à mesure que les confirmations s'accumulent.

## Texts

### s1-label

Alice crée une transaction

### s1-desc

Elle précise qui reçoit les pièces, en quelle quantité, ainsi que la commission versée aux mineurs.

### r-to

À

### r-to-v

L'adresse de Bob

### r-amount

Montant

### r-fee

Frais de réseau

### s2-label

Elle le signe avec sa clé privée

### s2-desc

La signature numérique prouve que ces pièces lui appartiennent et qu'elle est libre de les dépenser.

### s3-label

Diffuser sur le réseau

### s3-desc

La transaction signée est envoyée aux nœuds, qui vérifient qu'elle respecte les règles.

### chip-sig

Signature valide

### chip-bal

Assez de bitcoins

### chip-rules

Respecte les règles

### s4-label

Elle attend dans le mempool

### s4-desc

Les transactions valides sont placées en attente dans un pool de paiements en attente.

### s5-label

Les mineurs l'intègrent dans un bloc

### s5-desc

Les mineurs sélectionnent des transactions et se font concurrence pour miner un bloc.

### s6-label

Le bloc est ajouté à la blockchain

### s6-desc

Les autres nœuds vérifient le bloc, puis l'intègrent définitivement à la chaîne.

### s7-label

Bob reçoit des bitcoins

### s7-desc

La transaction est désormais validée. Alice ne peut plus dépenser ces pièces, tandis que Bob peut dépenser ce qu'il a reçu.

### foot

<strong>Chaque nouveau bloc renforce le caractère définitif de la transaction.</strong> À mesure que les blocs s'ajoutent les uns aux autres, il devient de plus en plus difficile, de manière exponentielle, de revenir sur une transaction — c'est ce qui confère au bitcoin son caractère définitif.
