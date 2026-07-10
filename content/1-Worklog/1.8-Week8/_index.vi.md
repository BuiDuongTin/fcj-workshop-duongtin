---
title: "Worklog Tuần 8"
date: 2026-06-06
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
* Hiểu cách tự động hóa quá trình phát hành ứng dụng trên EC2.
* Làm quen với AWS DevOps workflow gồm GitHub, CodePipeline, S3 và CodeDeploy.
* Biết cách triển khai Grafana và kết nối dữ liệu giám sát từ CloudWatch.
* Nắm cách dùng CloudWatch Agent để thu thập thêm chỉ số hệ thống và tối ưu lựa chọn instance.

### Công việc trong tuần:
* 06/06/2026: Xây dựng cơ chế tự động tối ưu chi phí EC2 bằng AWS Lambda, kết hợp giám sát qua VPC Flow Logs và CloudWatch.  
  Link: <https://000074.awsstudygroup.com/>
* 08/06/2026: Thực hành tự động hóa phát hành ứng dụng trên EC2 bằng AWS DevOps, thiết lập pipeline giữa GitHub, CodePipeline, S3 và CodeDeploy.  
  Link: <https://000017.awsstudygroup.com/>
* 10/06/2026: Triển khai Grafana trên EC2 và kết nối dữ liệu giám sát từ CloudWatch để tạo dashboard theo dõi CPUUtilization.  
  Link: <https://000029.awsstudygroup.com/>
* 11/06/2026: Thực hiện tối ưu hóa lựa chọn loại instance EC2 bằng cách phân tích tài nguyên thực tế và cài đặt CloudWatch Agent.  
  Link: <https://000032.awsstudygroup.com/>

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn quy trình phát hành ứng dụng, giám sát hệ thống và tối ưu chi phí trên AWS. Tôi cũng biết cách liên kết nhiều dịch vụ để tạo thành một luồng DevOps hoàn chỉnh.

**Điều tôi rút ra:**

* Lambda có thể hỗ trợ tự động hóa phản ứng với tình huống bất thường.
* CodePipeline và CodeDeploy giúp giảm thao tác deploy thủ công.
* Grafana là công cụ hữu ích để trực quan hóa dữ liệu CloudWatch.
* CloudWatch Agent mở rộng khả năng thu thập metrics phục vụ tối ưu instance.

**Phần thực hành:**

* Thiết lập pipeline triển khai ứng dụng.
* Tạo dashboard giám sát trên Grafana.
* Cấu hình CloudWatch Agent để lấy thêm dữ liệu hệ thống.
* Ghi chú lại những điểm cần tối ưu khi chọn instance EC2.
