Hệ thống Quản lý Văn bản và Điều hành
Đồ án nhóm môn Lập trình Web | Ngành Hệ thống thông tin quản lý (MIS)
Vai trò cá nhân: Phát triển module Quản lý văn bản đến và Trang chủ (Dashboard)

1. Giới thiệu dự án
Hệ thống Quản lý Văn bản và Điều hành là ứng dụng web hỗ trợ số hóa hoạt động tiếp nhận, xử lý, lưu trữ văn bản và quản lý công việc trong cơ quan, tổ chức. Dự án sử dụng Python và Django, kết hợp Django Templates, HTML, CSS và JavaScript để phát triển giao diện và xử lý nghiệp vụ.

Hệ thống được thực hiện theo hình thức đồ án nhóm. Các chức năng được chia thành những module riêng để thuận tiện phát triển, phối hợp và bảo trì.
2. Mục tiêu dự án
- Quản lý tập trung văn bản đến, văn bản đi và hồ sơ văn bản.
- Hỗ trợ tiếp nhận, chuyển tiếp, theo dõi và xử lý văn bản theo quy trình.
- Quản lý giao việc, phân công và theo dõi tiến độ công việc.
- Cung cấp trang tổng quan để tra cứu và theo dõi thông tin nhanh chóng.
- Góp phần giảm thao tác thủ công trong quản lý văn bản và điều hành.
3. Các chức năng chính
3.1. Quản lý văn bản đến
- Tiếp nhận và lưu thông tin văn bản đến.
- Hiển thị danh sách, tìm kiếm và xem chi tiết văn bản.
- Thêm mới, chỉnh sửa và cập nhật thông tin văn bản.
- Chuyển tiếp, hoàn trả và theo dõi trạng thái xử lý văn bản.
3.2. Quản lý văn bản đi
- Tạo, chỉnh sửa và xem chi tiết văn bản đi.
- Quản lý danh sách văn bản và theo dõi trạng thái xử lý.
- Hỗ trợ quy trình duyệt, ban hành văn bản.
3.3. Quản lý hồ sơ văn bản
- Tạo và quản lý hồ sơ.
- Phân loại, liên kết văn bản với hồ sơ và tra cứu thông tin hồ sơ.
3.4. Quản lý công việc
- Tạo công việc, giao việc và phân công xử lý.
- Theo dõi trạng thái, tiến độ và kết quả thực hiện.
- Hỗ trợ phê duyệt, hoàn trả và quản lý tài liệu liên quan.
3.5. Trang chủ (Dashboard)
- Hiển thị thông tin tổng quan về văn bản và công việc.
- Tổng hợp thông tin, số liệu và các trạng thái xử lý.
- Tổ chức các khu vực điều hướng đến những chức năng chính của hệ thống.
4. Công nghệ sử dụng
Thành phần	Công nghệ
Backend	Python, Django
Frontend	HTML, CSS, JavaScript
Template engine	Django Templates
Cơ sở dữ liệu	SQLite / PostgreSQL tùy cấu hình
Xử lý dữ liệu	Django ORM
Quản lý mã nguồn	Git, GitHub


Lưu ý về phiên bản: Phiên bản Django cần lấy theo tệp requirements.txt của mã nguồn đang đăng. Không nên giữ số phiên bản từ README cũ nếu đã cập nhật dependencies.

5. Cấu trúc dự án
QuanLyVanBan-DieuHanh/
├── manage.py
├── he_thong_quan_ly_van_ban/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
├── apps/
│   ├── accounts/
│   ├── core/
│   ├── quanlyvanbanden/
│   ├── quanlyvanbandi/
│   ├── hosovanban/
│   ├── quanlycongviec/
│   ├── templates/
│   └── static/
├── requirements.txt
├── .env.example
└── README.md
Cấu trúc trên tóm tắt các thành phần chính; những thư mục dữ liệu, tài liệu hoặc tệp phụ trợ có thể khác theo phiên bản mã nguồn.
6. Vai trò và đóng góp cá nhân
Hình thức: Đồ án nhóm môn Lập trình Web.
Vai trò: Thành viên phát triển hệ thống, phụ trách Quản lý văn bản đến và Trang chủ (Dashboard).
6.1. Module Quản lý văn bản đến
- Tham gia phát triển chức năng tiếp nhận và quản lý văn bản đến.
- Xây dựng giao diện danh sách, xem chi tiết, thêm mới và cập nhật thông tin văn bản.
- Phát triển các thao tác chuyển tiếp, hoàn trả và theo dõi quá trình xử lý văn bản trong phạm vi được phân công.
- Kết nối giao diện với dữ liệu và nghiệp vụ của module.
6.2. Trang chủ (Dashboard)
- Thiết kế và xây dựng giao diện trang chủ.
- Hiển thị thông tin tổng quan về văn bản và công việc.
- Tổ chức bố cục, các thành phần thống kê và điều hướng chức năng.
- Điều chỉnh giao diện để người dùng dễ theo dõi và thao tác.
6.3. Kỹ năng tích lũy
- Phát triển ứng dụng web với Python, Django và Django Templates.
- Làm việc với HTML, CSS, JavaScript và dữ liệu thông qua Django ORM.
- Phân tích luồng xử lý văn bản, xây dựng chức năng theo nghiệp vụ.
- Phối hợp và tích hợp các module trong quá trình thực hiện đồ án nhóm.
Chỉ giữ những nhiệm vụ bạn thực sự trực tiếp thực hiện và có thể giải thích khi phỏng vấn.

7. Hướng dẫn chạy dự án
Yêu cầu: Python và các thư viện tương thích với phiên bản Django khai báo trong requirements.txt.

Mở Terminal tại thư mục chứa manage.py, sau đó thực hiện:
py -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe manage.py migrate
.\.venv\Scripts\python.exe manage.py runserver
Mở trình duyệt tại: http://127.0.0.1:8000/.

Nếu dự án yêu cầu biến môi trường, hãy tạo cấu hình trên máy từ .env.example và thiết lập các giá trị cần thiết (như SECRET_KEY và cấu hình cơ sở dữ liệu). Không đưa .env, mật khẩu, chứng thư hoặc dữ liệu văn bản thật lên repository công khai.
8. Ghi chú
- Đây là dự án học tập được phát triển theo nhóm, không phải sản phẩm triển khai thương mại.
- Mỗi thành viên chịu trách nhiệm những phần việc khác nhau; nội dung ở mục 6 mô tả đóng góp cá nhân.
- Những chức năng có trong mã nguồn chưa đồng nghĩa đã được kiểm thử đầy đủ trên mọi môi trường.
- Khi tái sử dụng hoặc công khai mã nguồn, cần tôn trọng quyền chia sẻ của nhóm và kiểm tra dữ liệu nhạy cảm.
