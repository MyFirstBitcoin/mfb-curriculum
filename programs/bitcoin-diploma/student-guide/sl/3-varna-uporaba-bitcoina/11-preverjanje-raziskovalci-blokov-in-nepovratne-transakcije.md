# 3.11 Preverjanje, raziskovalci blokov in nepovratne transakcije

> **Definition – Identifikator transakcije in raziskovalec blokov**
>
> Vsak [identifikator transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) označuje v verigi blokov zapisano [transakcijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Raziskovalec blokov](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) prikazuje javne podatke omrežja Bitcoin, na primer podatke o [transakciji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), njenem stanju in številu [potrditev](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Omogoča koristen vpogled, vendar nima avtoritete nad omrežjem Bitcoin in ni dokaz o prejemnikovi identiteti ali poštenosti.


Kaj lahko ti javni podatki pokažejo in česa ne morejo? Pri posamezni [transakciji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) lahko pokažejo stanje, cilj, znesek, provizijo in število [potrditev](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation); ne morejo pa dokazati, zakaj je bilo plačilo izvedeno ali ali je oseba vredna zaupanja. V verigi blokov zapisana [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) je nepotrjena, potem ko je [oddana v omrežje](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast), in prejme [prvo potrditev](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation), ko je vključena v veljaven blok. Poznejši bloki povečujejo zaupanje v njeno mesto v evidenci, vendar ne odpravijo napačnega cilja ali prevare. Ni univerzalnega števila [potrditev](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) za vsa plačila; ustrezno preverjanje je odvisno od zneska in tveganja.

Če želite pregledati pripravljeno [transakcijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), pridobite njen [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), odprite zaupanja vreden raziskovalec za predvideno [omrežje Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) ter preverite stanje, cilj, znesek, provizijo in [potrditve](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Raziskovalec je le vmesnik. Iskanje naslova ali identifikatorja [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) lahko njegovemu upravljavcu razkrije, da se vaša naprava zanima za te podatke. Za vajo uporabite [transakcijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), ki jo je pripravil izobraževalec, ali natisnjen posnetek zaslona. V javni storitvi ne iščite osebnega naslova ali [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) udeleženca izobraževanja. Če pozneje raziskujete osebno plačilo, se seznanite s [kompromisi glede zasebnosti](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) in varnosti [pri uporabi](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) svoje povezave, preden uporabite javno storitev.


> **Callout – Javni podatki niso dokaz identitete ali poštenosti**
>
> Tak [raziskovalec blokov](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) lahko prikaže javne [transakcijske](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) podatke, vendar ne more dokazati, kdo nadzoruje naslov, zakaj je bilo plačilo izvedeno ali ali je prejemnik vreden zaupanja. Za vajo uporabite pripravljene primere in varujte [zasebnost](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) pri iskanju po javnih storitvah.



<!-- micrographic: confirmation-timeline-01 -->


![Izobraževalec in starejši udeleženec razpravljata o pripravljenem primeru na zaslonu, obrnjenem proti skupini, medtem ko tehnično vešči udeleženec upravlja miško; gledalec vidi zadnjo stran ohišja.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
