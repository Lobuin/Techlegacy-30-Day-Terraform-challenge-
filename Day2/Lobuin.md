# Setting up Terraform, Creating AWS, Installing VS code

## Participant name

**Ngwa Dieudonne Lobuin/ Techlegacy**
### task Completed

- [x] **setting up AWS account**
- [x] **Installed AWS CLI and configured**
- [x] **Install Visual Studio Code (VSCode) and added hashicorp terraform**
- [x] **Configured VSCode to work with AWS.**
- [x] **Deployed and single server and a web server**

```chl
provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "example" {
ami = "ami-07cc1bbe145f35b58"
instance_type = "t2.micro"
}
```
