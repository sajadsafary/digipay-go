# AdditionalInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PreferredGateway** | Pointer to **int32** | skips the payment method selection screen when set | [optional] 

## Methods

### NewAdditionalInfo

`func NewAdditionalInfo() *AdditionalInfo`

NewAdditionalInfo instantiates a new AdditionalInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdditionalInfoWithDefaults

`func NewAdditionalInfoWithDefaults() *AdditionalInfo`

NewAdditionalInfoWithDefaults instantiates a new AdditionalInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPreferredGateway

`func (o *AdditionalInfo) GetPreferredGateway() int32`

GetPreferredGateway returns the PreferredGateway field if non-nil, zero value otherwise.

### GetPreferredGatewayOk

`func (o *AdditionalInfo) GetPreferredGatewayOk() (*int32, bool)`

GetPreferredGatewayOk returns a tuple with the PreferredGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreferredGateway

`func (o *AdditionalInfo) SetPreferredGateway(v int32)`

SetPreferredGateway sets PreferredGateway field to given value.

### HasPreferredGateway

`func (o *AdditionalInfo) HasPreferredGateway() bool`

HasPreferredGateway returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


