# VoiceAdminApi

All URIs are relative to *http://134.185.92.211/code-persona-service*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**createVoiceVoicesPost**](VoiceAdminApi.md#createVoiceVoicesPost) | **POST** /voices | Create Voice |
| [**deleteVoiceVoicesVoiceUuidDelete**](VoiceAdminApi.md#deleteVoiceVoicesVoiceUuidDelete) | **DELETE** /voices/{voice_uuid} | Delete Voice |
| [**getAllVoicesVoicesGet**](VoiceAdminApi.md#getAllVoicesVoicesGet) | **GET** /voices | Get All Voices |
| [**syncElevenlabsVoicesSyncElevenlabsPost**](VoiceAdminApi.md#syncElevenlabsVoicesSyncElevenlabsPost) | **POST** /voices/sync-elevenlabs | Sync Elevenlabs |
| [**updateVoiceVoicesVoiceUuidPut**](VoiceAdminApi.md#updateVoiceVoicesVoiceUuidPut) | **PUT** /voices/{voice_uuid} | Update Voice |


<a name="createVoiceVoicesPost"></a>
# **createVoiceVoicesPost**
> BaseResponse_VoiceResponse_ createVoiceVoicesPost(VoiceCreate, request-id, request-kong-secret)

Create Voice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **VoiceCreate** | [**VoiceCreate**](../Models/VoiceCreate.md)|  | |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_VoiceResponse_**](../Models/BaseResponse_VoiceResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deleteVoiceVoicesVoiceUuidDelete"></a>
# **deleteVoiceVoicesVoiceUuidDelete**
> oas_any_type_not_mapped deleteVoiceVoicesVoiceUuidDelete(voice\_uuid, request-id, request-kong-secret)

Delete Voice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **voice\_uuid** | **UUID**|  | [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**oas_any_type_not_mapped**](../Models/AnyType.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getAllVoicesVoicesGet"></a>
# **getAllVoicesVoicesGet**
> BaseResponse_PaginatedVoiceResponse_ getAllVoicesVoicesGet(page, size, engine\_code, request-id, request-kong-secret)

Get All Voices

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **page** | **Integer**|  | [optional] [default to 1] |
| **size** | **Integer**|  | [optional] [default to 10] |
| **engine\_code** | **String**| Lọc theo mã Engine | [optional] [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_PaginatedVoiceResponse_**](../Models/BaseResponse_PaginatedVoiceResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="syncElevenlabsVoicesSyncElevenlabsPost"></a>
# **syncElevenlabsVoicesSyncElevenlabsPost**
> oas_any_type_not_mapped syncElevenlabsVoicesSyncElevenlabsPost(request-id, request-kong-secret)

Sync Elevenlabs

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**oas_any_type_not_mapped**](../Models/AnyType.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="updateVoiceVoicesVoiceUuidPut"></a>
# **updateVoiceVoicesVoiceUuidPut**
> BaseResponse_VoiceResponse_ updateVoiceVoicesVoiceUuidPut(voice\_uuid, VoiceUpdate, request-id, request-kong-secret)

Update Voice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **voice\_uuid** | **UUID**|  | [default to null] |
| **VoiceUpdate** | [**VoiceUpdate**](../Models/VoiceUpdate.md)|  | |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_VoiceResponse_**](../Models/BaseResponse_VoiceResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

