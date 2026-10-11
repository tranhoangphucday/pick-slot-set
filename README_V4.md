# README — Meme Set Matcher V4

## Giới thiệu
Meme Set Matcher V4 là website HTML dùng để quản lý người tham gia, nhập số lượng card và ghép full set. Phiên bản này không yêu cầu đăng nhập.

## Mở website
1. Tải file `Meme_Set_Matcher_Code_Tong_v4.html`.
2. Mở file bằng Chrome, Edge hoặc trình duyệt hiện đại.
3. Chọn mục trên thanh điều hướng để quản lý card, người tham gia, kết quả và lịch sử.

## Chức năng chính
- **Thêm người:** tạo hồ sơ và nhập số lượng từng loại card.
- **Thêm loại card:** dùng nút `＋ Thêm loại card` trên Tổng quan hoặc trong mục Card.
- **Xóa loại card:** dùng nút `🗑 Xóa loại card`; nhập số thứ tự loại cần xóa rồi xác nhận.
- **Đổi tên loại card:** quản lý tên loại card trong mục Card nếu phiên bản giao diện có chức năng tương ứng.
- **Ghép full set:** bấm `Chạy ghép set`; Random có thể bù một vị trí thiếu trong full set.
- **Nhập/Xuất CSV:** dùng để nhập dữ liệu hoặc sao lưu hồ sơ.

## Quy tắc ghép
Một full set cần đủ mọi loại card bắt buộc hiện đang được cấu hình. Card Random có thể thay cho một vị trí thiếu; mỗi card Random chỉ được sử dụng một lần.

## Lưu dữ liệu và sao lưu
- Dữ liệu lưu trong trình duyệt trên thiết bị hiện tại bằng `localStorage`.
- Dữ liệu không tự đồng bộ giữa các thiết bị hoặc các trình duyệt.
- Bấm `Xuất CSV` trước khi xóa nhiều card hoặc thay đổi dữ liệu quan trọng.
- Nếu xóa dữ liệu website trong trình duyệt, dữ liệu đã lưu cục bộ có thể mất.

## Khắc phục nhanh
- Nếu không thấy nút mới, hãy mở đúng file V4 vừa tải.
- Nếu trang không phản hồi, tải lại trang và thử mở bằng Chrome/Edge.
- Giữ file CSV xuất ra làm bản dự phòng.
