# 4.5 Lightningové platby

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning umožňuje prakticky využívat rychlé a drobné platby v síti Bitcoin. Může se hodit pro platby u pokladny, opakované místní platby, online služby nebo převody, u nichž by byl poplatek za on-chain transakci vzhledem k výši platby příliš vysoký.

Místní ukázka používání Lightningu by měla objasnit:

* zda je peněženka ve správě třetí strany, nebo pod vlastní správou uživatele
* jak se do peněženky doplňují prostředky
* zda doplnění prostředků vyžaduje on-chain [transakci](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) nebo využití služby
* jaká záloha nebo možnost obnovy chrání zůstatek
* jaký typ platebního požadavku se používá
* jaké poplatky nebo limity se uplatňují
* co se stane, když platba selže
* jak příjemce potvrzuje platbu

Takzvaná [**lightningová faktura**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) je platební požadavek vytvořený pro konkrétní platbu. Může obsahovat částku, údaje o cíli platby a dobu platnosti. Před zaplacením si v peněžence přečtěte [potvrzovací](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) obrazovku.

Takzvaná [**lightningová adresa**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) je pro člověka čitelný identifikátor, který podporují některé služby. Může vypadat jako e-mailová adresa, ale slouží k usnadnění směrování plateb, nikoli jako e-mailový účet. Závisí na poskytovateli nebo doméně, která ji podporuje.

Při platbě pod vedením postupujte takto:

1. Příjemce vytvoří správný požadavek.
1. Odesílatel jej naskenuje nebo zkopíruje.
1. Odesílatel zkontroluje příjemce, částku, jednotku a poplatek.
1. Odesílatel platbu schválí až poté, co se ujistí, že jsou údaje správné.
1. Obě strany potvrdí výsledek ve svých peněženkách.
1. Skupina vysvětlí rizika spojená s [úschovou prostředků](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) a se selháním platby.

Nepředpokládejte, že úspěšná platba přes Lightning dokazuje, že je peněženka bezpečná i pro vyšší zůstatky. Pohodlí při placení a [úschova prostředků](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) z hlediska bezpečnosti představují dvě samostatné otázky.
