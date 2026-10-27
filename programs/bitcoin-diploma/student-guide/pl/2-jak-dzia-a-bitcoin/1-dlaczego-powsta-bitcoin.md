# 2.1 Dlaczego powstał Bitcoin

Płatności cyfrowe istniały przed Bitcoinem. Ludzie mogli przesyłać pieniądze za pośrednictwem banków, sieci kart płatniczych i firm obsługujących płatności internetowe. Systemy te ułatwiały handel, ale każdy z nich zależał od zaufanej organizacji, która miała prowadzić [rejestr](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger), zatwierdzać konta, rozliczać przelewy i rozstrzygać spory.

Ta zależność daje władzę i stwarza ryzyko. [Pośrednik](https://curriculum.myfirstbitcoin.org/lexicon/en/#intermediary) może opóźnić płatność, pobrać opłatę, gromadzić dane osobowe i wykorzystywać je w niewłaściwy sposób, ograniczyć dostęp do konta, cofnąć przelew lub przestać działać. [Emitent](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer) danej [waluty](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency) może również zmieniać jej podaż.

Przez wiele lat informatycy próbowali stworzyć pieniądz cyfrowy, który nie potrzebowałby centralnego [emitenta](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer) ani firmy obsługującej płatności. Było to trudne wyzwanie. Informacje cyfrowe łatwo kopiować. Gdyby cyfrową monetę można było skopiować i wydać dwukrotnie, nie mogłaby ona pełnić funkcji pieniądza. Gdyby zaś jedna firma zapobiegała kopiowaniu, stawałaby się ośrodkiem kontroli i pojedynczym punktem awarii.

Bitcoin powstał, aby rozwiązać ten problem za pomocą [sieci równorzędnej](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network). Jego konstrukcja pozwala uczestnikom uzgodnić jedną [transakcyjną](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) historię bez centralnego [rejestru](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) prowadzonego przez jeden podmiot. Łączy publiczny [rejestr](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) ([łańcuch bloków](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain)), [podpisy cyfrowe](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature), sieć [węzłów weryfikujących](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node), [dowód pracy](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) oraz bodźce ekonomiczne.


<!-- micrographic: central-ledger-vs-bitcoin-01 -->
[W przypadku firmy płatniczej jedna organizacja prowadzi rejestr i zatwierdza każdy przelew. W sieci Bitcoin nadawca podpisuje transakcję, niezależne węzły ją weryfikują, a górnicy dodają ją do jednego wspólnego rejestru, dzięki czemu odbiorca jest mniej zależny od centralnego organu.](/micrographics/central-ledger-vs-bitcoin-01/pl.md)


![](https://cdn.sanity.io/images/vje9ehw2/staging/ff5854ad760ecdb1b1cdb024b46098be0212f47e-1536x1024.svg)



Bitcoin nie eliminuje zaufania z każdej dziedziny życia. Ogranicza potrzebę ufania centralnemu organowi w kwestii emisji i rozliczania swojego rodzimego pieniądza.

W tej książce **Bitcoin** pisany wielką literą B oznacza zazwyczaj sieć, protokół lub szerzej rozumiany system. Natomiast **bitcoin** pisany małą literą b oznacza jednostkę pieniężną lub [aktywo](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset). **BTC** to powszechnie stosowany skrót oznaczający ilość bitcoinów, zwłaszcza przy zapisywaniu [cen](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) lub konkretnych ilości. Portfel lub giełda to usługa, która może łączyć się z Bitcoinem; nie jest to sama [sieć Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network).
