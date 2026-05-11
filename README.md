# Portfolio Cá Nhân - Phan Nguyễn Nhân Tâm

## 🎯 Ý tưởng thiết kế tổng thể

Website portfolio cá nhân dành cho Tattoo Designer & Freelancer, tập trung vào phong cách **Cyber Tribal, Dark Lettering, Biomech và Custom Flash**.

- **Tone màu chủ đạo:** Đen + Xanh Navy Blue (#0a0e17, #4a8fe7) — tối, mạnh mẽ, gợi cảm giác cyberpunk/tribal hiện đại.
- **Font chữ:** Poppins (body - dễ đọc) + Merriweather (heading - thanh lịch, cá tính).
- **Bố cục:** Tối giản, rõ ràng, thân thiện với nhà tuyển dụng. Gồm đầy đủ các section: Hero (có ảnh đại diện), About, Projects (2 dự án), Skills (dạng grid card), Contact (có nút social).
- **Tính năng đặc biệt:** Dark/Light mode toggle, animation fadeIn/slideUp, hover glow neon xanh, progress bar có hiệu ứng fill, nút social (Instagram, Facebook, Zalo, X).
- **Responsive:** Hiển thị tốt trên mobile và desktop.

---

## 🤖 Công cụ AI đã sử dụng

| Công cụ | Mục đích sử dụng |
|---|---|
| **ChatGPT** | Hỗ trợ viết code HTML/CSS, debug, tối ưu giao diện, viết nội dung portfolio, tạo cấu trúc dự án, tạo README |
| **Midjourney** | Tham khảo texture biomech, cable cyberpunk, rễ phát sáng neon cho quá trình thiết kế tattoo (dự án "Source Code" và "Neon Roots") |

---

## 📝 Ví dụ Prompt đã sử dụng

### Prompt ChatGPT (code & nội dung):
Tôi cần tạo một portfolio cá nhân cho Tattoo Designer.
Phong cách: Cyber Tribal, Dark Lettering, Biomech, Custom Flash.
Tone màu: Đen + Xanh Navy Blue.
Yêu cầu: Hero (có ảnh đại diện), About, Projects (2 dự án: Source Code & Neon Roots),
Skills dạng grid card, Contact có nút social (IG, FB, Zalo, X).
Có Dark/Light mode toggle, animation mượt, responsive.
Font dễ đọc (Poppins + Merriweather).
Ảnh nền từ Pinterest, ảnh dự án và ảnh đại diện upload trực tiếp.
### Prompt Midjourney (texture tham khảo):
biomech texture, cyberpunk cable pattern,
tribal tattoo line art, dark mechanical,
black and blue, seamless texture reference
--style raw --ar 1:1neon glowing roots, cyberpunk organic vine,
mechanical tendrils, dark background,
blue and purple glow, tattoo reference
--style raw --ar 2:3
---

## 🔧 Quá trình chỉnh sửa kết quả AI

### 1. ChatGPT tạo code ban đầu
- ChatGPT tạo ra bộ khung HTML/CSS cơ bản với đầy đủ section theo yêu cầu.
- Code ban đầu còn thô, font chữ chưa phù hợp, layout chưa tối ưu cho mobile, chưa có Dark/Light mode.

### 2. Chỉnh sửa thủ công
- **Font chữ:** Thử nghiệm nhiều font (Orbitron, Rajdhani, Cinzel, Bebas Neue) và chốt lại Poppins + Merriweather vì dễ đọc nhất, vẫn giữ được cá tính.
- **Màu sắc:** Tinh chỉnh bảng màu đen + xanh navy (#0a0e17, #4a8fe7), thêm hiệu ứng glow neon xanh cho nút và border.
- **Dark/Light mode:** Tự code thêm JavaScript toggle + CSS light mode override cho tất cả thành phần. Nhiều lần debug do text bị mất nét ở light mode.
- **Nội dung About:** Viết lại theo giọng văn cá nhân, tự nhiên hơn, kể về kinh nghiệm thật (sale, tư vấn khách, dùng Midjourney hỗ trợ texture).
- **Dự án "Source Code":** Thêm storytelling đầy đủ (khách hàng 26 tuổi, trầm cảm, tự học code), quy trình 2 buổi chi tiết.
- **Dự án "Neon Roots":** Tự sáng tác thêm dự án thứ 2 (khách dancer, rễ neon cyberpunk), quy trình có dùng Midjourney tham khảo.
- **Skills:** Chuyển thành dạng grid card có icon, progress bar animation fill, hover nổi lên.
- **Contact:** Thêm 4 nút social (Instagram, Facebook, Zalo, X) có icon Font Awesome, hiệu ứng hover.
- **Ảnh đại diện:** Chuyển từ About lên Hero, để dạng hình vuông bo góc, có glow border.
- **Ảnh dự án:** Upload trực tiếp vào repo (source-code.jpg, neon-roots.png) thay vì dùng link ngoài để tránh lỗi 404.
- **Responsive:** Tối ưu breakpoint 700px, chuyển layout dọc, giảm font size, ẩn bớt padding.

### 3. Kết quả AI từ Midjourney
- Texture biomech và rễ neon từ Midjourney được dùng làm **reference**, không copy nguyên.
- Chỉ lấy cảm hứng về bề mặt, đường nét, cách xử lý mảng tối/sáng.
- Tất cả phác thảo và line art đều được vẽ tay lại, đảm bảo tính nguyên bản.

---

## ✨ Tính năng nổi bật

- 🌗 **Dark/Light mode toggle** (nút tròn góc phải màn hình)
- 🧑 **Ảnh đại diện** trên Hero (hình vuông bo góc, glow xanh)
- 📂 **2 dự án** có storytelling chi tiết + ảnh minh họa thật
- 🧩 **Skills dạng grid card** có icon, progress bar, hover animation
- 🔗 **Nút social** (Instagram, Facebook, Zalo, X) có hiệu ứng
- ✨ **Animation** fadeIn/slideUp khi scroll, hover glow
- 📱 **Responsive** đầy đủ cho mobile

---

## 📁 Cấu trúc dự án
portfolio-ca-nhan/
├── index.html # File HTML chính
├── style.css # File CSS (bao gồm Dark/Light mode)
├── Phong.jpg # Ảnh đại diện cá nhân (Hero)
├── source-code.jpg # Ảnh dự án Source Code
├── neon-roots.png # Ảnh dự án Neon Roots
├── README.md # Tài liệu mô tả (file này)
---

## 🌐 Link demo

👉 **https://portfolio-ca-nhan-beta.vercel.app**

---

## 👤 Thông tin cá nhân

- **Họ tên:** Phan Nguyễn Nhân Tâm
- **Vai trò:** Tattoo Designer & Freelancer
- **Trường:** Đại học Gia Định — TP. Hồ Chí Minh
- **Email:** wocphogg006.art@gmail.com
- **Instagram:** @Phznix.3010

---

> *"Your story, my lines."*