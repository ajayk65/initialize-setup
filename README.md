# initialize-setup

This is initial onetime setup. 
S3 buckets holds tfstate while dynamodb table will hold all history of tfstate.

[Install Terraform](https://www.terraform.io/downloads.html) </br>
Use [AWS Provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs#access_key) to setup the credentials </br>
Clone this repository.

Use below commands to initialze terraform with S3 bucket and DynamoDB as backend.</br>
Execeute the command from the directory where you cloned this project.</br>

**1.** terraform init</br>
**2.** terraform apply -var env=dev/test/prod</br>
