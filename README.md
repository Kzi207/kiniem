Web App Lưu Giữ Kỷ Niệm Tình Yêu

📌 Giới Thiệu
"Kỷ Niệm Của Chúng Ta" là một ứng dụng web cá nhân giúp bạn:

Lưu giữ những khoảnh khắc đáng nhớ trong tình yêu

Chia sẻ cảm xúc một cách sáng tạo và lãng mạn

Tổ chức các kỷ niệm, sự kiện quan trọng theo dòng thời gian

🔹 Dành riêng cho người bạn yêu thương
🔹 Giao diện đẹp mắt, dễ sử dụng
🔹 Bảo mật riêng tư, không lưu dữ liệu lên server

🚀 Cách Sử Dụng
1. Truy Cập Ứng Dụng
Mở file index.html bằng trình duyệt (Chrome, Firefox, Edge)

Mật khẩu mặc định: 09112009 (có thể thay đổi trong code)

2. Các Tính Năng Chính
Tính Năng	Mô Tả
🏠 Trang Chủ	Tổng quan về các kỷ niệm, ngày đặc biệt
📸 Ký Ức	Xem lại hình ảnh, video và ghi chú kỷ niệm
⏳ Đếm Ngày Yêu	Theo dõi thời gian bên nhau (ngày, giờ, phút, giây)
🎵 Nhạc Yêu Thích	Phát nhạc với playlist riêng của hai người
💌 Thư Tình	Viết và lưu trữ những lá thư ngọt ngào
📜 Lỗi Của Anh	Ghi lại những lần "phạm lỗi" và lời hứa
3. Cách Thêm Dữ Liệu Mới
Thêm ảnh: Đặt file vào thư mục img/ và cập nhật trong appData.memories

Thêm nhạc: Đặt file MP3 vào music/ và thêm vào appData.songs

Viết thư mới: Nhấn "Gửi thư" trong tab Thư Tình

🛠 Cài Đặt & Tùy Chỉnh
Yêu Cầu Hệ Thống
Trình duyệt hiện đại (Chrome, Firefox, Edge)

Kết nối Internet để tải thư viện (Font Awesome, Google Fonts)

Cấu Trúc Thư Mục
text
love-memories/
├── index.html          # Trang chính
├── img/                # Thư mục hình ảnh
│   ├── avtnam.jpg      # Ảnh đại diện của bạn
│   ├── avtnu.jpg       # Ảnh đại diện người yêu
│   └── ...             # Các ảnh kỷ niệm
├── music/              # Thư mục nhạc
│   ├── song1.mp3       # Bài hát yêu thích
│   └── ...             # Các bài hát khác
└── README.md           # Hướng dẫn sử dụng
Tùy Chỉnh Cá Nhân
Đổi mật khẩu:

javascript
// Trong file HTML, tìm dòng:
const correctPasscode = '09112009'; // Thay bằng mật khẩu mới
Thêm kỷ niệm mới:

javascript
memories: [
  {
    id: 4,  // Tăng số này lên
    title: "Tên kỷ niệm",
    date: "DD/MM/YYYY",
    image: "img/tên-file-ảnh.jpg",
    description: "Mô tả ngắn gọn..."
  }
]
Thêm bài hát:

javascript
songs: [
  {
    title: "Tên bài hát",
    artist: "Tên ca sĩ",
    src: "music/tên-file-nhạc.mp3",
    cover: "URL-ảnh-bìa"
  }
]
🔒 Bảo Mật & Riêng Tư
Mật khẩu bảo vệ ứng dụng

Không lưu dữ liệu lên server (chỉ lưu trên trình duyệt)

Chống sao chép nội dung (Ctrl+C, chuột phải bị vô hiệu hóa)

📥 Tải Xuống & Chạy Ứng Dụng
Tải toàn bộ thư mục (bao gồm index.html, img/, music/)

Mở file index.html bằng trình duyệt

Nhập mật khẩu và bắt đầu sử dụng!

💖 Dành tặng người bạn yêu thương!

Tác giả: Khánh Duy
Liên hệ: https://www.facebook.com/kzi207

"Tình yêu không phải là nhìn chằm chằm vào nhau, mà là cùng nhau hướng về một hướng." ❤️
