---
description: So what have we learned?
---

# Summary

We've used some fairly simple Terraform code to build an IPV6 enabled VPC, subnets etc and run up an EC2 instance running IPV6

By default our VPC is allocated a /56, and subnets are allocated \(at /64\) from this allocation.

We put up a webserver \(busybox\) and accessed it using raw IP address \(IPV4 and IPV6\). We learned that you sometimes have to put square brackets round IPV6 addresses

We added a DNS A record for the IPV4 address and a DNS AAAA record for the IPV6 address



