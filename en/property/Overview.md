The camera and shooting properties. Can be fetched with [GetDevicePropValue](../operation/0x1015_GetDevicePropValue.md) and set with [SetDevicePropValue](../operation/0x1016_SetDevicePropValue.md).

Notify when device properties change with [DevicePropChanged](../event/0x4006_DevicePropChanged.md).<BR>
However, there is no notification when properties set with [SetDevicePropValue](../operation/0x1016_SetDevicePropValue.md) are changed.

The properties support status is as follows.

| Property Name | Acquirement | Setting |
|:---|:---|:---|
| WhiteBalance | ○ | ○ |
| RGBGain | ○ | ○ |
| ExposureBiasCompensation | ○ | ○ |
| StillCaptureMode | ○ | － |
| PerceivedDeviceType | ○ | － |
| CaptureStatus | ○ | － |
| SleepDelay | ○ | ○ |
| RecordingTime | ○ | － |
| RemainingRecordingTime | ○ | － |
| RemainingVideos | ○ | － |
| SleepMode | ○ | ○ |
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

