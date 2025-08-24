# HelloUnity

Dự án này là một trò chơi 2D đơn giản, sử dụng **Unity Hub** và **Visual Studio**, với mục đích làm quen với các khái niệm cơ bản của phát triển game như quản lý **Scene**, giao diện người dùng (**UI**), và lập trình cơ bản trong Unity.

---

### 💻 Công Nghệ & Công cụ
* **Engine:** Unity
* **Ngôn ngữ:** C#
* **IDE:** Visual Studio

---

### 🎮 Gameplay

* **Mục tiêu:** Nhấn nút `Increase number` để đạt được 100 click.
* **Flow Game:**
    * **StartScene:** Bắt đầu trò chơi bằng cách nhấn nút `Start`.
    * **PlayingScene:** Diễn ra các thao tác chính. Trò chơi có một bộ đếm ngược trước khi bắt đầu.
    * **FinishScene:** Kết thúc trò chơi. Hiển thị kết quả thắng/thua và bảng thành tích.

### ✨ Các Tính Năng

* **Quản lý Scene:** Ba scene riêng biệt (`Start`, `Playing`, `Finish`) để phân chia luồng chơi.
* **UI tương tác:** Các nút bấm (`Start`, `Pause`, `Exit Game`, `Reset`, `Increase number`, v.v.) và các TextView để hiển thị thông tin.
* **Đếm giờ & Thống kê:** Hiển thị tổng số click và tốc độ click trung bình mỗi giây.
* **Hệ thống Thành tích:** Bảng thành tích ghi lại tối đa 10 thành tích nhanh nhất. Người chơi có thể nhập tên hoặc dùng tên mặc định sau khi thắng.

---

### 📜 Cấu trúc Dự án

* `StartScene.unity`
* `PlayingScene.unity`
* `FinishScene.unity`

---

### ⚖ License

Dự án này được phát hành dưới giấy phép **GPL-3.0 license**. Xem file `LICENSE` để biết thêm chi tiết.
