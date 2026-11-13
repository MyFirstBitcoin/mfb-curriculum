# 2.3 Mga Unang Pagtatangka sa Digital na Pera at ang Problema ng Dobleng Paggastos

Hindi ang Bitcoin ang unang pagtatangka sa paglikha ng digital na pera. Nabuo ito mula sa apat na dekada ng pag-eeksperimento, gamit ang mga ideya mula sa maraming naunang proyekto na nakatulong sa paghubog ng matagumpay nitong disenyo.

* [**Ang DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) ay gumamit ng [kriptograpiya](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) upang suportahan ang mga pribadong digital na pagbabayad. Nakasalalay ito sa isang sentral na kompanya at sa mga ugnayan nito sa mga bangko. Nang bumagsak ang kompanya, hindi na nakapagpatuloy ang sistema bilang isang malayang network ng pera.
* [**Ang Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) ay gumamit ng [patunay ng trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) upang gawing magastos ang pagpapadala ng mga hindi gustong email. Kailangang magsagawa ng trabaho ang computer ng nagpapadala bago magpadala ng mensahe. Ipinakita ng ideyang ito kung paano makatutulong ang gastos sa pagkukuwenta upang pigilan ang pang-aabuso.
* [**Ang Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) ay naglarawan ng isang iminungkahing sistema kung saan maaaring lumikha ang gawaing pagkukuwenta ng mga digital na rekord na limitado ang dami. Hindi ito inilunsad bilang isang kumpletong desentralisadong sistema ng pera, ngunit nakabuo ito ng mahahalagang ideya tungkol sa digital na [kakapusan](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) at patunay.
* [**Ang B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) at [**muling magagamit na patunay ng trabaho (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) ay nagsiyasat ng mga paraan upang makalikha o makapaglipat ang mga kalahok ng limitadong digital na [halaga](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) nang hindi umaasa lamang sa iisang sentral na database. Hindi kumpleto ang mga ito, ngunit nakatulong ang mga ito upang linawin kung ano ang kakailanganin ng isang gumaganang sistema.
* Bagaman ang [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) ay hindi pera, ipinakita nito na ang isang [peer-to-peer na network](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) ay maaaring magbigay-daan sa maraming magkakahiwalay na computer na magbahagi ng impormasyon nang walang iisang sentral na server na kumokontrol sa buong sistema.

Sama-sama, ipinakita ng mga eksperimentong ito ang mahahalagang bahagi ng palaisipan. Nilinaw rin ng mga ito ang natitirang problema.


<!-- card: definition -->
> **Definition – Dobleng paggastos**
>
> [Ang dobleng paggastos](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) ay isang pagtatangkang ipadala ang iisang digital na yunit sa dalawang tatanggap. Maaaring kopyahin nang eksakto ang digital na datos, kaya kailangan ng isang sistema ng digital na pera ng paraan upang matukoy kung aling [transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ang may bisa.


[Ang mga sentralisadong sistema](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) ay pumipigil dito sa pamamagitan ng pagpapaubaya sa iisang pinagkakatiwalaang database na magpasya kung aling pagbabayad ang nauna. Noong 31 Oktubre 2008, ang kay [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) na whitepaper, [_Bitcoin: Isang Peer-to-Peer na Sistema ng Elektronikong Pera_](https://bitcoin.org/bitcoin.pdf), ay nagpaliwanag ng ibang pamamaraan: isang pampublikong sistema na makapagtatatag ng magkakatugmang kasaysayan ng mga pagbabayad nang walang bangko, kompanya, o iba pang sentral na awtoridad.

Pinagsama-sama ng whitepaper ang mga katangiang kailangan para sa pamamaraang iyon:

1. **Isang [peer-to-peer na network](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [ang mga transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ay direktang ipinababatid sa isang network ng mga kalahok.
1. **[Mga digital na lagda](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** ang isang [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ay lihim na impormasyong lumilikha ng lagda upang pahintulutan ang paggastos; tanging ang may hawak nito ang makagagawa nito.
1. **Mga bloke at [pagmimina](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [ang mga minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ay nagtitipon ng [mga transaksyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sa mga bloke at gumagamit ng [patunay ng trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) upang makipagpaligsahan sa pagdaragdag ng susunod na bloke.
1. **Malayang [pagberipika](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [ang mga node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ay nagsusuri ng [mga transaksyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) at mga bloke batay sa mga tuntunin ng Bitcoin.
1. **Isang pinagsasaluhang kasaysayan na may naipong [patunay ng trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** kinikilala ng mga kalahok ang [wastong kadena](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) ng [mga transaksyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) na may pinakamaraming [naipong trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) bilang pinagsasaluhang tala.


<!-- micrographic: five-part-response-01 -->
[Nagtutulungan ang limang bahagi upang lutasin ang problema ng dobleng paggastos: isang peer-to-peer na network, mga digital na lagda, mga bloke at pagmimina, malayang beripikasyon, at isang pinagsasaluhang kasaysayan na may pinakamaraming naipong patunay ng trabaho. Sama-sama, pinahihintulutan ng mga ito ang network na tanggihan ang pangalawang paggastos nang walang sentral na awtoridad.](/micrographics/five-part-response-01/tl.md)


Ipinapaliwanag ng modyul na ito ang mga konseptong ito nang mas detalyado. Sama-sama, nagbigay ang mga ito ng praktikal na sagot sa [problema ng dobleng paggastos](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): maaaring tanggihan ng network ang ikalawang pagtatangkang gastusin ang parehong bitcoin nang hindi umaasa sa isang sentral na awtoridad. Inialok ng Bitcoin ang nawawalang kombinasyon na ilang dekada nang hinahanap sa mga eksperimento sa digital na pera.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
