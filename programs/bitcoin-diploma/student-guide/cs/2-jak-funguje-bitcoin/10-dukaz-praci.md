# 2.10 Důkaz prací

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Důkaz prací**
>
> [Důkaz prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) je proces, který [těžaři](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) využívají k soutěži o právo navrhnout další blok.


Každá [hašovací funkce](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) převádí data na výsledek pevné délky. Malá změna vstupu vede k nepředvídatelnému novému výsledku. [Těžař](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mění malou část dat v navrhovaném bloku a opakovaně jej hašuje. Výsledek je platný pouze tehdy, když je jeho číselná hodnota nižší než síťová [cílová hodnota](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), tedy mez stanovená pravidly; nižší [cílová hodnota](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) znamená méně [platných výsledků](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) a více pokusů. Žádná zkratka neexistuje, takže [těžaři](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mohou potřebovat mnoho pokusů.

Když [těžař](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) najde [platný výsledek](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), [rozešle](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok. [Uzly](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) mohou důkaz rychle ověřit, přestože jeho nalezení vyžadovalo značné množství výpočtů a energie. Pokud blok obsahuje [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), tato [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) získává své [první potvrzení](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): její záznam byl zahrnut do jednoho platného bloku. Každý další platný blok přidaný za tento blok přidává další [potvrzení](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), takže je pozici [transakce](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) v [blockchainu](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) nákladnější přepsat. Tento rozdíl je důležitý: vykonání práce je nákladné, ale její ověření je snadné.


<!-- micrographic: proof-of-work-process-01 -->
[Těžař opakovaně počítá hash navrženého bloku, dokud jeden výsledek není nižší než cílová hodnota sítě, a poté blok rozešle. Než se blok připojí k blockchainu, uzly rychle ověří důkaz a dodržení všech pravidel: vykonat práci je nákladné, ale ověřit ji je snadné.](/micrographics/proof-of-work-process-01/cs.md)


[Důkaz prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) slouží několika účelům:

* umožňuje nezávislým [těžařům](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) soutěžit bez centrálního plánovače
* činí přepisování pořadí [transakcí](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) nákladným
* propojuje bezpečnost sítě s fyzickým vybavením a energií
* podporuje veřejnou metodu výběru mezi soupeřícími platnými historiemi: řetězec s největším množstvím [nahromaděné práce](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Těžba](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) neřeší užitečné rovnice pro nějaký vnější účel. Jejím účelem je zabezpečit v síti Bitcoin pořadí [transakcí](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Síť pravidelně upravuje cílovou hodnotu: když bloky přicházejí příliš rychle, snižuje ji, a když přicházejí příliš pomalu, zvyšuje ji. Cílem je udržet průměrné tempo přibližně jednoho bloku každých deset minut i při změnách výpočetního výkonu.

[Důkaz prací](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) s sebou nese skutečné energetické náklady. Zastánci tvrdí, že právě tyto náklady jsou základem bezpečnosti Bitcoinu a mohou vytvářet poptávku po energii z flexibilních zdrojů nebo po energii, která by jinak zůstala nevyužitá. Kritici zpochybňují množství a původ spotřebované energie. Odpovědné posouzení zkoumá, jaká energie se využívá, odkud pochází, jakou bezpečnost zajišťuje a jaké alternativy se porovnávají.

![Vyučující, začínající studující a technicky zaměřený studující diskutují o stolním těžebním zařízení s ventilátorem a samostatným napájecím zdrojem.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
