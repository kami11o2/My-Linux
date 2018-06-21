## Luồng tệp
* Có 3 luồng tệp tiêu chuẩn luôn mở để sử dụng:
  1. Tiêu chuẩn đầu vào **(stdin)**.
  2. Tiêu chuẩn đầu ra **(stdout)**.
  3. Tiêu chuẩn lỗi **(stderr)**.
## Tìm tệp
* Tiện ích ```locate``` tìm kiếm thông qua cơ sở dữ liệu và thư mục được xây dựng trước đó trên hệ thống.
* Hầu hết hệ thống trên Linux chạy mỗi ngày nhưng có thể cập nhật bất cứ lúc nào bằng lệnh ```updatedb``` với tư cách **root user**.
>Kết quả thu được từ ```locate``` đôi khi rất dài, có thể sử dụng ```grep``` làm bộ lọc rút gọn danh sách có liên quan  
```
$ locate zip | grep bin
/usr/bin/gpg-zip
/usr/bin/gunzip
/usr/bin/gzip
/usr/bin/zipdetails
```  
