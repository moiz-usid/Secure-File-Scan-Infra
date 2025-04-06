# Secure File Scan Infrastructure

This project provides Terraform scripts to deploy a **secure web application on AWS**. The infrastructure includes a **Virtual Private Cloud (VPC)**, public and private **subnets**, **security groups**, and an **EC2 instance**, ensuring a robust, scalable, and secure environment for hosting the web application.

---

## 🚀 Overview

With this setup, you can:
- Provision a secure AWS environment using infrastructure-as-code.
- Deploy an EC2 instance inside a properly configured VPC.
- Access a web application hosted on that EC2 instance.

---

## 🛠️ Getting Started

To deploy the infrastructure on AWS, follow the steps below.

### ✅ Prerequisites

- [Terraform](https://www.terraform.io/downloads) installed on your local machine
- An AWS account with appropriate permissions
- AWS credentials configured (via environment variables, credentials file, or IAM role)

### 🔁 Clone the Repository

```bash
git clone https://github.com/moiz-usid/Secure-File-Scan-Infra
cd Secure-File-Scan-Infra
```

### 🧱 Initialize Terraform

```bash
terraform init
```

This will download the required providers and initialize the working directory.

### ⚙️ Review and Customize Configuration

Before deploying, review the configuration files (especially `main.tf`) to:

- Understand what resources will be created
- Make changes according to your specific requirements

### 🚀 Deploy the Infrastructure

```bash
terraform apply
```

- Review the proposed plan
- Type `yes` when prompted to confirm

### 🌐 Access the Web Application

After deployment is complete, Terraform will output the **public IP address** of the EC2 instance. Open a browser and navigate to:

```
http://<public-ip>
```

---

## 🧹 Cleanup

To destroy the infrastructure and avoid unwanted AWS charges:

```bash
terraform destroy
```

---

## 📌 About

A **Terraform-based infrastructure setup** for a secure web application hosted on AWS. This project uses:

- VPC with subnets
- EC2 instance hosting the application
- Proper security group rules
- Scalable and secure design

---

## 📬 Contact

Created by **[@moiz-usid](https://github.com/moiz-usid)** – feel free to reach out if you have any questions!

---
