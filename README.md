# Terraform-Demo-Project

📌 Project Overview
This project demonstrates how to provision AWS infrastructure using Terraform by creating an EC2 instance in a specified AWS region.

🛠️ Technologies Used

* **Terraform** (>= 1.2.0)
* **AWS EC2**
* **AWS Provider (HashiCorp)**
* **Git & GitHub**

📂 Project Structure

```
Terraform-Demo-Project/
│
├── main.tf          # Terraform configuration for AWS EC2
├── README.md        # Project documentation
└── .gitignore       # Ignored Terraform cache & state files
```

⚙️ Terraform Configuration Explained

🔹 Provider Configuration

* Uses **AWS provider**
* Region set to **us-west-2**
* Provider version constrained for stability

🔹 Resource Created

EC2 Instance

  * Instance Type: `t2.micro` (Free Tier eligible)
  * AMI: Amazon Linux AMI
  * Tag: `Terraform_Demo`

🚀 How to Run This Project

1️⃣ Prerequisites

* AWS Account
* Terraform Installed
* AWS CLI configured (`aws configure`)


2️⃣ Initialize Terraform

```bash
terraform init
```

3️⃣ Preview Infrastructure

```bash
terraform plan
```

4️⃣ Create EC2 Instance

```bash
terraform apply
```

Type `yes` when prompted

5️⃣ Destroy Infrastructure (Optional)
bash
terraform destroy

🔐 Best Practices Followed

* Infrastructure as Code (IaC)
* Version-controlled Terraform configuration
* Provider version pinning
* `.terraform` directory excluded using `.gitignore`
* Reproducible and environment-independent setup

📌 Resume Highlights

✔ Designed AWS infrastructure using Terraform
✔ Automated EC2 provisioning with IaC
✔ Applied DevOps best practices
✔ Hands-on experience with AWS & Terraform

👤 Author
- Masoom Maurya
Aspiring DevOps Engineer | Linux | AWS | Terraform | Docker | Kubernates | CI/CD

---
