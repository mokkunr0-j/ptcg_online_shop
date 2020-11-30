# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


# ポケカオンラインショップまとめ

## 概要

### ポケモンカードを取り扱っているオンラインショップのまとめサイト。定期的に情報を更新し、その時の最安値を表示する。

## コンセプト

### 最安値を見やすく表示。検索をしやすく、閲覧も見やすく。

## バージョン

### Ruby 2.7.1 Rails 6.0.3

## 機能一覧

- カード一覧機能
  - カード名、レアリティ、最安値、その店舗
  - 人気(閲覧順)で表示(kaminariでページ分けしてx枚ずつ表示)
  - ログインしてたらお気に入り登録可能に
  - 検索機能
    - カード名、収録パック、カードの種類、レアリティ、タイプ、テキスト
- 店舗一覧
  - 店舗名、URL
- カードの詳細情報ページ
  - カード名、券面、収録パック、カードの種類、レアリティ、タイプ、テキスト
  - その時の最安値とそのショップ名
  - それぞれの情報から飛べるところはリンクを貼り付け
- ユーザー登録機能
  - メールアドレス、名前、パスワードは必須
  - お気に入り登録したカード一覧、お気に入りの削除
  - お問い合わせ機能(管理者からの返信はメールから)
- 管理者ページ
  - 店舗情報編集機能
  - カード情報編集機能
  - お問い合わせ返信機能(メールで返信されるようにする)
  - 管理者のみが閲覧できるようにする

## スプレッドシート

### https://docs.google.com/spreadsheets/d/1tnOwEU7pFsHQX6BmVRZzbkAW8detaRc3dWY-EJsimjQ/edit#gid=547197584

## 画面遷移図、画面ワイヤーフレーム

### https://cacoo.com/diagrams/R2HyVS2MvCg4pyex/AB4CF?useTemplate=true&reload_rt=1606726496517_0

## 使用予定Gem

- slim
- slim-rails
- devise
- kaminari
- kaminari-bootstrap
- carrierwave
- mini_magick
- bcrypt
- faker
