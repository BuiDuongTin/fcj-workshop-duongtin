---
title: "Worklog Week 8"
date: 2026-06-05
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Objectives for week 8:
* Understand AWS load balancing and autoscaling.
* Get familiar with Application Load Balancer, Target Group, and Health Check.
* Learn Launch Template and its role in an Auto Scaling Group.
* Observe how systems run across multiple Availability Zones.

### Tasks for this week:
| Day | Task | Start Date | End Date | Resources |
| --- | --- | --- | --- | --- |
| 6 | - Review Elastic Load Balancing <br> - Understand the role of Application Load Balancer <br> - Note how ALB sends requests to multiple EC2 instances | 05/06/2026 | 05/06/2026 | <https://000006.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Learn Target Group and Health Check <br> - Check healthy and unhealthy states <br> - Note how health checks detect failed instances | 08/06/2026 | 08/06/2026 | <https://000006.awsstudygroup.com/> |
| 3 | - Learn Launch Template <br> - Note AMI, instance type, key pair, and security group in the template <br> - Identify the role of the template in Auto Scaling Group creation | 09/06/2026 | 09/06/2026 | <https://000006.awsstudygroup.com/> |
| 4 | - Learn Auto Scaling Group <br> - Understand desired, minimum, and maximum capacity <br> - Note how ASG adjusts instance count automatically | 10/06/2026 | 10/06/2026 | <https://000006.awsstudygroup.com/> |
| 5 | - Finish the architecture diagram with ALB and ASG <br> - Show the flow User → ALB → Target Group → EC2 Auto Scaling Group <br> - Clean up resources after the lab | 11/06/2026 | 11/06/2026 | <https://000006.awsstudygroup.com/> |

### Week 8 results:
**Overview:**

This week helped me understand how AWS handles scaling and load balancing for applications. I could describe the request flow from a user through ALB to multiple backend instances more clearly than before.

**What I learned:**

* ALB is an important middle layer for web applications.
* Target Group and Health Check help keep traffic healthy.
* Launch Template is a standard blueprint for launching instances.
* Auto Scaling Group makes systems more flexible under changing load.

**Hands-on practice:**

* Creating or simulating a Target Group.
* Configuring Health Check.
* Learning the Launch Template.
* Configuring an Auto Scaling Group.
* Redrawing the system flow diagram.
