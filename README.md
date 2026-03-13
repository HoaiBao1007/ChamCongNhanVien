- ChamCongNhanVien – Employee Attendance App
Ứng dụng chấm công nhân viên bằng công nghệ NFC được phát triển bằng Flutter.
Hệ thống cho phép nhân viên đăng nhập, quét thẻ NFC để chấm công và đồng bộ dữ liệu với hệ thống backend.
Ứng dụng giúp doanh nghiệp quản lý thời gian làm việc của nhân viên nhanh chóng, chính xác và tiện lợi.
- Features
•	Authentication
•	Đăng nhập tài khoản nhân viên.
•	Xác thực người dùng bằng JWT Token.
•	Lưu trạng thái đăng nhập.
- NFC Attendance
•	Quét thẻ NFC để thực hiện chấm công.
•	Ghi nhận thời gian Check-in / Check-out.
•	Gửi dữ liệu chấm công đến hệ thống backend.
- Employee Information
•	Hiển thị thông tin tài khoản nhân viên.
•	Lấy dữ liệu từ server thông qua API.
- Local Storage
•	Lưu token và dữ liệu đăng nhập bằng SharedPreferences.
•	Giữ trạng thái đăng nhập khi mở lại ứng dụng.
- Export Attendance Data
•	Xuất dữ liệu chấm công ra file Excel.
•	Chia sẻ file Excel thông qua các ứng dụng khác.
- API Integration
•	Gửi và nhận dữ liệu từ REST API.
•	Đồng bộ dữ liệu với backend.
- Permission Management
•	Xin quyền truy cập NFC.
•	Quản lý quyền truy cập thiết bị.
- Technologies Used
Programming Language
Dart
Framework
Flutter
| Package            | Description              |
| ------------------ | ------------------------ |
| nfc_manager        | Đọc dữ liệu từ thẻ NFC   |
| http               | Gửi request đến REST API |
| provider           | Quản lý state            |
| shared_preferences | Lưu trữ dữ liệu cục bộ   |
| jwt_decode         | Giải mã JWT token        |
| permission_handler | Quản lý quyền thiết bị   |
| excel              | Xuất file Excel          |
| share_plus         | Chia sẻ file             |

- Supported Platforms
Ứng dụng được phát triển bằng Flutter nên có thể chạy trên:
•	Android
•	iOS
•	Web
•	Windows
•	macOS
•	Linux
- Installation & Setup
1.	Clone repository
git clone https://github.com/HoaiBao1007/ChamCongNhanVien.git
2.	Di chuyển vào thư mục dự án
cd ChamCongNhanVien
3.	Cài đặt dependencies
flutter pub get
4.	Chạy ứng dụng
flutter run
5.	Kiểm tra môi trường Flutter
flutter doctor
- Project Structure
ChamCongNhanVien
│
├── android        # Source code Android
├── ios            # Source code iOS
├── web            # Web support
├── windows        # Windows support
├── macos          # macOS support
├── linux          # Linux support
│
├── lib            # Source code chính của ứng dụng
│   ├── models
│   ├── services
│   ├── screens
│   ├── providers
│   └── main.dart
│
├── pubspec.yaml   # Dependencies
└── README.md
- Future Improvements
•	Quản lý lịch sử chấm công.
•	Dashboard thống kê.
•	Quản lý nhiều nhân viên.
•	Tích hợp GPS khi chấm công.
•	Thông báo khi chấm công thành công.
- License
This project is for learning and demonstration purposes.
