# 2.10 Patunay ng trabaho

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Patunay ng trabaho**
>
> [Ang patunay ng trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ay ang prosesong ginagamit ng mga [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) upang makipagpaligsahan para sa karapatang magmungkahi ng susunod na bloke.


Ang [punsiyong hash](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) ay ginagawang resulta na may takdang haba ang datos. Ang maliit na pagbabago sa input ay lumilikha ng bagong resultang hindi mahuhulaan. Ang [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ay nagbabago ng maliit na bahagi ng datos sa isang iminungkahing bloke at paulit-ulit itong hina-hash. Balido lamang ang isang resulta kapag ang bilang nito ay mas mababa sa [target](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) ng network, isang hangganang itinakda ng mga tuntunin; ang mas mababang [target](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) ay nangangahulugan ng mas kaunting [balidong resulta](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) at mas maraming pagsubok. Walang mas maikling paraan, kaya ang mga [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ay maaaring kailangang gumawa ng maraming pagsubok.

Kapag ang isang [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ay nakahanap ng isang [balidong resulta](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), ito ay [nagbo-broadcast](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) ng bloke. [Ang mga node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ay maaaring mabilis na magsuri ng patunay, kahit na nangailangan ng malaking pagkukuwenta at enerhiya ang paghahanap nito. Kung may kasamang [transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ang bloke, ang [transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) na iyon ay tumatanggap ng [unang kumpirmasyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) nito: naisama na ang rekord nito sa isang balidong bloke. Bawat balidong blokeng idinaragdag pagkatapos nito ay nagdaragdag ng isa pang [kumpirmasyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), kaya para sa [transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), ang puwesto nito sa [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) ay mas magastos nang isulat muli. Mahalaga ang pagkakaibang ito: magastos gawin ang trabaho ngunit madaling beripikahin.


<!-- micrographic: proof-of-work-process-01 -->


[Ang patunay ng trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ay may ilang layunin:

* binibigyan nito ang mga independiyenteng [minero](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ng paraan upang makipagpaligsahan nang walang sentral na tagapag-iskedyul
* dahil dito, ang pagkakasunod-sunod ng mga [transaksiyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ay magastos isulat muli
* iniuugnay nito ang seguridad ng network sa pisikal na kagamitan at enerhiya
* sinusuportahan nito ang isang pampublikong paraan ng pagpili sa pagitan ng magkakatunggaling balidong kasaysayan: ang kadena na may pinakamaraming [naipong trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Ang pagmimina](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ay hindi lumulutas ng mga kapaki-pakinabang na ekwasyon para sa ibang layunin. Layunin nitong pangalagaan ang pagkakasunod-sunod sa Bitcoin ng mga [transaksyon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Pana-panahong inaayos ng network ang target: kapag masyadong mabilis ang pagdating ng mga bloke, ibinababa nito ang target, at kapag masyadong mabagal ang pagdating ng mga ito, itinataas nito ang target. Layunin nitong mapanatili ang karaniwang pagdating ng humigit-kumulang isang bloke kada sampung minuto habang nagbabago ang kapasidad sa pagkompyut.

[Ang patunay ng trabaho](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ay may tunay na gastos sa enerhiya. Iginigiit ng mga tagasuporta na ang gastos na ito ang nagsisilbing pundasyon ng seguridad ng Bitcoin at maaaring lumikha ng pangangailangan para sa enerhiyang naiaangkop ang paggamit o hindi sana magagamit. Kinukuwestiyon ng mga kritiko ang dami at pinagmumulan ng enerhiyang ginagamit. Sa isang responsableng pagsusuri, itinatanong kung anong enerhiya ang ginagamit, saan ito nagmumula, anong seguridad ang naibibigay nito, at anong mga alternatibo ang pinaghahambing.

![Tinatalakay ng tagapagturo, ng baguhang mag-aaral, at ng mag-aaral na may kaalamang teknikal ang isang kagamitang pangmina na nakapatong sa mesa, na may bentilador at hiwalay na suplay ng kuryente.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
