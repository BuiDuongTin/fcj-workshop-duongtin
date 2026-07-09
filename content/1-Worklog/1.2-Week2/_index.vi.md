---
title: "Worklog Tuần 2"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:
* Hiểu cách IAM bảo vệ tài khoản AWS.
* Phân biệt Root User, IAM User, Group, Role và Policy.
* Thực hành phân quyền theo nguyên tắc least privilege.
* Làm quen với thao tác switch role trong Console.

### Công việc trong tuần:
| Thứ | Nội dung | Bắt đầu | Hoàn thành | Tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - Ôn lại khái niệm IAM <br> - So sánh Root User và IAM User <br> - Ghi chú rủi ro khi dùng Root User cho công việc hằng ngày | 24/04/2026 | 24/04/2026 | <https://000002.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Tạo IAM Group và IAM User <br> - Gán user vào group phù hợp <br> - Đăng nhập Console bằng IAM User để kiểm tra quyền | 27/04/2026 | 27/04/2026 | <https://000002.awsstudygroup.com/> |
| 3 | - Tìm hiểu IAM Policy <br> - Phân biệt policy do AWS quản lý và policy do người dùng tự tạo <br> - Gán policy và kiểm tra lại quyền truy cập | 28/04/2026 | 28/04/2026 | <https://000002.awsstudygroup.com/> |
| 4 | - Tìm hiểu IAM Role <br> - Tạo role cho người dùng vận hành <br> - Ghi lại điểm khác nhau giữa role và quyền gán trực tiếp | 29/04/2026 | 29/04/2026 | <https://000002.awsstudygroup.com/> |
| 5 | - Thực hành switch role <br> - Cấu hình quyền cho phép đổi role <br> - Dọn dẹp tài nguyên sau khi hoàn thành lab | 30/04/2026 | 30/04/2026 | <https://000002.awsstudygroup.com/> |

### Kết quả tuần 2:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn cách AWS kiểm soát truy cập bằng IAM. Sau khi thực hành, tôi có thể tạo user, group, role và gán quyền theo cách an toàn hơn thay vì cấp quyền quá rộng.

**Điều tôi rút ra:**

* Root User chỉ nên dùng cho những tác vụ quản trị đặc biệt.
* IAM User, Group và Role là bộ ba rất quan trọng trong quản lý quyền.
* Policy cần được thiết kế sát nhu cầu, không cấp dư.
* Switch role là cách hữu ích để tách vai trò làm việc và vai trò quản trị.

**Phần thực hành:**

* Tạo group và user trong IAM.
* Gán policy cho đúng đối tượng.
* Tạo role và chuyển sang role đó để kiểm tra quyền.
* Dọn dẹp tài nguyên IAM sau lab.
