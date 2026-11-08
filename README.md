# Hệ thống Quản lý Văn bản và Điều hành

Dự án xây dựng bằng **Django** nhằm hỗ trợ quản lý văn bản và điều hành công việc trong cơ quan/doanh nghiệp.  
Hệ thống được phát triển từ giao diện frontend tĩnh và đang được chuyển đổi sang mô hình **Django Backend + Template Rendering**.

## Mục tiêu dự án

- Quản lý tập trung văn bản đi và văn bản đến
- Quản lý hồ sơ văn bản
- Hỗ trợ giao việc, phân công và theo dõi xử lý công việc
- Tăng khả năng tra cứu, theo dõi trạng thái và điều hành công việc
- Chuẩn hóa luồng xử lý văn bản trong hệ thống

## Module chính

### 1. Quản lý văn bản đi
- Thêm mới văn bản đi
- Cập nhật, chỉnh sửa văn bản đi
- Xem danh sách văn bản đi
- Xem chi tiết văn bản đi
- Duyệt và ban hành văn bản
- Theo dõi trạng thái xử lý văn bản đi

### 2. Quản lý văn bản đến
- Tiếp nhận văn bản đến
- Cập nhật, chỉnh sửa văn bản đến
- Xem danh sách văn bản đến
- Xem chi tiết văn bản đến
- Chuyển tiếp văn bản
- Hoàn trả văn bản
- Theo dõi tiến độ xử lý

### 3. Hồ sơ văn bản
- Tạo hồ sơ văn bản
- Quản lý danh sách hồ sơ
- Liên kết văn bản với hồ sơ
- Xem chi tiết hồ sơ
- Xử lý hồ sơ văn bản

### 4. Quản lý công việc
- Tạo công việc
- Giao việc
- Phân công công việc
- Theo dõi trạng thái xử lý
- Phê duyệt công việc
- Hoàn trả công việc
- Quản lý file liên quan đến công việc

## Công nghệ sử dụng

- **Backend:** Django 4.2.8
- **Frontend:** HTML, CSS
- **Database:** SQLite
- **Template Engine:** Django Templates
- **Quản lý file tĩnh:** Django Static Files
- **Quản lý media:** Django Media Files
- **Version Control:** Git, GitHub

## Cấu trúc dự án

```bash
he_thong_quan_ly_van_ban/
│
├── manage.py
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

## Vai trò và đóng góp cá nhân

**Dự án:** Hệ thống Quản lý Văn bản và Điều hành  
**Hình thức:** Đồ án nhóm môn Lập trình Web  
**Vai trò:** Thành viên phát triển hệ thống, phụ trách module Quản lý văn bản đến và Trang chủ (Dashboard).

### 1. Phát triển module Quản lý văn bản đến
- Tham gia xây dựng chức năng tiếp nhận và quản lý văn bản đến.
- Phát triển các chức năng hiển thị danh sách, xem chi tiết, thêm, chỉnh sửa và cập nhật thông tin văn bản.
- Xây dựng các chức năng hỗ trợ chuyển tiếp, hoàn trả và theo dõi quá trình xử lý văn bản theo nghiệp vụ của hệ thống.
- Hoàn thiện giao diện và kết nối dữ liệu phục vụ quản lý văn bản đến.

### 2. Phát triển Trang chủ (Dashboard)
- Thiết kế và xây dựng giao diện trang chủ của hệ thống.
- Triển khai hiển thị thông tin tổng quan về văn bản và công việc.
- Xây dựng các thành phần thống kê, trực quan hóa dữ liệu và điều hướng chức năng.
- Hoàn thiện bố cục và trải nghiệm người dùng.

### 3. Công nghệ và kỹ năng sử dụng
- **Backend:** Python, Django.
- **Frontend:** HTML, CSS, JavaScript, Django Templates.
- **Database:** SQL, Django ORM.
- **Kỹ năng:** Phát triển ứng dụng web, xử lý nghiệp vụ, tích hợp module và làm việc nhóm.

*Đây là những chức năng có trong mã nguồn thuộc hai module bạn phụ trách. Chỉ giữ những chức năng bạn thực sự trực tiếp triển khai.*
