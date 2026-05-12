# AIフローアーキテクト — 案件ショーケース

データ収集・分析基盤・自動化ワークフローを中心に手掛けた案件のシステム構成図と技術概要をまとめた公開リポジトリです。

クライアント名・固有ドメイン・認証情報は伏せた匿名化版です。**設計思想／技術選定の根拠／構成のみ**を記載しています。

## 案件一覧

| # | 案件 | 領域 | 構成図 |
|---|------|------|-------|
| 01 | X リポスト・ハッシュタグ投稿者抽出 | スクレイピング設計 | [cases/01-x-data-extraction.md](cases/01-x-data-extraction.md) |
| 02 | GA4 × BigQuery × AI 分析基盤 | データ基盤 / AI分析 | [cases/02-ga4-bq-ai-platform.md](cases/02-ga4-bq-ai-platform.md) |
| 03 | 帳票自動生成 + メール下書き一括保存 | バックオフィス自動化 | [cases/03-doc-generation-mail-imap.md](cases/03-doc-generation-mail-imap.md) |

## 提供サービス領域

- **データ基盤設計**: GA4 / BigQuery / Looker Studio / dbt風 staging→marts→reports 4層構造
- **スクレイピング設計**: API判定 → 代替手段選定（公式API・Cookie + Playwright・モバイル経由）
- **AI連携**: OpenAI GPT / Gemini / Claude を業務フローに組み込み
- **自動化基盤**: GitHub Actions / n8n / Cloud Run / Cloud Functions
- **法的・運用面**: 利用規約 / 個人情報保護 / rate-limit / Bot検知回避の事前整理

## ご連絡先

- CrowdWorks ・ Lancers ・ Coconala の各PFよりご連絡ください
- 屋号: AIフローアーキテクト
