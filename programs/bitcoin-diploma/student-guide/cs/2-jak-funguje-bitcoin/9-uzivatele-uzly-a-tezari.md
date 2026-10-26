# 2.9 Uživatelé, uzly a těžaři

Bitcoin funguje, protože různí účastníci plní různé role.

* **Uživatelé** přijímají, drží a posílají bitcoin. Uživatel může mít pod kontrolou vlastní klíče uložené v peněžence nebo využít služeb [správce](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Uživatelé dávají síti ekonomický smysl tím, že se rozhodují, zda budou přijímat bitcoin a kterým pravidlům či službám budou důvěřovat.
* [**Uzly**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) provozují software sítě Bitcoin a nezávisle ověřují dodržování pravidel. Každý [plný uzel](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) kontroluje, zda [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mají platné podpisy, zda bitcoiny již nebyly utraceny, zda bloky splňují požadavky [důkazu prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) a zda se nové bitcoiny vydávají podle [emisního plánu](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) sdílejí platná data s ostatními uzly a neplatná data odmítají.
* [**Těžaři**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) shromažďují čekající [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), sestavují [kandidátní bloky](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) a soutěží prostřednictvím [důkazu prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Úspěšný [těžař](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [rozešle](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok do sítě a může získat povolenou [blokovou subvenci](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) a [transakční poplatky](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Těžaři](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pomáhají určovat pořadí [transakcí](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) a zajišťují, že [účetní knihu](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) lze přepsat jen s vysokými náklady.
* **Vývojáři** kontrolují, píší a navrhují změny softwaru. Pravidla Bitcoinu jim nepatří. Změna softwaru má význam pouze tehdy, pokud se účastníci rozhodnou provozovat software, který se těmito pravidly řídí.


<!-- micrographic: bitcoin-participant-roles-01 -->


Tyto role se navzájem omezují:

* uživatel nemůže utratit bitcoin bez požadovaného platného podpisu
* takový [těžař](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) může navrhnout blok, ale [uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) rozhodují, zda odpovídá pravidlům
* jeden [uzel](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ověřuje podle vlastních pravidel, ale [konsenzus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) vyžaduje slučitelná pravidla napříč sítí
* vývojáři mohou navrhovat software, ale účastníci se rozhodují, zda jej budou používat

Někteří lidé zastávají několik rolí. [Těžař](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) může provozovat [uzel](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) a zároveň být uživatelem. Začátečník nemusí zastávat všechny role, aby dokázal vysvětlit, jak se tyto role navzájem vyvažují.

**Kontrolní otázka:** Proč [uzel](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ověřuje [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Uveďte alespoň jedno pravidlo, které [uzel](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontroluje.

![Vyučující vede technicky zaměřeného studenta u počítače, na kterém běží uzel. Monitor je otočený k nim a divák vidí jeho zadní kryt.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
