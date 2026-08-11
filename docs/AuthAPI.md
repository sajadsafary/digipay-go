# \AuthAPI

All URIs are relative to *https://api.mydigipay.com/digipay/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OauthTokenPost**](AuthAPI.md#OauthTokenPost) | **Post** /oauth/token | Obtain Access Token



## OauthTokenPost

> TokenResponse OauthTokenPost(ctx).Username(username).Password(password).GrantType(grantType).Execute()

Obtain Access Token



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sajadsafary/digipay-go"
)

func main() {
	username := "username_example" // string | 
	password := "password_example" // string | 
	grantType := "grantType_example" // string |  (default to "password")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.OauthTokenPost(context.Background()).Username(username).Password(password).GrantType(grantType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.OauthTokenPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OauthTokenPost`: TokenResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.OauthTokenPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOauthTokenPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **string** |  | 
 **password** | **string** |  | 
 **grantType** | **string** |  | [default to &quot;password&quot;]

### Return type

[**TokenResponse**](TokenResponse.md)

### Authorization

[basicAuth](../README.md#basicAuth)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

