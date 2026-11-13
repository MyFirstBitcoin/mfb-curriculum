# 3.11 Doğrulama, blok gezginleri ve geri alınamaz işlemler

<!-- card: definition -->
> **Definition – İşlem kimliği ve blok gezgini**
>
> Bir [işlem kimliği](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)), zincir üstü bir [işlemi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tanımlar. Bir [blok gezgini](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer), bir [işlemin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) durumu ve [onay](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) sayısı gibi herkese açık Bitcoin verilerini gösterir. Yararlı bir görünüm sunar; ancak Bitcoin üzerinde bir otorite değildir ve alıcının kimliğinin ya da dürüstlüğünün kanıtı da değildir.


Bu herkese açık bilgiler neyi gösterebilir, neyi gösteremez? Bir [işlemin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) durumunu, hedefini, tutarını, ücretini ve [onay](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) sayısını gösterebilir; ancak bir ödemenin neden yapıldığını veya bir kişinin güvenilir olup olmadığını kanıtlayamaz. Zincir üstü bir [işlem](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), [yayınlandıktan](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) sonra onaysızdır ve geçerli bir bloğa dahil edildiğinde [ilk onayını](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) alır. Sonraki bloklar, işlemin kayıttaki yerine duyulan güveni artırır; ancak yanlış bir hedefi veya bir dolandırıcılığı düzeltmez. Her ödeme için geçerli evrensel bir [onay](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) sayısı yoktur; uygun kontrol, tutara ve riske bağlıdır.

Hazırlanmış bir [işlemi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) incelemek için işlemin [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) değerini edinin, hedeflenen [Bitcoin ağı](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) için güvenilir bir gezgin açın ve durumu, hedefi, tutarı, ücreti ve [onayları](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) kontrol edin. Gezgin yalnızca bir arayüzdür. Bir adresi veya [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) değerini aramak, cihazınızın bu bilgiyle ilgilendiğini gezginin işletmecisine açığa çıkarabilir. Alıştırma için eğitmen tarafından hazırlanmış bir [işlem](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ya da basılı bir ekran görüntüsü kullanın. Bir öğrencinin kişisel adresini veya [işlemini](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) herkese açık bir hizmette aramayın. İleride kişisel bir ödemeyi araştırırsanız, herkese açık bir hizmeti kullanmadan önce bağlantınızın [gizlilik](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) ve güvenlik [ödünleşimlerini](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) öğrenin.


<!-- card: callout -->
> **Herkese açık veriler kimliğin veya dürüstlüğün kanıtı değildir**
>
> Bir [blok gezgini](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) herkese açık [işlem](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) verilerini gösterebilir, ancak bir adresi kimin kontrol ettiğini, bir ödemenin neden yapıldığını veya bir alıcının güvenilir olup olmadığını kanıtlayamaz. Alıştırma için hazırlanmış örnekleri kullanın ve herkese açık hizmetlerde arama yaparken [gizliliğinizi](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) koruyun.



<!-- micrographic: confirmation-timeline-01 -->
[Bir işlem, bekleyen havuzda onaylanmamış olarak bekler, ardından ilk onayı olarak Blok N'ye dahil edilir ve sonraki her blok bir onay daha ekler.](/micrographics/confirmation-timeline-01/tr.md)


![Eğitmen ve yaşça büyük öğrenci, gruba dönük bir monitördeki hazırlanmış bir örneği tartışırken teknik bilgisi olan öğrenci fareyi kullanıyor; izleyici monitörün arka kasasını görüyor.](https://cdn.sanity.io/images/vje9ehw2/staging/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
