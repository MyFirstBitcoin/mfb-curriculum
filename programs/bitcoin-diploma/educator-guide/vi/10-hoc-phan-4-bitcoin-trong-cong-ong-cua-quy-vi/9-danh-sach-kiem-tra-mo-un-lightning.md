# 10.9 Danh sách kiểm tra mô-đun Lightning

Trước buổi thực hành về Lightning, hãy xác minh và giải thích:

* ví là ví lưu ký hay ví tự lưu ký
* cách nạp tiền vào ví
* việc nạp hoặc rút tiền có sử dụng giao dịch trên chuỗi hay dịch vụ nào không
* cách khôi phục và duy trì hoạt động nếu nhà cung cấp hoặc thiết bị gặp sự cố
* yêu cầu là hóa đơn, có hỗ trợ [địa chỉ Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address), hay thuộc loại khác
* số tiền, đơn vị, người nhận, thời hạn, phí, hạn mức và [tính thanh khoản](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) cần cân nhắc
* cách nhận biết trạng thái thành công, đang chờ xử lý, hết hạn hoặc thất bại
* cách cả hai bên xác nhận kết quả một cách độc lập; và
* hoạt động mô phỏng ngoại tuyến.


<!-- card: dark -->
> **Một lần thanh toán Lightning thành công chỉ chứng minh rằng tuyến thanh toán này đã hoạt động một lần**
>
> Điều đó không chứng minh rằng ví an toàn để giữ số dư lớn hơn hoặc cùng tuyến thanh toán đó sẽ hoạt động ở mọi nơi.



<!-- micrographic: lightning-payment-sequence-01 -->
[Thanh toán Lightning qua sáu bước: người nhận tạo yêu cầu, người gửi quét yêu cầu, kiểm tra người nhận, số tiền, đơn vị, thời hạn hiệu lực và phí, rồi phê duyệt; khoản thanh toán được định tuyến và cả hai ví đều hiển thị kết quả. Mỗi ví có thể là ví lưu ký hoặc ví tự lưu ký; nếu thanh toán thất bại hoặc hết hạn, quy trình sẽ bắt đầu lại bằng một yêu cầu mới.](/micrographics/lightning-payment-sequence-01/vi.md)
