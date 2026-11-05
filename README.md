# HCM_KS26_CNTT2_IT108_Session20_Ex03

## 1. Báo cáo phân tích IPO

| Thành phần | Nội dung |
|---|---|
| Input | Backup Codes đã lưu trước đó ở nơi an toàn. |
| Process | Dùng mã dự phòng để xác thực theo cơ chế AWS hỗ trợ → Vô hiệu hóa MFA trên thiết bị cũ → Đăng ký MFA trên thiết bị mới → Tạo và lưu mã dự phòng mới nếu được hỗ trợ. |
| Output | Khôi phục quyền truy cập AWS, thiết bị cũ không còn dùng để xác thực được. |

## 2. Tại sao không nên lưu Backup Codes trong thư viện ảnh?

- Nếu mất điện thoại, người nhặt được có thể xem ảnh chứa mã dự phòng.
- Ảnh có thể tự đồng bộ lên Cloud, làm tăng nguy cơ bị lộ.
- Hacker có thể sử dụng mã dự phòng để vượt qua lớp xác thực 2FA.

Cách an toàn hơn: Lưu mã trong Password Manager có mã hóa hoặc cất bản giấy ở nơi an toàn.
