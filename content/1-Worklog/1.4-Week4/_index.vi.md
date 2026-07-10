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
* 08/05/2026: Xem video lý thuyết module 4, tìm hiểu dịch vụ lưu trữ trên AWS, static website và CORS.  
  Link: <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i>
* 09/05/2026: Tạo Storage Gateway, tạo File Shares và kết nối File Shares ở máy on-premise.  
  Link: <https://000024.awsstudygroup.com/>
* 10/05/2026: Thiết lập AWS Backup Plan và Backup Vault, thực hành restore và dọn dẹp tài nguyên sau kiểm thử.  
  Link: <https://000013.awsstudygroup.com/>
* 11/05/2026: Triển khai Amazon FSx for Windows File Server, tích hợp với Microsoft Active Directory và kiểm thử SMB từ Linux EC2.  
  Link: <https://000025.awsstudygroup.com/>
* 13/05/2026: Học các khái niệm IAM cốt lõi, tạo admin group/user, cấu hình Admin role, tạo OperatorUser và kiểm thử Switch Role.  
  Link: <https://000002.awsstudygroup.com/>

### Kết quả đạt được:
**Tổng quan:**

Tuần này giúp tôi hiểu rõ hơn các dịch vụ lưu trữ và quản trị truy cập trên AWS. Tôi cũng biết cách kết nối storage giữa AWS và môi trường on-premise.

**Điều tôi rút ra:**

* S3, Storage Gateway và FSx phục vụ các nhu cầu lưu trữ khác nhau.
* CORS là khái niệm cần chú ý khi xây dựng ứng dụng web với tài nguyên lưu trữ.
* FSx for Windows File Server phù hợp với môi trường cần tương thích SMB và Active Directory.
* IAM Role và Switch Role giúp tách bạch quyền rõ ràng hơn.

**Phần thực hành:**

* Tìm hiểu static website và CORS.
* Tạo Storage Gateway và File Shares.
* Triển khai FSx for Windows File Server và kiểm thử chia sẻ file.
* Tạo IAM user, group, role và thực hành chuyển vai trò.
