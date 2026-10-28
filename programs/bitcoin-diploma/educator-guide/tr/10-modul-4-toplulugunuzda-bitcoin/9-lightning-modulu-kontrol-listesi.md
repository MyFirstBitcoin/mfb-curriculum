# 10.9 Lightning modülü kontrol listesi

Bir Lightning atölyesinden önce şunları doğrulayın ve açıklayın:

* cüzdanın emanetçi (custodial) mi yoksa öz saklamalı (self-custodial) mı olduğu
* cüzdana nasıl fon yüklendiği
* fon yükleme veya çekme işleminin zincir üstü (on-chain) bir işlem mi yoksa bir hizmet mi kullandığı
* sağlayıcı veya cihaz arızalanırsa kurtarma ve sürekliliğin nasıl sağlanacağı
* talebin bir fatura mı, desteklenen bir [Lightning adresi](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) mi yoksa başka bir tür mü olduğu
* tutar, birim, alıcı, son geçerlilik süresi, ücret, limitler ve [likidite](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) ile ilgili hususlar
* başarılı, beklemede, süresi dolmuş veya başarısız bir ödemenin nasıl göründüğü
* her iki tarafın sonucu birbirinden bağımsız olarak nasıl doğruladığı ve
* çevrimdışı simülasyon.


<!-- card: dark -->
> **Tek bir başarılı Lightning ödemesi, yalnızca bu güzergâhın bir kez çalıştığını kanıtlar**
>
> Cüzdanın daha büyük bakiyeler için güvenli olduğunu ya da aynı yolun her yerde çalışacağını kanıtlamaz.



<!-- micrographic: lightning-payment-sequence-01 -->
[Altı adımda bir Lightning ödemesi: alıcı bir talep oluşturur, gönderen talebi tarar, alıcıyı, tutarı, birimi, son geçerlilik süresini ve ücreti kontrol eder, onaylar, ödeme yönlendirilir ve her iki cüzdan da sonucu gösterir. Her cüzdan emanetçi veya kendi kendine saklama türünde olabilir; başarısız olan veya süresi dolan bir ödeme yeni bir taleple yeniden başlar.](/micrographics/lightning-payment-sequence-01/tr.md)
