# 3.11 Ověřování, průzkumníky bloků a nevratné transakce

<!-- card: definition -->
> **Definition – Identifikátor transakce a průzkumník bloků**
>
> Každý [identifikátor transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) označuje blockchainovou [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Každý [průzkumník bloků](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) zobrazuje veřejná data sítě Bitcoin, například informace o [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction): její stav a [potvrzení](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) včetně jejich počtu. Poskytuje užitečný přehled, není však autoritou nad Bitcoinem ani důkazem totožnosti či poctivosti příjemce.


Co mohou tyto veřejné informace ukázat a co ukázat nemohou? Mohou ukázat informace o [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction): její stav, cíl, částku, poplatek a [potvrzení](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) včetně jejich počtu; nemohou prokázat, proč k platbě došlo nebo zda je daná osoba důvěryhodná. Blockchainová [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) je nepotvrzená poté, co je [rozšířena do sítě](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast), a získává své [první potvrzení](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) při zařazení do platného bloku. Další bloky zvyšují jistotu ohledně jejího místa v záznamu, ale nenapraví chybný cíl ani podvod. Neexistuje univerzální počet [potvrzení](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) pro všechny platby; vhodný způsob kontroly závisí na částce a riziku.

Chcete-li zkontrolovat připravenou [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), získejte její [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), otevřete důvěryhodný průzkumník pro zamýšlenou [síť Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) a zkontrolujte stav, cíl, částku, poplatek a [potvrzení](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Průzkumník je pouze rozhraní. Vyhledání adresy nebo [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) může jeho provozovateli prozradit, že se vaše zařízení o dané informace zajímá. K procvičování použijte vyučujícím připravenou [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) nebo vytištěný snímek obrazovky. Nevyhledávejte osobní adresu ani [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) studujícího prostřednictvím veřejné služby. Pokud budete později zkoumat osobní platbu, zjistěte, jaké [v oblasti soukromí](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) a bezpečnosti existují [kompromisy](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) u vašeho připojení, než použijete veřejnou službu.


<!-- card: callout -->
> **Veřejné údaje nejsou důkazem totožnosti ani poctivosti**
>
> Takový [prohlížeč bloků](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) může zobrazit veřejná [transakční](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) data, ale nemůže prokázat, kdo ovládá určitou adresu, proč platba proběhla nebo zda je příjemce důvěryhodný. Při procvičování používejte připravené příklady a chraňte [soukromí](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) při vyhledávání ve veřejných službách.



<!-- micrographic: confirmation-timeline-01 -->
[Transakce čeká nepotvrzená ve fondu čekajících transakcí, poté je zahrnuta do bloku N, čímž získá první potvrzení, a každý další blok přidává jedno další.](/micrographics/confirmation-timeline-01/cs.md)


![Vyučující a starší účastník kurzu diskutují o připraveném příkladu na monitoru natočeném ke skupině, zatímco technicky zdatný účastník ovládá myš; divák vidí zadní kryt monitoru.](https://cdn.sanity.io/images/vje9ehw2/staging/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
