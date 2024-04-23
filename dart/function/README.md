# 関数
非同期処理、例外処理についてまとめる。

## 非同期処理
### メリット
前の処理の終了を待たずに、次の処理を進めることができるため、時間短縮を行える。  
-> ユーザの処理待ちの時間を減らすことで、ユーザ体験の向上が見込める。  
同期処理  
A -> B -> C  
非同期処理  
A -> B,C 同時並行

例) Google Map
画面をスクロールした場合、画面は先に動くが、後から表示地点の読み込みが終わる。
これが同期の場合、ユーザからは画面が動かずに固まったように見える。

### 参考サイト
* [非同期処理を使いこなそう ! - 第 1 回 非同期処理ってなんだろう ? -](https://aws.amazon.com/jp/builders-flash/202206/master-asynchronous-execution-01/?awsf.filter-name=*all)