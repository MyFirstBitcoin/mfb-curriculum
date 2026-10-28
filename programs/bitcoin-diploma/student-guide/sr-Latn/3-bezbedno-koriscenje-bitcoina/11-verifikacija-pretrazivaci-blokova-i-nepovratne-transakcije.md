# 3.11 Verifikacija, pretraživači blokova i nepovratne transakcije

<!-- card: definition -->
> **Definition – ID transakcije i pretraživač blokova**
>
> Jedan [ID transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identifikuje na blokčejnu [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Jedan [pretraživač blokova](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) prikazuje javne podatke sa Bitcoin mreže, kao što su za određenu [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) njen status i broj [potvrda](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). On pruža koristan pregled, ali nema autoritet nad Bitcoin mrežom i ne predstavlja dokaz identiteta ili poštenja primaoca.


Šta ove javne informacije mogu da pokažu, a šta ne mogu? Mogu da pokažu za određenu [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) njen status, odredište, iznos, naknadu i broj [potvrda](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation); ne mogu da dokažu zašto je došlo do plaćanja ili da li je neka osoba pouzdana. Na blokčejnu [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ostaje nepotvrđena nakon što se [emituje](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) i dobija svoju [prvu potvrdu](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) kada bude uključena u važeći blok. Naredni blokovi povećavaju pouzdanost njenog mesta u evidenciji, ali ne ispravljaju pogrešno odredište niti prevaru. Ne postoji univerzalni broj [potvrda](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) za sva plaćanja; odgovarajuća provera zavisi od iznosa i rizika.

Da biste pregledali pripremljenu [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), pribavite njen [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), otvorite pouzdan pretraživač za predviđenu [Bitcoin mrežu](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) i proverite status, odredište, iznos, naknadu i [potvrde](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Pretraživač je samo interfejs. Pretraga adrese ili identifikatora [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) može otkriti njegovom operateru da je vaš uređaj zainteresovan za te informacije. Za vežbu koristite unapred pripremljenu [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) koju je obezbedio predavač ili odštampani snimak ekrana. Nemojte pretraživati ličnu adresu ili [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) polaznika na javnom servisu. Ako kasnije budete istraživali lično plaćanje, saznajte koje [privatnosne](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) i bezbednosne [kompromise](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) podrazumeva vaša veza pre nego što počnete da koristite javni servis.


<!-- card: callout -->
> **Javni podaci nisu dokaz identiteta ili poštenja**
>
> Jedan [pretraživač blokova](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) može da prikaže javne [transakcione](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) podatke, ali ne može da dokaže ko kontroliše adresu, zašto je došlo do plaćanja ili da li je primalac pouzdan. Koristite pripremljene primere za vežbu i štitite [privatnost](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) kada pretražujete javne servise.



<!-- micrographic: confirmation-timeline-01 -->
[Transakcija čeka nepotvrđena u skupu transakcija na čekanju, zatim se uključuje u blok N i time dobija prvu potvrdu, a svaki naredni blok dodaje još jednu.](/micrographics/confirmation-timeline-01/sr-Latn.md)


![Edukator i stariji polaznik razgovaraju o pripremljenom primeru na monitoru okrenutom ka grupi, dok tehnički potkovani polaznik upravlja mišem; posmatrač vidi zadnju stranu kućišta monitora.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
