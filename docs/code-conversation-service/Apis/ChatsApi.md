# ChatsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**deleteChatControllerDeleteChat**](ChatsApi.md#deleteChatControllerDeleteChat) | **DELETE** /code-conversation-service/chats/{chatId} |  |
| [**getVoiceSessionTokenControllerGetVoiceSessionToken**](ChatsApi.md#getVoiceSessionTokenControllerGetVoiceSessionToken) | **GET** /code-conversation-service/chats/{chat_id}/voice-token | Lấy token kết nối phiên hội thoại |
| [**startChatControllerStartChat**](ChatsApi.md#startChatControllerStartChat) | **POST** /code-conversation-service/chats/start |  |
| [**streamChatControllerStreamChat**](ChatsApi.md#streamChatControllerStreamChat) | **POST** /code-conversation-service/chats/stream |  |


<a name="deleteChatControllerDeleteChat"></a>
# **deleteChatControllerDeleteChat**
> deleteChatControllerDeleteChat(chatId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **chatId** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="getVoiceSessionTokenControllerGetVoiceSessionToken"></a>
# **getVoiceSessionTokenControllerGetVoiceSessionToken**
> getVoiceSessionTokenControllerGetVoiceSessionToken(chat\_id, use\_reasoning, persona\_id)

Lấy token kết nối phiên hội thoại

    Cấp phát Access Token để client kết nối vào phòng hội thoại tương ứng với phiên chat hiện tại. Yêu cầu gói VIP.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **chat\_id** | **String**|  | [default to null] |
| **use\_reasoning** | **String**|  | [default to null] |
| **persona\_id** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="startChatControllerStartChat"></a>
# **startChatControllerStartChat**
> startChatControllerStartChat()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="streamChatControllerStreamChat"></a>
# **streamChatControllerStreamChat**
> streamChatControllerStreamChat(StreamChatRequestDto)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **StreamChatRequestDto** | [**StreamChatRequestDto**](../Models/StreamChatRequestDto.md)|  | |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

