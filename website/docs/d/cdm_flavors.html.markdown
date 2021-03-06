---
subcategory: "Cloud Data Migration (CDM)"
layout: "huaweicloud"
page_title: "HuaweiCloud: huaweicloud_cdm_flavors"
sidebar_current: "docs-huaweicloud-datasource-cdm-flavors"
description: |-
  Get the flavor information on a HuaweiCloud cdm service.
---

# huaweicloud\_cdm\_flavors

Use this data source to get available Huaweicloud cdm flavors.
This is an alternative to `huaweicloud_cdm_flavors_v1`

## Example Usage

```hcl
data "huaweicloud_cdm_flavors" "flavor" {
}
```

## Attributes Reference

The following attributes are exported:

* `version` -
  The version of the flavor.

* `flavors` -
  Indicates the flavors information. Structure is documented below.

The `flavors` block contains:

* `name` - The name of the cdm flavor.
* `id` - The id of the cdm flavor.
