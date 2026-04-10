# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Bảng điểm sinh viên
- Tài khoản giảng viên
- Cơ sở dữ liệu hệ thống

**CIA mapping:**
- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

**Phân tích sự cố B:**
- Threat: Người dùng trái phép hoặc người nội bộ chỉnh sửa điểm không đúng quyền
- Vulnerability: Mật khẩu yếu, không có xác thực đa yếu tố (MFA), phân quyền chưa rõ ràng, không có log theo dõi
- Mitigation: Triển khai MFA, phân quyền rõ ràng theo vai trò, ghi log thay đổi điểm, yêu cầu phê duyệt khi chỉnh sửa

### 4. Kết luận ngắn
(4-6 dòng: em học được gì từ bài lab này, phần nào khó nhất, điều gì cần chú ý khi phân tích một sự cố an toàn thông tin.)
