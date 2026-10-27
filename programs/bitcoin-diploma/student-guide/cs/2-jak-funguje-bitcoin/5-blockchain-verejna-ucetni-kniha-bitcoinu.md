# 2.5 Blockchain: veřejná účetní kniha Bitcoinu

<!-- card: definition -->
> **Definition – Blockchain**
>
> Bitcoinový [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) je veřejný [transakční](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) záznam replikovaný na mnoha nezávislých počítačích. Blok sdružuje sadu platných [transakcí](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) do další navrhované části tohoto záznamu. Každý platný blok odkazuje na předchozí blok, čímž síti poskytuje uspořádanou sdílenou historii, kterou lze ověřovat.



<!-- card: light -->
> **Jak uzly dosahují konsenzu**
>
> [Uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) nezávisle kontrolují dodržování stejných pravidel a shodují se na platné historii s největším množstvím nahromaděného [důkazu prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Změna dřívějšího záznamu změní jeho blok a naruší návaznost pozdějších bloků, takže konkurenční historie musí tuto práci provést znovu a dohnat stávající historii, než ji [uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) přijmou. Tento nákladný proces určování pořadí pomáhá síti dosáhnout [konsenzu](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) bez centrálního správce záznamů. Kopie se nemění současně; [uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) přijímají a ověřují data nezávisle. Bitcoin cílí v průměru na jeden nový blok přibližně každých deset minut. Přepsat historii je obtížné a nákladné, nikoli však doslova nemožné: mohou se vyskytnout dočasné konkurenční historie a reorganizace.
