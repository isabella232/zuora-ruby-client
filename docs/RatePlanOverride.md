# Zuora::RatePlanOverride

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**charge_overrides** | [**Array&lt;ChargeOverride&gt;**](ChargeOverride.md) |  | [optional] 
**custom_fields** | [**CustomFields**](CustomFields.md) |  | [optional] 
**product_rate_plan_id** | **String** |  | 
**unique_token** | **String** | A unique string to represent the rate plan charge in the order. The unique token is used to perform multiple actions against a newly added rate plan. For example, if you want to add and update a product in the same order, you would assign a unique token to the product rate plan when added and use that token in future order actions. | [optional] 


