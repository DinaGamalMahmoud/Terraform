# Terraform
Creating a Ghost Blog Terraform Module from "Using Terraform to Manage Applications and Infrastructure course" on Linux Academy

To Deploy the infrastructure:
>> Initialize Terraform
               terraform init

>> Generate a Terraform plan:
               terraform plan -out=tfplan -var image_name=ghost:alpine -var ext_port=8080
               
>> Apply Terraform plan
               terraform apply tfplan
