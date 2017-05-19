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
| 0x1014 | GetDevicePropDesc          | 指定されたデバイスプロパティ([property](../property/Overview.md))の仕様を返す。 |
| 0x1015 | GetDevicePropValue          | 指定されたデバイスプロパティ([property](../property/Overview.md))の値を返す。 |
| 0x1016 | SetDevicePropValue          | 指定されたデバイスプロパティ([property](../property/Overview.md))に現在値を設定する。 |
| 0x1018 | TerminateOpenCapture          | 指定TransactionIDの連続撮影を終了させる。 |
| 0x101B | GetPartialObject          | 指定オブジェクトハンドルに対するオブジェクトの指定された一部のデータ範囲を返す。 |
| 0x101C | InitiateOpenCapture          | 連続撮影を開始する。 |
| 0x99A3 | SendConfigObject          | 設定情報（[startup.cfg](../operation/ConfigFile.md)）のオブジェクトを本体へ送信する。 |
| 0x99A4 | GetConfigObject          | 本体から設定情報（[startup.cfg](../operation/ConfigFile.md)）のオブジェクトを返す。 |
