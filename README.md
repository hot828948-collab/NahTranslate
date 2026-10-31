<div align="center">

# 🌍 Nah.translate

<img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
<img src="https://img.shields.io/badge/Language-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/UI-Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Beta-orange?style=for-the-badge" />

*Ứng dụng dịch thuật di động hiện đại, thông minh và tối ưu hóa trải nghiệm ngoại tuyến cho Android.*

[Tính năng](#-tính-năng-nổi-bật) • [Cơ chế cập nhật](#-cơ-chế-kiểm-tra-cập-nhật-ota) • [Nhóm phát triển](#-đội-ngũ-phát-triển)

<img width="200" height="200" alt="1792897529569_1660190258815017049_1660190258815017049_c3f6b6392eb5e06f094672c802e31bd2" src="https://github.com/user-attachments/assets/0d77042a-1080-4e48-8f91-debce6d2b555" />

</div>

---

## 📖 Giới thiệu dự án

**Nah.translate** là ứng dụng di động được phát triển độc lập sử dụng 100% **Kotlin** và **Jetpack Compose** theo phong cách Material Design. Ứng dụng hướng tới tốc độ xử lý mượt mà, giao diện tối giản hỗ trợ chế độ tối (Dark Mode) linh hoạt, cùng hệ thống tra cứu từ điển và ôn tập ngữ pháp chuyên sâu ngay trong tầm tay.

---

## ✨ Tính năng nổi bật

* 🚀 **Dịch thuật ngoại tuyến (Offline Translation):** Tích hợp Google ML Kit giúp xử lý văn bản nhanh chóng mà không phụ thuộc hoàn toàn vào kết nối mạng.
* 📚 **Sổ tay & Ngữ pháp thông minh:** Hỗ trợ lưu trữ ghi chú cá nhân, tổng hợp hệ thống **12 thì cơ bản trong tiếng Anh** và **50 động từ bất quy tắc** phục vụ ôn tập hiệu quả.
* 🔄 **Cơ chế OTA Updates tự động:** Tự động kết nối với GitHub Releases để kiểm tra phiên bản mới, hiển thị bảng **What's new** trực quan và hỗ trợ tải file `.apk` trực tiếp trong ứng dụng.
* 🎵 **Tiện ích tích hợp đa dạng:** Quản lý dung lượng bộ nhớ thông minh (`AppStorageInfoCard`), trình phát nhạc mini tích hợp (`MusicPlayerCard`) và phím tắt truy cập thư mục dữ liệu hệ thống.

---

## ⚙️ Cơ chế Kiểm tra Cập nhật (GitHub OTA)

Ứng dụng sử dụng hệ thống quản lý phiên bản nhẹ nhàng thông qua tệp `version.json` đặt tại nhánh chính của mã nguồn:

1. **Kiểm tra:** App thực hiện HTTP GET tới link Raw của `version.json` trên GitHub.
2. **Đối chiếu:** So sánh `versionCode` hiện tại trên máy với `versionCode` mới nhất từ máy chủ.
3. **Phản hồi:** Nếu có phiên bản mới, hệ thống kích hoạt hộp thoại thông báo chi tiết thay đổi (`releaseNotes`) kèm đường dẫn tải trực tiếp từ GitHub Releases.

---

## 🛠️ Thông tin kỹ thuật (Tech Stack)

* **Ngôn ngữ lập trình:** Kotlin
* **Giao diện người dùng:** Jetpack Compose (Material 3)
* **Xử lý bất đồng bộ:** Kotlin Coroutines
* **Lưu trữ & Dữ liệu:** Local Room / SharedPreferences & JSON Parsing

---

## 👥 Đội ngũ phát triển

* **Developer:** Tinn
* **Tester:** Dang Huy

---

<div align="center">
  <i>Được phát triển với ❤️ bởi Tinn. Bản quyền thuộc về dự án Nah.translate.</i>
</div>
