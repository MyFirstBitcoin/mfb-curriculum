# 1.8 Ngân hàng dự trữ một phần

Khi quý vị gửi tiền mặt vào ngân hàng, ngân hàng ghi nhận một [khoản nợ phải trả](https://curriculum.myfirstbitcoin.org/lexicon/en/#liability) cho quý vị: ngân hàng nợ quý vị số dư tài khoản. Ngân hàng thường không giữ toàn bộ số tiền của mọi khoản tiền gửi dưới dạng tiền mặt. Thay vào đó, ngân hàng duy trì [dự trữ thanh khoản](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity)—tiền mặt hoặc [tài sản](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) có thể nhanh chóng dùng để thanh toán—và sử dụng bảng cân đối kế toán của mình để cho vay và thực hiện các khoản đầu tư khác.

Khi một ngân hàng thương mại phê duyệt khoản vay, ngân hàng thường tạo ra một khoản tiền gửi mới trong tài khoản của người vay. Điều này làm tăng lượng tiền trong ngân hàng dưới dạng [tiền gửi](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-deposit). Khi nợ gốc được hoàn trả, lượng [tiền gửi](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-deposit) đó giảm đi. Ngân hàng chịu sự ràng buộc bởi [vốn](https://curriculum.myfirstbitcoin.org/lexicon/en/#capital) theo quy định, [thanh khoản](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity) cần thiết, [rủi ro tín dụng](https://curriculum.myfirstbitcoin.org/lexicon/en/#credit-risk), các quy định pháp lý, chi phí huy động vốn và nhu cầu từ [những người vay đủ điều kiện](https://curriculum.myfirstbitcoin.org/lexicon/en/#qualified-borrower).


<!-- micrographic: bank-loan-deposit-01 -->
[Quy trình cho vay ngân hàng được đơn giản hóa: người vay đăng ký vay, ngân hàng phê duyệt khoản vay và ghi có một khoản tiền gửi mới vào tài khoản của người vay, sau đó người vay hoàn trả cho ngân hàng cả tiền gốc lẫn tiền lãi.](/micrographics/bank-loan-deposit-01/vi.md)


Các ngân hàng thường tìm kiếm [lợi nhuận](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-profit) bằng cách thu lãi và phí từ các khoản cho vay và đầu tư, đồng thời chi trả chi phí hoạt động, huy động vốn và tuân thủ quy định, cũng như gánh chịu tổn thất khi người vay không hoàn trả. Những hoạt động và ràng buộc này khác nhau tùy theo ngân hàng và khu vực pháp lý.


<!-- card: definition -->
> **Definition – Ngân hàng dự trữ một phần**
>
> [Ngân hàng dự trữ một phần](https://curriculum.myfirstbitcoin.org/lexicon/en/#fractional-reserve-banking) mô tả hình thức hoạt động ngân hàng trong đó các ngân hàng chỉ giữ một phần nghĩa vụ tiền gửi dưới dạng dự trữ có thể sử dụng ngay, đồng thời cho vay và nắm giữ các [tài sản](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) khác. Mức dự trữ bắt buộc và các giới hạn khác khác nhau giữa các quốc gia và có thể thay đổi theo thời gian.


Điều này tạo ra hai rủi ro quan trọng:

* **[Rủi ro thanh khoản](https://curriculum.myfirstbitcoin.org/lexicon/en/#liquidity-risk):** Một ngân hàng có thể nắm giữ các khoản cho vay dài hạn được kỳ vọng sẽ được hoàn trả nhưng vẫn không có đủ tiền mặt hoặc [tài sản](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) có thể sử dụng nhanh chóng để đáp ứng nhiều yêu cầu rút tiền ngay hôm nay.
* **[Rủi ro mất khả năng thanh toán](https://curriculum.myfirstbitcoin.org/lexicon/en/#solvency-risk):** Các khoản cho vay không được hoàn trả hoặc tình trạng [tài sản](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) [mất giá](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) có thể khiến tổng [tài sản](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) của ngân hàng có giá trị thấp hơn số nợ phải trả. Trong trường hợp đó, ngân hàng không thể thực hiện đầy đủ các nghĩa vụ của mình ngay cả khi có thời gian để bán [tài sản](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset).


<!-- micrographic: liquidity-vs-solvency-01 -->
[Rủi ro thanh khoản: nhiều người gửi tiền xếp hàng rút tiền hôm nay, và ngân hàng hiện không có đủ tiền mặt dù các khoản cho vay của ngân hàng có thể được hoàn trả sau này. Rủi ro mất khả năng thanh toán: người vay không trả được nợ vay mua nhà, và giá trị tài sản của ngân hàng trở nên thấp hơn số tiền ngân hàng đang nợ.](/micrographics/liquidity-vs-solvency-01/vi.md)


![](https://cdn.sanity.io/images/vje9ehw2/production/f5f7999af936541b5928421cac58b3e5c7abd428-1536x1024.svg)



Một [**đợt rút tiền hàng loạt**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bank-run) xảy ra khi nhiều người gửi tiền cố gắng rút tiền hoặc số dư tài khoản của họ cùng lúc vì lo ngại ngân hàng có thể phá sản. [Bảo hiểm tiền gửi](https://curriculum.myfirstbitcoin.org/lexicon/en/#deposit-insurance) và việc [ngân hàng trung ương](https://curriculum.myfirstbitcoin.org/lexicon/en/#central-bank) cho vay có thể làm giảm sự hoảng loạn, nhưng điều kiện được bảo hiểm và hạn mức bảo hiểm khác nhau tùy theo khu vực pháp lý. Những biện pháp bảo vệ này phụ thuộc vào các tổ chức và quy định, đồng thời có thể chuyển một phần tổn thất hoặc rủi ro từ một ngân hàng riêng lẻ sang toàn hệ thống.

Các quy định và hoạt động giám sát có thể giảm rủi ro, nhưng không thể ngăn chặn mọi trường hợp gian lận, quản lý yếu kém, lạm dụng quyền lực chính trị hoặc sai sót đơn thuần. Những vấn đề này là các khả năng cần được đánh giá, chứ không phải kết cục của mọi hệ thống ngân hàng.

Bài học cốt lõi không phải là mọi ngân hàng đều sắp phá sản. Mà là số dư tài khoản ngân hàng chính là lời hứa của ngân hàng sẽ thanh toán cho quý vị. Điều này không giống với việc nắm giữ [tài sản thanh toán](https://curriculum.myfirstbitcoin.org/lexicon/en/#asset) một cách trực tiếp.
