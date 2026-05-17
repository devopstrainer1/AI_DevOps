# Terraform

## What is Terraform?
Terraform is an open-source Infrastructure as Code (IaC) tool for building, changing, and versioning infrastructure safely and efficiently.

## Architecture
- Configuration Files: Define infrastructure resources.
- Providers: Plugins to interact with cloud providers.
- State File: Tracks infrastructure state.

## Example Configuration
```hcl
provider "aws" {
  region = "us-west-2"
}
resource "aws_instance" "example" {
  ami           = "ami-0c55b159cbfafe1f0"
  instance_type = "t2.micro"
}
```
