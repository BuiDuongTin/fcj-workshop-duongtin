---
title: "Worklog Week 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Objectives for week 6:
* Understand how Amazon RDS supports managed databases on AWS.
* Distinguish self-managed databases from managed ones.
* Create an RDS instance and configure networking correctly.
* Connect EC2 to RDS and verify database behavior.
* Get a basic sense of backup, restore, and Multi-AZ.

### Tasks for this week:
| Day | Task | Start Date | End Date | Resources |
| --- | --- | --- | --- | --- |
| 6 | - Review Amazon RDS at a high level <br> - Distinguish relational and non-relational databases <br> - Note the benefits of managed databases on AWS | 22/05/2026 | 22/05/2026 | <https://000005.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Learn DB Instance, DB Subnet Group, and Security Group for RDS <br> - Design the database inside a private subnet <br> - Define how EC2 connects to RDS | 25/05/2026 | 25/05/2026 | <https://000005.awsstudygroup.com/> |
| 3 | - Create an RDS Database Instance <br> - Configure engine, storage, user, password, and networking <br> - Check the endpoint after creation | 26/05/2026 | 26/05/2026 | <https://000005.awsstudygroup.com/> |
| 4 | - Connect EC2 to RDS <br> - Open access with Security Group rules <br> - Test the connection with a command-line tool or client | 27/05/2026 | 27/05/2026 | <https://000005.awsstudygroup.com/> |
| 5 | - Review backup, restore, and Multi-AZ <br> - Update the diagram with EC2, RDS, private subnet, and Security Group <br> - Clean up resources after the lab | 28/05/2026 | 28/05/2026 | <https://000005.awsstudygroup.com/> |

### Week 6 results:
**Overview:**

This week helped me understand the role of RDS in a cloud architecture. I practiced creating a managed database, setting up connectivity, and thinking about how EC2 talks to RDS in a real system.

**What I learned:**

* RDS removes much of the day-to-day database maintenance work.
* DB Subnet Group and Security Group define how the database can be reached.
* The endpoint is a key detail when connecting to RDS.
* Backup, restore, and Multi-AZ are central to reliability.

**Hands-on practice:**

* Creating an RDS Database Instance.
* Placing the database in a private subnet.
* Allowing EC2 to access RDS through Security Group rules.
* Connecting and checking the endpoint.
* Cleaning up resources after the lab.
