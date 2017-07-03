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

## 会議体
会議名 | 開催目的 | 開催日時 | 参加者 | 場所 | 内容
--- | --- | --- | --- | --- | ---
スプリントMTG（スプリント計画会議） | XXX | 毎週X曜日XX:00〜XX:00(Max) | フリーズ食品開発）山本社長 <br> フロイデ) | apper.in | XXX
デイリースクラム | 情報共有 | 毎日XX:00〜XX:00 | フロイデ開発チーム | フロイデ社内 | 昨日やったこと <br> 今日やること <br> 困っていること

- 客先用勤務表
  - メンバーは毎日記録すること
  - 各月最終営業日までにPLが確認

## 開発環境
環境・ツール | 用途
--- | ---
AWS(ELB) | ロードバランサー ※SSL、ドメイン適用必要
AWS(EIP） | 固定IP
AWS(RDS） | DB(MySQL)
AWS(EC2） | OS(CentOS7)
AWS(CloudWathc) | サーバー監視
Nginx  + Puma | Webサーバー・APサーバー
Ruby 2.X.X | プログラミング言語
Rails 5.X.X | フレームワーク
[Rubocop](https://github.com/froide-kk/rubocop-guide) | コード静的チェック
[ruby-style-guide](https://github.com/fortissimo1997/ruby-style-guide/blob/japanese/README.ja.md) | Rubyコーディング規約
[rails-style-guide](https://github.com/satour/rails-style-guide/blob/master/README-jaJA.md) | Railsコーディング規約
RSpec / Capybara or Turnip | テストコード
bootstap | フロント
CircleCI？ | CIツール
Capistrano | デプロイツール
waffle.io？ | タスク管理ツール
Github | バージョン管理
GoogleDrive？ | ドキュメント共有
Chrome最新版 | 対象ブラウザ  

## ステージング環境
- http://XXX

名前 | メールアドレス | パスワード
--- | --- | ---
システム管理 | XXX | XXX

## 本番環境
- https://xxx
