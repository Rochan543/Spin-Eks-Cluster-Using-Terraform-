# Terraform-


To upload a document to Git containing the complete picture of your EKS cluster configuration, follow these steps:

1. Prepare the Document
Consolidate all your Terraform files (main.tf, variables.tf, outputs.tf, etc.) into a single directory.
Add a README file (README.md) to explain the purpose of the configuration, its components, and how to use it.
Example README.md:

markdown
Copy code
# EKS Cluster Configuration with Terraform

This repository contains the Terraform configuration files to deploy an Amazon EKS cluster.

## Files
- `main.tf`: Main configuration file for AWS resources.
- `variables.tf`: Input variables for customization.
- `outputs.tf`: Outputs for cluster details after deployment.

## Usage
1. Initialize Terraform:
   ```bash
   terraform init
2. To preview the changes Terraform will make to your infrastructure without applying them.
   ```bash
   terraform plan
3. To apply the changes specified in your Terraform configuration files and execute the plan.
   ```bash
   terraform apply


## Spin EKS Cluster Using Terraform Script 
This documentation provides a step-by-step guide to creating an Amazon Elastic Kubernetes Service (EKS) cluster using Terraform, with a focus on addressing the omission of the IAM user. The steps include an explanation of the Terraform script and necessary modifications 
## Prerequisites 
## Required Tools: 
• Terraform installed on your local system. 
• AWS CLI configured with your credentials.

![Screenshot 2025-01-15 091116](https://github.com/user-attachments/assets/1079314d-978e-49a6-890a-92d50d05582c)

## 1. Folder Structure 
project-root/ 
├── main.tf       
     # Core Terraform configuration 
├── variables.tf       # Input variable definitions 
├── outputs.tf       
  # Output definitions 
└── README.md          # Documentation 
## 2. IAM User Creation:

![Screenshot 2025-01-15 091342](https://github.com/user-attachments/assets/3544effb-673d-4b27-a82a-5e638e5887ca)
![Screenshot 2025-01-15 091404](https://github.com/user-attachments/assets/dc6fc1b1-90cb-4e5b-a86c-a61559ba6426)
![Screenshot 2025-01-15 091433](https://github.com/user-attachments/assets/6e65d867-8672-4046-a7c4-32c082c455e9)
![Screenshot 2025-01-15 091501](https://github.com/user-attachments/assets/2ed1d5f2-40ed-49c3-a9a8-c84a202cbba1)
![Screenshot 2025-01-15 091540](https://github.com/user-attachments/assets/877aa2a8-e279-409e-93bd-6254b5819e99)
![Screenshot 2025-01-15 091652](https://github.com/user-attachments/assets/1b3509e4-c660-464e-92d5-5b141814d2f4)
![Screenshot 2025-01-15 091717](https://github.com/user-attachments/assets/314791a1-9d85-4711-802d-fe86fec279d8)
![Screenshot 2025-01-15 091743](https://github.com/user-attachments/assets/46895b8b-c9d1-471b-a874-a6e9ec4559e5)
![Screenshot 2025-01-15 091809](https://github.com/user-attachments/assets/ab02c299-f116-41ac-ad17-dfa4e8073293)
![Screenshot 2025-01-15 091844](https://github.com/user-attachments/assets/74022056-c68e-4973-9bff-e5e7407a5a0c)
![Screenshot 2025-01-15 092032](https://github.com/user-attachments/assets/14b1aff7-6546-48fd-a521-cf01b0408046)
![image](https://github.com/user-attachments/assets/948b88bd-42ac-4418-a352-38f109f93196)
![Screenshot 2025-01-15 092128](https://github.com/user-attachments/assets/b947e586-27b5-4f5b-b18d-b679adf4a01f)
![Screenshot 2025-01-15 092202](https://github.com/user-attachments/assets/0eff68c3-d9d9-4203-9e85-dcd5e2397b34)
![Screenshot 2025-01-15 092247](https://github.com/user-attachments/assets/77b3c142-8670-46ea-8a2b-c3fb267f09fd)

## Conclusion 
This configuration demonstrates a complete setup for deploying a scalable and secure EKS cluster on AWS. It’s designed for flexibility, allowing easy modifications to suit specific requirements. If you're interested in modern DevOps practices or cloud-native solutions, this is a great starting point!
















