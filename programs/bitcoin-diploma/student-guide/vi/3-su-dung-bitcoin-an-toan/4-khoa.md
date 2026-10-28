# 3.4 Khóa

Quyền sở hữu Bitcoin được bảo đảm bằng các khóa mật mã.


<!-- card: definition -->
> **Definition – Khóa riêng tư**
>
> Một [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) là thông tin bí mật cho phép ví tạo ra các [chữ ký số](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) hợp lệ. Chữ ký cho phép chi tiêu bitcoin do khóa tương ứng kiểm soát. Bất kỳ ai có được [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) thường đều có thể chi tiêu số tiền đó.


Một [**khóa công khai**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) được suy ra bằng toán học từ [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Khóa này giúp xác minh chữ ký mà không tiết lộ [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Các địa chỉ được tạo từ [khóa công khai](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) thông qua thông tin của khóa đó.

Quy tắc cốt lõi rất đơn giản:

**Thông tin công khai dùng để nhận tiền có thể được chia sẻ. Thông tin riêng tư dùng để chi tiêu phải được giữ bí mật.**

Một [chữ ký số](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) chứng minh rằng [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) cần thiết đã cho phép thực hiện một [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Chữ ký số không đưa [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) vào trong [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) xác minh chữ ký trước khi chấp nhận việc chi tiêu.

Hầu hết các ví dành cho người mới bắt đầu đều sử dụng [chữ ký đơn](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): một khóa riêng tư cho phép thực hiện một giao dịch. Các ví hiện đại tự động quản lý nhiều khóa. Người mới bắt đầu không nên sao chép hoặc thao tác với từng [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ở dạng chuỗi. Hãy bảo vệ bản sao lưu được ví chấp thuận và làm theo quy trình khôi phục của ví.

Không một nhà giáo dục, công ty cung cấp ví, nhân viên sàn giao dịch, nhân viên hỗ trợ kỹ thuật hay nhà phát triển Bitcoin chân chính nào cần biết [khóa riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) hoặc [cụm từ khôi phục](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase) của quý vị. Bất kỳ ai yêu cầu thông tin này đều nên được xem là một mối đe dọa.


<!-- card: light -->
> **Hãy thử:** Phân loại các ví dụ đã chuẩn bị thành ba nhóm: thông tin có thể chia sẻ an toàn để nhận tiền, thông tin bí mật dùng để chi tiêu và thông tin có thể công khai nhưng vẫn nên được giữ kín khi gắn với một cá nhân.



<!-- micrographic: private-key-public-info-01 -->
[Một khóa riêng tư bí mật, tuyệt đối không được chia sẻ, được dùng để tạo ra thông tin công khai có thể chia sẻ: một khóa công khai được suy ra từ khóa riêng tư đó và một địa chỉ nhận được tạo từ khóa công khai. Chính khóa riêng tư đó tạo ra các chữ ký mà các nút xác minh được mà không bao giờ biết khóa riêng tư.](/micrographics/private-key-public-info-01/vi.md)
