# React.js meetup

## opening

* 会場案内 & sponser talk
* eight: online buisiness card exchange

## @Panda_Program: Reactの情報蒐集源

* 大切なことは一次資料に当たること
  * github
    * きつい
      * ほぼ一次資料を探す

* 公式ドキュメント
* 設計思想
  * Thinking in React
* ロードマップ

* Facebook の公式サイト
  * 回h津者向けBlog
  * FacebookのConference(F8)の動画
  * React の公式 Twitter

* Dan Abramov
  * Twitter
    * ホットリロードに取り組み中

* Blog
  * 最初 Medium
  * 次 Overriacted(Gatsby.js製)

* Google Discover
* web.dev
  * Chrome開発チームがReact製のことについて

## @taka_ft: Rakuten Travelのフロントエンド刷新について

* フロントエンドエンジニアだけでかなりの人数
* React使っている(2017,8年頃を契機に)
* 次世代楽天トラベルを目指している
* consumer
* provider
* ui-component
  * storybook
  * 2PRがしんどい（ui-componentライブラリと取り込む側）
    * 一回ライブラリ化を諦める
    * 将来的にまたcomponent化するかも
* framework library
  * react-universal-hot-exampleにもinspire
* i18n/l10n
* Reliability
  * componentの肥大化
  * performance劣化
  * targetがない
  * Role & Responsibility
    * process - kpi tracker: dashboard / 通知
  * Review


## @otofu-square: postcss-jsx で React x CSS in JS を快適にする

* jubilee works
  * timetree

* postcss-jsxとは
  * postcss の syntax のプラグイン
  * 様々な css in js ライブラリの記法をパース

* 例
  * autoprefixer
    * stylis
      * grid hogehogeに対応してない
  * webpack 上で使う
    * use: ["babel-loadr", "ここ"]

* stylelint の --fix が使える
  * stylelint は内部で PostCSS に依存している
  * 昨年末 --syntax css-in-js が追加

* stylis のサポート外の vendor prefix も対応可能

* css in js でもビルドタイムでスタイルをいろいろいじれるように


## @toshi-toma: React+Storybook ことはじめ

* Atomic Design の本 -> storybook

### storybook

* ui component をアプリケーションとは独立した環境で開発できるツール
* `build-storybook`コマンドでコンポーネントリストの静的サイトを作成できる

* officialが参考になる

* with typescript
  * `./storybook/webpack.config.js`
    * tsx ファイルがかけるようになった
    * ./storybook/config

## @camcam_lemon React.lazyとSuspenseで行うLazy Load

* 日本事務機

* React.lazyとSuspenseって？
  * コンポーネントをdynamic importするAPI: lzay
  * dynamic importが完了するまで表示するやつ

## @dai_shi: React hooksで非同期処理

* Daishi Kato
* reactive-react-redux
  * react hooks + Proxy で redux を使う

* React hooks と非同期処理
  * 主にデータ処理
  * hooks自体は非同期処理を直接的にはサポートしていない
* suspense for data fetching(+ react -cache街)

* hooksならではのデータ取得
  * react-aacheの本質がキャッシュならば、キャッシュがいらない場合のhooksは生き残るのでは?

* ライブラリ2つのかだい
  * useEffectでキャンセルできる
  * debounce, all, raceなどがhooksレベルでできること

* ライブラリを使ってできる具体例
  * Typeahead query
  * テキストフィールドに・・・

* react-hooks-async
  * abortcontrollerを使ってキャンセル

## @remsleep_zzz: React code splitting について(仮)

* React パフォーマンス改善

* 手段の選定
  * code spliting

* 初期レンダリング遅くね？
  * ソースが多すぎ
    * bundleされるjsが多いと
    * 可読性再利用性は下げたくない

* ssr, lazyloadとか

* コードを分割
  * 必要なものだけ最初読み込んであとから違うの読み込む

* ssrしたらコード分割いらないわけではない

* 1.page
* 2.fold(shokihyouji)
* 3.temporal
  * modal, tooltip

* NINARY
  * 動的インポートを行う

* devで半分
* prodでさらに半分

* webpackの設定の調整は重要

* prefetch / preload

* webpack
  * 1.bundle.js
  * chunkの設定変えてあげると効率的なところが望める


## @yassan_: ReactとAutoMLで エンジニアの顔判定してみた

* 株式会社ゲームエイト

* フロントエンドっぽい顔is何
* cloud automl vision
  * こいつが学習するやつ



## @Naoki Kobayashi: React Hooksを安全に使う

* wantedly

* hooksのメモ化

* usecallbackでメモ化

* react-hooks/exhausitive-depth おすすめ(公式でも)
* disabled の場合は必ずコメント: ルール化

* 間接的に変化する場合はあかん
  - stop-runaway-react-effects


## @kashira2339: React Hooks にまつわる不安から心を解き放つ話

* CyberBuzz

* classコンポーネント
  * ライフサイクル複雑

* Higher-order components
  * wrapper hell
  * recompose R.I.P

* Build-in hooks
  * use state
  * use effect

* react-use
