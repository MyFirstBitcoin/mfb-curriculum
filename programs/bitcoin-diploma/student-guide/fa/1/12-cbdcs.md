# 1.12 ارزهای دیجیتال بانک مرکزی (CBDCs)

<!-- card: definition -->
> **Definition – ارز دیجیتال بانک مرکزی (CBDC)**
>
> یک [ارز دیجیتال بانک مرکزی](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc)، یا [CBDC](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc)، شکل دیجیتالیِ [پول فیات](https://curriculum.myfirstbitcoin.org/lexicon/en/#fiat-money) است که به‌عنوان یک [بدهی](https://curriculum.myfirstbitcoin.org/lexicon/en/#liability) از سوی یک [بانک مرکزی](https://curriculum.myfirstbitcoin.org/lexicon/en/#central-bank) منتشر می‌شود: این طلبی است که [بانک مرکزی](https://curriculum.myfirstbitcoin.org/lexicon/en/#central-bank) به دارندهٔ آن بدهکار است. این ارز با پول نقد فیزیکی و سپردهٔ عادی در یک بانک تجاری تفاوت دارد، هرچند ممکن است تجربهٔ کاربری آن‌ها مشابه به نظر برسد.


[CBDC](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc) طراحی‌های متفاوتی دارد. برخی عمدتاً برای مؤسسات مالی در نظر گرفته شده‌اند؛ برخی دیگر برای استفادهٔ عموم پیشنهاد می‌شوند. ابتدا بپرسید [صادرکننده](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer) کیست: در مورد یک [CBDC](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc)، [بانک مرکزی](https://curriculum.myfirstbitcoin.org/lexicon/en/#central-bank) همچنان [صادرکننده](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer) است و همچنان می‌تواند سیاست پولی اعمال کند. یک [CBDC](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc) بنابراین نه عرضهٔ پول را ثابت می‌کند و نه کنترل مرکزی را از میان می‌برد؛ تغییر آن صرفاً در فناوری و توزیعِ [پول فیات](https://curriculum.myfirstbitcoin.org/lexicon/en/#fiat-money) است.

سپس بپرسید این طراحی چه امکاناتی فراهم می‌کند. بسته به قواعد، یک [CBDC](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc) ممکن است تسویهٔ سریع‌تر، دسترسی گسترده‌تر یا قابلیت‌های تازه‌ای برای پرداخت فراهم کند. همچنین ممکن است به مؤسسات توانایی بیشتری برای نظارت بر [تراکنش‌ها](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)، اعمال قواعد، محدود کردن استفاده یا پیوند دادن مستقیم هویت به پرداخت‌ها بدهد. این همان کنترل متمرکز است: به‌جای آنکه کاربران عادی به‌طور مستقل قواعد مربوط را تعیین کنند یا تغییر دهند، یک مؤسسه این کار را انجام می‌دهد.

![](https://cdn.sanity.io/images/vje9ehw2/staging/6171d569570864221093ac065898303ea3c20838-1536x1024.svg)


<!-- micrographic: cbdc-comparison-table-01 -->
[جدولی که پول نقد، سپرده‌های بانکی، ارز دیجیتال بانک مرکزی برای عموم و بیت‌کوین را از نظر ناشر، شکل، دسترسی، قابل مشاهده بودن پرداخت‌ها، قواعد عرضه و راستی‌آزمایی مقایسه می‌کند. دیجیتال بودن به معنای غیرمتمرکز بودن نیست: ارز دیجیتال بانک مرکزی همچنان توسط بانک مرکزی منتشر می‌شود و دسترسی به آن، قابل مشاهده بودن پرداخت‌ها و راستی‌آزمایی آن به طراحی‌اش بستگی دارد.](/micrographics/cbdc-comparison-table-01/fa.md)


دیجیتالی بودن به‌خودی‌خود به معنای غیرمتمرکز بودن، کمیاب بودن، خصوصی بودن یا امکان راستی‌آزمایی مستقل نیست. یک [CBDC](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc) ممکن است از فناوری دیجیتال استفاده کند، اما همچنان نوعی [پول فیات](https://curriculum.myfirstbitcoin.org/lexicon/en/#fiat-money) است اگر [صادرکننده](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuer)، قواعد عرضه، قواعد دسترسی و مجوزهای پرداخت آن همچنان به‌صورت متمرکز مدیریت شوند.

هنگام بحث دربارهٔ یک [CBDC](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc)، بپرسید:

* چه کسی پول را منتشر می‌کند؟
* چه کسانی می‌توانند آن را نگهداری یا از آن استفاده کنند؟
* چه اطلاعاتی جمع‌آوری می‌شود؟
* آیا می‌توان یک پرداخت را مسدود، محدود یا برگشت داد؟
* آیا قواعد می‌توانند تغییر کنند؟
* آیا کاربران عادی می‌توانند به‌طور مستقل قواعد را راستی‌آزمایی کنند؟
* بدون برق یا دسترسی به اینترنت چه اتفاقی می‌افتد؟
* چه حمایت‌های قانونی‌ای وجود دارد؟

فرض نکنید که هر طرح پیشنهادیِ [ارز دیجیتال بانک مرکزی](https://curriculum.myfirstbitcoin.org/lexicon/en/#cbdc) طراحی یکسانی دارد. از اطلاعات به‌روز، محلی و معتبر استفاده کنید.
