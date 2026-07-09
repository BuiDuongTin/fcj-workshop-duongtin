---
title: "Worklog Week 2"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Objectives for week 2:
* Understand how IAM protects AWS accounts.
* Distinguish Root User, IAM User, Group, Role, and Policy.
* Practice least-privilege access control.
* Get comfortable switching roles in the Console.

### Tasks for this week:
| Day | Task | Start Date | End Date | Resources |
| --- | --- | --- | --- | --- |
| 6 | - Review IAM basics <br> - Compare Root User and IAM User <br> - Note the risks of using Root User for daily operations | 24/04/2026 | 24/04/2026 | <https://000002.awsstudygroup.com/> <br><https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> |
| 2 | - Create an IAM Group and IAM User <br> - Add users to the appropriate group <br> - Sign in with the IAM User and check permissions | 27/04/2026 | 27/04/2026 | <https://000002.awsstudygroup.com/> |
| 3 | - Learn IAM Policy <br> - Compare AWS managed policies and customer managed policies <br> - Attach policies and verify access | 28/04/2026 | 28/04/2026 | <https://000002.awsstudygroup.com/> |
| 4 | - Learn IAM Role <br> - Create a role for operational access <br> - Record the difference between roles and direct permissions | 29/04/2026 | 29/04/2026 | <https://000002.awsstudygroup.com/> |
| 5 | - Practice role switching <br> - Allow the user to assume the role <br> - Clean up IAM resources after the lab | 30/04/2026 | 30/04/2026 | <https://000002.awsstudygroup.com/> |

### Week 2 results:
**Overview:**

This week gave me a clearer understanding of IAM and access control on AWS. After the labs, I could create users, groups, and roles, and I understood why permissions should be kept as narrow as possible.

**What I learned:**

* Root User should be reserved for special administrative tasks.
* IAM User, Group, and Role are the core of AWS permission management.
* Policies should match the real task and avoid over-permission.
* Role switching helps separate daily work from administrative access.

**Hands-on practice:**

* Creating a group and user in IAM.
* Attaching policies to the right identities.
* Creating a role and testing access through it.
* Cleaning up IAM resources after the lab.
