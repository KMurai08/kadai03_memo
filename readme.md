
# ①課題番号-プロダクト名

かえってくる人形（ホラーノベルゲーム）

## ②課題内容（どんな作品か）

- 人形を捨てるホラーノベルゲームです。
- 人形を捨てる場所名を入力し、ローカルストレージに保存して次の更新ページで取り出して表示。
- ページ訪問数をローカルストレージに保存して、条件分岐。

## ③DEMO

https://kmurai08.github.io/kadai03_memo/

## ④作ったアプリケーション用のIDまたはPasswordがある場合

- ID: なし
- PW: なし

## ⑤工夫した点・こだわった点

- 怖い雰囲気を壊さないようにボタンを文章の中に混ぜた。
- ブラウザの更新ボタンを押さなくていいように、ボタンにページ更新の処理を含めた。


## ⑥難しかった点・次回トライしたいこと(又は機能)

- ローカルストレージに配列を過去入力した内容も連続して保存していきたかったが、更新すると最新のものしか保存できていなかった。今回は最新の保存内容を取り出せれば問題なかったが、次回、使うことがあれば配列の保存を使ってみたい。
- 音や画面の演出をもっと追加したかった。

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

- [感想]なんとなく参考元からコピーペーストしていたら作りたいものを完成できたが、ローカルストレージの保存や取り出しに使う定数の宣言をいまいちよく理解できていないのを実感した。
- [参考記事]
  - 1. ページ訪問数カウント[(https://recooord.org/javascript-localstorage-count/)]
  - 2. 配列をローカルストレージに保存[https://yurupro.cloud/3107/]
  - 3. ページを更新するボタン[https://codingls.com/jquery/804/#toc2]
