# RefundRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProviderId** | **string** | unique merchant-generated id for this refund, which must differ from the providerId of the purchase being returned | 
**Amount** | **int64** | amount to return to the customer in Rials, up to the original purchase amount | 
**SaleTrackingCode** | **string** | trackingCode of the original purchase being returned | 

## Methods

### NewRefundRequest

`func NewRefundRequest(providerId string, amount int64, saleTrackingCode string, ) *RefundRequest`

NewRefundRequest instantiates a new RefundRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRefundRequestWithDefaults

`func NewRefundRequestWithDefaults() *RefundRequest`

NewRefundRequestWithDefaults instantiates a new RefundRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProviderId

`func (o *RefundRequest) GetProviderId() string`

GetProviderId returns the ProviderId field if non-nil, zero value otherwise.

### GetProviderIdOk

`func (o *RefundRequest) GetProviderIdOk() (*string, bool)`

GetProviderIdOk returns a tuple with the ProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderId

`func (o *RefundRequest) SetProviderId(v string)`

SetProviderId sets ProviderId field to given value.


### GetAmount

`func (o *RefundRequest) GetAmount() int64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *RefundRequest) GetAmountOk() (*int64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *RefundRequest) SetAmount(v int64)`

SetAmount sets Amount field to given value.


### GetSaleTrackingCode

`func (o *RefundRequest) GetSaleTrackingCode() string`

GetSaleTrackingCode returns the SaleTrackingCode field if non-nil, zero value otherwise.

### GetSaleTrackingCodeOk

`func (o *RefundRequest) GetSaleTrackingCodeOk() (*string, bool)`

GetSaleTrackingCodeOk returns a tuple with the SaleTrackingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSaleTrackingCode

`func (o *RefundRequest) SetSaleTrackingCode(v string)`

SetSaleTrackingCode sets SaleTrackingCode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


