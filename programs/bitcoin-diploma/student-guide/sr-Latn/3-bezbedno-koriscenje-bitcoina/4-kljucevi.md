# 3.4 Ključevi

Vlasništvo nad Bitcoinom obezbeđuje se kriptografskim ključevima.


<!-- card: definition -->
> **Definition – Privatni ključ**
>
> Jedan [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) je tajni podatak koji novčaniku omogućava da kreira važeće [digitalne potpise](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Potpis odobrava trošenje bitcoina koji su pod kontrolom odgovarajućeg ključa. Svako ko dođe do [privatnog ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) obično može da potroši ta sredstva.


Jedan [**javni ključ**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) izvodi se matematičkim putem iz [privatnog ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). On omogućava proveru potpisa bez otkrivanja [privatnog ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adrese se kreiraju na osnovu [javno-ključnih](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) podataka.

Osnovno pravilo je jednostavno:

**Javni podaci za primanje sredstava mogu se deliti. Privatni podaci za trošenje sredstava moraju ostati tajni.**

Jedan [digitalni potpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) dokazuje da je potreban [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) odobrio [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). On ne smešta [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) unutar [transakcije](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) proveravaju potpis pre nego što prihvate trošenje sredstava.

Većina novčanika za početnike koristi [jedan potpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): jedan privatni ključ odobrava transakciju. Savremeni novčanici automatski upravljaju mnogim ključevima. Početnici ne treba da kopiraju niti da rukuju pojedinačnim [privatnim ključevima](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) u obliku nizova znakova. Zaštitite rezervnu kopiju koju novčanik podržava i pratite njegov postupak oporavka.

Nijednom legitimnom edukatoru, kompaniji koja razvija novčanik, zaposlenom u menjačnici, radniku tehničke podrške ili Bitcoin programeru nije potreban vaš [privatni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ili [početna fraza](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Svakoga ko ih traži treba smatrati pretnjom.


<!-- card: light -->
> **Isprobajte:** Razvrstajte pripremljene primere u tri grupe: podaci koji se mogu bezbedno deliti radi primanja sredstava, tajni podaci za trošenje sredstava i podaci koji mogu biti javni, ali ih ipak treba čuvati kao privatne kada su povezani sa određenom osobom.



<!-- micrographic: private-key-public-info-01 -->
[Iz tajnog privatnog ključa, koji se nikada ne sme deliti, izvode se javni podaci koji se mogu deliti: javni ključ izveden iz njega i adresa za primanje kreirana na osnovu tog javnog ključa. Isti privatni ključ kreira potpise koje čvorovi proveravaju, a da pritom nikada ne saznaju privatni ključ.](/micrographics/private-key-public-info-01/sr-Latn.md)
