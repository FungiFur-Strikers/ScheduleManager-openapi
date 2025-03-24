# ScheduleManager API

<div align="center">

![GitHub last commit](https://img.shields.io/github/last-commit/FungiFur-Strikers/ScheduleManager-openapi)
![GitHub](https://img.shields.io/github/license/FungiFur-Strikers/ScheduleManager-openapi)

</div>

## 概要

スケジュール管理システムのためのREST API仕様書です。この仕様書はOpenAPI (Swagger) 3.0形式で記述されており、モダンで使いやすいAPIインターフェースを提供します。

### 主な機能

- スケジュールの作成・編集・削除
- ユーザー管理機能
- 高度な検索・フィルタリング
- カレンダー連携機能
- 通知管理システム

## ドキュメント

<div align="center">

### [Redoc形式のドキュメントを見る](https://fungifur-strikers.github.io/ScheduleManager-openapi/)

</div>

## 開発環境のセットアップ

### 必要な環境

| 要件 | バージョン |
|------|------------|
| Docker | 20.10.x以上 |
| Docker Compose | 2.x以上 |

### クイックスタート

1. **リポジトリのクローン**
```bash
git clone -b main https://github.com/FungiFur-Strikers/ScheduleManager-openapi.git
cd ScheduleManager-openapi
```

2. **Dockerコンテナの起動**

```bash
docker compose watch
```

3. **APIドキュメントへのアクセス**

以下のURLでドキュメントを閲覧できます：

http://localhost:8080


## API仕様書の編集

APIの仕様は `openapi.yml` で管理されています。このファイルは以下の特徴を持っています：

- OpenAPI 3.0形式準拠
- 詳細なリクエスト/レスポンス定義
- 実装例の提供
- 充実したコメント

## 継続的デプロイメント

このリポジトリはGitHub Actionsを活用して、以下の自動化を実現しています：

- mainブランチへのプッシュで自動デプロイ
- GitHub Pagesへの自動公開
- API仕様の自動検証

## コントリビューション

1. このリポジトリをフォーク
2. 新しいブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add amazing feature'`)
4. ブランチをプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## ライセンス

このプロジェクトは[MITライセンス](LICENSE)の下で公開されています。

---
