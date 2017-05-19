## 概要

設定情報（startup.cfg）は、本体の初期状態設定ファイル。<BR>
本体起動時に読み込まれ、本体を設定情報の状態にする。


## 記述形式

### 設定情報（startup.cfg）の記述

JSON形式で記述する。<BR>
文字コードはUTF-8とすること。

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

### parameterの記述

形式によって異なる。

```
case Number
	Value

case String
	"Value"
```

## 有効なoperation

| 名前 | parameter | 概要 |
|:---|:---|:---|
| SetDevicePropValue | - | プロパティ値の設定 |


## 有効なproprety

| 名前 | parameter | 概要 |
|:---|:---|:---|
| WhiteBalance              | Number | ホワイトバランス |
| RGBGain                   | String | RGBの値 |
| ExposureBiasCompensation  | Number | 露出補正値 |
| VideoBitrate              | Number | 録画ビットレート |
| ZenithMode                | Number | カメラの天頂補正モード |
| VideoOutput               | Number | 映像出力のモード |
| AudioOutput               | Number | HDMIでの音声出力の有無 |
| StandbyLedBrightness      | Number | 待機状態のLEDの輝度 |
| TransmittingLedBrightness | Number | 転送状態のLEDの輝度 |
| WDR                       | Number | カメラのWDR(Wide Dynamic Range)モード |
| StitchMode                | Number | カメラ2つの映像をつなぐモード |
| AudioInputGain            | Number | 音声入力ゲイン |


## 記述例

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
