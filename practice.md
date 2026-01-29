### Lesson Day-1 is all about the why is terraform , why terraform and uses of terraform, installtion and setup
 --> basic commands :
    1.terraform init : initilizlize the terrafom directory and download the providers configuration
    2.terraform validate : validates the syntaxt errors, like , if the syntax is intact or  not.?
    3.terraform plan : it's kind of dry run which will show us the information such as what all the resources are going to created
    4.terrafrom apply --auto-approve : this will execute the terrafrom scripts to provisiom the infrastructure.
    5.terraform destroy --auto-approve : This will destroy the entire infra.


### Lesson Day-2 is all about the terraform providers
# Q1: Providers are the plugins that allows terraformt to intercat with the aws, azure,gcp

<!-- terraform {
    required_proviers {
        aws = {
         source  = "hashicorp/aws"
         version = ">= 5.0   
        }
    }
}

provider "aws" {
    region = "us-east-1"
} -->

### Lesson Day-3 : In day , we will learn about the how to install and configure kubectl and configure aws credentails using commands such as "aws configure" .
# now create an s3 bucket using terrafrom 

<!-- terraform {
    required_provider{
        aws = {
          source  = "hashicorp/aws"
            version = ">= 5.0    
        }
    }
}
provider "aws"{
    region = "us-east-1"
}

resource "aws_s3_bucket" "This is the dummy bucket" {
    bucket = "This is the dummy bucket"

    tags = {
        name = "Duummy Bucket"
        environment = "Dev"
    }
} -->
