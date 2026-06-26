# BookmarksApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**addBookmarkControllerExecute**](BookmarksApi.md#addBookmarkControllerExecute) | **PUT** /code-conversation-service/bookmarks/{folderId}/item |  |
| [**createFolderBookmarkControllerExecute**](BookmarksApi.md#createFolderBookmarkControllerExecute) | **POST** /code-conversation-service/bookmarks |  |
| [**deleteFolderBookmarkControllerExecute**](BookmarksApi.md#deleteFolderBookmarkControllerExecute) | **DELETE** /code-conversation-service/bookmarks/{folderId} |  |
| [**getAllBookmarkControllerExecute**](BookmarksApi.md#getAllBookmarkControllerExecute) | **GET** /code-conversation-service/bookmarks |  |
| [**getDetailBookmarkControllerExecute**](BookmarksApi.md#getDetailBookmarkControllerExecute) | **GET** /code-conversation-service/bookmarks/{folderId} |  |
| [**removeBookmarkControllerExecute**](BookmarksApi.md#removeBookmarkControllerExecute) | **DELETE** /code-conversation-service/bookmarks/{folderId}/item/{chatId} |  |


<a name="addBookmarkControllerExecute"></a>
# **addBookmarkControllerExecute**
> addBookmarkControllerExecute(folderId, AddBookmarkRequestDto)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **folderId** | **String**|  | [default to null] |
| **AddBookmarkRequestDto** | [**AddBookmarkRequestDto**](../Models/AddBookmarkRequestDto.md)|  | |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

<a name="createFolderBookmarkControllerExecute"></a>
# **createFolderBookmarkControllerExecute**
> createFolderBookmarkControllerExecute(CreateFolderBookmarkRequestDto)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **CreateFolderBookmarkRequestDto** | [**CreateFolderBookmarkRequestDto**](../Models/CreateFolderBookmarkRequestDto.md)|  | |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

<a name="deleteFolderBookmarkControllerExecute"></a>
# **deleteFolderBookmarkControllerExecute**
> deleteFolderBookmarkControllerExecute(folderId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **folderId** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="getAllBookmarkControllerExecute"></a>
# **getAllBookmarkControllerExecute**
> getAllBookmarkControllerExecute(skip, limit)



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

<a name="getDetailBookmarkControllerExecute"></a>
# **getDetailBookmarkControllerExecute**
> getDetailBookmarkControllerExecute(folderId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **folderId** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="removeBookmarkControllerExecute"></a>
# **removeBookmarkControllerExecute**
> removeBookmarkControllerExecute(folderId, chatId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **folderId** | **String**|  | [default to null] |
| **chatId** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

