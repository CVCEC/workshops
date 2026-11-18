# workshops.cvcec.org — 12 Con Giáp · Vietnamese Woodblock Workshop

Landing page song ngữ Anh – Việt cho workshop in mộc bản 12 con giáp
(CVCEC × VICEE, nghệ nhân Nguyễn Công Đạt – làng Thanh Liễu),
Chủ nhật 06.12.2026, 14:00, số 24 ngõ 123 Kim Quan Thượng, Long Biên, Hà Nội.

Trang tĩnh, không cần build: mở `index.html` là chạy. Xuất từ bản thiết kế Claude Design.

## Cấu trúc
- `index.html` — toàn bộ trang (HTML + CSS + JS trong một file)
- `assets/` — ảnh và logo
- `assets/process/` — 10 ảnh phần Quy trình (xem `assets/process/README.txt`)
- `CNAME` — tên miền `workshops.cvcec.org` cho GitHub Pages
- `.nojekyll` — để GitHub Pages phục vụ file nguyên trạng

## Hai chỗ còn để trống (tìm trong index.html)
1. `[Registration form link]` — thay bằng link form đăng ký; đồng thời đổi `href="#register"`
   của nút **Register now · Đăng ký ngay** thành link đó.
2. `[link / QR code / email]` — cách nhận bài học sau workshop.

## Tính năng tương tác
- Ô nhập năm sinh → con giáp, câu “Tôi tuổi …” có nút nghe.
- Bài 1: điền động từ (kéo thả trên máy tính, chạm để chọn – chạm để đặt trên iPad/điện thoại), nút Kiểm tra.
- Bài 2: nối 10 từ Việt – Anh.
- Nút loa dùng giọng tiếng Việt có sẵn của trình duyệt (Web Speech API, `vi-VN`).

## Tên miền
DNS tại Nhân Hòa: bản ghi **CNAME** `workshops` → `cvcec.github.io`.
GitHub: Settings › Pages › Deploy from a branch › `main` / `(root)`; Custom domain `workshops.cvcec.org`; bật Enforce HTTPS.

© 2026 Canada Vietnam Cultural & Educational Council (CVCEC) & VICEE. Nội dung quy trình và ảnh phần Process: Mộc bản Thanh Liễu.
