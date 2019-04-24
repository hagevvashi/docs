# Rakute Commerce QA Night#1

# Introduction to Rakuten Commerce QA Night

* 今後も続ける予定だから#1
* 日本人だけではないよ

# Automation Testing for Leisure Service by @emurins

* ニックネームで呼ぶ文化
* レジャープロダクトデパートメント
* role 毎にチームが構成されている
* scope: 5 services
* members: 10  * off site
* skill: not only programmer

## Topics
* engineer時代のテスト自動化失敗談
* QA時代にどう導入したか

* e2e
* for begginer

* not contain how

## engineer 時代の話

* 目指せカバレッジ○○%
  * as metrics
  * 各チームそれを目指した

* 流行りの技術でとにかく動かそう
  * できるエンジニアがいた

* これでよい？
* カバレッジ○○%について
  * UI操作をもとにとにかく自動化

* とにかく自動化するところが目的になっていた
* step に関して自動化した
* 品質ではない

* 品質を担保させるものではなかった
* 高価な自動化コード

* 流行りの技術でとにかく動かそう

* できるエンジニア手動で技術選定(ruby)
* 動くことが最優先

* 保守困難
* 活かされていない

* 目的のないテスト
* 活用されない

* 結果お蔵入りに

## QAになってどうやって導入した？

* テスト自動化設計でスコープ、目的を明確化
* テスト自動化の保守・運用設計

* テスト自動化の工程のなかで、計画と設計を重視

* 上流をちゃんとしないと下流がこける

* 保守や運用どうやって？
  * 保守
    * ツール
    * コード
    * 実行環境
  * チームにあったツールを選定

* 自動化に求められること
  * 毎日
  * 早期発見
  * 即改修確認

    * 最小限のジョブ
    * 何回実行しても動く
    * 結果分析が容易


* 自動化は基本毎日どこかしらでこける

## まとめ

* テスト自動化設計でスコープ、目的を明確化
  * 自動化できるところを正しく品質担保

* 自動化の保守・運用設計
  * 長期間の運用に耐えうる

## Q&A

* デバイスが必要な自動化の場合
  * アピュームとかが必要になる

* 開発との関わり方
  * qa
  * manager
    * pdmも兼ねている
  * development


# Test Automation at Rakuten Travel by Cayetano Clint and Chiang ChiLun (English)

## Intro

* Clint

## Rakuten Travel

## Team

## testware overview

## ui test automation

* java
* testng
* selenium

* ui test
* development (push) : test

* testcase generator
* defines the senario

## api

* apache http (diffrerence)
* all testcase independent
* scratch で作った

## conclusion



# Rakuten QA group and Automation team/ Mayur Gondhalekar (English)

* horizontal

# Rakuten QA Group Introduction & Best Practices/ Yusuke Nakamura

## about

* 2010新卒~5年developer
* 2016~ test engineer

## 品質保証グループ

* 様々なサービスがある
* 品質に対する窓口

* 可視化
* 文書化
* コミュニケーション

## 可視化

* バグステータス
* プロジェクトステータス
* 日時タスク

* Jira看板ボード
* リアルなボード
  * 遅れているのかどうかが分かるのが大事
* Jiraを使ってばぐかんりしている
* 修正数/起票数とか可視化
* 生産性をプロットすることで、過去プロジェクトとの比較、次回のプロジェクトの工数見積に活かす

## 文書化

* 情報整理
  * インデックス
  * ラベリング
* 情報管理
  * アップデート

## コミュニケーション

* 品質向上には関わりや関係性が大事

* やらかしたとき
* マネージャが、QAしっかりテストしたの！？となる
* しっかりとは？
* テストとは「バグのあることを証明する活動」
* テストは「バグのないことは証明できない」
* 限られた時間を増やすことしかできない
  * 早期テスト
* 開発とQAをどう結びつけるか
* テストとは手を抜こうと思えば手を抜ける

## 英語について

* MTGは英語
* 外国籍のメンバーが増えた
