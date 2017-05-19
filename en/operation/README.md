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
| 0x1014 | GetDevicePropDesc          | Return the specifications for the specified device properties ([property](../property/Overview.md)). |
| 0x1015 | GetDevicePropValue          | Return the values for the specified device properties ([property](../property/Overview.md)). |
| 0x1016 | SetDevicePropValue          | Set the current values as the specified device properties ([property](../property/Overview.md)). |
| 0x1018 | TerminateOpenCapture          | End continuous shooting for the specified Transaction ID. |
| 0x101B | GetPartialObject          | Return some data specified by an object for the specified object handle. |
| 0x101C | InitiateOpenCapture          | Begin continuous shooting. |
| 0x99A3 | SendConfigObject          | Send setting information ([startup.cfg](../operation/ConfigFile.md)) objects to the camera. |
| 0x99A4 | GetConfigObject          | Return setting information ([startup.cfg](../operation/ConfigFile.md)) objects from the camera. |
