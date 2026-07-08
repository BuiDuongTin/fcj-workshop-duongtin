---
title: "Worklog Tuần 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---



### Mục tiêu tuần 5:
* Tìm hiểu các thành phần chính của EC2 và cách vận hành compute trong AWS.
* Nắm được cơ chế Auto Scaling, EBS, Instance Store, User Data, Metadata.
* Thực hành backup, Storage Gateway và triển khai EC2 phục vụ cho lưu trữ.
* Thực hành triển khai static website bằng S3 và CloudFront.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - Tìm hiểu về EC2, các loại instance, AMI, key pair <br> - Biết được EBS, Instance Store, User Data, Metadata <br> - Ôn lại các thành phần quan trọng khi vận hành compute trên AWS | 15/05/2026 | 15/05/2026 | <https://youtu.be/-t5h4N6vfBs?si=GeVdhO9IEDjzzS_D> <br><https://youtu.be/e7XeKdOVq40?si=T3I4pgPoEfVytcU3> <br><https://youtu.be/yAR6QRT3N1k?si=GQghyBwLCpijrDON> <br><https://youtu.be/hKr_TfGP7NY?si=gR2MqaLAFrqL-KBo> <br><https://youtu.be/6IHNDJ85aoQ?si=M0puk6DJpliO7ahf> <br><https://youtu.be/_v_43Wi7zjo?si=qNDVWzKcQFNO2mGh> <br><https://youtu.be/Ew3QRaKJQSA?si=xNvXvD8yFhnSMJby> |
| 2 | - Nắm được cách EC2 Auto Scaling hỗ trợ scale VM <br> - Tìm hiểu về các dịch vụ lưu trữ và compute như EFS, FSx, Lightsail, MGN ở mức tổng quan <br> - Ghi lại trường hợp sử dụng của từng dịch vụ | 18/05/2026 | 18/05/2026 | <https://youtu.be/bbLcPitXJSY?si=eyVnxvL9ho0LpUYy> <br><https://youtu.be/hFVYG8WqfU0?si=9Px4wmR4IRZxk15n> |
| 3 | - Thực hành: <br>     + Triển khai AWS Backup <br>     + Tạo backup plan <br>     + Kiểm thử restore và cleanup <br>     + Dọn dẹp backup | 19/05/2026 | 19/05/2026 | <https://000013.awsstudygroup.com/> |
| 4 | - Thực hành: <br>     + Tạo S3 bucket để dùng với Storage Gateway <br>     + Tạo EC2 cho Storage Gateway <br>     + Tạo Storage Gateway và File Share <br>     + Dọn dẹp Storage Gateway | 20/05/2026 | 20/05/2026 | <https://000024.awsstudygroup.com/> |
| 5 | - Thực hành: <br>     + Tạo bucket và upload dữ liệu <br>     + Bật static website hosting <br>     + Cấu hình public access block <br>     + Cấu hình CloudFront và kiểm thử website <br>     + Dọn dẹp website, CloudFront và bucket | 21/05/2026 | 21/05/2026 | <https://000057.awsstudygroup.com/> |


### Kết quả tuần 5:
**Tổng quan:**

Tuần này mở rộng thêm các nội dung quanh EC2, storage của instance, Auto Scaling và backup. Bên cạnh đó, tôi cũng thực hành với Storage Gateway và triển khai static website bằng S3 kết hợp CloudFront.

**Kiến thức lý thuyết tiếp thu:**

* Khái niệm về kiến trúc EC2, AMI, key pair.
* EBS và Instance Store.
* User Data và Metadata.
* EC2 Auto Scaling.
* Tổng quan về EFS, FSx, Lightsail và MGN.
* Storage Gateway và nền tảng về Backup.
* S3 static website hosting và CloudFront.

**Thực hành với bài lab:**

* Tạo backup plan và test restore.
* Tạo Storage Gateway và file share.
* Tạo S3 bucket, upload dữ liệu và bật static website hosting.
* Cấu hình CloudFront để phân phối nội dung website.
* Dọn dẹp tài nguyên backup, Storage Gateway, CloudFront và S3 sau khi hoàn tất lab.


