# Bài tập: Tạo Trang Đăng Ký Người Dùng (Bootstrap Forms & Carousel)

Dự án thiết kế giao diện đăng ký tài khoản chuyên nghiệp, tận dụng tối đa các lớp có sẵn của **Bootstrap 5.3.3**:

## Các thành phần nổi bật
1. **Bootstrap Carousel**:
   - Nằm ở cột bên trái (`col-lg-6`) trên màn hình lớn.
   - Trình diễn các lợi ích khi gia nhập dịch vụ (Cộng đồng, Tài liệu độc quyền, Cơ hội nghề nghiệp).
   - Tích hợp indicators, caption đổ bóng và các nút điều hướng chuyển ảnh mượt mà.
2. **Bootstrap Form Đăng Ký**:
   - Nằm ở cột bên phải (`col-lg-6`) bọc trong Card sang trọng với `shadow-lg`.
   - Các trường thông tin:
     - **Họ và tên**: Input Text kèm `input-group` icon `bi-person-fill`.
     - **Email**: Input Email kèm `input-group` icon `bi-envelope-fill`.
     - **Mật khẩu**: Input Password kèm `input-group` icon `bi-lock-fill`.
     - **Xác nhận mật khẩu**: Input Password kèm `input-group` icon `bi-shield-lock-fill`.
   - Checkbox đồng ý điều khoản dịch vụ.
   - Nút Submit nổi bật (`btn btn-primary btn-lg d-grid`).
3. **Bố cục Responsive**:
   - Sử dụng **Bootstrap Grid** (`row`, `col-12`, `col-lg-6`) và Flexbox (`min-vh-100 d-flex flex-column my-auto`).
   - Tối ưu hiển thị đẹp mắt trên cả điện thoại di động và máy tính để bàn.

## Chạy thử nghiệm
Mở tệp `index.html` trong bất kỳ trình duyệt web nào.
