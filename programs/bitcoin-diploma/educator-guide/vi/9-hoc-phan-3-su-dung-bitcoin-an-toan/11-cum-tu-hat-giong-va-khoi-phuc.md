# 9.11 Cụm từ hạt giống và khôi phục

Một [cụm từ hạt giống](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase), còn được gọi là [cụm từ khôi phục](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase), là một phương thức khôi phục được nhiều ví sử dụng. Đây là một danh sách các từ theo thứ tự, có thể tái tạo các khóa cho những thiết kế ví tương thích. Không phải ví nào cũng có tính năng này, và cụm từ này có quyền năng lớn hơn mật khẩu tài khoản thông thường.

Hãy giảng giải các hệ quả:

* các từ chính xác theo đúng thứ tự có thể khôi phục quyền kiểm soát
* bất kỳ ai có được cụm từ này đều có thể giành quyền kiểm soát
* việc làm mất cụm từ có thể khiến không còn cách khôi phục
* [khả năng tương thích của ví](https://curriculum.myfirstbitcoin.org/lexicon/en/#wallet-compatibility) rất quan trọng; và
* cụm từ hạt giống có khả năng đã bị lộ phải được coi là không còn an toàn.


<!-- micrographic: seed-phrase-on-paper-01 -->
[Cụm từ khôi phục là một danh sách các từ theo thứ tự, ở đây là mười hai từ mẫu được đánh số và viết trên giấy. Các từ chính xác theo đúng thứ tự có thể khôi phục quyền kiểm soát trong một ví tương thích, vì vậy cụm từ này cần được giữ bí mật và lưu trữ ngoại tuyến.](/micrographics/seed-phrase-on-paper-01/vi.md)


![](https://cdn.sanity.io/images/vje9ehw2/production/d437a5edfbe870f7dba8fd565d33ea6a3622a90d-1536x1024.svg)

#### Tuyệt đối không làm những việc sau trong lớp

* Không yêu cầu học viên đọc to các từ khôi phục.
* Không đi quanh lớp khi học viên đang ghi lại các từ khôi phục thật.
* Không để học viên chụp ảnh, gửi qua tin nhắn, gửi email, in, lưu trên đám mây hoặc nộp cụm từ khôi phục.
* Không dùng ví thật có tiền của một học viên để trình diễn việc khôi phục trước mọi người.
* Không nhập cụm từ khôi phục của [ví phần cứng](https://curriculum.myfirstbitcoin.org/lexicon/en/#hardware-wallet) vào một trang web hoặc biểu mẫu thông thường trên máy tính.
* Không giữ lại những cụm từ thực hành mà sau này được dùng để bảo vệ tiền của học viên.

#### Hoạt động: mô phỏng mức độ sẵn sàng khôi phục

**Trình bày:** Trình diễn toàn bộ quy trình kiểm tra khôi phục bằng các từ khôi phục đã chuẩn bị sẵn hoặc một ví thực hành trống chỉ dùng tạm. Các từ này có thể khôi phục ví thực hành trống đó, nhưng không được dùng để bảo vệ ví cá nhân hoặc ví có tiền. Giải thích về khả năng tương thích, [quyền riêng tư](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy), kết quả mong đợi và việc đặt lại.

**Thực hành:** Học viên sắp xếp các thẻ đã chuẩn bị sẵn theo thứ tự hoặc khôi phục một ví thực hành chỉ dùng tạm trong môi trường riêng tư, có kiểm soát. Họ phải giữ tài liệu ngoài tầm nhìn của người khác và nhận diện các yêu cầu không an toàn.

**Vận dụng:** Học viên giải thích hoặc trình diễn cách:

1. sử dụng hướng dẫn chính thức dành cho đúng ví đang dùng.
1. xác nhận khả năng tương thích khi khôi phục.
1. thực hiện riêng tư, không có máy ảnh, camera hoặc người quan sát.
1. sử dụng phương thức kiểm tra bản sao lưu hoặc khôi phục đáng tin cậy.
1. xác minh thông tin nhận tiền hoặc lịch sử thực hành đúng như mong đợi.
1. xóa dữ liệu trên thiết bị dùng tạm; và
1. trả lại tài liệu giả lập một cách an toàn hoặc tiêu hủy theo hướng dẫn.


<!-- micrographic: recovery-practice-lanes-01 -->
[Người học thực hiện các bước thực hành khôi phục trong một khu vực riêng tư, kiểm tra kết quả mong đợi, xóa dữ liệu trên thiết bị và trả lại hoặc tiêu hủy tài liệu giả định. Giáo viên quan sát các quyết định và cách xử lý an toàn nhưng tuyệt đối không nhìn thấy các từ khôi phục bí mật.](/micrographics/recovery-practice-lanes-01/vi.md)



<!-- card: callout -->
> **Coi cụm từ hạt giống đã bị lộ là không còn an toàn**
>
> Nếu cụm từ hạt giống thật có khả năng đã bị lộ, hãy ngừng coi đó là bản sao lưu an toàn, tạo một ví mới đáng tin cậy với thông tin khôi phục mới và chuyển tiền sau khi xác minh kỹ địa chỉ đích. Học viên nên tìm kiếm sự trợ giúp mà không tiết lộ bất kỳ cụm từ nào trong hai cụm từ.


Việc thừa kế, [đa chữ ký](https://curriculum.myfirstbitcoin.org/lexicon/en/#multisignature) trong thiết kế ví, các cụm mật khẩu nâng cao và việc lập kế hoạch khôi phục tài sản giá trị lớn có thể đòi hỏi biện pháp bảo mật nâng cao và tư vấn pháp lý chuyên nghiệp. Những nội dung này nằm ngoài yêu cầu thực hành bắt buộc của Bitcoin Diploma.

![Giảng viên hướng dẫn cuộc thảo luận về mức độ sẵn sàng khôi phục trong khi học viên lớn tuổi đặt một thẻ thực hành trống vào phong bì, còn học viên am hiểu kỹ thuật quan sát.](https://cdn.sanity.io/images/vje9ehw2/production/23cdb205174fa99b2d0df47ef606b53f8329f152-1054x1492.png)
