# Secure-File-Scan-Infra

## Overview

This project provides Terraform scripts to deploy a **secure web application** on **AWS**. The infrastructure setup includes:

- A **Virtual Private Cloud (VPC)**
- **Public and private subnets**
- **Security groups**
- An **EC2 instance**

The goal is to create a scalable and secure environment to host a file scanning web application.

---

## Getting Started

### Prerequisites

Before deploying the infrastructure, ensure you have:

- **Terraform** installed. You can download it from [terraform.io](https://www.terraform.io/downloads).
- **AWS credentials** configured on your machine. You can use:
  - Environment variables
  - AWS shared credentials file (`~/.aws/credentials`)
  - IAM roles (if running within AWS)

---

### Clone the Repository

```bash
git clone https://github.com/moiz-usid/Secure-File-Scan-Infra
cd Secure-File-Scan-Infra
