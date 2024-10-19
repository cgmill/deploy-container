# Basic Terraform Project
Deploys an AWS pipeline for building and deploying a container to an ECS cluster fronted by a load balancer. Below are the steps to deploy the project.


# Usage
To deploy the terraform project, run the following commands:
```
terraform init
terraform apply
```

After deployment, log into your AWS console, navigate to CodePipeline, and update the connection to your GitHub repository.

To destroy the project, run the following command:
```
terraform destroy
```

# TODO
- Move hardcoded values to variables.tf file
    - GitHub repository
- ~ Break up main.tf into multiple files ~ 
- Rename resources
- Review policies for mistakes and principal of least privilege
