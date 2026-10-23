# 3.14 Zincir üstü ve Lightning ödemeleri

![](https://cdn.sanity.io/images/vje9ehw2/production/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Zincir üstü ve Lightning ödemeleri**
>
> [Zincir üstü ödemeler](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) Bitcoin'in [blok zincirine](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) kaydedilir ve [onay](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) kazanır. Lightning, Bitcoin üzerine kurulu, hızlı ve sık ödemeleri destekleyebilen bir ödeme ağıdır. Bir Lightning ödemesi hızla tamamlanabilir ya da başarısız olabilir; Lightning cüzdanı ise yine de emanetçi veya kendi kendine saklama (self-custody) türünde olabilir.



> **Dark – Ödeme yolu, saklama türünü belirlemez**
>
> Zincir üstü ve Lightning ödemeleri farklı [ödünleşimler](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) içerir. Bir Lightning cüzdanı emanetçi veya kendi kendine saklama türünde olabilir; hızlı ve başarılı bir ödeme, bir hizmetin daha büyük bakiyeler ya da her durum için uygun olduğunu kanıtlamaz.



<!-- micrographic: onchain-lightning-table-01 -->


Alıcı hangi yolu bekliyor? Ödeme yapmadan önce size bir zincir üstü adres mi, yoksa bir [Lightning faturası](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) ya da ödeme talebi mi verdiğini teyit edin. Zincir üstü bir cüzdan her [Lightning faturasını](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) doğrudan ödeyemez; bir Lightning cüzdanı da her zincir üstü işlemi desteklemeyebilir. Bazı uygulamalar her iki yolu da destekler, ancak ek ücretler ya da hizmet bağımlılıkları getirebilir. Ayrıntılı Lightning kurulumu, kanallar, yönlendirme ve [likidite](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) konuları [İleri Düzey Öğrenme](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) kapsamındadır; canlı yerel uygulama ise güvenli ve uygun olduğunda **Modül 4** kapsamında yapılır.

Hazırlanmış bir senaryonun her iki ödeme yolunu da sunduğunu düşünün. Kullanmayı planladığınız cüzdan hangi talebi kullanabilir ve onaylamadan önce neleri kontrol edersiniz? Yanıt, alınan ödeme talebine, cüzdana ve duruma bağlıdır; evrensel bir “en iyi” yola değil.

![Eğitmen, tahtadaki iki farklı geometrik ödeme yolunu gösterirken başlangıç düzeyindeki ve teknik öğrenciler bunları değerlendiriyor.](https://cdn.sanity.io/images/vje9ehw2/production/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
