---
title: "Worklog Tuần 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:
* Hiểu cách Amazon RDS hỗ trợ database được quản lý trên AWS.
* Phân biệt database tự vận hành và database managed.
* Tạo RDS instance và cấu hình mạng phù hợp.
* Kết nối EC2 với RDS và kiểm tra hoạt động của database.
* Nắm sơ lược backup, restore và Multi-AZ.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - Tìm hiểu Amazon RDS ở mức tổng quan <br> - Phân biệt relational database và non-relational database <br> - Ghi lại lợi ích của dịch vụ managed database trên AWS | 22/05/2026 | 22/05/2026 | <https://000005.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Tìm hiểu DB Instance, DB Subnet Group và Security Group cho RDS <br> - Thiết kế database trong private subnet <br> - Xác định cách EC2 kết nối đến RDS | 25/05/2026 | 25/05/2026 | <https://000005.awsstudygroup.com/> |
| 3 | - Tạo RDS Database Instance <br> - Cấu hình engine, storage, user, password và networking <br> - Kiểm tra endpoint sau khi tạo | 26/05/2026 | 26/05/2026 | <https://000005.awsstudygroup.com/> |
| 4 | - Kết nối EC2 với RDS <br> - Mở quyền truy cập bằng Security Group <br> - Kiểm tra kết nối bằng dòng lệnh hoặc client | 27/05/2026 | 27/05/2026 | <https://000005.awsstudygroup.com/> |
| 5 | - Tìm hiểu backup, restore và Multi-AZ <br> - Cập nhật sơ đồ có EC2, RDS, private subnet và Security Group <br> - Dọn dẹp tài nguyên sau lab | 28/05/2026 | 28/05/2026 | <https://000005.awsstudygroup.com/> |

### Kết quả tuần 6:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn vai trò của RDS trong kiến trúc cloud. Tôi đã thực hành tạo database managed, cấu hình kết nối và hình dung cách EC2 giao tiếp với RDS trong một hệ thống thật.

**Điều tôi ghi nhớ:**

* RDS giảm bớt công việc vận hành database.
* DB Subnet Group và Security Group quyết định database có thể được truy cập như thế nào.
* Endpoint là thông tin cần theo dõi khi kết nối RDS.
* Backup, restore và Multi-AZ là các yếu tố rất quan trọng cho độ tin cậy.

**Phần thực hành:**

* Tạo RDS Database Instance.
* Đặt database trong private subnet.
* Cho phép EC2 truy cập RDS qua Security Group.
* Kết nối và kiểm tra endpoint.
* Dọn dẹp tài nguyên sau lab.
