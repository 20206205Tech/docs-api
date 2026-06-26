# DocumentsApi

All URIs are relative to *http://134.185.92.211/code-document-service*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**getDocumentStatusDocumentsDocIdGet**](DocumentsApi.md#getDocumentStatusDocumentsDocIdGet) | **GET** /documents/{doc_id} | Get Document Status |
| [**listUserDocumentsDocumentsGet**](DocumentsApi.md#listUserDocumentsDocumentsGet) | **GET** /documents/ | List User Documents |
| [**retryDocumentProcessingDocumentsDocIdRetryPost**](DocumentsApi.md#retryDocumentProcessingDocumentsDocIdRetryPost) | **POST** /documents/{doc_id}/retry | Retry Document Processing |
| [**uploadDocumentDocumentsUploadPost**](DocumentsApi.md#uploadDocumentDocumentsUploadPost) | **POST** /documents/upload | Upload Document |


<a name="getDocumentStatusDocumentsDocIdGet"></a>
# **getDocumentStatusDocumentsDocIdGet**
> BaseResponse_DocumentDetailResponse_ getDocumentStatusDocumentsDocIdGet(doc\_id, request-id, request-kong-secret)

Get Document Status

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **doc\_id** | **String**|  | [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_DocumentDetailResponse_**](../Models/BaseResponse_DocumentDetailResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="listUserDocumentsDocumentsGet"></a>
# **listUserDocumentsDocumentsGet**
> BaseResponse listUserDocumentsDocumentsGet(skip, limit, request-id, request-kong-secret)

List User Documents

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **skip** | **Integer**|  | [optional] [default to 0] |
| **limit** | **Integer**|  | [optional] [default to 20] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse**](../Models/BaseResponse.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="retryDocumentProcessingDocumentsDocIdRetryPost"></a>
# **retryDocumentProcessingDocumentsDocIdRetryPost**
> oas_any_type_not_mapped retryDocumentProcessingDocumentsDocIdRetryPost(doc\_id, request-id, request-kong-secret)

Retry Document Processing

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **doc\_id** | **String**|  | [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**oas_any_type_not_mapped**](../Models/AnyType.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="uploadDocumentDocumentsUploadPost"></a>
# **uploadDocumentDocumentsUploadPost**
> BaseResponse_DocumentUploadResponse_ uploadDocumentDocumentsUploadPost(file, request-id, request-kong-secret)

Upload Document

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **file** | **File**| Document file to upload | [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_DocumentUploadResponse_**](../Models/BaseResponse_DocumentUploadResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

