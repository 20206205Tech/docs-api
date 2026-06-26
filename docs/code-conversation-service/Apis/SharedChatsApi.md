# SharedChatsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**generateLinkShareControllerExecute**](SharedChatsApi.md#generateLinkShareControllerExecute) | **POST** /code-conversation-service/shared-chats |  |
| [**manageShareControllerExecute**](SharedChatsApi.md#manageShareControllerExecute) | **GET** /code-conversation-service/shared-chats |  |
| [**revokeShareControllerExecute**](SharedChatsApi.md#revokeShareControllerExecute) | **DELETE** /code-conversation-service/shared-chats/{shareId} |  |
| [**viewShareControllerExecute**](SharedChatsApi.md#viewShareControllerExecute) | **GET** /code-conversation-service/shared-chats/public/{shareId}/{token} |  |


<a name="generateLinkShareControllerExecute"></a>
# **generateLinkShareControllerExecute**
> generateLinkShareControllerExecute(GenerateLinkShareRequestDto)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **GenerateLinkShareRequestDto** | [**GenerateLinkShareRequestDto**](../Models/GenerateLinkShareRequestDto.md)|  | |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

<a name="manageShareControllerExecute"></a>
# **manageShareControllerExecute**
> manageShareControllerExecute(skip, limit)



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

<a name="revokeShareControllerExecute"></a>
# **revokeShareControllerExecute**
> revokeShareControllerExecute(shareId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **shareId** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="viewShareControllerExecute"></a>
# **viewShareControllerExecute**
> viewShareControllerExecute(shareId, token)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **shareId** | **String**|  | [default to null] |
| **token** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

