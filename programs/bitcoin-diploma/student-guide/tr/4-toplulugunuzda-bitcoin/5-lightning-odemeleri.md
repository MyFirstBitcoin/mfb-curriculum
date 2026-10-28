# 4.5 Lightning ödemeleri

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Alıcı, telefonunda tutarı içeren bir Lightning ödeme talebi oluşturur, gönderen bunu tarayıp öder ve ödeme kısa bir süre sonra alıcının telefonuna ulaşır.](/micrographics/lightning-phone-payment-01/tr.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[Altı adımda bir Lightning ödemesi: alıcı bir talep oluşturur, gönderen talebi tarar, alıcıyı, tutarı, birimi, son geçerlilik süresini ve ücreti kontrol eder, onaylar, ödeme yönlendirilir ve her iki cüzdan da sonucu gösterir. Her cüzdan emanetçi veya kendi kendine saklama türünde olabilir; başarısız olan veya süresi dolan bir ödeme yeni bir taleple yeniden başlar.](/micrographics/lightning-payment-sequence-01/tr.md)


Lightning, hızlı ve küçük Bitcoin ödemelerini pratik hâle getirebilir. Bir satıcı tezgâhı, tekrarlanan yerel ödemeler, çevrimiçi hizmetler veya zincir üstü (on-chain) ücretin ödeme tutarına göre çok yüksek kalacağı transferler için uygun olabilir.

Yerel bir Lightning gösterimi şunları belirlemelidir:

* cüzdanın emanetçi (custodial) mi yoksa öz saklamalı (self-custodial) mı olduğu
* cüzdana nasıl bakiye yüklendiği
* bakiye yüklemenin zincir üstü bir [işlem](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mi yoksa bir hizmet mi gerektirdiği
* bakiyeyi hangi yedekleme veya kurtarma yönteminin koruduğu
* hangi tür ödeme talebinin kullanıldığı
* hangi ücretlerin veya limitlerin geçerli olduğu
* bir ödeme başarısız olduğunda ne olduğu
* alıcının ödemeyi nasıl doğruladığı

Bir [**Lightning faturası**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), belirli bir ödeme için oluşturulan bir ödeme talebidir. Bir tutar, hedef bilgisi ve bir son geçerlilik süresi içerebilir. Ödeme yapmadan önce cüzdanın [onay](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) ekranını okuyun.

Bir [**Lightning adresi**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address), bazı hizmetlerin desteklediği, insanlar tarafından okunabilir bir tanımlayıcıdır. Bir e-posta adresine benzeyebilir, ancak bir e-posta hesabı değil, ödeme yönlendirmeyi kolaylaştıran bir araçtır. Onu destekleyen sağlayıcıya veya alan adına bağlıdır.

Rehberli bir ödeme için:

1. Alıcı doğru talebi oluşturur.
1. Gönderen talebi tarar veya kopyalar.
1. Gönderen alıcıyı, tutarı, birimi ve ücreti kontrol eder.
1. Gönderen, ancak ayrıntılar doğru olduktan sonra onay verir.
1. Her iki taraf da sonucu kendi cüzdanında doğrular.
1. Grup, [saklama](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) ve başarısızlık risklerini açıklar.

Başarılı bir Lightning ödemesinin, cüzdanın daha büyük bakiyeler için güvenli olduğunu kanıtladığını varsaymayın. Ödeme kolaylığı ile [saklama](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) güvenliği ayrı konulardır.
