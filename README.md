# Bootstrap Base Tumblr Theme
Tumblr用に作成した[Bootstrap](http://twitter.github.com/bootstrap/)をベースにしたテーマです。  
このテーマは[mikejarema/bootstrap-tumblr-theme ・ GitHub](https://github.com/mikejarema/bootstrap-tumblr-theme) をフォークして作成しております。

## 概要
* Bootstrapは、Version 2.2.2を利用しております。
* ヘッダー、フッター、ボディ(3カラム)の構成となっております。
* テキストの投稿をメインに考えて作成しております。

[動作イメージ](http://testniwaringo.tumblr.com/)


## ページ詳細

### ヘッダー
* ブログタイトル、フォローへのリンク、アーカイブへのリンク、検索があります。
* インデックスページのみ、ヘッダー下にブログタイトル、説明が表示されます。

### ボディ(左サイド)
* POSTした日付がボタンで表示されます。クリックで個別ページに移動します。
* 個別ページでは、設定された各種シェアボタンが表示されます。ボタンは以下です。
** Tumblr
** Twitter
** はてなブックマーク
** Facebook
** google+1
** Buffer

### ボディ(メイン)
#### インデックスページ、個別ページ共通
* POSTしたタイトル、内容が表示されます。
* 内容カラムの下に、タグカラムがあります。

#### インデックスページのみ
* インデックスページにのみ、Disqusのコメント数が表示されます。
* インデックスページにのみ、PostNotes件数が表示されます。

#### 個別ページのみ
* ウィジェット1で入力された内容
* Disqusのコメント詳細
* ウィジェット2で入力された内容
* PostNotes詳細

※ コメントを挟み込む様な形でウィジェットエリアを設けております。

### ボディ(右カラム)
* プロファイル写真 128px
* 設定したFollow on Tumblrボタン
* 設定したSNSへのリンクアイコン

### フッタ
Tumblr、Bootstrap、テーマのGithubページへのリンク


## 使い方

1. bootstrap-tumblr-theme.htmlの内容をコピーして下さい。
2. [カスタマイズ | Tumblr](http://www.tumblr.com/customize)に移動して下さい。
3. カスタムテーマの「HTMLを編集」をクリックして、1.でコピーした内容を貼り付けて下さい。
4. 上部の「保存」、「閉じる」をクリックして下さい。
5. 再度、[カスタマイズ | Tumblr](http://www.tumblr.com/customize)に移動して下さい。
6. デザイン設定の各種項目を設定して下さい。

## 設定項目

### テキスト項目
- **Google Webmaster Tool Code** - Googleウェブマスター用のコードを入力して下さい。google-site-verificationのメタ要素のcontentに入力した内容が反映されます。
- **Google Analytics UA Code** - Google AnalyticsのUA Codeを入力してください。
- **Disqus Shortname** - DisqusのShortnameを入力してください。
- **Follow Tumblelog** - Tumblelogを入力してください。入力されると右カラムに{Follow on Tumblr}アイコンが表示されます。
- **Twitter ID** - TwitterのIDを入力してください。右カラムにTwitterアイコンが表示されます。
- **Github ID** - GithuのIDを入力してください。右カラムにGithubアイコンが表示されます。
- **Google Plusone ID** - Google+1のIDを入力して下さい |https://plus.google.com/{ここの数字}/posts|。右カラムにGoogle+1アイコンが表示されます。
- **Facebook ID** - フェイスブックのIDを入力して下さい。右カラムにFacebookアイコンが表示されます。
- **Wordpress URL** - ワードプレスのブログURLを入力して下さい。右カラムにWordpressアイコンが表示されます。
- **Widgets Code1** - Widgets用です。スクリプトタグ等を入力して下さい。 Disqusコメント上部に表示されます。
- **Widgets Code2** - Widgets用です。スクリプトタグ等を入力して下さい。 Disqusコメント下部に表示されます。

ウィジェットはZenbackなどの利用を想定しております。

### 選択項目
- **Show RSS Button** - 右カラムにRSSアイコンを表示します。
- **Show Twitter Share Button** - 左カラムにTwitterのシェアボタンを表示します。
- **Show Hatena Bookmark Share Button** - 左カラムにはてなブックマークのシェアボタンを表示します。
- **Show Google Plusone Share Button** - 左カラムにGoogle+1のシェアボタンを表示します。
- **Show Buffer Share Button** - 左カラムにBufferのシェアボタンを表示します。
- **Show Facebook Share Button** - 左カラムにFacebookのシェアボタンを表示します。
- **Show Tumblr Share Button** - 左カラムにTumblrのシェアボタンを表示します。

## License
The MIT License
