# 2.5 Blokzincir: Bitcoin'in Herkese Açık Defteri

<!-- card: definition -->
> **Definition – Blok Zinciri**
>
> Bitcoin'in [blok zinciri](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain), birçok bağımsız bilgisayarda kopyaları tutulan, herkese açık bir [işlem](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) kaydıdır. Bir blok, bir dizi geçerli [işlemi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) bu kaydın önerilen bir sonraki bölümünde bir araya getirir. Her geçerli blok bir öncekine bağlanır ve böylece ağa doğrulanabilecek sıralı, ortak bir geçmiş sunar.



<!-- card: light -->
> **Düğümler uzlaşıya nasıl varır?**
>
> [Düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) aynı kuralları bağımsız olarak denetler ve en fazla birikmiş [iş kanıtına](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) sahip geçerli geçmişte buluşur. Daha önceki bir kaydı değiştirmek, o kaydın bloğunu değiştirir ve sonraki bloklarla olan bağlantıları koparır; bu nedenle rakip bir geçmişin, [düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) onu kabul etmeden önce bu işi yeniden yapması ve aradaki farkı kapatması gerekir. Bu maliyetli sıralama süreci, ağın merkezi bir kayıt tutucu olmadan [uzlaşıya](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) varmasına yardımcı olur. Kopyalar aynı anda değişmez; [düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verileri bağımsız olarak alır ve doğrular. Bitcoin, ortalama olarak yaklaşık her on dakikada bir yeni blok üretilmesini hedefler. Geçmişi yeniden yazmak zor ve maliyetlidir, ancak değiştirilmesi kelimenin tam anlamıyla imkânsız değildir: geçici rakip geçmişler ve yeniden düzenlemeler yaşanabilir.
