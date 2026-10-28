# 2.9 Gebruikers, nodes en miners

Bitcoin werkt omdat verschillende deelnemers verschillende rollen vervullen.

* **Gebruikers** ontvangen, bewaren en versturen bitcoin. Een gebruiker kan zijn eigen sleutels in een Wallet beheren of een [bewaarder](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) gebruiken. Gebruikers geven het netwerk economische betekenis door te kiezen of zij bitcoin accepteren en welke regels of diensten zij vertrouwen.
* [**Nodes**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) draaien Bitcoin-software en controleren de regels onafhankelijk. Een [full Node](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) controleert of [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) geldige handtekeningen hebben, of bitcoin niet al zijn uitgegeven, of blocks voldoen aan [Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) en of nieuwe bitcoin het [uitgifteschema](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule) volgen. [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) delen geldige gegevens met peers en weigeren ongeldige gegevens.
* [**Miners**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) verzamelen openstaande [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), bouwen [kandidaat-blocks](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) en concurreren via [Proof-of-Work](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Een succesvolle [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [verspreidt](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) een block en kan de toegestane [Block subsidy](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) en [transactiekosten](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee) ontvangen. [Miners](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) helpen [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) te ordenen en maken het [Grootboek](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) kostbaar om te herschrijven.
* **Ontwikkelaars** beoordelen, schrijven en stellen softwarewijzigingen voor. Zij zijn geen eigenaar van de regels van Bitcoin. Een softwarewijziging doet er alleen toe als deelnemers ervoor kiezen software te draaien die deze regels volgt.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Vier rollen in Bitcoin: gebruikers ontvangen, bewaren en versturen bitcoin, nodes controleren zelfstandig de regels, miners stellen kandidaat-blokken samen met proof of work en ontwikkelaars stellen software voor. Geen enkele rol heeft zeggenschap over het netwerk.](/micrographics/bitcoin-participant-roles-01/nl.md)


Deze rollen begrenzen elkaar:

* een gebruiker kan geen bitcoin uitgeven zonder de vereiste geldige handtekening
* een [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan een block voorstellen, maar [Nodes](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) beslissen of het de regels volgt
* een [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) controleert aan de hand van zijn eigen regels, maar [consensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) vereist compatibele regels in het hele netwerk
* ontwikkelaars kunnen software voorstellen, maar deelnemers kiezen zelf of ze die draaien

Sommige mensen vervullen meerdere rollen. Een [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan een [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) draaien en tegelijk gebruiker zijn. Een beginner hoeft niet elke rol zelf te vervullen om uit te leggen hoe de rollen elkaar in evenwicht houden.

**Controlevraag:** Waarom controleert een [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) de [transacties](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Noem ten minste één regel die een [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) controleert.

![De docent begeleidt de technisch onderlegde leerling bij een node-computer; de monitor is naar hen toe gericht en de achterkant van de behuizing is zichtbaar voor de kijker.](https://cdn.sanity.io/images/vje9ehw2/production/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
