# HTML 学習ロードマップ

## 概要

HTML の勉強をこれから始めようと思っている人のために作りました。

- 未経験からフロントエンドの勉強を始めて何をしたらいいかわからない人
- HTML Professional Level1 の資格受験を検討している人

などの参考になれば幸いです

### ここでしないこと

各自フィットする勉強法があると思うので、詳細な説明はしません

- 公式のリファレンスなどを参考に実際に手を動かしてみる
- youtube で調べたり、Udemy の講座を買ったりして動画で学ぶ
- 本を買う or 図書館で借りる(出版年が古すぎない方が良い)  
  など、いろいろ自分に合う方法を取り入れてみると良いです。

---

## はじめての人

プログラミングとか初めての人は Progate やドットインストールを使用して勉強すると楽しく学べると思います  
[Progate](https://prog-8.com/)  
[ドットインストール](https://dotinstall.com/)  
無料枠だけでも勉強になります。

一通り終わったら実際に自分でコーディングしながら学習すると良いです  
特にこだわりがなければエディタは[VSCODE](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)、ブラウザは[Chrome](https://www.google.com/intl/ja_jp/chrome/)を使用することをお勧めします

---

## HTML

### よく使われる HTML タグの意味と使い方をなんとなく理解する

- メタデータ  
  ` <html> <head> <meta> <link> <title> <style> <body>`
- テキストコンテンツ  
  `<div> <p> <ol> <ul> <li> <blockquote> `
- インラインテキスト  
  `<a> <br> <small> <em> <q> <s> `
- セクションニングコンテンツ  
  `<article> <main> <h1>~<h6> <aside> <nav> <header> <footer> <section>`
- 画像メディア  
  `<img> <video>`
- 埋め込みコンテンツ  
  `<iframe> <picture> <source>`
- SVG  
  `<svg>`
- テーブル  
  `<table> <thead> <tbody> <tfoot> <tr> <th> <td> <col>`
- フォーム  
  `<form> <input> <label> <button>`

### タグが持つ属性について理解する

- グローバル属性  
  `id class style `
- タグ固有の属性があることを知る（すぐ覚える必要はない）  
  例えば`<link>`タグが持つ rel や href など

要素について調べたいときは適宜[HTML リファレンス](https://developer.mozilla.org/ja/docs/Web/HTML/Element#%E7%94%BB%E5%83%8F%E3%81%A8%E3%83%9E%E3%83%AB%E3%83%81%E3%83%A1%E3%83%87%E3%82%A3%E3%82%A2)や[HTML 属性リファレンス](https://developer.mozilla.org/ja/docs/Web/HTML/Attributes)を参照することをおすすめします

上記に挙げたタグや属性だけでも膨大な量があるので最初から覚えようとしなくて OK  
コードを書いていくうちにある程度自然と覚えることになる

## CSS

### プロパティ

Progate とかで HTML と一緒に学べる範囲をまずはしっかり理解する。  
 膨大な量があるので頑張って暗記する必要はない

### ボックスモデル

コンテンツ、パディング、ボーダー、マージンについて理解する[(参考)](https://reffect.co.jp/html/understanding_box_model_of_css)  
 ブロックとインラインブロックについて理解する

### Flex & Grid

Flex の概念について理解する [(参考)](https://www.webcreatorbox.com/tech/css-flexbox-cheat-sheet)  
 ゲーム感覚で学びたい人は[こちら](https://flexboxfroggy.com/#ja)もお勧め

### カスケード

継承と詳細度のスコアがあることを理解する[(参考)](https://developer.mozilla.org/ja/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance)

### セレクター

[参考](https://www.tohoho-web.com/css/selector.htm#attrEqual)

- ユニバーサルセレクタ
- タイプ(タグ名)セレクタ
- クラスセレクタ
- ID セレクタ
- セレクタリスト  
   `E, F { ... }`
- 結合子
  - ` E F { ... }`
  - `E > F { ... }`
  - `E + F { ... }`
  - `E ~ F { ... }`
  - `E || F { ... }`
- 属性セレクタ
  - `[attr]`
  - `[attr="val"]`
  - `[attr~="val"]`
  - `[attr|="val"]`
  - `[attr^="val"]`
  - `[attr$="val"]`
  - `[attr*="val"]`
- 擬似クラス  
  `:hover :nth-of-type :nth-child`

### メディアクエリ & レスポンシブ対応

Viewport、メディアクエリを学んでマルチデバイス対応したページの作り方を把握する

### レイアウト

使ってる要素やスタイリングが適切かどうかはあまり気にせず、見よう見まねで何か作ってみる

- ワンカラムレイアウト
- マルチカラムレイアウト(聖杯レイアウトなど)
- グリッドレイアウト

---

これから書こうと思っていること

## Web の基礎知識

- HTTP/HTTPS
- TLS
- HTTP メソッド
- ステータスコード
- HTTP ヘッダ
- ChromeDev ツールを触ってみる

## API の基礎知識

- トピック検討中
