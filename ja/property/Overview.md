本体や撮影のプロパティであり、[GetDevicePropValue](../operation/0x1015_GetDevicePropValue.md)で取得、[SetDevicePropValue](../operation/0x1016_SetDevicePropValue.md)で設定ができる。

[DevicePropChanged](../event/0x4006_DevicePropChanged.md)でデバイスプロパティの変更を通知する。<BR>
ただし、[SetDevicePropValue](../operation/0x1016_SetDevicePropValue.md)による設定したプロパティの変更は、通知されない。

各プロパティの対応状況は以下のとおり。

| プロパティ名 | 取得 | 設定 |
|:---|:---|:---|
| WhiteBalance | ○ | ○ |
| RGBGain | ○ | ○ |
| ExposureBiasCompensation | ○ | ○ |
| StillCaptureMode | ○ | － |
| PerceivedDeviceType | ○ | － |
| CaptureStatus | ○ | － |
| RecordingTime | ○ | － |
| RemainingRecordingTime | ○ | － |
| RemainingVideos | ○ | － |
| ZenithMode | ○ | ○ |
| VideoOutput | ○ | ○ |
| AudioOutput | ○ | ○ |
| StandbyLedBrightness | ○ | ○ |
| TransmittingLedBrightness | ○ | ○ |
| WDR | ○ | ○ |
| StitchMode | ○ | ○ |
| AudioInputGain | ○ | ○ |
| VideoBitrate | ○ | ○ |
| FlickerReductionMode | ○ | ○ |
| ColorTemperature | ○ | ○ |
