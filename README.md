## 目的
給食工場の業務をシステム化することで、受注管理・生産管理・工程管理・発注管理・入荷管理・出荷管理・在庫管理・請求管理等の業務を円滑に行う。

## 経緯
7月の工場生産開始に伴い、山崎様からのご紹介で、給食システム開発の実績がある弊社にお声がけ頂いた。

## 概要
給食工場の業務システム開発を行い、2017年10月の段階で初期導入を図る。

## 体制・役割
#### 株式会社パソナテックシステムズ
- PO
山本社長

#### 株式会社パソナテックシステムズ
- PL
高田

- Team
小崎  
山口励

## 会議体
会議名 | 開催目的 | 開催日時 | 参加者 | 場所 | 内容
--- | --- | --- | --- | --- | ---
スプリントMTG <br> （スプリント計画会議） | 情報共有 | 毎週月曜 <br> XX:00〜XX:00(Max) | フリーズ食品開発） <br> 山本社長・山崎様・その他部門関係者<br> フロイデ) <br> 高田・小崎・山口励 | apper.in | 次回スプリントで行うプロダクトバックログの決定
デイリースクラム | 情報共有 | 毎日09:30〜09:45 | フロイデ開発チーム | フロイデ社内 | 昨日やったこと <br> 今日やること <br> 困っていること

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

## その他
- お客様との会議では議事録作成し、会議後速やかに関係者と共有すること  
メール？ドキュメント共有のみ？
- 客先用勤務表
  - メンバーは毎日記録すること  
  - 各月最終営業日までにPLが確認し、翌月第1営業日AMまでに管理課へ提出すること

