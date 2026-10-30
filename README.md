# Portfolio CV - Phạm Văn Việt Hùng

Portfolio cá nhân giới thiệu thông tin, kỹ năng, dự án và quá trình học tập của Phạm Văn Việt Hùng. Đây là website tĩnh viết bằng HTML và CSS; form liên hệ chỉ minh họa kiểm tra dữ liệu và trang kết quả, không gửi email hay lưu dữ liệu.

## Liên kết

- **Website:** [GitHub Pages](https://phamhung16.github.io/K20_Portfolio_CNTT20_04/)
- **Mã nguồn:** [Phamhung16/K20_Portfolio_CNTT20_04](https://github.com/Phamhung16/K20_Portfolio_CNTT20_04)
- **Hồ sơ GitHub:** [Phamhung16](https://github.com/Phamhung16)
- **Mã nguồn ứng dụng được bàn giao:** [commit 0e4c0c9](https://github.com/Phamhung16/K20_Portfolio_CNTT20_04/commit/0e4c0c9c86e4893a3ee0ab4b572e6ae32f00bb76)
- **Tài liệu:** [AI_LOG.md](AI_LOG.md) · [RELEASE_NOTES.md](RELEASE_NOTES.md)

## Cấu trúc thư mục

```text
.
├── index.html          # Trang portfolio và form liên hệ
├── ket-qua.html        # Trang kết quả của form
├── README.md
├── AI_LOG.md           # Nhật ký sử dụng AI và quyết định
├── RELEASE_NOTES.md    # Ghi chú bản bàn giao v7
├── assets/
│   ├── images.png      # Ảnh đại diện đang dùng
│   ├── avatar.svg      # Ảnh SVG có sẵn
│   └── du-an-1.svg ... du-an-3.svg
└── css/
    ├── README.md
    └── style.css       # Giao diện và responsive
```

## Chạy trên máy

Không cần cài thư viện hay build. Từ thư mục gốc của repository, chạy máy chủ tĩnh:

```powershell
py -m http.server 8000
```

Mở <http://localhost:8000/>. Có thể mở trực tiếp `index.html` bằng trình duyệt, nhưng máy chủ tĩnh giúp kiểm tra các đường dẫn trang và tài nguyên nhất quán hơn. Google Fonts cần kết nối Internet; nếu ngoại tuyến, trang dùng font dự phòng.

## Nguồn xuất bản

Website đang được phục vụ tại GitHub Pages ở liên kết phía trên. Mã trang nằm ở thư mục gốc của nhánh `main` và repository không có bước build. URL Pages phản hồi HTTP 200; API cấu hình Pages trả 404 nên nhánh/thư mục xuất bản trong Settings chưa được xác minh độc lập.

## Cách kiểm tra trang và chức năng

1. Mở `index.html`; kiểm tra CSS, ảnh đại diện và ba hình minh họa dự án hiển thị.
2. Dùng menu để chuyển tới **Giới thiệu**, **Kỹ năng**, **Dự án**, **Học tập** và **Liên hệ**; thu nhỏ cửa sổ để kiểm tra bố cục responsive.
3. Trong form liên hệ, thử gửi để trống hoặc nhập email sai để thấy kiểm tra HTML5. Nhập họ tên từ 2 ký tự, email hợp lệ và lời nhắn từ 10 đến 500 ký tự rồi gửi.
4. Form dùng `GET` và chuyển tới `ket-qua.html`. Kiểm tra trang kết quả và lưu ý dữ liệu có thể hiện trên URL; form không gửi email và không lưu dữ liệu lên máy chủ.
5. Mở trực tiếp `ket-qua.html` để kiểm tra trang kết quả; dùng nút quay lại để trở về form.

## Hồ sơ và minh chứng

- Hồ sơ tác giả: [github.com/Phamhung16](https://github.com/Phamhung16)
- Repository: [github.com/Phamhung16/K20_Portfolio_CNTT20_04](https://github.com/Phamhung16/K20_Portfolio_CNTT20_04)
- Bản mã ứng dụng đã đối chiếu: [commit 0e4c0c9](https://github.com/Phamhung16/K20_Portfolio_CNTT20_04/commit/0e4c0c9c86e4893a3ee0ab4b572e6ae32f00bb76)
- Bản chạy: [GitHub Pages](https://phamhung16.github.io/K20_Portfolio_CNTT20_04/)

Các thẻ dự án hiện là nội dung giới thiệu, liên kết dự án riêng chưa được cung cấp; không xem các dòng chữ đó là liên kết có thể bấm.
