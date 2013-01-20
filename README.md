# Bootstrap Base Tumblr Theme
Tumblr用に作成した[Bootstrap](http://twitter.github.com/bootstrap/)をベースにしたテーマです。  
このテーマは[mikejarema/bootstrap-tumblr-theme ・ GitHub](https://github.com/mikejarema/bootstrap-tumblr-theme) をフォークして作成しております。

## 概要

* Bootstrapは、Version 2.2.2を利用しております。
* ヘッダー、フッター、ボディ(3カラム)の構成となっております。
* テキストの投稿をメインに考えて作成しております。

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
* プロフィール写真 128px
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
**Google Webmaster Tool Code** - Googleウェブマスター用のコードを入力して下さい。google-site-verificationのメタ要素のcontentに入力した内容が反映されます。
**Google Analytics UA Code** - Google AnalyticsのUA Codeを入力してください。
**Disqus Shortname** - DisqusのShortnameを入力してください。
**Follow Tumblelog** - Tumblelogを入力してください。入力されると{Follow on Tumblr}ボタンが表示されます。

**Widgets Code1** - Widgets用です。スクリプトタグ等を入力して下さい。 Disqusコメント上部に表示されます。
**Widgets Code2** - Widgets用です。スクリプトタグ等を入力して下さい。 Disqusコメント下部に表示されます。
ウィジェットはZenbackなどの利用を想定しております。

## Configuration Variables

**Background** - Background image.

**Sharing Buttons** - Tweet button (optional via @account & post-tweet follow recommendation), Facebook Like button.

**Disqus Shortname** - Adds Disqus-powered comments to each post permalink page.

**Application Stylesheet** - Drop in your application stylesheet URL here to instruct Tumblr to assimilate your application styling. Hopefully it "just works". Failing that, you can either drop in some Custom CSS or customize the theme markup directly.

**Show Description On Index** - Optionally hide the hero unit (blog description) on the index page.

**Use Responsive Styles** - Determines whether or not the styles used for the theme adapt to different screen sizes & formats.

**Link Logo To Application** - Should the logo (top left, in the nav) link to your Application URL?

**Application URL** - If "Link Logo To Application" is enabled, your blog logo links to this URL.


## Roadmap

* looking for feedback and bug reports, please [complain](https://github.com/mikejarema/bootstrap-tumblr-theme/issues), fork and contribute!)


## Blogs Using Bootstrap Tumblr Theme

* [Namevine Blog](http://blog.namevine.com/)
* [Mike Jarema's Blog](http://mikejarema.com/)
* [The Unscatter.com Blog](http://company.unscatter.com/)
* [Neil Merton's Personal Site](http://neil.merton.me/)
* [Everything in the Sky](http://everythinginthesky.com/)
* [Sam The Cobra's Blog](http://blog.samthecobra.com/)
* [GelaSkins Blog](http://gelaskins.tumblr.com/)
* [Joshua Morrison Photography](http://joshuamorrisonphotography.tumblr.com/)
* [Fourist](http://4ist.tumblr.com/)
* [Edman Goodrich's Blog](http://blog.edmangoodrich.com/)
* [EmbedTree Blog](http://blog.embedtree.com/)
* [FilePicker Blog](http://blog.filepicker.io/)
* [Alex Seville's Blog](http://blog.alexanderseville.com/)
* [AppSocially's Blog](http://blog.appsocial.ly/)
* [Bootswatch Blog](http://news.bootswatch.com/post/32306706557/a-tumblr-theme-for-bootswatch)
* [GetHyper.com](http://gethyper.com/)
* [Ben Bowler's Blog](http://benbowler.com/)
* [Jim Mueller's Blog](http://blog.jimueller.com/)
* [ICodeLike.Me](http://icodelike.me/)
* [/dev/nfc](http://devnfc.com/)
* [Nick Roseboro's Blog](http://blog.nickroseboro.com/)
* [Distrify Blog](http://blog.distrify.com/)
* [Vash Blog](http://blog.vash.co/)
* _... your site? fork and submit a pull request with your site listed here_ 


## License & Notes

The MIT License - Copyright (c) 2012 [Mike Jarema](http://mikejarema.com)

