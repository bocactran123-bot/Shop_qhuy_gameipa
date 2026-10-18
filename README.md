# QH MOD — Website đầy đủ (bản tĩnh)

## Có gì trong gói này?
1. Trang chủ theo bố cục tham khảo video: logo QH MOD phát sáng, thống kê, nút YouTube/TikTok/Telegram/Discord, mục yêu thích/mới, danh mục ngang và danh sách file cập nhật.
2. Danh sách Game và Ứng dụng, bộ lọc, tìm kiếm, sắp xếp.
3. Nút tải xuống và trường liên kết tải có thể chỉnh trong quản trị.
4. Cửa sổ chi tiết cho từng game/ứng dụng.
5. Bảng quản trị demo: thêm, sửa, xóa, xuất JSON.
6. Giao diện responsive cho iPhone, Android, tablet và máy tính.

## Mở thử
- Giải nén ZIP.
- Mở `index.html` bằng trình duyệt, hoặc tải cả thư mục lên GitHub Pages / Cloudflare Pages.
- Website không cần lệnh build; nếu nền tảng hỏi Build command thì để trống. Thư mục đầu ra là thư mục gốc chứa `index.html`.

## Quản trị demo
- Bấm **Quản trị**.
- Mã demo ban đầu: `qhmod123`.
- Có thể thêm/sửa/xóa nội dung và gắn URL tải.
- Dữ liệu demo được lưu trong `localStorage` của trình duyệt đang dùng.

## Quan trọng trước khi phát hành công khai
Đây là bản frontend tĩnh, chưa có backend/cơ sở dữ liệu. Mã quản trị trong JavaScript không phải cơ chế bảo mật; người khác có thể xem mã nguồn. Dữ liệu localStorage không đồng bộ giữa người dùng hoặc thiết bị. Các số liệu, tên game và liên kết mạng xã hội trong bản mẫu cần được thay bằng dữ liệu thật của bạn. Để có quản trị thật, đăng nhập an toàn và dữ liệu dùng chung, cần thêm backend (ví dụ Cloudflare Workers + D1 hoặc Supabase) và cấu hình xác thực ở phía máy chủ.

Các mục game/ứng dụng ban đầu là dữ liệu minh họa. Chỉ điền liên kết tới tệp bạn sở hữu hoặc được phép phân phối; kiểm tra tệp và nguồn tải trước khi công khai.
