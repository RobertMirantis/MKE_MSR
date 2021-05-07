# MKE_MSR
Create a 3 node cluster using Terraform (TF). Builds 1 master, 1 worker and an own MSR.

terraform init
terraform apply [ --auto-approve ]
terraform destroy [ --auto-approve ]

Please take care of installation of Terraform and AWS CLI.
Don't forget to update your todays AWS credentials in ~/.aws/credentials.
