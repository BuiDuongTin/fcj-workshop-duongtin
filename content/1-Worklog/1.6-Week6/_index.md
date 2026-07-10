---
title: "Worklog Week 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Objectives for week 6:
* Review database fundamentals and AWS database selection criteria.
* Understand how to deploy and secure relational databases with Amazon RDS.
* Learn how to migrate and synchronize data with AWS DMS.
* Get familiar with WAF for stronger web application protection.

### Tasks for this week:
| Day | Task | Start Date | End Date | Resources |
| --- | --- | --- | --- | --- |
| 1 | - Watch the module 6 theory video on YouTube <br> - Review core database concepts and DB selection criteria <br> - Learn managed relational database systems on AWS | 22/05/2026 | 22/05/2026 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Research how to integrate Amazon RDS with a Node.js application <br> - Deploy MySQL on Amazon RDS in a private subnet <br> - Protect it with Security Group chaining | 23/05/2026 | 23/05/2026 | <https://000005.awsstudygroup.com/> |
| 3 | - Study schema conversion and database migration workflows <br> - Migrate from Amazon RDS MySQL to Amazon RDS MariaDB with AWS DMS <br> - Configure source and target endpoints and use Full Load with CDC | 24/05/2026 | 24/05/2026 | <https://000043.awsstudygroup.com/> |
| 4 | - Deploy AWS WAF to protect the web application <br> - Place WAF in front of ALB, connect ALB to EC2 and RDS <br> - Test traffic filtering and reduction of unwanted requests | 26/05/2026 | 26/05/2026 | <https://000026.awsstudygroup.com/> |

### Week 6 results:
**Overview:**

This week helped me understand how to build and protect applications that use databases on AWS. I also learned how AWS DMS supports migration between database engines.

**Knowledge learned:**

* Amazon RDS is suitable for transactional workloads and makes database operations easier.
* Security Group chaining is one way to restrict direct access to RDS from the Internet.
* AWS DMS supports database migration and synchronization between database systems.
* AWS WAF is an important protection layer for filtering unwanted web traffic.

**Hands-on practice:**

* Created a MySQL RDS instance in a private subnet.
* Connected a Node.js application to RDS.
* Migrated data to MariaDB with DMS.
* Configured WAF and tested traffic filtering.
