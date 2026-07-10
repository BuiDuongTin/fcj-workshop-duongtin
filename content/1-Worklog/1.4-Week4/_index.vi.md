---
title: "Worklog Tuần 4"
date: 2026-05-08
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:
* Hiểu nhóm dịch vụ storage trên AWS và vai trò của từng dịch vụ.
* Làm quen với static website, CORS và Storage Gateway.
* Nắm được cách triển khai Amazon FSx for Windows File Server.
* Ôn lại các khái niệm IAM cơ bản và thực hành Switch Role.

### Công việc trong tuần:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 1 | - Xem video lý thuyết module 4 trên YouTube <br> - Tìm hiểu về dịch vụ lưu trữ trên AWS <br> - Tìm hiểu về static website và CORS | 08/05/2026 | 08/05/2026 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Tạo Storage Gateway <br> - Tạo File Shares <br> - Kết nối File Shares ở máy on-premise | 09/05/2026 | 09/05/2026 | <https://000024.awsstudygroup.com/> |
| 3 | - Thiết lập chính sách sao lưu trên AWS Backup bằng cách tạo Backup Plan và Backup Vault <br> - Áp dụng tag-based assignment để tự động đưa EC2 vào rule sao lưu <br> - Thực hiện diễn tập khôi phục dữ liệu và dọn dẹp tài nguyên sau kiểm thử | 10/05/2026 | 10/05/2026 | <https://000013.awsstudygroup.com/> |
| 4 | - Triển khai Amazon FSx for Windows File Server <br> - Tích hợp FSx với Microsoft Active Directory <br> - Kiểm thử SMB từ Linux EC2 và xác minh đồng bộ file giữa các node | 11/05/2026 | 11/05/2026 | <https://000025.awsstudygroup.com/> |
| 5 | - Học các khái niệm IAM cốt lõi: root account, account ID, group, policy, role <br> - Tạo admin group/user, cấu hình Admin role, tạo OperatorUser và kiểm thử Switch Role | 13/05/2026 | 13/05/2026 | <https://000002.awsstudygroup.com/> |

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn các dịch vụ lưu trữ và quản trị truy cập trên AWS. Tôi cũng biết cách kết nối storage giữa AWS và môi trường on-premise.

**Kiến thức đã học:**

* Amazon S3, Storage Gateway và FSx phục vụ các nhu cầu lưu trữ khác nhau trên AWS.
* CORS là cơ chế cần chú ý khi ứng dụng web truy cập tài nguyên từ domain khác.
* FSx for Windows File Server phù hợp với môi trường cần tương thích SMB và Active Directory.
* IAM Role và Switch Role giúp phân tách quyền truy cập rõ ràng hơn trong quá trình làm việc.

**Phần thực hành:**

* Tìm hiểu static website và CORS.
* Tạo Storage Gateway và File Shares.
* Triển khai FSx for Windows File Server và kiểm thử chia sẻ file.
* Tạo IAM user, group, role và thực hành chuyển vai trò.
