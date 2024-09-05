# YamakawaNihonshiB-Words.rb
ウェブフィルタの傾向評価用スクリプトです。

## [Draft] My graduation thesis's English translation 
[A prototyping of the poll-based browser filter for education about named that the “Alt Filter” (2012)](https://docs.google.com/document/d/1Xoy2sQM66y1-8d0a86DIDpWHxMtv5camqgo_8Y0-TnA/edit?usp=drivesdk).

## TODO
- テキストマイニングの書籍の読み込み。2024/01/31
- 卒論を置きたい。2024/02/02
- 卒論を英訳したい。辞書を探したい。2024/02/02

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
詳しくは卒論の本文である ```thesis.tex``` を参照してください。


