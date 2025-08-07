# terraform-docker-task
Task 3 - Provision NGINX Docker container using Terraform
# Terraform Docker Task: Deploy Nginx Container

This project demonstrates how to use **Terraform** to deploy an **Nginx** Docker container locally.

## 🚀 Objective

Automate the provisioning of a Docker container running Nginx using Terraform.

## 🧰 Tech Stack

- **Terraform**
- **Docker**
- **Nginx**
- **Ubuntu** (via MobaXterm or WSL)

## 📁 Folder Structure

terraform-docker-task/
├── main.tf
├── variables.tf
├── outputs.tf
├── provider.tf
├── terraform.tfstate
├── README.md
## ⚙️ Prerequisites

- Docker installed and running
- Terraform installed
- MobaXterm or Linux terminal (WSL/Ubuntu)

## 📦 How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/abhilashshivarchaka/terraform-docker-task.git
   cd terraform-docker-task

2. Initialize Terraform
  terraform init
3. Check the Terraform Plan
  terraform plan
4. Apply the Configuration
  terraform apply

5. Access Nginx
Open your browser and go to:
👉 http://localhost:9090

You should see the Nginx welcome page.

🧹 Tear Down
To remove the container and image:

terraform destroy
If you get an error related to image conflicts, force remove the image manually:

docker rmi -f nginx:latest
🙋‍♂️ Author
Abhilash Shivarchaka

GitHub: @abhilashshivarchaka
