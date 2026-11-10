# 4.7 Yerel harcama ve ödeme alma senaryoları

![](https://cdn.sanity.io/images/vje9ehw2/production/fa265ee4b78004e155781ac30066875cd39cc983-1536x1024.svg)


<!-- micrographic: coffee-shop-payment-01 -->
[Dört adımda bir kafede ödeme: müşteri sipariş verir, garson bir fatura gönderir, müşteri telefonundan bitcoin ile öder ve garson kahveyi teslim eder.](/micrographics/coffee-shop-payment-01/tr.md)


Yerel olarak bilinen mal ve hizmetleri kullanın. Ürünün tam olarak ne olduğu önemli değildir; önemli olan ödemenin ardındaki mantıktır.

###### Senaryo 1: Küçük bir alışveriş

Bir müşteri gündelik bir ürün satın almak istiyor. Satıcı Lightning ve zincir üstü Bitcoin kabul ediyor.

* Küçük ve anlık bir ödeme için hangi yol daha uygun olabilir?
* Ödeme talebini kim oluşturur?
* Müşteri tutarı ve birimi nasıl kontrol eder?
* Satıcı ödemenin başarılı olduğunu nasıl anlar?
* Müşterinin cüzdanında “gönderildi” yazıyor ancak satıcı “alındı” bilgisini görmüyorsa ne olur?

###### Senaryo 2: Emek karşılığı ödeme

Bir çalışan, ödemenin bir kısmını bitcoin olarak almayı kabul ediyor.

* Belirlenen [fiyat](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) yerel [para biriminde](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency) mi, bitcoin cinsinden mi, yoksa [sats](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi) cinsinden mi?
* Hangi anda [döviz kuru](https://curriculum.myfirstbitcoin.org/lexicon/en/#exchange-rate) belirleniyor?
* Varsa ücreti kim ödüyor?
* Alıcı [öz saklama](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody) kullanıyor mu?
* Hangi gelir veya vergi kaydı gerekiyor?
* Çalışan bu tutarı güvenli bir şekilde yönetebilir mi?

###### Senaryo 3: Aile üyeleri arasında bir transfer

Bir kişi, başka bir yerdeki bir aile üyesine [değer](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) göndermek istiyor.

* Mevcut yöntemin maliyetleri ve gecikmeleri nelerdir?
* Her bir kişi bitcoin'i nasıl edinecek veya kullanacak?
* Alıcı bitcoin mi yoksa yerel [para birimi](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency) mi istiyor?
* Her adımda hangi borsa ve [saklama](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) riskleri ortaya çıkıyor?
* Tüm ücretler hesaba katıldığında, yolun tamamı zaman veya para tasarrufu sağlıyor mu?

###### Senaryo 4: Bir iade

Bir satıcının [değeri](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) iade etmesi gerekiyor; yapılan ödeme bir [zincir üstü ödeme](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment)ydi.

* Satıcı neden yeni bir iade adresi talep etmelidir?
* Satıcı, talebin gerçekten müşteriden geldiğini nasıl doğrulayabilir?
* İade [işlem ücretini](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee) kim ödüyor?
* Her iki taraf hangi kaydı saklamalıdır?

###### Senaryo 5: Bir topluluk bağışı

Yerel bir kuruluş bitcoin ile destek almak istiyor.

* Bağışçılar gerçek ödeme talebini nasıl doğrulayacak?
* Alıcı cüzdanı ve yedeğini kim kontrol ediyor?
* Bağışlar zincir üstünde mi, Lightning üzerinden mi yoksa her ikisiyle mi alınacak?
* Şeffaflık için hangi bilgiler kamuya açık olmalı, bağışçıların güvenliği için hangileri gizli kalmalıdır?
* Yerel muhasebe, vergi veya raporlama kuralları için hangi kayıtlar gereklidir?

Canlı bir uygulama için düşük değerli bir ürün veya bir simülasyon kullanın. Öğrenci, ödemeyi onaylamadan önce sürecin tamamını açıklayabilmelidir.
