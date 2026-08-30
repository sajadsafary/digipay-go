# RefundResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | [**Result**](Result.md) |  | 
**TrackingCode** | Pointer to **string** | tracking code of the refund itself, distinct from saleTrackingCode | [optional] 

## Methods

### NewRefundResponse

`func NewRefundResponse(result Result, ) *RefundResponse`

NewRefundResponse instantiates a new RefundResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRefundResponseWithDefaults

`func NewRefundResponseWithDefaults() *RefundResponse`

NewRefundResponseWithDefaults instantiates a new RefundResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *RefundResponse) GetResult() Result`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *RefundResponse) GetResultOk() (*Result, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *RefundResponse) SetResult(v Result)`

SetResult sets Result field to given value.


### GetTrackingCode

`func (o *RefundResponse) GetTrackingCode() string`

GetTrackingCode returns the TrackingCode field if non-nil, zero value otherwise.

### GetTrackingCodeOk

`func (o *RefundResponse) GetTrackingCodeOk() (*string, bool)`

GetTrackingCodeOk returns a tuple with the TrackingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingCode

`func (o *RefundResponse) SetTrackingCode(v string)`

SetTrackingCode sets TrackingCode field to given value.

### HasTrackingCode

`func (o *RefundResponse) HasTrackingCode() bool`

HasTrackingCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


