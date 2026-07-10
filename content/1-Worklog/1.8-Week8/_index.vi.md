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
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 1 | - Xây dựng cơ chế tự động tối ưu chi phí EC2 bằng AWS Lambda <br> - Thiết lập quy trình giám sát lưu lượng ICMP thông qua VPC Flow Logs, CloudWatch Metric Filter, CloudWatch Alarm, SNS và Lambda | 06/06/2026 | 06/06/2026 | <https://000074.awsstudygroup.com/> |
| 2 | - Thực hành tự động hóa quá trình phát hành ứng dụng trên EC2 bằng bộ công cụ AWS DevOps <br> - Thiết lập pipeline giữa GitHub, CodePipeline, S3 và CodeDeploy | 08/06/2026 | 08/06/2026 | <https://000017.awsstudygroup.com/> |
| 3 | - Thực hành triển khai Grafana trên EC2 và kết nối dữ liệu giám sát từ CloudWatch <br> - Cấu hình VPC, Security Group, IAM Role và tạo dashboard theo dõi CPUUtilization | 10/06/2026 | 10/06/2026 | <https://000029.awsstudygroup.com/> |
| 4 | - Thực hiện tối ưu hóa việc lựa chọn loại instance EC2 thông qua việc phân tích tài nguyên thực tế <br> - Triển khai CloudWatch Agent nhằm thu thập thông tin bộ nhớ và cung cấp dữ liệu đầu vào cho các công cụ đánh giá hiệu năng | 11/06/2026 | 11/06/2026 | <https://000032.awsstudygroup.com/> |

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
