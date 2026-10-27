# 3.4 Mga Susi

Ipinapatupad ang pagmamay-ari ng Bitcoin sa pamamagitan ng mga kriptograpikong susi.


<!-- card: definition -->
> **Definition – Pribadong susi**
>
> Ang [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ay lihim na impormasyon na nagbibigay-daan sa isang wallet na gumawa ng mga wastong [digital na lagda](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Pinahihintulutan ng isang lagda ang paggastos ng bitcoin na kontrolado ng kaukulang susi. Sinumang makakuha ng [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ay karaniwang makakagastos ng pondong iyon.


Ang [**pampublikong susi**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) ay kinukuha sa pamamagitan ng matematika mula sa [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Nakakatulong ito sa pagberipika ng isang lagda nang hindi ibinubunyag ang [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Ang mga address ay ginagawa mula sa [pampublikong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) na impormasyon.

Simple ang pangunahing tuntunin:

**Maaaring ibahagi ang pampublikong impormasyon para sa pagtanggap. Dapat manatiling lihim ang pribadong impormasyon para sa paggastos.**

Ang [digital na lagda](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) ay nagpapatunay na ang kinakailangang [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ay nagpahintulot sa isang [transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Hindi nito inilalagay ang [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) sa loob ng [transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Ang mga node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ay nagbeberipika ng lagda bago tanggapin ang paggastos.

Karamihan sa mga wallet para sa mga baguhan ay gumagamit ng [iisang lagda](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): isang pribadong susi ang nagpapahintulot sa isang transaksiyon. Awtomatikong pinamamahalaan ng mga makabagong wallet ang maraming susi. Hindi dapat kopyahin o pangasiwaan ng mga baguhan ang mga indibidwal na [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) na string. Pangalagaan po ninyo ang aprubadong backup ng wallet at sundin ang pamamaraan nito sa pagbawi.

Walang lehitimong tagapagturo, kumpanya ng wallet, empleyado ng palitan, kawani ng teknikal na suporta, o developer ng Bitcoin na nangangailangan ng inyong [pribadong susi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) o [seed phrase](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Dapat ituring na banta ang sinumang humihingi nito.


<!-- card: light -->
> **Subukan po ninyo:** Pagbukud-bukurin ang mga inihandang halimbawa sa tatlong pangkat: ligtas ibahagi para sa pagtanggap, lihim na impormasyon para sa paggastos, at impormasyong maaaring maging pampubliko ngunit dapat pa ring panatilihing pribado kapag nakaugnay sa isang tao.



<!-- micrographic: private-key-public-info-01 -->
[Ang isang lihim na pribadong susi, na hindi dapat ibahagi kailanman, ay pinagmumulan ng pampublikong impormasyong maaaring ibahagi: isang pampublikong susi na hinango mula rito at isang address sa pagtanggap na nilikha mula roon. Ang parehong pribadong susi ay lumilikha ng mga lagdang bineberipika ng mga node nang hindi kailanman nalalaman ang pribadong susi.](/micrographics/private-key-public-info-01/tl.md)
