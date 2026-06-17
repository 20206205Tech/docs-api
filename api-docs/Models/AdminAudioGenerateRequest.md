# AdminAudioGenerateRequest
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **text** | **String** | Nội dung văn bản cần chuyển thành giọng nói | [default to null] |
| **voice\_uuid** | **String** | UUID của giọng đọc (voice_uuid từ bảng voices) hoặc voice_code | [optional] [default to vi-VN-NamMinhNeural] |
| **speed** | **BigDecimal** | Tốc độ đọc (mặc định 1.0, &lt; 1 là chậm, &gt; 1 là nhanh) | [optional] [default to 1.0] |
| **response\_format** | **String** | Định dạng file (mp3, wav, ogg) | [optional] [default to mp3] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

