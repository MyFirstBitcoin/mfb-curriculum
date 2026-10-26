# 9.20 Zincir üstü ve Lightning ödemeleri

Ödeme yolunu [saklamadan (custody)](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) ayıran bir karşılaştırma kullanın.


| Soru | Zincir üstü (on-chain) | Lightning |
| --- | --- | --- |
| Mutabakat nerede kaydedilir? | Doğrudan Bitcoin'in blok zincirinde | Ödeme güncellemeleri Bitcoin'in üzerine kurulu bir ağ aracılığıyla gerçekleşir; kanallar nihayetinde Bitcoin'e dayanır |
| Yeni başlayanlar için yaygın alma bilgisi | Zincir üstü adres | Fatura (invoice), desteklenen Lightning adresi veya onaylanmış başka bir talep türü |
| Tipik kullanım | Temel katman mutabakatı, genellikle daha büyük veya daha seyrek transferler | Yerel araçların ve likiditenin desteklediği yerlerde genellikle küçük veya sık ödemeler |
| Zamanlama | İlk onay, işlemin bir bloğa dahil edilmesine bağlıdır | Genellikle hızlıdır, ancak ödemeler başarısız olabilir |
| Ücretler ve kapasite | İşlem verisine ve blok alanı talebine bağlıdır | Cüzdana, rotaya, likiditeye, hizmete ve ödeme koşullarına bağlıdır |
| Saklama | Emanetçi veya kendi kendine saklamalı olabilir | Emanetçi veya kendi kendine saklamalı olabilir |
| Yeni başlayanlar için temel kontrol | Doğru adres, ağ, tutar, ücret ve onay | Doğru fatura veya hedef, tutar, son geçerlilik süresi, ücret ve ödeme sonucu |


Lightning ayrı bir coin değildir. Başarılı bir Lightning ödemesi, cüzdanın daha büyük bir bakiye için güvenli olduğunu kanıtlamaz. Kanal işletimi, yönlendirme altyapısı ve [likidite](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) yönetimi, [İleri Düzey Öğrenme](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) konularıdır ve Bitcoin Diploması kapsamı dışında kalır.


<!-- micrographic: on-chain-and-lightning-01 -->
