# tmizuno.net

個人ポートフォリオサイト - 研究成果・職歴・ブログを公開

## サイト情報

- **URL**: https://tmizuno.net
- **フレームワーク**: Astro
- **ホスティング**: GitHub Pages

## 開発手順

### 1. セットアップ

```bash
yarn install
```

### 2. ローカル開発

```bash
yarn dev
```

ブラウザで http://localhost:4321 を開く

### 3. ビルド確認

```bash
yarn build
```

`dist/` フォルダに出力される

### 4. デプロイ

mainブランチにマージすると自動デプロイされる

```bash
git checkout main
git merge <your-branch>
git push origin main
```

GitHub Actionsが自動でビルド＆デプロイを実行

## ファイル構成

```
src/
├── layouts/
│   └── Layout.astro    # 共通レイアウト（ナビ、SEO設定）
└── pages/
    ├── index.md        # トップページ
    ├── research.md     # 研究
    ├── publication.md  # 出版物
    ├── blogs.md        # ブログ一覧
    └── blog/           # ブログ記事
public/
├── CNAME              # カスタムドメイン設定
└── (画像ファイル)
```

## ブログ記事の追加方法

1. `src/pages/blog/` に新しい `.md` ファイルを作成

```markdown
---
title: 記事タイトル
description: 記事の説明
layout: ../../layouts/Layout.astro
---

# 記事タイトル

本文...
```

2. `src/pages/blogs.md` にリンクを追加

3. コミット＆mainにマージ

## コマンド一覧

| コマンド | 説明 |
|---------|------|
| `yarn dev` | ローカル開発サーバー起動 |
| `yarn build` | 本番用ビルド |
| `yarn preview` | ビルド結果のプレビュー |
