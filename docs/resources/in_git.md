---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "sealedsecret_in_git Resource - terraform-provider-sealedsecret"
subcategory: ""
description: |-
  
---

# sealedsecret_in_git (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **filepath** (String) The filepath in the Git repository. Including the filename itself and extension
- **name** (String) name of the secret, must be unique
- **namespace** (String) namespace of the secret

### Optional

- **data** (Map of String, Sensitive) Key/value pairs to populate the secret. The value will be base64 encoded
- **id** (String) The ID of this resource.
- **string_data** (Map of String, Sensitive) Key/value pairs to populate the secret.
- **type** (String) The secret type (ex. Opaque)

### Read-Only

- **public_key_hash** (String) The public key hashed to detect if the public key changes.


