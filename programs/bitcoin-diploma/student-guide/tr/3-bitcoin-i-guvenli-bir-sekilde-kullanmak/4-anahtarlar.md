# 3.4 Anahtarlar

Bitcoin sahipliği kriptografik anahtarlar aracılığıyla sağlanır.


> **Definition – Özel anahtar**
>
> Bir [özel anahtar](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key), bir cüzdanın geçerli [dijital imzalar](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) oluşturmasını sağlayan gizli bilgidir. Bir imza, ilgili anahtarın kontrol ettiği bitcoin'in harcanmasına yetki verir. [Özel anahtarı](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ele geçiren herkes genellikle bu fonları harcayabilir.


Bir [**açık anahtar**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key), matematiksel olarak [özel anahtardan](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) türetilir. Bir imzanın, [özel anahtarı](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) açığa çıkarmadan doğrulanmasına yardımcı olur. Adresler, [açık anahtar](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) bilgilerinden oluşturulur.

Temel kural basittir:

**Herkese açık alma bilgileri paylaşılabilir. Özel harcama bilgileri gizli kalmalıdır.**

Bir [dijital imza](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature), gerekli [özel anahtarın](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) bir [işlemi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) yetkilendirdiğini kanıtlar. İmza, [özel anahtarı](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) asla [işlemin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) içine yerleştirmez. [Düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node), harcamayı kabul etmeden önce imzayı doğrular.

Yeni başlayanlara yönelik cüzdanların çoğu [tek imzalı yapıyı](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature) kullanır: bir işlemi tek bir özel anahtar yetkilendirir. Modern cüzdanlar birçok anahtarı otomatik olarak yönetir. Yeni başlayanlar tek tek [özel anahtar](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) dizilerini kopyalamamalı veya bunlarla uğraşmamalıdır. Cüzdanın onaylı yedeğini koruyun ve kurtarma prosedürünü izleyin.

Hiçbir meşru eğitmen, cüzdan şirketi, borsa çalışanı, teknik destek personeli veya Bitcoin geliştiricisinin [özel anahtarınıza](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) veya [kurtarma ifadenize (seed phrase)](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase) ihtiyacı yoktur. Bunu isteyen herkes bir tehdit olarak görülmelidir.


> **Light**
>
> **Deneyin:** Hazırlanmış örnekleri üç gruba ayırın: alma işlemi için paylaşılması güvenli olanlar, gizli harcama bilgileri ve herkese açık olabilen ancak bir kişiyle ilişkilendirildiğinde yine de gizli tutulması gereken bilgiler.



<!-- micrographic: private-key-public-info-01 -->
