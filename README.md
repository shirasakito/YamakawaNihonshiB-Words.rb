# YamakawaNihonshiB-Words.rb
thesis 2012

ウェブフィルタの傾向評価用スクリプト。

どのウェブフィルタで日本史に関わるどの単語の Google 検索がどの程度カットされるか。

_攻撃コードを含むウェブサイトにアクセスする可能性があります。_

Google の検索結果の先頭 10 個を評価する。
```
url = agent.page.root.search(’a.l’).map{|j|j[’href’]}
```
ウェブブラウザとそのタイトルバーを記録するプログラムを呼び出す。
```
pid ie = Process.spawn(’”C:\Program Files\Internet Explorer\iexplore.exe”’ + ’ ”’ + row temp + ’”’)
pid url = Process.spawn(’LastUrlRecorder.exe’)
```
生徒側の GUI は卒論の本文を参照してください。
