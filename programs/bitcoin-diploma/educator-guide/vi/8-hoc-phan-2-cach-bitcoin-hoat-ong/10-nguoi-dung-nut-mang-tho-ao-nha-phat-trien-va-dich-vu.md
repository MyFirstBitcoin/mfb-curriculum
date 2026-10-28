# 8.10 Người dùng, nút mạng, thợ đào, nhà phát triển và dịch vụ

Hãy sử dụng chính xác các giới hạn vai trò sau đây dành cho người mới bắt đầu:


| Vai trò | Chức năng chính dành cho người mới bắt đầu | Không có nghĩa là |
| --- | --- | --- |
| Người dùng | Lựa chọn nhận, nắm giữ, gửi, xác minh và chấp nhận bitcoin, trực tiếp hoặc thông qua các dịch vụ | Tự động vận hành mọi bộ phận của mạng |
| Nút | Kiểm tra độc lập các giao dịch và khối theo các quy tắc của mình, đồng thời chuyển tiếp dữ liệu hợp lệ | Tạo khối mới hoặc áp đặt quy tắc cho mọi người |
| Thợ đào | Xây dựng các khối ứng viên và thực hiện bằng chứng công việc để đề xuất thứ tự của chúng | Có thể khiến việc phát hành hoặc các giao dịch không hợp lệ trở nên hợp lệ đối với các nút trung thực |
| Nhà phát triển | Rà soát, viết và đề xuất phần mềm | Có thể buộc những người tham gia chấp nhận thay đổi quy tắc |
| Dịch vụ Bitcoin | Cung cấp ví, sàn giao dịch, trình khám phá, giao diện thanh toán hoặc giao diện khác | Chính là giao thức Bitcoin |



<!-- micrographic: bitcoin-participant-roles-01 -->
[Bốn vai trò trong Bitcoin: người dùng nhận, nắm giữ và gửi bitcoin, các nút độc lập xác minh việc tuân thủ các quy tắc, thợ đào xây dựng các khối ứng viên bằng bằng chứng công việc, và nhà phát triển đề xuất phần mềm. Không một vai trò riêng lẻ nào kiểm soát mạng lưới.](/micrographics/bitcoin-participant-roles-01/vi.md)


#### Hoạt động: khối không hợp lệ

Hãy đưa cho một học viên đóng vai [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) một [khối ứng viên](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) tạo ra khoản trợ cấp vượt mức mà thẻ quy tắc của [nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) cho phép. Các học viên đóng vai [nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kiểm tra và từ chối khối đó.

Thảo luận sau hoạt động:

* Người [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) đã thực sự thực hiện công việc nhưng vẫn không được phép phá vỡ các quy tắc.
* [Các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) áp dụng quy tắc một cách độc lập, nhưng mạng thực tế hoạt động bằng phần mềm và việc trao đổi thông tin, chứ không phải bằng một cuộc bỏ phiếu trong lớp học.
* Một nhà phát triển có thể viết các quy tắc khác, nhưng việc áp dụng là tự nguyện và các quy tắc không tương thích có thể tạo ra một mạng riêng biệt.

Hãy hỏi:

> Tại sao một [nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) xác minh các giao dịch? Hãy nêu ít nhất một quy tắc mà nút đó kiểm tra.
