## Luồng tệp
* Có 3 luồng tệp tiêu chuẩn luôn mở để sử dụng:
  1. Tiêu chuẩn đầu vào **(stdin)**.
  2. Tiêu chuẩn đầu ra **(stdout)**.
  3. Tiêu chuẩn lỗi **(stderr)**.
## Tìm tệp
* Tiện ích ```locate``` tìm kiếm thông qua cơ sở dữ liệu và thư mục được xây dựng trước đó trên hệ thống.
* Hầu hết hệ thống trên Linux chạy mỗi ngày nhưng có thể cập nhật bất cứ lúc nào bằng lệnh ```updatedb``` với tư cách **root user**.
* Kết quả thu được từ ```locate``` đôi khi rất dài, có thể sử dụng ```grep``` làm bộ lọc rút gọn danh sách có liên quan  Nó sẽ chỉ in các dòng có chứa một hoặc nhiều chuỗi được chỉ định như sau: 
```
$ locate zip | grep bin
/usr/bin/gpg-zip
/usr/bin/gunzip
/usr/bin/gzip
/usr/bin/zipdetails
```  
* Có thể sử dụng các ký tự đại diện để tìm kiếm tên tệp có chứa các ký tự cụ thể.

|Ký tự|Kết quả|
|---------|-----------|
|?     |Phù hợp với bất kỳ ký tự đơn nào|
|*     |Phù hợp với bất kỳ chuỗi ký tự nào|
|[set] |Phù hợp với bất kỳ ký tự nào nằm trong tập ký tự|
|[!set]|Phù hợp với bất kỳ ký tự nào không nằm trong tập ký tự|
