---
title: "Worklog Tuần 3"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:
* Hiểu cách triển khai VM và các dịch vụ compute trên AWS.
* Làm quen với các dịch vụ bổ trợ như EC2 Auto Scaling, EFS/FSx, Lightsail và MGN.
* Biết cách thiết lập backup và restore bằng AWS Backup.
* Nắm được quy trình triển khai Storage Gateway và S3 Static Website.

### Công việc trong tuần:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 1 | - Xem video lý thuyết module 3 trên YouTube <br> - Tìm hiểu cách triển khai VM trên AWS <br> - Tìm hiểu dịch vụ bổ trợ compute: EC2 Auto Scaling, EFS/FSx, Lightsail, MGN | 01/05/2026 | 01/05/2026 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Thiết lập chính sách sao lưu trên AWS Backup bằng cách tạo Backup Plan và Backup Vault <br> - Áp dụng tag-based assignment để tự động đưa EC2 vào rule sao lưu <br> - Thực hiện diễn tập khôi phục dữ liệu và dọn dẹp tài nguyên sau kiểm thử | 03/05/2026 | 03/05/2026 | <https://000013.awsstudygroup.com/> |
| 3 | - Tạo Storage Gateway <br> - Tạo File Shares <br> - Kết nối File Shares ở máy on-premise | 05/05/2026 | 05/05/2026 | <https://000024.awsstudygroup.com/> |
| 4 | - Tìm hiểu các khái niệm của Amazon S3 như S3 Bucket và S3 Object <br> - Triển khai static website trên S3 và kiểm tra hoạt động <br> - Bật CloudFront, thực hành Versioning, di chuyển object và sao chép object sang region khác | 06/05/2026 | 06/05/2026 | <https://000057.awsstudygroup.com/> |

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn cách AWS hỗ trợ compute, backup và lưu trữ. Tôi cũng biết cách triển khai website tĩnh trên S3 và tăng tốc bằng CloudFront.

**Kiến thức đã học:**

* AWS Backup giúp chuẩn hóa quy trình sao lưu và phục hồi dữ liệu.
* Storage Gateway đóng vai trò cầu nối giữa hệ thống on-premise và dịch vụ lưu trữ trên AWS.
* Amazon S3 có thể được dùng để lưu trữ dữ liệu và triển khai website tĩnh.
* Versioning, move object và copy object là các thao tác quan trọng trong quản lý dữ liệu trên S3.

**Phần thực hành:**

* Tạo plan và vault trên AWS Backup.
* Thực hiện restore để kiểm tra khả năng khôi phục dữ liệu.
* Cấu hình Storage Gateway và File Shares.
* Triển khai static website trên S3 và kiểm tra hoạt động qua CloudFront.
