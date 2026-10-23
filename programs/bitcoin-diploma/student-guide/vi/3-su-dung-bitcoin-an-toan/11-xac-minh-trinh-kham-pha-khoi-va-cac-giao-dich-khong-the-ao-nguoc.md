# 3.11 Xác minh, trình khám phá khối và các giao dịch không thể đảo ngược

> **Definition – Mã giao dịch và trình khám phá khối**
>
> Một [mã giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) dùng để định danh trên chuỗi một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Một [trình khám phá khối](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) hiển thị dữ liệu Bitcoin công khai, chẳng hạn như thông tin về một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction): trạng thái và số lượt [xác nhận](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Đây là một công cụ tra cứu hữu ích, không phải cơ quan có thẩm quyền đối với Bitcoin và cũng không phải bằng chứng về danh tính hay sự trung thực của người nhận.


Thông tin công khai này có thể và không thể cho biết những gì? Nó có thể cho biết thông tin về một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction): trạng thái, địa chỉ đích, số tiền, phí và số lượt [xác nhận](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation); nó không thể chứng minh lý do một khoản thanh toán được thực hiện hay một người có đáng tin cậy hay không. Trên chuỗi, một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) vẫn chưa được xác nhận sau khi được [phát đi](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) và nhận được [lượt xác nhận đầu tiên](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) khi được đưa vào một khối hợp lệ. Các khối tiếp theo củng cố độ tin cậy về vị trí của giao dịch trong bản ghi, nhưng không thể khắc phục việc gửi sai địa chỉ đích hay một vụ lừa đảo. Không có số lượt [xác nhận](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) chung cho mọi khoản thanh toán; cách kiểm tra phù hợp phụ thuộc vào số tiền và mức độ rủi ro.

Để kiểm tra một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) đã được chuẩn bị sẵn, hãy lấy [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) của giao dịch đó, mở một trình khám phá đáng tin cậy dành cho [mạng Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) dự định sử dụng, rồi kiểm tra trạng thái, địa chỉ đích, số tiền, phí và số lượt [xác nhận](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Trình khám phá chỉ là một giao diện. Việc tìm kiếm một địa chỉ hoặc [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) có thể tiết lộ cho bên vận hành dịch vụ rằng thiết bị của quý vị đang quan tâm đến thông tin đó. Để thực hành, hãy sử dụng một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) do giảng viên chuẩn bị sẵn hoặc bản in ảnh chụp màn hình. Không tìm kiếm địa chỉ cá nhân hoặc [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) cá nhân của học viên trên dịch vụ công khai. Nếu sau này quý vị tra cứu một khoản thanh toán cá nhân, hãy tìm hiểu những [quyền riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) và yếu tố bảo mật phải [đánh đổi](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) khi sử dụng kết nối của mình trước khi dùng dịch vụ công khai.


> **Callout – Dữ liệu công khai không phải là bằng chứng về danh tính hay sự trung thực**
>
> Một [trình khám phá khối](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) có thể hiển thị dữ liệu [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) công khai, nhưng không thể chứng minh ai kiểm soát một địa chỉ, vì sao một khoản thanh toán được thực hiện, hay liệu người nhận có đáng tin cậy hay không. Hãy sử dụng các ví dụ đã chuẩn bị sẵn để thực hành và bảo vệ [quyền riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) khi tra cứu trên các dịch vụ công khai.



<!-- micrographic: confirmation-timeline-01 -->


![Giáo viên và học viên lớn tuổi thảo luận về một ví dụ đã chuẩn bị sẵn trên màn hình hướng về phía nhóm, trong khi học viên am hiểu kỹ thuật thao tác chuột; người xem nhìn thấy mặt sau của màn hình.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
