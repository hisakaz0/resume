# 職務経歴書

# 個人データ

| 氏名 | 福岡 久和（ふくおか ひさかず） |
| --- | --- |
| 生年月日 | 1993/12/23 |
| GitHub | [https://github.com/hisakaz0](https://github.com/hisakaz0) |

![k3zbfmatpt1i2psl5jujx24fcvhu.png](%E8%81%B7%E5%8B%99%E7%B5%8C%E6%AD%B4%E6%9B%B8%2074bfcd77f6474b4dbc428c8128744d01/k3zbfmatpt1i2psl5jujx24fcvhu.png)

# 職務経歴

## フリー株式会社 / 会計アプリ Android版 開発・保守

期間：2023/09 ～ 現在

いままで気づかれていなかったクラッシュ修正し、クラッシュフリー率を1%弱改善。チーム内プロジェクトをメインで担当しつつ、事業部全体のプロジェクトを携わった。

## フリー株式会社 / PoC向けLLM API開発

期間：2024/09 ～ 2025/01

iOS/Androidアプリ向けにLLM/RAGを利用できる簡易なAPIを作成。他チームから協力してもらい、インフラ構築からAPI開発まで担当。

利用技術：AWS Lambda, Bedrock, S3, cloudfront, Node.js, express.js

## フリー株式会社 / 社内向け auth sdk 開発

期間：2023/12 ～ 2024/04

iOS/Androidアプリで OAuth 2.0 の対応するため社内向けSDKの作成。仕様策定から導入手順書の作成などゼロから作成。 

りようぎｊ

## [合同会社DMM.com](https://dmm-corp.com/)  / [DMM TV](https://tv.dmm.com/) 新サービス立ち上げ

期間：2022/01 ～ 2023/08

「DMM TV」のサービス開発において、iOS/Androidアプリの開発リーダーを担当。アーキテクチャ選定や採用、CI/CDなど開発環境を用意しつつ、10名規模のAndroidチームのリーダーも担当した。技術のメンターもしつつ、動画のオフライン再生をメインに実装した。リリース後は開発と並行して持続可能な開発体制を強化中。以下利用した技術。

Kotlin Multiplatform Mobilieを導入してiOS/Androidの実装を共通化。API通信はapollo graphql、非同期処理はkotlin coroutinesを使用。UIはJetpack composeで構築した。

*Androidモバイルアプリ：[https://play.google.com/store/apps/details?id=com.dmm.premium](https://play.google.com/store/apps/details?id=com.dmm.premium&hl=ja&gl=JP)*

## [合同会社DMM.com](https://dmm-corp.com/)  / 新サービス PoC

期間：2021/09 ～ 2021/12

新サービス立ち上げに向けPoCとして、Googleのストア課金ができるアプリをリリース。ストア課金を実装し、並行してチームリーダーを担当。

## [株式会社EXPLAZA](https://corp.explaza.jp/) / 新サービス立ち上げ

期間：2022/04 ～ 2022/06

副業でExpo/React Nativeを使いモバイルアプリ開発を手伝った。Googleログイン・アカウント登録や商品検索を実装。CI/CDを整備し、ベータ版アプリを配布をおこなった。

*Androidアプリ：[https://play.google.com/store/apps/details?id=jp.explaza.app.explaza](https://play.google.com/store/apps/details?id=jp.explaza.app.explaza)*

*iOSアプリ：[https://apps.apple.com/jp/app/id6443840438](https://apps.apple.com/jp/app/id6443840438)*

## [合同会社DMM.com](https://dmm-corp.com/) / Androidモバイル向け動画プレイヤーアプリ開発・保守

期間：2018/08 ～ 2021/08

Androidネイティブアプリの機能追加や不具合修正など開発・保守。Google PlayStoreのリリースを担当した。主に対応した箇所は以下。

- プロプライエタリな動画プレイヤーライブラリからExoPlayerへの乗り換え
- circle ciを使ってCI/CD環境の整備
- アプリのアーキテクチャが2015年頃のままで開発がしずらかったため、１）java → kotlin, support library → androidxへの移行、２）multi module化、layered architectureへのリアーキテクチャを主導して開発、３）モダンなライブラリへ移行

３）は具体的に以下。

- google volley → retrofit, okhttp
- daggerの導入
- java.util.executor, AsyncTask → kotlin coroutines

*Androidモバイル向けアプリ：[https://play.google.com/store/apps/details?id=com.dmm.app.movieplayer](https://play.google.com/store/apps/details?id=com.dmm.app.movieplayer)*

## [合同会社DMM.com](https://dmm-corp.com/) / FireTV向け動画プレイヤーアプリ開発・保守

期間：2018/08 ～ 2021/08

モバイルアプリ開発と並行して、FireTVアプリの開発・保守も担当。FabricからFirebaseへの移行をメインで担当した。

*FireTV向けアプリ：[https://www.amazon.co.jp/dp/B01BL1W8RE](https://www.amazon.co.jp/dp/B01BL1W8RE)*

# スキルセット

## フレームワーク

- Android
- KMM(Kotlin multiplatform mobile)
- React Native, Expo
- Jetpack compose

### 言語

- Java
- Kotlin
- JavaScript, TypeScript

### ライブラリ

- Jetpack
    - Room
    - ViewModel, LiveData
    - Navigation
    - WorkManager
    - Paging
    - App Distribution
    - Performance monitoring
- Material Design
- Firebase
    - Cloud Messaging
    - Analytics
    - Crashlytics
    - Remote config
- kotlin coroutines, flow
- kotlinx.datetime, threetenbp
- kotlinx.serialization
- Dagger2(hilt), Koin
- Lottie
- Datadog
- apollo grapql
- retrofit, okhttp3, ktor
- [Puree](https://github.com/cookpad/puree-kotlin)
- junit, mockk
- Timber, [Napier](https://github.com/AAkira/Napier)
- Google PlayStore publishing API
- Google PlayStore billing API
- leak canary

### 動画再生

- ExoPlayer
- chromecast(sender)

### アーキテクチャや構成

- Layered Architecture
- Gradle multi-module
- Gradle version catalog, composite build

### CI/CD

- Github Actions
- CircleCi
- DeployGate
- Bitrise
- fastlane
- Danger

### Lint/Formatter

- android lint
- ktlint
- detekt