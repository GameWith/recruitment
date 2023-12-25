# GameWith エンジニア採用ページ
ご覧いただきありがとうございます。  
このページではGameWithのエンジニア採用にあたり、技術スタックや開発プロセス、社内カルチャーなどを紹介しています。  
GameWithの[採用情報ページ](https://recruit.gamewith.co.jp/)も合わせてご覧ください

詳しく話を聞きたいという方は、是非[Wantedly ページ](https://www.wantedly.com/projects/606408)からカジュアル面談にお申し込みください。  
[GameWith エンジニアの採用面接ガイド](https://github.com/GameWith/recruitment/blob/master/interview_guide_engineer.md)も一読いただけると幸いです。

# GameWithの開発スタイルのご紹介
## 技術スタック・ツール
サーバサイド言語としては、主に PHP と Go を採用しています。  
GameWithは FuelPHP というフレームワークを利用して開発されていますが、適切な粒度でのサービス分割、新規実装部分は Go+Vue.js にて実装するケースも増えています。  
最近ではスマホアプリや一部の Web に Flutter を取り入れています。

## 提供サービス紹介

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

#### GameWith 日本語版スクリーンショット
PC(Web)

<a href="images/gamewithjp1.png">
  <img src="images/gamewithjp1.png" style="width:30%; display:block;" />  
</a>

SP(Web)

<a href="images/gamewithjp2.png">
  <img src="images/gamewithjp2.png" style="width:30%; display:block;" />
</a>


#### GameWith英語版スクリーンショット
<a href="images/gamewithen.png">
  <img src="images/gamewithen.png" style="width:30%; display:block;" />
</a>

#### iOSアプリ

https://apps.apple.com/jp/app/gamewith-%E3%82%B2%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A3%E3%82%BA/id1296719342

#### Androidアプリ

https://play.google.com/store/apps/details?id=jp.gamewith.gamewith

### AIM練習ソフト
- クライアントサイド: Unity (C#)
- サーバサイド：Go
- データベース：Aurora MySQL
- インフラ: 
  - AWS（ALB, ECS Fargate, S3, Lambda, CloudFront...）
  - GS2（GameServiceService）主にユーザー管理系に利用

#### AIM練習ソフト概要
<a href="images/aim1.png">
    <img src="images/aim1.png" style="width:30%; display:block;" />
</a>

#### AIM練習ソフスクリーンショット(開発中)
<a href="images/aim2.png">
    <img src="images/aim2.png" style="width:30%; display:block;"/>
</a>
<a href="images/aim3.png">
    <img src="images/aim3.png" style="width:30%; display:block;"/>
</a>



## GameWithを構成する周辺システムについて
GameWithはさまざまなマイクロサービスや独自ライブラリなどで構成されています。  
より良いサービスをユーザーに提供するためにシステムも日々進化していますが数が多いので一部を抜粋してご紹介します。

### GameWithDesignSystem
<a href="images/aboutgds.png">
  <img src="images/aboutgds.png" style="width:30%; display:block;" />
</a>

[GameWith Developer Blog 「GameWithのリプレイスについて vol.2 〜Web Components を Vue で書いたら最高だった編〜」](https://tech.gamewith.co.jp/entry/2020/04/21/185819)より。

### 記事下コメントシステム
GameWithの各種記事に書き込みできるコメントを管理するシステムです。

バックエンドは Go、フロントエンドは GameWithDesignSystem（Vue.js/TypeScript）を利用しています。  
会員登録せずとも書き込みができる仕様になっているため、トラフィックの多いGameWithでもユーザーが快適に利用できるようにフロントエンドでの非同期描画や CDN の利用などの工夫をしています。

### GO最新攻略 & レイド招待・個体値チェッカー
<a href="images/pokegoapp.png">
  <img src="images/pokegoapp.png" style="width:30%; display:block;" />
</a>

[GameWith Developer Blog 「社内でFlutterを採用しアプリと管理画面を開発した話」](https://tech.gamewith.co.jp/entry/2022/11/04/150724)より。

# GameWithエンジニアの働き方

## フルリモートワークと裁量労働制
GameWithではフルリモートワークと裁量労働制を導入しています。  
もちろん配属チームでの調整は必要ですが、柔軟な調整ができます。  
保育園送り迎えのため 9 時〜 18 時勤務にしたり、朝が苦手で 12 時〜 21 時勤務など、さまざまなエンジニアが在籍しています。  
通院のために開始時間を遅くしたり昼休憩を長くして、その分夜に長めに仕事をするという方もいます。

## 組織体制
サービス開発部では約 25 名のメンバーが在籍しています。  
事業に沿ったチームと、それを横断的にサポートするチームが存在します。  
定期的に情報共有会を開催したり、一部のメンバーは複数のチームを兼務していたりとチーム間連携も活発に行われています。  
ロールとしてはリーダー/ディレクター/エンジニアというメンバーでチームが構成されています。  

開発チームの年齢は 26 歳〜 42 歳のレンジで構成されており、ボリュームゾーンは 30 代前半です。  
攻略記事ライター出身やディレクター経験のあるエンジニアも在籍しており、さまざまな経歴を持つエンジニアが存在するのも特徴です。  
育児中のエンジニアリーダーやマネージャー、女性エンジニア、外国籍エンジニアなども活躍しています。  

# 開発プロセス 

## プロジェクトの進み方

チームごとにワークフローを決めて動いているため細かな違いがありますが、以下の部分は共通しています。
- 1週間を1スプリントとしたアジャイル開発
- 1日1回ビデオ通話による朝会（デイリースクラムのようなもの）を実施

また、チームや仕事内容によって度合いは変わりますが各事業部とも仕様の相談・調整を随時行っています。開発部が主体的にビジネス視点での改善や施策を提案しコミットすることを強く推奨しており、ビジネス側もそれを受け入れる風土があります。

## 各種管理
コミュニケーションツールとして slack、 チームのタスク管理には ZenHub、ドキュメント管理には Notion を利用しており、**フルリモートワーク体制でも滞りなく業務が遂行できる**ツールを積極的に導入しています。

<a href="images/zenhub.png">
  <img src="images/zenhub.png" style="width:30%; display:block;" />
</a>

ZenHubのカンバンボード
## 日常的にリリースを行う
現在の月間リリース数は80前後。平均すると1日に4〜5回リリースが行われている計算になります。  
GameWithではユーザに価値を素早く届けることを重視しており、ビッグバンリリースよりも小さなリリースを日常的に行うのが良しとされています。

# エンジニアから見たGameWithの面白さ
## ハイトラフィックなサービスの開発運用
月間5億PV、4500万UUが利用するサービスのため、自らリリースした施策への反応がすぐに返ってきます。  
秒間リクエスト数まで意識をして設計や実装する必要があるため、エンジニアとしてのスキルが磨かれます。

## いちゲームユーザーとしての視点が活かせる
2020年〜の巣ごもり需要により、ゲーム業界全体の市場規模が大きく伸長しています。  
その中で攻略メディアビジネスも競争が激化しており、差別化やメディアとしてさらなる品質向上が重要になってきています。

そのため、いかに素早くユーザのニーズに応えられるようなサービスを提供し続けることができるかが今後の成長の鍵となります。  
技術力だけでなく業界のトレンドやいま流行しているゲームについてのキャッチアップも同時に求められ、とても刺激的な環境です。

## あらゆるステークホルダを支える屋台骨
GameWithを開発するエンジニアにとって、少なくとも3つのステークホルダが存在すると考えています。  
まず１つにゲームを楽しむエンドユーザーです。品質の高い情報をいち早くユーザーに届け、ユーザーのゲームプレイをより快適にすることが求められます。

次にゲームを売り出すパブリッシャーやデベロッパーです。発売されたゲームをより楽しんでもらうこと、ゲームの魅力をより多くのユーザーに届けることでさらなるゲーム業界の発展に寄与していきます。

最後にGameWithでゲームの記事を書くライターです。ダッシュボードを常に改善し続けることで彼らがより効率的に良い記事をリリースし続けることを目ざいます。

このような多様なステークホルダが満足するようにエンジニアリングの観点から最善を尽くしています。

## GameWith開発部が目指す組織の姿
### ボトムアップでのシステム改善・施策提案の実施
コンテンツだけではなくサービスとして、より良い価値提供をユーザに行えるような組織体制を目指しています。  
解像度高くサービスのことを理解しているエンジニアだからこそできる施策やシステム改善などを積極的に実現できるよう仕組みやカルチャーをつくっています。

<a href="images/buttomup.png">
  <img src="images/buttomup.png" style="width:30%; display:block;" />
</a>

### 提案ボード
数値分析によるファクトベースでの施策立案。  
施策立案をする際には、どのKPIに対して影響があるかを考えます。実際にリリースしたあとに結果はどうだったかを振り返る場をつくるようにしています。  
数値分析グループでは週次での定期レポーティング会を行っており、エンジニアもサービス全体の数値把握をおこなう機会があります。

<a  href="images/analytics.png">
  <img src="images/analytics.png" style="width:30%; display:block;" />
</a>

### 開発効率の改善
2013年にGameWithがリリースされ、以来多くの機能開発を行ってきました。コードベースや組織の拡大に伴うスピード低下を避けるために課題をひとつずつクリアし、あらゆる面から効率向上のための取り組みをおこなっています。
- 機動的なペアプロ、モブワークの実践
- 設計・コード・セキュリティレビューの実施
- E2Eテスト自動化によるテスト工数圧縮
- 不要コードの削減

# カルチャー
## 業務アピール会・社内LT会
毎月おこなわれるサービス開発部の全体会のコンテンツのひとつとして、業務に対する個人のこだわりポイントを話してもらう業務アピール会というものを実施しています。  
また、毎週金曜日の業務時間終了後に任意参加の社内LT会が開催されています。ここでは、最近気になった技術やトピックなどを自由に発表しています。  

<a href="images/appeal.png">
  <img src="images/appeal.png" style="width:30%; display:block;" />
</a>

## 互いに感謝・称賛するカルチャー
Slack上で ピアボーナスのシステムである[HeyTaco](https://heytaco.com/)を採用しています。  
これはタコスの絵文字で感謝を手軽に表現することでインセンティブを付与できるシステムです。  
タコスを集めるとガチャを引くことができ、当たりが出ると iTunesカード もしくは GooglePlayカード をもらうことができます。

<a href="images/tacos.png">
  <img src="images/tacos.png" style="width:30%; display:block;" />
</a>

## 積極的なスキルアップ支援
エンジニアのスキルアップの支援として以下の手当や取り組みを行っています

### 技術勉強手当
業務時間外に月10時間以上の取り組みをした場合に支給されます。  
基本的にはアウトプットが残る形を推奨しています。
- コードがあるものは GitHub のリポジトリ公開
- 読書をしたものは内容のサマリをブログで公開
- etc…

<a href="images/study.png">
  <img src="images/study.png" style="width:30%; display:block;" /> 
</a>

### OSSコントリビュータ / コミッタ手当
GitHub の場合、スター数が一定以上の OSS に対して Issue の起票や PullRequest のマージを一定以上行うことによって支給されます。  
ハードルが高い分、半年程度継続して手当が支給されます。

<a href="images/contributer.png">
  <img src="images/contributer.png" style="width:30%; display:block;" />
</a>

### テックブログの執筆
社内でテックブログ推進委員がおり、ブログ作成に不安がある人も安心して書くことができます。  
ブログを記載することはエンジニアのスキル向上に役に立つと捉えており、業務時間を使ってブログ執筆も可能です。

<a href="images/blog.png">
  <img src="images/blog.png" style="width:30%; display:block;" />
</a>

# appendix
- [GameWith エンジニアの採用面接ガイド](https://github.com/GameWith/recruitment/blob/master/interview_guide_engineer.md)
- [GameWith エンジニアやサービス開発にまつわる記事](https://github.com/GameWith/recruitment/blob/master/articles.md)
- [X - GameWith_Dev](https://twitter.com/gamewith_dev)

