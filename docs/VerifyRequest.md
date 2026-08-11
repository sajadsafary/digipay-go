# VerifyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TrackingCode** | **string** | purchase tracking code | 
**ProviderId** | **string** | same providerId sent during ticket creation | 

## Methods

### NewVerifyRequest

`func NewVerifyRequest(trackingCode string, providerId string, ) *VerifyRequest`

NewVerifyRequest instantiates a new VerifyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyRequestWithDefaults

`func NewVerifyRequestWithDefaults() *VerifyRequest`

NewVerifyRequestWithDefaults instantiates a new VerifyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTrackingCode

`func (o *VerifyRequest) GetTrackingCode() string`

GetTrackingCode returns the TrackingCode field if non-nil, zero value otherwise.

### GetTrackingCodeOk

`func (o *VerifyRequest) GetTrackingCodeOk() (*string, bool)`

GetTrackingCodeOk returns a tuple with the TrackingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingCode

`func (o *VerifyRequest) SetTrackingCode(v string)`

SetTrackingCode sets TrackingCode field to given value.


### GetProviderId

`func (o *VerifyRequest) GetProviderId() string`

GetProviderId returns the ProviderId field if non-nil, zero value otherwise.

### GetProviderIdOk

`func (o *VerifyRequest) GetProviderIdOk() (*string, bool)`

GetProviderIdOk returns a tuple with the ProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderId

`func (o *VerifyRequest) SetProviderId(v string)`

SetProviderId sets ProviderId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


