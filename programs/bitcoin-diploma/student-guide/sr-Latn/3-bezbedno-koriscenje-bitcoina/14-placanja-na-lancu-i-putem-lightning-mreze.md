# 3.14 Plaćanja na lancu i putem Lightning mreže

![](https://cdn.sanity.io/images/vje9ehw2/production/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Plaćanja na lancu i putem Lightning mreže**
>
> [Plaćanja na lancu](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) beleže se u Bitcoinovom [blokčejnu](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) i dobijaju [potvrde](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning je mreža za plaćanje izgrađena na Bitcoinu koja može da podrži brza i česta plaćanja. Plaćanje putem Lightning mreže može se brzo završiti ili biti neuspešno, a novčanik koji se koristi i dalje može biti uz staranje pružaoca usluge ili uz samostalno staranje korisnika.



> **Dark – Putanja plaćanja ne određuje ko čuva sredstva**
>
> Plaćanja na lancu i putem Lightning mreže podrazumevaju različite [kompromise](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Lightning novčanik može biti uz staranje pružaoca usluge ili uz samostalno staranje korisnika, a brzo i uspešno plaćanje ne dokazuje da je usluga prikladna za veće iznose sredstava ili za svaku situaciju.



<!-- micrographic: onchain-lightning-table-01 -->


Koju putanju primalac očekuje? Pre plaćanja proverite da li je dostavio adresu na lancu ili [Lightning fakturu](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) ili zahtev za plaćanje. Novčanik za plaćanja na lancu ne može direktno da plati svaku [Lightning fakturu](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), a Lightning novčanik možda ne podržava svaku radnju na lancu. Neke aplikacije podržavaju obe putanje, ali mogu dodati naknade ili zavisnost od drugih usluga. Detaljno podešavanje Lightning mreže, kanali, rutiranje i [likvidnost](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) spadaju u [Napredno učenje](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); praktično vežbanje uživo u lokalnom okruženju spada u **Modul 4** kada je bezbedno i primereno.

Zamislite da pripremljeni scenario nudi obe putanje plaćanja. Koji zahtev predviđeni novčanik može da koristi i šta biste proverili pre nego što odobrite plaćanje? Odgovor zavisi od zahteva za prijem uplate, novčanika i situacije — a ne od neke univerzalno „najbolje“ putanje.

![Predavač pokazuje dve različite geometrijske putanje plaćanja na tabli, dok ih polaznici početnici i polaznici sa tehničkim predznanjem razmatraju.](https://cdn.sanity.io/images/vje9ehw2/production/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
