---
title: "Worklog Tuần 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Nắm các dịch vụ hỗ trợ bảo mật và quản trị rủi ro trên AWS.
* Hiểu cách Security Hub và AWS Config giúp theo dõi trạng thái an toàn.
* Làm quen với Lambda, tagging, Resource Group và Permission Boundary.
* Biết cách dùng KMS, CloudTrail và Athena để giám sát và phân tích hoạt động truy cập.

### Công việc trong tuần:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 1 | - Xem video lý thuyết module 5 trên YouTube <br> - Xây dựng nền tảng IAM, mã hóa, giám sát bảo mật, quản trị đa tài khoản cho môi trường AWS an toàn | 15/05/2026 | 15/05/2026 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Tìm hiểu chức năng và cách triển khai AWS Security Hub cùng AWS Config <br> - Kích hoạt Security Hub CSPM và đánh giá các chuẩn bảo mật AWS Foundational Security Best Practices, CIS Benchmark, PCI DSS | 16/05/2026 | 16/05/2026 | <https://000018.awsstudygroup.com/> |
| 3 | - Xây dựng cơ chế tự động tối ưu chi phí EC2 bằng AWS Lambda <br> - Thiết lập quy trình giám sát lưu lượng ICMP qua VPC Flow Logs, CloudWatch Metric Filter, CloudWatch Alarm, SNS và Lambda để tự động dừng EC2 | 17/05/2026 | 17/05/2026 | <https://000022.awsstudygroup.com/> |
| 4 | - Tìm hiểu và áp dụng chiến lược gắn thẻ để quản lý tài nguyên trên AWS <br> - Triển khai các phiên bản EC2 cho nhiều môi trường và quản lý thẻ tập trung <br> - Xây dựng Resource Group dựa trên tiêu chí tag | 18/05/2026 | 18/05/2026 | <https://000027.awsstudygroup.com/> |
| 5 | - Xây dựng cơ chế kiểm soát quyền truy cập EC2 dựa trên tag thông qua IAM <br> - Thiết lập IAM Policy yêu cầu EC2 phải được gắn tag Environment=Test khi khởi tạo | 19/05/2026 | 19/05/2026 | <https://000028.awsstudygroup.com/> |
| 6 | - Thực hành sử dụng IAM Permission Boundary để quản lý giới hạn quyền người dùng <br> - Cấu hình Permission Boundary cho các nhóm DoiPho và Dev nhằm ngăn leo thang đặc quyền | 19/05/2026 | 19/05/2026 | <https://000030.awsstudygroup.com/> |
| 7 | - Thực hành mã hóa dữ liệu bằng AWS KMS và giám sát các sự kiện truy cập <br> - Sử dụng CloudTrail Data Events và Athena để phân tích log | 20/05/2026 | 20/05/2026 | <https://000033.awsstudygroup.com/> |
| 8 | - Kiểm thử IAM Role và Condition | 21/05/2026 | 21/05/2026 | <https://000044.awsstudygroup.com/> |

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn cách AWS hỗ trợ bảo mật, kiểm soát quyền và tối ưu chi phí. Tôi cũng biết cách giám sát tài nguyên theo tag và kiểm tra truy cập bằng các dịch vụ ghi log.

**Kiến thức đã học:**

* AWS Security Hub và AWS Config giúp phát hiện, theo dõi và đánh giá cấu hình bảo mật.
* AWS Lambda có thể được dùng để tự động hóa các phản ứng khi hệ thống phát hiện bất thường.
* Tagging là phương pháp quan trọng để quản lý và phân loại tài nguyên trên AWS.
* AWS KMS, CloudTrail và Athena hỗ trợ mã hóa, ghi log và phân tích hoạt động truy cập dữ liệu.

**Phần thực hành:**

* Bật Security Hub CSPM và xem các chuẩn đánh giá.
* Dùng Lambda để tự động dừng EC2 theo điều kiện giám sát.
* Tổ chức tài nguyên bằng tags và Resource Group.
* Thực hành Permission Boundary, KMS và kiểm thử IAM Condition.
