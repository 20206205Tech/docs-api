# PublicApi

All URIs are relative to *http://134.185.92.211/code-persona-service*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**getAllPersonaPersonasGet**](PublicApi.md#getAllPersonaPersonasGet) | **GET** /personas | Get All Persona |


<a name="getAllPersonaPersonasGet"></a>
# **getAllPersonaPersonasGet**
> BaseResponse_PaginatedPersonaResponse_ getAllPersonaPersonasGet(page, size, persona\_id)

Get All Persona

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **page** | **Integer**|  | [optional] [default to 1] |
| **size** | **Integer**|  | [optional] [default to 10] |
| **persona\_id** | **UUID**| Lọc danh sách theo persona_id | [optional] [default to null] |

### Return type

[**BaseResponse_PaginatedPersonaResponse_**](../Models/BaseResponse_PaginatedPersonaResponse_.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

