# StillCaptureMode

## Device Prop Code

0x5013

## Overview

Fetch a shooting method.

## Support value

| Value | Description |
|:---|:---|
| 0x8002 | Video Shooting<BR>Shooting mode is the value during Video Shooting. |
| 0x8005 | HDMI Live Streaming<BR>Shooting mode is the value during HDMI Live Streaming. |

## Event

When the shooting method is changed with the camera, a [DevicePropChanged](../event/0x4006_DevicePropChanged.md) event notification is sent.
