# zenn-articles

[Zenn](https://zenn.dev/) の記事をGitHub連携で管理するリポジトリ。

`articles/` に Markdown を置いて push すると Zenn に反映される。

## 使い方

```bash
npx zenn preview            # ローカルプレビュー（http://localhost:8000）
npx zenn new:article        # 新規記事のひな形を作成
```

## frontmatter

```yaml
---
title: "記事タイトル"
emoji: "🎤"          # 1文字
type: "tech"         # tech（技術記事） or idea（アイデア）
topics: ["whisper", "python"]   # 5つまで
published: false     # true にすると公開される
---
```

**`published: false` の間は下書き扱いで、push しても公開されない。**
公開したくなったら true に変えて push する。

## 記事一覧

| slug | タイトル | 状態 |
|---|---|---|
| `whisper-accuracy-ab-testing` | Whisperの精度改善、5施策を実測したら3つ棄却になった話 | 下書き |
