---
title: "Worklog Tuần 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Mở rộng hiểu biết về phần compute và lưu trữ của EC2.
* Làm quen với Auto Scaling, backup và các dịch vụ lưu trữ liên quan.
* Thực hành AWS Backup, Storage Gateway và static website hosting.
* Kết hợp S3 với CloudFront để phân phối nội dung website.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - Ôn lại EC2, AMI, key pair, EBS và Instance Store <br> - Ghi chú User Data và Metadata <br> - Tóm tắt các thành phần quan trọng khi vận hành compute | 15/05/2026 | 15/05/2026 | <https://youtu.be/-t5h4N6vfBs?si=GeVdhO9IEDjzzS_D> <br><https://youtu.be/e7XeKdOVq40?si=T3I4pgPoEfVytcU3> <br><https://youtu.be/yAR6QRT3N1k?si=GQghyBwLCpijrDON> <br><https://youtu.be/hKr_TfGP7NY?si=gR2MqaLAFrqL-KBo> <br><https://youtu.be/6IHNDJ85aoQ?si=M0puk6DJpliO7ahf> <br><https://youtu.be/_v_43Wi7zjo?si=qNDVWzKcQFNO2mGh> <br><https://youtu.be/Ew3QRaKJQSA?si=xNvXvD8yFhnSMJby> |
| 2 | - Tìm hiểu EC2 Auto Scaling <br> - Xem tổng quan EFS, FSx, Lightsail và MGN <br> - Ghi lại trường hợp sử dụng của từng dịch vụ | 18/05/2026 | 18/05/2026 | <https://youtu.be/bbLcPitXJSY?si=eyVnxvL9ho0LpUYy> <br><https://youtu.be/hFVYG8WqfU0?si=9Px4wmR4IRZxk15n> |
| 3 | - Triển khai AWS Backup <br> - Tạo backup plan <br> - Kiểm thử restore và dọn dẹp sau restore | 19/05/2026 | 19/05/2026 | <https://000013.awsstudygroup.com/> |
| 4 | - Tạo S3 bucket cho Storage Gateway <br> - Khởi tạo EC2 phục vụ Storage Gateway <br> - Tạo gateway và file share <br> - Dọn dẹp toàn bộ tài nguyên | 20/05/2026 | 20/05/2026 | <https://000024.awsstudygroup.com/> |
| 5 | - Tạo bucket và upload dữ liệu <br> - Bật static website hosting <br> - Cấu hình CloudFront và kiểm thử website <br> - Xóa website, distribution và bucket sau khi hoàn tất | 21/05/2026 | 21/05/2026 | <https://000057.awsstudygroup.com/> |

### Kết quả tuần 5:
**Tổng quan:**

Tuần này giúp tôi nối thêm phần compute với lưu trữ và phân phối nội dung. Tôi hiểu rõ hơn cách AWS Backup, Storage Gateway và CloudFront có thể hỗ trợ một hệ thống cloud ở những tình huống rất khác nhau.

**Điều tôi rút ra:**

* EBS và Instance Store phục vụ các nhu cầu lưu trữ khác nhau.
* Auto Scaling giúp hệ thống linh hoạt hơn khi tải tăng giảm.
* Backup và restore là phần không thể thiếu khi làm việc với dữ liệu.
* S3 kết hợp CloudFront có thể dùng để phát hành website tĩnh nhanh và gọn.

**Phần thực hành:**

* Tạo backup plan và kiểm tra restore.
* Tạo Storage Gateway và file share.
* Đưa dữ liệu lên S3 và bật static website hosting.
* Cấu hình CloudFront để phân phối nội dung website.
* Dọn dẹp tài nguyên sau lab.
