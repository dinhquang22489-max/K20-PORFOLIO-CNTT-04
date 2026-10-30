không hiện ảnh
không đúng đường dẫn
# Nhật ký lỗi

## Các lỗi được ghi nhận

1. **README.md thiếu hướng dẫn sản phẩm** — Đã xác nhận. README hiện chỉ có tên thư mục dự án và một dòng mô tả ngắn; chưa có tác giả, mô tả sản phẩm, liên kết repository/Pages, cấu trúc thư mục, cách chạy local, nguồn xuất bản, hướng dẫn kiểm tra chức năng, hồ sơ hoặc minh chứng.
2. **Không hiển thị ảnh** — Người dùng báo lỗi. Trong `index.html` hiện không có thẻ ảnh và thư mục dự án chưa có tệp ảnh trong danh sách hiện có; vì vậy ảnh chưa được đưa vào sản phẩm, không thể xác nhận đây là lỗi sai đường dẫn ảnh.
3. **Đường dẫn không đúng** — Người dùng báo lỗi. Chưa có URL hoặc đường dẫn cụ thể để tái hiện; README hiện không chứa liên kết. Cần cung cấp liên kết/tệp bị lỗi để xác định chính xác nguyên nhân.

## Ghi chú kiểm tra

- `index.html` và `ket-qua.html` có liên kết stylesheet `css/style.css`, phù hợp với cấu trúc thư mục hiện có.
- Biểu mẫu trong `index.html` gửi bằng GET tới `ket-qua.html`; đây là mô phỏng, không gửi email hoặc lưu dữ liệu.
