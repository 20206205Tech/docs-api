# SpeechGenerateRequest
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **input** | **String** | Nội dung văn bản cần chuyển thành giọng nói | [optional] [default to Xin chào. Bạn đang sử dụng dịch vụ chuyển văn bản thành giọng nói.] |
| **model** | **String** | Tên model | [optional] [default to tts-1] |
| **voice** | **String** | Mã giọng đọc (VD: vi-VN-NamMinhNeural) | [optional] [default to vi-VN-NamMinhNeural] |
| **response\_format** | **String** | Định dạng file (mp3, wav, ogg) | [optional] [default to mp3] |
| **speed** | **BigDecimal** | Tốc độ đọc | [optional] [default to 1.0] |
| **stream\_format** | **String** | Định dạng stream | [optional] [default to audio] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

