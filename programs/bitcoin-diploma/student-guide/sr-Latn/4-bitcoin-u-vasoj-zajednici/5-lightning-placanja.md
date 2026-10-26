# 4.5 Lightning plaćanja

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning može učiniti brza, mala Bitcoin plaćanja praktičnim. Može biti pogodan za plaćanje na kasi, ponovljena lokalna plaćanja, onlajn usluge ili prenose kod kojih bi naknada za transakciju na lancu bila prevelika u odnosu na iznos plaćanja.

Lokalna demonstracija Lightning plaćanja treba da razjasni:

* da li je novčanik starateljski ili samostalni
* kako se sredstva uplaćuju u novčanik
* da li uplata sredstava zahteva blokčejn [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ili neku uslugu
* koja rezervna kopija ili postupak oporavka štiti sredstva
* koja vrsta zahteva za plaćanje se koristi
* koje naknade ili ograničenja važe
* šta se dešava kada plaćanje ne uspe
* kako primalac potvrđuje plaćanje

Jedna [**Lightning faktura**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) je zahtev za plaćanje kreiran za određeno plaćanje. Može sadržati iznos, podatke o odredištu i vreme isteka. Pročitajte na novčaniku [potvrdni](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) ekran pre plaćanja.

Jedna [**Lightning adresa**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) je ljudima čitljiv identifikator koji podržavaju neke usluge. Može izgledati kao adresa e-pošte, ali služi za jednostavnije usmeravanje plaćanja, a ne kao nalog e-pošte. Zavisi od pružaoca usluge ili domena koji je podržava.

Za plaćanje uz vođenje:

1. Primalac kreira odgovarajući zahtev.
1. Pošiljalac ga skenira ili kopira.
1. Pošiljalac proverava primaoca, iznos, jedinicu i naknadu.
1. Pošiljalac odobrava plaćanje tek kada su podaci tačni.
1. Obe strane potvrđuju ishod u svojim novčanicima.
1. Grupa objašnjava rizike povezane sa [čuvanjem sredstava](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) i neuspehom plaćanja.

Nemojte pretpostavljati da uspešno Lightning plaćanje dokazuje da je novčanik bezbedan za čuvanje većih iznosa. Praktičnost plaćanja i [čuvanje sredstava](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) na bezbedan način odvojena su pitanja.
