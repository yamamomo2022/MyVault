# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## リポジトリ概要

これは個人用のObsidianナレッジベース（MyVault）で、構造化されたノート管理と知識管理を目的としています。マークダウンファイルとテンプレートを使用して、メモ、日記、読書記録を管理しています。

## ディレクトリ構成

- `00-templates/`: 標準化されたノート作成用のテンプレート。YAMLフロントマターを含む日記テンプレートなど
- `01-inbox/`: 後で整理が必要な新しいメモの一時保存場所
- `02-daily/`: 日々の記録とメモ
- `03-books/`: 読書メモと書籍関連コンテンツ
- `copilot-custom-prompts/`: テキスト処理タスク用のGitHub Copilotカスタムプロンプト集

## 主要ファイルとパターン

### テンプレート
- `00-templates/template_daily.md`: Obsidianのtemplater構文を使用した日記テンプレート。日付変数と`#journal`、`#journal/daily`タグを含む

### Copilot連携
`copilot-custom-prompts/`ディレクトリには、コンテンツ処理用の専用プロンプトが含まれています：
- テキスト変換（要約、簡素化、長文化/短縮化）
- 言語処理（翻訳、文法修正）
- コンテンツ生成（目次、用語集）
- ソーシャルメディア形式（ツイート変換）

各プロンプトファイルは、`copilot-command-context-menu-enabled`やコマンド順序設定などでCopilotの動作を設定するYAMLフロントマターを使用しています。

## このVaultでの作業

コンテンツを修正・作成する際は：
- 整理のために確立されたディレクトリ構造に従う
- YAMLフロントマターで適切なタグを使用（特に日記には`#journal`タグ）
- 新しいコンテンツはinbox → 適切な場所へのワークフローを維持
- READMEファイルに記載されている日本語コンテキストを尊重する