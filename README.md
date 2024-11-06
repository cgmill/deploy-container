# Basic Terraform Project
Deploys an AWS pipeline for building and deploying a container to an ECS cluster fronted by a load balancer. I will eventually use this project to spin up infrastructure for bugtracker. Below are the steps to deploy the project.


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
- [ ] Move hardcoded values to variables.tf file
- [X] Break up main.tf into multiple files
- [ ] Refactor resources
- [ ] Review policies for mistakes to ensure nothing is overly permissioned
