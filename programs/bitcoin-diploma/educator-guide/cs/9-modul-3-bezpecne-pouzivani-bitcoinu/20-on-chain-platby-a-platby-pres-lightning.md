# 9.20 On-chain platby a platby přes Lightning

Použijte srovnání, které odděluje platební cestu od [úschovy prostředků](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody).


| Otázka | On-chain | Lightning |
| --- | --- | --- |
| Kde se zaznamenává vypořádání? | Přímo v blockchainu Bitcoinu | Aktualizace plateb probíhají prostřednictvím sítě vybudované nad Bitcoinem; kanály jsou v konečném důsledku závislé na Bitcoinu |
| Běžné údaje pro příjem plateb u začátečníků | On-chain adresa | Faktura, podporovaná lightningová adresa nebo jiný schválený typ platebního požadavku |
| Typické využití | Vypořádání na základní vrstvě, často větší nebo méně časté převody | Často malé nebo časté platby tam, kde je podporují místní nástroje a dostupná likvidita |
| Rychlost | První potvrzení závisí na zařazení do bloku | Často rychlé, ale platby mohou selhat |
| Poplatky a kapacita | Závisí na transakčních datech a poptávce po prostoru v blocích | Závisí na peněžence, trase, likviditě, službě a podmínkách platby |
| Úschova prostředků | Prostředky mohou být ve správě třetí strany nebo ve vlastní správě | Prostředky mohou být ve správě třetí strany nebo ve vlastní správě |
| Hlavní kontrola pro začátečníky | Správná adresa, síť, částka, poplatek a potvrzení | Správná faktura nebo cíl platby, částka, doba platnosti, poplatek a výsledek platby |


Lightning není samostatná mince. Úspěšná lightningová platba nedokazuje, že je peněženka bezpečná pro uložení vyššího zůstatku. Provoz kanálů, infrastruktura směrování a problematika [likvidity](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) a jejího řízení patří do [pokročilého studia](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) nad rámec programu Bitcoin Diploma.


<!-- micrographic: on-chain-and-lightning-01 -->
[Platby na blockchainu se zaznamenávají přímo do blockchainu Bitcoinu, zatímco Lightning je platební síť postavená na Bitcoinu pro rychlé a časté platby, které však mohou i selhat. Obě možnosti mohou využívat správu prostředků třetí stranou nebo vlastní správu prostředků.](/micrographics/on-chain-and-lightning-01/cs.md)
