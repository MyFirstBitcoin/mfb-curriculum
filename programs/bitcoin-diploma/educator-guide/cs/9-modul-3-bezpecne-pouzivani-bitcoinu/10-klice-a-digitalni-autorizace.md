# 9.10 Klíče a digitální autorizace

Zdůrazňujte toto praktické pravidlo:

> Veřejné údaje pro příjem plateb lze sdílet. Soukromé údaje pro utrácení musí zůstat v tajnosti.

Vysvětlete:

* každý [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) opravňuje k utrácení prostřednictvím [digitálního podpisu](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature)
* každý [veřejný klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) umožňuje ověření bez odhalení [soukromého klíče](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key)
* moderní peněženky automaticky spravují mnoho klíčů; a
* začátečníci by neměli kopírovat nezpracované [soukromé klíče](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) v podobě řetězců ani s nimi manipulovat.

Nepoužívejte tvrzení „váš [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) dokazuje, kdo jste“. Dokazuje oprávnění dané klíčem, nikoli právní totožnost.

Žádný důvěryhodný pedagog, společnost poskytující peněženku, zaměstnanec burzy, vývojář, pracovník podpory ani veřejně známá osobnost nepotřebuje studentův [soukromý klíč](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ani [obnovovací frázi](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase).


<!-- micrographic: private-key-public-info-01 -->
[Z tajného soukromého klíče, který se nikdy nesmí sdílet, se odvozují veřejné informace, které sdílet lze: veřejný klíč odvozený ze soukromého klíče a přijímací adresa vytvořená z veřejného klíče. Tentýž soukromý klíč vytváří podpisy, které uzly ověřují, aniž by kdy zjistily soukromý klíč.](/micrographics/private-key-public-info-01/cs.md)
