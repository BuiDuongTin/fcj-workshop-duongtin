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
* 29/05/2026: Xem video lý thuyết module 7 và ôn lại các chủ đề liên quan đến chi phí, giám sát và logging.  
  Link: <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i>
* 30/05/2026: Phân tích dữ liệu chi phí AWS bằng AWS Glue kết hợp Amazon Athena, tạo Crawler, Data Catalog và truy vấn CUR bằng SQL.  
  Link: <https://000040.awsstudygroup.com/>
* 31/05/2026: Thực hành triển khai ứng dụng trên Amazon EC2, cấu hình VPC, Security Group và môi trường LAMP/Node.js.  
  Link: <https://000004.awsstudygroup.com/>
* 03/06/2026: Thực hành Amazon CloudWatch Workshop và triển khai tài nguyên bằng AWS CloudFormation, đồng thời xử lý lỗi liên quan đến Region và vCPU quota.  
  Link: <https://000008.awsstudygroup.com/>

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu cách kết hợp các dịch vụ AWS để phân tích chi phí, triển khai ứng dụng và tự động hóa hạ tầng. Tôi cũng thấy rõ vai trò của CloudFormation trong việc tái tạo môi trường.

**Điều tôi rút ra:**

* CUR, Glue và Athena là bộ công cụ hữu ích cho phân tích dữ liệu chi phí.
* EC2 vẫn là nền tảng quen thuộc để chạy ứng dụng web cơ bản.
* CloudWatch hỗ trợ theo dõi hoạt động và phát hiện lỗi khi triển khai.
* CloudFormation giúp mô tả hạ tầng bằng mã và giảm thao tác thủ công.

**Phần thực hành:**

* Tạo Glue Crawler và truy vấn dữ liệu bằng Athena.
* Triển khai ứng dụng trên EC2.
* Kiểm tra và xử lý lỗi khi deploy bằng CloudFormation.
* Ghi chú lại các vấn đề liên quan đến region và quota.
