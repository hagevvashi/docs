# bonfirefrontend * frontrend

* frontrend: cyber
* bonfire: yahoo
  * 普段はyahooのロッジで
  * 5/18 インサイドフロントエンド cyber * yahoo
* theme
  * 若手
  * 新しい挑戦と学び

# 新卒3年目、ヤフーで学んだ2年間を振り返る@ydamaha

* @濱田唯

## toipcs

* チーム開発の心構え
* 設計・構成への意識
* 新しい技術に対する意欲

## チーム開発

* レビューは大事
* プロジェクトの雰囲気もつくる気がする

## 設計・構成への意識

* not 動けばいい
* typescript
* redux
* atomic design
* ルールが言語化されていること
* メンバーが合意していること

## 新しい技術に対する意識

* 議論に参加するために自らも取り入れる側に
* 自由に技術選定可能
* 導入コスト・メリットの議論


# AbemaTV 新卒1年目エンジニア実録@nodaguti

* @野口 直寛

## 1年目エンジニア実録

* 研修でslackを作る
* coverage 99%達成
* reactを使っているがreduxを使っていない
* rxjsでの独自実装

### abemaTVの視聴形態

* tv
* 見逃し視聴
* video

### video をモバイルブラウザから見れるように

* 不確定要素に対する対応（課題）

### 見逃し視聴

* 数字を上げていく課題

### chrome dev summit 参加@sanfransisco

* 前回frontrendで話した

### 12月

* 負債返済
* prettier導入とか

### 1月〜

* 仕様が曖昧なやつ
* apiとのすり合わせ

## 2年目に向けて

* 「学生エンジニア」から「事業プロダクトを作るプロのエンジニア」として成長することができた
* 機能開発を2つの視点から捉えられるようになった
  * どう ux に影響するか
  * どう kpi に影響するか

### これからどうしたい

* キャリアパス: テックリード
* リーダーシップ
  * 「チームで作る」ということに対する経験
* 専門性
  * High performance website
* 「技術から事業に貢献できるエンジニア」


# Webフロントエンド&デザインで学んだ2年間を総括@@innovate_7110

* 内藤秀彦

## デザインによるサービスの改善

* サービスの解決したい課題を探す
* どう改善するかプレゼン
* OK -> ABテスト

### 抽象的なキーワードで商品を絞り込みにくい

* cvr を ui の abテスト・改善で伸ばす

#### 問題？

* いろいろな要素をあわせて一つの解決策としてしまったせいで、何が要因で良かったのかわからない

## UI パーツのコーディングのお作法

## 勝ち筋

### cvr why

取扱高 = 注文数 * 平均注文単価
注文数 = ////

### 絞り込み

* 関連語
* リッチ検索窓

### 行き止まりをなくす

* オートページャー
* サンドイッチ

## テストの実装

* 小規模ならcss

## legacyの置き換え

* php ssr * jQuery

## データビジュ荒いぜねーション

* d3.js

## ビッグデータの可視化

* ビッグデータで新社会人の悩みを知る

# こえのブログでのPWA 〜開発現場編〜@herablog

* @原 一成
* 新卒12年目

* しゃべるだけでブログになる
* webアプリ

## なぜ、今音声？
* 2016年、30代の90%がスマホ所持
* 2012 -> 2017 でデータ通信量が倍に

## なぜ、web？

* クロスプラットフォーム
* 小さくリリース
* webも発展した

* ネイティブアプリのように
* csrで高速なアプリ
* 初回表示時の速さも担保する

* time to interactive が遅くなる
* first meaningfulpaint も遅くなる

* 早くjsを呼ぶ
* 初期表示のためのjsのサイズを小さくする

* PRPL Pattern (push, render, pre-cache, lazy load)
* entrypoint(html)
* app shell
* http/2 server push
* pre-cache (service-worker like native app)

* cdn活用

* client -> cdn edge almost 100% | -> origin server -> db

* event-driven cahe purging
* when deploy / db modify

* web-component 試用
* 捨てやすさ

* extend && shadow dom

* 166KB(gzip style 込)
* light house で高得点

* webでaudio recording

* navigator.mediaDevice
* navigator.permission.query -> grant

* 音声を圧縮
  * web assembly を用いて
    * wav -> mp3

* 詳細は・・・ブログ

* 開発フロー

* 餅つき開発

* 早い共通化より捨てやすい

* 餅つき結果->commit数1000を超える

* 最速でプロトタイプ

* 実装難易度が早めにわかったり
* firebaseフル活用

* すぐにhtml+purejs mock
  * -> 2.5ヶ月後component

* アクセシビリティ
  * outlineスタイルを決める->デザイナさん相談

* 詳細はスライド

* デプロイ心理的安全性

* 簡単にデプロイできることは、プロダクト改善に役立つ
* 932デプロイ

* Perf Budget
* パフォーマンスバジェット
* 財政予算に見立てる
* Budgetの種類
* Timing___

* 計測するページを決め、計測する
* 競合を定義
* 現状維持

* FCP:1.8s -> 1.5s
* 参考はスライド

* OSSのように開発する
* 数カ月後の自分は他人・・・
* いつでも開発者が参加できる
