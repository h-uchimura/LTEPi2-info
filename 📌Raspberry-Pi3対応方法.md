[🔙目次ページへ戻る](README.md)

# 📌Raspberry-Pi3対応方法

## はじめに

[LTEPi for D](http://www.candy-line.io/proandsv.html#ltepiford)は、出荷時の状態でRaspberry Pi Model B+、Raspberry Pi 2 Model Bに対応しています。

Raspberry Pi 3 Model Bについては、Raspberry Pi Model B+やRaspberry Pi 2 Model Bと比べて、消費電力が大きく異なります。このため、容量のより大きな電流を供給できる専用のACアダプターと、そのアダプターを[LTEPi for D](http://www.candy-line.io/proandsv.html#ltepiford)に取り付けるためのDCジャックが必要となります。

これらの作業はご利用者自身にて実施してください。

## 準備するもの

1. 4.0A対応ACアダプター（GF24-US0540）
1. 4.0A対応DCジャック（2DC-0005D100）
1. マイクロSDカード（お使いのOSがインストールされているもの）
1. LANケーブル、またはWiFi USBアダプター（お使いの環境に応じてご用意ください）
1. その他、もしあれば普段お使いの周辺機器（キーボード、ディスプレイ等）

* 4.0A未満のACアダプターでは、電波状況やCPU利用状況により、電力が足りず正常に動作しないことがあります

## 対応作業

### DCジャックを取り付ける

LTEPi for DにDCジャックを取り付けましょう。

### LTEPi for Dをラズパイ3に取り付ける

GPIOピンを合わせてラズパイ3とLTEPi for Dを取り付けましょう。

### ACアダプターをLTEPi for Dに接続する

**注意：ラズパイ3本体のUSB電源を利用してはいけません。本体やLTEPi for Dが故障することがあります**

ラズパイ3にSDカードが入っていることを確認して、LTEPi for DのDCジャックに、ACアダプターを接続しましょう。

### 動作を確認する

ラズパイ3が正常に動作しているかどうかご確認ください。

---
COPYRIGHT © 2016 CANDY LINE, Inc. [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
