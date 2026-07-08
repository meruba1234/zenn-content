# zenn-content

[Zenn](https://zenn.dev) 記事管理用リポジトリ。GitHub 連携で `articles/` 配下の Markdown を自動公開する。

## 運用ルール

- `published: false` で下書き保存 → Zenn 上で自分だけプレビュー確認 → `true` に変えて push すると公開される
- 記事は匿名化 (取引先名・社内固有情報を伏せる) を徹底する
- スラッグ (ファイル名) は英数字・ハイフン・アンダースコアのみ、12〜50文字

## 新しい記事の追加

```bash
cd articles
# 適当なファイル名で新規作成 (例: my-article-title.md)
```

frontmatter テンプレート:

```yaml
---
title: "記事タイトル"
emoji: "😊"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["タグ1", "タグ2"]
published: false
---
```
