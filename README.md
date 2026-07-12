---

# Ming Yin のポートフォリオサイト

HTML、CSS、JavaScriptで制作し、AWS上にデプロイした個人ポートフォリオサイトです。

🌐 **デモサイト**
- https://mingyin.dev

---

# プロジェクト概要

このプロジェクトは、Web開発のスキルとクラウドエンジニアリングへの取り組みを紹介するために制作したポートフォリオサイトです。
サイトはHTML、CSS、JavaScriptによる静的Webサイトとして構築し、AWSの各種サービスを利用して、安全性・可用性・拡張性を考慮した構成で公開しています。

---

# 使用技術

### フロントエンド

- レスポンシブWebデザイン
- HTML5
- CSS3
- JavaScript

### AWS クラウド

- Amazon S3（プライベートバケット）
- Amazon CloudFront
- Origin Access Control (OAC)
- AWS Certificate Manager (ACM)
- Amazon Route 53
- CloudFront Functions

### セキュリティ

- HTTPS（SSL/TLS）
- HTTP Basic認証
- プライベートS3オリジン
- カスタム404エラーページ

### バージョン管理

- Git
- GitHub

---

# 主な機能

- レスポンシブ対応のポートフォリオサイト
- AWSによる静的サイトホスティング
- 独自ドメイン（`mingyin.dev`）
- ACMによるHTTPS対応
- CloudFrontによる高速コンテンツ配信
- Origin Access Control（OAC）によるプライベートS3保護
- CloudFront FunctionsによるURLリライト
- HTTP Basic認証
- カスタム404ページ

---

# AWS アーキテクチャ

```text
                   GitHub
                      │
                      ▼
                  ソースコード
                      │
                      ▼
      Amazon S3（プライベートバケット）
                      ▲
                      │
      Origin Access Control（OAC）
                      │
                      ▼
          Amazon CloudFront
                      │
      CloudFront Functions
      ├── URLリライト
      └── Basic認証
                      │
                      ▼
       Route 53 + ACM（HTTPS）
                      │
                      ▼
          https://mingyin.dev
```

---

# 技術スタック

| カテゴリ | 使用技術 |
|-----------|----------|
| フロントエンド | HTML5、CSS3、JavaScript |
| クラウド | Amazon S3、CloudFront、Route 53、ACM |
| セキュリティ | OAC、HTTPS、Basic認証 |
| ツール | Git、GitHub、Adobe Dreamweaver、Adobe illustrator、Canva |

---

# プロジェクト構成

```text
My-Portfolio/
├── shared/
│   ├── css/
│   ├── js/
│   ├── assets/
│   └── favicon.svg
│   
├── about/
├── works/
├── contact/
├── index.html
├── 404.html
└── README.md
```

---

# デプロイ構成

本サイトは以下のAWSサービスを利用して公開しています。

- Amazon S3（プライベートバケット）
- Amazon CloudFront
- Origin Access Control（OAC）
- Amazon Route 53
- AWS Certificate Manager（ACM）

---

# 作者

**Ming Yin**

- Portfolio: https://mingyin.dev
- GitHub: https://github.com/tming2288-star
