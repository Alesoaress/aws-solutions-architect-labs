# ☁️ AWS Solutions Architect Labs

Welcome! 👋

This repository documents my practical journey studying AWS Cloud through hands-on labs, real-world scenarios, and AWS best practices.

The objective is to build production-inspired cloud environments while preparing for the **AWS Certified Solutions Architect – Associate (SAA-C03)** certification and developing a professional Cloud Engineering portfolio.

---

## 🎯 Goals

- Learn AWS through hands-on labs
- Build secure, highly available, and scalable cloud architectures
- Understand AWS best practices
- Practice troubleshooting and problem-solving
- Develop practical experience with AWS infrastructure
- Prepare for AWS Certified Solutions Architect – Associate (SAA-C03)
- Build a professional Cloud Engineering portfolio

---

## 🛠️ Technologies & AWS Services

### ✅ Completed

- AWS Identity and Access Management (IAM)
- Amazon VPC
- Amazon S3
- Amazon RDS
- Amazon EC2
- Amazon EBS
- Elastic Load Balancing (Application Load Balancer)
- Amazon EC2 Auto Scaling

### ⏳ Currently Studying

- Amazon Route 53
- DNS and AWS networking services

### 🔒 Planned

- Amazon ECS
- Amazon ECR
- AWS Lambda
- Amazon API Gateway
- Amazon CloudWatch (advanced monitoring)
- Amazon SNS
- Amazon SQS
- AWS KMS
- AWS Secrets Manager
- AWS Systems Manager
- AWS Security Services
- AWS Analytics Services
- AWS AI & Machine Learning Services
- AWS Cost Management & FinOps

### 🚀 Future Studies

- Docker
- Terraform
- GitHub Actions
- CI/CD
- Kubernetes (Amazon EKS)

---

## 📚 Labs

| Lab | Status |
| --- | --- |
| [01 - IAM - Secure Access Management](01-secure-access-management/) | ✅ Completed |
| [02 - VPC - Network Foundation](02-network-foundation/) | ✅ Completed |
| [03 - S3 - Storage Services](03-storage-services/) | ✅ Completed |
| [04 - RDS - Database Services](04-database-services/) | ✅ Completed |
| [05 - EC2 & EBS - Compute & Block Storage](lab-05-ec2-ebs/) | ✅ Completed |
| [06 - Elastic Load Balancing & Auto Scaling](06-load-balancing-auto-scaling/) | ✅ Completed |
| 07 - Route 53 & DNS | ⏳ Next Lab |
| 08 - Containers & Serverless | 🔒 Locked |
| 09 - Monitoring & Governance | 🔒 Locked |
| 10 - Messaging & Integration | 🔒 Locked |
| 11 - Security & Cryptography | 🔒 Locked |
| 12 - Big Data & Analytics | 🔒 Locked |
| 13 - AI & Machine Learning | 🔒 Locked |
| 14 - FinOps | 🔒 Locked |

---

## 🧪 Hands-on Experience

Throughout the labs, the following practical scenarios have been implemented:

### 🔐 Identity & Access Management

- IAM users, groups, and policies
- Multi-Factor Authentication (MFA)
- Access permissions and security best practices

### 🌐 Networking

- Custom VPC and public subnet configuration
- Internet Gateway and Route Tables
- Security Groups and Network ACLs
- Multi-Availability Zone network configuration
- Network access control between AWS resources

### 🗄️ Storage & Databases

- Amazon S3 storage configuration and lifecycle policies
- S3 versioning and pre-signed URLs
- Amazon RDS database deployment and administration
- Database connectivity and monitoring
- Amazon EBS volume creation and attachment
- XFS filesystem configuration and mounting
- Persistent EBS mounting using `/etc/fstab`
- EBS persistence validation after EC2 reboot
- EBS Snapshot creation
- EBS Snapshot restoration and data recovery

### 💻 Compute & Web Servers

- Amazon EC2 instance deployment
- Apache HTTP Server installation and configuration
- SSH remote access to EC2
- EC2 User Data automation
- EC2 Launch Template creation and version management
- Web application connectivity validation

### ⚖️ Load Balancing & Auto Scaling

- Application Load Balancer deployment
- Internet-facing HTTP listener configuration
- Target Group creation and configuration
- HTTP health check implementation
- Multi-AZ EC2 deployment
- Auto Scaling Group configuration
- Minimum, desired, and maximum instance capacity configuration
- ELB-based instance health checks
- Automated instance replacement through Instance Refresh
- Launch Template version updates
- HTTP connectivity testing using PowerShell
- Successful validation of HTTP 200 responses

### 🔧 Troubleshooting & Problem-Solving

- Security Group and Network ACL communication
- Public subnet internet connectivity
- EC2 SSH connectivity
- Web server accessibility
- Database connectivity
- EBS filesystem configuration
- Persistent storage after instance reboot
- Snapshot-based data recovery
- EC2 User Data initialization failures
- Target Group health check troubleshooting
- Launch Template configuration updates
- Auto Scaling instance replacement validation

---

## 📂 Repository Structure

```text
aws-solutions-architect-labs/
│
├── 01-secure-access-management/
├── 02-network-foundation/
├── 03-storage-services/
├── 04-database-services/
│
├── lab-05-ec2-ebs/
│   ├── README.md
│   ├── architecture.png
│   └── evidencias/
│
├── 06-load-balancing-auto-scaling/
│   ├── README.md
│   └── evidencias/
│       ├── 01-vpc-multi-az.png
│       ├── 02-alb-security-group.png
│       ├── 03-ec2-security-group.png
│       ├── 04-launch-template.png
│       ├── 05-target-group.png
│       ├── 06-target-group-health-check.png
│       ├── 07-application-load-balancer.png
│       ├── 08-alb-listener.png
│       ├── 09-auto-scaling-group.png
│       ├── 10-asg-ec2-instances.png
│       ├── 11 - instance-refresh-success.png
│       └── architecture.png
│
├── LICENSE
└── README.md
```

Future laboratory directories will be added as each project is implemented.

Each completed lab contains:

- 📄 Technical documentation
- 🏗️ Architecture diagram
- 📸 Implementation evidence
- 🧠 Key learnings
- ✅ AWS best practices
- 🔧 Troubleshooting scenarios

---

## 🏗️ Architecture & Troubleshooting

The labs are designed not only to deploy AWS services, but also to understand how the components interact within a cloud architecture.

The projects progressively introduce more advanced infrastructure concepts, from identity management and networking to compute, storage, databases, load balancing, and automated instance management.

### High Availability & Scalability

Lab 06 introduced a multi-AZ web application architecture using an Application Load Balancer and Amazon EC2 Auto Scaling.

The infrastructure included:

- An internet-facing Application Load Balancer
- Two EC2 instances distributed across separate Availability Zones
- A Target Group with HTTP health checks
- An Auto Scaling Group configured to maintain two instances
- A Launch Template with automated Apache provisioning

The lab also included troubleshooting an EC2 initialization issue, updating the Launch Template, and successfully replacing instances using Instance Refresh.

Dynamic CPU-based scaling was not tested and remains a topic for future practical exercises.

### Practical Troubleshooting

The projects include scenarios involving:

- Network communication and access permissions
- EC2 connectivity and application availability
- Database connectivity and administration
- Persistent block storage and recovery
- Web server initialization
- Application Load Balancer health checks
- EC2 instance replacement and configuration updates

The goal is to understand **why the architecture works**, not only how to create AWS resources.

---

## 📌 Certifications

- ✅ AWS Certified Cloud Practitioner (CLF-C02)
- 🎯 Studying for AWS Certified Solutions Architect – Associate (SAA-C03)

---

## 🎯 Career Focus

Developing practical skills in:

**Cloud Computing • AWS • Infrastructure • DevOps • Cloud Architecture • High Availability • Troubleshooting**

---

## 👨‍💻 Author

**Carlos Alexandre Soares**

Cloud Computing • AWS • DevOps • Infrastructure

---

⭐ This repository will be continuously updated as new AWS labs and cloud engineering projects are completed.
