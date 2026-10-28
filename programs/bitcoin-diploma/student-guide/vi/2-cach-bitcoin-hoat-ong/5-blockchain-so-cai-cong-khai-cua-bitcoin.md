# 2.5 Blockchain: Sổ cái công khai của Bitcoin

<!-- card: definition -->
> **Definition – Chuỗi khối**
>
> Bitcoin có [chuỗi khối](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) là một bản ghi công khai về [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) được sao chép trên nhiều máy tính độc lập. Một khối tập hợp các [giao dịch](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) hợp lệ thành phần tiếp theo được đề xuất cho bản ghi đó. Mỗi khối hợp lệ liên kết với khối trước đó, tạo cho mạng lưới một lịch sử chung có thứ tự để xác minh.



<!-- card: light -->
> **Cách các nút đạt được sự đồng thuận**
>
> [Các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kiểm tra độc lập theo cùng một bộ quy tắc và cùng đi đến lịch sử hợp lệ có lượng [bằng chứng công việc](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) tích lũy lớn nhất. Việc thay đổi một bản ghi trước đó làm thay đổi khối chứa nó và phá vỡ các liên kết với những khối sau, vì vậy một lịch sử cạnh tranh phải thực hiện lại lượng công việc đó và bắt kịp trước khi [các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) chấp nhận nó. Quá trình sắp xếp thứ tự tốn kém này giúp mạng lưới đạt được [sự đồng thuận](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) mà không cần một bên lưu giữ bản ghi tập trung. Các bản sao không thay đổi đồng thời; [các nút](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tiếp nhận và xác thực dữ liệu một cách độc lập. Bitcoin đặt mục tiêu trung bình khoảng mười phút có một khối mới. Việc viết lại lịch sử rất khó và tốn kém, chứ không phải hoàn toàn không thể thay đổi: các lịch sử cạnh tranh tạm thời và việc tái tổ chức chuỗi có thể xảy ra.
