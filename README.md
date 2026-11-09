# Trò chơi ôn tập Tiếng Việt lớp 2 – Bài "Gọi bạn"

Trò chơi 2 đội, chọn đáp án bằng động tác tay:
- ✋ Giơ tay trái = A
- 🤚 Giơ tay phải = B
- 🙌 Giơ hai tay = C

22 câu hỏi, mỗi lượt một bạn đại diện mỗi đội, 30 giây/câu.
Điểm: đúng 100 + thưởng tốc độ tối đa 50, sai hoặc hết giờ 0.

## Cách chạy
Mở file `index.html` bằng trình duyệt (cần mạng để tải phông chữ, không có mạng vẫn chơi được).

## Đăng lên GitHub Pages
1. Tạo repository mới, tải `index.html` và `README.md` lên.
2. Vào Settings > Pages > Source: chọn nhánh `main`, thư mục `/ (root)` > Save.
3. Sau 1-2 phút, trang chạy tại `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

## Sửa câu hỏi
Mở `index.html`, tìm mảng `Q`. Mỗi câu có dạng:
`["Câu hỏi",["Đáp án A","Đáp án B","Đáp án C"],chỉ_số_đúng]` (0 = A, 1 = B, 2 = C).
Đổi thời gian và điểm ở dòng `var TL=30,B=50,P=100;` (giây/câu, điểm thưởng tối đa, điểm đúng).
