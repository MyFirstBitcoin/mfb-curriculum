# 1.8 Osittaisvarantopankkitoiminta

Kun talletatte käteistä pankkiin, pankki kirjaa [velan](https://curriculum.myfirstbitcoin.org/lexicon/en/#liability) teille: se on teille velkaa tilinne saldon verran. Pankki ei tavallisesti säilytä jokaisen talletuksen jokaista rahayksikköä fyysisenä käteisenä. Sen sijaan se pitää hallussaan [likvidejä reservejä](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity)—käteistä tai [varoja](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset), joita se voi käyttää nopeasti maksuihin—ja käyttää tasettaan lainojen myöntämiseen ja muihin sijoituksiin.

Kun liikepankki hyväksyy lainan, se luo yleensä uuden talletuksen lainanottajan tilille. Tämä kasvattaa pankkien [talletusrahan määrää](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-deposit). Kun lainapääoma maksetaan takaisin, tämän [talletusrahan](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-deposit) määrä vähenee. Pankkien toimintaa rajoittavat [vakavaraisuutta](https://curriculum.myfirstbitcoin.org/lexicon/en/#capital) koskevat säännöt, [maksuvalmiutta](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity) koskevat tarpeet, [luottoriski](https://curriculum.myfirstbitcoin.org/lexicon/en/#credit-risk), sääntely, rahoituskustannukset ja [luottokelpoisten lainanottajien kysyntä](https://curriculum.myfirstbitcoin.org/lexicon/en/#qualified-borrower).


<!-- micrographic: bank-loan-deposit-01 -->
[Pankkilaina yksinkertaistettuna: lainanottaja hakee lainaa, pankki hyväksyy lainan ja kirjaa lainanottajan tilille uuden talletuksen, ja lainanottaja maksaa myöhemmin pankille takaisin lainapääoman korkoineen.](/micrographics/bank-loan-deposit-01/fi.md)


Pankit tavoittelevat yleensä [voittoa](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-profit) ansaitsemalla korkoja ja palkkioita lainoista ja sijoituksista. Samalla ne maksavat toiminnasta, rahoituksesta ja sääntelystä aiheutuvat kustannuksensa ja kantavat tappiot, kun lainanottajat eivät maksa lainojaan takaisin. Nämä toiminnot ja rajoitteet vaihtelevat pankeittain ja lainkäyttöalueittain.


<!-- card: definition -->
> **Definition – Osittaisvarantojärjestelmä**
>
> [Osittaisvarantojärjestelmä](https://curriculum.myfirstbitcoin.org/lexicon/en/#fractional-reserve-banking) tarkoittaa pankkitoimintaa, jossa pankit pitävät vain osan talletusveloistaan välittömästi käytettävissä olevina reserveinä ja samalla myöntävät lainoja ja pitävät hallussaan muita [varoja](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset). Vaadittu reservien taso ja muut rajoitukset vaihtelevat maittain ja voivat muuttua ajan myötä.


Tästä syntyy kaksi merkittävää riskiä:

* **[Maksuvalmiusriski](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity-risk):** Pankilla voi olla pitkäaikaisia lainasaamisia, jotka odotetaan maksettavan takaisin, mutta sillä ei silti välttämättä ole riittävästi käteistä tai nopeasti käytettävissä olevia [varoja](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) monien samana päivänä tehtävien nostojen kattamiseen.
* **[Vakavaraisuusriski](https://curriculum.myfirstbitcoin.org/lexicon/en/#solvency-risk):** Luottotappiot tai laskevat [omaisuuden](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) [arvot](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) voivat johtaa siihen, että pankin kaikkien [varojen](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) arvo jää sen velkoja pienemmäksi. Tällöin pankki ei pysty täyttämään velvoitteitaan kokonaan, vaikka sillä olisi aikaa myydä [varoja](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset).


<!-- micrographic: liquidity-vs-solvency-01 -->
[Maksuvalmiusriski: monet tallettajat jonottavat nostaakseen rahansa tänään, eikä pankilla ole nyt riittävästi käteistä, vaikka sen myöntämät lainat saatetaan maksaa takaisin myöhemmin. Vakavaraisuusriski: lainanottajat jättävät asuntolainansa maksamatta, ja pankin varojen arvo laskee sen velkojen määrää pienemmäksi.](/micrographics/liquidity-vs-solvency-01/fi.md)


![](https://cdn.sanity.io/images/vje9ehw2/staging/f5f7999af936541b5928421cac58b3e5c7abd428-1536x1024.svg)



Pankin [**talletuspako**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-run) syntyy, kun monet tallettajat yrittävät nostaa rahansa tai tilivarojaan samanaikaisesti, koska he pelkäävät pankin kaatuvan. [Talletussuoja](https://curriculum.myfirstbitcoin.org/lexicon/en/#deposit-insurance) ja [keskuspankin](https://curriculum.myfirstbitcoin.org/lexicon/en/#central-bank) luotonanto voivat vähentää paniikkia, mutta talletussuojan piiriin kuulumisen ehdot ja korvausrajat vaihtelevat lainkäyttöalueittain. Nämä suojakeinot riippuvat instituutioista ja säännöistä, ja ne voivat siirtää osan tappioista tai riskeistä yksittäiseltä pankilta laajemmalle järjestelmälle.

Sääntely ja valvonta voivat vähentää riskejä, mutta ne eivät voi estää kaikkia petoksia, huonoa johtamista, poliittisia väärinkäytöksiä tai yksinkertaisia virheitä. Nämä ongelmat ovat arvioitavia mahdollisuuksia, eivät jokaisen pankkijärjestelmän väistämättömiä seurauksia.

Keskeinen opetus ei ole se, että jokainen pankki olisi kaatumaisillaan. Se on se, että pankkitilin saldo on pankin lupaus maksaa teille. Se ei ole sama asia kuin pitää selvityksessä käytettävää [omaisuuserää](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) suoraan hallussaan.
