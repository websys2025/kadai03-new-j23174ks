## 自動販売機（データ構造と各種処理）のミニレポート
### Q5-1. 自動販売機の商品データついて説明せよ。
* データ構造（各項目とその説明）
* 各商品の商品番号、名前、値段、在庫数を連想配列で格納している
* id : 商品番号（整数）
* name : 商品名（文字列）
* price : 価格（整数）
* stock : 在庫数（整数）
* 連想配列の配列として定義するメリット　：　データを素早く検索したり、更新したり、削除したりできる
### Q5-2. showItemListの処理内容について説明せよ。
* 配列の繰り返し処理　：　iがitemsの個数分になるまで繰り返す
* 連想配列の参照方法　：　itemsのi番目を表示する
### Q5-3. buyItemの処理内容について説明せよ。
* 商品購入の可否判定　：　stockが0なら購入不可メッセージの表示
* 商品在庫を減らす処理　：　itemsのi-１番目の在庫を-1する
* 商品番号のエラー処理　：　1~8以外ならばエラーメッセージを表示する
### Q5-4. プログラムの考察
* データ構造について　：　商品の表示をする際に、変数の名前が別になってしまうとfor文が使えなかったりするが、配列化することでまとめることができ、さらにデータの追加や削除が容易である。
* 商品一覧表示と購入処理を関数化したメリット　：　表示させたい内容が同じな場合、なんどもコンソール出力内容を書くとスクリプトが長くなり読みずらいため、まとめたほうが短い文で表示させることができる。
### Q5-5. 感想
* 今回の課題で苦労したこと：セミコロンがなくても動くため、誤字に気づきづらかった。インデントが2になったり4になったりと共通してないため、tabキーが使いづらかった。
* 演習を通して理解できたこと : 連想配列の仕組みが分かった。
* この自動販売機プログラムの追加機能や課題など　：　どのような処理をする文を書けばいいかがわかりづらかった。とくに、「ここにコードを書く」だけなのが分かりづらい
