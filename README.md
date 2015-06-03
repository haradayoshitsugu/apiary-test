### 1．confファイル内のheaderの値を適宜置き換えてください

```
例．
bot_01.conf
 header=X-Maihama-User-Id:5566d15962ed3125fd000183
 header=X-Parse-Object-Id:lSeOdWJdmy
```

### 2．下記コマンドを実行してください

```
cd bot_01
curl --config bot_01.conf
```
