# curl使い方

## オプション
### --data-binary <data>
データを指定する文字列の前にアットマーク@を付けた場合、その後ろはファイル名を表す。
改行などを含むデータを変換せずにそのまま送信する。似たオプションの-d, --dataもデータを送信するが、データの変換が行われる。

### --unix-socket <path>
ネットワークを通さずに、指定されたunixソケットを通して通信する。

## 参考
[curl - How To Use](https://curl.se/docs/manpage.html)