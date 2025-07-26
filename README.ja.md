# HSEARL

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-green)](https://github.com/HSEARL/hsearl-spec/discussions)
[![RFC Process](https://img.shields.io/badge/RFC-Process-orange)](./RFCs/)

**言語:** [English](README.md) | [日本語](README.ja.md)

## 概要

このリポジトリは、HSEARL（ハール）フレームワークの中核となる意味論、構造、拡張プロセスを定義します。

HSEARLは、人間をデジタル空間上で構築するための、フレームワークや技術群の総称となります。

HSEARLは以下をモデル化するための正式な仕様を提供することを目標とします：

- **認知アーキテクチャ**: 記憶システム、注意メカニズム、意思決定プロセス
- **動機的ダイナミクス**: 欲求階層、目標追求、行動適応
- **環境との相互作用**: 文脈に応じた反応と生態学的制約
- **時間的進化**: 学習、発達、時間にわたる状態遷移

このプロジェクトの目的は人の活動における純粋なタスクを解決することであり、人間とは何かという学術的な思想、根拠、正確さの議論を対象としません。

現状LLMを用いた実装が前提であり、それに対しての必要なフレームワーク、技術群とみなすことができます。

## プロジェクトの範囲

この仕様リポジトリには以下が含まれます：
- **核となる定義**: [HSEARLの基本概念](hsearl)
- **拡張メカニズム**: 互換性を保ちながら新機能を追加する方法
- **正式なスキーマ**: データ構造定義と検証ルール
- **設計文書**: アーキテクチャガイドラインとベストプラクティス

## クイックスタート

```bash
# リポジトリをクローン
git clone https://github.com/HSEARL/hsearl-spec.git
cd hsearl-spec

# 核となる仕様を確認
cd hsearl/

# データスキーマを確認
cd schemas/
```

## リポジトリ構造

```
hsearl-spec/
├── hsearl/            # HSEARLフレームワーク定義
│   ├── frame/        # フレームワーク仕様
│   ├── memory/       # メモリシステム
│   └── physicality/  # 肉体性
├── RFCs/             # Request for Comments（提案）
├── schemas/          # JSON/YAMLスキーマ
├── docs/             # 追加文書
│   ├── architecture/ # アーキテクチャガイド
│   ├── design/       # 設計文書
│   └── glossary.md   # 用語と定義
├── experimental/     # 実験的機能
└── LICENSE, README等 # プロジェクトファイル
```

## 主要文書

- 📚 **[ハール仕様](./hsearl/)** - HSEARLの基本概念
- 📜 **[RFCプロセス](./RFCs/)** - 変更提案の方法
- 📖 **[用語集](./docs/glossary.ja.md)** - 主要用語と定義（[英語版](./docs/glossary.md)）

## 関連プロジェクト

- 🧪 **[hsearl-core](https://github.com/HSEARL/hsearl-core)** - ライブラリのコード、プロンプト実装

## コミュニティ

- **ディスカッション**: [GitHub Discussions](https://github.com/HSEARL/hsearl-spec/discussions)
- **イシュー**: [バグレポートと機能要求](https://github.com/HSEARL/hsearl-spec/issues)
- **メーリングリスト**:
## 参加方法

貢献を歓迎しています！以下をご提出ください：
- 変更提案のためのRFC
- バグレポートと機能要求のためのイシュー
- 仕様改善のためのプルリクエスト
- ドキュメントの改善

## バージョニング

この仕様は[セマンティックバージョニング](https://semver.org/)に従います：
- **メジャー**: 核となる仕様への破壊的変更
- **マイナー**: 後方互換性のある新機能
- **パッチ**: 明確化と修正

現在のバージョン: **0.1.0** （プリリリース）

## ライセンス

| 部分 | ライセンス | 商用利用 |
|------|------------|----------|
| hsearl-spec | Apache 2.0 | 自由 |
| hsearl-core (reference code) | Polyform Noncommercial 1.0.0 | **禁止**（商用は要別契約） |

商用利用の際にはこちらにご連絡ください → **contact@zeetio.jp**
