# 3.10 Gửi bitcoin

**Thực hành 2: tạm dừng và kiểm tra trước khi gửi**

Việc gửi cần được thực hiện cẩn thận hơn vì trên Bitcoin, một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) hợp lệ thường rất khó hoặc không thể đảo ngược. Trước khi nhấn nút phê duyệt, quý vị có thể giải thích ai sẽ nhận khoản thanh toán và vì sao không?


> **Callout – Dừng lại và xác minh trước khi gửi**
>
> Xác nhận người nhận, phương thức thanh toán, đích đến, số tiền và đơn vị, phí hoặc thời hạn hiệu lực, và màn hình cuối cùng. Nếu có bất kỳ điều gì khác với yêu cầu từ nguồn đáng tin cậy, hoặc có người tạo cảm giác cấp bách hay yêu cầu thông tin khôi phục, hãy dừng lại và xác minh độc lập. Hãy thử gửi một khoản nhỏ khi chưa quen với quy trình.


1. Xác nhận người nhận và mục đích qua một kênh đáng tin cậy.
1. Xác nhận phương thức thanh toán: trên chuỗi hoặc qua Lightning.
1. Quét hoặc nhập đích đến, rồi đối chiếu với màn hình nhận tiền đáng tin cậy.
1. Kiểm tra số tiền, đơn vị, thông tin về phí hoặc thời hạn hiệu lực, và bản tóm tắt cuối cùng.
1. Hãy thử gửi một khoản nhỏ khi chưa quen với quy trình.
1. Chỉ phê duyệt khi mọi mục đều khớp; sau đó kiểm tra kết quả thanh toán.

![Học viên lớn tuổi đưa ra một chiếc điện thoại dùng để thực hành, trong khi người mới học kiểm tra một chiếc điện thoại khác và giảng viên hướng dẫn việc đối chiếu.](https://cdn.sanity.io/images/vje9ehw2/production/8ce88167dc1b3c490b69bd8e045d32add1ce975d-1054x1492.png)


<!-- micrographic: pre-send-checklist-01 -->


Đối với một [khoản thanh toán trên chuỗi](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment), **phí mạng** được trả để đưa [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) vào một khối. Mức phí này phụ thuộc chủ yếu vào dữ liệu [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) và nhu cầu về [không gian khối](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-space), chứ không đơn thuần phụ thuộc vào số tiền được gửi. Mức phí ước tính và thời gian xử lý có thể thay đổi, vì vậy hãy đọc bản tóm tắt cuối cùng thay vì cho rằng một khoản thanh toán có giá trị nhỏ sẽ có phí thấp.

Nếu đích đến thay đổi bất ngờ, yêu cầu trở nên cấp bách, hoặc có người yêu cầu thông tin khôi phục, quý vị nên làm gì? Hãy dừng lại. Xác minh yêu cầu một cách độc lập, hoặc nhờ trợ giúp mà không chia sẻ thông tin bí mật.

![Giảng viên hướng dẫn người mới học đối chiếu điện thoại với thiết bị nhận tiền của chủ cơ sở kinh doanh trước khi phê duyệt một khoản thanh toán.](https://cdn.sanity.io/images/vje9ehw2/production/2a3f35ea865512968fcaeb22e3c6fd06985394c5-1055x1491.png)
