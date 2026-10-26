# 2.3 Những nỗ lực ban đầu về tiền kỹ thuật số và vấn đề chi tiêu hai lần

Bitcoin không phải là nỗ lực đầu tiên nhằm tạo ra tiền kỹ thuật số. Bitcoin được xây dựng dựa trên bốn thập kỷ thử nghiệm, kế thừa những ý tưởng từ nhiều dự án trước đó đã góp phần định hình thiết kế thành công của nó.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) sử dụng [mật mã học](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) để hỗ trợ các khoản thanh toán kỹ thuật số có tính riêng tư. Hệ thống này phụ thuộc vào một công ty trung tâm và các mối quan hệ với ngân hàng. Khi công ty thất bại, hệ thống không thể tiếp tục hoạt động như một mạng lưới tiền tệ độc lập.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) sử dụng [bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) để khiến việc gửi thư điện tử không mong muốn trở nên tốn kém. Máy tính của người gửi phải thực hiện công việc tính toán trước khi gửi thư. Ý tưởng này cho thấy chi phí tính toán có thể hạn chế hành vi lạm dụng như thế nào.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) mô tả một hệ thống được đề xuất, trong đó công việc tính toán có thể tạo ra các bản ghi kỹ thuật số khan hiếm. Hệ thống này chưa được triển khai thành một hệ thống tiền tệ phi tập trung hoàn chỉnh, nhưng đã phát triển những ý tưởng quan trọng về [tính khan hiếm kỹ thuật số](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) và bằng chứng.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) và [**bằng chứng công việc có thể tái sử dụng (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) khám phá những cách để người tham gia tạo ra hoặc chuyển giao [giá trị kỹ thuật số khan hiếm](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) mà không chỉ dựa vào một cơ sở dữ liệu trung tâm duy nhất. Các hệ thống này chưa hoàn thiện, nhưng đã giúp làm rõ những gì một hệ thống hoạt động được sẽ cần có.
* Mặc dù [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) không phải là tiền, hệ thống này cho thấy một [mạng ngang hàng](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) có thể cho phép nhiều máy tính độc lập chia sẻ thông tin mà không cần một máy chủ trung tâm kiểm soát toàn bộ hệ thống.

Nhìn chung, những thử nghiệm này đã cho thấy các mảnh ghép hữu ích của bài toán. Chúng cũng làm rõ vấn đề còn tồn tại.


> **Definition – Chi tiêu hai lần**
>
> [Chi tiêu hai lần](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) là hành vi cố gắng gửi cùng một đơn vị kỹ thuật số cho hai người nhận. Dữ liệu kỹ thuật số có thể được sao chép hoàn hảo, vì vậy một hệ thống tiền kỹ thuật số cần có cách xác định [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) nào là hợp lệ.


[Các hệ thống tập trung](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) ngăn chặn điều này bằng cách để một cơ sở dữ liệu đáng tin cậy quyết định khoản thanh toán nào diễn ra trước. Vào ngày 31 tháng 10 năm 2008, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto), trong sách trắng [_Bitcoin: Một hệ thống tiền mặt điện tử ngang hàng_](https://bitcoin.org/bitcoin.pdf), đã giải thích một cách tiếp cận khác: một hệ thống công khai có thể thiết lập lịch sử thanh toán chung mà không cần ngân hàng, công ty hay cơ quan trung ương nào khác.

Sách trắng đã tập hợp các tính năng cần thiết cho cách tiếp cận đó:

1. **Một [mạng ngang hàng](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [các giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) được thông báo trực tiếp đến một mạng lưới những người tham gia.
1. **[Chữ ký số](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** một [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) là thông tin bí mật dùng để tạo chữ ký nhằm cho phép chi tiêu; chỉ người nắm giữ khóa đó mới có thể làm việc này.
1. **Các khối và [hoạt động khai thác](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) tập hợp các [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) thành các khối và sử dụng [bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) để cạnh tranh giành quyền thêm khối tiếp theo.
1. **Sự độc lập trong [xác minh](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kiểm tra các [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) và khối theo các quy tắc của Bitcoin.
1. **Lịch sử chung có tích lũy [bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** những người tham gia công nhận [chuỗi hợp lệ](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) gồm các [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) có lượng [công việc tích lũy](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) lớn nhất là bản ghi chung.


<!-- micrographic: five-part-response-01 -->


Học phần này giải thích chi tiết hơn về các khái niệm này. Khi kết hợp lại, chúng đã mang đến một giải pháp thiết thực cho [vấn đề chi tiêu hai lần](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): mạng lưới có thể từ chối lần chi tiêu thứ hai đối với cùng một lượng bitcoin mà không cần dựa vào một cơ quan trung ương. Bitcoin đã mang đến sự kết hợp còn thiếu mà các thử nghiệm về tiền kỹ thuật số đã tìm kiếm suốt nhiều thập kỷ.

![](https://cdn.sanity.io/images/vje9ehw2/staging/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
