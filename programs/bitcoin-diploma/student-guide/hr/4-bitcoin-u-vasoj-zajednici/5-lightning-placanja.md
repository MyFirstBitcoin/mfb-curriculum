# 4.5 Lightning plaćanja

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning može učiniti brza i mala plaćanja Bitcoinom praktičnima. Može biti prikladan za plaćanja na prodajnom mjestu, ponovljena lokalna plaćanja, internetske usluge ili prijenose kod kojih bi naknada za transakciju na lancu bila previsoka u odnosu na iznos plaćanja.

Lokalna demonstracija Lightninga trebala bi razjasniti:

* je li novčanik skrbnički ili samoskrbnički
* kako se novčanik puni sredstvima
* zahtijeva li punjenje sredstvima na lancu provedenu [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ili uslugu
* koja sigurnosna kopija ili mogućnost oporavka štiti sredstva
* koja se vrsta zahtjeva za plaćanje upotrebljava
* koje se naknade ili ograničenja primjenjuju
* što se događa kada plaćanje ne uspije
* kako primatelj potvrđuje plaćanje

Jedan [**Lightning račun**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) je zahtjev za plaćanje izrađen za određeno plaćanje. Može sadržavati iznos, podatke o odredištu i vrijeme isteka. Pregledajte u novčaniku [potvrdni](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) zaslon prije plaćanja.

Jedna [**Lightning adresa**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) je ljudima čitljiv identifikator koji podržavaju neke usluge. Može izgledati kao adresa e-pošte, ali služi za jednostavnije usmjeravanje plaćanja, a nije račun e-pošte. Ovisi o pružatelju usluge ili domeni koja je podržava.

Za plaćanje uz vodstvo:

1. Primatelj izrađuje ispravan zahtjev.
1. Pošiljatelj ga skenira ili kopira.
1. Pošiljatelj provjerava primatelja, iznos, jedinicu i naknadu.
1. Pošiljatelj odobrava plaćanje tek nakon što provjeri da su podaci točni.
1. Obje strane potvrđuju rezultat u svojim novčanicima.
1. Skupina objašnjava rizike [skrbništva](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) i neuspjeha plaćanja.

Nemojte pretpostavljati da uspješno plaćanje putem Lightninga dokazuje da je novčanik siguran za držanje većih iznosa. Praktičnost plaćanja i [skrbnička](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) sigurnost zasebna su pitanja.
