# React.js meetup #8

## sponserLT

https://developer.kaizenplatform.com/entry/2019/03/26/120000

## kon_shouさん Gatsby紹介&Gatsbyのビルドをザックリ理解


## @as_masaさん TBD

### Application特性

* 全部載せ系(twitter, facebook)
* ページ遷移系(管理画面, ECサイト)

#### 全部のせ

* Application起動から終了まで
  * すべての状態は終了するまで亡くならない
* タイムライン系: 差分を追加する傾向

* デメリット
  * メモリ使いすぎ

#### ページ遷移系

* 2つのライフサイクル
  * 全部のせの同じ: Application起動から終了まで
    * ログイン状態とか、マスターデータの保持-> アプリケーション状態と定義
  * ページ表示から別ページに遷移するまでのライフサイクル
    * ページ状態と定義
    * ページに必要な状態を持つ

* メリット
  * 型としてライフサイクルを定義可能


* デメリット
  * 遷移タイミングで遅くなる

## @sonatardさん 「React Hooks - カスタムフックとカプセル化」

## fff_komatsuさん TBD

* カオナビの人

## @natural_clarさん 「connectが要らないreact-redux」

https://react-redux-new-api.naturalclar.now.sh/
