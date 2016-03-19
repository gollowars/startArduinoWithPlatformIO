# Start Arduino with platformio

## よく使うだろうコマンドたち
```
platformio init --board=<ボード名> # platformを初期化
platformio serialports list
platformio run # buildする。platformio.iniでauto-uploadを有効にしておくと自動でuploadできる。
platformio serialports monitor # シリアルモニターする。
platformio serialports list # シリアルポートを確認
```
