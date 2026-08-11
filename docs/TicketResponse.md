# TicketResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | [**Result**](Result.md) |  | 
**Ticket** | **string** | unique identifier for this purchase session | 
**RedirectUrl** | **string** | customer is redirected here to complete payment | 

## Methods

### NewTicketResponse

`func NewTicketResponse(result Result, ticket string, redirectUrl string, ) *TicketResponse`

NewTicketResponse instantiates a new TicketResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketResponseWithDefaults

`func NewTicketResponseWithDefaults() *TicketResponse`

NewTicketResponseWithDefaults instantiates a new TicketResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *TicketResponse) GetResult() Result`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *TicketResponse) GetResultOk() (*Result, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *TicketResponse) SetResult(v Result)`

SetResult sets Result field to given value.


### GetTicket

`func (o *TicketResponse) GetTicket() string`

GetTicket returns the Ticket field if non-nil, zero value otherwise.

### GetTicketOk

`func (o *TicketResponse) GetTicketOk() (*string, bool)`

GetTicketOk returns a tuple with the Ticket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTicket

`func (o *TicketResponse) SetTicket(v string)`

SetTicket sets Ticket field to given value.


### GetRedirectUrl

`func (o *TicketResponse) GetRedirectUrl() string`

GetRedirectUrl returns the RedirectUrl field if non-nil, zero value otherwise.

### GetRedirectUrlOk

`func (o *TicketResponse) GetRedirectUrlOk() (*string, bool)`

GetRedirectUrlOk returns a tuple with the RedirectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUrl

`func (o *TicketResponse) SetRedirectUrl(v string)`

SetRedirectUrl sets RedirectUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


