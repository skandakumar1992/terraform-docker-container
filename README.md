📌 Recommended Order:
Step	   Action	                              Tool
1	     Write Terraform code (main.tf)	    Terraform
2	     Run terraform init	                Terraform
3     Run terraform plan	                Terraform
4	    Run terraform apply	                Terraform
5	    Verify Docker container is working  Docker
6	    Push code to GitHub	                Git
7	    Run terraform destroy (optional)    Terraform

✅ Objective
Provision a Docker container locally using Terraform.

🧰 Tools Required
Terraform (v1.0+)
Docker (running locally)

📁 Step 1: Project Structure (Terraform Side)
    create a folder 
📝 Step 2: Write Terraform Configuration (Terraform Side)
    inside the folder create a main.tf
🔄 Step 3: Initialize Terraform (Terraform Side)
    *terraform init
    *terraform plan
    *terraform apply

    You can now access Nginx in your browser:
    👉 http://localhost:8080
    Also verify using Docker CLI: 
    docker ps
    terraform state list

🌀 Step 4: Initialize Git in the Project
    *git init
    *git add .
    *git commit -m "Initial commit: Provision Docker container using Terraform"

🌐 Step 5: Create a GitHub Repo
   Go to GitHub → Click New Repository
   Name it, e.g., terraform-docker-container

🔗 Step 6: Add Remote and Push
    *git remote add origin https://github.com/skandakumar1992/terraform-docker-container.git
    *git branch -M main
    *git push -u origin main

🧾 Step 7: Files That Will Be Pushed
         File	                                 Purpose
       main.tf	                    Terraform config to provision Docker infra
       README.md 	                   You can add to describe the repo

🧹 Step 8: Destroy Infrastructure
    terraform destroy
