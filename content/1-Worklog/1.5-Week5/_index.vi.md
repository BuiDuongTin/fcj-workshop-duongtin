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
* 15/05/2026: Xem video lý thuyết module 5 và tìm hiểu nền tảng IAM, mã hóa, giám sát bảo mật và quản trị đa tài khoản.  
  Link: <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i>
* 16/05/2026: Tìm hiểu AWS Security Hub và AWS Config, kích hoạt Security Hub CSPM và đánh giá các chuẩn bảo mật.  
  Link: <https://000018.awsstudygroup.com/>
* 17/05/2026: Xây dựng cơ chế tự động tối ưu chi phí EC2 bằng AWS Lambda, kết hợp VPC Flow Logs, CloudWatch, SNS và Lambda để tự động dừng EC2 khi cần.  
  Link: <https://000022.awsstudygroup.com/>
* 18/05/2026: Thực hành chiến lược gắn thẻ, quản lý EC2 qua Tags, tạo Resource Group và lưu nhóm tài nguyên theo điều kiện tag.  
  Link: <https://000027.awsstudygroup.com/>
* 19/05/2026: Xây dựng IAM Policy dựa trên tag và thực hành Permission Boundary để kiểm soát quyền của nhóm DoiPho và Dev.  
  Link: <https://000028.awsstudygroup.com/> <https://000030.awsstudygroup.com/>
* 20/05/2026: Thực hành mã hóa dữ liệu bằng AWS KMS, theo dõi truy cập bằng CloudTrail Data Events và phân tích log bằng Athena.  
  Link: <https://000033.awsstudygroup.com/>
* 21/05/2026: Kiểm thử IAM Role và Condition.  
  Link: <https://000044.awsstudygroup.com/>

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn cách AWS hỗ trợ bảo mật, kiểm soát quyền và tối ưu chi phí. Tôi cũng biết cách giám sát tài nguyên theo tag và kiểm tra truy cập bằng các dịch vụ ghi log.

**Điều tôi rút ra:**

* Security Hub và AWS Config giúp phát hiện và theo dõi cấu hình chưa an toàn.
* Lambda có thể được dùng để tự động hóa phản ứng khi phát hiện bất thường.
* Tagging là cách quản lý tài nguyên rất hiệu quả khi dự án có nhiều môi trường.
* KMS, CloudTrail và Athena hỗ trợ kiểm tra và phân tích hoạt động truy cập dữ liệu.

**Phần thực hành:**

* Bật Security Hub CSPM và xem các chuẩn đánh giá.
* Dùng Lambda để tự động dừng EC2 theo điều kiện giám sát.
* Tổ chức tài nguyên bằng tags và Resource Group.
* Thực hành Permission Boundary, KMS và kiểm thử IAM Condition.
