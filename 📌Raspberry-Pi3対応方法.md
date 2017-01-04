[🔙目次ページへ戻る](README.md)

# 📌AC電源供給対応方法

## はじめに

[LTEPi for D](http://www.candy-line.io/proandsv.html#ltepiford)は、出荷時の状態では、ラズパイ本体のUSB電源より電力が供給されます。
ラズパイ本体に[LTEPi for D](http://www.candy-line.io/proandsv.html#ltepiford)以外のUSB機器を取り付けた時や、CPU負荷が高い処理を行った時は、電力低下が起こることがあります。このような低下をできるだけ避けるために、[LTEPi for D](http://www.candy-line.io/proandsv.html#ltepiford)には、直接ACアダプターを接続できる接続口（DCジャック）をつけることができます。
もし、安定的に電源を供給する必要がある場合は以下の部品や機器を用意し、[LTEPi for D](http://www.candy-line.io/proandsv.html#ltepiford)に取り付けてください。

なお、これらの作業はお手数ですがご利用者自身にて実施してください。

## 準備するもの

1. 4.0A対応ACアダプター（GF24-US0540）
1. 4.0A対応DCジャック（2DC-0005D100）
1. マイクロSDカード（お使いのOSがインストールされているもの）
1. LANケーブル、またはWiFi USBアダプター（お使いの環境に応じてご用意ください）
1. その他、もしあれば普段お使いの周辺機器（キーボード、ディスプレイ等）

* 4.0A未満のACアダプターでは、電波状況や追加したUSB機器の利用状況、それにCPU利用状況により、電力が足りず正常に動作しないことがあります

## 対応作業

### DCジャックを取り付ける

LTEPi for DにDCジャックを取り付けましょう。

### LTEPi for Dをラズパイに取り付ける

GPIOピンを合わせてラズパイとLTEPi for Dを取り付けましょう。

### ACアダプターをLTEPi for Dに接続する

**注意：ラズパイ本体のUSB電源を利用してはいけません。本体やLTEPi for Dが故障することがあります**

ラズパイにSDカードが入っていることを確認して、LTEPi for DのDCジャックに、ACアダプターを接続しましょう。

### 動作を確認する

ラズパイが正常に動作しているかどうかご確認ください。

---
COPYRIGHT © 2016 CANDY LINE, Inc. [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
