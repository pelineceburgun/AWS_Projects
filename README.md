# 📘 AWS Projects Documentation

This repository contains documentation of my hands-on AWS projects, each focused on learning and applying different AWS services through practical, real-world scenarios.

## 🚀 Projects

### 🔐 IAM & EC2 Access Management 
**Services:** AWS IAM, Amazon EC2

In this project, I worked on managing authentication and authorization in AWS by simulating a real-world DevOps scenario at NextWork.

**What I did:**
- Launched development and production EC2 instances
- Used EC2 tags to separate environments
- Created IAM policies with tag-based access control
- Set up IAM user groups and users (intern onboarding)
- Restricted intern access to development resources only
- Tested permissions using the IAM Policy Simulator
- Configured an Account Alias for easier login

**Key Concepts Learned:**
- Principle of least privilege
- Tag-based access control
- Secure user and permission management
- Safe policy testing without impacting production

---

### 🌐 Host a Static Website Using S3
**Services:** Amazon S3

Hosted a static website using an Amazon S3 bucket.

**Key Implementations:**
- Bucket configuration for static website hosting
- Public access settings
- Object permissions and access policies

---

### 📊 Analytics with QuickSight
**Services:** AWS QuickSight

Analyzed a Netflix dataset using AWS QuickSight.

**Key Implementations:**
- Importing and preparing data
- Creating visual dashboards
- Gaining insights through interactive analytics

---

### 🤖 AI Lex – Chatbot Development
**Services:** Amazon Lex

Built a conversational chatbot using Amazon Lex.

**Key Focus Areas:**
- Intents, utterances, and slots
- Basic conversation flows
- Testing and deploying the chatbot

---

### 🤖 AI Lex – Part 2 (Advanced Features)
**Services:** Amazon Lex

Enhanced the chatbot with advanced capabilities.

**Key Improvements:**
- Adding custom responses
- Improving conversation logic
- Implementing additional features and refinements

### 🌐 Build a Secure VPC
**Services:** Amazon VPC, Subnets, Internet Gateway
Designed and deployed a Virtual Private Cloud (VPC) to create a secure and organized cloud network environment.

**Key Implementations:**

-Created a VPC with a custom IPv4 CIDR block

-Divided the VPC into public and private subnets

-Enabled auto-assign public IPv4 addresses for the public subnet

-Created and attached an Internet Gateway to allow internet connectivity
### 🌐 VPC Traffic Flow & Security
**Services:** Amazon VPC, Subnets, Internet Gateway, Route Tables, Security Groups, Network ACLs

Designed and deployed a secure VPC network in AWS, focusing on traffic flow management and layered security controls.

**Key Implementations:**


-Configured public and private subnets to segment resources
-Attached an Internet Gateway and set up route tables to direct traffic
-Implemented security groups to control inbound/outbound traffic at the resource level
-Configured Network ACLs for additional subnet-level traffic control
-Applied security best practices for both inbound and outbound traffic rules

### 🌐 Creating a Private Subnet
**Services:** Amazon VPC, Subnets, Route Tables, Network ACLs
Extended the secure VPC architecture by adding a private subnet with dedicated routing and access control, isolating backend resources from the public internet.
Key Implementations:
- Created a private subnet within an existing VPC
- Built a dedicated private route table with local-only routing (no internet gateway route)
- Detached the private subnet from the main route table to prevent accidental internet exposure
- Configured a custom Network ACL for the private subnet allowing only intra-VPC traffic
- Applied defense-in-depth principles using both route table isolation and NACL restrictions
### 🚀 Launching VPC Resources
**Services:** Amazon VPC, Amazon EC2, Key Pairs, Security Groups
Launched EC2 instances within the custom VPC infrastructure to understand secure cloud compute deployment and remote access patterns.
**Key Implementations:**
-Created a new EC2 instance (t2.micro) within the custom VPC
-Generated and downloaded an SSH key pair for secure authentication
-Configured security group rules to allow SSH (port 22) access from my IP address
-Assigned the EC2 instance to the public subnet within the VPC
-Enabled auto-assign public IPv4 address for direct internet accessibility
-Connected to the EC2 instance via SSH using the private key (.pem format)
-Verified instance connectivity and tested basic commands


## 🎯 Purpose of This Repository

This repository serves as a learning journal and portfolio to document my progress with AWS services, cloud security, analytics, and AI-based solutions through hands-on projects.
