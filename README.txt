SỔ TỪ DỄ NHẦM HSK 6: BỘ FILE ĐƯA LÊN WEB

Cấu trúc (giữ nguyên, để cùng một thư mục):
  index.html              trang chính (toàn bộ app nằm trong file này)
  manifest.webmanifest    khai báo app cài được (tên, màu, icon)
  sw.js                   chạy offline sau lần mở đầu
  icons/                  icon 192, 512, maskable, apple-touch, favicon

Đưa lên web (chọn một):
  GitHub Pages:  tạo repo, tải cả thư mục này lên, Settings > Pages > chọn nhánh main, thư mục root.
  Netlify:       vào app.netlify.com/drop, kéo thả cả thư mục này vào.
  Cloudflare Pages / Vercel: tạo project mới, tải thư mục này lên, không cần lệnh build.

Lưu ý:
  - Phải mở qua https (các dịch vụ trên đều có sẵn). Mở thẳng file trên máy thì app vẫn chạy nhưng không cài được.
  - Điểm làm bài và đánh dấu lưu trong trình duyệt của từng người (localStorage), không đồng bộ giữa các máy.
  - Khi đăng bản mới, đổi VERSION trong sw.js (ví dụ so-tu-v12) để người dùng nhận bản mới.
  - Cài như app: Chrome/Edge chọn "Cài đặt ứng dụng"; iPhone mở bằng Safari > Chia sẻ > Thêm vào MH chính.
