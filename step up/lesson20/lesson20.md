# ローカルストレージを使ったTODO
これは、だれでもエンジニア山浦清秀さんのユーチューブ教材をみて作成しました。[TODOアプリ](https://www.youtube.com/watch?v=E08jeQBa1D0)
***
## 気に入ってる点
1. 入門講座ですが、アプリ開発の進め方も一緒に説明している。
2. CSSを使わず作ってしまう Bootstrapライブラリーに興味が沸く。
3. ローカルストレージの使いかたが分かる。 
***
## 動作確認の方法　
➀　Web開発は、ページ表示と開発ツール（edgeでもOK）を両方開いて行うと便利なことが判りました。VBAでDeburg.printとを使って出力すのと同じで、console.logを使って出力することを学びました。

②　VScodeで開発中Webページは、open with life server を使って開く。ソース変更をするとWebページが自動更新され便利。2画面環境にするともっと便利です。
***
## HTMLの簡易作成
➀！tab で骨具み作成

②　BootstrapライブラりーでCSSレスで作成可能（リンクをコピぺ貼りで利用可能　CDN）clasでスタイルを設定する（使いながら覚える？）

③　JavascriptはIDを設定しておくと便利（追記・変更をJavascriptで行う）
***
## Javascriptプログラム作成の特徴
➀　操作領域は、document操作で、IDと同一名で定義する。

②　ローカルストレージ操作はJSON形式で行う。ストレージ名と同一定義にする。

JSON形式は、オブジェクト形式入力ですが、プロパティ値はエスケープシーケンスで記述が必用になります。

1. \n　改行
2. \t　タブ
3. \'　シングルクォート
4. \"　ダブルクォート
5. \　バックスラッシュ

定義名を同じにしておくことで、関連性が明確になる。一方で勘違いもでる。慣れることが大切です。
