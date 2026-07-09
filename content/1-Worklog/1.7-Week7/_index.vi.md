---
title: "Worklog Tuần 7"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:
* Hiểu quy trình chuyển đổi schema và migration database trên AWS.
* Làm quen với AWS SCT và AWS DMS.
* Nắm được vai trò của source database và target database.
* Theo dõi một migration task từ đầu đến cuối.
* Kiểm tra dữ liệu sau khi migration hoàn tất.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 6 | - Tìm hiểu workshop Database Schema Conversion & Migration <br> - Xác định mục tiêu của bài lab <br> - Ghi lại các thành phần chính của quy trình migration | 29/05/2026 | 29/05/2026 | <https://000043.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Tìm hiểu AWS Schema Conversion Tool <br> - Ghi chú cách SCT hỗ trợ chuyển đổi schema <br> - Xác định những phần cần kiểm tra trước migration | 01/06/2026 | 01/06/2026 | <https://000043.awsstudygroup.com/> |
| 3 | - Tìm hiểu AWS Database Migration Service <br> - Nắm replication instance, source endpoint, target endpoint và migration task <br> - Ghi lại full load và ongoing replication | 02/06/2026 | 02/06/2026 | <https://000043.awsstudygroup.com/> |
| 4 | - Cấu hình source database và target database <br> - Kiểm tra kết nối giữa các thành phần <br> - Chuẩn bị cho migration task | 03/06/2026 | 03/06/2026 | <https://000043.awsstudygroup.com/> |
| 5 | - Tạo migration task <br> - Theo dõi tiến độ migration <br> - Kiểm tra dữ liệu sau migration <br> - Dọn dẹp tài nguyên sau lab | 04/06/2026 | 04/06/2026 | <https://000043.awsstudygroup.com/> |

### Kết quả tuần 7:
**Tổng quan:**

Tuần này tập trung vào việc chuyển đổi schema và di chuyển database. Tôi hiểu rõ hơn vai trò của AWS SCT và AWS DMS trong việc hỗ trợ migration giữa các hệ quản trị cơ sở dữ liệu.

**Điều tôi ghi nhớ:**

* SCT hỗ trợ chuyển đổi schema trước khi migration.
* DMS giúp đẩy dữ liệu từ nguồn sang đích.
* Source endpoint, target endpoint và replication instance là các thành phần chính.
* Việc kiểm tra dữ liệu sau migration là bước không thể bỏ qua.

**Phần thực hành:**

* Cấu hình source database và target database.
* Tạo endpoint cho migration.
* Tạo và theo dõi migration task.
* Kiểm tra dữ liệu sau khi chuyển xong.
* Dọn dẹp tài nguyên cuối lab.
