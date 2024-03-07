# This is an example please modify
# AWS RDS Aurora MySQL

This terraform module creates ...

## Quick Links
 * [AWS Terraform Documentation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)

## Example Usage
```
module "example" {
  source                 = "truemark/terraform-template"
  version                = "0.0.1"
  database_name          = "example"
  deletion_protection    = true
}
```
## Parameters
The following parameters are supported:

- apply_immediately
- allowed_cidr_blocks
- auto_minor_version_upgrade
- backup_retention_period
- ca_cert_identifier
