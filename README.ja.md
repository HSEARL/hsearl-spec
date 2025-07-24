# HSEARL仕様

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Discussions](https://img.shields.io/badge/GitHub-Discussions-green)](https://github.com/HSEARL/hsearl-spec/discussions)
[![RFC Process](https://img.shields.io/badge/RFC-Process-orange)](./RFCs/)

**言語:** [English](README.md) | [日本語](README.ja.md)

## 概要

このリポジトリは、HSEARL（Human Semantic & Ecological Adaptive Representation Language）フレームワークの中核となる意味論、構造、拡張プロセスを定義します。HSEARLは、人間の認知、動機、適応を表現・シミュレーションするための意味的骨格です。

HSEARLは以下をモデル化するための正式な仕様を提供します：
ハール＝コア＋補助＋記憶＋肉体性＋？

- **認知アーキテクチャ**: 記憶システム、注意メカニズム、意思決定プロセス
- **動機的ダイナミクス**: 欲求階層、目標追求、行動適応
- **環境との相互作用**: 文脈に応じた反応と生態学的制約
- **時間的進化**: 学習、発達、時間にわたる状態遷移

## プロジェクトの範囲

この仕様リポジトリには以下が含まれます：
- **核となる定義**: 基本概念とデータ構造
- **拡張メカニズム**: 互換性を保ちながら新機能を追加する方法
- **正式なスキーマ**: データ構造定義と検証ルール
- **設計文書**: アーキテクチャガイドラインとベストプラクティス

## クイックスタート

```bash
# リポジトリをクローン
git clone https://github.com/HSEARL/hsearl-spec.git
cd hsearl-spec

# 核となる仕様を確認
cd specs/

# データスキーマを確認
cd schemas/
```

## リポジトリ構造

```
hsearl-spec/
├── specs/              # 正式な仕様書
│   ├── core/          # 核となるフレームワーク定義
│   ├── extensions/    # 標準拡張
│   └── experimental/  # 実験的機能
├── RFCs/              # Request for Comments（提案）
├── schemas/           # JSON/YAMLスキーマ
├── docs/              # 追加文書
│   ├── architecture/  # アーキテクチャガイド
│   └── glossary.md   # 用語と定義
└── .github/           # プロジェクト管理
```

## 主要文書

- 📚 **[コア仕様](./specs/core/)** - HSEARLの基本概念
- 📜 **[RFCプロセス](./RFCs/)** - 変更提案の方法
- 🏛️ **[ガバナンス](./GOVERNANCE.md)** - 意思決定プロセス
- 🔒 **[セキュリティポリシー](./SECURITY.md)** - 脆弱性報告
- 📝 **[貢献ガイド](./CONTRIBUTING.md)** - 貢献方法
- 📖 **[用語集](./docs/glossary.md)** - 主要用語と定義（[日本語版](./docs/ja/glossary.md)）

## 関連プロジェクト

- 🧪 **[hsearl-core](https://github.com/HSEARL/hsearl-core)** - リファレンス実装
- 📊 **[hsearl-eval](https://github.com/HSEARL/hsearl-eval)** - 評価フレームワーク
- 🔧 **[hsearl-tools](https://github.com/HSEARL/hsearl-tools)** - 開発ユーティリティ

## コミュニティ

- **ディスカッション**: [GitHub Discussions](https://github.com/HSEARL/hsearl-spec/discussions)
- **イシュー**: [バグレポートと機能要求](https://github.com/HSEARL/hsearl-spec/issues)
- **メーリングリスト**: hsearl-dev@googlegroups.com

## 参加方法

貢献を歓迎しています！詳細は[貢献ガイド](./CONTRIBUTING.md)をご覧ください：
- RFCの提出
- イシューの報告
- 仕様の改善
- 文書の充実

## バージョニング

この仕様は[セマンティックバージョニング](https://semver.org/)に従います：
- **メジャー**: 核となる仕様への破壊的変更
- **マイナー**: 後方互換性のある新機能
- **パッチ**: 明確化と修正

現在のバージョン: **0.1.0** （プリリリース）

## ライセンス

このプロジェクトはApache License 2.0の下でライセンスされています - 詳細は[LICENSE](./LICENSE)ファイルをご覧ください。