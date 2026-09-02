# denchiya — 電池屋 社内向け資料

株式会社電池屋の社内向け資料（Claude 用コネクタの利用ガイド・手順書・業務資料）を置いているリポジトリです。
すべて GitHub Pages で公開しており、URL を知っている人はブラウザでそのまま開けます（検索エンジンには載りません）。

**社員に配る URL はこれ1つ**（入口ページ。以下の全資料へのリンクがあります）: **https://takehiroichikura.github.io/denchiya/**

## 🔗 閲覧URL

### MCP 利用ガイド（Claude 用コネクタ）

> **MCP は招待コードがないと使えません。** 各コネクタを初めてつなぐとき、認可画面で招待コード（`INV-あなたの名前-…`）の入力を求められます。
> 招待コードは市倉が社員ごとに発行します。全コネクタ共通で、発行から30日有効です。持っていない人・期限が切れた人は市倉まで。

| コネクタ | 何ができるか | ガイド |
|---|---|---|
| 楽天MCP | 楽天RMS の受注・問い合わせ・商品・在庫・クーポン等 | **https://takehiroichikura.github.io/denchiya/rakuten-mcp-guide.html** |
| Yahoo!ショッピング MCP | 受注・問い合わせ・在庫・価格 | **https://takehiroichikura.github.io/denchiya/yahoo-mcp-guide.html** |
| Amazonセラー MCP | セラーセントラル（モール出品側）の注文・FBA在庫・出品・価格・売上 | **https://takehiroichikura.github.io/denchiya/amazon-seller-mcp-guide.html** |
| Amazonベンダー MCP | ベンダーセントラル（4社）の発注・小売分析・請求 | **https://takehiroichikura.github.io/denchiya/amazon-vendor-mcp-guide.html** |
| Amazon Pay MCP | 本館（自社サイト）の Amazon Pay 決済状態・入金・決済レポート | **https://takehiroichikura.github.io/denchiya/amazon-pay-mcp-guide.html** |
| 価格.com MCP | 価格.com の他店価格・自店順位 | **https://takehiroichikura.github.io/denchiya/kakaku-mcp-guide.html** |
| Chatwork MCP | 自分の Chatwork の未読・要約・タスク、自分の名前での投稿（自分のトークン登録が必要） | **https://takehiroichikura.github.io/denchiya/chatwork-mcp-guide.html** |
| UiPath MCP | 社内RPA（UiPath）のジョブ状況確認・操作 | **https://takehiroichikura.github.io/denchiya/uipath-mcp-guide.html** |
| サイボウズ ユーザー管理 MCP | サイボウズのユーザー・組織管理（担当者限定） | **https://takehiroichikura.github.io/denchiya/cybozu-mcp-guide.html** |

### 手順書

| 資料 | URL |
|---|---|
| GitHubアカウント作成手順書 | **https://takehiroichikura.github.io/denchiya/github-account-setup.html** |

### 業務資料

| 資料 | URL |
|---|---|
| 電池屋 全業務マップ | **https://takehiroichikura.github.io/denchiya/gyomu-map.html** |
| スキル化候補マップ | **https://takehiroichikura.github.io/denchiya/skill-map.html** |

※ 全ページに `noindex` を設定しており、Google等の検索結果には表示されません（URLを知っている人は閲覧できます）。

## 📄 資料ファイル

### MCP 利用ガイド

| ファイル | 内容 |
|---|---|
| [rakuten-mcp-guide.html](./rakuten-mcp-guide.html) | 楽天MCP の利用ガイド。接続手順・できること・書き込み操作の約束ごと |
| [yahoo-mcp-guide.html](./yahoo-mcp-guide.html) | Yahoo!ショッピング MCP の利用ガイド |
| [amazon-seller-mcp-guide.html](./amazon-seller-mcp-guide.html) | Amazonセラー MCP の利用ガイド |
| [amazon-vendor-mcp-guide.html](./amazon-vendor-mcp-guide.html) | Amazonベンダー MCP の利用ガイド |
| [amazon-pay-mcp-guide.html](./amazon-pay-mcp-guide.html) | Amazon Pay MCP の利用ガイド |
| [kakaku-mcp-guide.html](./kakaku-mcp-guide.html) | 価格.com MCP の利用ガイド |
| [chatwork-mcp-guide.html](./chatwork-mcp-guide.html) | Chatwork MCP の利用ガイド（APIトークンの申請・登録手順を含む） |
| [uipath-mcp-guide.html](./uipath-mcp-guide.html) | UiPath MCP の利用ガイド |
| [cybozu-mcp-guide.html](./cybozu-mcp-guide.html) | サイボウズ ユーザー管理 MCP（担当者限定）の利用ガイド |

### 手順書

| ファイル | 内容 |
|---|---|
| [github-account-setup.html](./github-account-setup.html) | 「Claude×業務自動化研修」の前に済ませておくGitHubアカウントの作成手順（手順1〜5＋補足） |

### 業務資料

| ファイル | 内容 |
|---|---|
| [gyomu-map.html](./gyomu-map.html) | 電池屋 全業務マップ。従業員23名の「業務詳細」Excel（2026年8月）を統合し、5つの商流・仕事の流れ・部門別の業務と工数・使用システム・改善の種をまとめた資料 |
| [skill-map.html](./skill-map.html) | スキル化候補マップ。全業務マップからClaudeスキル化できそうな業務を個人別に82件抽出し、着手しやすさ（A/B/C）と横断6テーマで整理した資料 |

## 更新方法

各HTMLファイルを編集してこのリポジトリにプッシュ（またはWebからアップロード）すれば、閲覧URLの内容も自動で更新されます。

## 管理

Eコマース部 システム課（市倉）
