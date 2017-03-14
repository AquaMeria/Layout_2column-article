# 2Column Layout Article


## 本レイアウトについて  
BootStrapをベースにした2カラムの記事レイアウト。  

![スクリーンショット](http://aquanation.heteml.jp/demo/layout/2column_article.png "2カラム記事型レイアウト")
 構成要素  
　├ [ヘッダー] - 横並びメニュー(ハンバーガーメニュー) + メインビジュアル  
　├ [コンテンツ] - コンテンツエリア
　├ [サイドメニュー] - 広告 + 人気記事 + カテゴリー・タグ
　└ [フッター] - サイト説明 + カテゴリナビ  
　※( )内はSP時  



## 対応ブラウザ  

| **Windows** | **Mac** | **スマートフォン・タブレット** |  
|:----- |:-----:|:-----:|:-----:|  
|InternetExplorer 11|○|×|×|  
|Safari 最新版|×|○|○|  
|GoogleChrome 最新版|○|○|○|  
|Firefox 最新版|○|○|×|  
|iOS 10~|×|×|○|  
|AndroidOS 5.0~|×|×|○|  

 
 
## ディレクトリ構造  
 ルート  
　├ [css] … サイトで使われるCSSファイルを全て格納する  
　│　├ bootstrap.min.css … Bootstrapの標準CSS  
　│　├ common.css … 共通パーツで使用するCSS(ヘッダー・フッター)  
　│　├ module.css … 全ページで共通で使用するパーツCSS(無記入)   
　│　└ pagename.css …  各ページでのみ使用するCSS(コンテンツ)  
　│   
　├ [js] … サイトで使われるJavaScriptを全て格納する  
　│　├ bootstrap.min.js … Bootstrapの標準JS  
　│　├ common.js … 共通パーツで使用するJS(ページスクロール)  
　│　├ module.js … 全ページで共通で使用するパーツJS(無記入)   
　│　└ pagename.js …  各ページでのみ使用するJS(無記入)  
　│     
　└ index.html  

