## Hệ thống tập tin
- Được gọi là **File System**.
- Có chức năng tổ chức, kiểm soát các tập tin và siêu dữ liệu tương ứng, được lưu trên ổ đĩa nhằm cho phép truy cập nhanh chóng và an toàn.
- Sắp xếp dữ liệu được lưu trên đĩa cứng của máy tính.
- Kiểm soát thường xuyên vị trí vật lý của mọi thành phần dữ liệu trên đĩa nhưng vẫn cho phép người dùng truy cập nhanh chóng và an toàn khi cần thiết.
- Cho phép máy tính nhanh chóng tìm thấy một tập tin nào đó.
### Hệ thống tập tin Ext2
- **Ext2 (Second Extended File System – Ext2fs)**.
- Được cải tiến từ File System đầu tiên của Linux.
- Hỗ trợ các kiểu tập tin chuẩn của Unix **(các tập tin thường, thư mục, các tập tin dành riêng thiết bị và các symbolic
link)**.
- Hỗ trợ lên đên 4TB, 255 ký tự và khắc phục hạn chế về tốc độ của phiên bản Ext tiền nhiệm.
- Dùng cấu trúc dữ liệu được gọi là nút định dạng (inode) để tham chiếu và định vị tập tin cũng như các dữ liệu tương ứng.
### Hệ thống tập tin Ext3
- Thêm chức năng quan trọng **Journaling File System**.
- Giúp thao tác an toàn hơn, như khi hệ điều hành bị tắt bất chợt, trong File System xuất hiện lỗi,... thì hệ điều hành sẽ phát hiện được lần tắt bị lỗi unclean shutdown trước đó và tự sửa.
- 