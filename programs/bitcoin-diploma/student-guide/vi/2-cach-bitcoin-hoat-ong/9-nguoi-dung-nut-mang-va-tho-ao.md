# 2.9 Người dùng, nút mạng và thợ đào

Bitcoin hoạt động nhờ các bên tham gia đảm nhận những vai trò khác nhau.

* **Người dùng** nhận, nắm giữ và gửi bitcoin. Người dùng có thể tự kiểm soát các khóa của mình được lưu trong ví hoặc sử dụng một [bên lưu ký](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Người dùng tạo ý nghĩa kinh tế cho mạng lưới bằng cách lựa chọn có chấp nhận bitcoin hay không và tin tưởng những quy tắc hoặc dịch vụ nào.
* [**Các nút**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) chạy phần mềm Bitcoin và xác minh các quy tắc một cách độc lập. Một [nút đầy đủ](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) kiểm tra để bảo đảm rằng [các giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) có chữ ký hợp lệ, bitcoin chưa bị chi tiêu trước đó, các khối đáp ứng yêu cầu về [bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), và bitcoin mới tuân theo [lịch trình phát hành](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) chia sẻ dữ liệu hợp lệ với các nút ngang hàng và từ chối dữ liệu không hợp lệ.
* [**Thợ đào**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) tập hợp các [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) đang chờ xử lý, xây dựng [các khối ứng viên](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block), và cạnh tranh thông qua [bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Một [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [thành công sẽ phát tán](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) một khối và có thể nhận khoản [trợ cấp khối](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) được phép cùng với [phí giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) giúp sắp xếp thứ tự [các giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) và khiến việc viết lại [sổ cái](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) trở nên tốn kém.
* **Các nhà phát triển** rà soát, viết và đề xuất các thay đổi phần mềm. Họ không sở hữu các quy tắc của Bitcoin. Một thay đổi phần mềm chỉ có ý nghĩa khi các bên tham gia lựa chọn chạy phần mềm tuân theo những quy tắc đó.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Bốn vai trò trong Bitcoin: người dùng nhận, nắm giữ và gửi bitcoin, các nút độc lập xác minh việc tuân thủ các quy tắc, thợ đào xây dựng các khối ứng viên bằng bằng chứng công việc, và nhà phát triển đề xuất phần mềm. Không một vai trò riêng lẻ nào kiểm soát mạng lưới.](/micrographics/bitcoin-participant-roles-01/vi.md)


Các vai trò này giới hạn lẫn nhau:

* người dùng không thể chi tiêu bitcoin nếu không có chữ ký hợp lệ theo yêu cầu
* một [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) có thể đề xuất một khối, nhưng [các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) quyết định khối đó có tuân theo các quy tắc hay không
* một [nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) xác minh theo các quy tắc riêng của mình, nhưng [sự đồng thuận](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) đòi hỏi các quy tắc tương thích trên toàn mạng lưới
* các nhà phát triển có thể đề xuất phần mềm, nhưng những người tham gia quyết định có chạy phần mềm đó hay không

Một số người đảm nhiệm nhiều vai trò. Một [thợ đào](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) có thể vận hành một [nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) và đồng thời là người dùng. Người mới bắt đầu không cần đảm nhiệm mọi vai trò để giải thích cách các vai trò cân bằng lẫn nhau.

**Câu hỏi nhanh:** Tại sao một [nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) xác minh [các giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Hãy nêu ít nhất một quy tắc mà một [nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kiểm tra.

![Giảng viên hướng dẫn học viên kỹ thuật tại một máy tính chạy nút, với màn hình hướng về phía họ và phần vỏ phía sau màn hình hiện ra trước mắt người xem.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
