# Terraform External Module

This Terraform module creates an S3 bucket with configurable settings.

## Usage

```hcl
module "example" {
  source = "github.com/your-username/terraform-external-module"

  bucket_name = "my-example-bucket"
}
