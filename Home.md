[🔙表紙ページへ戻る](Home.md)

[![GitHub release](https://img.shields.io/github/release/CANDY-LINE/ltepi2-service.svg)](https://github.com/CANDY-LINE/ltepi2-service/releases/latest)
[![License BSD3](https://img.shields.io/github/license/CANDY-LINE/ltepi2-service.svg)](http://opensource.org/licenses/BSD-3-Clause)

ltepi2-serviceは、Raspberry Pi上で動作する[LTEPi for D](http://www.candy-line.io/proandsv.html#ltepiford)を動作させるためのシステムサービス（Raspberry Pi上で自動的に動作するソフトウェア）です。

本サービスでは、以下の機能を提供しています。

- AM Telecom社製LTE/3Gモジュールの自動初期設定(モデム設定とAPN設定)
- AM Telecom社製LTE/3Gモジュールの自動起動
- AM Telecom社製LTE/3Gモジュールを操作するコマンドラインツール
    - APN設定、表示
    - LTE/3Gネットワーク状態表示
    - SIM状態表示
    - モデム情報表示

また、以下のモジュールも同時にインストールされます。**常にインストールされます。**
- [candy-board-cli](https://github.com/CANDY-LINE/candy-board-cli) ... コマンドラインツール
- [candy-board-amt](https://github.com/CANDY-LINE/candy-board-amt) ... CANDY-LINE基板AM Telecomモデム向け共通モジュール

以下のモジュールは、インストールの可否を選択可能です。 **通常はインストールされます。**
- [CANDY RED](https://github.com/dbaba/candy-red) ... CANDY EGGクラウドサービスに接続可能なNode-REDベースのフローエディターです。Node.js v0.12またはv4.4が入っていない場合は、Node.js v0.12もインストールされます。すべてのインストールを終えるまでは、有線LAN環境で1~2時間以上かかる場合があります。**Node.jsを更新するため、プリインストールされているNode-REDはアンインストールされます。**既存Node-REDをお使いの方は[こちらの移行方法](Node-REDからの移行方法)をご覧ください。

---
COPYRIGHT © 2016 CANDY LINE, Inc. [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
