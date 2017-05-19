# RGBGain

## Device Prop Code

0x5006

## 概要

RGBの値を取得または設定する。<BR>
（[WhiteBalance](../property/0x5005_WhiteBalance.md) がマニュアル時のみ有効）

## サポート値

RGBの各値を数値として"R:G:B"の文字列形式で設定する。
Gは100固定となる。

| Value | Description |
|:---|:---|
| R | 0～500（1きざみ） |
| G | 100（固定） |
| B | 0～500（1きざみ） |
