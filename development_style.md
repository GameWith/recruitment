# GameWith の開発スタイル


## 技術スタック・ツール

サーバサイド言語として、**主にPHPとGoを採用**しています。
GameWith は FuelPHP というフレームワークを利用して開発されていますが、適切な粒度でのサービス分割、**新規実装部分はGo+Vue.jsにて実装するケースも増えています**。

最近ではスマホアプリや一部のwebにflutter を取り入れています。

### GameWith

- サーバサイド：PHP, Go, (Python, Node.js)
- フロントエンド：TypeScript, ES6, jQuery, Vue.js, Web Components, LESS...
- クライアントサイド: Swift, Kotlin, Flutter (Dart), Unity (C#)
- データベース：MySQL, Aurora, DocumentDB, DynamoDB
- システムモニタリング：New Relic, Firebase Performance Monitoring
- 分析基盤：BigQuery, Google Analytics 4, Google Data Studio
- テスト：Autify
- インフラ
    - AWS（ALB, ECS Fargate, ElastiCache, S3, Lambda, CloudFront...）
    - GCP（Firebase, Cloud Firestore, Cloud Functions, Vision AI...）
    - Akamai（Image and Video Manager, Adaptive Media Delivery...）
    - Terraform

### AIM練習ソフト

- クライアントサイド: Unity (C#)
- サーバサイド：Go
- データベース：Aurora MySQL
- インフラ:
    - AWS（ALB, ECS Fargate, S3, Lambda, CloudFront...）
    - GS2（GameServiceService）主にユーザー管理系に利用

[StackShare](https://stackshare.io/gamewith-inc/gamewith) でも使用している技術スタックやツールなども公開しています。

より詳細に興味がある場合は是非カジュアル面談へお申し込みください。技術的課題や今後の展望などについてもお話できればと思います。

## 開発プロセス

### プロジェクトの進み方

チームごとにワークフローを決めて動いているため細かな違いがありますが、以下の部分は共通しています。

- 1週間を1スプリントとしたアジャイル開発
- 1日1回ビデオ通話による朝会（デイリースクラムのようなもの）を実施

また、チームや仕事内容によって度合いは変わりますが各事業部とも仕様の相談・調整を随時行っています。開発部が主体的にビジネス視点での改善や施策を提案しコミットすることを強く推奨しており、ビジネス側もそれを受け入れる風土があります。

### 各種管理

コミュニケーションツールとして slack、 チームのタスク管理にはZenHub、ドキュメント管理にはNotionを利用しており、**フルリモートワーク体制でも**滞りなく業務が遂行できるツールを積極的に導入しています。

| ZenHub のカンバンボード | Notion |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/1130921/115806189-41d0a180-a421-11eb-90cd-8f947d7a813e.png) | ![image](https://user-images.githubusercontent.com/1130921/115806224-501ebd80-a421-11eb-83b0-8b1755d7faf0.png) |

## 日常的にリリースを行う

現在の月間リリース数は80前後。**平均すると1日に4〜5回リリースが行われている**計算になります。

GameWithではユーザに価値を素早く届けることを重視しており、ビッグバンリリースよりも小さなリリースを日常的に行うのが良しとされています。