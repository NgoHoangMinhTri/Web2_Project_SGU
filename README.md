# Website sells clothes and bags
## Mô tả
- Link trang website: [website bán hàng Minimal](https://minimal.crv.vn/)
- Do để tránh khó khăn trong đồ án nên nhóm đã lượt **bỏ chức năng viết blog**

Dự án này là một hệ thống quản lý cửa hàng trực tuyến với các chức năng cơ bản như một trang web bán hàng. Dự án được phát triển bởi một nhóm, trong đó tôi đã chịu trách nhiệm cho các phần sau:
- Giao diện giỏ hàng
- Giao diện trang admin quản lý sản phẩm
- Quản lý liên hệ
- Quản lý đánh giá
- Backend xử lý quản lý liên hệ

## Phần Tôi Đã Thực Hiện

- **Giao Diện Giỏ Hàng**: 
  - Thêm sản phẩm vào giỏ hàng.
  - Xem danh sách sản phẩm trong giỏ hàng.
  - Xóa sản phẩm khỏi giỏ hàng.

- **Giao Diện Trang Admin Quản Lý Sản Phẩm**: 
  - Thêm sản phẩm mới.
  - Sửa đổi thông tin sản phẩm.
  - Xóa sản phẩm.

- **Quản Lý Liên Hệ**: 
  - Hiển thị các yêu cầu liên hệ từ khách hàng.
  - Xử lý các yêu cầu liên hệ.

- **Quản Lý Đánh Giá**: 
  - Hiển thị các đánh giá từ khách hàng.
  - Xử lý các đánh giá.

- **Backend Xử Lý Quản Lý Liên Hệ**: 
  - Xử lý các yêu cầu liên hệ được gửi từ giao diện người dùng.

## Cài Đặt
Để cài đặt và chạy dự án này, vui lòng làm theo các bước sau:

1. **Tải File Code**
    - Clone repository từ GitHub:
      ```bash
      git clone https://github.com/NgoHoangMinhTri/Web2_Project_SGU.git
      ```
    - Hoặc tải file code zip từ GitHub và giải nén.

2. **Tạo Database trên MySQL**
    - Mở MySQL và tạo một database mới tên là `website_sells_clothes_and_bags`:
      ```sql
      CREATE DATABASE website_sells_clothes_and_bags;
      ```

3. **Khởi Tạo Database**
    - Import file `DATA_CONTRUCTOR.sql` để khởi tạo cấu trúc database:
      - Mở công cụ quản lý cơ sở dữ liệu như phpMyAdmin hoặc MySQL Workbench.
      - Chọn database `website_sells_clothes_and_bags`.
      - Import file `DAL/DATA_CONTRUCTOR.sql`.

4. **Push Dữ Liệu Lên Database**
    - Import file `TABLES.sql` để push dữ liệu có sẵn vào database:
      - Mở công cụ quản lý cơ sở dữ liệu như phpMyAdmin hoặc MySQL Workbench.
      - Chọn database `website_sells_clothes_and_bags`.
      - Import file `DAL/TABLES.sql`.

5. **Mở Trình Duyệt**
    - Sau khi hoàn thành các bước trên, mở trình duyệt và truy cập vào:
      ```
      http://localhost/Web2_Project_SGU-master/GUI/view/login.php
      ```
    - Đăng nhập bằng tài khoản admin để vào trang quản trị hoặc đăng nhập bằng tài khoản khách để vào trang khách hàng.

## Công Nghệ Sử Dụng
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Php, Ajax
- **Cơ Sở Dữ Liệu**: MySql
- **Khác**: Git

## Liên Hệ

Nếu bạn có bất kỳ câu hỏi hoặc phản hồi nào, vui lòng liên hệ với tôi qua:
- **Email**: ngohoangminhtri0512@gmail.com
