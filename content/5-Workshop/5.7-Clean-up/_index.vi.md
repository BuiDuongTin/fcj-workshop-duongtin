---
title: "Dọn dẹp tài nguyên"
date: 2026-07-04
weight: 7
chapter: false
pre: " <b> 5.7. </b> "
---

Clean-up cần thực hiện sau khi hoàn thành lab để tránh phát sinh chi phí AWS không cần thiết. Nên xóa tài nguyên theo đúng thứ tự vì một số stack phụ thuộc vào tài nguyên được tạo bởi các stack trước đó.

**5.7.1:** [Xóa DB init stack](5.7.1-Delete-db-init-stack/)

**5.7.2:** [Xóa ECS services stack](5.7.2-Delete-ecs-services-stack/)

**5.7.3:** [Empty S3 bucket do foundation tạo](5.7.3-Empty-S3-buckets/)

**5.7.4:** [Xóa foundation stack](5.7.4-Delete-foundation-stack/)

**5.7.5:** [Xóa WAF stack](5.7.5-Delete-WAF-stack/)

**5.7.6:** [Xóa ECR repositories](5.7.6-Delete-ECR-repositories/)

**5.7.7:** [Xóa artifact và template bucket](5.7.7-Delete-artifact-buckets/)
