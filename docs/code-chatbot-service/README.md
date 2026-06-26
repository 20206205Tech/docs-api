# Documentation for code-chatbot-service (production)

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://134.185.92.211/code-chatbot-service*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *ChatsApi* | [**getChatDetailEndpointChatsChatIdGet**](Apis/ChatsApi.md#getChatDetailEndpointChatsChatIdGet) | **GET** /chats/{chat_id} | Get Chat Detail Endpoint |
*ChatsApi* | [**getListChatsEndpointChatsGet**](Apis/ChatsApi.md#getListChatsEndpointChatsGet) | **GET** /chats | Get List Chats Endpoint |
| *DefaultApi* | [**rootGet**](Apis/DefaultApi.md#rootGet) | **GET** / | Root |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [ChatDetailResponse](./Models/ChatDetailResponse.md)
 - [ChatListResponse](./Models/ChatListResponse.md)
 - [ChatMessageDTO](./Models/ChatMessageDTO.md)
 - [ChatSummaryDTO](./Models/ChatSummaryDTO.md)
 - [HTTPValidationError](./Models/HTTPValidationError.md)
 - [Location_inner](./Models/Location_inner.md)
 - [ReasoningStepDTO](./Models/ReasoningStepDTO.md)
 - [SourceDTO](./Models/SourceDTO.md)
 - [ValidationError](./Models/ValidationError.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="HTTPBearer"></a>
### HTTPBearer

- **Type**: HTTP Bearer Token authentication

