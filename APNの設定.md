[🔙目次ページへ戻る](README.md)

APNを設定します。単一のAPNのみ設定することができます。

すでにインターネットに接続できている状態でAPNを変更した場合、変更を反映させるためにはモジュールを再起動する必要があります。```sudo reboot```などの方法で再起動を行ってください。

```bash
pi@raspberrypi:~ $ sudo candy apn set -n APN名 -u ユーザーID -p パスワード
```

以下に、3つのMVNO向けの設定例を示します。他のMVNOをお使いの場合も、上記コマンドを利用してAPNを設定することができます。

## U-mobileの設定

デフォルトの設定には、U-mobile向けの設定が入っています。もし、他のAPNからU-mobileの設定に戻したい時は、次のコマンドを実行しましょう。

```bash
pi@raspberrypi:~ $ sudo candy apn set -n umobile.jp -u umobile@umobile.jp -p umobile
```

## IIJ mioの設定

IIJ mioをご利用の場合は、以下のコマンドを実行してAPNを設定しましょう。

```bash
pi@raspberrypi:~ $ sudo candy apn set -n iijmio.jp -u mio@iij -p iij
```

## SORACOM Airの設定

SORACOM Airをご利用の場合は、以下のコマンドを実行してAPNを設定しましょう。

```bash
pi@raspberrypi:~ $ sudo candy apn set -n soracom.io -u sora -p sora
```

## OCNモバイルONEの設定

OCNモバイルONEをご利用の場合は、以下のコマンドを実行してAPNを設定しましょう。

```bash
pi@raspberrypi:~ $ sudo candy apn set -n lte-d.ocn.ne.jp -u mobileid@ocn -p mobile
```

* [APNの表示](APNの表示.md)
* [ネットワーク状態の表示](ネットワーク状態の表示.md)
* [SIM認識状態の表示](SIM認識状態の表示.md)
* [モデム情報の表示](モデム情報の表示.md)

---
COPYRIGHT © 2016 CANDY LINE, Inc. [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
