# How Transations Work

## Alt text

Alice'ten Bob'a yapılan bir bitcoin ödemesini gösteren dikey, yedi adımlı bir akış: işlemin oluşturulması ve imzalanması, ağa yayınlanması, düğümler tarafından doğrulanması, mempool, bir bloğa kazılması ve onaylar biriktikçe bloğun blok zincirine eklenmesi.

## Texts

### s1-label

Alice bir işlem oluşturur

### s1-desc

Coinleri kimin alacağını, ne kadar olduğunu ve madenciler için bir ücreti belirtir.

### r-to

Alıcı

### r-to-v

Bob&#8217;un adresi

### r-amount

Tutar

### r-fee

Ağ ücreti

### s2-label

İşlemi özel anahtarıyla imzalar

### s2-desc

Dijital imza, coinleri harcama hakkının ona ait olduğunu kanıtlar.

### s3-label

Ağa yayınlanır

### s3-desc

İmzalanan işlem, kurallara uyup uymadığını kontrol eden düğümlere gönderilir.

### chip-sig

Geçerli imza

### chip-bal

Yeterli bitcoin

### chip-rules

Kurallara uygun

### s4-label

Mempool'da bekler

### s4-desc

Geçerli işlemler, bekleyen ödemelerden oluşan bir havuzda bekler.

### s5-label

Madenciler onu bir bloğa ekler

### s5-desc

Madenciler işlemleri seçer ve bir blok kazmak için yarışır.

### s6-label

Blok, blok zincirine eklenir

### s6-desc

Diğer düğümler bloğu doğrular, ardından onu kalıcı olarak zincire ekler.

### s7-label

Bob bitcoini alır

### s7-desc

İşlem artık onaylanmıştır. Alice bu coinleri tekrar harcayamaz ve Bob aldığı tutarı harcayabilir.

### foot

<strong>Her yeni blok işlemi daha da derine gömer.</strong> Üstüne eklenen her blokla birlikte işlemi geri almak katlanarak zorlaşır &#8212; bitcoini kesin kılan da budur.
