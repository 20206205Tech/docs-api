# Documentation for code-conversation-service (production)

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://localhost*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *AppApi* | [**appControllerGetRoot**](Apis/AppApi.md#appControllerGetRoot) | **GET** /code-conversation-service |  |
| *BookmarksApi* | [**addBookmarkControllerExecute**](Apis/BookmarksApi.md#addBookmarkControllerExecute) | **PUT** /code-conversation-service/bookmarks/{folderId}/item |  |
*BookmarksApi* | [**createFolderBookmarkControllerExecute**](Apis/BookmarksApi.md#createFolderBookmarkControllerExecute) | **POST** /code-conversation-service/bookmarks |  |
*BookmarksApi* | [**deleteFolderBookmarkControllerExecute**](Apis/BookmarksApi.md#deleteFolderBookmarkControllerExecute) | **DELETE** /code-conversation-service/bookmarks/{folderId} |  |
*BookmarksApi* | [**getAllBookmarkControllerExecute**](Apis/BookmarksApi.md#getAllBookmarkControllerExecute) | **GET** /code-conversation-service/bookmarks |  |
*BookmarksApi* | [**getDetailBookmarkControllerExecute**](Apis/BookmarksApi.md#getDetailBookmarkControllerExecute) | **GET** /code-conversation-service/bookmarks/{folderId} |  |
*BookmarksApi* | [**removeBookmarkControllerExecute**](Apis/BookmarksApi.md#removeBookmarkControllerExecute) | **DELETE** /code-conversation-service/bookmarks/{folderId}/item/{chatId} |  |
| *ChatsApi* | [**deleteChatControllerDeleteChat**](Apis/ChatsApi.md#deleteChatControllerDeleteChat) | **DELETE** /code-conversation-service/chats/{chatId} |  |
*ChatsApi* | [**getVoiceSessionTokenControllerGetVoiceSessionToken**](Apis/ChatsApi.md#getVoiceSessionTokenControllerGetVoiceSessionToken) | **GET** /code-conversation-service/chats/{chat_id}/voice-token | Lấy token kết nối phiên hội thoại |
*ChatsApi* | [**startChatControllerStartChat**](Apis/ChatsApi.md#startChatControllerStartChat) | **POST** /code-conversation-service/chats/start |  |
*ChatsApi* | [**streamChatControllerStreamChat**](Apis/ChatsApi.md#streamChatControllerStreamChat) | **POST** /code-conversation-service/chats/stream |  |
| *SharedChatsApi* | [**generateLinkShareControllerExecute**](Apis/SharedChatsApi.md#generateLinkShareControllerExecute) | **POST** /code-conversation-service/shared-chats |  |
*SharedChatsApi* | [**manageShareControllerExecute**](Apis/SharedChatsApi.md#manageShareControllerExecute) | **GET** /code-conversation-service/shared-chats |  |
*SharedChatsApi* | [**revokeShareControllerExecute**](Apis/SharedChatsApi.md#revokeShareControllerExecute) | **DELETE** /code-conversation-service/shared-chats/{shareId} |  |
*SharedChatsApi* | [**viewShareControllerExecute**](Apis/SharedChatsApi.md#viewShareControllerExecute) | **GET** /code-conversation-service/shared-chats/public/{shareId}/{token} |  |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [AddBookmarkRequestDto](./Models/AddBookmarkRequestDto.md)
 - [CreateFolderBookmarkRequestDto](./Models/CreateFolderBookmarkRequestDto.md)
 - [GenerateLinkShareRequestDto](./Models/GenerateLinkShareRequestDto.md)
 - [StreamChatRequestDto](./Models/StreamChatRequestDto.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="HTTPBearer"></a>
### HTTPBearer

- **Type**: HTTP Bearer Token authentication (JWT)

