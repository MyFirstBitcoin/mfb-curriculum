# 3.14 Plaćanja na lancu i putem mreže Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Plaćanja na lancu i putem Lightninga**
>
> [Plaćanja na lancu](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) bilježe se u Bitcoinovu [lancu blokova](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) i dobivaju [potvrde](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning je platna mreža izgrađena na Bitcoinu koja može podržavati brza i česta plaćanja. Plaćanje putem Lightninga može se brzo izvršiti ili ne uspjeti, a novčanik koji se za njega koristi može biti skrbnički ili samoskrbnički.



> **Dark – Način plaćanja ne određuje skrbništvo**
>
> Plaćanja na lancu i putem Lightninga podrazumijevaju različite [kompromise](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Lightning novčanik može biti skrbnički ili samoskrbnički, a brzo i uspješno plaćanje ne dokazuje da je usluga prikladna za veće iznose ili svaku situaciju.



<!-- micrographic: onchain-lightning-table-01 -->


Koji način plaćanja primatelj očekuje? Prije plaćanja provjerite je li dostavio adresu za plaćanje na lancu ili [Lightning račun](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) ili zahtjev za plaćanje. Novčanik za plaćanja na lancu ne može izravno platiti svaki [Lightning račun](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), a Lightning novčanik možda ne podržava svaku radnju na lancu. Neke aplikacije podržavaju oba načina plaćanja, ali mogu dodati naknade ili ovisnost o drugim uslugama. Detaljno postavljanje Lightninga, kanali, usmjeravanje i [likvidnost](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) obuhvaćeni su temom [Napredno učenje](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); praktične vježbe uživo u lokalnom okruženju pripadaju **Modulu 4** kada je to sigurno i primjereno.

Zamislite da pripremljeni scenarij nudi oba načina plaćanja. Koji zahtjev može upotrijebiti predviđeni novčanik i što biste provjerili prije nego što ga odobrite? Odgovor ovisi o zahtjevu za primanje uplate, novčaniku i situaciji — a ne o univerzalno „najboljem” načinu plaćanja.

![Predavač na ploči pokazuje dvije različite geometrijske putanje plaćanja dok ih polaznik početnik i tehnički potkovani polaznici razmatraju.](https://cdn.sanity.io/images/vje9ehw2/production/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
