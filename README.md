# YamakawaNihonshiB-Words.rb
ウェブフィルタの傾向評価用スクリプトです。

## TODO
- テキストマイニングの書籍の読み込み。2024/01/31

## 注意
- **攻撃コードを含むウェブサイトにアクセスする可能性があります。**

## 概要
どのウェブフィルタで日本史に関わるどの単語の Google 検索がどの程度カットされるか。

Google の検索結果の先頭 10 個を評価する。
```ruby
url = agent.page.root.search(’a.l’).map{|j|j[’href’]}
```
ウェブブラウザとそのタイトルバーを記録するプログラムを呼び出す。
```ruby
pid ie = Process.spawn(’”C:\Program Files\Internet Explorer\iexplore.exe”’ + ’ ”’ + row temp + ’”’)
pid url = Process.spawn(’LastUrlRecorder.exe’)
```
生徒側の GUI および文献は次の URI の卒論の本文を参照してください。

[https://shirasakito.github.io](https://shirasakito.github.io)


