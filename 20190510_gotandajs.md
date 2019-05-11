# gotanda.js

# Web Components入門 @tiwu_official

* https://speakerdeck.com/arayaryoma/gotandajs-11-nodejs-recursive-readdir

* pwa とか web component 好き
* vanilla js, html, css で再利用可能なコンポーネントを作るやつ
* カスタム要素
  * customElements.define()
  * 新しいタグは必ずダッシュが必要
* shadow dom
  * cssを閉じ込める(scoped css)
* 事例
  * youtube
  * 声のブログ
  * pairs
  * 一休
* 対応ブラウザ
  * Edge以外いける

# Node.jsでのrecursive readdirを考える @あらや

* https://speakerdeck.com/arayaryoma/gotandajs-11-nodejs-recursive-readdir

# Gatsbyで画像を扱うときのTips @takanorip

* gatsby
  * react 製の静的サイトジェネレータ
  * ビルド時にローカルにサーバ立てる
  * graphQLでアクセス
* 画像
  * gatsby-image という標準ライブラリを用いてアクセス
  * コンポーネントから呼ぶクエリとルートから渡すからクエリ
  * ルートから渡すクエリにはvariablesを渡せるが、コンポーネントからは不可能
    * じゃあどうすれば動的コンテンツを読み込めるんだ・・・
* gatsby-transformar-library
  * jsonをインポートしなくてもコンポーネントのクエリからjsonの値にアクセス可能
  * "image"に相対パスを書いておくとビルド時に解釈してくれる

# フロントエンドのいろは @kahirokunn

* react-redux
  * reducerの粒度の話とか
  * stateでやればいいのになぜreducer？とか
* react-apolo
  * cacheがいい感じに効く
* elm
  * システムレベルでの品質担保が可能になった

* 結論
  * 状態管理が非常に大変

* セカンドシステム症候群


# 今更recomposeの話(仮) @Quramy

* https://qiita.com/Quramy/items/248df8d30e8a93d503f8

# AWS CDK の話 @yamatatsu

* https://slides.yamatatsu193.net/cdk/0#0

# dockerでnodeの開発は厳しいのか？ @mizuki_r

* https://speakerdeck.com/rymizuki/dockerdenodefalsekai-fa-hayan-siifalseka-number-gotandajs

* 弁護士ドットコムの人
* I/O が非常に遅い
* Docker に mount した Volume の更新は遅い
* マウントしなければよい
  * まぁまぁいける
* VS Code Insiders

# Gatsby.jsとNetlifyとの付き合い方 @kikunantoka

* https://speakerdeck.com/kikunantoka/gatsby-js-and-netlify
