## Hệ thống tập tin
- Được gọi là **File System**.
- Có chức năng tổ chức, kiểm soát các tập tin và siêu dữ liệu tương ứng, được lưu trên ổ đĩa nhằm cho phép truy cập nhanh chóng và an toàn.
- Sắp xếp dữ liệu được lưu trên đĩa cứng của máy tính.
- Kiểm soát thường xuyên vị trí vật lý của mọi thành phần dữ liệu trên đĩa nhưng vẫn cho phép người dùng truy cập nhanh chóng và an toàn khi cần thiết.
- Cho phép máy tính nhanh chóng tìm thấy một tập tin nào đó.
>Tóm lại File System có chức năng định nghĩa một file trên máy tính
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
>`Journaling` chỉ được sử dụng khi ghi dữ liệu lên ổ cứng và ghi thông tin vào phân vùng. Đồng thời, nó cũng khắc phục vấn đề xảy ra khi ổ cứng gặp lỗi trong quá trình này, nếu không có journal thì hệ điều hành sẽ không thể biết được file dữ liệu có được ghi đầy đủ tới ổ cứng hay chưa.
### Hệ thống tập tin Ext4
- Giảm bớt hiện tượng phân mảnh dữ liệu trong ổ cứng, hỗ trợ các file và phân vùng có dung lượng lớn..., Thích hợp với ổ SSD.
### Hệ thống tập tin XFS
- Quản lý được file có kích thước là 9 Exabyte. Cho phép các ứng dụng duy trì được tốc độ truy xuất dữ liệu trên đĩa.
