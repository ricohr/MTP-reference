# operation

| Code | Operation | Overview |
|:---|:---|:---|
| 0x1001 | GetDeviceInfo          | デバイス情報のデータを返す。 |
| 0x1002 | OpenSession          | セッションを開始する。 |
| 0x1003 | CloseSession          | セッションを終了する。 |
| 0x1004 | GetStorageIDs          | 現在有効なStorage IDのリストを返す。 |
| 0x1005 | GetStorageInfo          | 指定されたStorage IDに対する情報を返す。 |
| 0x1006 | GetNumObjects          | 指定Storage IDに対するオブジェクトの数を返す。 |
| 0x1007 | GetObjectHandles          | 指定Storage IDに対するオブジェクトハンドルを返す。 |
| 0x1008 | GetObjectInfo          | 指定オブジェクトハンドルに対するオブジェクト情報を返す。 |
| 0x1009 | GetObject          | 指定オブジェクトハンドルに対するオブジェクトを返す。 |
| 0x100A | GetThumb          | 指定オブジェクトハンドル内のサムネイルを返す。 |
| 0x100B | DeleteObject          | 指定オブジェクトハンドルに対するオブジェクトを削除する。 |
| 0x1014 | GetDevicePropDesc          | 指定されたデバイスプロパティ([property](./property/Overview.md))の仕様を返す。 |
| 0x1015 | GetDevicePropValue          | 指定されたデバイスプロパティ([property](./property/Overview.md))の値を返す。 |
| 0x1016 | SetDevicePropValue          | 指定されたデバイスプロパティ([property](./property/Overview.md))に現在値を設定する。 |
| 0x1018 | TerminateOpenCapture          | 指定TransactionIDの連続撮影を終了させる。 |
| 0x101B | GetPartialObject          | 指定オブジェクトハンドルに対するオブジェクトの指定された一部のデータ範囲を返す。 |
| 0x101C | InitiateOpenCapture          | 連続撮影を開始する。 |
| 0x99A3 | SendConfigObject          | 設定情報（[startup.cfg](./operation/ConfigFile.md)）のオブジェクトを本体へ送信する。 |
| 0x99A4 | GetConfigObject          | 本体から設定情報（[startup.cfg](./operation/ConfigFile.md)）のオブジェクトを返す。 |

# property

| Code | Property | Overview |
|:---|:---|:---|
| 0x5005 | WhiteBalance          | ホワイトバランスを取得または設定する。 |
| 0x5006 | RGBGain          | RGBの値を取得または設定する。 |
| 0x5010 | ExposureBiasCompensation          | 露出補正値を取得または設定する。 |
| 0x5013 | StillCaptureMode          | 撮影方法を取得する。 |
| 0xD407 | PerceivedDeviceType          | カメラのデバイス種類を取得する。 |
| 0xD803 | SleepDelay             | カメラが自動的にスリープ状態になる時間を取得または設定する。| 
| 0xD808 | CaptureStatus          | カメラの撮影実行状態を取得する。 |
| 0xD809 | RecordingTime          | 撮影中の動画撮影時間(秒)を取得する。 |
| 0xD80A | RemainingRecordingTime          | 撮影中の残り動画撮影可能時間(秒)を取得する。 |
| 0xD80D | RemainingVideos          | カメラ本体の残り動画撮影可能時間(秒)を取得する。 |
| 0xD80E | SleepMode           | カメラのスリープ状態を取得または設定する。| 
| 0xD812 | ZenithMode          | カメラの天頂補正モードを取得または設定する。 |
| 0xD813 | VideoOutput          | 映像出力のモードを取得または設定する。 |
| 0xD814 | AudioOutput          | HDMI時の音声出力の有無を取得または設定する。 |
| 0xD815 | StandbyLedBrightness          | 待機状態のLEDの輝度を取得または設定する。 |
| 0xD816 | TransmittingLedBrightness          | 転送状態のLEDの輝度を取得または設定する。 |
| 0xD817 | WDR          | カメラのWDR(Wide Dynamic Range)モードを取得または設定する。 |
| 0xD818 | StitchMode         | 2つのレンズの映像をつなぐモードを取得または設定する。 |
| 0xD819 | AudioInputGain         | 音声入力ゲインを取得または設定する。 |
| 0xD81A | VideoBitrate          | 録画ビットレートを取得または設定する。 |
| 0xD81B | FlickerReductionMode     | カメラのフリッカー低減モードを取得または設定する。 |
| 0xD81C | ColorTemperature         | カメラの色温度（ケルビン）の値を取得または設定する。 |

# event

| Code | Event | Overview |
|:---|:---|:---|
| 0x4002 | ObjectAdded          | オブジェクト追加を通知する。 |
| 0x4004 | StoreAdded           | ストレージ（マイクロSDカード）の追加を通知する。 |
| 0x4005 | StoreRemoved         | ストレージ（マイクロSDカード）の除去を通知する。 |
| 0x4006 | DevicePropChanged    | デバイスプロパティの変更を通知する。 |
| 0x400A | StoreFull            | ストレージFULLを通知する。 |
| 0x400C | StorageInfoChanged   | ストレージ情報の変更を通知する。 |
