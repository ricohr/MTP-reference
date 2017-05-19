# StillCaptureMode

## Device Prop Code

0x5013

## 概要

撮影方法を取得する。

## サポート値

| Value | Description |
|:---|:---|
| 0x8002 | 動画撮影<BR>撮影モードが「動画記録」時の値。 |
| 0x8005 | HDMIライブストリーミング<BR>撮影モードが「HDMIライブストリーミング」時の値。 |

## イベント

本体操作によって撮影方法を切り替えた場合には、[DevicePropChanged](../event/0x4006_DevicePropChanged.md) イベントが通知される。
