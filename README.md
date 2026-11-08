# HỆ THỐNG QUẢN LÝ VĂN BẢN VÀ ĐIỀU HÀNH

**Đồ án nhóm – Phát triển ứng dụng web**

**Công nghệ:** Python | Django | HTML | CSS | JavaScript | SQLite

---

## 1. Giới thiệu dự án

Hệ thống Quản lý Văn bản và Điều hành là ứng dụng web được xây dựng bằng Django nhằm hỗ trợ quản lý văn bản và điều hành công việc trong cơ quan, tổ chức và doanh nghiệp.

Dự án được phát triển từ giao diện frontend tĩnh và từng bước chuyển đổi sang mô hình Django Backend kết hợp Django Template Rendering, giúp tích hợp giao diện với cơ sở dữ liệu và xử lý các nghiệp vụ quản lý.

Hệ thống hướng đến việc số hóa quy trình tiếp nhận, xử lý, lưu trữ và tra cứu văn bản, đồng thời hỗ trợ phân công và theo dõi tiến độ công việc.

## 2. Mục tiêu dự án

- Quản lý tập trung văn bản đi và văn bản đến.
- Quản lý hồ sơ và lưu trữ văn bản.
- Hỗ trợ giao việc, phân công và theo dõi tiến độ xử lý công việc.
- Nâng cao khả năng tra cứu và theo dõi trạng thái văn bản.
- Chuẩn hóa quy trình xử lý văn bản trong hệ thống.
- Hỗ trợ công tác quản lý và điều hành hoạt động của tổ chức.

## 3. Các module chính

### 3.1. Quản lý văn bản đi

- Thêm mới văn bản đi.
- Cập nhật và chỉnh sửa thông tin văn bản đi.
- Hiển thị danh sách văn bản đi.
- Xem thông tin chi tiết văn bản.
- Hỗ trợ duyệt và ban hành văn bản.
- Theo dõi trạng thái xử lý văn bản đi.

### 3.2. Quản lý văn bản đến

- Tiếp nhận và quản lý văn bản đến.
- Thêm mới, cập nhật và chỉnh sửa thông tin văn bản.
- Hiển thị danh sách văn bản đến.
- Xem thông tin chi tiết từng văn bản.
- Hỗ trợ chuyển tiếp văn bản đến các đơn vị hoặc cá nhân liên quan.
- Xử lý hoàn trả văn bản.
- Theo dõi trạng thái và tiến độ xử lý văn bản.
- Hỗ trợ tra cứu thông tin và lịch sử xử lý văn bản.

### 3.3. Quản lý hồ sơ văn bản

- Tạo mới hồ sơ văn bản.
- Quản lý danh sách hồ sơ.
- Liên kết văn bản với hồ sơ.
- Xem thông tin chi tiết hồ sơ.
- Hỗ trợ xử lý và quản lý hồ sơ văn bản.

### 3.4. Quản lý công việc

- Tạo mới công việc.
- Giao việc và phân công nhiệm vụ.
- Theo dõi trạng thái xử lý công việc.
- Hỗ trợ phê duyệt và hoàn trả công việc.
- Quản lý các tệp đính kèm liên quan.
- Theo dõi tiến độ thực hiện công việc.

### 3.5. Trang chủ và quản lý tài khoản

- Hiển thị thông tin tổng quan của hệ thống.
- Hỗ trợ thống kê văn bản và công việc.
- Cung cấp giao diện điều hướng đến các module nghiệp vụ.
- Quản lý tài khoản và hỗ trợ phân quyền người dùng.

## 4. Công nghệ sử dụng

| Thành phần | Công nghệ |
|---|---|
| Ngôn ngữ lập trình | Python |
| Backend | Django |
| Frontend | HTML, CSS, JavaScript |
| Cơ sở dữ liệu | SQLite |
| Template Engine | Django Templates |
| Truy cập dữ liệu | Django ORM |
| Quản lý file tĩnh | Django Static Files |
| Quản lý tệp tải lên | Django Media Files |
| Quản lý mã nguồn | Git, GitHub |

## 5. Cấu trúc dự án

```text
he_thong_quan_ly_van_ban/
│
├── manage.py
│
├── config/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── apps/
│   ├── core/
│   ├── accounts/
│   ├── quanlyvanbandi/
│   ├── quanlyvanbanden/
│   ├── hosovanban/
│   └── quanlycongviec/
│
├── templates/
│   ├── base.html
│   ├── dashboard.html
│   ├── index.html
│   ├── otp.html
│   ├── registration/
│   ├── quanlyvanbandi/
│   ├── quanlyvanbanden/
│   ├── hosovanban/
│   └── quanlycongviec/
│
├── static/
│   └── assets/
│       ├── css/
│       ├── js/
│       ├── img/
│       └── fonts/
│
├── media/
│   ├── van_ban_di/
│   ├── van_ban_den/
│   ├── ho_so_van_ban/
│   └── cong_viec/
│
└── requirements.txt
```

## 6. Vai trò và đóng góp cá nhân

**Hình thức thực hiện:** Đồ án nhóm – Môn Lập trình Web.

**Vai trò:** Thành viên phát triển hệ thống, phụ trách module Quản lý văn bản đến.

### 6.1. Phát triển module Quản lý văn bản đến

Phụ trách xây dựng và hoàn thiện các chức năng nghiệp vụ liên quan đến quá trình tiếp nhận, quản lý và xử lý văn bản đến trong hệ thống.

Các công việc chính:

- **Quản lý thông tin văn bản:** Xây dựng các chức năng thêm mới, hiển thị danh sách, xem chi tiết, cập nhật và chỉnh sửa thông tin văn bản đến.
- **Xử lý nghiệp vụ văn bản:** Triển khai các chức năng chuyển tiếp và hoàn trả văn bản theo quy trình xử lý của hệ thống.
- **Theo dõi quá trình xử lý:** Hỗ trợ quản lý trạng thái văn bản và theo dõi lịch sử chuyển tiếp, xử lý.
- **Phát triển giao diện:** Xây dựng và hoàn thiện giao diện quản lý văn bản đến bằng HTML, CSS, JavaScript và Django Templates.
- **Kết nối Backend và Database:** Sử dụng Django và Django ORM để xử lý dữ liệu, kết nối các chức năng giao diện với cơ sở dữ liệu.

### 6.2. Kiểm thử và hoàn thiện module

- Kiểm tra các chức năng thêm, sửa, xem chi tiết và quản lý danh sách văn bản đến.
- Kiểm tra luồng chuyển tiếp và hoàn trả văn bản.
- Phát hiện và xử lý các lỗi phát sinh trong quá trình phát triển.
- Hoàn thiện chức năng để tích hợp với các module khác trong hệ thống.

### 6.3. Công nghệ và kỹ năng vận dụng

- **Backend Development:** Python, Django, Django ORM.
- **Frontend Development:** HTML, CSS, JavaScript, Django Templates.
- **Database:** SQLite, xử lý dữ liệu quan hệ.
- **Business Logic:** Phân tích và triển khai quy trình xử lý văn bản đến.
- **Software Testing:** Kiểm thử chức năng và xử lý lỗi.
- **Teamwork:** Phối hợp phát triển và tích hợp module trong dự án nhóm.

## 7. Kết quả và kiến thức tích lũy

Thông qua quá trình phát triển module Quản lý văn bản đến, dự án giúp vận dụng các kiến thức và kỹ năng:

- Hiểu quy trình phát triển ứng dụng web bằng Django.
- Xây dựng các chức năng CRUD phục vụ quản lý dữ liệu.
- Tổ chức xử lý các nghiệp vụ theo yêu cầu thực tế.
- Kết nối giao diện với Backend và cơ sở dữ liệu.
- Làm việc với Django Models, Views và Templates.
- Kiểm thử chức năng và xử lý lỗi phát sinh.
- Phối hợp phát triển các module trong một hệ thống phần mềm chung.

## 8. Ghi chú

- Dự án được xây dựng phục vụ mục đích học tập và nghiên cứu.
- Hệ thống được phát triển theo hình thức đồ án nhóm.
- Phần đóng góp cá nhân tập trung vào module Quản lý văn bản đến.
- Các module còn lại thuộc phạm vi phát triển chung của nhóm.

---

**Hệ thống Quản lý Văn bản và Điều hành**

*Đồ án phát triển ứng dụng web bằng Python và Django.*
