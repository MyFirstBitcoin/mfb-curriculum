# 2.10 Dovada muncii

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Dovada Muncii**
>
> [Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) este procesul prin care [minerii](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) concurează pentru dreptul de a propune următorul bloc.


O [Funcție Hash](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) transformă datele într-un rezultat de lungime fixă. O mică modificare a datelor de intrare produce un rezultat nou, imprevizibil. Un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) modifică o mică parte din datele unui bloc propus și îi aplică în mod repetat funcția hash. Un rezultat este valid doar atunci când valoarea sa numerică este sub valoarea stabilită de rețea ca [țintă](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), un prag stabilit de reguli; o [țintă](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) mai mică înseamnă mai puține [rezultate valide](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) și mai multe încercări. Nu există nicio scurtătură, așa că [minerii](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pot fi nevoiți să facă multe încercări.

Când un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) găsește un [rezultat valid](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), acesta [difuzează](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blocul. [Nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) pot verifica rapid dovada, chiar dacă găsirea ei a necesitat un volum semnificativ de calcule și energie. Dacă blocul include o [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), acea [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) primește [prima Confirmare](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): înregistrarea sa a fost inclusă într-un bloc valid. Fiecare bloc valid adăugat ulterior adaugă încă o [Confirmare](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), sporind costul rescrierii poziției [Tranzacției](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) în [Blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain). Această diferență este importantă: munca este costisitor de efectuat și ușor de verificat.


<!-- micrographic: proof-of-work-process-01 -->
[Un miner calculează în mod repetat hashul unui bloc propus până când un rezultat este sub ținta rețelei, apoi difuzează blocul. Nodurile verifică rapid dovada și respectarea fiecărei reguli înainte ca blocul să fie inclus în blockchain: munca este costisitoare de realizat și ușor de verificat.](/micrographics/proof-of-work-process-01/ro.md)


[Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) îndeplinește mai multe scopuri:

* le oferă [minerilor](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) independenți o modalitate de a concura fără un coordonator central
* face ca ordinea [Tranzacțiilor](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) să fie costisitor de rescris
* leagă securitatea rețelei de echipamente și energie din lumea reală
* susține o metodă publică de a alege între istorice valide concurente: lanțul cu cea mai multă [muncă acumulată](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Mineritul](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) nu rezolvă ecuații utile unui scop extern. Scopul său este să asigure, în Bitcoin, ordonarea [tranzacțiilor](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Rețeaua ajustează periodic ținta: când blocurile sosesc prea repede, o reduce, iar când sosesc prea încet, o mărește, urmărind menținerea unei medii de aproximativ un bloc la fiecare zece minute, pe măsură ce puterea de calcul se schimbă.

[Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) implică un cost energetic real. Susținătorii afirmă că acest cost stă la baza securității Bitcoin și poate crea cerere pentru energie disponibilă în mod flexibil sau care altfel ar rămâne neutilizată. Criticii pun sub semnul întrebării cantitatea și sursa energiei utilizate. O evaluare responsabilă analizează ce energie este utilizată, de unde provine, ce securitate oferă și ce alternative sunt comparate.

![Cadrul didactic, cursantul începător și cursantul cu pregătire tehnică discută despre un dispozitiv de minerit de masă, cu ventilator și sursă de alimentare separată.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
