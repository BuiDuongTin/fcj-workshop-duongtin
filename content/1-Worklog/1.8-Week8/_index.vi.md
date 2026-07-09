---
title: "Worklog Tuần 8"
date: 2026-06-05
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
* Hiểu mô hình cân bằng tải và tự mở rộng trên AWS.
* Làm quen với Application Load Balancer, Target Group và Health Check.
* Nắm Launch Template và vai trò của nó trong Auto Scaling Group.
* Quan sát cách hệ thống chạy trên nhiều Availability Zone.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - Tìm hiểu tổng quan Elastic Load Balancing <br> - Nắm vai trò của Application Load Balancer <br> - Ghi lại cách ALB phân phối request đến nhiều EC2 Instance | 05/06/2026 | 05/06/2026 | <https://000006.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Tìm hiểu Target Group và Health Check <br> - Kiểm tra trạng thái healthy/unhealthy <br> - Ghi lại cách health check phát hiện instance lỗi | 08/06/2026 | 08/06/2026 | <https://000006.awsstudygroup.com/> |
| 3 | - Tìm hiểu Launch Template <br> - Ghi chú AMI, instance type, key pair và security group trong template <br> - Xác định vai trò của template khi tạo Auto Scaling Group | 09/06/2026 | 09/06/2026 | <https://000006.awsstudygroup.com/> |
| 4 | - Tìm hiểu Auto Scaling Group <br> - Nắm desired, minimum và maximum capacity <br> - Ghi lại cách ASG tự điều chỉnh số lượng instance | 10/06/2026 | 10/06/2026 | <https://000006.awsstudygroup.com/> |
| 5 | - Hoàn thiện sơ đồ kiến trúc có ALB và ASG <br> - Thể hiện luồng User → ALB → Target Group → EC2 Auto Scaling Group <br> - Dọn dẹp tài nguyên sau lab | 11/06/2026 | 11/06/2026 | <https://000006.awsstudygroup.com/> |

### Kết quả tuần 8:
**Tổng quan:**

Tuần này giúp tôi hiểu cách AWS xử lý mở rộng và cân bằng tải cho ứng dụng. Tôi có thể mô tả luồng request từ người dùng qua ALB đến nhiều instance phía sau rõ hơn trước.

**Điều tôi ghi nhớ:**

* ALB là lớp trung gian quan trọng cho ứng dụng web.
* Target Group và Health Check giúp kiểm soát chất lượng traffic.
* Launch Template là mẫu chuẩn để khởi tạo instance.
* Auto Scaling Group giúp hệ thống linh hoạt hơn khi tải thay đổi.

**Phần thực hành:**

* Tạo hoặc mô phỏng Target Group.
* Cấu hình Health Check.
* Tìm hiểu Launch Template.
* Cấu hình Auto Scaling Group.
* Vẽ lại sơ đồ luồng xử lý của hệ thống.
