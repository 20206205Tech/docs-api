# SubscriptionsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**getMySubscriptionControllerExecute**](SubscriptionsApi.md#getMySubscriptionControllerExecute) | **GET** /code-payment-service/subscriptions |  |
| [**getTransactionHistoryControllerExecute**](SubscriptionsApi.md#getTransactionHistoryControllerExecute) | **GET** /code-payment-service/subscriptions/history |  |
| [**manualActivateTransactionControllerExecute**](SubscriptionsApi.md#manualActivateTransactionControllerExecute) | **POST** /code-payment-service/subscriptions/manual-activate/{transaction_id} |  |
| [**purchaseSubscriptionControllerExecute**](SubscriptionsApi.md#purchaseSubscriptionControllerExecute) | **POST** /code-payment-service/subscriptions/purchase |  |


<a name="getMySubscriptionControllerExecute"></a>
# **getMySubscriptionControllerExecute**
> getMySubscriptionControllerExecute()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="getTransactionHistoryControllerExecute"></a>
# **getTransactionHistoryControllerExecute**
> getTransactionHistoryControllerExecute(skip, limit)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **skip** | **BigDecimal**|  | [default to null] |
| **limit** | **BigDecimal**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="manualActivateTransactionControllerExecute"></a>
# **manualActivateTransactionControllerExecute**
> manualActivateTransactionControllerExecute(transaction\_id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **transaction\_id** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="purchaseSubscriptionControllerExecute"></a>
# **purchaseSubscriptionControllerExecute**
> purchaseSubscriptionControllerExecute(PurchaseSubscriptionRequestDto)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **PurchaseSubscriptionRequestDto** | [**PurchaseSubscriptionRequestDto**](../Models/PurchaseSubscriptionRequestDto.md)|  | |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

