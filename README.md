# 🌸 Dành tặng Nị, cả một vườn thương - 20/10

Dự án trang web tương tác chúc mừng 20/10 dành riêng cho Nị, sẵn sàng để đẩy lên **GitHub** và deploy lên **Vercel**.

---

## 📁 Cấu trúc thư mục chuẩn Vercel

```text
vuon-thuong-20-10/
├── index.html               # Trang chính (Vercel tự động nhận diện làm trang chủ)
├── vercel.json              # Cấu hình tối ưu tốc độ tải ảnh & nhạc trên Vercel CDN
├── README.md                # Hướng dẫn sử dụng & deploy
└── assets/
    ├── images/              # Chứa 4 bức ảnh của Nị
    │   ├── ni-1.jpg
    │   ├── ni-2.jpg
    │   ├── ni-3.jpg
    │   └── ni-4.jpg
    └── music/               # Chứa nhạc nền
        └── bg-music.mp3
```

---

## 🖼️ Cách thay ảnh và nhạc của bạn

1. **Thay ảnh của người yêu**:
   - Chọn 4 bức ảnh đẹp nhất của Nị, đổi tên thành `ni-1.jpg`, `ni-2.jpg`, `ni-3.jpg`, `ni-4.jpg` rồi chép vào thư mục `assets/images/`.
   - *(Nếu ảnh của bạn có đuôi `.png` hoặc bạn muốn thêm nhiều hơn 4 bức ảnh, chỉ cần sửa danh sách `USER_CONFIG.photos` ở dòng ~558 trong `index.html`)*.
2. **Thay nhạc nền**:
   - Đổi tên bài hát `.mp3` bạn muốn dùng thành `bg-music.mp3` rồi chép vào thư mục `assets/music/`.
   - *(Nếu bạn chưa bỏ file `.mp3` vào, trang web đã tích hợp sẵn **Hộp nhạc Piano Music Box tự động** phát giai điệu lãng mạn ngay khi chạm vào bông hoa đầu tiên).*

---

## 🚀 Cách đẩy lên GitHub và Deploy lên Vercel

### Bước 1: Đẩy code lên GitHub
Mở Terminal / PowerShell tại thư mục `D:\chuyên để\vuon-thuong-20-10` và chạy:
```bash
git init
git add .
git commit -m "Vườn hoa 20/10 dành tặng Nị"
git branch -M main
git remote add origin https://github.com/<ten-tai-khoan-cua-ban>/<ten-repo>.git
git push -u origin main
```

### Bước 2: Deploy lên Vercel (Miễn phí, có link gửi ngay)
1. Truy cập [https://vercel.com](https://vercel.com) và đăng nhập bằng tài khoản **GitHub**.
2. Bấm **Add New...** $\rightarrow$ **Project**.
3. Chọn repository bạn vừa tạo và bấm **Import** $\rightarrow$ **Deploy**.
4. Chỉ sau ~15 giây, Vercel sẽ cấp cho bạn một đường link dạng `https://vuon-thuong-ni.vercel.app` để gửi tặng người yêu!
