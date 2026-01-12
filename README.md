# TODOアプリ

シンプルで使いやすいWebベースのTODOアプリケーションです。

## 機能

- TODOの追加
- TODOの削除
- TODOの完了/未完了の切り替え
- ローカルストレージによるデータの永続化

## 使い方

1. `index.html` をブラウザで開く
2. 入力欄に新しいTODOを入力
3. 「追加」ボタンをクリックするか、Enterキーを押してTODOを追加
4. チェックボックスをクリックして完了/未完了を切り替え
5. 「削除」ボタンをクリックしてTODOを削除

## ファイル構成

- `index.html` - メインHTMLファイル
- `style.css` - スタイルシート
- `script.js` - JavaScript（ロジック）

## 技術スタック

- HTML5
- CSS3
- JavaScript (Vanilla)
- LocalStorage API

## データの永続化

TODOデータはブラウザのLocalStorageに保存されるため、ブラウザを閉じても再度開いたときに前回のデータが復元されます。

## デプロイ

このアプリケーションは以下のURLでアクセスできます:

- **Vercel**: https://todo-beta-lilac.vercel.app
- **GitHub Pages**: https://iiyan.github.io/todo/

自動デプロイが有効になっているため、masterブランチへのpushで自動的にデプロイされます。
