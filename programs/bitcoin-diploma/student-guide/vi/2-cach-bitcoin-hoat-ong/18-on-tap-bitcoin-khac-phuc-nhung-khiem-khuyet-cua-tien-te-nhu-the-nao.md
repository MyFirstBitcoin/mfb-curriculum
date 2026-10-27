# 2.18 Ôn tập: Bitcoin khắc phục những khiếm khuyết của tiền tệ như thế nào?

Quý vị hãy tạm dừng và suy ngẫm xem các quy tắc công khai, việc phát hành hữu hạn, chuyển tiền ngang hàng và tính độc lập trong [xác minh](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification) giải quyết những hạn chế được xác định trong **Mô-đun 1**: nguồn cung thay đổi, sự kiểm soát của các tổ chức, khả năng tiếp cận bị hạn chế và sự phụ thuộc vào lòng tin như thế nào. Vì sao [các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) và [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) có vai trò khác nhau, và vì sao [việc chi tiêu hai lần](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) phải được ngăn chặn? Bitcoin thay thế một phần lòng tin vào các tổ chức bằng [việc xác minh](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification) và trách nhiệm cá nhân; Bitcoin không loại bỏ rủi ro hay [những đánh đổi](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off).


<!-- micrographic: bitcoin-responses-tradeoffs-01 -->
[Một bảng đối chiếu năm điểm yếu có thể có của các hệ thống tiền tệ hiện đại với cách Bitcoin giải quyết và trách nhiệm hoặc sự đánh đổi mới mà mỗi cách giải quyết mang lại. Bitcoin thay thế một phần niềm tin vào các tổ chức bằng việc xác minh và trách nhiệm cá nhân, nhưng không loại bỏ rủi ro.](/micrographics/bitcoin-responses-tradeoffs-01/vi.md)


**Câu hỏi trọng tâm:** Dựa trên những gì quý vị đã học về Bitcoin trong mô-đun này, liệu Bitcoin có [giá trị](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) đối với quý vị không? Liệu [giá](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) hiện tại của bitcoin có phản ánh [giá trị](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) của nó không?

#### Những điểm chính cần ghi nhớ

* Bitcoin được tạo ra để cho phép chuyển tiền kỹ thuật số mà không cần một bên tập trung quản lý [sổ cái](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) đồng thời ngăn chặn [việc chi tiêu hai lần](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending).
* Với tính công khai, [sổ cái](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger), [chữ ký số](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature), [mạng ngang hàng](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network), [bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), cùng tính độc lập trong [xác minh](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification) của Bitcoin phối hợp với nhau để duy trì một bản ghi chung về [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) trong quá khứ.
* Bitcoin có tính phi tập trung theo nghĩa không một bên tham gia riêng lẻ nào có thể đơn phương thay đổi số dư hoặc các quy tắc áp dụng cho tất cả mọi người.
* Người dùng lựa chọn có nắm giữ hoặc chấp nhận bitcoin hay không; [các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) xác minh việc tuân thủ các quy tắc; [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) đề xuất các khối; còn các nhà phát triển có thể đề xuất, nhưng không thể áp đặt, những thay đổi đối với phần mềm.
* Bitcoin có lịch trình cung ứng công khai với mức tối đa là 21 triệu BTC, và [các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) từ chối những khối vi phạm quy tắc này.
* Một bitcoin (1 BTC) được chia thành 100.000.000 [sats](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi), vì vậy mọi người có thể sử dụng các đơn vị nhỏ hơn mà không cần có cả một bitcoin.
* Bitcoin có thể được đánh giá là [đồng tiền lành mạnh](https://curriculum.myfirstbitcoin.org/lexicon/en/#sound-money) dựa trên các thuộc tính tiền tệ, đồng thời vẫn nhìn nhận những [đánh đổi](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off): [biến động giá](https://curriculum.myfirstbitcoin.org/lexicon/en/#volatility), mức độ chấp nhận còn hạn chế, các khoản thanh toán thường khó hoặc không thể đảo ngược, và yêu cầu mỗi cá nhân phải có trách nhiệm cao hơn.

#### Dành một chút thời gian suy ngẫm

Giờ đây, quý vị sẽ giải thích khác đi về phần nào trong thiết kế của Bitcoin, và vì sao?
