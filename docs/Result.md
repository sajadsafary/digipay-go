# Result

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** |  | [optional] 
**Status** | **int32** | not exhaustive, other codes may be returned by DigiPay | 
**Message** | **string** |  | 
**Level** | Pointer to **string** |  | [optional] 

## Methods

### NewResult

`func NewResult(status int32, message string, ) *Result`

NewResult instantiates a new Result object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultWithDefaults

`func NewResultWithDefaults() *Result`

NewResultWithDefaults instantiates a new Result object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *Result) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Result) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Result) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Result) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetStatus

`func (o *Result) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Result) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Result) SetStatus(v int32)`

SetStatus sets Status field to given value.


### GetMessage

`func (o *Result) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *Result) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *Result) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetLevel

`func (o *Result) GetLevel() string`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *Result) GetLevelOk() (*string, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *Result) SetLevel(v string)`

SetLevel sets Level field to given value.

### HasLevel

`func (o *Result) HasLevel() bool`

HasLevel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


