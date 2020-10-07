README.md

![KANBN](https://media.giphy.com/media/7A1NfPDwFyjlZP0CsG/giphy.gif)
<h1 align="center">ToDoタスク管理アプリ</h1>


## 🔍・本番環境
ログインURL:https://kanban1001.herokuapp.com/users/sign_in
・Eメール:test@i.softbank.jp<br>
・パスワード:P77777<br>

## 🔍概要
・Deviseを使ったサインアップ・サインイン機能の開発<br>
・リストやカードを作成する機能の開発<br>
・リストを編集、削除する機能の開発<br>
・リスト詳細機能の開発<br>
・カードを移動する実装<br>
・Herokuを使ってWebアプリケーションを公開<br>


## 🔍制作背景(意図)
HTML・CSS・Javascript・Rubyを使用して開発し、主にRuby on Railsの大まかな流れを把握する事を目標と板しました。
Trelloを参考にして開発し、Trelloのカードと呼ばれる付箋みたいなものを動かしながらタスクを視覚的に管理できるように致しました。

## 🔍工夫したポイント
・ユーザーの情報とリストの情報の関係を工夫してDB設計を致しました。「リストの情報・カードの情報」など全ての情報の関係性を考え、全ての情報をの関係を洗い出したら、テーブル設計を行いました。
テーブル設計で、例えばusersテーブルとlistsテーブルにはどういった関係があるか設計することで、後に変更があった場合も対応できる冗長性・拡張性を考慮出来るよう作成致しました。<br>
・font-awesome-sassを導入することで、Web上でよく利用されるアイコンをアイコンフォントという文字として表示致しました。<br>

## 🔍使用技術(開発環境)
<p align="center">
  <a href="javascriptロゴ"><img src="https://github.com/Daisuke-23/kanban-1001/blob/master/javascript-1.svg" height="100px；" /></a>
  <a href="Rubyロゴ"><img src="https://github.com/Daisuke-23/line-bot/blob/master/%E3%82%BF%E3%82%99%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%88%E3%82%99.png" height="100px；" /></a>
  <a href="Railsロゴ"><img src="https://github.com/Daisuke-23/line-bot/blob/master/rails.png" height="100px;" /></a>
</p>


## 🔍課題や今後実装したい機能
・今回実装したサインアップページをカスタマイズして、パスワードのフォーム1つでもサインアップできるようにしたいです。
・ログインしているユーザーのユーザー名も編集できるようにしたいです、流れとしては、<br>
1.トップページ左上のユーザー名をクリックすると編集ページに遷移<br>
2.テキストボックスに新しい名前を入力<br>
3.編集するボタンを押下<br>
4.更新が成功したら、トップページにリダイレクトし、失敗すれば編集ページに遷移<br>
※ビューはリスト編集ページのものを流用する<br>
