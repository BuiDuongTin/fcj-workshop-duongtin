---
title: "Worklog Week 3"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Objectives for week 3:
* Understand how AWS organizes networking through Amazon VPC.
* Learn subnet, routing, gateway, and access-filtering basics.
* Separate traffic flow for public and private subnets.
* Get a brief overview of VPC troubleshooting tools.

### Tasks for this week:
| Day | Task | Start Date | End Date | Resources |
| --- | --- | --- | --- | --- |
| 6 | - Review Amazon VPC basics <br> - Learn CIDR block concepts <br> - Differentiate Default VPC and Custom VPC | 01/05/2026 | 01/05/2026 | <https://000003.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Learn Subnet <br> - Compare Public Subnet and Private Subnet <br> - Record the role of Route Table in AWS networking | 04/05/2026 | 04/05/2026 | <https://000003.awsstudygroup.com/> |
| 3 | - Learn Internet Gateway and NAT Gateway <br> - Note how each subnet reaches the Internet differently <br> - Keep the NAT Gateway cost in mind | 05/05/2026 | 05/05/2026 | <https://000003.awsstudygroup.com/> |
| 4 | - Learn Security Group and Network ACL <br> - Compare stateful and stateless behavior <br> - Write simple inbound/outbound rules | 06/05/2026 | 06/05/2026 | <https://000003.awsstudygroup.com/> |
| 5 | - Review VPC Flow Logs, Reachability Analyzer, and Session Manager <br> - Get a basic look at Site-to-Site VPN <br> - Finish a complete network layer diagram | 07/05/2026 | 07/05/2026 | <https://000003.awsstudygroup.com/> |

### Week 3 results:
**Overview:**

This week gave me a clearer picture of AWS networking and the role of VPC in isolating and routing traffic. I also understood better why public and private subnets are separated.

**What I learned:**

* VPC is the base for designing your own network on AWS.
* Route tables, gateways, and subnets define how traffic moves.
* Security Group and Network ACL serve different filtering purposes.
* NAT Gateway enables Internet access for private subnet resources, but cost matters.

**Hands-on practice:**

* Drawing a VPC layout with public and private subnets.
* Setting basic routing for each subnet.
* Noting the traffic flow through Internet Gateway and NAT Gateway.
* Reworking the network layer diagram in a simpler form.
