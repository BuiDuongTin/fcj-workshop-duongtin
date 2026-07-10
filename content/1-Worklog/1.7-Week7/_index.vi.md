---
title: "Worklog Tuần 7"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:
* Biết cách phân tích chi phí AWS từ dữ liệu CUR.
* Làm quen với AWS Glue, Athena và mô hình truy vấn dữ liệu trên S3.
* Thực hành triển khai ứng dụng trên EC2.
* Nắm quy trình triển khai tài nguyên bằng CloudWatch và CloudFormation.

### Công việc trong tuần:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 1 | - Xem video lý thuyết module 7 trên YouTube <br> - Ôn lại các chủ đề liên quan đến chi phí, giám sát và logging | 29/05/2026 | 29/05/2026 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Thực hành phân tích dữ liệu chi phí AWS bằng AWS Glue kết hợp Amazon Athena <br> - Triển khai S3 bucket, Glue Crawler, Data Catalog và truy vấn Athena SQL dựa trên dữ liệu CUR | 30/05/2026 | 30/05/2026 | <https://000040.awsstudygroup.com/> |
| 3 | - Thực hành triển khai ứng dụng trên Amazon EC2 <br> - Cấu hình VPC, tạo EC2 Linux/Windows, quản lý Security Group và thiết lập môi trường LAMP/Node.js | 31/05/2026 | 31/05/2026 | <https://000004.awsstudygroup.com/> |
| 4 | - Thực hành Amazon CloudWatch Workshop và triển khai tài nguyên bằng AWS CloudFormation <br> - Kiểm tra và xử lý lỗi triển khai EC2 liên quan đến Region và giới hạn vCPU quota | 03/06/2026 | 03/06/2026 | <https://000008.awsstudygroup.com/> |

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu cách kết hợp các dịch vụ AWS để phân tích chi phí, triển khai ứng dụng và tự động hóa hạ tầng. Tôi cũng thấy rõ vai trò của CloudFormation trong việc tái tạo môi trường.

**Kiến thức đã học:**

* CUR, AWS Glue và Amazon Athena là bộ công cụ hữu ích để phân tích dữ liệu chi phí trên AWS.
* Amazon EC2 là nền tảng quen thuộc để triển khai và chạy ứng dụng web.
* Amazon CloudWatch hỗ trợ theo dõi hoạt động hệ thống và phát hiện lỗi trong quá trình triển khai.
* AWS CloudFormation cho phép mô tả hạ tầng bằng mã và giảm thao tác thủ công khi triển khai.

**Phần thực hành:**

* Tạo Glue Crawler và truy vấn dữ liệu bằng Athena.
* Triển khai ứng dụng trên EC2.
* Kiểm tra và xử lý lỗi khi deploy bằng CloudFormation.
* Ghi chú lại các vấn đề liên quan đến region và quota.
