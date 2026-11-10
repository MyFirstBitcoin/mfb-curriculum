# 2.3 Wczesne próby stworzenia pieniądza cyfrowego i problem podwójnego wydatkowania

Bitcoin nie był pierwszą próbą stworzenia pieniądza cyfrowego. Powstał na podstawie czterech dekad eksperymentów, czerpiąc z pomysłów wielu wcześniejszych projektów, które pomogły ukształtować jego udaną konstrukcję.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) wykorzystywał [kryptografię](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) do obsługi prywatnych płatności cyfrowych. Był zależny od jednej centralnej firmy i współpracy z bankami. Gdy firma upadła, system nie mógł dalej funkcjonować jako niezależna sieć pieniężna.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) wykorzystywał [dowód pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) do zwiększenia kosztu wysyłania niechcianych wiadomości e-mail. Komputer nadawcy musiał wykonać pracę przed wysłaniem wiadomości. Pomysł ten pokazał, jak koszt obliczeniowy może zniechęcać do nadużyć.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) opisywał proponowany system, w którym praca obliczeniowa mogłaby tworzyć rzadkie zapisy cyfrowe. Nie został uruchomiony jako kompletny zdecentralizowany system pieniężny, ale rozwinął ważne koncepcje dotyczące cyfrowej [rzadkości](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) i dowodu.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) i [**dowód pracy wielokrotnego użytku (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) badały sposoby, w jakie uczestnicy mogliby tworzyć lub przekazywać rzadką cyfrową [wartość](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) bez polegania wyłącznie na jednej centralnej bazie danych. Były niekompletne, ale pomogły sprecyzować, czego potrzebowałby działający system.
* Chociaż [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) nie był pieniądzem, pokazał, że [sieć peer-to-peer](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) może umożliwiać wielu niezależnym komputerom wymianę informacji bez jednego centralnego serwera kontrolującego cały system.

Łącznie eksperymenty te dostarczyły przydatnych elementów układanki. Pomogły też sprecyzować problem, który wciąż pozostawał do rozwiązania.


<!-- card: definition -->
> **Definition – Podwójne wydawanie**
>
> [Podwójne wydawanie](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) to próba wysłania tej samej jednostki cyfrowej do dwóch odbiorców. Dane cyfrowe można kopiować bez żadnych zmian, dlatego system pieniądza cyfrowego potrzebuje sposobu na ustalenie, która [transakcja](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) jest ważna.


[Systemy scentralizowane](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) zapobiegają temu, pozwalając jednej zaufanej bazie danych rozstrzygać, która płatność była pierwsza. 31 października 2008 roku [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) w swojej białej księdze, [_Bitcoin: elektroniczny system pieniężny peer-to-peer_](https://bitcoin.org/bitcoin.pdf), wyjaśnił inne podejście: publiczny system, który mógłby ustalać wspólną historię płatności bez banku, firmy ani innego centralnego organu.

Biała księga połączyła cechy niezbędne do zastosowania tego podejścia:

1. **Jedna [sieć peer-to-peer](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transakcje](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) są ogłaszane bezpośrednio w sieci uczestników.
1. **[Podpisy cyfrowe](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** jeden [klucz prywatny](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) to tajna informacja służąca do tworzenia podpisu zatwierdzającego wydanie środków; może to zrobić wyłącznie jego posiadacz.
1. **Bloki i [wydobywanie](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [górnicy](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) zbierają [transakcje](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) w bloki i korzystają z [dowodu pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), aby rywalizować o dodanie kolejnego bloku.
1. **Niezależna [weryfikacja](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [węzły](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) sprawdzają [transakcje](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i bloki pod kątem zgodności z zasadami Bitcoina.
1. **Wspólna historia ze skumulowanym [dowodem pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** uczestnicy uznają [prawidłowy łańcuch](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) obejmujący [transakcje](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) z największą ilością [skumulowanej pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) za wspólny zapis.


<!-- micrographic: five-part-response-01 -->
[Pięć elementów wspólnie rozwiązuje problem podwójnego wydawania środków: sieć peer-to-peer, podpisy cyfrowe, bloki i wydobywanie, niezależna weryfikacja oraz wspólna historia o największym skumulowanym dowodzie pracy. Razem pozwalają sieci odrzucić ponowne wydanie tych samych środków bez udziału centralnego organu.](/micrographics/five-part-response-01/pl.md)


Ten moduł wyjaśnia te pojęcia bardziej szczegółowo. Razem dały one praktyczne rozwiązanie [problemu podwójnego wydawania](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): sieć może odrzucić drugą próbę wydania tego samego bitcoina bez polegania na centralnym organie. Bitcoin zaoferował brakujące połączenie rozwiązań, którego poszukiwano przez dziesięciolecia eksperymentów z pieniądzem cyfrowym.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
