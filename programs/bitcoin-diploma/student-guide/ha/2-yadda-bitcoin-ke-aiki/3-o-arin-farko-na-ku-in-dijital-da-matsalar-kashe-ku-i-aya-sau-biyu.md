# 2.3 Ƙoƙarin farko na kuɗin dijital da matsalar kashe kuɗi ɗaya sau biyu

Bitcoin ba shi ne yunƙuri na farko na samar da kuɗin dijital ba. An gina shi bisa gwaje-gwajen shekaru arba'in, ana ɗauko ra'ayoyi daga ayyuka da dama da suka gabace shi waɗanda suka taimaka wajen tsara shi cikin nasara.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) ya yi amfani da [ilimin ɓoye bayanai](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) don tallafa wa biyan kuɗin dijital cikin sirri. Ya dogara da kamfani guda ɗaya a tsakiya da kuma alaƙa da bankuna. Da kamfanin ya durƙushe, tsarin bai iya ci gaba a matsayin cibiyar sadarwar kuɗi mai zaman kanta ba.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) ya yi amfani da [hujjar aiki](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) don sa aika imel marar buƙata ya zama mai tsada. Dole kwamfutar mai aikawa ta yi wani aiki kafin aika saƙo. Wannan ra'ayi ya nuna yadda tsadar aikin kwamfuta za ta iya hana amfani da tsarin ta hanyar da ba ta dace ba.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) ya bayyana wani tsarin da aka gabatar wanda aikin kwamfuta zai iya samar da bayanan dijital masu ƙaranci a cikinsa. Ba a ƙaddamar da shi a matsayin cikakken tsarin kuɗi marar cibiyar iko guda ɗaya ba, amma ya bunƙasa muhimman ra'ayoyi game da yadda abubuwan dijital ke kasancewa [masu ƙaranci](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) da kuma hujja.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) da [**hujjar aiki mai yiwuwa a sake amfani da ita (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) sun binciki hanyoyin da mahalarta za su iya ƙirƙira ko tura wani abu na dijital mai ƙaranci da ke da [ƙima](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) ba tare da dogaro kawai da rumbun bayanai guda ɗaya a tsakiya ba. Ba su kammala ba, amma sun taimaka wajen fayyace abin da tsarin da zai yi aiki zai buƙata.
* Ko da yake [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) ba kuɗi ba ne, ya nuna cewa [cibiyar sadarwar tsara-da-tsara](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) za ta iya ba kwamfutoci masu zaman kansu da yawa damar raba bayanai ba tare da uwar garke guda ɗaya a tsakiya tana sarrafa dukan tsarin ba.

A haɗe, waɗannan gwaje-gwaje sun nuna sassa masu amfani na mafitar da ake nema. Sun kuma fayyace matsalar da ta rage.


> **Definition – Kashe kuɗi sau biyu**
>
> [Kashe kuɗi sau biyu](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) yunƙuri ne na aika raka'ar dijital guda ɗaya ga masu karɓa biyu. Ana iya yin kwafin bayanan dijital daidai da na asali, don haka tsarin kuɗin dijital yana buƙatar hanyar tantance wace [mu'amala](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ce ingantacciya.


[Tsarukan da ke da cibiyar iko guda ɗaya](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) suna hana hakan ta hanyar barin rumbun bayanai guda ɗaya amintacce ya yanke shawarar wane biyan kuɗi ne ya zo da farko. A ranar 31 Oktoba 2008, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) a cikin farar takardarsa, [_Bitcoin: Tsarin Kuɗin Lantarki na Tsara-da-Tsara_](https://bitcoin.org/bitcoin.pdf), ya bayyana wata hanya dabam: tsarin da kowa zai iya shiga wanda zai iya tabbatar da tarihin biyan kuɗi na bai ɗaya ba tare da banki, kamfani, ko wata hukuma ta tsakiya ba.

Farar takardar ta haɗa fasalolin da ake buƙata don wannan hanya:

1. **Wata [cibiyar sadarwar tsara-da-tsara](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [mu'amaloli](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ana sanar da su kai tsaye ga cibiyar sadarwar mahalarta.
1. **[Sa hannun dijital](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** wani [mabuɗin sirri](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) bayani ne na sirri da ke ƙirƙirar sa hannu don ba da izinin kashe kuɗi; mai riƙe da shi kaɗai ne zai iya yin hakan.
1. **Tubalai da [haƙar ma'adinai](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [masu haƙar ma'adinai](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) suna tattara [ma'amaloli](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) a cikin tubalai kuma suna amfani da [shaidar aiki](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) don yin gasa wajen ƙara tubali na gaba.
1. **Tabbatarwa mai [zaman kanta](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [mahaɗai](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) suna bincika [ma'amaloli](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) da tubalai bisa ƙa'idojin Bitcoin.
1. **Tarihin bai ɗaya mai tarin [shaidar aiki](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** mahalarta suna amincewa da [ingantacciyar sarƙa](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) ta [ma'amaloli](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mai mafi yawan [aikin da aka tara](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) a matsayin kundin bayanan bai ɗaya.


<!-- micrographic: five-part-response-01 -->


Wannan sashe yana bayyana waɗannan ra'ayoyi dalla-dalla. A tare, sun samar da mafita mai amfani ga [matsalar kashe kuɗi ɗaya sau biyu](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): hanyar sadarwar za ta iya ƙin amincewa da yunƙurin kashe bitcoin ɗaya a karo na biyu ba tare da dogaro da wata hukuma ta tsakiya ba. Bitcoin ya samar da haɗin abubuwan da aka rasa, wanda gwaje-gwajen kuɗin dijital suka shafe shekaru da dama suna nema.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
