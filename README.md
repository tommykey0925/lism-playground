# Lism Playground

[Lism CSS](https://lism-css.com/) のサンプル集を [Astro](https://astro.build/) で構築したショーケースサイト。

**Live:** https://tommykey0925.github.io/lism-playground/

## ページ

| ページ | 内容 |
|---|---|
| Home | サンプル一覧 + テーマ切替 |
| Primitives | `l--stack` / `l--flex` / `l--grid` / `l--fluidCols` / `l--columns` / `l--sideMain` のショーケース |
| Property Class | `-p` / `-bdrs` / `-fz` / `-bxsh` / `-bgc` のビジュアル一覧 |
| Blog | Glassmorphism 全面適用の実用デザインサンプル |
| Liquid Glass | iOS 26 Control Center 風の液体ガラス UI (SVG displacement filter + backdrop-filter) |

## 開発

```bash
pnpm install
pnpm dev
```

## デプロイ

`main` ブランチに push すると GitHub Actions が自動で GitHub Pages にデプロイします。

## 使用技術

- [Astro 6.1](https://astro.build/)
- [Lism CSS 0.14](https://lism-css.com/)
- pnpm
