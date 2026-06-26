# PlansApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**archivePlanControllerExecute**](PlansApi.md#archivePlanControllerExecute) | **DELETE** /code-payment-service/plans/{plan_id} |  |
| [**createPlanControllerExecute**](PlansApi.md#createPlanControllerExecute) | **POST** /code-payment-service/plans |  |
| [**getAllPlanControllerExecute**](PlansApi.md#getAllPlanControllerExecute) | **GET** /code-payment-service/plans |  |


<a name="archivePlanControllerExecute"></a>
# **archivePlanControllerExecute**
> archivePlanControllerExecute(plan\_id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **plan\_id** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="createPlanControllerExecute"></a>
# **createPlanControllerExecute**
> createPlanControllerExecute(CreatePlanRequestDto)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **CreatePlanRequestDto** | [**CreatePlanRequestDto**](../Models/CreatePlanRequestDto.md)|  | |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

<a name="getAllPlanControllerExecute"></a>
# **getAllPlanControllerExecute**
> getAllPlanControllerExecute(skip, limit)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **skip** | **BigDecimal**|  | [default to null] |
| **limit** | **BigDecimal**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

