# 8.10 Kullanıcılar, düğümler, madenciler, geliştiriciler ve hizmetler

Yeni başlayanlar için şu kesin sınırları kullanın:


| Rol | Yeni başlayanlar için temel işlev | Şu anlama gelmez |
| --- | --- | --- |
| Kullanıcı | Doğrudan veya hizmetler aracılığıyla bitcoin almayı, tutmayı, göndermeyi, doğrulamayı ve kabul etmeyi seçer | Ağın her parçasını otomatik olarak çalıştırır |
| Düğüm | İşlemleri ve blokları kendi kurallarına göre bağımsız olarak kontrol eder ve geçerli verileri iletir | Yeni bloklar oluşturur veya herkese kural dayatır |
| Madenci | Aday bloklar oluşturur ve bunların sırasını önermek için iş ispatı yapar | Geçersiz ihracı veya işlemleri dürüst düğümler için geçerli hâle getirebilir |
| Geliştirici | Yazılımı inceler, yazar ve önerir | Katılımcıları bir kural değişikliğini benimsemeye zorlayabilir |
| Bitcoin hizmeti | Cüzdan, borsa, blok gezgini, ödeme veya başka bir arayüz sağlar | Bitcoin protokolünün kendisidir |



<!-- micrographic: bitcoin-participant-roles-01 -->


#### Etkinlik: geçersiz blok

Bir öğrenciye [madenci](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) rolünü vererek ona [bir aday blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) verin; bu blok, [düğüm](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kural kartının izin verdiğinden daha fazla sübvansiyon oluşturur. [Düğüm](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) rolündeki öğrenciler bloğu kontrol eder ve reddeder.

Değerlendirme:

* Bu [madenci](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gerçek bir iş yaptı, ancak yine de kuralları çiğneme izni kazanmadı.
* [Düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kuralları bağımsız olarak uygular, ancak gerçek ağ bir sınıf oylaması değil, yazılım ve iletişimden oluşur.
* Bir geliştirici başka kurallar yazabilir, ancak bunları benimsemek gönüllülüğe dayanır ve uyumsuz kurallar ayrı bir ağ oluşturabilir.

Sorun:

> Bir [düğüm](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) işlemleri neden doğrular? Kontrol ettiği en az bir kuralı söyleyin.
