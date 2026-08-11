# BasketDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BasketId** | Pointer to **string** | required for CREDIT/BNPL purchases | [optional] 
**Items** | Pointer to [**[]BasketItem**](BasketItem.md) |  | [optional] 

## Methods

### NewBasketDetails

`func NewBasketDetails() *BasketDetails`

NewBasketDetails instantiates a new BasketDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBasketDetailsWithDefaults

`func NewBasketDetailsWithDefaults() *BasketDetails`

NewBasketDetailsWithDefaults instantiates a new BasketDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBasketId

`func (o *BasketDetails) GetBasketId() string`

GetBasketId returns the BasketId field if non-nil, zero value otherwise.

### GetBasketIdOk

`func (o *BasketDetails) GetBasketIdOk() (*string, bool)`

GetBasketIdOk returns a tuple with the BasketId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBasketId

`func (o *BasketDetails) SetBasketId(v string)`

SetBasketId sets BasketId field to given value.

### HasBasketId

`func (o *BasketDetails) HasBasketId() bool`

HasBasketId returns a boolean if a field has been set.

### GetItems

`func (o *BasketDetails) GetItems() []BasketItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *BasketDetails) GetItemsOk() (*[]BasketItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *BasketDetails) SetItems(v []BasketItem)`

SetItems sets Items field to given value.

### HasItems

`func (o *BasketDetails) HasItems() bool`

HasItems returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


