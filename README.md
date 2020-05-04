## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| aws | n/a |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| description | IAM role description | `any` | n/a | yes |
| name | IAM role name | `any` | n/a | yes |
| policies | A list of IAM policy ARNs to attach to the role | `list(string)` | `[]` | no |
| role\_path | The path applied to the IAM role | `string` | `"/"` | no |

## Outputs

No output.

