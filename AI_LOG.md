# Nhật ký sử dụng AI

Nhật ký này chỉ ghi điều có trong mã nguồn, lịch sử Git và yêu cầu thực tế. Không có bản ghi gốc về việc dùng AI cho lần sửa đường dẫn ngày 2026-10-30, vì vậy không suy đoán prompt, phản hồi hay quyết định cá nhân của người sửa ở lần đó.

## 2026-10-30 - Sửa đường dẫn tài nguyên

- **Hiện tượng và dữ kiện ban đầu:** Bản ghi cũ `AI_log.md` nêu “không hiện css”, “ảnh dự án bị lỗi” và “sai đường dẫn avtar”. Trước commit sửa, đường dẫn CSS và ảnh dùng đường dẫn không phù hợp với cấu trúc thư mục khi chạy GitHub Pages dạng project site.
- **Nhận định trước AI:** Không có nhận định trước AI trong bản ghi cũ; không thể khôi phục từ repository.
- **Công cụ/prompt/phản hồi AI:** Không có dữ kiện về công cụ, prompt hoặc phản hồi AI cho lần sửa này. Không kết luận rằng lần sửa có hoặc không dùng AI.
- **Gợi ý AI:** Không có dữ kiện để xác định.
- **Quyết định có lý do:** Không có ghi chép về người đưa ra quyết định hoặc lý do tại thời điểm sửa. Chỉ có thể xác nhận thay đổi được lưu trong commit `0e4c0c9`.
- **Phần sửa được ghi nhận:** `index.html` và `ket-qua.html` tham chiếu `css/style.css`; trang chính tham chiếu ảnh `assets/images.png` và `assets/du-an-1.svg`.
- **Thử lại và kết quả:** Bản ghi ban đầu không lưu kết quả kiểm thử. Trong lần cập nhật nhật ký này, URL Pages và các tài nguyên triển khai được kiểm tra bằng HTTP; kết quả cụ thể ở mục 2026-10-31.

## 2026-10-31 - Cập nhật tài liệu bàn giao

- **Hiện tượng và dữ kiện ban đầu:** `README.md` chỉ có tiêu đề `K20_Lab6`; nhật ký cũ chỉ ghi các triệu chứng và một câu về thay đổi. Repository có `index.html`, `ket-qua.html`, CSS trong `css/`, ảnh trong `assets/`; form liên hệ gửi GET tới trang kết quả và ghi rõ không gửi email/lưu dữ liệu. Yêu cầu bàn giao chỉ định README, nhật ký AI tên `AI_LOG.md` và ghi chú phiên bản v7.
- **Nhận định trước AI:** Không có bản tự đánh giá riêng của sinh viên được lưu trước phiên này. Dữ kiện kỹ thuật được đối chiếu trực tiếp với mã nguồn; không tự ghi nhận định này như lời nói trước AI của sinh viên.
- **Công cụ/prompt:** Trợ lý AI Copilot trong phiên này; yêu cầu của người dùng là tạo/cập nhật `README.md`, `AI_LOG.md` và `RELEASE_NOTES.md` theo các mục bàn giao, phù hợp với sản phẩm thực tế.
- **Gợi ý AI:** Đối chiếu HTML, CSS, assets, lịch sử Git và URL đang xuất bản; ghi cách chạy/kiểm tra, liên kết tới commit cụ thể, đồng thời nêu rõ giới hạn của form và phần nào chưa có bằng chứng.
- **Quyết định và lý do:** Yêu cầu của người dùng chọn thống nhất tên `AI_LOG.md` và yêu cầu mô tả đúng sản phẩm. Bản ghi lần này giữ các giới hạn đã thể hiện trong mã, trỏ tới commit ứng dụng hiện có và không tạo prompt, kết quả kiểm thử hay tag phát hành không có bằng chứng. Các nội dung do AI tổng hợp cần người làm bài đọc lại trước khi nộp.
- **Phần sửa:** Viết lại README với cấu trúc repo, cách chạy local, nguồn Pages và các bước kiểm tra; thống nhất tên nhật ký thành `AI_LOG.md`; thêm ghi chú bàn giao v7.
- **Thử lại và kết quả:** GET tới URL Pages gốc, `index.html`, `ket-qua.html`, `css/style.css`, `assets/images.png` và ba ảnh `assets/du-an-1.svg`, `assets/du-an-2.svg`, `assets/du-an-3.svg` đều trả HTTP 200; yêu cầu HEAD tới repository cũng trả HTTP 200. API đọc cấu hình Pages trả 404 nên không xác nhận được nhánh/thư mục trong Settings. Chưa thực hiện kiểm thử tương tác trên trình duyệt; HTTP 200 chỉ xác nhận tài nguyên được phục vụ.
