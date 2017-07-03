## 目的


## 経緯


## 概要


## 体制・役割
#### フリーズ食品開発株式会社
- PO
山本社長

#### フロイデ株式会社
- PL
高田

- Team
小崎  
山口励


## 進め方
#### スプリントMTG（スプリント計画会議）
- 開催日時  
毎週X曜日XX:00〜XX:00(Max)  

- ツール
apper.in

- 開催目的
  - xxx

- スプリント期間  
1w

- 参加者  
  - フリーズ食品開発）
  - フロイデ）

#### コミュニケーションツール
- apper.in  
スプリントMTG実施

- Slack  
開発チーム間の報連相

#### デイリースクラム
- 開催日時  
毎週X曜日XX:00〜XX:00(Max)  

- 内容
```
## 昨日やったこと  
- xx
## 今日やること  
- xx
## 困ってること
- xx
```

- 客先用勤務表
  - メンバーは毎日記録すること
  - 各月最終営業日までにPLが確認

## 開発環境
名前 | 用途
--- | ---
AWS(ELB) | ロードバランサー ※SSL、ドメイン適用必要
AWS(EIP） | 固定IP
AWS(RDS） | DB(MySQL)
AWS(EC2） | OS(CentOS7)
AWS(CloudWathc) | サーバー監視
Nginx  + Puma | Webサーバー・APサーバー

- プログラミング言語、フレームワーク
  - Ruby 2.X.X
  - Rails 5.X.X
  - [Rubocop](https://github.com/froide-kk/rubocop-guide)

- コーディング規約
  - [ruby-style-guide](https://github.com/fortissimo1997/ruby-style-guide/blob/japanese/README.ja.md)
  - [rails-style-guide](https://github.com/satour/rails-style-guide/blob/master/README-jaJA.md)

- テストコード
  - RSpec / Capybara or Turnip

- フロント
  - bootstrap

- CI
  - CircleCI？  

- デプロイツール
  - Capistrano

- プロジェクト管理ツール
  - waffle.io？

- 対象ブラウザ  
  - Chrome最新版

- その他
  - バージョン管理  
Github
  - ドキュメント共有  
  GoogleDrive？

## ステージング環境
- http://XXX

名前 | メールアドレス | パスワード
--- | --- | ---
システム管理 | XXX | XXX

## 本番環境
- https://xxx
