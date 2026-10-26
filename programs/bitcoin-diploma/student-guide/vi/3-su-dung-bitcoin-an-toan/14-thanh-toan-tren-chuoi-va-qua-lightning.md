# 3.14 Thanh toán trên chuỗi và qua Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Thanh toán trên chuỗi và qua Lightning**
>
> [Các khoản thanh toán trên chuỗi](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) được ghi lại trên Bitcoin thông qua [chuỗi khối](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) và nhận được [các xác nhận](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning là một mạng thanh toán được xây dựng trên Bitcoin, có thể hỗ trợ các khoản thanh toán nhanh và thường xuyên. Một khoản thanh toán qua Lightning có thể hoàn tất nhanh chóng hoặc thất bại, và ví dùng để thanh toán vẫn có thể là ví lưu ký hoặc ví tự lưu ký.



> **Dark – Phương thức thanh toán không quyết định quyền lưu ký**
>
> Thanh toán trên chuỗi và qua Lightning có những [đánh đổi](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) khác nhau. Ví Lightning có thể là ví lưu ký hoặc ví tự lưu ký, và việc một khoản thanh toán thành công nhanh chóng không chứng minh rằng dịch vụ đó phù hợp để giữ số dư lớn hơn hoặc phù hợp với mọi tình huống.



<!-- micrographic: onchain-lightning-table-01 -->


Người nhận muốn nhận thanh toán theo phương thức nào? Trước khi thanh toán, hãy xác nhận xem họ đã cung cấp địa chỉ trên chuỗi hay [hóa đơn Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) hoặc yêu cầu thanh toán qua Lightning. Ví trên chuỗi không thể trực tiếp thanh toán mọi [hóa đơn Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), và ví Lightning có thể không hỗ trợ mọi thao tác trên chuỗi. Một số ứng dụng hỗ trợ cả hai phương thức nhưng có thể tính thêm phí hoặc làm phát sinh sự phụ thuộc vào dịch vụ. Nội dung chi tiết về thiết lập Lightning, các kênh, định tuyến và [tính thanh khoản](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) thuộc phần [Học tập nâng cao](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); hoạt động thực hành trực tiếp tại địa phương nằm trong **Mô-đun 4** khi bảo đảm an toàn và phù hợp.

Hãy tưởng tượng một tình huống được chuẩn bị sẵn cho phép thanh toán theo cả hai phương thức. Ví dự định sử dụng có thể xử lý yêu cầu nào, và quý vị sẽ kiểm tra điều gì trước khi phê duyệt thanh toán? Câu trả lời phụ thuộc vào yêu cầu nhận thanh toán, ví và tình huống — chứ không phụ thuộc vào một phương thức “tốt nhất” cho mọi trường hợp.

![Giảng viên chỉ vào hai lộ trình thanh toán có dạng hình học khác nhau trên bảng, trong khi người mới học và người học có kiến thức kỹ thuật cùng xem xét.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
