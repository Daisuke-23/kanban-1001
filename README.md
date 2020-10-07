README.md

![LINE BOT](https://github.com/Daisuke-23/line-bot/blob/master/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202020-10-07%2014.17.46.png)
<h1 align="center">LINE BOT</h1>


## 🔍LINE ID

<p align="center">
  <a href="LINEロゴ"><img src="https://github.com/Daisuke-23/line-bot/blob/master/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202020-10-07%2016.52.10.png" height="200px；" /></a></p>

## 🔍概要
・LineのMessage APIを使用<br>
・メッセージを送信すると今日、明日の天気を教えてくれる。<br>
・天気の情報はdrk7.jp(Japan Weather Forecast xml)を使用

## 🔍制作背景(意図)
雨が降るかどうか確認するためだけに毎朝天気予報などを見るのが面倒で、LINEで確認出来たら便利だな！と思い付き作成致しました。
またLINEは誰もがインストールしているツールなので、LINE botを友達追加するだけで気軽に使ってもらう事が出来ます。<br>

## 🔍工夫したポイント
・天気情報は、drk7.jpで提供していただいている、Japan Weather Forecast xmlファイルを使用させていただきました。<br>
・当日の東京エリアの降水確率（6〜12時、12〜18時、18〜24時）のどれか１つが20%以上であった場合にメッセージを送信しています。<br>
・ifの条件式の中で降水確率によって送信されるメッセージを変更しています。

## 🔍使用技術(開発環境)
<p align="center">
  <a href="LINEロゴ"><img src="https://github.com/Daisuke-23/line-bot/blob/master/line_icon_200_v3.jpg" height="100px；" /></a>
  <a href="Rubyロゴ"><img src="https://github.com/Daisuke-23/line-bot/blob/master/%E3%82%BF%E3%82%99%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%88%E3%82%99.png" height="100px；" /></a>
  <a href="Railsロゴ"><img src="https://github.com/Daisuke-23/line-bot/blob/master/rails.png" height="100px;" /></a>
</p>


## 🔍課題や今後実装したい機能
・楽天APIを使って欲しい商品名を送信すれば、ランキング１位〜３位の商品を返してくれる」LINE botを作成したいです。私はよくオンラインショッピングでランキングを見て買い物をするのですが、ランキングページを見に行くのが面倒という事もあり思い付きました。また自分で作ったものが動いて、人に使ってもらえるととても嬉しいです！
