# HSEARL仕様への貢献

**言語:** [English](CONTRIBUTING.md) | [日本語](CONTRIBUTING.ja.md)

HSEARL仕様プロジェクトへの関心をお寄せいただき、ありがとうございます！コミュニティからの貢献を歓迎しており、このガイドでは貢献の方法をご説明します。

## 貢献の種類

### 1. イシューの報告
- **バグレポート**: 仕様の矛盾や誤りを発見した場合
- **機能要求**: 新しい機能や改善の提案
- **質問**: 仕様の理解に関する質問

### 2. RFC（Request for Comments）の提出
重要な変更や新機能については、RFCプロセスを通じて提案してください：

1. `RFCs/RFC-TEMPLATE.md`をベースに新しいRFCを作成
2. `RFCs/RFC-XXXX-your-title.md`として保存
3. プルリクエストを提出
4. コミュニティディスカッションに参加

### 3. 仕様の改善
- 仕様文書の明確化
- 構造とフォーマットの改善
- データスキーマの更新

### 4. 文書の充実
- 用語集の更新
- 例の追加
- 翻訳の改善

## 貢献プロセス

### 準備
1. GitHubアカウントを作成
2. リポジトリをフォーク
3. ローカルにクローン：
   ```bash
   git clone https://github.com/your-username/hsearl-spec.git
   cd hsearl-spec
   ```

### 変更の作成
1. 新しいブランチを作成：
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. 変更を実施
   - 関連する仕様文書を更新
   - 必要に応じてスキーマを更新
   - 用語集を更新（新しい概念がある場合）

3. 変更をコミット：
   ```bash
   git add .
   git commit -m "feat: your descriptive commit message"
   ```

### プルリクエストの提出
1. フォークにプッシュ：
   ```bash
   git push origin feature/your-feature-name
   ```

2. GitHubでプルリクエストを作成
3. テンプレートに従って詳細を記入
4. レビューを待ち、フィードバックに対応

## スタイルガイド

### 文書フォーマット
- Markdownを使用
- セクション見出しには`##`を使用
- コードブロックには適切な言語タグを使用
- 行の長さは120文字以内

### 用語の使用
- 技術用語は[用語集](./docs/glossary.md)に従う
- 新しい用語を導入する場合は用語集を更新
- 一貫した用語を使用

### コミットメッセージ
```
type(scope): description

[optional body]

[optional footer]
```

タイプ:
- `feat`: 新機能
- `fix`: バグ修正
- `docs`: 文書のみの変更
- `style`: フォーマット変更
- `refactor`: リファクタリング
- `test`: テスト追加
- `chore`: その他の変更

## コミュニティガイドライン

### 行動規範
すべての参加者は[行動規範](./CODE_OF_CONDUCT.md)に従ってください。

### コミュニケーション
- 建設的で敬意ある議論を心がける
- 技術的な議論に集中する
- 多様な視点を尊重する

### レビュープロセス
- すべての変更はレビューが必要
- 最低1人のメンテナーの承認が必要
- 破壊的変更にはより多くのレビューが必要

## 質問とサポート

- **ディスカッション**: [GitHub Discussions](https://github.com/HSEARL/hsearl-spec/discussions)
- **イシュー**: 具体的な問題について
- **メール**: hsearl-dev@googlegroups.com

## ライセンス

貢献することで、あなたの変更がApache 2.0ライセンスの下でライセンスされることに同意したものとします。

---

*HSEARLコミュニティへのご参加をお待ちしています！*