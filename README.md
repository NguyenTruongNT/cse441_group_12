# 📱 [Tên Đề Tài / Ứng Dụng - Chờ nhóm thống nhất]

> **Môn học:** Phát triển ứng dụng cho các thiết bị di động (CSE441)  
> **Nhóm thực hiện:** Nhóm 12  
> **Nền tảng:** [Chờ cập nhật...]  

---

## 📖 1. Giới thiệu dự án

* **Mục tiêu của ứng dụng:** [Mô tả bài toán thực tế và giá trị mang lại cho người dùng - Chờ cập nhật]
* **Đối tượng người dùng hướng đến:** [Chờ cập nhật]

### 🌟 Các tính năng cốt lõi dự kiến
* 🔹 **Tính năng 1:** [Chờ cập nhật sau khi chốt đề tài]
* 🔹 **Tính năng 2:** [Chờ cập nhật sau khi chốt đề tài]
* 🔹 **Tính năng 3:** [Chờ cập nhật sau khi chốt đề tài]
* 🔹 **Tính năng 4:** [Chờ cập nhật sau khi chốt đề tài]

---

## 👥 2. Danh Sách Thành Viên và Phân Chia Vai Trò

| STT | Họ và Tên | Mã Sinh Viên (MSSV) | Vai Trò | Nhiệm Vụ Phụ Trách | GitHub Profile |
|:---:|:---|:---:|:---:|:---|:---|
| 1 | **Nguyễn Văn Trường** | 2351170625 | Trưởng nhóm (Team Leader) | [Chờ phân công sau khi chốt đề tài] | [NguyenTruongNT](https://github.com/NguyenTruongNT) |
| 2 | **Vũ Tuấn Khanh** | 2251172386 | Thành viên | [Chờ phân công sau khi chốt đề tài] | [@username](https://github.com/) |
| 3 | **Đinh Trọng Nhật** | 2351060476 | Thành viên | [Chờ phân công sau khi chốt đề tài] | [@username](https://github.com/) |
| 4 | **Vũ Hải Đăng** | 2351170580 | Thành viên | [Chờ phân công sau khi chốt đề tài] | [@username](https://github.com/) |
| 5 | **Lý Đình Sơn** | 2351170615 | Thành viên | [Chờ phân công sau khi chốt đề tài] | [@username](https://github.com/) |

*(Ghi chú: Sau khi nhóm họp và thống nhất đề tài, các thành viên sẽ cùng phân chia cụ thể các phần việc vào cột này).*

---

## 🛠️ 3. Công Nghệ và Môi Trường Phát Triển

* **Framework / Ngôn ngữ:** [Chờ cập nhật...]
* **Kiến trúc ứng dụng:** [Chờ cập nhật...]
* **Cơ sở dữ liệu:** [Chờ cập nhật...]
* **Quản lý trạng thái (State Management):** [Chờ cập nhật...]
* **Công cụ thiết kế UI/UX:** [Figma / Chờ cập nhật...]

---

## 📁 4. Cấu trúc thư mục dự án (Dự kiến)

```text
cse441_group_12/
├── .github/                      # GitHub configurations & templates
│   └── pull_request_template.md  # Template cho Pull Request
├── assets/                       # Tài nguyên hình ảnh, biểu tượng, fonts
│   ├── icons/
│   └── images/
├── lib/                          # Mã nguồn chính
│   ├── core/                     # Thành phần dùng chung toàn app
│   ├── data/                     # Tầng dữ liệu (Models, Repositories)
│   └── presentation/             # Tầng giao diện (Screens, Widgets)
├── .gitignore                    # Các file/thư mục bỏ qua khi commit
└── README.md                     # Tài liệu giới thiệu dự án
```
*(Cấu trúc này sẽ được điều chỉnh cụ thể theo framework nhóm lựa chọn)*

---

## 🚀 5. Hướng dẫn cài đặt & Khởi chạy

### Yêu cầu tiên quyết (Prerequisites)
* Đã cài đặt [Flutter SDK](https://docs.flutter.dev/get-started/install) (Khuyến nghị bản Stable >= 3.x).
* Đã cấu hình [Android Studio](https://developer.android.com/studio) hoặc [Visual Studio Code](https://code.visualstudio.com/) với Flutter extension.
* Máy ảo (Android Emulator) hoặc thiết bị thật đã bật tính năng USB Debugging.

### Các bước khởi chạy

1. **Clone repository về máy:**
   ```bash
   git clone https://github.com/NguyenTruongNT/cse441_group_12.git 
   cd cse441_group_12 
   ```

2. **Cài đặt các gói phụ thuộc (Dependencies):**
   ```bash
   flutter pub get
   ```

3. **Kiểm tra thiết bị kết nối:**
   ```bash
   flutter devices
   ```

4. **Chạy ứng dụng:**
   ```bash
   flutter run
   ```

---

## 🌿 6. Quy trình phối hợp & Đóng góp mã nguồn (Git Workflow)

Để đảm bảo tính nhất quán, tránh xung đột code (conflict) và kiểm soát chất lượng, các thành viên **bắt buộc tuân thủ quy trình sau**:

### 6.1. Quy tắc nhánh (Branching Strategy)
* Nhánh `main`: Nhánh chứa mã nguồn ổn định nhất, chỉ cập nhật thông qua Pull Request được duyệt. **Không commit trực tiếp lên `main`**.
* Nhánh tính năng: Mỗi thành viên tạo nhánh riêng xuất phát từ `main` theo cú pháp:
  * `feature/<tên-tính-năng>` (VD: `feature/add-expense-screen`, `feature/sqlite-storage`)
  * `fix/<tên-lỗi>` (VD: `fix/chart-overflow-bug`)

### 6.2. Các bước đóng góp code
1. **Lấy code mới nhất từ nhánh `main`:**
   ```bash
   git checkout main
   git pull origin main
   ```
2. **Tạo nhánh làm việc mới:**
   ```bash
   git checkout -b feature/ten-tinh-nang
   ```
3. **Thực hiện code, kiểm tra và commit:**
   ```bash
   git add .
   git commit -m "feat: mo ta ngan gon ve tinh nang"
   ```
   *Tuân thủ Conventional Commits (`feat:`, `fix:`, `refactor:`, `docs:`, `ui:`).*
4. **Đẩy nhánh lên GitHub:**
   ```bash
   git push origin feature/ten-tinh-nang
   ```
5. **Tạo Pull Request (PR):**
   * Truy cập GitHub Repository và bấm **Compare & pull request**.
   * Điền mô tả theo mẫu có sẵn, gán Nhóm trưởng / Thành viên khác làm **Reviewer**.
   * Sau khi được kiểm tra và duyệt (Approved), tiến hành merge vào `main`.
