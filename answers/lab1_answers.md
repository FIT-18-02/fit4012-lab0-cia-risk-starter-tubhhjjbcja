# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Bùi Anh Tuấn

**MSSV:** 1871020619
**Lớp/Nhóm:** CNTT18-02
---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Bảng điểm sinh viên
- Asset 2: Tài khoản giảng viên
- Asset 3 (nếu có): Cơ sở dữ liệu hệ thống

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

---

## 3. Phân tích sự cố B
- Threat: Người dùng trái phép hoặc người nội bộ chỉnh sửa điểm không đúng quyền
- Vulnerability: Mật khẩu yếu, không có xác thực đa yếu tố (MFA), phân quyền chưa rõ ràng, không có log theo dõi
- Mitigation: Triển khai MFA, phân quyền rõ ràng theo vai trò, ghi log thay đổi điểm, yêu cầu phê duyệt khi chỉnh sửa

---

## 4. Reflection
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý vấn đề liên quan đến Integrity vì dữ liệu điểm số rất quan trọng. Nếu điểm bị thay đổi sai mà không kiểm soát, sẽ ảnh hưởng lớn đến sinh viên và uy tín của hệ thống. Em sẽ triển khai xác thực đa yếu tố và phân quyền rõ ràng để hạn chế truy cập trái phép. Đồng thời, hệ thống cần ghi log để theo dõi mọi thay đổi. Sau khi đảm bảo tính toàn vẹn dữ liệu, em mới tiếp tục xử lý các vấn đề khác như bảo mật và tính sẵn sàng.



---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-Availability-B-Integrity-C-Confidentiality}
