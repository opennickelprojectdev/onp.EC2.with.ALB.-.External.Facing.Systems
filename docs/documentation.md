# onp.base.template

## Metadata
| attribute               | value                                         |
| ----------------------- | --------------------------------------------- |
| pattern-id              | cba.EC2.ALB.EFSystems.ALB                             |
| pattern-name            | EC2 with ALB External Facing Systems                                |
| pattern-version         | 1.0.0                                         |
| pattern-description     | ALB for Internet Facing Web Tier                        |
| organisation-id         | cba                                            |
| pattern-categories      | Network                                     |

## What is this pattern?
This is a sample blueprint to use ALB inside CBA for External Facing Web Tiers

![](./diagrams/res/alb.png)

## What are the use cases?
- The ALB Pattern could be used to expose workloads that are eternally facing.
- The ALB could be used as a reverse proxy to navigate trafic to the specific destination.

## Variables

| Variable               | Source                                         | Value |
| -----------------------| --------------------------------------------- | ------|
| ALB ARN                   | SSM Parameter | cba/network/efalbname|