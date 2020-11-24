# Key Distributor Cloud Function

This example illustrates how to use the `key-distributor` submodule to generate a secure service account key distribution Cloud Function

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| cfn\_members | List of Cloud Function invokers in IAM member format | `list(string)` | n/a | yes |
| project\_id | The ID of the project in which to provision resources. | `string` | n/a | yes |
| public\_key\_file | ASCII armored PGP public key file | `string` | n/a | yes |
| region | Region where the Cloud Function will be launched | `string` | `"us-central1"` | no |

## Outputs

| Name | Description |
|------|-------------|
| function\_name | n/a |
| project\_id | n/a |
| region | n/a |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

To provision this example, run the following from within this directory:
- `terraform init` to get the plugins
- `terraform plan` to see the infrastructure plan
- `terraform apply` to apply the infrastructure build
- `terraform destroy` to destroy the built infrastructure
