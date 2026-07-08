# 🚀 Terraform AWS Tasks Solutions – Level 1

![Terraform](https://img.shields.io/badge/Terraform-1.x-623CE4?style=for-the-badge&logo=terraform)
![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?style=for-the-badge&logo=amazonaws)
![Infrastructure as Code](https://img.shields.io/badge/IaC-Terraform-blue?style=for-the-badge)
![DevOps](https://img.shields.io/badge/DevOps-Automation-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## 📖 Overview

This repository contains solutions to a series of Terraform-based AWS infrastructure tasks designed to demonstrate practical Infrastructure as Code (IaC) skills using Terraform.

The project covers provisioning and managing AWS resources including:

- Amazon VPC
- Amazon S3
- Amazon DynamoDB
- Amazon Kinesis
- AWS IAM
- EC2 Key Pairs
- Elastic IP Associations

These solutions showcase fundamental Terraform concepts such as:

✅ Resource creation

✅ Data sources

✅ AWS integrations

✅ Security best practices

✅ Cloud infrastructure automation

---

## 🏗 Architecture Overview

```text
                        ┌─────────────────┐
                        │   Terraform     │
                        │ Infrastructure  │
                        │ as Code (IaC)   │
                        └────────┬────────┘
                                 │
          ┌──────────────────────┼──────────────────────┐
          │                      │                      │
          ▼                      ▼                      ▼

  ┌────────────┐       ┌────────────────┐      ┌──────────────┐
  │    VPC     │       │      S3        │      │ DynamoDB     │
  │ IPv4/IPv6  │       │ Public/Private │      │ Users Table  │
  └────────────┘       └────────────────┘      └──────────────┘

          │                      │                      │
          ▼                      ▼                      ▼

  ┌────────────┐       ┌────────────────┐      ┌──────────────┐
  │ IAM Users  │       │ Kinesis Stream │      │ Elastic IP   │
  │ & Policies │       │ Data Streaming │      │ Association  │
  └────────────┘       └────────────────┘      └──────────────┘
```

---

## 📂 Repository Structure

```text
terraform-aws-tasks-solutions/

├── README.md
├── Terraform_Tasks_Solutions_Level_1.md
│
├── images/
│   ├── create-vpc-ipv6.png
│   ├── create-vpc-ipv4.png
│   ├── private-s3-bucket.png
│   ├── public-s3-bucket.png
│   ├── dynamodb-table.png
│   ├── kinesis-stream.png
│   ├── iam-user.png
│   ├── iam-policy.png
│   ├── create-keypair.png
│   └── elastic-ip-association.png
│
├── examples/
│   └── terraform.tfvars
│
└── LICENSE
```

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Terraform | Infrastructure as Code |
| AWS VPC | Network Isolation |
| Amazon S3 | Object Storage |
| DynamoDB | NoSQL Database |
| Kinesis | Data Streaming |
| IAM | Identity & Access Management |
| EC2 | Compute Resources |
| Elastic IP | Static Public IPs |

---

# 📋 Tasks Implemented

---

## ✅ Task 1 – Create VPC with IPv6

Creates an AWS VPC with:

- IPv4 CIDR Block
- Auto-Generated IPv6 CIDR Block
- Resource Tagging

### Skills Demonstrated

- AWS Networking
- IPv6 Configuration
- Terraform Resource Management

### Screenshot

```markdown
![VPC IPv6](images/create-vpc-ipv6.png)
```

---

## ✅ Task 2 – Create VPC with IPv4 CIDR

Creates a custom VPC with an IPv4 CIDR block.

### Skills Demonstrated

- VPC Provisioning
- CIDR Planning
- AWS Networking

### Screenshot

```markdown
![VPC IPv4](images/create-vpc-ipv4.png)
```

---

## ✅ Task 3 – Create Private S3 Bucket

Creates a secure private Amazon S3 bucket.

### Security Controls

- Block Public ACLs
- Block Public Policies
- Restrict Public Access

### Skills Demonstrated

- Cloud Security
- Secure Storage Design
- AWS S3 Governance

### Screenshot

```markdown
![Private S3 Bucket](images/private-s3-bucket.png)
```

---

## ✅ Task 4 – Create Public S3 Bucket

Creates a publicly accessible S3 bucket.

### Skills Demonstrated

- S3 Permissions
- ACL Configuration
- Public Object Hosting

### Screenshot

```markdown
![Public S3 Bucket](images/public-s3-bucket.png)
```

---

## ✅ Task 5 – Create DynamoDB Table

Creates a DynamoDB table using on-demand billing.

### Skills Demonstrated

- NoSQL Databases
- DynamoDB Configuration
- Cost Optimization

### Screenshot

```markdown
![DynamoDB](images/dynamodb-table.png)
```

---

## ✅ Task 6 – Create Kinesis Stream

Creates a Kinesis Data Stream.

### Skills Demonstrated

- Streaming Architectures
- Event Processing
- AWS Data Services

### Screenshot

```markdown
![Kinesis Stream](images/kinesis-stream.png)
```

---

## ✅ Task 7 – Create IAM User

Creates a new IAM user.

### Skills Demonstrated

- Identity Management
- Least Privilege Concepts
- AWS Security

### Screenshot

```markdown
![IAM User](images/iam-user.png)
```

---

## ✅ Task 8 – Attach IAM Policy

Attaches a policy to an IAM user.

### Skills Demonstrated

- IAM Policies
- Permission Management
- Security Governance

### Screenshot

```markdown
![IAM Policy](images/iam-policy.png)
```

---

## ✅ Task 9 – Generate EC2 Key Pair

Creates:

- RSA Private Key
- AWS Key Pair
- Local PEM File

### Skills Demonstrated

- Authentication
- SSH Access Management
- Terraform Providers

### Screenshot

```markdown
![Key Pair](images/create-keypair.png)
```

---

## ✅ Task 10 – Attach Elastic IP

Associates a static Elastic IP with an EC2 instance.

### Skills Demonstrated

- EC2 Management
- Networking
- Public Connectivity

### Screenshot

```markdown
![Elastic IP](images/elastic-ip-association.png)
```

---

# 🎯 Learning Outcomes

By completing these exercises, the following Terraform and AWS skills were demonstrated:

✅ Terraform Resource Management

✅ Infrastructure as Code (IaC)

✅ AWS Networking

✅ Identity and Access Management

✅ S3 Storage Administration

✅ DynamoDB Database Provisioning

✅ Kinesis Stream Configuration

✅ EC2 Security Concepts

✅ Elastic IP Allocation

✅ Cloud Security Best Practices

---

# 🚀 Getting Started

## Prerequisites

- AWS Account
- Terraform Installed
- AWS CLI Configured

Verify installation:

```bash
terraform -version
aws --version
```

---

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/terraform-aws-tasks-solutions.git
cd terraform-aws-tasks-solutions
```

---

## Initialize Terraform

```bash
terraform init
```

---

## Validate Configuration

```bash
terraform validate
```

---

## Review Execution Plan

```bash
terraform plan
```

---

## Deploy Infrastructure

```bash
terraform apply
```

---

# 📚 Key Terraform Concepts Covered

- Providers
- Resources
- Data Sources
- State Management
- Variables
- Outputs
- Resource Dependencies
- Security Controls

---

# 👨‍💻 Author

### Emmanuel Mulenga

**Multi-Cloud Certified Engineer | DevSecOps | Cloud Infrastructure | Cybersecurity**

- AWS
- Terraform
- Azure
- DevSecOps
- Linux
- Kubernetes
- CI/CD

🔗 LinkedIn: https://www.linkedin.com/in/emmanuelmulenga

---

# ⭐ Support

If you found this project helpful:

⭐ Star the repository

🍴 Fork the repository

🛠 Contribute improvements

📢 Share with the community

---

## License

This project is licensed under the MIT License.
