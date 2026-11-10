# 3.6 Používání se správou třetí stranou a s vlastní správou

<!-- card: definition -->
> **Definition – Správa prostředků**
>
> [Správa prostředků](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) odpovídá na praktickou otázku: kdo ovládá klíče potřebné k utrácení bitcoinů?


Ve **správcovské** službě ovládá klíče společnost nebo jiná osoba. Váš zobrazený zůstatek je příslibem od [správce](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Obvykle se přihlašujete ke svému účtu a žádáte službu o zpracování výběru nebo platby.

Tento rozdíl je důležitý pro ověřování. Pravidla Bitcoinu a celkové množství bitcoinů lze ověřit nezávisle, ale pokud neovládáte klíče, nemůžete nezávisle ověřit, že zůstatek zobrazený na vašem účtu odpovídá bitcoinům, které služba drží a zpřístupní vám. Veřejný blockchain může ukázat bitcoiny ovládané pomocí klíčů; nemůže ukázat, že služba dluží konkrétnímu zákazníkovi zůstatek zobrazený na účtu. Dokud nemůžete provést výběr a převzít kontrolu nad klíči, je váš zůstatek příslibem služby, že vám poskytne bitcoiny, nikoli bitcoiny, které si můžete sami přímo ověřit a utratit.

V **nesprávcovské** neboli **uživatelem spravované** peněžence ovládáte klíče VY. Peněženka podepisuje [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) z vašeho pověření. Stále mohou existovat závislosti na softwaru, hardwaru, serverech či síti, ale žádný [správce](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) nemusí schvalovat platné utracení prostředků přímo na blockchainu.

![](https://cdn.sanity.io/images/vje9ehw2/production/f93df0cc4a2ad82b3410a9ad4c3273d1b760f8ea-1774x887.svg)


<!-- micrographic: who-controls-keys-01 -->
[Při úschově u poskytovatele má poskytovatel kontrolu nad klíči a schvaluje platby, takže zůstatek je jeho příslibem. Při vlastní úschově má uživatel kontrolu nad klíči a zálohami; oba způsoby mají své závislosti a rizika selhání.](/micrographics/who-controls-keys-01/cs.md)



<!-- micrographic: custody-comparison-table-01 -->
[Tabulka porovnávající používání se správou třetí stranou a s vlastní správou: kdo drží klíče, kdo zajišťuje obnovení přístupu a jaký je hlavní kompromis u každého z nich. Ani jeden model není bez rizika.](/micrographics/custody-comparison-table-01/cs.md)


[Správa prostředků](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) není z uživatelského rozhraní vždy zřejmá. Pokud nemáte kontrolu nad způsobem obnovení přístupu a potřebujete, aby společnost schválila výběr, pravděpodobně využíváte [správce](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). [Vlastní správa prostředků](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody) není zkouškou vaší osobní hodnoty; důležité je rozpoznat, komu důvěřujete a jaká rizika podstupujete.

**Vyzkoušejte si:** Přečtěte si dva připravené popisy peněženek. U každé uveďte, kdo ovládá klíče, kdo by mohl obnovit přístup a jedno riziko, které je třeba prověřit před jejím použitím.
