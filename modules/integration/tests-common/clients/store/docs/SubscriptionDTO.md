
# SubscriptionDTO

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**subscriptionId** | **String** | The UUID of the subscription |  [optional]
**applicationId** | **String** | The UUID of the application | 
**apiId** | **String** | The unique identifier of the API. |  [optional]
**apiInfo** | [**APIInfoDTO**](APIInfoDTO.md) |  |  [optional]
**applicationInfo** | [**ApplicationInfoDTO**](ApplicationInfoDTO.md) |  |  [optional]
**throttlingPolicy** | **String** |  | 
**status** | [**StatusEnum**](#StatusEnum) |  |  [optional]


<a name="StatusEnum"></a>
## Enum: StatusEnum
Name | Value
---- | -----
BLOCKED | &quot;BLOCKED&quot;
PROD_ONLY_BLOCKED | &quot;PROD_ONLY_BLOCKED&quot;
UNBLOCKED | &quot;UNBLOCKED&quot;
ON_HOLD | &quot;ON_HOLD&quot;
REJECTED | &quot;REJECTED&quot;



