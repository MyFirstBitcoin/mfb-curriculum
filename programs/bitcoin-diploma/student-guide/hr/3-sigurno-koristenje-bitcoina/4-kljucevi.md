# 3.4 Ključevi

Vlasništvo nad Bitcoinom osigurava se kriptografskim ključevima.


> **Definition – Privatni ključ**
>
> Jedan [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) tajni je podatak koji novčaniku omogućuje stvaranje valjanih [digitalnih potpisa](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Potpis odobrava trošenje bitcoina pod kontrolom odgovarajućeg ključa. Svatko tko dođe do [privatnog ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) obično može potrošiti ta sredstva.


Jedan [**javni ključ**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) matematički se izvodi iz [privatnog ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Pomaže pri provjeri potpisa bez otkrivanja [privatnog ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adrese se stvaraju iz [javnoključnih](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) podataka.

Temeljno je pravilo jednostavno:

**Javni podaci za primanje mogu se dijeliti. Privatni podaci za trošenje moraju ostati tajni.**

Jedan [digitalni potpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) dokazuje da je potrebni [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) odobrio [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Time se [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ne unosi u [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) provjeravaju potpis prije nego što prihvate trošenje.

Većina novčanika za početnike koristi [jedan potpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): jedan privatni ključ odobrava transakciju. Suvremeni novčanici automatski upravljaju brojnim ključevima. Početnici ne bi trebali kopirati ni obrađivati pojedinačne [privatne ključeve](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) u obliku nizova znakova. Zaštitite sigurnosnu kopiju koju novčanik podržava i slijedite njegov postupak oporavka.

Nijednom vjerodostojnom edukatoru, tvrtki koja razvija novčanik, zaposleniku mjenjačnice, djelatniku tehničke podrške ni programeru Bitcoina nije potreban vaš [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ili [početna fraza](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Svakoga tko to zatraži trebate smatrati prijetnjom.


> **Light**
>
> **Isprobajte:** Razvrstajte pripremljene primjere u tri skupine: podaci koje je sigurno dijeliti radi primanja, tajni podaci za trošenje i podaci koji mogu biti javni, ali bi ipak trebali ostati privatni kada su povezani s nekom osobom.



<!-- micrographic: private-key-public-info-01 -->
