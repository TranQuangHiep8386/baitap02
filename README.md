# baitap02
mobile
1. Bối cảnh và Nhu cầu
Thực tế tại các cửa hàng cầm đồ, việc quản lý hợp đồng bằng sổ sách hoặc các phần mềm máy tính truyền thống gây ra nhiều bất tiện khi chủ cửa hàng cần kiểm tra thông tin nhanh chóng từ xa hoặc ngay tại quầy bằng thiết bị di động. Bài toán đặt ra là xây dựng một ứng dụng web hiện đại, có khả năng lưu trữ dữ liệu tập trung và tương thích tốt với các thiết bị di động.

2. Mục tiêu của Hệ thống
Quản lý thông tin định danh: Lưu trữ chính xác thông tin khách hàng, bao gồm họ tên và số CCCD để đảm bảo tính pháp lý của hợp đồng.

Quản lý tài sản và tài chính: Ghi nhận chi tiết tên món hàng cầm cố và số tiền giải ngân tương ứng.

Kiểm soát thời hạn: Theo dõi chặt chẽ ngày lập hợp đồng và thiết lập thời hạn thanh toán để chủ cửa hàng chủ động trong việc nhắc nợ hoặc thanh lý tài sản.

Tối ưu hóa hiển thị: Chuyển đổi giao diện quản lý từ dạng bảng (Table) phức tạp sang dạng thẻ (Card) trực quan, giúp việc tra cứu trên điện thoại trở nên dễ dàng.

3. Đối tượng sử dụng
Chủ cửa hàng (Admin): Sử dụng giao diện quản trị để nhập liệu, sửa đổi thông tin và quản lý toàn bộ danh sách hợp đồng.

Nhân viên kiểm tra (Viewer): Sử dụng thiết bị di động truy cập qua mạng nội bộ để xem nhanh trạng thái các hợp đồng và thời hạn thanh toán.

4. Giải pháp Công nghệ đã áp dụng
Framework: Sử dụng Django 4.2 để xây dựng logic xử lý dữ liệu và giao diện quản trị nhanh chóng.

Cơ sở dữ liệu: Sử dụng MariaDB để lưu trữ dữ liệu bền vững và an toàn.

Triển khai: Ứng dụng công nghệ Docker & Docker Compose để đóng gói hệ thống, giúp việc cài đặt và triển khai bài tập trở nên nhất quán trên mọi máy tính.

Giao diện: Kết hợp Bootstrap để tạo thiết kế Responsive, đảm bảo ứng dụng hoạt động mượt mà trên mọi kích thước màn hình.
tạo môi trường trên docker
<img width="1080" height="592" alt="image" src="https://github.com/user-attachments/assets/7a39d2ef-30cf-451a-8ee7-9f81f8524ef3" />
khởi chạy 
<img width="1134" height="208" alt="image" src="https://github.com/user-attachments/assets/ca10375d-be15-45f2-aa4a-6c66c95b4e8b" />
tạo tai khoan admin
<img width="1120" height="497" alt="image" src="https://github.com/user-attachments/assets/014eb638-4655-4fdb-8739-038e88d35820" />

<img width="1139" height="222" alt="image" src="https://github.com/user-attachments/assets/1190fedb-1f06-4eba-b74d-4f0d4bd4b900" />
giao diện
<img width="1915" height="908" alt="image" src="https://github.com/user-attachments/assets/5b565ddd-d580-424e-9799-8350bc9c2a34" />
đăng ký hợp đồng
<img width="2543" height="655" alt="image" src="https://github.com/user-attachments/assets/0f79f53b-56f3-435e-a338-4994a48cd2e8" />

<img width="1306" height="163" alt="image" src="https://github.com/user-attachments/assets/44e3756d-be9b-4d2d-9487-cd95494821a0" />
hợp đồng cầm đồ 
<img width="2533" height="777" alt="image" src="https://github.com/user-attachments/assets/562a88e1-4822-4b7f-bb67-c81e5b63c0a7" />

<img width="1582" height="184" alt="image" src="https://github.com/user-attachments/assets/f1ccf655-87a8-4bbb-ae5e-ec69fa5a889a" />

<img width="1300" height="180" alt="image" src="https://github.com/user-attachments/assets/4fdbcfe8-ec0a-4f41-88b3-b5ca9adf3013" />
<img width="266" height="216" alt="image" src="https://github.com/user-attachments/assets/6b168681-f3f8-4f07-9efe-1244cbfdd9c5" />
