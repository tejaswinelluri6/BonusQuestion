# BonusQuestion
deploying infrastructure using Terraform to the AWS cloud provider
- VPC with public subnets
- Internet Gateway and Route Table
- Security Group for HTTP and SSH access
- Two EC2 instances in separate subnets
- Application Load Balancer (ALB)
- Target Group and Listener for ALB
  
aws configure
# Initialize the Terraform working directory
terraform init
# validate
terraform validate
# See an execution plan
terraform plan          
# Apply the changes to your AWS account
terraform apply   
# destroy all infrastructure
terraform destroy
