# terraform-aws-hostedzone
This terraform module creates hosted zones in AWS.

The following resources will be created:
 - Route53 domain - Domains to create a public hosted zone

<!--- BEGIN_TF_DOCS --->

## Requirements

| Name | Version |
|------|---------|
| terraform | >= 0.12.0 |

## Providers

| Name | Version |
|------|---------|
| aws | n/a |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| route53\_domain | Domains to create a public hosted zone | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| route53\_domain | n/a |
| route53\_zone\_ns | n/a |

<!--- END_TF_DOCS --->

## Author

Module managed by [Elumina Group](https://github.com/EluminaGroup).

## License

Apache 2 Licensed. See [LICENSE](https://github.com/EluminaGroup/terraform-aws-hostedzone/blob/master/LICENSE) for full details.
