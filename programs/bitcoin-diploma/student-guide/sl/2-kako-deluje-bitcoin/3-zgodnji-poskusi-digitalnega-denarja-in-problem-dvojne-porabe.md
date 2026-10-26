# 2.3 Zgodnji poskusi digitalnega denarja in problem dvojne porabe

Bitcoin ni bil prvi poskus ustvarjanja digitalnega denarja. Temeljil je na štirih desetletjih preizkušanja in črpal iz zamisli številnih prejšnjih projektov, ki so pomagali oblikovati njegovo uspešno zasnovo.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) je uporabljal [kriptografijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) za omogočanje zasebnih digitalnih plačil. Odvisen je bil od osrednjega podjetja in povezav z bankami. Ko je podjetje propadlo, sistem ni mogel nadaljevati delovanja kot neodvisno denarno omrežje.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) je uporabljal [dokaz o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) za povečanje stroškov pošiljanja neželene e-pošte. Pošiljateljev računalnik je moral pred pošiljanjem sporočila opraviti računsko delo. Ta zamisel je pokazala, kako lahko računski stroški odvračajo od zlorab.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) je opisoval predlagani sistem, v katerem bi lahko računsko delo ustvarjalo redke digitalne zapise. Ni zaživel kot celovit decentraliziran denarni sistem, vendar je razvil pomembne zamisli o digitalni [redkosti](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) in dokazovanju.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) in [**dokaz o delu za večkratno uporabo (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) sta raziskovala načine, kako bi udeleženci lahko ustvarjali ali prenašali redko digitalno [vrednost](https://curriculum.myfirstbitcoin.org/lexicon/en/#value), ne da bi se zanašali le na eno osrednjo podatkovno zbirko. Bila sta nedokončana, vendar sta pomagala razjasniti, kaj bi delujoč sistem potreboval.
* Čeprav [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) ni bil denar, je pokazal, da bi [omrežje enakovrednih udeležencev](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) številnim neodvisnim računalnikom lahko omogočilo izmenjavo informacij, ne da bi en osrednji strežnik nadzoroval celoten sistem.

Ti poskusi so skupaj razkrili uporabne koščke sestavljanke. Razjasnili so tudi težavo, ki je še ostala.


> **Definition – Dvojna poraba**
>
> [Dvojna poraba](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) je poskus pošiljanja iste digitalne enote dvema prejemnikoma. Digitalne podatke je mogoče popolnoma kopirati, zato digitalni denarni sistem potrebuje način za ugotavljanje, katera [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) je veljavna.


[Centralizirani sistemi](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) to preprečujejo tako, da eni zaupanja vredni podatkovni zbirki prepustijo odločitev o tem, katero plačilo je prispelo prvo. 31. oktobra 2008 je [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) v beli knjigi [_Bitcoin: sistem elektronske gotovine med enakovrednimi udeleženci_](https://bitcoin.org/bitcoin.pdf) pojasnil drugačen pristop: javni sistem, ki bi lahko vzpostavil skupno zgodovino plačil brez banke, podjetja ali drugega osrednjega organa.

Bela knjiga je združila značilnosti, potrebne za ta pristop:

1. **Eno [omrežje enakovrednih udeležencev](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) se sporočajo neposredno omrežju udeležencev.
1. **[Digitalni podpisi](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** en [zasebni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) je tajni podatek, s katerim se ustvari podpis za odobritev porabe; to lahko stori le njegov imetnik.
1. **Bloki in [rudarjenje](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [rudarji](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) združujejo [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) v bloke in uporabljajo [dokaz o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) pri tekmovanju za dodajanje naslednjega bloka.
1. **Neodvisno [preverjanje](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [vozlišča](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) preverjajo [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) in bloke glede na pravila Bitcoina.
1. **Skupna zgodovina z nakopičenim [dokazom o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** udeleženci prepoznajo [veljavno verigo](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) iz [transakcij](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) z največ [nakopičenega dela](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) kot skupni zapis.


<!-- micrographic: five-part-response-01 -->


Ta modul podrobneje pojasnjuje te koncepte. Skupaj so ponudili praktično rešitev za [problem dvojne porabe](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): omrežje lahko zavrne drugi poskus porabe istega bitcoina, ne da bi se zanašalo na osrednjo avtoriteto. Bitcoin je ponudil manjkajočo kombinacijo, ki so jo desetletja iskali s poskusi ustvarjanja digitalnega denarja.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
