# NuxtMeetUp#8

# スポンサーLT Gaiax様

# Next vs Nuxt ~TypeScript + Serverless...~ @Roadagain

* meguro.es などでよく見かける方
* モバイルファクトリー
* NuxtがデファクトだがNextを使いたい
* 比較検証した
* 結局Next諦めた
* 検証実験
* ts, firebase cloud function, pwa
* cloud function: next
* pwa: nuxt
* create-n(e|u)xt-app
  * create-next-app
    * sample(ボイラープレート)選択可
    * 毛色バラバラ
  * create-nuxt-app
    * pwa
* 導入
  * Next
    * with-firebase-hosting-and-typescript
  * Nuxt
    * nuxt-ts(当時)
    * @nuxt/typescript(今)
* SSR on Cloud Functions for Firebase
* PWA
  * next
    * root/static に manifest 生成
    * よって out


# GatewayパターンとSchema駆動開発 @andoshin11


# axios-moduleをやめてaxiosを使う @nakajmg

* Client-side gateway

# 新しく参画したプロジェクトでNuxtに置き換えようとして・・・@YoheiFujii

* オクト
* 筋肉
* Angular v1 から脱却したい
* nuxt 置き換え
* テックブログ参考に

# LT5 Yoshinori Ishii

* 株式会社アズーム
* Nuxtを採用した経緯
* 採用効果有り
* Vuex の Actions と Mutaitions を Pages からどちらも呼び出してOKか
  * Pagesから呼び出すのはActionsのみ
  * vuex-pathifyでmutationsの自動生成
* VueのUIライブラリってデザインと構造の分離ができていない気がするけど、気にならない？
  * custom elements + sass mixin + rscss
  * RSCSSとは https://rscss.io/


# LT6 masaakikunsan

* Frontでもテスト書くべきでね？
* SCOUTER
* フロントでもテストを書く理由
  * js の複雑化 -> しんどさ
  * プロダクトによってテストケースが膨大: 手動テストがきつい
  * コードがきれいになる
* テスト書かないときに起きる事故
  * AのロジックいじったらBが死んだ
  * テスト漏れがあって死んでいた
  * なんで動いているかわからないコードを触って死んだ
* 自分を守るためにテストを書く
* フロントでのテスト
  * とりまjestでテスト
  * e2e
