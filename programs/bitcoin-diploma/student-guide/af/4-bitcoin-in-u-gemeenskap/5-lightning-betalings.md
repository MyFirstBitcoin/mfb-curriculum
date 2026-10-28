# 4.5 Lightning-betalings

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Die ontvanger skep 'n Lightning-betalingsversoek met die bedrag op hul foon, die sender skandeer dit en betaal, en die betaling kom 'n oomblik later op die ontvanger se foon aan.](/micrographics/lightning-phone-payment-01/af.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[’n Lightning-betaling in ses stappe: die ontvanger skep ’n versoek, die sender skandeer dit, kontroleer die ontvanger, bedrag, eenheid, vervaltyd en fooi, keur dit goed, die betaling word geroeteer, en albei beursies wys die resultaat. Elke beursie kan deur ’n bewaarder of deur die gebruiker self beheer word, en ’n mislukte of vervalde betaling begin weer met ’n nuwe versoek.](/micrographics/lightning-payment-sequence-01/af.md)


Lightning kan vinnige, klein Bitcoin-betalings prakties maak. Dit kan geskik wees vir 'n handelaar se toonbank, herhaalde plaaslike betalings, aanlyndienste of oorplasings waar 'n fooi vir 'n transaksie op die blokketting te hoog sou wees in verhouding tot die betaling.

'n Plaaslike Lightning-demonstrasie behoort die volgende duidelik te maak:

* of die Beursie deur 'n diensverskaffer of deur die gebruiker self beheer word
* hoe die Beursie befonds word
* of befondsing 'n blokketting-[Transaksie](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) of 'n diens vereis
* watter rugsteun of herstelmetode die saldo beskerm
* watter soort betalingsversoek gebruik word
* watter fooie of limiete van toepassing is
* wat gebeur wanneer 'n betaling misluk
* hoe die ontvanger betaling bevestig

'n [**Lightning-faktuur**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) is 'n betalingsversoek wat vir 'n spesifieke betaling geskep word. Dit kan 'n bedrag, bestemmingsinligting en 'n vervaltyd insluit. Lees die Beursie se [Bevestiging](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) op die skerm voordat u betaal.

'n [**Lightning-adres**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) is 'n mensleesbare identifiseerder wat deur sommige dienste ondersteun word. Dit lyk dalk soos 'n e-posadres, maar dit is 'n gerieflike manier om betalings te roeteer, nie 'n e-posrekening nie. Dit is afhanklik van die verskaffer of domein wat dit ondersteun.

Vir 'n betaling onder begeleiding:

1. Die ontvanger skep die korrekte versoek.
1. Die sender skandeer of kopieer dit.
1. Die sender kontroleer die ontvanger, bedrag, eenheid en fooi.
1. Die sender keur dit eers goed nadat die besonderhede korrek is.
1. Albei partye bevestig die resultaat in hul eie Beursies.
1. Die groep verduidelik die risiko's van [bewaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) en mislukking.

Moenie aanvaar dat 'n suksesvolle Lightning-betaling bewys dat die Beursie veilig is vir groter saldo's nie. Betalingsgerief en [bewaring](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) se sekuriteit is afsonderlike kwessies.
