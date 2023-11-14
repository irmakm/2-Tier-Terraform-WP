# 2-Tier-Terraform-WP
Configure the Provider, VPC and Subnets
Remember to create the Key pair wordpressKey.

Deployment 

terraform init
After launching Terraform, we can produce an execution plan to preview the modifications to our AWS infrastructure. The plan describes in detail the resources that will be generated, updated, or eliminated.

terraform plan
We can proceed with deploying our infrastructure on AWS after we are satisfied with the execution plan. Terraform will supply the required resources and configure them to our specifications.

terraform apply
Before proceeding with the deployment, Terraform will ask for confirmation. To proceed, type yes and hit Enter.

It will take some time to complete the deployment procedure.
Terraform will return information about the created resources, including as IP addresses, DNS names, RDS endpoint, user, and database names, once the deployment is complete.

Congratulations! You used Terraform to successfully deploy your WordPress application on a two-tier AWS infrastructure.