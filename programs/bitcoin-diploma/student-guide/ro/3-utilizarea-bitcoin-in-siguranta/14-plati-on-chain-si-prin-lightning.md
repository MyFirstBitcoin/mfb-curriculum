# 3.14 Plăți on-chain și prin Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Plăți on-chain și prin Lightning**
>
> [Plățile on-chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) sunt înregistrate în [Blockchain-ul Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) și primesc [confirmări](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning este o rețea de plăți construită pe Bitcoin, care poate permite plăți rapide și frecvente. O plată prin Lightning se poate finaliza rapid sau poate eșua, iar Portofelul utilizat poate fi cu custodie sau cu autocustodie.



> **Dark – Traseul plății nu determină custodia**
>
> Plățile on-chain și cele prin Lightning implică diferite [compromisuri](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Un Portofel Lightning poate fi cu custodie sau cu autocustodie, iar o plată rapidă și reușită nu dovedește că un serviciu este potrivit pentru solduri mai mari sau pentru orice situație.



<!-- micrographic: onchain-lightning-table-01 -->


Ce traseu de plată așteaptă destinatarul să folosiți? Înainte de a plăti, verificați dacă acesta a furnizat o adresă on-chain sau o [factură Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) ori o cerere de plată. Un Portofel on-chain nu poate plăti direct orice [factură Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), iar un Portofel Lightning este posibil să nu permită orice operațiune on-chain. Unele aplicații permit ambele trasee de plată, dar pot adăuga comisioane sau dependențe de servicii. Configurarea detaliată a Lightning, canalele, rutarea și [lichiditatea](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) sunt subiecte de [Studiu avansat](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); exercițiile practice locale cu plăți reale își au locul în **Modulul 4**, atunci când se pot desfășura în siguranță și sunt adecvate.

Imaginați-vă că un scenariu pregătit oferă ambele trasee de plată. Ce cerere poate utiliza Portofelul ales și ce ați verifica înainte de a o aproba? Răspunsul depinde de cererea de primire a plății, de Portofel și de situație — nu de un traseu universal „cel mai bun”.

![Cadrul didactic indică pe o tablă două trasee geometrice diferite de plată, în timp ce cursanții începători și cei cu pregătire tehnică le analizează.](https://cdn.sanity.io/images/vje9ehw2/production/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
