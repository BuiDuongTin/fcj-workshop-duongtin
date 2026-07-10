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
* 01/05/2026: Xem video lý thuyết module 3 và tìm hiểu cách triển khai VM trên AWS cùng các dịch vụ hỗ trợ compute.  
  Link: <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i>
* 03/05/2026: Thiết lập chính sách sao lưu trên AWS Backup, tạo Backup Plan và Backup Vault, thực hành restore và dọn dẹp tài nguyên sau kiểm thử.  
  Link: <https://000013.awsstudygroup.com/>
* 05/05/2026: Tạo Storage Gateway, tạo File Shares và cấu hình kết nối File Shares từ máy on-premise.  
  Link: <https://000024.awsstudygroup.com/>
* 06/05/2026: Tìm hiểu S3 Bucket, S3 Object, triển khai static website trên S3, bật CloudFront, và thực hành Versioning, move/copy object sang region khác.  
  Link: <https://000057.awsstudygroup.com/>

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn cách AWS hỗ trợ compute, backup và lưu trữ. Tôi cũng biết cách triển khai website tĩnh trên S3 và tăng tốc bằng CloudFront.

**Điều tôi rút ra:**

* AWS Backup giúp chuẩn hóa quy trình sao lưu và phục hồi.
* Storage Gateway là cầu nối hữu ích giữa on-premise và AWS storage.
* S3 không chỉ dùng để lưu trữ mà còn có thể phục vụ website tĩnh.
* Versioning và sao chép object là các thao tác quan trọng để quản lý dữ liệu an toàn hơn.

**Phần thực hành:**

* Tạo plan và vault trên AWS Backup.
* Thực hiện restore để kiểm tra khả năng khôi phục dữ liệu.
* Cấu hình Storage Gateway và File Shares.
* Triển khai static website trên S3 và kiểm tra hoạt động qua CloudFront.
