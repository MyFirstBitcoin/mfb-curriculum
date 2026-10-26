# 2.10 Bằng chứng công việc

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Bằng chứng công việc**
>
> [Bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) là quy trình [các thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) sử dụng để cạnh tranh giành quyền đề xuất khối tiếp theo.


Một [hàm băm](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) biến dữ liệu thành một kết quả có độ dài cố định. Một thay đổi nhỏ ở dữ liệu đầu vào tạo ra một kết quả mới không thể đoán trước. Một [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) thay đổi một phần dữ liệu nhỏ trong khối được đề xuất và băm khối đó nhiều lần. Một kết quả chỉ hợp lệ khi giá trị số của nó thấp hơn [mục tiêu](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) của mạng, một ngưỡng do các quy tắc quy định; mức thấp hơn của [mục tiêu](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) đồng nghĩa với việc có ít [kết quả hợp lệ](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) hơn và cần nhiều lần thử hơn. Không có lối tắt, nên [các thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) có thể phải thử rất nhiều lần.

Khi một [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) tìm được một [kết quả hợp lệ](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), thợ đào đó [phát tán](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) khối đó. [Các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) có thể kiểm tra bằng chứng nhanh chóng, dù việc tìm ra bằng chứng đó đòi hỏi lượng tính toán và năng lượng đáng kể. Nếu khối chứa một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), thì [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) đó nhận được [lần xác nhận đầu tiên](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): bản ghi của giao dịch đã được đưa vào một khối hợp lệ. Mỗi khối hợp lệ được thêm vào sau khối đó sẽ bổ sung một [lần xác nhận](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), khiến [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) có vị trí trong [chuỗi khối](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) mà việc viết lại trở nên tốn kém hơn. Sự khác biệt này rất quan trọng: công việc tốn kém để thực hiện nhưng dễ xác minh.


<!-- micrographic: proof-of-work-process-01 -->


[Bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) phục vụ một số mục đích:

* nó giúp những người độc lập làm [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) có cách cạnh tranh mà không cần một bộ điều phối trung tâm
* nó khiến thứ tự của các [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) trở nên tốn kém để viết lại
* nó gắn bảo mật mạng với thiết bị và năng lượng trong thế giới thực
* nó hỗ trợ một phương pháp công khai để lựa chọn giữa các lịch sử hợp lệ cạnh tranh nhau: chuỗi có nhiều [công việc tích lũy](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) nhất

[Hoạt động khai thác](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) không giải các phương trình hữu ích để phục vụ một mục đích bên ngoài. Mục đích của hoạt động này là bảo đảm rằng Bitcoin duy trì đúng thứ tự các [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Mạng lưới điều chỉnh ngưỡng mục tiêu theo định kỳ: khi các khối được tạo ra quá nhanh, mạng lưới hạ ngưỡng mục tiêu xuống, còn khi các khối được tạo ra quá chậm, mạng lưới nâng ngưỡng mục tiêu lên, nhằm duy trì tốc độ trung bình khoảng một khối mỗi mười phút khi năng lực tính toán thay đổi.

[Bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) đòi hỏi chi phí năng lượng thực tế. Những người ủng hộ cho rằng chính chi phí này là nền tảng bảo đảm tính bảo mật của Bitcoin và có thể tạo ra nhu cầu đối với các nguồn năng lượng có thể cung ứng linh hoạt hoặc vốn sẽ không được sử dụng. Những người chỉ trích đặt câu hỏi về lượng năng lượng được sử dụng và nguồn gốc của năng lượng đó. Một đánh giá có trách nhiệm cần xem xét loại năng lượng nào được sử dụng, năng lượng đó đến từ đâu, mang lại mức độ bảo mật nào và đang được so sánh với những phương án thay thế nào.

![Giảng viên, học viên mới bắt đầu và học viên chuyên về kỹ thuật thảo luận về một thiết bị khai thác để bàn có quạt và bộ nguồn riêng.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
