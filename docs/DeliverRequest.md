# DeliverRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeliveryDate** | **int64** | delivery time, epoch milliseconds | 
**InvoiceNumber** | **string** |  | 
**TrackingCode** | **string** |  | 
**Products** | **[]string** |  | 

## Methods

### NewDeliverRequest

`func NewDeliverRequest(deliveryDate int64, invoiceNumber string, trackingCode string, products []string, ) *DeliverRequest`

NewDeliverRequest instantiates a new DeliverRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliverRequestWithDefaults

`func NewDeliverRequestWithDefaults() *DeliverRequest`

NewDeliverRequestWithDefaults instantiates a new DeliverRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliveryDate

`func (o *DeliverRequest) GetDeliveryDate() int64`

GetDeliveryDate returns the DeliveryDate field if non-nil, zero value otherwise.

### GetDeliveryDateOk

`func (o *DeliverRequest) GetDeliveryDateOk() (*int64, bool)`

GetDeliveryDateOk returns a tuple with the DeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryDate

`func (o *DeliverRequest) SetDeliveryDate(v int64)`

SetDeliveryDate sets DeliveryDate field to given value.


### GetInvoiceNumber

`func (o *DeliverRequest) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *DeliverRequest) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *DeliverRequest) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### GetTrackingCode

`func (o *DeliverRequest) GetTrackingCode() string`

GetTrackingCode returns the TrackingCode field if non-nil, zero value otherwise.

### GetTrackingCodeOk

`func (o *DeliverRequest) GetTrackingCodeOk() (*string, bool)`

GetTrackingCodeOk returns a tuple with the TrackingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingCode

`func (o *DeliverRequest) SetTrackingCode(v string)`

SetTrackingCode sets TrackingCode field to given value.


### GetProducts

`func (o *DeliverRequest) GetProducts() []string`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *DeliverRequest) GetProductsOk() (*[]string, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *DeliverRequest) SetProducts(v []string)`

SetProducts sets Products field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


