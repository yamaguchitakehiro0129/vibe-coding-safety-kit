# 用語インデックス

AIに質問するための、用語集。

---

## このページの使い方

このページは、読み物ではない。
AIに質問を投げるための、索引である。

使い方は3つ。

ひとつ。気になる用語を見つける。
ふたつ。AIに「○○について、初心者にもわかるように教えて」と聞く。
みっつ。理解できたら、関連用語に広げていく。

全部を理解する必要はない。
今日のあなたに必要な、2つか3つを拾えばいい。

---

## A. アーキテクチャ

* レイヤードアーキテクチャ
* ヘキサゴナルアーキテクチャ（Ports and Adapters）
* オニオンアーキテクチャ
* クリーンアーキテクチャ
* マイクロサービス / モノリス / モジュラーモノリス
* イベント駆動アーキテクチャ（EDA）
* CQRS
* イベントソーシング
* BFF（Backend for Frontend）
* サーバーレスアーキテクチャ

## B. ドメインモデリング

* DDD（ドメイン駆動設計）
* 境界づけられたコンテキスト
* ユビキタス言語
* エンティティ / 値オブジェクト / 集約
* ドメインイベント
* 戦略的設計 / 戦術的設計

## C. データ

* 正規化と非正規化
* ERモデリング
* イミュータブルデータモデル
* Single Source of Truth
* Event Sourcing
* スタースキーマ / スノーフレークスキーマ

## D. API設計

* REST原則
* GraphQL / gRPC
* バージョニング戦略
* ページネーション（オフセット型 / カーソル型）
* HATEOAS
* OpenAPI
* 冪等性キー（Idempotency Key）
* RFC 7807 Problem Details

## E. 整合性とトランザクション

* ACID特性
* 楽観ロック / 悲観ロック
* 分散トランザクション
* Sagaパターン
* 結果整合性
* 冪等性
* Outboxパターン

## F. キャッシュ

* cache-aside / write-through / write-back
* キャッシュスタンピード
* TTL jitter
* ホットキー問題
* CDNエッジキャッシュ

## G. 設計原則

* SOLID原則（SRP / OCP / LSP / ISP / DIP）
* DRY / KISS / YAGNI
* 関心の分離
* Tell, Don't Ask
* デメテルの法則
* Composition over Inheritance
* Fail Fast

## H. デザインパターン

* Factory / Builder / Singleton
* Adapter / Decorator / Proxy
* Observer / Strategy / Command
* Repository
* Unit of Work
* Specification

## I. テスト

* テストピラミッド / テスティングトロフィー
* TDD / BDD
* Given-When-Then / Arrange-Act-Assert
* プロパティベーステスト
* コントラクトテスト
* ミューテーションテスト
* テストダブル（Stub / Spy / Mock / Fake）

## J. 並行処理

* スレッドセーフティ
* レースコンディション
* TOCTOU
* デッドロック
* async / await
* Reactive Programming
* バックプレッシャー

## K. 性能

* N+1問題
* インデックス設計
* EXPLAIN
* Big O記法
* メモリリーク
* プロファイリング
* コネクションプール
* スロークエリ
* コールドスタート
* Core Web Vitals（LCP / INP / CLS）

## L. スケーラビリティ

* 水平スケーリング / 垂直スケーリング
* ステートレス設計
* シャーディング
* レプリケーション
* CAP定理 / PACELC定理
* ロードバランシング

## M. 可用性

* 単一障害点（SPOF）
* サーキットブレーカー
* バルクヘッドパターン
* 指数バックオフとリトライ
* カナリアリリース / Blue-Greenデプロイ / フィーチャーフラグ
* RTO / RPO

## N. 可観測性

* ログ / メトリクス / トレース
* OpenTelemetry
* 構造化ログ
* SLI / SLO / SLA
* ゴールデンシグナル
* アラート疲れ

## O. セキュリティ全般

* OWASP Top 10
* OWASP ASVS
* Defense in Depth
* ゼロトラスト
* 最小権限の原則
* Assume Breach
* 監査証跡

## P. 認証・認可

* OAuth 2.0
* OIDC
* PKCE
* JWT
* MFA / WebAuthn / FIDO2
* セッションフィクセーション
* IDOR（Insecure Direct Object Reference）
* RBAC / ABAC
* 認証 vs 認可

## Q. 暗号化・機密情報

* CSPRNG
* bcrypt / Argon2 / scrypt
* ソルト
* IV（初期化ベクトル）
* KMS / HSM / Vault / Secrets Manager
* 鍵ローテーション

## R. 入力検証・出力エンコーディング

* ホワイトリスト方式
* JSON Schema検証
* XXE（XML External Entity）
* Billion Laughs攻撃
* パストラバーサル
* Zip Bomb
* CSV Injection

## S. インジェクション攻撃

* SQLインジェクション
* OSコマンドインジェクション
* LDAPインジェクション
* NoSQLインジェクション
* テンプレートインジェクション（SSTI）
* デシリアライズ攻撃
* オープンリダイレクト
* SSRF（サーバサイドリクエストフォージェリ）

## T. 通信の保護

* TLS
* HSTS
* CSP（Content Security Policy）
* CORS
* X-Frame-Options
* X-Content-Type-Options

## U. 依存関係とサプライチェーン

* lockファイル
* 脆弱性スキャン
* タイポスクワッティング
* サプライチェーン攻撃
* SBOM（Software Bill of Materials）
* EOLパッケージ

## V. LLM・AI特有

* プロンプトインジェクション（直接 / 間接）
* ツール汚染
* OWASP LLM Top 10
* ハルシネーション
* RAG（Retrieval-Augmented Generation）

## W. UI / UX

* WCAG
* WAI-ARIA
* インクルーシブデザイン
* ニールセンの10ヒューリスティクス
* アフォーダンス / シグニファイア
* ヒックの法則 / フィッツの法則

## X. プロセスとドキュメント

* ADR（Architecture Decision Record）
* C4モデル
* Conventional Commits
* SemVer（セマンティックバージョニング）
* GitFlow / GitHub Flow / Trunk-Based Development

---

## 使い方の指針

このリストは、すべて理解する必要はない。

「いま自分が困っている問題」に近そうな用語を、ひとつだけ選ぶ。
それをAIに聞いて、関連用語に広げていく。

そうやって、少しずつ自分の武器を増やしていく。
それが、エンジニアとしての成長である。
