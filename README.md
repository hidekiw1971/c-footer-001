# compornent（共通部品）

## イメージ画像
<img width="390" alt="image" src="https://user-images.githubusercontent.com/99580997/159115366-ae40e641-211e-471f-9374-c48f095d1321.png">
<img width="776" alt="image" src="https://user-images.githubusercontent.com/99580997/159115380-005ee213-2069-4ebb-8a67-92747edf7231.png">
<img width="1088" alt="image" src="https://user-images.githubusercontent.com/99580997/159115388-cff8b7d3-c820-49ac-a238-19a042c437d7.png">


## 概要

- フッター(名前、メニュー、copyright)
- スムーススクロール ボタン(追従)が必要な場合は追加する。

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- 本当は以下のようにスマフォ時は`<li></li>を<a><li></li></a>`で囲んで`display: blolck;`にしたかったが、htmlチェックでエラーとなったので断念。
- `<a class="footer__menu--link" href="#"><li class="footer__menu--list">事業内容</li></a>` → htmlチェックでエラーを検知
- `<li class="footer__menu--list"><a class="footer__menu--link" href="#">事業内容</a></li>` → htmlチェック問題なし

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> footerディレクトリをコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="1012" alt="image" src="https://user-images.githubusercontent.com/99580997/159115428-d15b2471-2831-40ea-8aca-c79b44f5ab0c.png">

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
- <img width="1012" alt="image" src="https://user-images.githubusercontent.com/99580997/159115449-0e5e5b4e-95ea-4a92-93db-78036a47c87b.png">


## portfolio url:

- https://c-0028.wtb.cfbx.jp/

## 参考にしたサイト

- CSS：ホバー時のアンダーラインアニメーションの実装サンプルと mixin を用いた実装方法
- https://www.nxworld.net/css-hover-underline-animation-examples-and-sass-mixin.html

## 更新履歴

- 2022/3/19 初版 作成完了

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
