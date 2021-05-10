# GameWith の開発スタイル

## 技術スタック・ツール

サーバサイド言語として、主に PHP と Go を採用しています。
GameWith は FuelPHP というフレームワークを利用して開発されていますが、適切な粒度でのサービス分割、新規実装部分は Go + Vue.js にて実装するケースも増えています。

モダンな技術を積極的に取り入れたり、Web 標準に従うことで業界をリードできるよう努めています。

- サーバサイド：PHP, Go, (Python, Node.js)
- フロントエンド：TypeScript, ES6, jQuery, Vue.js, Web Components, LESS...
- データベース：MySQL, Aurora, DocumentDB, DynamoDB
- システムモニタリング：New Relic, Firebase Performance Monitoring
- 分析基盤：BigQuery, Google Analytics 4, Google Data Studio
- インフラ
    - AWS（ALB, ECS Fargate, ElastiCache, S3, Lambda, CloudFront...）
    - GCP（Firebase, Cloud Firestore, Cloud Functions, Vision AI...）
    - Akamai（Image and Video Manager, Adaptive Media Delivery...）

[StackShare](https://stackshare.io/gamewith-inc/gamewith) でも使用している技術スタックやツールなども公開しています。

より詳細について興味がある場合はカジュアル面談へお申し込みください。技術的課題や今後の展望などについてもお話できればと思います。

## 開発プロセス

チームにより多少の違いはありますが、基本的には 1 週間を 1 スプリントとしたアジャイル開発が行われています。サービス開発部だけでなく各事業部とも仕様の相談・調整を随時行っています。

チームのタスク管理には ZenHub、ドキュメント管理には Notion を利用しており、フルリモートワーク体制を強みにできるようなツール選定をおこなっています。

| ZenHub のカンバンボード | Notion |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/1130921/115806189-41d0a180-a421-11eb-90cd-8f947d7a813e.png) | ![image](https://user-images.githubusercontent.com/1130921/115806224-501ebd80-a421-11eb-83b0-8b1755d7faf0.png) |

