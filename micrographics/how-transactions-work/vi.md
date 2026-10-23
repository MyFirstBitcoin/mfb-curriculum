# How Transations Work

## Alt text

Sơ đồ dọc gồm bảy bước mô tả một khoản thanh toán bitcoin từ Alice đến Bob: tạo và ký giao dịch, phát giao dịch lên mạng, các nút xác minh, chờ trong mempool, được khai thác vào một khối và khối được thêm vào chuỗi khối khi số lượt xác nhận tăng dần.

## Texts

### s1-label

Alice tạo một giao dịch

### s1-desc

Cô chỉ định người nhận, số lượng bitcoin và phí trả cho thợ đào.

### r-to

Đến

### r-to-v

Địa chỉ của Bob

### r-amount

Số lượng

### r-fee

Phí mạng

### s2-label

Cô ký giao dịch bằng khóa riêng của mình

### s2-desc

Chữ ký số chứng minh cô có quyền chi tiêu số bitcoin đó.

### s3-label

Phát giao dịch lên mạng

### s3-desc

Giao dịch đã ký được gửi đến các nút để kiểm tra xem giao dịch có tuân thủ các quy tắc hay không.

### chip-sig

Chữ ký hợp lệ

### chip-bal

Đủ bitcoin

### chip-rules

Tuân thủ các quy tắc

### s4-label

Giao dịch chờ trong mempool

### s4-desc

Các giao dịch hợp lệ chờ trong một vùng chứa các khoản thanh toán đang chờ xử lý.

### s5-label

Thợ đào đưa giao dịch vào một khối

### s5-desc

Các thợ đào chọn giao dịch và cạnh tranh để khai thác một khối.

### s6-label

Khối được thêm vào chuỗi khối

### s6-desc

Các nút khác xác minh khối rồi gắn khối đó vĩnh viễn vào chuỗi.

### s7-label

Bob nhận được bitcoin

### s7-desc

Giao dịch giờ đã được xác nhận. Alice không thể chi tiêu lại số bitcoin đó, còn Bob có thể chi tiêu số bitcoin mình đã nhận.

### foot

<strong>Mỗi khối mới khiến giao dịch nằm sâu hơn trong chuỗi.</strong> Với mỗi khối được thêm vào phía sau, việc đảo ngược giao dịch trở nên khó hơn theo cấp số nhân &#8212; đó là điều tạo nên tính chung cuộc của bitcoin.
