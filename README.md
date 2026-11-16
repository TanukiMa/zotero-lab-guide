# 研究室向け Zotero 導入・共有ガイド

Windows (`winget`) と macOS (Homebrew) で Zotero をインストールし、研究室メンバー間で書誌情報を **Group Library** で共有するための手順書です。

## ドキュメントの閲覧方法

### ローカルで HTML を生成する場合

```bash
# Quarto がインストールされている環境で
quarto preview
# または
quarto render
```

生成された HTML は `docs/` ディレクトリに出力されます。

### GitHub Pages で公開する場合（推奨）

1. このリポジトリを GitHub に push
2. Settings → Pages で Source を `Deploy from a branch` → `main` / `/docs` に設定
3. 数分後に公開されます

## ファイル構成

```
.
├── README.md          # このファイル
├── _quarto.yml        # Quarto プロジェクト設定
├── index.qmd          # 本文（メインガイド）
└── docs/              # レンダリング後の HTML（GitHub Pages 用）
```

## 内容概要

1. Windows / macOS での Zotero インストール手順
2. アカウント作成と同期設定
3. Group Library の作成・メンバー招待・共有方法
4. 研究室向けの運用ルール提案
5. よくある質問

## ライセンス

このドキュメント自体は研究室内部利用を想定しています。必要に応じてライセンスを追加してください。

## 更新履歴

- 2026-11-16: 初版作成
