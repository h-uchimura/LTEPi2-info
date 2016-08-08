モジュールが認識しているSIMの状態を表示します。 結果文字列の`state `には、以下の文字列が入ります。

1. `SIM_STATE_READY ` ... SIMが認識されている
1. `SIM_STATE_ABSENT ` ... SIMが認識されていない

```bash
$ sudo candy sim show
{
  "msisdn": "11111111111",
  "state": "SIM_STATE_READY",
  "imsi": "440111111111111"
}
```