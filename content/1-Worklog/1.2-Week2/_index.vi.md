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
* 25/04/2026: Xem video lý thuyết module 2 và tìm hiểu các dịch vụ mạng trên AWS như VPC, Security Group, Internet Gateway, EC2 và CloudFormation.  
  Link: <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i>
* 26/04/2026: Thiết kế và triển khai VPC theo tiêu chuẩn AWS Well-Architected Framework, đồng thời cấu hình các thành phần bảo mật mạng quan trọng.  
  Link: <https://000003.awsstudygroup.com/vi/>
* 27/04/2026: Xây dựng mô hình DNS hybrid bằng Route 53 Resolver, tạo hai VPC mô phỏng và cấu hình route tables, Resolver inbound/outbound endpoints cùng resolver rules.  
  Link: <https://000010.awsstudygroup.com/>
* 28/04/2026: Thực hiện VPC Peering thủ công giữa hai VPC, cấu hình routing và security group, rồi kiểm tra giao tiếp qua private IP.  
  Link: <https://000019.awsstudygroup.com/>
* 29/04/2026: Triển khai kiến trúc hub-and-spoke với AWS Transit Gateway, gắn nhiều VPC, kiểm tra route propagation và xác minh kết nối end-to-end.  
  Link: <https://000020.awsstudygroup.com/>

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn cách AWS tổ chức mạng, đặc biệt là cách VPC, peering, resolver và Transit Gateway hỗ trợ kết nối giữa nhiều môi trường khác nhau.

**Điều tôi rút ra:**

* VPC là nền tảng để tự thiết kế mạng trên AWS.
* Route table, gateway và subnet quyết định luồng traffic.
* Route 53 Resolver hỗ trợ mô hình DNS hybrid giữa on-premises và AWS.
* Transit Gateway là lựa chọn phù hợp khi cần kết nối nhiều VPC theo mô hình hub-and-spoke.

**Phần thực hành:**

* Thiết kế và triển khai VPC theo yêu cầu bài lab.
* Cấu hình kết nối giữa nhiều VPC bằng peering và TGW.
* Kiểm tra đường đi của traffic và kết quả ping giữa các mạng.
* Ghi chú lại các hạn chế và điểm cần chú ý của từng mô hình kết nối.
