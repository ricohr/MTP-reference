## Overview

The settings data (startup.cfg) is the camera's default settings file.<BR>
The file is loaded when the camera is turned on and sets the camera as per the settings data.


## Description Format

### Description of Settings Data (startup.cfg)

The settings data is described in JSON format.<BR>
Set the character code to UTF-8.

```
{
	operation : parameter,
	... ,
	operation  (only SetDevicePropValue)
	{
		property : parameter,
		...
	}
}
```

### Parameter Description

The parameter description differs depending on the format.

```
case Number
	Value

case String
	"Value"
```

## Valid Operations

| Name | parameter | Overview |
|:---|:---|:---|
| SetDevicePropValue | - | Property settings |


## Valid Properties

| Name | parameter | Overview |
|:---|:---|:---|
| WhiteBalance              | Number | White balance |
| RGBGain                   | String | RGB values |
| ExposureBiasCompensation  | Number | Exposure compensation values |
| SleepDelay                | Number | Delay time for sleeping |
| SleepMode                | Number | Sleep mode |
| ZenithMode                | Number | Camera top/bottom correction mode |
| VideoOutput               | Number | Video output mode |
| AudioOutput               | Number | HDMI audio output |
| StandbyLedBrightness      | Number | LED brightness during standby |
| TransmittingLedBrightness | Number | LED brightness during transfer |
| WDR                       | Number | Camera Wide Dynamic Range (WDR) mode  |
| StitchMode                | Number | Stitching two camera video mode |
| AudioInputGain            | Number | Audio Input Gain |
| VideoBitrate              | Number | Recording bit rate |
| FlickerReductionMode      | Number | Camera Flicker Reduction mode |
| ColorTemperature          | Number | Color temperature value |


## Description Example

```
{
    "SetDevicePropValue" :
    {
        "WhiteBalance" : 1,
        "RGBGain" : "480:100:180",
        "ExposureBiasCompensation" : 0
    }
}
```
