# TicketRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CellNumber** | **string** | customer mobile number | 
**Amount** | **int64** | purchase amount in Rials | 
**ProviderId** | **string** | unique merchant-generated id for this purchase | 
**CallbackUrl** | **string** |  | 
**BasketDetailsDto** | Pointer to [**BasketDetails**](BasketDetails.md) |  | [optional] 
**AdditionalInfo** | Pointer to [**AdditionalInfo**](AdditionalInfo.md) |  | [optional] 

## Methods

### NewTicketRequest

`func NewTicketRequest(cellNumber string, amount int64, providerId string, callbackUrl string, ) *TicketRequest`

NewTicketRequest instantiates a new TicketRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketRequestWithDefaults

`func NewTicketRequestWithDefaults() *TicketRequest`

NewTicketRequestWithDefaults instantiates a new TicketRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCellNumber

`func (o *TicketRequest) GetCellNumber() string`

GetCellNumber returns the CellNumber field if non-nil, zero value otherwise.

### GetCellNumberOk

`func (o *TicketRequest) GetCellNumberOk() (*string, bool)`

GetCellNumberOk returns a tuple with the CellNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCellNumber

`func (o *TicketRequest) SetCellNumber(v string)`

SetCellNumber sets CellNumber field to given value.


### GetAmount

`func (o *TicketRequest) GetAmount() int64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *TicketRequest) GetAmountOk() (*int64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *TicketRequest) SetAmount(v int64)`

SetAmount sets Amount field to given value.


### GetProviderId

`func (o *TicketRequest) GetProviderId() string`

GetProviderId returns the ProviderId field if non-nil, zero value otherwise.

### GetProviderIdOk

`func (o *TicketRequest) GetProviderIdOk() (*string, bool)`

GetProviderIdOk returns a tuple with the ProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderId

`func (o *TicketRequest) SetProviderId(v string)`

SetProviderId sets ProviderId field to given value.


### GetCallbackUrl

`func (o *TicketRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *TicketRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *TicketRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.


### GetBasketDetailsDto

`func (o *TicketRequest) GetBasketDetailsDto() BasketDetails`

GetBasketDetailsDto returns the BasketDetailsDto field if non-nil, zero value otherwise.

### GetBasketDetailsDtoOk

`func (o *TicketRequest) GetBasketDetailsDtoOk() (*BasketDetails, bool)`

GetBasketDetailsDtoOk returns a tuple with the BasketDetailsDto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBasketDetailsDto

`func (o *TicketRequest) SetBasketDetailsDto(v BasketDetails)`

SetBasketDetailsDto sets BasketDetailsDto field to given value.

### HasBasketDetailsDto

`func (o *TicketRequest) HasBasketDetailsDto() bool`

HasBasketDetailsDto returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *TicketRequest) GetAdditionalInfo() AdditionalInfo`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *TicketRequest) GetAdditionalInfoOk() (*AdditionalInfo, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *TicketRequest) SetAdditionalInfo(v AdditionalInfo)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *TicketRequest) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


