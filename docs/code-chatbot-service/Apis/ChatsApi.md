# ChatsApi

All URIs are relative to *http://134.185.92.211/code-chatbot-service*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**getChatDetailEndpointChatsChatIdGet**](ChatsApi.md#getChatDetailEndpointChatsChatIdGet) | **GET** /chats/{chat_id} | Get Chat Detail Endpoint |
| [**getListChatsEndpointChatsGet**](ChatsApi.md#getListChatsEndpointChatsGet) | **GET** /chats | Get List Chats Endpoint |


<a name="getChatDetailEndpointChatsChatIdGet"></a>
# **getChatDetailEndpointChatsChatIdGet**
> ChatDetailResponse getChatDetailEndpointChatsChatIdGet(chat\_id, before\_id, limit, request-id, request-kong-secret)

Get Chat Detail Endpoint

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **chat\_id** | **UUID**|  | [default to null] |
| **before\_id** | **UUID**|  | [optional] [default to null] |
| **limit** | **Integer**|  | [optional] [default to 20] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**ChatDetailResponse**](../Models/ChatDetailResponse.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getListChatsEndpointChatsGet"></a>
# **getListChatsEndpointChatsGet**
> ChatListResponse getListChatsEndpointChatsGet(skip, limit, request-id, request-kong-secret)

Get List Chats Endpoint

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **skip** | **Integer**|  | [optional] [default to 0] |
| **limit** | **Integer**|  | [optional] [default to 100] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**ChatListResponse**](../Models/ChatListResponse.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

