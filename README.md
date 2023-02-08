# terraform-devops-cicd
terraform-devops-cicd



Usefull tools and commands in dev1.0 branch (terraform and jenkins)  
Pre-requisites to run the project:  
    Locally in your system  
        Install - Git, AWS-CLI and terraform  
        configure aws-cli with your access and secret key by the command - aws configure  
        
[Git commands](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html):  
git clone <url> - To clone the remote repository locally  
  Add your values in the provider.yaml file (with your aws s3 bucket)  
  
[Terraform commands](https://developer.hashicorp.com/terraform/cli/commands):  
  terraform init -  Prepare your working directory for other commands  
  terraform fmt - To formact the code  
  terraform validate - Check whether the configuration is valid  
  terraform plan - Show changes required by the current configuration  
  terraform apply -  Create or update infrastructure  
  terraform destroy - Destroy previously-created infrastructure  
  

  


Usefull tools and commands in dev1.0 branch (terraform and Github actions)

