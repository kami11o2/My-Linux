
## Terminal
- Là cửa sổ giúp người dùng sử dụng máy tính qua các câu lệnh.
### 1. Terminal ảo
- Vì Linux có tính đa nhiệm nên có cung cấp thêm các terminal ảo để ta có thể sử dụng nhiều **terminal** cùng lúc.
### 2. Smart terminal
- Giúp người dùng có thể làm việc với giao diện đồ họa chứ không đơn thuần là làm việc trên màn hình đen nữa.
```
Ctrl + Alt + Fn: Chuyển về terminal
Ctrl + F7      : Chuyển về môi trường đồ họa
```
## Shell
- Để người dùng có thể giao tiếp với máy tính bằng các câu lệnh. Đóng vai như một **thông dịch viên** để cho hệ điều hành có thể hiểu các câu lệnh của người sử dụng.
- Có nhiều Shell khác nhau nhưng **bash** là Shell mặc định của Red Hat Linux.
```
halt  : để shutdown hệ thống.
reboot: để shutdown rồi khởi động lại hệ thống.
- Để dùng 2 lệnh này ta cần có quyền tương ứng.
```
## Thi hành lệnh
- Cú pháp lệnh cơ bản:
```
command -option arguments

command  : lệnh truyện vào
option   : lựa chọn của lệnh thực hiện sau một dấu **"-"**
arguments: nơi lệnh cần truy cập tới
```
- Để thực hiện nhiều lệnh giữa các cú pháp lệnh ta dùng một dấu **";"**.
- Dùng **Ctrl + C** để ngừng lệnh hiện tại lại.
- Sử dụng **"\"** để viết tiếp lệnh đang thực hiện ở dòng hiện tại xuống dòng kế tiếp.
### Pipeline
- Dùng để kết nối các tiến trình bằng cách lấy đầu ra của lệnh này làm đầu vào của lệnh khác.
- Cú pháp thi hành pipeline:
```
command_1 | command_2 | command_3 ...
```
## Chuyển hướng đầu vào/ra
- Mọi chương trình chạy trong shell đều mở ba tập tin (thiết bị): nhập chuẩn (standard input),
xuất chuẩn (standard output), và lỗi chuẩn (standard error).
```
- Thiết bị nhập chuẩn: cung cấp cách thức lấy dữ liệu nhập vào.
- Thiết bị xuất chuẩn: cung cấp cách thức gửi dữ liệu xuất ra.
- Thiết bị lỗi chuẩn : ghi lại báo cáo lỗi trong quá trình thi hành.
```
>< biểu thị đầu vào  
> biểu thị đầu ra

