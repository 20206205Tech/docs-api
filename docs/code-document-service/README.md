# Documentation for code-document-service (production)

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://134.185.92.211/code-document-service*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *DefaultApi* | [**rootGet**](Apis/DefaultApi.md#rootGet) | **GET** / | Root |
| *DocumentsApi* | [**getDocumentStatusDocumentsDocIdGet**](Apis/DocumentsApi.md#getDocumentStatusDocumentsDocIdGet) | **GET** /documents/{doc_id} | Get Document Status |
*DocumentsApi* | [**listUserDocumentsDocumentsGet**](Apis/DocumentsApi.md#listUserDocumentsDocumentsGet) | **GET** /documents/ | List User Documents |
*DocumentsApi* | [**retryDocumentProcessingDocumentsDocIdRetryPost**](Apis/DocumentsApi.md#retryDocumentProcessingDocumentsDocIdRetryPost) | **POST** /documents/{doc_id}/retry | Retry Document Processing |
*DocumentsApi* | [**uploadDocumentDocumentsUploadPost**](Apis/DocumentsApi.md#uploadDocumentDocumentsUploadPost) | **POST** /documents/upload | Upload Document |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [BaseResponse](./Models/BaseResponse.md)
 - [BaseResponse_DocumentDetailResponse_](./Models/BaseResponse_DocumentDetailResponse_.md)
 - [BaseResponse_DocumentUploadResponse_](./Models/BaseResponse_DocumentUploadResponse_.md)
 - [DocumentDetailResponse](./Models/DocumentDetailResponse.md)
 - [DocumentUploadResponse](./Models/DocumentUploadResponse.md)
 - [HTTPValidationError](./Models/HTTPValidationError.md)
 - [Location_inner](./Models/Location_inner.md)
 - [ValidationError](./Models/ValidationError.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="HTTPBearer"></a>
### HTTPBearer

- **Type**: HTTP Bearer Token authentication

