# 2.10 Dokaz o delu

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Dokaz o delu**
>
> [Dokaz o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) je postopek, s katerim [rudarji](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) tekmujejo za pravico do predlaganja naslednjega bloka.


Z [zgoščevalno funkcijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) se podatki pretvorijo v rezultat nespremenljive dolžine. Majhna sprememba vhodnih podatkov ustvari nepredvidljiv nov rezultat. [Rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) spremeni majhen del podatkov v predlaganem bloku in ga večkrat zgoščuje. Rezultat je veljaven le, če je njegova številska vrednost pod omrežno [ciljno vrednostjo](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), pragom, določenim s pravili; nižja [ciljna vrednost](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) pomeni manj [veljavnih rezultatov](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) in več poskusov. Bližnjice ni, zato [rudarji](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) morda potrebujejo veliko poskusov.

Ko [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) najde [veljaven rezultat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), [razpošlje](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok. [Vozlišča](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) lahko dokaz hitro preverijo, čeprav je njegovo iskanje zahtevalo veliko računanja in energije. Če blok vsebuje [transakcijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), ta [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) prejme svojo [prvo potrditev](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): njen zapis je bil vključen v en veljaven blok. Vsak veljaven blok, dodan za njim, doda še eno [potrditev](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), zaradi česar je mesto [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) v [verigi blokov](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) dražje prepisati. Ta razlika je pomembna: opravljanje dela je drago, njegovo preverjanje pa preprosto.


<!-- micrographic: proof-of-work-process-01 -->
[Rudar znova in znova izračunava zgoščeno vrednost predlaganega bloka, dokler en rezultat ni nižji od ciljne vrednosti omrežja, nato blok razpošlje. Vozlišča hitro preverijo dokaz in upoštevanje vsakega pravila, preden se blok pridruži verigi blokov: opravljanje dela je drago, njegovo preverjanje pa preprosto.](/micrographics/proof-of-work-process-01/sl.md)


[Dokaz o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ima več namenov:

* neodvisnim [rudarjem](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) omogoča tekmovanje brez osrednjega razporejevalnika
* podraži spreminjanje vrstnega reda [transakcij](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) s prepisovanjem
* povezuje varnost omrežja s fizično opremo in energijo
* podpira javno metodo za izbiro med konkurenčnimi veljavnimi zgodovinami: verigo z največ [nakopičenega dela](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Rudarjenje](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ne rešuje uporabnih enačb za kak zunanji namen. Njegov namen je zavarovati vrstni red Bitcoinovih [transakcij](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Omrežje občasno prilagodi ciljno vrednost: kadar bloki prihajajo prehitro, jo zniža, kadar prihajajo prepočasi, pa jo zviša. Tako ob spreminjanju računske moči stremi k povprečju približno enega bloka vsakih deset minut.

[Dokaz o delu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) vključuje dejanske stroške energije. Zagovorniki trdijo, da so ti stroški temelj varnosti Bitcoina in lahko ustvarijo povpraševanje po energiji, katere porabo je mogoče prilagajati, ali po energiji, ki bi sicer ostala neizkoriščena. Kritiki dvomijo o upravičenosti količine in izvora porabljene energije. Odgovorna presoja obravnava vprašanja, katera energija se uporablja, od kod prihaja, kakšno varnost zagotavlja in katere alternative se primerjajo.

![Izobraževalec, udeleženec začetnik in tehnično podkovani udeleženec razpravljajo o namizni rudarski napravi z ventilatorjem in ločenim napajalnikom.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
