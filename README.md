# p5js-vscode-live

## 何

p5js+typescriptのlive preview環境

## 使い方

+ Recommendされる拡張機能のインストール
+ yarn
+ sketch.tsの編集
+ コマンドパレットからOpen p5 live panel

## メモ
prelaodはサーバーが起動している必要があるようなので、preloadを使用するコードを書くときはLive Serverを起動して、コンパイルされたコードで確認する。
Live Server起動後、buildスクリプトを実行するとLive Serverでコンパイルされたp5jsが表示されるhtmlをブラウザで開く。
