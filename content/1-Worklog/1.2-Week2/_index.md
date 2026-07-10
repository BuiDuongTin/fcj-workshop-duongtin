---
title: "Worklog Week 2"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Objectives for week 2:
* Understand how AWS networking is organized with VPC and related components.
* Learn how to connect multiple environments using peering, resolver, and Transit Gateway.
* Get familiar with routing and DNS resolution in a hybrid model.
* Learn how to check connections between VPCs and note the limits of each model.

### Tasks for this week:
| Day | Task | Start Date | End Date | Resources |
| --- | --- | --- | --- | --- |
| 1 | - Watch the module 2 theory video on YouTube <br> - Learn about AWS networking services such as VPC, Security Group, Internet Gateway, EC2, and CloudFormation | 25/04/2026 | 25/04/2026 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Design and deploy VPC according to the AWS Well-Architected Framework <br> - Configure key network security components <br> - Set up secure connectivity between on-premises and AWS | 26/04/2026 | 26/04/2026 | <https://000003.awsstudygroup.com/vi/> |
| 3 | - Build a hybrid DNS model with Route 53 Resolver to resolve names across environments <br> - Create on-premises and AWS VPCs, then set up VPC Peering for connectivity <br> - Configure route tables, Resolver inbound/outbound endpoints, and resolver rules | 27/04/2026 | 27/04/2026 | <https://000010.awsstudygroup.com/> |
| 4 | - Perform manual VPC Peering setup <br> - Create two VPCs with separate CIDR ranges and configure routing and security groups for internal traffic <br> - Verify communication through private IPs | 28/04/2026 | 28/04/2026 | <https://000019.awsstudygroup.com/> |
| 5 | - Deploy a hub-and-spoke network architecture using AWS Transit Gateway as the central connector <br> - Attach 4 VPCs to the TGW and handle routing issues caused by missing propagation settings <br> - Test end-to-end connectivity and clean up resources to avoid extra cost | 29/04/2026 | 29/04/2026 | <https://000020.awsstudygroup.com/> |

### Week 2 results:
**Overview:**

This week helped me understand how AWS networking is built, especially how VPC, peering, resolver, and Transit Gateway connect multiple environments.

**Knowledge learned:**

* Amazon VPC is the base for building private networks on AWS.
* Route tables, gateways, and subnets control how traffic is routed.
* Route 53 Resolver supports hybrid DNS resolution between on-premises and AWS.
* AWS Transit Gateway is a central service for connecting many VPCs in a hub-and-spoke model.

**Hands-on practice:**

* Designed and deployed VPCs for the labs.
* Set up VPC connectivity with peering and TGW.
* Checked traffic flow and ping results between networks.
* Noted the limitations and important points of each connectivity model.
