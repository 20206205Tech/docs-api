# EngineAdminApi

All URIs are relative to *http://134.185.92.211/code-persona-service*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**createEngineEnginesPost**](EngineAdminApi.md#createEngineEnginesPost) | **POST** /engines | Create Engine |
| [**deleteEngineEnginesEngineIdDelete**](EngineAdminApi.md#deleteEngineEnginesEngineIdDelete) | **DELETE** /engines/{engine_id} | Delete Engine |
| [**getAllEnginesEnginesGet**](EngineAdminApi.md#getAllEnginesEnginesGet) | **GET** /engines | Get All Engines |
| [**updateEngineEnginesEngineIdPut**](EngineAdminApi.md#updateEngineEnginesEngineIdPut) | **PUT** /engines/{engine_id} | Update Engine |


<a name="createEngineEnginesPost"></a>
# **createEngineEnginesPost**
> BaseResponse_EngineResponse_ createEngineEnginesPost(EngineCreate, request-id, request-kong-secret)

Create Engine

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **EngineCreate** | [**EngineCreate**](../Models/EngineCreate.md)|  | |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_EngineResponse_**](../Models/BaseResponse_EngineResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deleteEngineEnginesEngineIdDelete"></a>
# **deleteEngineEnginesEngineIdDelete**
> oas_any_type_not_mapped deleteEngineEnginesEngineIdDelete(engine\_id, request-id, request-kong-secret)

Delete Engine

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **engine\_id** | **UUID**|  | [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**oas_any_type_not_mapped**](../Models/AnyType.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getAllEnginesEnginesGet"></a>
# **getAllEnginesEnginesGet**
> BaseResponse_PaginatedEngineResponse_ getAllEnginesEnginesGet(page, size, request-id, request-kong-secret)

Get All Engines

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **page** | **Integer**|  | [optional] [default to 1] |
| **size** | **Integer**|  | [optional] [default to 10] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_PaginatedEngineResponse_**](../Models/BaseResponse_PaginatedEngineResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="updateEngineEnginesEngineIdPut"></a>
# **updateEngineEnginesEngineIdPut**
> BaseResponse_EngineResponse_ updateEngineEnginesEngineIdPut(engine\_id, EngineUpdate, request-id, request-kong-secret)

Update Engine

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **engine\_id** | **UUID**|  | [default to null] |
| **EngineUpdate** | [**EngineUpdate**](../Models/EngineUpdate.md)|  | |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_EngineResponse_**](../Models/BaseResponse_EngineResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

