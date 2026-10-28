# 4.5 Thanh toán qua Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Người nhận tạo yêu cầu thanh toán Lightning kèm số tiền trên điện thoại của mình, người gửi quét yêu cầu và thanh toán, rồi khoản thanh toán đến điện thoại của người nhận sau giây lát.](/micrographics/lightning-phone-payment-01/vi.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[Thanh toán Lightning qua sáu bước: người nhận tạo yêu cầu, người gửi quét yêu cầu, kiểm tra người nhận, số tiền, đơn vị, thời hạn hiệu lực và phí, rồi phê duyệt; khoản thanh toán được định tuyến và cả hai ví đều hiển thị kết quả. Mỗi ví có thể là ví lưu ký hoặc ví tự lưu ký; nếu thanh toán thất bại hoặc hết hạn, quy trình sẽ bắt đầu lại bằng một yêu cầu mới.](/micrographics/lightning-payment-sequence-01/vi.md)


Lightning có thể giúp các khoản thanh toán Bitcoin nhỏ, nhanh chóng trở nên thiết thực. Lightning có thể phù hợp cho quầy thanh toán của cửa hàng, các khoản thanh toán thường xuyên tại địa phương, dịch vụ trực tuyến hoặc các khoản chuyển tiền mà phí trên chuỗi sẽ quá cao so với số tiền thanh toán.

Một buổi minh họa Lightning tại địa phương cần làm rõ:

* ví là ví lưu ký hay ví tự lưu ký
* cách nạp tiền vào ví
* việc nạp tiền có yêu cầu thực hiện trên chuỗi một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) hay sử dụng một dịch vụ
* biện pháp sao lưu hoặc khôi phục nào bảo vệ số dư
* loại yêu cầu thanh toán nào đang được sử dụng
* những khoản phí hoặc giới hạn nào được áp dụng
* điều gì xảy ra khi thanh toán thất bại
* cách người nhận xác nhận thanh toán

Một [**hóa đơn Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) là một yêu cầu thanh toán được tạo cho một khoản thanh toán cụ thể. Hóa đơn có thể bao gồm số tiền, thông tin đích đến và thời điểm hết hạn. Quý vị hãy đọc phần [xác nhận](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) trên màn hình của ví trước khi thanh toán.

Một [**địa chỉ Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) là một mã định danh dễ đọc được một số dịch vụ hỗ trợ. Địa chỉ này có thể trông giống địa chỉ email, nhưng đây là một tiện ích định tuyến thanh toán, không phải tài khoản email. Địa chỉ này phụ thuộc vào nhà cung cấp hoặc tên miền hỗ trợ nó.

Đối với một lần thanh toán có hướng dẫn:

1. Người nhận tạo yêu cầu phù hợp.
1. Người gửi quét hoặc sao chép yêu cầu đó.
1. Người gửi kiểm tra người nhận, số tiền, đơn vị và phí.
1. Người gửi chỉ phê duyệt sau khi các thông tin chi tiết đã chính xác.
1. Cả hai bên xác nhận kết quả trong ví của mình.
1. Nhóm giải thích các rủi ro về [lưu ký](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) và thanh toán thất bại.

Quý vị đừng cho rằng một khoản thanh toán Lightning thành công chứng tỏ ví an toàn để giữ số dư lớn hơn. Sự tiện lợi khi thanh toán và việc [lưu ký](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) an toàn là hai vấn đề riêng biệt.
