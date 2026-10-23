# 10.11 Modül seçeneği B: küçük alışveriş

**Amaç:** Satış noktasında bir ödeme yapmayı uygulamak ve yerel koşullara uygun olduğu durumlarda zincir üstü (on-chain) ödeme ile Lightning'i karşılaştırmak.

**Sunum:** Satıcı doğru ödeme talebini oluşturur; müşteri alıcıyı, ödeme türünü, tutarı, birimi ve ücreti doğrular; her iki taraf da sonucu teyit eder.

**Uygulama:** Düşük değerli bir ürün, test ortamı veya simülasyon kullanın. Başarısız olmuş ya da süresi dolmuş bir talebi de dahil edin.

**Üretim:** Öğrenci onaylanmış ödeme rolünü tamamlar ve şunları açıklar:

* seçilen ödeme kanalının tutara ve zamanlamaya neden uygun olduğunu
* cüzdanı kimin kontrol ettiğini
* ödemenin alındığının nasıl teyit edildiğini
* gönderenin ve satıcının ekranları birbiriyle uyuşmazsa ne olacağını ve
* ne zaman durulması gerektiğini.

**Değerlendirme:** Hızlı bir ödeme, otomatik olarak gizli, kendi kendine saklamalı veya aynı şekilde kesin olmadığı gibi daha yüksek tutarlar için de uygun değildir.
