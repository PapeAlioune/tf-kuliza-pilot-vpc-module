# Terraform, VPC, and AWS (oh my!)

This module enable provisionning VPC in AWS.

## PS:
You will need to set AWS profile in order to let Terraform use the credentials

## Build Process

```bash
# Initialize VPC Module
terraform init

# List the ressources that will be created
terraform plan

# Provision by applying TF config
terraform apply -f

# Clean Up
terraform destroy
```

## Verifying VPC provision

You can validate the VPC provisionning by going through AWS VPC console

