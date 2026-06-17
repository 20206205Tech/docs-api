# PersonaAdminApi

All URIs are relative to *http://134.185.92.211/code-persona-service*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**createPersonaPersonasPost**](PersonaAdminApi.md#createPersonaPersonasPost) | **POST** /personas | Create Persona |
| [**deletePersonaPersonasPersonaIdDelete**](PersonaAdminApi.md#deletePersonaPersonasPersonaIdDelete) | **DELETE** /personas/{persona_id} | Delete Persona |
| [**updatePersonaPersonasPersonaIdPut**](PersonaAdminApi.md#updatePersonaPersonasPersonaIdPut) | **PUT** /personas/{persona_id} | Update Persona |
| [**uploadPersonaAudioPersonasUploadAudioPost**](PersonaAdminApi.md#uploadPersonaAudioPersonasUploadAudioPost) | **POST** /personas/upload-audio | Upload Persona Audio |
| [**uploadPersonaAvatarPersonasUploadAvatarPost**](PersonaAdminApi.md#uploadPersonaAvatarPersonasUploadAvatarPost) | **POST** /personas/upload-avatar | Upload Persona Avatar |


<a name="createPersonaPersonasPost"></a>
# **createPersonaPersonasPost**
> BaseResponse_PersonaResponse_ createPersonaPersonasPost(PersonaCreate, request-id, request-kong-secret)

Create Persona

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **PersonaCreate** | [**PersonaCreate**](../Models/PersonaCreate.md)|  | |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_PersonaResponse_**](../Models/BaseResponse_PersonaResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deletePersonaPersonasPersonaIdDelete"></a>
# **deletePersonaPersonasPersonaIdDelete**
> oas_any_type_not_mapped deletePersonaPersonasPersonaIdDelete(persona\_id, request-id, request-kong-secret)

Delete Persona

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **persona\_id** | **UUID**|  | [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**oas_any_type_not_mapped**](../Models/AnyType.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="updatePersonaPersonasPersonaIdPut"></a>
# **updatePersonaPersonasPersonaIdPut**
> BaseResponse_PersonaResponse_ updatePersonaPersonasPersonaIdPut(persona\_id, PersonaUpdate, request-id, request-kong-secret)

Update Persona

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **persona\_id** | **UUID**|  | [default to null] |
| **PersonaUpdate** | [**PersonaUpdate**](../Models/PersonaUpdate.md)|  | |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_PersonaResponse_**](../Models/BaseResponse_PersonaResponse_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="uploadPersonaAudioPersonasUploadAudioPost"></a>
# **uploadPersonaAudioPersonasUploadAudioPost**
> BaseResponse_str_ uploadPersonaAudioPersonasUploadAudioPost(file, request-id, request-kong-secret)

Upload Persona Audio

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **file** | **File**|  | [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_str_**](../Models/BaseResponse_str_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

<a name="uploadPersonaAvatarPersonasUploadAvatarPost"></a>
# **uploadPersonaAvatarPersonasUploadAvatarPost**
> BaseResponse_str_ uploadPersonaAvatarPersonasUploadAvatarPost(file, request-id, request-kong-secret)

Upload Persona Avatar

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **file** | **File**|  | [default to null] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**BaseResponse_str_**](../Models/BaseResponse_str_.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

