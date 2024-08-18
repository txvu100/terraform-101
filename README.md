# Terraform 101

``` bash
terraform init
terraform plan

terraform apply
terraform apply --auto-approve
terraform apply -target aws_instance.web_server
terraform apply -var-file terraform.tfvars

terraform destroy
terraform destroy -target aws_instance.web_server

terraform refresh

terraform state list
terraform state show <resource>
```
