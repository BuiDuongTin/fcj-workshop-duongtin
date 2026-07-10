---
title: "Worklog Tuần 2"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:
* Hiểu cách AWS tổ chức mạng với VPC và các thành phần liên quan.
* Nắm được cách kết nối giữa nhiều môi trường thông qua peering, resolver và Transit Gateway.
* Làm quen với khái niệm định tuyến và phân giải DNS trong mô hình hybrid.
* Biết cách kiểm tra kết nối giữa các VPC và ghi chú các điểm hạn chế của từng mô hình.

### Công việc trong tuần:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 1 | - Xem video lý thuyết module 2 trên YouTube <br> - Tìm hiểu về các dịch vụ mạng trên AWS như VPC, Security Group, Internet Gateway, EC2 và CloudFormation | 25/04/2026 | 25/04/2026 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Thiết kế và triển khai VPC theo tiêu chuẩn AWS Well-Architected Framework <br> - Cấu hình các thành phần bảo mật mạng quan trọng <br> - Thiết lập kết nối an toàn giữa môi trường on-premise và AWS | 26/04/2026 | 26/04/2026 | <https://000003.awsstudygroup.com/vi/> |
| 3 | - Xây dựng mô hình DNS hybrid bằng Route 53 Resolver để kết nối phân giải tên giữa các môi trường <br> - Dựng hai mạng mô phỏng gồm on-premises VPC và AWS VPC, sau đó thiết lập VPC Peering để thông mạng <br> - Cấu hình route tables, Resolver inbound/outbound endpoints và resolver rules | 27/04/2026 | 27/04/2026 | <https://000010.awsstudygroup.com/> |
| 4 | - Thực hiện kết nối liên mạng bằng cách cấu hình VPC Peering theo phương pháp thủ công <br> - Khởi tạo hai VPC với dải CIDR tách biệt, sau đó thiết lập routing và security group phù hợp để cho phép lưu lượng nội bộ <br> - Xác minh khả năng giao tiếp qua private IP giữa hai VPC | 28/04/2026 | 28/04/2026 | <https://000019.awsstudygroup.com/> |
| 5 | - Triển khai kiến trúc mạng hub-and-spoke sử dụng AWS Transit Gateway làm trung tâm kết nối <br> - Gắn 4 VPC vào TGW thông qua các attachment, đồng thời xử lý sự cố định tuyến do thiếu cấu hình route propagation <br> - Thực hiện kiểm tra liên thông giữa các VPC và thu hồi tài nguyên để tránh phát sinh chi phí | 29/04/2026 | 29/04/2026 | <https://000020.awsstudygroup.com/> |

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn cách AWS tổ chức mạng, đặc biệt là cách VPC, peering, resolver và Transit Gateway hỗ trợ kết nối giữa nhiều môi trường khác nhau.

**Kiến thức đã học:**

* Amazon VPC là nền tảng để tự xây dựng mạng riêng trên AWS.
* Route table, gateway và subnet quyết định cách lưu lượng được định tuyến trong hệ thống.
* Route 53 Resolver hỗ trợ phân giải DNS giữa môi trường on-premises và AWS trong mô hình hybrid.
* AWS Transit Gateway là dịch vụ trung tâm phù hợp khi cần kết nối nhiều VPC theo mô hình hub-and-spoke.

**Phần thực hành:**

* Thiết kế và triển khai VPC theo yêu cầu bài lab.
* Cấu hình kết nối giữa nhiều VPC bằng peering và TGW.
* Kiểm tra đường đi của traffic và kết quả ping giữa các mạng.
* Ghi chú lại các hạn chế và điểm cần chú ý của từng mô hình kết nối.
