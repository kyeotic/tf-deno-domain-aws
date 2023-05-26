# tf-deno-domain-aws

Route53 Terraform setup for a Deno Deploy Domain

```hcl
module "domain" {
  source      = "github.com/kyeotic/tf-deno-domain-aws"
  zone_name   = "kye.dev"
  domain_name = "site.kye.dev"
  deno_acme   = "123456._amce.deno.dev."
}
```