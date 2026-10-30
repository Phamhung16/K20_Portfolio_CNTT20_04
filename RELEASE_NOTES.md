# RELEASE NOTES

## Portfolio CV - v7 bàn giao

- **Ngày cập nhật tài liệu:** 2026-10-31 (UTC+08:00)
- **Mã phiên bản:** v7, nhãn bàn giao theo yêu cầu. Repository hiện không có tag hoặc cơ chế version riêng.
- **Tác giả:** Phạm Văn Việt Hùng
- **Repository:** [Phamhung16/K20_Portfolio_CNTT20_04](https://github.com/Phamhung16/K20_Portfolio_CNTT20_04)
- **Bản mã ứng dụng tham chiếu:** [commit 0e4c0c9c86e4893a3ee0ab4b572e6ae32f00bb76](https://github.com/Phamhung16/K20_Portfolio_CNTT20_04/commit/0e4c0c9c86e4893a3ee0ab4b572e6ae32f00bb76)
- **Bản chạy:** [GitHub Pages](https://phamhung16.github.io/K20_Portfolio_CNTT20_04/)

### Thay đổi chính

- Hoàn thiện portfolio CV tĩnh gồm trang giới thiệu, kỹ năng, dự án, học tập và liên hệ.
- Bổ sung trang kết quả cho form liên hệ thực hành.
- Cập nhật đường dẫn CSS và ảnh theo cấu trúc thư mục, phù hợp với URL dạng project site của GitHub Pages.
- Bổ sung hướng dẫn mở, chạy và kiểm tra sản phẩm trong [README.md](README.md), cùng nhật ký AI tại [AI_LOG.md](AI_LOG.md).

### Lỗi đã sửa

Commit `0e4c0c9` sửa đường dẫn stylesheet bị sai ở hai trang HTML, đường dẫn ảnh đại diện và hình minh họa dự án đầu tiên. Bản ghi sửa lỗi có trong [commit](https://github.com/Phamhung16/K20_Portfolio_CNTT20_04/commit/0e4c0c9c86e4893a3ee0ab4b572e6ae32f00bb76).

### Hạn chế còn lại

- Form chỉ kiểm tra dữ liệu bằng HTML5 và chuyển dữ liệu bằng GET; không gửi email, không có máy chủ và không lưu dữ liệu. Giá trị nhập có thể xuất hiện trên URL.
- Các liên kết GitHub riêng trong thẻ dự án vẫn là nội dung chờ cập nhật, không phải liên kết có thể bấm.
- Google Fonts cần Internet; trình duyệt dùng font dự phòng khi ngoại tuyến.
- v7 là nhãn bàn giao trong tài liệu, không phải Git tag. Commit được dẫn ở trên là commit ứng dụng đã có trong repository; các tài liệu bàn giao mới cần được lưu cùng bản nộp cuối.

### Tiếp tục kiểm tra và bàn giao

1. Mở [website GitHub Pages](https://phamhung16.github.io/K20_Portfolio_CNTT20_04/) và kiểm tra ảnh, CSS, menu, responsive cùng form theo [README.md](README.md).
2. Thử gửi form thiếu trường hoặc sai email, sau đó gửi dữ liệu hợp lệ; xác nhận trang `ket-qua.html` mở và URL GET có thể chứa dữ liệu.
3. Nếu cập nhật source, kiểm tra lại các đường dẫn tương đối trên Pages và cập nhật liên kết tới commit thực tế được nộp. Không ghi nhận kết quả kiểm thử tương tác nếu chưa thực hiện.
