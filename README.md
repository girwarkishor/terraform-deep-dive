# Terraform with AWS

## what is Infrastructure as Code (IaC)
- Ansible
- Chef
- Puppet
- Terraform

## Terraform Setup
- Linux
- MacOS
- Windows

## AWS account creation and AWS CLI setup
- AWS acoount creation and access setup
- AWS CLI configration for terraform AWS provider

## Understanding AWS services
- EC2
- VPC (IGW, RouteTable, Subnet, SecurityGroup etc.,)
- S3
- Key
- IAM
- EBS
- AMI
- ELB
- ASG

## Terraform basic commands and HCL syntax
- terraform commands
  - terraform init
  - terraform validate
  - terraform plan
  - terraform apply
  - terraform destroy
  - terraform fmt/validate/workspace/state

- terraform configuration language syntax
  - blocks
  - arguments
  - attributes
  - meta-arguments
  - identifiers
  - comments

- terraform top-level blocks
  - settings block
  - provider block
  - resource block
  - input variable block
  - output value block
  - local value block
  - data source block
  - modules block

Multiple Providers usage
Dependency Lock File Importance
## Terraform resources
- Resources Syntax and Behavior
- Resources Meta-Argument - depends_on
- Resources Meta-Argument - count
- Resources Meta-Argument - for_each
- Resources Meta-Argument - lifecycle

## Terraform variables
- Basics
- Assign When Prompted
- Override default with cli var
- Override with environment variables
- Assign with terraform.tfvars
- Assign with tfvars var-file argument
- Assign with auto tfvars
- Lists & Maps
- Validation Rules
- Sensitive Input Variables

## Terraform Functions
- Filesystem
- Collection
- String
- Numeric

## Terraform Values
- Output values
- Local values

## Terraform datasources
- datasource arguments
- lifecycle

## Terraform Backends
- Local State Storage
- Remote State Storage
  - S3 bucket
- State Commands

## Terraform Workspaces
- CLI Workspaces with local backend
- CLI Workspaces with remote backend

## Terraform Provisioners
- File Provisioner
- local-exec Provisioner
- remote-exec Provisioner
- Null Resource

## Terraform Modules
- Modules from Public Registry
- Build Local Module

## Terraform Cloud
- Terraform Cloud - VCS-Driven Worflow
- Terraform Cloud - CLI-Driven Worflow
- Terraform Cloud - Share modules in private module registry
- Migrate State to Terraform Cloud
- Basic Sentinel Policies
- Cost Control Sentinel Policies
- CIS Sentinel Policies
- State Import

## Terraform Graph

## Terraform Expressions
- Dynamic Expressions
- Dynamic Blocks
