# How Transations Work

## Alt text

Svislý diagram se sedmi kroky znázorňující bitcoinovou platbu, kterou Alice posílá uživateli Bob: vytvoření a podepsání transakce, její odeslání do sítě, ověření uzly, čekání v mempoolu, vytěžení bloku s transakcí a přidání bloku do blockchainu s postupně přibývajícími potvrzeními.

## Texts

### s1-label

Alice vytvoří transakci

### s1-desc

Určí, kdo mince obdrží, v jakém množství a jaký bude poplatek pro těžaře.

### r-to

Komu

### r-to-v

Adresa uživatele Bob

### r-amount

Částka

### r-fee

Síťový poplatek

### s2-label

Podepíše ji svým soukromým klíčem

### s2-desc

Digitální podpis dokazuje, že má právo tyto mince utratit.

### s3-label

Odeslání do sítě

### s3-desc

Podepsaná transakce se odešle uzlům, které zkontrolují, zda splňuje pravidla.

### chip-sig

Platný podpis

### chip-bal

Dostatek bitcoinů

### chip-rules

Splňuje pravidla

### s4-label

Čeká v mempoolu

### s4-desc

Platné transakce čekají v zásobníku nevyřízených plateb.

### s5-label

Těžaři ji zahrnou do bloku

### s5-desc

Těžaři vybírají transakce a soutěží o vytěžení bloku.

### s6-label

Blok se připojí k blockchainu

### s6-desc

Ostatní uzly blok ověří a poté ho natrvalo připojí k řetězci.

### s7-label

Bob obdrží bitcoiny

### s7-desc

Transakce je nyní potvrzená. Alice už tyto mince nemůže znovu utratit a Bob může utratit to, co obdržel.

### foot

<strong>Každý nový blok dále potvrzuje transakci.</strong> S každým dalším přidaným blokem je její zvrácení exponenciálně obtížnější &#8212; právě díky tomu jsou bitcoinové platby konečné.
