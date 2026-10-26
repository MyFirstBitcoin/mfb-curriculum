# 2.10 İş İspatı

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – İş kanıtı**
>
> [İş kanıtı](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), [madencilerin](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bir sonraki bloğu önerme hakkı için yarışırken kullandığı süreçtir.


Bir [hash fonksiyonu](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) veriyi sabit uzunlukta bir sonuca dönüştürür. Girdideki küçük bir değişiklik, öngörülemeyen yeni bir sonuç üretir. Bir [madenci](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) önerilen bir bloktaki küçük bir veri parçasını değiştirir ve onu tekrar tekrar hash'ler. Bir sonuç, yalnızca sayısı ağın [hedefinin](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) altında olduğunda geçerlidir; hedef, kurallarla belirlenen bir eşiktir. Daha düşük bir [hedef](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), daha az [geçerli sonuç](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) ve daha fazla deneme anlamına gelir. Kestirme bir yol yoktur, bu nedenle [madencilerin](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) çok sayıda deneme yapması gerekebilir.

Bir [madenci](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner), [geçerli bir sonuç](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) bulduğunda bloğu [yayınlar](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast). [Düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node), bulunması önemli miktarda hesaplama ve enerji gerektirmiş olsa da kanıtı hızlıca kontrol edebilir. Blok bir [işlem](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) içeriyorsa, o [işlem](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) böylece [ilk onayını](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) alır: kaydı geçerli bir bloğa dahil edilmiştir. Ondan sonra eklenen her geçerli blok bir [onay](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) daha ekler ve [işlemin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) kaydının [blokzincirdeki](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) yerini yeniden yazmayı daha maliyetli hale getirir. Bu fark önemlidir: işin üretilmesi maliyetli, doğrulanması ise kolaydır.


<!-- micrographic: proof-of-work-process-01 -->


[İş kanıtı](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) birkaç amaca hizmet eder:

* bağımsız [madencilere](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) merkezi bir planlayıcı olmadan yarışmanın bir yolunu sunar
* bu sayede [işlemlerin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sıralamasını yeniden yazmak maliyetli hale gelir
* ağ güvenliğini gerçek dünyadaki ekipman ve enerjiye bağlar
* rakip geçerli geçmişler arasında seçim yapmak için kamuya açık bir yöntemi destekler: en fazla [birikmiş işe](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) sahip zincir

[Madencilik](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), dışarıdaki bir amaca yönelik yararlı denklemler çözmez. Amacı, Bitcoin [işlemlerinin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sıralamasını güvence altına almaktır. Ağ, hedefi periyodik olarak ayarlar: bloklar çok hızlı geldiğinde hedefi düşürür, çok yavaş geldiğinde ise yükseltir; böylece işlem gücü değiştikçe ortalama olarak yaklaşık her on dakikada bir blok hedeflenir.

[İş ispatı](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) gerçek bir enerji maliyeti içerir. Destekçiler, Bitcoin'in güvenliğini sağlamlaştıranın bu maliyet olduğunu ve bunun esnek ya da başka türlü kullanılmayacak enerji için talep yaratabileceğini savunur. Eleştirmenler ise kullanılan enerjinin miktarını ve kaynağını sorgular. Sorumlu bir değerlendirme; hangi enerjinin kullanıldığını, nereden geldiğini, ne tür bir güvenlik sağladığını ve hangi alternatiflerle karşılaştırıldığını sorar.

![Eğitmen, başlangıç düzeyindeki öğrenci ve teknik öğrenci, fanlı ve ayrı güç kaynaklı masaüstü bir madencilik cihazını tartışıyor.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
