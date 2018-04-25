terraform-datadog-timeboard-asg
=================

Terraform module to create Datadog Timeboard for ASG.



Usage
-----

```hcl
module "timeboard_asg_beical-asg" {
  source          = "github.com/traveloka/terraform-datadog-timeboard-asg.git?ref=0.1.0"
  product_domain  = "BEI"
  asg_name        = "beical-asg"
}
```

Terraform Version
-----------------

This module was created using Terraform 0.11.5. 
So to be more safe, Terraform version 0.11.5 or newer is required to use this module.

Authors
-------

* [Karsten Ari Agathon](https://github.com/karstenaa)

License
-------

Apache 2 Licensed. See LICENSE for full details.
