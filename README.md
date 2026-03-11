# BanDoAnNhanh
📌 Giới thiệu
Dự án WEB BÁN ĐỒ ĂN là một website bán đồ ăn nhanh lấy cảm hứng từ các thương hiệu như KFC, Domino’s, Jollibee.
Dự án được thực hiện trong khuôn khổ Assignment môn Lập trình Quản Lý Dự Án Agile – FPT Polytechnic.

Ở giai đoạn hiện tại, nhóm tập trung vào:

Xây dựng giao diện web hoàn chỉnh
Kết nối CSDL SQL Server
Load và hiển thị sản phẩm lên giao diện
(Các chức năng nghiệp vụ sẽ được phát triển ở giai đoạn sau)

🎯 Mục tiêu giai đoạn 1
Xây dựng website theo mô hình Spring Boot MVC
Thiết kế giao diện hiện đại, thân thiện người dùng
Hiển thị danh sách sản phẩm từ database
Phân chia công việc nhóm và quản lý tiến độ bằng Excel
Chuẩn bị nền tảng để phát triển backend ở giai đoạn tiếp theo

🛠️ Công nghệ sử dụng
Java JDK 17
Spring Boot MVC
Thymeleaf
Spring Data JPA
SQL Server
HTML, CSS, Bootstrap
Stitch (Google) – thiết kế UI
Git & GitHub – quản lý source code
Trello – quản lý công việc nhóm

🗂️ Chức năng hiện có (Giai đoạn 1)

👤 Người dùng (Frontend)
Trang chủ hiển thị sản phẩm
Danh sách sản phẩm theo loại:
Combo
Đồ ăn
Nước uống
Trang chi tiết sản phẩm
Trang Giỏ hàng (UI only)
Trang Đăng nhập / Đăng ký (UI only)
🛠️ Quản trị (Admin – UI only)
Trang Admin Dashboard
Danh sách sản phẩm
Form Thêm / Sửa / Xóa sản phẩm (chỉ giao diện)

⚠️ Lưu ý:
Các chức năng như giỏ hàng, đăng nhập, đặt hàng chưa xử lý backend và sẽ được phát triển ở giai đoạn sau.

🗄️ Cơ sở dữ liệu
Sử dụng SQL Server
Các bảng chính:
Category (Combo, Đồ ăn, Nước)
Product (Tên, giá, hình ảnh, mô tả, loại)
Có dữ liệu mẫu để phục vụ hiển thị giao diện
📁 Cấu trúc thư mục
WEB_BAN_DO_AN ├── src/main/java │ ├── controller │ ├── entity │ ├── repository │ └── WebBanDoAnApplication.java ├── src/main/resources │ ├── templates │ │ ├── home │ │ ├── product │ │ ├── admin │ │ └── auth │ ├── static │ │ ├── css │ │ └── images │ └── application.properties ├── database.sql └── README.md

👥 Phân công công việc nhóm

Thành viên 1 – Backend & Cơ sở dữ liệu

Thiết lập project Spring Boot

Thiết kế và xây dựng CSDL (Database)

Kết nối Spring Boot với Database

Xây dựng API hiển thị sản phẩm (READ)


Thành viên 2 – Backend chức năng

Xây dựng API thêm / sửa / xóa sản phẩm (CRUD)

Xây dựng API đăng nhập / đăng ký

Xử lý logic giỏ hàng (Cart)

Kiểm tra và test API


Thành viên 3 – Frontend người dùng

Thiết kế giao diện Home

Thiết kế giao diện Product

Thiết kế giao diện Cart

Tích hợp dữ liệu từ Backend vào UI


Thành viên 4 – Frontend Admin & Báo cáo

Thiết kế giao diện Admin Dashboard

Trang Login

Thiết kế giao diện quản lý sản phẩm (Admin)

Viết báo cáo và tổng hợp dự án

Kiểm tra Responsive giao diện


📊 Quản lý tiến độ
Sử dụng Trello để quản lý công việc
Công việc được chia theo từng thẻ:
Việc chưa làm
Việc đang làm
Việc đã làm
Việc làm lại
Mỗi thẻ có mô tả, người phụ trách và lịch sử cập nhật

🚀 Định hướng phát triển (Giai đoạn 2)
Hoàn thiện chức năng giỏ hàng
Đăng nhập & phân quyền người dùng
Đặt hàng và quản lý đơn hàng
Bảo mật và phân quyền Admin
Thống kê và báo cáo doanh thu

📌 Ghi chú
Dự án hiện tại tập trung vào giao diện + hiển thị dữ liệu
Backend nghiệp vụ sẽ được triển khai sau
Mã nguồn được tổ chức rõ ràng, dễ mở rộng

✨ Dự án phục vụ mục đích học tập – Assignment Quản Lý Dự An Agile
