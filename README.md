# 🚀 Personal Portfolio - Trần Huỳnh Sang

Chào mừng bạn đến với kho lưu trữ mã nguồn Website Hồ sơ cá nhân (Portfolio) của mình! 
Dự án này được xây dựng từ con số 0 với mục đích không chỉ để trưng bày các dự án, kỹ năng (Java Core, SQL, Blockchain...) mà còn là một sân chơi để mình thực hành các kỹ thuật Frontend hiện đại.

🌐 **Xem trang web trực tiếp tại đây:** [https://tranhuynhsang.netlify.app](https://tranhuynhsang.netlify.app)

---

## 🌟 Hành trình xây dựng dự án

Dự án này là một hành trình "lột xác" thú vị:
1. **Khởi đầu:** Bắt đầu từ việc tìm hiểu cấu trúc HTML/CSS cơ bản qua một Template có sẵn.
2. **Refactoring (Tối ưu hóa mã):** Gộp các file CSS rườm rà thành 1 cấu trúc duy nhất để dễ quản lý, áp dụng triệt để phương pháp đặt tên class theo chuẩn **BEM**.
3. **Định hình phong cách:** Chuyển đổi toàn bộ giao diện sang phong cách **Dark Mode** (Nền Xám Than kết hợp Cam Cháy) nam tính, góc cạnh và chuẩn "Dev".
4. **Thêm "gia vị" Tương tác:** Tự tay viết code tạo hiệu ứng nền lơ lửng, thanh kỹ năng chạy ngang (Marquee) và đặc biệt là một **Mini-game Đập Bug** bằng JavaScript thuần để giữ chân người xem.
5. **Đưa lên mây (Deployment):** Tích hợp Web3Forms để nhận email góp ý và thiết lập luồng CI/CD với GitHub & Netlify để website tự động cập nhật mỗi khi sửa code.

---

## 🛠️ Công nghệ & Kỹ thuật áp dụng

Dự án này sử dụng 100% **Front-end thuần (Vanilla)**, không phụ thuộc vào các thư viện nặng nề như Bootstrap hay Tailwind, nhằm tối ưu hóa tốc độ tải trang và hiểu sâu về bản chất của code.

### 1. HTML5 (Cấu trúc & Ngữ nghĩa)
* Sử dụng **Semantic HTML** (`<header>`, `<section>`, `<footer>`) để tối ưu hóa SEO và dễ đọc code.
* Cấu trúc form liên hệ tích hợp Web3Forms (Không cần Backend).
* Tích hợp cấu trúc Timeline cho phần Học vấn & Kinh nghiệm.

### 2. CSS3 (Giao diện & Hiệu ứng)
* **CSS Variables (`:root`)**: Quản lý tập trung toàn bộ mã màu, kích thước font, độ bo góc. Đổi toàn bộ màu web chỉ bằng cách sửa 1 dòng code.
* **BEM (Block Element Modifier)**: Đặt tên class rõ ràng, chống xung đột CSS (VD: `.project-card__content`, `.btn--primary`).
* **Flexbox & CSS Grid**: Bố cục trang web được chia lưới (2 cột trên Desktop, 1 cột trên Mobile), đảm bảo độ hiển thị hoàn hảo trên mọi kích thước màn hình (**Fully Responsive**).
* **Glassmorphism**: Ứng dụng `backdrop-filter: blur` để tạo hiệu ứng thẻ kính mờ ảo cho các thành phần UI.
* **Keyframe Animations**: Xử lý các chuyển động phức tạp như: 
  * Ánh sáng lơ lửng (`floatGlow`).
  * Thanh kỹ năng cuộn vô cực (`move-left`).
  * Các khối nội dung từ từ xuất hiện khi load trang (`fadeUp`).

### 3. Vanilla JavaScript (Logic tương tác)
* Thao tác trực tiếp với DOM (DOM Manipulation).
* Sử dụng `setInterval` và `setTimeout` để tạo vòng lặp tính toán vị trí ngẫu nhiên cho Mini-game "Bug Smasher".
* Xử lý sự kiện click chuột và hệ thống tính điểm tương tác trực tiếp.

### 4. Công cụ (Tools & Deployment)
* **Trình soạn thảo:** Visual Studio Code.
* **Quản lý phiên bản:** Git & GitHub.
* **Hosting & CI/CD:** Netlify.
* **Xử lý Form:** API Web3Forms.

---

## 📚 Hướng dẫn cài đặt & Triển khai (Dành cho người tham khảo)

Nếu bạn muốn clone (nhân bản) dự án này về để làm một chiếc CV cho riêng mình, hãy làm theo các bước sau:

 Bước 1: Clone dự án
Mở Terminal và chạy lệnh sau để kéo code về máy:
git clone [https://github.com/HuynhSang-IT/Ten-Kho-Cua-Ban.git](https://github.com/HuynhSang-IT/Ten-Kho-Cua-Ban.git)
 Bước 2: Tùy chỉnh thông tin cá nhân
Mở file index.html và chỉnh sửa lại các thông tin:
Thẻ <h1>, <p> để đổi tên và giới thiệu.
Thêm/Bớt các khối <div class="timeline-item"> để thay đổi lộ trình học vấn.
Thay link ảnh trong thư mục assets.
 Bước 3: Thiết lập gửi Form về Email của bạn
Truy cập Web3Forms.
Nhập Email của bạn vào để nhận Access Key.
Mở file index.html, tìm dòng <input type="hidden" name="access_key" value="..."> và thay Value bằng Key của bạn.
 Bước 4: Triển khai (Deploy) lên Netlify
Đẩy code của bạn lên một kho GitHub cá nhân.
Đăng nhập vào Netlify, chọn Add new site -> Import from GitHub.
Chọn kho code chứa trang web này.
Bấm Deploy. Từ giờ, mỗi khi bạn lệnh git push lên GitHub, Netlify sẽ tự động nhận diện và cập nhật website của bạn ngay lập tức!
📬 Liên hệ
Tác giả: Trần Huỳnh Sang
Email: sang123567tqs@gmail.com
Định hướng: Java Backend Developer | Blockchain Enthusiast
Nếu bạn thấy giao diện này thú vị, đừng quên để lại một ⭐ cho repository này nhé!
