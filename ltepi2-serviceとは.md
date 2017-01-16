[🔙目次ページへ戻る](README.md)

[![GitHub release](https://img.shields.io/github/release/CANDY-LINE/ltepi2-service.svg)](https://github.com/CANDY-LINE/ltepi2-service/releases/latest)
[![License BSD3](https://img.shields.io/github/license/CANDY-LINE/ltepi2-service.svg)](http://opensource.org/licenses/BSD-3-Clause)

ltepi2-serviceは、ラズパイ上で動作する[LTEPi for D](https://www.candy-line.io/製品一覧/ltepi-for-d/)を動作させるためのシステムサービス（ラズパイ上で自動的に動作するソフトウェア）です。

本サービスでは、以下の機能を提供しています。

- AM Telecom社製LTE/3Gモジュールの自動初期設定(モデム設定とAPN設定)
- AM Telecom社製LTE/3Gモジュールの自動起動
- AM Telecom社製LTE/3Gモジュールを操作するコマンドラインツール(「[`candy`コマンド](コマンドラインツール.md))
    - [APN設定](APNの設定.md)
    - [APN表示](APNの表示.md)
    - [LTE/3Gネットワーク状態表示](ネットワーク状態の表示.md)
    - [SIM認識状態表示](SIM認識状態の表示.md)
    - [モデム情報表示](モデム情報の表示.md)

また、上記の機能を実現するため、以下のPythonモジュールが自動的にインストールされます。**これらは常に自動的にインストールされますので、個別に入れていただく必要はありません。**
- [`candy`コマンドラインツール](コマンドラインツール.md)（[ソースコード](https://github.com/CANDY-LINE/candy-board-cli)）
- CANDY-LINE基板AM Telecomモデム向け共通モジュール（[ソースコード](https://github.com/CANDY-LINE/candy-board-amt)） 

以下のモジュールについては、インストールを行うかどうかについて選択することが可能です。 **通常は自動的にインストールされます。**
- [CANDY RED](https://github.com/dbaba/candy-red) ... CANDY EGGクラウドサービスに接続可能なNode-REDベースのフローエディターです。Node.js v0.12またはv4.4が入っていない場合は、Node.js v0.12もインストールされます。すべてのインストールを終えるまでは、有線LAN環境で1~2時間以上かかる場合があります。**Node.jsを更新するため、プリインストールされているNode-REDはアンインストールされます。**既存Node-REDをお使いの方は[こちらの移行方法](Node-REDからの移行方法)をご覧ください。

---
* [対応ハードウェア](対応ハードウェア.md)
* [対応OS](対応OS.md)

---
COPYRIGHT © 2017 CANDY LINE, Inc. [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
