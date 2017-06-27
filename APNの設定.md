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

## mopera U (Xiデータ通信用アクセスポイント)の設定

mopera Uをご利用の場合は、あらかじめ`mopera U基本ユーザID`と`mopera U基本パスワード`をご確認ください。ご不明な場合は、[こちら](https://www.mopera.net/manual/pcpda/option/index.html)をご覧になるかNTT DOCOMO社までお問い合わせください。
IDとパスワードがわかりましたら、以下のコマンドを実行してAPNを設定しましょう。

```bash
pi@raspberrypi:~ $ sudo candy apn set -n mopera.net -u mopera U基本ユーザID -p mopera U基本パスワード
```

例）`mopera U基本ユーザID`が「myuser」であり、`mopera U基本パスワード`が「1234567」の場合
```bash
pi@raspberrypi:~ $ sudo candy apn set -n mopera.net -u myuser -p 1234567
```

* `mopera U基本ユーザID`と`mopera U基本パスワード`はご自身の情報に置き換えて入力してください
* Xiデータ通信用アクセスポイント以外のAPNをご利用の場合は、[こちらのページ](https://start.mopera.net/contents/noauth/access/accessPc.html)をご覧ください

* [APNの表示](APNの表示.md)
* [ネットワーク状態の表示](ネットワーク状態の表示.md)
* [SIM認識状態の表示](SIM認識状態の表示.md)
* [モデム情報の表示](モデム情報の表示.md)

---
© 2017 CANDY LINE INC. [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
