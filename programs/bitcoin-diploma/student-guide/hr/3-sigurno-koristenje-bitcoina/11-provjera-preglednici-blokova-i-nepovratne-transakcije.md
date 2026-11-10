# 3.11 Provjera, preglednici blokova i nepovratne transakcije

> **Definition – Identifikator transakcije i preglednik blokova**
>
> Pojedini [identifikator transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identificira [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) u lancu blokova. Pojedini [preglednik blokova](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) prikazuje javne podatke o Bitcoinu, primjerice podatke o [transakciji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), njezinu statusu i broju [potvrda](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Pruža koristan pregled, ali nema ovlasti nad Bitcoinom niti dokazuje identitet ili poštenje primatelja.


Što ti javni podaci mogu pokazati, a što ne mogu? Mogu prikazati podatke o [transakciji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction): njezin status, odredište, iznos, naknadu i broj [potvrda](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation); ne mogu dokazati zašto je plaćanje izvršeno ni je li neka osoba pouzdana. Pojedina [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) u lancu blokova nepotvrđena je nakon što se [objavi na mreži](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast), a dobiva svoju [prvu potvrdu](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) kada se uključi u valjani blok. Kasniji blokovi povećavaju pouzdanost njezina mjesta u zapisu, ali ne ispravljaju pogrešno odredište ni prijevaru. Ne postoji univerzalan broj [potvrda](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) za svako plaćanje; odgovarajuća provjera ovisi o iznosu i riziku.

Kako biste pregledali pripremljenu [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), pribavite njezin [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), otvorite pouzdan preglednik za predviđenu [Bitcoin mrežu](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) i provjerite status, odredište, iznos, naknadu i [potvrde](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Preglednik je samo sučelje. Pretraživanje adrese ili identifikatora [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) može njegovu operateru otkriti da je vaš uređaj zainteresiran za te podatke. Za vježbu upotrijebite [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) koju je pripremio nastavnik ili ispisanu snimku zaslona. Nemojte pretraživati osobnu adresu polaznika ni njegovu [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) putem javne usluge. Ako kasnije budete istraživali osobno plaćanje, upoznajte se s aspektima [privatnosti](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) i sigurnosti te [kompromisima](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) koje vaša veza podrazumijeva prije nego što se koristite javnom uslugom.


> **Callout – Javni podaci nisu dokaz identiteta ni poštenja**
>
> Jedan [preglednik blokova](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) može prikazati javne [transakcijske](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) podatke, ali ne može dokazati tko kontrolira adresu, zašto je došlo do plaćanja ili je li primatelj pouzdan. Za vježbu upotrebljavajte pripremljene primjere i štitite [privatnost](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) pri pretraživanju javnih servisa.



<!-- micrographic: confirmation-timeline-01 -->


![Edukator i stariji polaznik raspravljaju o pripremljenom primjeru na monitoru okrenutom prema skupini, dok tehnički potkovan polaznik upravlja mišem; gledatelj vidi stražnju stranu kućišta.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
