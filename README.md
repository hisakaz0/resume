# 職務経歴書

# 個人データ

| 氏名 | 福岡 久和（ふくおか ひさかず） |
| --- | --- |
| 生年月日 | 1993/12/23 |
| GitHub | [https://github.com/hisakaz0](https://github.com/hisakaz0) |

<image alt='profile' src='media/profile.png' width=320 />

# 職務経歴

## [株式会社Stack](https://stack.inc/) / 基盤システム開発

期間：2025/09 〜 現在

https://stack.inc/pages/sq

利用技術：xxx

## [フリー株式会社](https://www.freee.co.jp/) / 会計アプリ Android/iOS/バックエンド 開発・保守

期間：2023/09 ～ 2025/08

チーム内プロジェクトをメインで担当しつつ、事業部全体のプロジェクトにも携わった。具体は以下。

* いままで原因が分からず放置されていたクラッシュ修正
    * クラッシュフリー率を約1,2%改善
* 強制アップデート実施
* Android15(targetsdk 35)、edge-to-edgeの対応
* クライアントで利用するAPI開発(BFF)

利用技術：iOS, Android, Swift, SPM, Kotlin, Ruby on Rails

## [フリー株式会社](https://www.freee.co.jp/) / PoC向けLLM API開発

期間：2024/09 ～ 2025/01

フロントアプリ向けにLLM/RAGを利用できるPoCなAPIを作成。他チームと協力しながら、インフラ設計・構築からAPI開発まで担当。2名のチームで主に担当した。

利用技術：AWS Lambda, Bedrock, S3, cloudfront, Node.js, express.js

## [フリー株式会社](https://www.freee.co.jp/) / 社内向け 認証SDK 開発

期間：2023/12 ～ 2024/04

iOS/Androidアプリで OAuth 2.0 を使った認証に対応するため社内向けSDKの作成。仕様策定、SDK開発、導入手順書の作成などを担当した。PKCEにも対応した。

利用技術：iOS, Swift, Android, Kotlin, OAuth, ASWebAuthenticationSession, Android Custom Tabs

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
