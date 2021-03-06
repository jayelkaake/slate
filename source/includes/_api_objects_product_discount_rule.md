# <span class="jumptarget">  Bulk Pricing </span>

Bulk pricing rules applied to a product.

## <span class="jumptarget">  Bulk Pricing Object - Properties </span>

| Name | Type | Description |
| --- | --- | --- |
| id | string | The ID of the bulk discount rule. |
| product_id | int | The ID of the product associated with this bulk discount rule. |
| min | int | The minimum inclusive quantity of a product to satisfy this rule. Must be greater than or equal to zero. |
| max | int | The maximum inclusive quantity of a product to satisfy this rule. Must be greater than the min value, unless this field has a value of 0 (zero), in which case there will be no maximum bound for this rule. |
| type | enum |
| type_value | decimal | The value of the discount |
