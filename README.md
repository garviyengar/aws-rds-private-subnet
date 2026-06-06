# AWS RDS in Private Subnets using Terraform

Secure AWS infrastructure demonstrating database deployment in private subnets using Terraform.

## Overview

This project provisions:

* Custom VPC
* Public Subnet
* Private Subnet Group
* RDS MySQL Database
* Security Groups
* Public EC2 Instance
* Private Database Layer

The architecture follows security best practices by placing the database inside private subnets and restricting direct internet access.

## Architecture

```text
Internet
    │
    ▼
Public EC2 Instance
    │
    ▼
Security Group Rules
    │
    ▼
RDS MySQL Database
(Private Subnets)
```

## Technologies

* AWS
* Terraform
* RDS MySQL
* VPC
* EC2
* Security Groups

## Learning Outcomes

* Database Security
* Private Subnet Design
* AWS RDS Deployment
* Terraform Infrastructure Management
* Secure Cloud Architecture
