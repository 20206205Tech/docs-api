# Documentation for code-persona-service (production)

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://134.185.92.211/code-persona-service*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *AudioApi* | [**adminGenerateAudioAudioV1TtsPost**](Apis/AudioApi.md#adminGenerateAudioAudioV1TtsPost) | **POST** /audio/v1/tts | Admin Generate Audio |
*AudioApi* | [**generateSpeechAudioV1AudioSpeechPost**](Apis/AudioApi.md#generateSpeechAudioV1AudioSpeechPost) | **POST** /audio/v1/audio/speech | Generate Speech |
*AudioApi* | [**rootAudioV1Get**](Apis/AudioApi.md#rootAudioV1Get) | **GET** /audio/v1/ | Root |
| *DefaultApi* | [**rootGet**](Apis/DefaultApi.md#rootGet) | **GET** / | Root |
| *EngineAdminApi* | [**createEngineEnginesPost**](Apis/EngineAdminApi.md#createEngineEnginesPost) | **POST** /engines | Create Engine |
*EngineAdminApi* | [**deleteEngineEnginesEngineIdDelete**](Apis/EngineAdminApi.md#deleteEngineEnginesEngineIdDelete) | **DELETE** /engines/{engine_id} | Delete Engine |
*EngineAdminApi* | [**getAllEnginesEnginesGet**](Apis/EngineAdminApi.md#getAllEnginesEnginesGet) | **GET** /engines | Get All Engines |
*EngineAdminApi* | [**updateEngineEnginesEngineIdPut**](Apis/EngineAdminApi.md#updateEngineEnginesEngineIdPut) | **PUT** /engines/{engine_id} | Update Engine |
| *PersonaAdminApi* | [**createPersonaPersonasPost**](Apis/PersonaAdminApi.md#createPersonaPersonasPost) | **POST** /personas | Create Persona |
*PersonaAdminApi* | [**deletePersonaPersonasPersonaIdDelete**](Apis/PersonaAdminApi.md#deletePersonaPersonasPersonaIdDelete) | **DELETE** /personas/{persona_id} | Delete Persona |
*PersonaAdminApi* | [**updatePersonaPersonasPersonaIdPut**](Apis/PersonaAdminApi.md#updatePersonaPersonasPersonaIdPut) | **PUT** /personas/{persona_id} | Update Persona |
*PersonaAdminApi* | [**uploadPersonaAudioPersonasUploadAudioPost**](Apis/PersonaAdminApi.md#uploadPersonaAudioPersonasUploadAudioPost) | **POST** /personas/upload-audio | Upload Persona Audio |
*PersonaAdminApi* | [**uploadPersonaAvatarPersonasUploadAvatarPost**](Apis/PersonaAdminApi.md#uploadPersonaAvatarPersonasUploadAvatarPost) | **POST** /personas/upload-avatar | Upload Persona Avatar |
| *PublicApi* | [**getAllPersonaPersonasGet**](Apis/PublicApi.md#getAllPersonaPersonasGet) | **GET** /personas | Get All Persona |
| *VoiceAdminApi* | [**createVoiceVoicesPost**](Apis/VoiceAdminApi.md#createVoiceVoicesPost) | **POST** /voices | Create Voice |
*VoiceAdminApi* | [**deleteVoiceVoicesVoiceUuidDelete**](Apis/VoiceAdminApi.md#deleteVoiceVoicesVoiceUuidDelete) | **DELETE** /voices/{voice_uuid} | Delete Voice |
*VoiceAdminApi* | [**getAllVoicesVoicesGet**](Apis/VoiceAdminApi.md#getAllVoicesVoicesGet) | **GET** /voices | Get All Voices |
*VoiceAdminApi* | [**syncElevenlabsVoicesSyncElevenlabsPost**](Apis/VoiceAdminApi.md#syncElevenlabsVoicesSyncElevenlabsPost) | **POST** /voices/sync-elevenlabs | Sync Elevenlabs |
*VoiceAdminApi* | [**updateVoiceVoicesVoiceUuidPut**](Apis/VoiceAdminApi.md#updateVoiceVoicesVoiceUuidPut) | **PUT** /voices/{voice_uuid} | Update Voice |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [AdminAudioGenerateRequest](./Models/AdminAudioGenerateRequest.md)
 - [BaseResponse_EngineResponse_](./Models/BaseResponse_EngineResponse_.md)
 - [BaseResponse_PaginatedEngineResponse_](./Models/BaseResponse_PaginatedEngineResponse_.md)
 - [BaseResponse_PaginatedPersonaResponse_](./Models/BaseResponse_PaginatedPersonaResponse_.md)
 - [BaseResponse_PaginatedVoiceResponse_](./Models/BaseResponse_PaginatedVoiceResponse_.md)
 - [BaseResponse_PersonaResponse_](./Models/BaseResponse_PersonaResponse_.md)
 - [BaseResponse_VoiceResponse_](./Models/BaseResponse_VoiceResponse_.md)
 - [BaseResponse_str_](./Models/BaseResponse_str_.md)
 - [EngineCreate](./Models/EngineCreate.md)
 - [EngineResponse](./Models/EngineResponse.md)
 - [EngineUpdate](./Models/EngineUpdate.md)
 - [HTTPValidationError](./Models/HTTPValidationError.md)
 - [Location_inner](./Models/Location_inner.md)
 - [PaginatedEngineResponse](./Models/PaginatedEngineResponse.md)
 - [PaginatedPersonaResponse](./Models/PaginatedPersonaResponse.md)
 - [PaginatedVoiceResponse](./Models/PaginatedVoiceResponse.md)
 - [PersonaCreate](./Models/PersonaCreate.md)
 - [PersonaResponse](./Models/PersonaResponse.md)
 - [PersonaUpdate](./Models/PersonaUpdate.md)
 - [SpeechGenerateRequest](./Models/SpeechGenerateRequest.md)
 - [ValidationError](./Models/ValidationError.md)
 - [VoiceCreate](./Models/VoiceCreate.md)
 - [VoiceResponse](./Models/VoiceResponse.md)
 - [VoiceUpdate](./Models/VoiceUpdate.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="APIKeyHeader"></a>
### APIKeyHeader

- **Type**: API key
- **API key parameter name**: Authorization
- **Location**: HTTP header

<a name="HTTPBearer"></a>
### HTTPBearer

- **Type**: HTTP Bearer Token authentication

