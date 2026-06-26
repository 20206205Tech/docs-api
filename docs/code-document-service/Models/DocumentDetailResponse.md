# DocumentDetailResponse
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **id** | **UUID** | Unique document ID | [default to null] |
| **filename** | **String** | Original filename | [default to null] |
| **status** | **String** | Current processing status | [default to null] |
| **has\_file** | **Boolean** | Trạng thái tồn tại của file gốc | [optional] [default to false] |
| **has\_content** | **Boolean** | Trạng thái tồn tại của file nội dung (.md) | [optional] [default to false] |
| **has\_summary** | **Boolean** | Trạng thái tồn tại của file tóm tắt (.txt) | [optional] [default to false] |
| **file\_url** | **String** | URL to access the file | [optional] [default to null] |
| **parsed\_content\_url** | **String** | URL to access the parsed markdown file | [optional] [default to null] |
| **summary\_url** | **String** | URL to access the summary text file | [optional] [default to null] |
| **created\_at** | **Date** | Creation timestamp | [default to null] |
| **updated\_at** | **Date** | Last update timestamp | [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

