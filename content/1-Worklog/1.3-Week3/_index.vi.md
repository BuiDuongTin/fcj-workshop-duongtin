---
title: "Worklog Tuần 3"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:
* Hiểu cách AWS tổ chức networking qua Amazon VPC.
* Làm quen với subnet, route table, gateway và bộ lọc truy cập.
* Tách được luồng traffic cho public subnet và private subnet.
* Biết sơ lược các công cụ hỗ trợ kiểm tra kết nối trong VPC.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - Ôn khái niệm Amazon VPC <br> - Tìm hiểu CIDR block <br> - Phân biệt Default VPC và Custom VPC | 01/05/2026 | 01/05/2026 | <https://000003.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Tìm hiểu Subnet <br> - So sánh Public Subnet và Private Subnet <br> - Ghi lại vai trò của Route Table trong mạng AWS | 04/05/2026 | 04/05/2026 | <https://000003.awsstudygroup.com/> |
| 3 | - Tìm hiểu Internet Gateway và NAT Gateway <br> - Ghi chú cách từng subnet đi Internet khác nhau <br> - Lưu ý chi phí của NAT Gateway | 05/05/2026 | 05/05/2026 | <https://000003.awsstudygroup.com/> |
| 4 | - Tìm hiểu Security Group và Network ACL <br> - Phân biệt stateful và stateless <br> - Viết rule inbound/outbound đơn giản | 06/05/2026 | 06/05/2026 | <https://000003.awsstudygroup.com/> |
| 5 | - Xem tổng quan VPC Flow Logs, Reachability Analyzer và Session Manager <br> - Làm quen với Site-to-Site VPN <br> - Vẽ lại sơ đồ network layer hoàn chỉnh | 07/05/2026 | 07/05/2026 | <https://000003.awsstudygroup.com/> |

### Kết quả tuần 3:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn networking trên AWS, đặc biệt là cách VPC chia hệ thống thành nhiều lớp để kiểm soát truy cập và định tuyến. Tôi cũng hình dung rõ hơn lý do phải tách public subnet và private subnet.

**Điều tôi ghi nhớ:**

* VPC là nền tảng để tự thiết kế mạng trên AWS.
* Route table, gateway và subnet quyết định đường đi của traffic.
* Security Group và Network ACL có vai trò khác nhau.
* NAT Gateway cho phép private subnet ra Internet nhưng cần cân nhắc chi phí.

**Phần thực hành:**

* Vẽ mô hình VPC với public/private subnet.
* Thiết lập route cơ bản cho từng subnet.
* Ghi chú luồng truy cập qua Internet Gateway và NAT Gateway.
* Hoàn thiện sơ đồ network layer theo cách dễ đọc hơn.
