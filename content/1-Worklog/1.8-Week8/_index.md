---
title: "Worklog Week 8"
date: 2026-06-06
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Objectives for week 8:
* Learn how to automate the application release process on EC2.
* Get familiar with the AWS DevOps workflow using GitHub, CodePipeline, S3, and CodeDeploy.
* Learn how to deploy Grafana and connect CloudWatch monitoring data.
* Understand how CloudWatch Agent helps collect additional system metrics and improve instance selection.

### Tasks for this week:
| Day | Task | Start Date | End Date | Resources |
| --- | --- | --- | --- | --- |
| 1 | - Build an automated EC2 cost-optimization flow with AWS Lambda <br> - Set up ICMP monitoring with VPC Flow Logs, CloudWatch Metric Filter, CloudWatch Alarm, SNS, and Lambda | 06/06/2026 | 06/06/2026 | <https://000074.awsstudygroup.com/> |
| 2 | - Practice automating application release on EC2 with the AWS DevOps toolset <br> - Set up a pipeline connecting GitHub, CodePipeline, S3, and CodeDeploy | 08/06/2026 | 08/06/2026 | <https://000017.awsstudygroup.com/> |
| 3 | - Deploy Grafana on EC2 and connect monitoring data from CloudWatch <br> - Configure VPC, Security Group, IAM Role, and create a dashboard for CPUUtilization | 10/06/2026 | 10/06/2026 | <https://000029.awsstudygroup.com/> |
| 4 | - Optimize EC2 instance selection by analyzing real resource usage <br> - Deploy CloudWatch Agent to collect memory data and provide input for performance analysis tools | 11/06/2026 | 11/06/2026 | <https://000032.awsstudygroup.com/> |

### Week 8 results:
**Overview:**

This week helped me better understand the release process, system monitoring, and cost optimization on AWS. I also learned how to connect multiple services into a complete DevOps flow.

**Knowledge learned:**

* AWS Lambda can help automate responses to unusual conditions.
* AWS CodePipeline and CodeDeploy reduce manual deployment work.
* Grafana is useful for visualizing CloudWatch monitoring data.
* CloudWatch Agent expands metric collection and supports better instance selection.

**Hands-on practice:**

* Set up an application deployment pipeline.
* Built a monitoring dashboard in Grafana.
* Configured CloudWatch Agent to collect extra system data.
* Noted the points to consider when choosing EC2 instance types.
