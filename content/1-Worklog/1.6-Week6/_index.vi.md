---
title: "Worklog Tuần 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:
* Ôn lại kiến thức về cơ sở dữ liệu và tiêu chí lựa chọn DB trên AWS.
* Hiểu cách triển khai và bảo vệ cơ sở dữ liệu quan hệ bằng Amazon RDS.
* Biết cách chuyển đổi và đồng bộ dữ liệu với AWS DMS.
* Làm quen với WAF để tăng cường bảo vệ ứng dụng web.

### Công việc trong tuần:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 1 | - Xem video lý thuyết module 6 trên YouTube <br> - Ôn lại khái niệm cốt lõi về cơ sở dữ liệu và tiêu chí lựa chọn DB <br> - Học hệ CSDL quan hệ managed trên AWS | 22/05/2026 | 22/05/2026 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Nghiên cứu cách tích hợp Amazon RDS với ứng dụng Node.js <br> - Triển khai MySQL trên Amazon RDS trong private subnet <br> - Bảo vệ bằng Security Group chaining | 23/05/2026 | 23/05/2026 | <https://000005.awsstudygroup.com/> |
| 3 | - Nghiên cứu quy trình chuyển đổi schema và di chuyển cơ sở dữ liệu <br> - Thực hiện migration từ Amazon RDS MySQL sang Amazon RDS MariaDB bằng AWS DMS <br> - Cấu hình source/target endpoint và dùng Full Load kết hợp CDC | 24/05/2026 | 24/05/2026 | <https://000043.awsstudygroup.com/> |
| 4 | - Triển khai AWS WAF để bảo vệ ứng dụng web <br> - Thiết lập WAF trước ALB, kết nối ALB với EC2 và RDS <br> - Kiểm tra khả năng lọc lưu lượng truy cập | 26/05/2026 | 26/05/2026 | <https://000026.awsstudygroup.com/> |

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn cách xây dựng và bảo vệ ứng dụng có cơ sở dữ liệu trên AWS. Tôi cũng nắm được cách migration dữ liệu giữa các engine khác nhau bằng DMS.

**Điều tôi rút ra:**

* Amazon RDS phù hợp cho workload giao dịch và cần vận hành đơn giản.
* Security Group chaining giúp hạn chế truy cập trực tiếp vào RDS từ Internet.
* AWS DMS hỗ trợ quá trình di chuyển và đồng bộ dữ liệu tương đối linh hoạt.
* WAF là lớp bảo vệ quan trọng phía trước ứng dụng web.

**Phần thực hành:**

* Tạo RDS MySQL trong private subnet.
* Kết nối ứng dụng Node.js với RDS.
* Chạy migration sang MariaDB bằng DMS.
* Cấu hình WAF và kiểm tra lọc lưu lượng.
