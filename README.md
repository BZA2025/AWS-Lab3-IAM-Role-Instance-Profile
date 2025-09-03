# ⚡ Lab 3 – AWS VPC Networking & Subnetting

## 📌 Overview
In this lab, I designed and implemented a **custom Amazon VPC** with multiple subnets, route tables, and security controls. The objective was to practice **network segmentation** and enforce clear separation between **public, private, and database layers** while applying AWS networking best practices.

This lab built the foundation for later labs (e.g., **Lab 6 – 3-Tier Web Application**) by establishing a reusable VPC design.

---

## 🏗️ Architecture Components
- **Amazon VPC** with CIDR block (10.0.0.0/16)  
- **Public subnets** for internet-facing resources  
- **Private subnets** for application workloads  
- **Database subnets** isolated with no direct internet access  
- **Internet Gateway (IGW)** and **NAT Gateway** for routing  
- **Route Tables** directing traffic between tiers  
- **Security Groups (SGs) & NACLs** enforcing least-privilege access  

---

## 🔑 Key Steps Completed
- Created a custom VPC with **CIDR 10.0.0.0/16**  
- Configured **2 public**, **2 private**, and **2 database** subnets across AZs  
- Attached an **Internet Gateway** and a **NAT Gateway** for outbound connectivity  
- Built **custom route tables** for each subnet tier  
- Applied **Security Groups & NACLs** to enforce tier-based communication rules  

---

## ✅ Skills Demonstrated
- AWS VPC design and subnetting strategy  
- Routing table and NAT Gateway configuration  
- Multi-AZ design for high availability  
- Security Groups vs. NACLs for layered protection  
- Network isolation for secure architectures  

---

## 🚀 Next Steps
- Extend VPC design to host **EC2 instances** (Lab 4)  
- Integrate **RDS database layer** into private subnets  
- Apply **Terraform** for IaC automation in later labs  

---

📂 **Repository:** [Lab 3 – AWS VPC Networking & Subnetting]
