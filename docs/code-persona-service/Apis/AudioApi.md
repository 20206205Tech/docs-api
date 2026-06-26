# AudioApi

All URIs are relative to *http://134.185.92.211/code-persona-service*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**adminGenerateAudioAudioV1TtsPost**](AudioApi.md#adminGenerateAudioAudioV1TtsPost) | **POST** /audio/v1/tts | Admin Generate Audio |
| [**generateSpeechAudioV1AudioSpeechPost**](AudioApi.md#generateSpeechAudioV1AudioSpeechPost) | **POST** /audio/v1/audio/speech | Generate Speech |
| [**rootAudioV1Get**](AudioApi.md#rootAudioV1Get) | **GET** /audio/v1/ | Root |


<a name="adminGenerateAudioAudioV1TtsPost"></a>
# **adminGenerateAudioAudioV1TtsPost**
> oas_any_type_not_mapped adminGenerateAudioAudioV1TtsPost(AdminAudioGenerateRequest, is\_download, request-id, request-kong-secret)

Admin Generate Audio

    API dành cho Admin để tạo và nghe thử/tải xuống file âm thanh.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **AdminAudioGenerateRequest** | [**AdminAudioGenerateRequest**](../Models/AdminAudioGenerateRequest.md)|  | |
| **is\_download** | **Boolean**| True để trình duyệt tải file, False để nghe trực tiếp | [optional] [default to false] |
| **request-id** | **String**|  | [optional] [default to null] |
| **request-kong-secret** | **String**|  | [optional] [default to null] |

### Return type

[**oas_any_type_not_mapped**](../Models/AnyType.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="generateSpeechAudioV1AudioSpeechPost"></a>
# **generateSpeechAudioV1AudioSpeechPost**
> oas_any_type_not_mapped generateSpeechAudioV1AudioSpeechPost(SpeechGenerateRequest)

Generate Speech

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **SpeechGenerateRequest** | [**SpeechGenerateRequest**](../Models/SpeechGenerateRequest.md)|  | |

### Return type

[**oas_any_type_not_mapped**](../Models/AnyType.md)

### Authorization

[APIKeyHeader](../README.md#APIKeyHeader)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="rootAudioV1Get"></a>
# **rootAudioV1Get**
> oas_any_type_not_mapped rootAudioV1Get()

Root

### Parameters
This endpoint does not need any parameter.

### Return type

[**oas_any_type_not_mapped**](../Models/AnyType.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

