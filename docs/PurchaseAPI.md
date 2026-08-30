# \PurchaseAPI

All URIs are relative to *https://api.mydigipay.com/digipay/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PurchasesDeliverPost**](PurchaseAPI.md#PurchasesDeliverPost) | **Post** /purchases/deliver | Deliver Purchase
[**PurchasesVerifyPost**](PurchaseAPI.md#PurchasesVerifyPost) | **Post** /purchases/verify | Verify Purchase
[**RefundsPost**](PurchaseAPI.md#RefundsPost) | **Post** /refunds | Refund Purchase
[**TicketsBusinessPost**](PurchaseAPI.md#TicketsBusinessPost) | **Post** /tickets/business | Create Purchase Ticket



## PurchasesDeliverPost

> DeliverResponse PurchasesDeliverPost(ctx).Type_(type_).Agent(agent).DigipayVersion(digipayVersion).DeliverRequest(deliverRequest).Execute()

Deliver Purchase



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
	type_ := int32(56) // int32 | 
	agent := "WEB" // string | 
	digipayVersion := "2022-02-02" // string | 
	deliverRequest := *openapiclient.NewDeliverRequest(int64(123), "InvoiceNumber_example", "TrackingCode_example", []string{"Products_example"}) // DeliverRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPI.PurchasesDeliverPost(context.Background()).Type_(type_).Agent(agent).DigipayVersion(digipayVersion).DeliverRequest(deliverRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPI.PurchasesDeliverPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchasesDeliverPost`: DeliverResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPI.PurchasesDeliverPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchasesDeliverPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | **int32** |  | 
 **agent** | **string** |  | 
 **digipayVersion** | **string** |  | 
 **deliverRequest** | [**DeliverRequest**](DeliverRequest.md) |  | 

### Return type

[**DeliverResponse**](DeliverResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PurchasesVerifyPost

> VerifyResponse PurchasesVerifyPost(ctx).Type_(type_).Agent(agent).DigipayVersion(digipayVersion).VerifyRequest(verifyRequest).Execute()

Verify Purchase



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
	type_ := int32(56) // int32 | 
	agent := "WEB" // string | 
	digipayVersion := "2022-02-02" // string | 
	verifyRequest := *openapiclient.NewVerifyRequest("TrackingCode_example", "ProviderId_example") // VerifyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPI.PurchasesVerifyPost(context.Background()).Type_(type_).Agent(agent).DigipayVersion(digipayVersion).VerifyRequest(verifyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPI.PurchasesVerifyPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PurchasesVerifyPost`: VerifyResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPI.PurchasesVerifyPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPurchasesVerifyPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | **int32** |  | 
 **agent** | **string** |  | 
 **digipayVersion** | **string** |  | 
 **verifyRequest** | [**VerifyRequest**](VerifyRequest.md) |  | 

### Return type

[**VerifyResponse**](VerifyResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefundsPost

> RefundResponse RefundsPost(ctx).Type_(type_).RefundRequest(refundRequest).Execute()

Refund Purchase



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
	type_ := int32(56) // int32 | 
	refundRequest := *openapiclient.NewRefundRequest("ProviderId_example", int64(123), "SaleTrackingCode_example") // RefundRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPI.RefundsPost(context.Background()).Type_(type_).RefundRequest(refundRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPI.RefundsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefundsPost`: RefundResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPI.RefundsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRefundsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | **int32** |  | 
 **refundRequest** | [**RefundRequest**](RefundRequest.md) |  | 

### Return type

[**RefundResponse**](RefundResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TicketsBusinessPost

> TicketResponse TicketsBusinessPost(ctx).Type_(type_).Agent(agent).DigipayVersion(digipayVersion).TicketRequest(ticketRequest).Execute()

Create Purchase Ticket



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
	type_ := int32(56) // int32 | 
	agent := "WEB" // string | 
	digipayVersion := "2022-02-02" // string | 
	ticketRequest := *openapiclient.NewTicketRequest("CellNumber_example", int64(123), "ProviderId_example", "CallbackUrl_example") // TicketRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseAPI.TicketsBusinessPost(context.Background()).Type_(type_).Agent(agent).DigipayVersion(digipayVersion).TicketRequest(ticketRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseAPI.TicketsBusinessPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TicketsBusinessPost`: TicketResponse
	fmt.Fprintf(os.Stdout, "Response from `PurchaseAPI.TicketsBusinessPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTicketsBusinessPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | **int32** |  | 
 **agent** | **string** |  | 
 **digipayVersion** | **string** |  | 
 **ticketRequest** | [**TicketRequest**](TicketRequest.md) |  | 

### Return type

[**TicketResponse**](TicketResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

