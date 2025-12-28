# Amour Swipe  
**Amour Swipe** là ứng dụng di động hẹn hò hiện đại, giúp người dùng tìm kiếm mối quan hệ ý nghĩa thông qua cơ chế **vuốt để ghép đôi** (swipe-to-match) quen thuộc, kết hợp với **tư vấn tình cảm thông minh** từ **LOVE AI**. Ứng dụng mang đến trải nghiệm kết nối an toàn, hiệu quả và thân thiện.
**Ứng dụng hẹn hò thông minh với cơ chế vuốt match và tư vấn AI**

<p align="center">
  <img src="https://via.placeholder.com/1280x640/FF6B6B/FFFFFF?text=Amour+Swipe" alt="Amour Swipe Banner" width="100%"/>
</p>

**Amour Swipe** là ứng dụng di động hẹn hò hiện đại, được thiết kế nhằm mang đến trải nghiệm kết nối tình cảm an toàn, hiệu quả và thông minh. Ứng dụng kết hợp cơ chế **vuốt để ghép đôi** (swipe-to-match) quen thuộc với **tính năng tư vấn AI** mang tên **LOVE AI**, giúp người dùng tự tin hơn trong giao tiếp và xây dựng mối quan hệ ý nghĩa.

Dự án được thực hiện bởi nhóm sinh viên lớp 64HTTT3 – Khoa Công nghệ Thông tin, Trường Đại học Thủy Lợi, trong khuôn khổ môn học **Phát triển ứng dụng di động** dưới sự hướng dẫn tận tình của **Thầy Nguyễn Văn Nam**.

## ✨ Các tính năng chính

- Đăng ký & Đăng nhập an toàn bằng email/mật khẩu  
- Cập nhật hồ sơ cá nhân chi tiết: giới tính, ngày sinh, ảnh đại diện (tải lên hoặc chụp trực tiếp), vị trí GPS  
- Cơ chế vuốt match mượt mà: vuốt phải để thích, vuốt trái để bỏ qua  
- Ghép đôi tự động khi hai người cùng thích  
- Quản lý tương tác: danh sách "Đã thích" và "Lượt thích"  
- Trò chuyện thời gian thực với người đã match  
- **LOVE AI** – Trợ lý AI thông minh hỗ trợ tư vấn tình cảm, gợi ý câu trả lời, giải đáp thắc mắc  
- Xem và chỉnh sửa hồ sơ cá nhân linh hoạt  
- Cài đặt nâng cao: đổi mật khẩu, bật/tắt thông báo, điều chỉnh phạm vi tìm kiếm  
- Giao diện hiện đại, thân thiện, tối ưu trải nghiệm trên thiết bị di động  

## 🛠 Công nghệ sử dụng

| Công nghệ              | Mô tả                                                                 |
|------------------------|-----------------------------------------------------------------------|
| **Java**               | Ngôn ngữ lập trình chính cho ứng dụng Android                         |
| **Android SDK**        | Nền tảng phát triển ứng dụng Android chính thức                       |
| **Firebase**           | Authentication, Firestore (database), Cloud Storage (ảnh), Cloud Messaging (thông báo) |
| **Google Maps API**    | Xác định vị trí GPS và tính năng tìm kiếm theo khoảng cách            |
| **AI Integration**     | Tích hợp mô hình ngôn ngữ lớn (Gemini / OpenAI / tùy chỉnh) cho LOVE AI |
| **Jetpack Compose**    | Thư viện xây dựng giao diện hiện đại (UI toolkit)                     |
| **Room**               | Cơ sở dữ liệu cục bộ (nếu cần cache dữ liệu)                          |
| **Coroutines & Flow**  | Xử lý bất đồng bộ và quản lý luồng dữ liệu                            |
| **Retrofit**           | Gọi API HTTP (nếu tích hợp backend tùy chỉnh)                         |
| **Material Design 3**  | Hệ thống thiết kế giao diện theo chuẩn Google                         |
| **Thiết kế UI/UX**     | Figma – Thiết kế giao diện và prototype                               |

## 📊 Thông tin dự án

| Thông tin                  | Chi tiết                                                                 |
|----------------------------|--------------------------------------------------------------------------|
| **Tên đề tài**             | Ứng dụng Amour Swipe – Ứng dụng hẹn hò thông minh với vuốt match và tư vấn AI |
| **Nhóm thực hiện**         | Đào Việt Chung, Nguyễn Thị Hải Xuân, Đặng Hữu Trưởng (Lớp 64HTTT3)       |
| **Giảng viên hướng dẫn**   | Thầy Nguyễn Văn Nam                                                      |
| **Môn học**                | Phát triển ứng dụng di động                                              |
| **Trường**                 | Trường Đại học Thủy Lợi – Khoa Công nghệ Thông tin                       |

## 👥 Phân công nhiệm vụ chi tiết

| Thành viên              | Nhiệm vụ chính                                                                                           | Công nghệ & Module chính                           |
|-------------------------|----------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| **Đào Việt Chung**      | - Thiết kế và triển khai toàn bộ backend Firebase (Firestore, Storage, Authentication)<br>- Xây dựng hệ thống Authentication (đăng ký, đăng nhập, đổi mật khẩu, bảo mật)<br>- Triển khai chat realtime (tin nhắn giữa người dùng)<br>- Phát triển và tích hợp **LOVE AI** (chatbot tư vấn tình cảm thông minh)<br>- Tối ưu hiệu suất, bảo mật dữ liệu và xử lý bất đồng bộ toàn ứng dụng | Firebase Authentication, Firestore, Cloud Messaging, AI API, Coroutines, Retrofit |
| **Đặng Hữu Trưởng**     | - Triển khai cơ chế vuốt match (swipe screen) – tính năng cốt lõi và nổi bật nhất<br>- Xây dựng logic ghép đôi tự động khi hai người cùng thích<br>- Phát triển danh sách "Đã thích" và "Lượt thích" (quản lý tương tác)<br>- Tích hợp tính năng tải/chụp ảnh hồ sơ (CameraX)<br>- Triển khai xác định vị trí GPS và tìm kiếm theo khoảng cách<br>- Thiết kế prototype trên Figma | Jetpack Compose, Animations, Geolocation, CameraX, Figma |
| **Nguyễn Thị Hải Xuân** | - Xây dựng màn hình đăng ký, đăng nhập, chọn giới tính/ngày sinh<br>- Triển khai màn hình cập nhật hồ sơ cơ bản<br>- Phát triển các màn hình cài đặt (đổi mật khẩu, bật/tắt thông báo, phạm vi tìm kiếm)<br>- Hỗ trợ giao diện danh sách chat và hồ sơ người dùng<br>- Soạn thảo báo cáo và tài liệu dự án | Jetpack Compose, Material Design 3, Documentation  |

## 📱 Giao diện ứng dụng

*(Các ảnh screenshot sẽ được cập nhật sau khi hoàn thiện ứng dụng)*

<p align="center">
  <img src="https://via.placeholder.com/300x600/FF6B6B/FFFFFF?text=Onboarding+Screen" alt="Onboarding" width="200"/>
  <img src="https://via.placeholder.com/300x600/FF6B6B/FFFFFF?text=Swipe+Match" alt="Swipe" width="200"/>
  <img src="https://via.placeholder.com/300x600/FF6B6B/FFFFFF?text=Match+Success" alt="Match Success" width="200"/>
  <img src="https://via.placeholder.com/300x600/FF6B6B/FFFFFF?text=Chat+with+LOVE+AI" alt="LOVE AI" width="200"/>
</p>

## 📄 Tài liệu liên quan

- **Thiết kế giao diện (Figma)**: [Link Figma](https://www.figma.com/file/...)  
- **Báo cáo chi tiết**: [Nhóm 21_64HTTT3_BTL.docx](docs/Nhóm%2021_64HTTT3_BTL.docx)  
- **File APK (Android)**: [Tải APK](https://drive.google.com/...)  

## 📜 Giấy phép

Dự án được phát triển với mục đích học tập và nghiên cứu, không sử dụng cho mục đích thương mại.

## 🙏 Lời tri ân

Nhóm xin chân thành cảm ơn **Thầy Nguyễn Văn Nam** đã tận tình hướng dẫn, chỉ bảo và tạo điều kiện để chúng em hoàn thành bài tập lớn môn học này.  

Cảm ơn sự đồng hành và hỗ trợ của các thành viên trong nhóm đã cùng nhau xây dựng nên một sản phẩm ý nghĩa và đầy tiềm năng.

**Amour Swipe** – Nơi kết nối yêu thương bắt đầu từ một cú vuốt tay.
