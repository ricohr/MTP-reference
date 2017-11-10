# operation

| Code | Operation | Overview |
|:---|:---|:---|
| 0x1001 | GetDeviceInfo          | Return the device information data. |
| 0x1002 | OpenSession          | Start a session. |
| 0x1003 | CloseSession          | End a session. |
| 0x1004 | GetStorageIDs          | Return the currently enabled Storage ID list. |
| 0x1005 | GetStorageInfo          | Return the information about the specified Storage ID. |
| 0x1006 | GetNumObjects          | Return the number of objects for the specified Storage ID. |
| 0x1007 | GetObjectHandles          | Return the object handle for the specified Storage ID. |
| 0x1008 | GetObjectInfo          | Return object information for the specified object handle. |
| 0x1009 | GetObject          | Return an object for the specified object handle. |
| 0x100A | GetThumb          | Return a thumbnail in the specified object handle. |
| 0x100B | DeleteObject          | Delete an object for the specified object handle. |
| 0x1014 | GetDevicePropDesc          | Return the specifications for the specified device properties ([property](./property/Overview.md)). |
| 0x1015 | GetDevicePropValue          | Return the values for the specified device properties ([property](./property/Overview.md)). |
| 0x1016 | SetDevicePropValue          | Set the current values as the specified device properties ([property](./property/Overview.md)). |
| 0x1018 | TerminateOpenCapture          | End continuous shooting for the specified Transaction ID. |
| 0x101B | GetPartialObject          | Return some data specified by an object for the specified object handle. |
| 0x101C | InitiateOpenCapture          | Begin continuous shooting. |
| 0x99A3 | SendConfigObject          | Send setting information ([startup.cfg](./operation/ConfigFile.md)) objects to the camera. |
| 0x99A4 | GetConfigObject          | Return setting information ([startup.cfg](./operation/ConfigFile.md)) objects from the camera. |

# property

| Code | Property | Overview |
|:---|:---|:---|
| 0x5005 | WhiteBalance          | Set or fetch white balance. |
| 0x5006 | RGBGain          | Set or fetch RGB values. |
| 0x5010 | ExposureBiasCompensation          | Set or fetch exposure compensation values. |
| 0x5013 | StillCaptureMode          | Fetch a shooting method. |
| 0xD407 | PerceivedDeviceType          | Fetch the camera device type. |
| 0xD808 | CaptureStatus          | Fetch the camera shooting state. |
| 0xD809 | RecordingTime          | Fetch the video shooting time (seconds) during shooting. |
| 0xD80A | RemainingRecordingTime          | Fetch the remaining available video shooting time (seconds) during shooting. |
| 0xD80D | RemainingVideos          | Fetch the remaining available video shooting time (seconds) on the camera. |
| 0xD812 | ZenithMode          | Set or fetch the camera top/bottom correction mode. |
| 0xD813 | VideoOutput          | Set or fetch video output mode. |
| 0xD814 | AudioOutput          | Set or fetch whether to output audio when connected via HDMI. |
| 0xD815 | StandbyLedBrightness          | Set or fetch standby LED brightness. |
| 0xD816 | TransmittingLedBrightness          | Set or fetch LED brightness during transfer. |
| 0xD817 | WDR          | Set or fetch the camera Wide Dynamic Range (WDR) mode. |
| 0xD818 | StitchMode         | Set or fetch stitching two video lenses mode. |
| 0xD819 | AudioInputGain         | Set or fetch audio input gain. |
| 0xD81A | VideoBitrate          | Set or fetch recording bit rate. |
| 0xD81B | FlickerReductionMode  | Set or fetch the camera Flicker Reduction mode. |
| 0xD81C | ColorTemperature      | Set or fetch camera color temperature (Kelvin) values. |

# event

| Code | Event | Overview |
|:---|:---|:---|
| 0x4002 | ObjectAdded          | Notify when an object is added. |
| 0x4004 | StoreAdded           | Notify when storage (microSD card) is added. |
| 0x4005 | StoreRemoved         | Notify when storage (microSD card) is removed. |
| 0x4006 | DevicePropChanged    | Notify when device properties change. |
| 0x400A | StoreFull            | Notify when storage is full. |
| 0x400C | StorageInfoChanged   | Notify when storage information changes. |
