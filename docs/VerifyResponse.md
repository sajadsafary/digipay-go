# VerifyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | [**Result**](Result.md) |  | 
**TrackingCode** | **string** |  | 
**ProviderId** | Pointer to **string** |  | [optional] 
**Amount** | Pointer to **interface{}** |  | [optional] 
**AdditionalInfo** | Pointer to [**VerifyAdditionalInfo**](VerifyAdditionalInfo.md) |  | [optional] 

## Methods

### NewVerifyResponse

`func NewVerifyResponse(result Result, trackingCode string, ) *VerifyResponse`

NewVerifyResponse instantiates a new VerifyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyResponseWithDefaults

`func NewVerifyResponseWithDefaults() *VerifyResponse`

NewVerifyResponseWithDefaults instantiates a new VerifyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *VerifyResponse) GetResult() Result`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *VerifyResponse) GetResultOk() (*Result, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *VerifyResponse) SetResult(v Result)`

SetResult sets Result field to given value.


### GetTrackingCode

`func (o *VerifyResponse) GetTrackingCode() string`

GetTrackingCode returns the TrackingCode field if non-nil, zero value otherwise.

### GetTrackingCodeOk

`func (o *VerifyResponse) GetTrackingCodeOk() (*string, bool)`

GetTrackingCodeOk returns a tuple with the TrackingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingCode

`func (o *VerifyResponse) SetTrackingCode(v string)`

SetTrackingCode sets TrackingCode field to given value.


### GetProviderId

`func (o *VerifyResponse) GetProviderId() string`

GetProviderId returns the ProviderId field if non-nil, zero value otherwise.

### GetProviderIdOk

`func (o *VerifyResponse) GetProviderIdOk() (*string, bool)`

GetProviderIdOk returns a tuple with the ProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderId

`func (o *VerifyResponse) SetProviderId(v string)`

SetProviderId sets ProviderId field to given value.

### HasProviderId

`func (o *VerifyResponse) HasProviderId() bool`

HasProviderId returns a boolean if a field has been set.

### GetAmount

`func (o *VerifyResponse) GetAmount() interface{}`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *VerifyResponse) GetAmountOk() (*interface{}, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *VerifyResponse) SetAmount(v interface{})`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *VerifyResponse) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### SetAmountNil

`func (o *VerifyResponse) SetAmountNil(b bool)`

 SetAmountNil sets the value for Amount to be an explicit nil

### UnsetAmount
`func (o *VerifyResponse) UnsetAmount()`

UnsetAmount ensures that no value is present for Amount, not even an explicit nil
### GetAdditionalInfo

`func (o *VerifyResponse) GetAdditionalInfo() VerifyAdditionalInfo`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *VerifyResponse) GetAdditionalInfoOk() (*VerifyAdditionalInfo, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *VerifyResponse) SetAdditionalInfo(v VerifyAdditionalInfo)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *VerifyResponse) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


