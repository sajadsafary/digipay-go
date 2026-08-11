# TokenResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessToken** | **string** |  | 
**TokenType** | **string** |  | 
**RefreshToken** | Pointer to **string** |  | [optional] 
**ExpiresIn** | **int64** |  | 
**Scope** | Pointer to **string** |  | [optional] 
**Jti** | Pointer to **string** |  | [optional] 

## Methods

### NewTokenResponse

`func NewTokenResponse(accessToken string, tokenType string, expiresIn int64, ) *TokenResponse`

NewTokenResponse instantiates a new TokenResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTokenResponseWithDefaults

`func NewTokenResponseWithDefaults() *TokenResponse`

NewTokenResponseWithDefaults instantiates a new TokenResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessToken

`func (o *TokenResponse) GetAccessToken() string`

GetAccessToken returns the AccessToken field if non-nil, zero value otherwise.

### GetAccessTokenOk

`func (o *TokenResponse) GetAccessTokenOk() (*string, bool)`

GetAccessTokenOk returns a tuple with the AccessToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessToken

`func (o *TokenResponse) SetAccessToken(v string)`

SetAccessToken sets AccessToken field to given value.


### GetTokenType

`func (o *TokenResponse) GetTokenType() string`

GetTokenType returns the TokenType field if non-nil, zero value otherwise.

### GetTokenTypeOk

`func (o *TokenResponse) GetTokenTypeOk() (*string, bool)`

GetTokenTypeOk returns a tuple with the TokenType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenType

`func (o *TokenResponse) SetTokenType(v string)`

SetTokenType sets TokenType field to given value.


### GetRefreshToken

`func (o *TokenResponse) GetRefreshToken() string`

GetRefreshToken returns the RefreshToken field if non-nil, zero value otherwise.

### GetRefreshTokenOk

`func (o *TokenResponse) GetRefreshTokenOk() (*string, bool)`

GetRefreshTokenOk returns a tuple with the RefreshToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshToken

`func (o *TokenResponse) SetRefreshToken(v string)`

SetRefreshToken sets RefreshToken field to given value.

### HasRefreshToken

`func (o *TokenResponse) HasRefreshToken() bool`

HasRefreshToken returns a boolean if a field has been set.

### GetExpiresIn

`func (o *TokenResponse) GetExpiresIn() int64`

GetExpiresIn returns the ExpiresIn field if non-nil, zero value otherwise.

### GetExpiresInOk

`func (o *TokenResponse) GetExpiresInOk() (*int64, bool)`

GetExpiresInOk returns a tuple with the ExpiresIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresIn

`func (o *TokenResponse) SetExpiresIn(v int64)`

SetExpiresIn sets ExpiresIn field to given value.


### GetScope

`func (o *TokenResponse) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *TokenResponse) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *TokenResponse) SetScope(v string)`

SetScope sets Scope field to given value.

### HasScope

`func (o *TokenResponse) HasScope() bool`

HasScope returns a boolean if a field has been set.

### GetJti

`func (o *TokenResponse) GetJti() string`

GetJti returns the Jti field if non-nil, zero value otherwise.

### GetJtiOk

`func (o *TokenResponse) GetJtiOk() (*string, bool)`

GetJtiOk returns a tuple with the Jti field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJti

`func (o *TokenResponse) SetJti(v string)`

SetJti sets Jti field to given value.

### HasJti

`func (o *TokenResponse) HasJti() bool`

HasJti returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


