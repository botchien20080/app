# SoftwareHub Pro — Local Software Center

## Chạy ngay
1. Giải nén thư mục.
2. Mở `index.html` bằng Chrome/Edge.
3. Không cần cài XAMPP, Node.js hay database.

## Quản lý phần mềm
- Bấm **⚡ Quản trị** hoặc **+ Thêm phần mềm**.
- Có thể thêm, sửa, xóa phần mềm.
- Dữ liệu tự lưu vào `LocalStorage` của trình duyệt.
- Vào **Cài đặt → Xuất dữ liệu JSON** để sao lưu.
- Có thể nhập JSON lại trên máy khác.

## Cập nhật phần mềm sau này
Mỗi phần mềm là một object trong `assets/data.js`. Có thể cập nhật dữ liệu trực tiếp tại đây, hoặc dùng giao diện quản trị.
Nếu muốn quản lý nhiều máy/người dùng, có thể nâng cấp backend sau này:
- PHP + MySQL
- Node.js + SQLite/MySQL
- REST API
- Google Sheets/API

## Cấu trúc
- `index.html` — giao diện chính
- `assets/style.css` — giao diện
- `assets/data.js` — dữ liệu mẫu
- `assets/app.js` — chức năng
- `README.md` — hướng dẫn
