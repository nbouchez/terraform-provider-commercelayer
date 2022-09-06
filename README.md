<!-- Code generated by gomarkdoc. DO NOT EDIT -->

# commercelayer

```go
import "github.com/incentro-dc/terraform-provider-commercelayer/commercelayer"
```

## Index

- [Constants](<#constants>)
- [func Provider() *schema.Provider](<#func-provider>)
- [func boolRef(val interface{}) *bool](<#func-boolref>)
- [func diagErr(err error) diag.Diagnostics](<#func-diagerr>)
- [func float64ToFloat32Ref(val interface{}) *float32](<#func-float64tofloat32ref>)
- [func keyValueRef(val interface{}) map[string]interface{}](<#func-keyvalueref>)
- [func providerConfigureFunc(ctx context.Context, d *schema.ResourceData) (interface{}, diag.Diagnostics)](<#func-providerconfigurefunc>)
- [func resourceAddress() *schema.Resource](<#func-resourceaddress>)
- [func resourceAddressCreateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourceaddresscreatefunc>)
- [func resourceAddressDeleteFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourceaddressdeletefunc>)
- [func resourceAddressReadFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourceaddressreadfunc>)
- [func resourceAddressUpdateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourceaddressupdatefunc>)
- [func resourceCustomerGroup() *schema.Resource](<#func-resourcecustomergroup>)
- [func resourceCustomerGroupCreateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcecustomergroupcreatefunc>)
- [func resourceCustomerGroupDeleteFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcecustomergroupdeletefunc>)
- [func resourceCustomerGroupReadFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcecustomergroupreadfunc>)
- [func resourceCustomerGroupUpdateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcecustomergroupupdatefunc>)
- [func resourceMerchant() *schema.Resource](<#func-resourcemerchant>)
- [func resourceMerchantCreateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcemerchantcreatefunc>)
- [func resourceMerchantDeleteFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcemerchantdeletefunc>)
- [func resourceMerchantReadFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcemerchantreadfunc>)
- [func resourceMerchantUpdateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcemerchantupdatefunc>)
- [func resourcePriceList() *schema.Resource](<#func-resourcepricelist>)
- [func resourcePriceListCreateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcepricelistcreatefunc>)
- [func resourcePriceListDeleteFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcepricelistdeletefunc>)
- [func resourcePriceListReadFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcepricelistreadfunc>)
- [func resourcePriceListUpdateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics](<#func-resourcepricelistupdatefunc>)
- [func stringRef(val interface{}) *string](<#func-stringref>)


## Constants

```go
const (
    addressType       = "addresses"
    merchantType      = "merchants"
    customerGroupType = "customer_groups"
    priceListType     = "price_lists"
)
```

## func [Provider](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/provider.go#L11>)

```go
func Provider() *schema.Provider
```

## func [boolRef](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/util.go#L38>)

```go
func boolRef(val interface{}) *bool
```

## func [diagErr](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/util.go#L8>)

```go
func diagErr(err error) diag.Diagnostics
```

## func [float64ToFloat32Ref](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/util.go#L48>)

```go
func float64ToFloat32Ref(val interface{}) *float32
```

## func [keyValueRef](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/util.go#L27>)

```go
func keyValueRef(val interface{}) map[string]interface{}
```

## func [providerConfigureFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/provider.go#L51>)

```go
func providerConfigureFunc(ctx context.Context, d *schema.ResourceData) (interface{}, diag.Diagnostics)
```

## func [resourceAddress](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_addresses.go#L10>)

```go
func resourceAddress() *schema.Resource
```

## func [resourceAddressCreateFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_addresses.go#L180>)

```go
func resourceAddressCreateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceAddressDeleteFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_addresses.go#L223>)

```go
func resourceAddressDeleteFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceAddressReadFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_addresses.go#L161>)

```go
func resourceAddressReadFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceAddressUpdateFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_addresses.go#L229>)

```go
func resourceAddressUpdateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceCustomerGroup](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_customer_groups.go#L10>)

```go
func resourceCustomerGroup() *schema.Resource
```

## func [resourceCustomerGroupCreateFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_customer_groups.go#L88>)

```go
func resourceCustomerGroupCreateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceCustomerGroupDeleteFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_customer_groups.go#L115>)

```go
func resourceCustomerGroupDeleteFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceCustomerGroupReadFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_customer_groups.go#L68>)

```go
func resourceCustomerGroupReadFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceCustomerGroupUpdateFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_customer_groups.go#L122>)

```go
func resourceCustomerGroupUpdateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceMerchant](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_merchants.go#L11>)

```go
func resourceMerchant() *schema.Resource
```

## func [resourceMerchantCreateFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_merchants.go#L89>)

```go
func resourceMerchantCreateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceMerchantDeleteFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_merchants.go#L125>)

```go
func resourceMerchantDeleteFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceMerchantReadFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_merchants.go#L85>)

```go
func resourceMerchantReadFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourceMerchantUpdateFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_merchants.go#L129>)

```go
func resourceMerchantUpdateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourcePriceList](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_price_list.go#L10>)

```go
func resourcePriceList() *schema.Resource
```

## func [resourcePriceListCreateFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_price_list.go#L98>)

```go
func resourcePriceListCreateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourcePriceListDeleteFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_price_list.go#L127>)

```go
func resourcePriceListDeleteFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourcePriceListReadFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_price_list.go#L78>)

```go
func resourcePriceListReadFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [resourcePriceListUpdateFunc](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/resource_price_list.go#L134>)

```go
func resourcePriceListUpdateFunc(ctx context.Context, d *schema.ResourceData, i interface{}) diag.Diagnostics
```

## func [stringRef](<https://github.com/incentro-dc/terraform-provider-commercelayer/blob/main/commercelayer/util.go#L16>)

```go
func stringRef(val interface{}) *string
```



Generated by [gomarkdoc](<https://github.com/princjef/gomarkdoc>)

<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_commercelayer"></a> [commercelayer](#requirement\_commercelayer) | >= 0.0.1 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_commercelayer"></a> [commercelayer](#provider\_commercelayer) | >= 0.0.1 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [commercelayer_address.incentro_address](https://registry.terraform.io/providers/incentro-dc/commercelayer/latest/docs/resources/address) | resource |
| [commercelayer_customer_group.incentro_customer_group](https://registry.terraform.io/providers/incentro-dc/commercelayer/latest/docs/resources/customer_group) | resource |
| [commercelayer_price_list.incentro_price_list](https://registry.terraform.io/providers/incentro-dc/commercelayer/latest/docs/resources/price_list) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_api_endpoint"></a> [api\_endpoint](#input\_api\_endpoint) | n/a | `string` | n/a | yes |
| <a name="input_auth_endpoint"></a> [auth\_endpoint](#input\_auth\_endpoint) | n/a | `string` | n/a | yes |
| <a name="input_client_id"></a> [client\_id](#input\_client\_id) | n/a | `string` | n/a | yes |
| <a name="input_client_secret"></a> [client\_secret](#input\_client\_secret) | n/a | `string` | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->