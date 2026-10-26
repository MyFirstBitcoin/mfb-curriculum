# 2.3 Erken dijital para girişimleri ve çifte harcama sorunu

Bitcoin, dijital paraya yönelik ilk girişim değildi. Kırk yıllık deneylerin üzerine inşa edildi ve başarılı tasarımını şekillendirmeye yardımcı olan daha önceki birçok projenin fikirlerinden yararlandı.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash), [kriptografiyi](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) özel dijital ödemeleri desteklemek için kullandı. Merkezi bir şirkete ve bankacılık ilişkilerine bağımlıydı. Şirket iflas ettiğinde sistem, bağımsız bir para ağı olarak varlığını sürdüremedi.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash), [iş ispatını](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) istenmeyen e-postaları maliyetli hâle getirmek için kullandı. Gönderenin bilgisayarı, bir mesaj göndermeden önce belirli bir iş yapmak zorundaydı. Bu fikir, hesaplama maliyetinin kötüye kullanımı nasıl caydırabileceğini gösterdi.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold), hesaplama işinin kıt dijital kayıtlar oluşturabileceği önerilen bir sistemi tanımladı. Tam bir merkeziyetsiz para sistemi olarak hayata geçirilmedi, ancak dijital [kıtlık](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) ve ispat hakkında önemli fikirler geliştirdi.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) ve [**yeniden kullanılabilir iş ispatı (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work), katılımcıların kıt dijital [değer](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) yaratmaları veya aktarmaları için yalnızca tek bir merkezi veritabanına dayanmayan yolları araştırdı. Eksiktiler, ancak işleyen bir sistemin nelere ihtiyaç duyacağını netleştirmeye yardımcı oldular.
* Her ne kadar [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) para olmasa da, bir [eşler arası ağın](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network), tüm sistemi kontrol eden tek bir merkezi sunucu olmadan birçok bağımsız bilgisayarın bilgi paylaşmasına olanak tanıyabileceğini gösterdi.

Bu deneyler birlikte, yapbozun işe yarar parçalarını ortaya koydu. Aynı zamanda geriye kalan sorunu da netleştirdiler.


> **Definition – Çifte harcama**
>
> [Çifte harcama](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending), aynı dijital birimi iki farklı alıcıya gönderme girişimidir. Dijital veriler kusursuz biçimde kopyalanabildiğinden, bir dijital para sisteminin hangi [işlemin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) geçerli olduğunu belirlemenin bir yoluna ihtiyacı vardır.


[Merkezi sistemler](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) bunu, hangi ödemenin önce geldiğine tek bir güvenilir veritabanının karar vermesini sağlayarak önler. 31 Ekim 2008'de [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto)'nun teknik makalesi [_Bitcoin: A Peer-to-Peer Electronic Cash System_](https://bitcoin.org/bitcoin.pdf), farklı bir yaklaşımı açıkladı: banka, şirket veya başka bir merkezi otorite olmadan ortak bir ödeme geçmişi oluşturabilen, herkese açık bir sistem.

Makale, bu yaklaşım için gereken özellikleri bir araya getirdi:

1. **Bir [eşler arası ağ](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [işlemler](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) doğrudan katılımcılardan oluşan bir ağa duyurulur.
1. **[Dijital imzalar](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** bir [özel anahtar](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key), bir harcamayı yetkilendirmek için imza oluşturan gizli bir bilgidir; bunu yalnızca sahibi yapabilir.
1. **Bloklar ve [madencilik](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [madenciler](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) topladıkları [işlemleri](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) bloklara yerleştirir ve [iş ispatını](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) kullanarak bir sonraki bloğu eklemek için yarışır.
1. **Bağımsız [doğrulama](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tek tek [işlemleri](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ve blokları Bitcoin'in kurallarına göre kontrol eder.
1. **Ortak bir geçmiş ve birikmiş [iş ispatı](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** katılımcılar, [geçerli](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) olan [işlem zincirleri](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) arasından en fazla [birikmiş işe](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) sahip olanı ortak kayıt olarak kabul eder.


<!-- micrographic: five-part-response-01 -->


Bu modül bu kavramları daha ayrıntılı açıklamaktadır. Bunlar bir arada, [çifte harcama sorununa](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) pratik bir yanıt getirdi: ağ, merkezi bir otoriteye dayanmadan aynı bitcoin'i ikinci kez harcama girişimini reddedebilir. Bitcoin, onlarca yıldır süren dijital para deneylerinin aradığı eksik bileşimi sundu.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
