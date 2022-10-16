# 業務経歴書

## 基本情報

|key|value|
|----|----|
|名前|楠原 彰悟|
|現住所|大阪府 大阪市|
|Zenn|[@mikana0918](https://zenn.dev/mikana0918)
|ブログ|[Tinglehacker](https://raku-noma.site/) (月間PV5万越を達成)
|英語力|TOEIC960点(大学3年時)|

## 概要

- モダンなフロントエンド（主にVue.js/Nuxt.js）における基盤コード開発からE2Eテスト基盤、storybook基盤構築、コンポーネント設計、CI/CD基盤開発などフロントエンド技術と自動化技術に強みがあります。
- バックエンドにおいても、動的・静的型付けの主要な言語(PHP,Python,Kotlin)と各種フレームワーク、DB（MySQL, PostgreSQL）の経験があり、フルスタックからフロントエンド専業まで柔軟な対応ができます。
- 各種GoF系のデザインパターン（Builder, Strategy, Composition, Decorator, Facade, Adapter etc）の扱いにある程度習熟しており、アプリケーションアーキテクチャ設計にも経験があります。
- ドメイン駆動開発における戦術的パターンに関して、最低限、実務を行う程度の理解があります。（業務経験あり）
- AWSのマネージドサービスにおける知見もあり、AWS CDKを使ったIaCおよびCI/CD基盤の構築、各種API連携などサーバーレス基盤の知見・業務経験もあります。

- スタートアップ〜小規模web自社開発チームなど、限られた人数の中で広範な領域を担当する必要がある段階で価値を発揮しやすいエンジニアです。

- SEO対策に対する知見（個人ブログにおいて月間5万PV以上達成）webマーケティング・グロース施策の知見もあり、webディレクターとしての実務経験もあるため、開発を飛び出した領域からwebサービスをバックアップできるのが強みです。

## スキル

- 基本的にすべて実業務で使用した技術だけを列挙しています。

### 言語

 PHP | JavaScript | TypeScript | golang | bash |  Kotlin | Python | 

### フレームワーク等(ver.)

 Laravel |  FastAPI | Spring Boot | CakePHP(3) | Nuxt.js | Vue.js(~2.7) | React.js(17.x) | WordPress |

### RDB/NoSQL

MySQL | PostgreSQL | CloudFirestore | MongoDB 

### クラウド

#### AWS

Amplify | VPC | S3 | Cloud Front | Lambda | ECS | Fargate | ECR |  IAM | RDS(MySQL|PostgreSQL) | Aurora | SNS | SES | CloudFormation | CloudWatch | CloudTrail | SecretsManager | CodeDeploy | CodePipeline | CodeBuild | EventBridge | SSM | 


#### GCP 

Cloud Functions | Cloud Firestore | Firebase Hosting

### SaaS/PaaS

GitHub | GitHub Actions | CircleCI | DataDog | Sentry | Shopify

### その他

AWS CDK | Github Actions | Terraform | Docker | nginx | unicorn | Apache | Gulp | Webpack | SASS | Vuetify | ElementUI | Puppeteer | Playwright 

## バリューを発揮しやすい業務
- フロントエンド設計
- BFF構成におけるフルスタック開発
- パッケージマネージャの導入
- LinterやFormatterの導入
- 単体テストや統合テストの導入
- アプリケーション設計
- gitブランチモデルの適切な定義
- サーバーレス基盤構築
- CI/CDパイプラインの構築
- e2eテスト基盤構築
- インフラのコード化
- デプロイの自動化

## 主な業務経歴

### MA系PaaSの開発 (2022年2月~)

【プロジェクト概要】営業支援およびMA系ツールdigimaの開発

【担当業務】 フロントエンド開発、バックエンド開発
- React.js + TypeScriptによるフロントエンド開発
- golangマイクロサービス + Laravel proxy APIバックエンド開発
- SMS送信機能のフルリプレイス
- バックエンドマイクロサービスへの機能追加・移行・テストコード作成
- Elasticsearchを使った全文検索マイクロサービスの新規開発
- メールサーバーからSMTP/IMAPプロトコルを利用してメール送信受信を行うマイクロサービスの新規開発
- Uipathを使った不動産情報クローラマイクロサービスの開発

【発揮したバリュー】英語が使えることを活かし、英語ベースでの業務を行なっているチームへ参画し、新規機能のフロントエンドとバックエンド
の開発を行いました。フロントエンドが自分が一番詳しい場合が多かったので、フォーカスはフロントエンドですが、工数が足りない場合は
積極的にバックエンドの開発も行っていました。golang + Reactの組み合わせはいずれも初めてでしたが、1ヶ月程度でキャッチアップをしました。
途中からフロントエンドの設計やライブラリ選定、レガシーコード改善などフロントエンドの旗振り役をしつつ、バックエンドの工数が重たかったので、
バックエンドをメインで開発していました。


### AI系データ分析プラットフォームの開発 (2021年5月~2月, 以後副業)

【プロジェクト概要】手軽にAIを作ってシュミレーションを行うAI系プロダクトdatagustoの開発

【担当業務】フロントエンド設計（コンポーネント、アプリケーション）、フロントエンド開発（Vue.js/TypeScript/Amplify/Storybook/Playwright)、オフショア管理（ベトナム）、バックエンドAPIの開発(Python/FastAPI)/AWS CDKによるインフラのコード化（IAMユーザ作成のPR・コード化）

- Vue.js + TypeScript + Vuetifyによるフロントエンド開発
- パッケージマネジャ、エディタ設定、Linter/Formatter,Makefileによる開発環境の平準化
- CompositionAPI(for vue2)や関数型コンポーネントなどの技術調査・実践
- Sentryの導入
- 開発ドキュメント整備
- Python + FastAPIによるバックエンドAPI開発
- Playwrightの導入および基盤e2eコード・パイプライン整備
- Vuetifyによる基盤コンポーネントの整備
- IAMユーザー作成の自動化をAWSCDKによるIaCで実現
- 英語力を使ったオフショア開発のバックアップ
- コンポーネントに対する権限認可モジュールの作成
- PrivateCloud版リリースのためのクロスアカウントCI/CDパイプラインの構築（AWS・github）
- slack連携
- Vue3へのアップデートの調査~実施

【発揮したバリュー】設計・開発をスケールのできる基盤にしてほしいとのことで、当初ご相談いただきました。フロントエンドのコンポーネント設計から、StoryBook構築、E2Eテストの導入を行いました。オフショア開発のマネジメント業務も発生したため、英語を使った対応を行いました。Python・FastAPIについては、業務では初めての経験でしたが、キャッチアップ。AWS CDKについてもインフラのコード化については座学程度の知識がなかったものの、ここでも休日を学習に当てるなどしてキャッチアップ。迅速かつ堅牢なフロントエンド基盤およびDevOps基盤の作成に貢献しました。


### 副業マッチングサイトの継続開発 (2021年4月~2021年5月)

【プロジェクト概要】副業マッチングサイトCrowdLinksの開発

【担当業務】新規機能開発

【発揮したバリュー】新規機能開発のUIおよびバックエンドAPIの改修などを担当。


### デザイナー向け転職サイトの求人票システムの開発 (2021年2月~2021年3月)

【プロジェクト概要】デザイナー向け転職サイトの求人票システムの機能追加

【担当業務】フロントエンド開発 / 設計など

- フロントエンドの新規機能開発を担当
- Nuxtのコミュニティ各種プラグインの調査および実装(Markdown-it, Sentry)
- エラーモジュールの全体的なリファクタリング
- node-versionによるNodeバージョン固定およびパッケージengineの設定
- Playwrightの調査および組み込みによるE2Eテスト自動化・基盤コード作成
- SEO流入改善のためのサイト改善ポイントの棚卸し
- コンポーネントに対する権限認可モジュールの作成

【発揮したバリュー】静的型付けのNuxtについては初めてでしたが、苦労しつつもキャッチアップ。
キャッチアップ後は、新規技術の調査と実装を並行して行い、1ヶ月程度で数多くの新規機能の
実現や、各種自動化も行い、プロジェクトの基盤整備に新規技術を意欲的に追加。フロントエンドエンジニア
が開発生産性を最大限あげられ、外部発信する際にも話題にあげられるプロジェクト作りに貢献しました。

### D2C向けPaaS ECサイトの開発 (2020年10月~2021年3月)

【プロジェクト概要】D2C向けPaaS ECサイトのBFF開発エンジニア

【担当業務】BFFのエンジニアとして、フロントエンドおよびバックエンドの実装を担当

- 新規ブランドの立ち上げに際して、ローカル開発用のdocker-compose/bashスクリプトの作成
- サイト速度向上のための調査および問題点の棚卸し
- 新規商品種類の追加（コンタクトレンズ商品）のための、カートモジュールの全改修
- 本番以外の環境で、IP直などで参照できてしまう環境のSEO検索を回避するためのモジュールの作成・設計・テスト

【発揮したバリュー】関数型のライブラリを多く使ったPHP,TypeScriptのプロジェクトで、
開発スタイルとしてはアジャイル、DDDとレベルの高い環境であったが、
かなり多くの苦労をしながらキャッチアップ。アプリケーションコードのレベルが高く、
当初は全く歯が立たなかったのですが、最終的にはDDDの戦術的パターンで構築された
影響範囲があまりに大きい既存コード（カートモジュール）に対するリファクタを行うなど、
キャッチアップの大変な状況でも、最終的にチームの一人として貢献。
複数ブランド・複数環境がある中でのSEOの検索避けモジュールの設計・開発など、既存のコードベースでは
太刀打ちできない問題に根気強く取り組み、最後までやり切る力を発揮しました。


### フードテック系WEBサービスの開発 (2020年2月~2020年12月)

【プロジェクト概要】日本最大規模のフードテック系サービスのバックエンドAPI改修・テストコードの改修 / 関連するECサイトの継続開発および設計・マーケティング支援 / 女性向けカバンブランドの受託案件のディレクター兼エンジニア / サステナブル系ECサイトの新規開発 / サステナブル系ECサイトのサステナブル系メディアへの組み込み

【担当業務】複数事業の複数webサービスに、エンジニア、マーケター、ディレクターなどの多種多様な立ち回りから
事業の売り上げUPに貢献しました。

- Laravel / Vue.jsを利用したバッチ処理による、店舗へのレポート生成の自動化およびメール送付
- ECサイトの新規機能開発に関連するテーブル設計
- staginからmasterブランチへの自動PR作成するための調査・組み込み
- ECサイト構築の知見を使った、Shopifyを利用した短期間での新規事業およびECサイトの本番リリース
- Webhookの知見を使った、ShopifyとSlack連携およびShopifyとメディアサイト連携の構築
- 女性向けカバンブランドの新規受託開発案件のディレクション全ておよび開発
- SEO対策のための施策作成および打ち手の検討
- SEO対策と開発をブリッジするためのチームを立ち上げ

【発揮したバリュー】以前までの受託開発での実装方式とは全く違う中、初めて事業会社でのエンジニアとして
スタート。開発も正直まともにできているとは言い難い状況ではあったが、休みの日も学習に時間を当てるなどして
Laravel, Vueの開発方式の短期間でキャッチアップ。そのあとは、アルバイト時代に多くの経験を積んでいた、
SEO対策 X 開発という領域でバリューを発揮。マーケティングも理解するエンジニア、およびディレクションも理解するエンジニアとして新規事業の立ち上げに複数貢献。事業部門の売り上げUPに貢献しました。

### 医療機関と医療者向けのマッチングサービスの開発 (2019年7月~2020年2月)

【プロジェクト概要】医療機関と医療者を繋げるマッチングサービス新規受託開発。80%ほどの画面をベトナムに開発依頼し、20%ほどの画面開発を日本側で担当。全体の結合およびバグ修正およびUATまでも日本側で行い、設計からリリースまでを行なったプロジェクト。

【担当業務】webアプリケーションのコア部分の開発(Laravel, jQuery) / オフショア開発の管理およびコード整合性の担保

- Laravelによるバックエンド開発
- jQuery +  Laravel bladeによるフロントエンド開発
- テーブル設計
- アプリケーションアーキテクチャ設計
- オフショアとの英語によるやりとり

【発揮したバリュー】初めてのエンジニア専業としての実務経験で、正直言って全く仕事は歯が立ちませんでした。
しかし、1ヶ月程度でLaravel + jQueryというスタックにキャッチアップ。新規機能開発および簡単な実装の
簡易なアーキテクチャ設計までを担当できるように成長しました。ポテンシャルと手を動かす速さを発揮し、これまで
経験のあったマークアップなどについても工数の不足しているチームに貢献。プロジェクトとして大幅に納期が遅れるなど
逆境の中でも、自分だけ最後までエンジニアとして残って納品に貢献しました。
