# terraform-vpc-august

module "august" {
  source  = "Dalerino/august/vpc"
  version = "1.0.0"
  region = "us-east-2"
  vpc_cidr = "10.0.0.0/16"
}