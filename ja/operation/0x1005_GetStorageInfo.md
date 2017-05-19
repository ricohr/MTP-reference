# GetStorageInfo

## Operation Code

0x1005

## 概要

指定されたStorage IDに対する情報を返す。

各Dataset fieldの詳細は以下の通り。

| 名前 | 仕様 |
|:---|:---|
| MaxCapability | ストレージ容量 |
| FreeSpaceInBytes | 利用可能なストレージ空き容量 |

録画時は、利用可能なストレージ空き容量が更新される。
