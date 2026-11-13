# 2.9 Mga Gumagamit, Node, at Minero

Gumagana ang Bitcoin dahil magkakaibang tungkulin ang ginagampanan ng iba't ibang kalahok.

* **Ang mga gumagamit** ay tumatanggap, nag-iingat, at nagpapadala ng bitcoin. Maaaring kontrolin ng isang gumagamit ang sarili niyang mga key na nakaimbak sa isang wallet o gumamit ng isang [tagapag-ingat](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Binibigyan ng mga gumagamit ng kabuluhang pang-ekonomiya ang network sa pamamagitan ng pagpili kung tatanggap sila ng bitcoin at kung aling mga tuntunin o serbisyo ang kanilang pagkakatiwalaan.
* [**Ang mga node**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ay nagpapatakbo ng software ng Bitcoin at nagsasariling nagsusuri kung nasusunod ang mga tuntunin. Ang isang [buong node](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) ay tumitiyak na ang mga [transaksyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ay may mga wastong lagda, na hindi pa nagagastos ang bitcoin, na natutugunan ng mga block ang [patunay ng trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), at na sumusunod ang bagong bitcoin sa [iskedyul ng paglalabas](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Ang mga node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ay nagbabahagi ng wastong datos sa mga kapwa node at tumatanggi sa di-wastong datos.
* [**Ang mga minero**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ay nangangalap ng mga nakabinbing [transaksyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), bumubuo ng mga [kandidatong block](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block), at nakikipagpaligsahan sa pamamagitan ng [patunay ng trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Ang isang matagumpay na [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [ay nagpapalaganap](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) ng isang block at maaaring makatanggap ng pinahihintulutang [subsidyo sa block](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) at [mga bayarin sa transaksyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Ang mga minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ay tumutulong sa pagsasaayos ng pagkakasunod-sunod ng mga [transaksyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) at nagiging dahilan upang ang [talaan](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) ay maging magastos na muling isulat.
* **Ang mga developer** ay nagsusuri, nagsusulat, at nagmumungkahi ng mga pagbabago sa software. Hindi nila pag-aari ang mga tuntunin ng Bitcoin. Nagkakaroon lamang ng saysay ang isang pagbabago sa software kung pipiliin ng mga kalahok na magpatakbo ng software na sumusunod sa mga tuntuning iyon.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Apat na papel sa Bitcoin: ang mga gumagamit ay tumatanggap, nag-iingat at nagpapadala ng bitcoin, ang mga node ay nagsasariling nagbeberipika ng pagsunod sa mga tuntunin, ang mga minero ay bumubuo ng mga kandidatong bloke gamit ang patunay ng trabaho, at ang mga developer ay nagmumungkahi ng software. Walang iisang papel ang kumokontrol sa network.](/micrographics/bitcoin-participant-roles-01/tl.md)


Nililimitahan ng mga tungkuling ito ang isa't isa:

* hindi maaaring gumastos ng bitcoin ang isang gumagamit kung wala ang kinakailangang wastong lagda
* ang isang [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ay maaaring magmungkahi ng isang block, ngunit [ang mga node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ang nagpapasya kung sumusunod ito sa mga tuntunin
* ang isang [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ay nagsusuri ayon sa sarili nitong mga tuntunin, ngunit ang [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) ay nangangailangan ng magkakatugmang tuntunin sa buong network
* maaaring magmungkahi ng software ang mga developer, ngunit ang mga kalahok ang nagpapasiya kung patatakbuhin nila ito

May mga taong gumaganap ng ilang tungkulin. Ang isang [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ay maaaring magpatakbo ng isang [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) at maging gumagamit din. Hindi kailangang gampanan ng isang baguhan ang bawat tungkulin upang maipaliwanag kung paano binabalanse ng mga tungkulin ang isa't isa.

**Maikling tanong:** Bakit ang isang [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ay nagsusuri ng mga [transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Magbigay kayo ng kahit isang tuntunin na sinusuri ng isang [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node).

![Ginagabayan ng tagapagturo ang mag-aaral ng teknikal na paksa sa isang computer na nagpapatakbo ng node, habang nakaharap sa kanila ang monitor at nakikita ng tumitingin ang likurang kaha nito.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
