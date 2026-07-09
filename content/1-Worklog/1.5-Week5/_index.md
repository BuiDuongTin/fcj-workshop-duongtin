---
title: "Worklog Week 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Objectives for week 5:
* Expand my understanding of EC2 compute and storage.
* Get familiar with Auto Scaling, backup, and related storage services.
* Practice AWS Backup, Storage Gateway, and static website hosting.
* Combine S3 and CloudFront to deliver website content.

### Tasks for this week:
| Day | Task | Start Date | End Date | Resources |
| --- | --- | --- | --- | --- |
| 6 | - Review EC2, AMI, key pair, EBS, and Instance Store <br> - Note User Data and Metadata <br> - Summarize the key compute concepts | 15/05/2026 | 15/05/2026 | <https://youtu.be/-t5h4N6vfBs?si=GeVdhO9IEDjzzS_D> <br><https://youtu.be/e7XeKdOVq40?si=T3I4pgPoEfVytcU3> <br><https://youtu.be/yAR6QRT3N1k?si=GQghyBwLCpijrDON> <br><https://youtu.be/hKr_TfGP7NY?si=gR2MqaLAFrqL-KBo> <br><https://youtu.be/6IHNDJ85aoQ?si=M0puk6DJpliO7ahf> <br><https://youtu.be/_v_43Wi7zjo?si=qNDVWzKcQFNO2mGh> <br><https://youtu.be/Ew3QRaKJQSA?si=xNvXvD8yFhnSMJby> |
| 2 | - Learn EC2 Auto Scaling <br> - Review EFS, FSx, Lightsail, and MGN at a high level <br> - Record use cases for each service | 18/05/2026 | 18/05/2026 | <https://youtu.be/bbLcPitXJSY?si=eyVnxvL9ho0LpUYy> <br><https://youtu.be/hFVYG8WqfU0?si=9Px4wmR4IRZxk15n> |
| 3 | - Deploy AWS Backup <br> - Create a backup plan <br> - Test restore and clean up after the restore | 19/05/2026 | 19/05/2026 | <https://000013.awsstudygroup.com/> |
| 4 | - Create an S3 bucket for Storage Gateway <br> - Launch EC2 for Storage Gateway <br> - Create the gateway and file share <br> - Remove all resources after the lab | 20/05/2026 | 20/05/2026 | <https://000024.awsstudygroup.com/> |
| 5 | - Create a bucket and upload sample data <br> - Enable static website hosting <br> - Configure CloudFront and test the website <br> - Delete the website, distribution, and bucket when done | 21/05/2026 | 21/05/2026 | <https://000057.awsstudygroup.com/> |

### Week 5 results:
**Overview:**

This week connected compute with storage and content delivery. I gained a better picture of how AWS Backup, Storage Gateway, and CloudFront solve very different problems inside one cloud platform.

**What I learned:**

* EBS and Instance Store serve different storage needs.
* Auto Scaling makes systems more flexible under changing load.
* Backup and restore are essential when working with data.
* S3 plus CloudFront is a practical way to publish a static website.

**Hands-on practice:**

* Creating a backup plan and testing restore.
* Creating Storage Gateway and a file share.
* Uploading content to S3 and enabling static website hosting.
* Configuring CloudFront to deliver the website.
* Cleaning up resources after the lab.
