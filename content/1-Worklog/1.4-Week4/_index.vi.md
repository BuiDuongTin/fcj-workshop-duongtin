---
title: "Worklog Tuần 4"
date: 2026-05-08
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:
* Hiểu EC2 là gì và khi nào nên dùng.
* Làm quen với AMI, instance type, key pair, security group và EBS.
* Thực hành khởi tạo cả Linux instance lẫn Windows instance.
* Kết nối máy chủ bằng SSH, RDP hoặc EC2 Instance Connect.
* Cài một web server đơn giản trên EC2.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - Tìm hiểu EC2 ở mức tổng quan <br> - Ghi lại vai trò của AMI, instance type, key pair, security group và EBS <br> - Phân biệt máy Linux và máy Windows trên AWS | 08/05/2026 | 08/05/2026 | <https://000004.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Chuẩn bị môi trường cho EC2 <br> - Tạo security group phù hợp <br> - Kiểm tra lại các rule truy cập cần thiết | 11/05/2026 | 11/05/2026 | <https://000004.awsstudygroup.com/> |
| 3 | - Khởi tạo Windows Server instance <br> - Kết nối bằng Remote Desktop <br> - Ghi chú các lỗi thường gặp khi kết nối | 12/05/2026 | 12/05/2026 | <https://000004.awsstudygroup.com/> |
| 4 | - Khởi tạo Amazon Linux instance <br> - Kết nối bằng SSH hoặc EC2 Instance Connect <br> - Kiểm tra cấu hình ban đầu của máy chủ | 13/05/2026 | 13/05/2026 | <https://000004.awsstudygroup.com/> |
| 5 | - Cài đặt một web server cơ bản trên EC2 <br> - Kiểm tra truy cập qua public IP <br> - Cập nhật sơ đồ có EC2, security group và Internet Gateway | 14/05/2026 | 14/05/2026 | <https://000004.awsstudygroup.com/> |

### Kết quả tuần 4:
**Tổng quan:**

Tuần này giúp tôi hiểu EC2 như lớp compute cốt lõi của AWS. Khi làm lab, tôi quen hơn với quy trình tạo instance, mở cổng đúng cách, đăng nhập máy chủ và đưa một dịch vụ web nhỏ lên chạy thử.

**Điều tôi ghi nhớ:**

* EC2 là máy chủ ảo có thể tùy biến theo nhu cầu.
* AMI và instance type quyết định nền tảng và cấu hình máy.
* Security Group là phần không thể bỏ qua khi mở truy cập.
* Kết nối Linux và Windows khác nhau, nên cần chuẩn bị đúng công cụ.

**Phần thực hành:**

* Tạo instance trên AWS.
* Đăng nhập Windows qua RDP.
* Đăng nhập Linux qua SSH hoặc EC2 Instance Connect.
* Cài web server và kiểm tra bằng public IP.
* Dọn dẹp tài nguyên sau lab.
