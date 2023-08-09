# PicoCMS-Z

APIベースのヘッドレスCMSと、それを利用するためのライブラリ・ツールを提供するオープンソースプロジェクトです。  

既存のものよりも、もっとシンプルで、使いやすく、最低限の機能をもたせたため、PicoCMSと名付けました。  

Zはかっこいいから。

## コンセプト

- シンプルで使いやすい最小限の機能をもつ。
- ローカル環境で記事を作成・編集できる。
- 記事はMarkdownで書かれることを想定。

## サービス

### PicoCMS

APIベースのヘッドレスCMS

- コンソール画面の提供
- Web APIの提供

[Repository](https://github.com/PicoCMS-Z/PicoCMS)

### PicoCMS CLI

ローカル環境での記事の編集をサポートするツール。  

- Web APIにリクエストを送れるコマンドの提供。
- Markdownファイルを解析して、参照されている画像ファイルを自動アップロード。(未定)

### PicoCMS Client

ブログアプリ側から記事を取得するためのライブラリ。  

- PicoCMS Web APIにリクエストを送信するクライアントライブラリ。

#### 対応言語

- JavaScript(Node.js)
- Go
- Python

## アピールポイント

- フルスタックプロジェクト
- マイクロサービスアーキテクチャ
- k8sを用いたインフラ管理
- Terraformを用いたインフラ構築
- Rustの軽快な動作
- OSS

## 技術スタック

### バックエンド

- Rust/axum
- Go/Gin
- MongoDB

### フロントエンド

- Next.js

### インフラ

- Google Cloud Platform 
- Kubernetes
- Terraform