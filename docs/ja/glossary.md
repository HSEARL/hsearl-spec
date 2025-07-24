# HSEARL用語集

この文書では、HSEARL仕様全体で使用される主要な用語と概念を定義しています。

**言語:** [English](../glossary.md) | [日本語](./glossary.md)

## 基本用語

### エージェント（Agent）
HSEARLフレームワークを実装するエンティティで、認知、適応、目標指向行動が可能。

### 注意メカニズム（Attention Mechanism）
関連性とリソース制約に基づいて情報処理の選択と優先順位付けを行うシステムコンポーネント。

### 認知アーキテクチャ（Cognitive Architecture）
知覚、記憶、推論、行動選択を含む精神プロセスの全体的な構造と組織。

### コンテキスト（Context）
エージェントの行動と意思決定に影響を与える環境的および内部状態情報。

### 動機・衝動（Drive）
基本的な欲求を満たすために行動を活性化する根本的な動機力。

### 生態学的適応（Ecological Adaptation）
環境制約と機会に応じてエージェントが行動と内部モデルを調整するプロセス。

### エピソード（Episode）
記憶に保存される有界な経験の連続で、通常は一貫した出来事や相互作用を表す。

### 目標（Goal）
エージェントの計画と行動選択を導く望ましい状態または結果。

### HSEARL
Human Semantic & Ecological Adaptive Representation Language - 認知システムをモデル化するためのフレームワーク。

### 記憶システム（Memory System）
ワーキングメモリ、エピソード記憶、意味記憶を含む、情報の符号化、保存、検索を担当するコンポーネント群。

### 動機状態（Motivational State）
行動選択に影響を与える欲求、衝動、目標の現在の構成。

### 欲求階層（Need Hierarchy）
基本的（生理的）から複雑（自己実現）までの欲求の構造化された組織。

### 意味ネットワーク（Semantic Network）
概念をノード、関係性をエッジとする知識表現構造。

### 状態表現（State Representation）
認知的、動機的、生理的変数を含むエージェントの内部状態の正式な符号化。

### 状態遷移（State Transition）
定義されたルールと制約に支配された、ある有効な状態から別の状態への変化。

### 時間的ダイナミクス（Temporal Dynamics）
学習率、記憶減衰、適応速度を含む認知の時間に基づく側面。

### ワーキングメモリ（Working Memory）
認知タスク中に情報を一時的に維持・操作するための限定容量システム。

## 仕様用語

### 適合性（Conformance）
実装がHSEARL仕様要件にどの程度準拠しているかの度合い。

### 拡張（Extension）
互換性を保ちながらHSEARLコア仕様上に構築された追加機能。

### RFC（Request for Comments）
HSEARL仕様への変更または追加のための提案文書。

### スキーマ（Schema）
HSEARLコンポーネントのデータ構造と検証ルールの正式な定義。

### セマンティックバージョン（Semantic Version）
仕様変更を追跡するために使用されるバージョニングスキーム（MAJOR.MINOR.PATCH）。

## 実装用語

### バインディング（Binding）
HSEARL仕様の言語固有の実装。

### 互換性（Compatibility）
異なるHSEARL実装が正常に相互運用する能力。

### バリデータ（Validator）
データまたは実装がHSEARL仕様に適合しているかをチェックするツール。

## 略語

- **API**: Application Programming Interface（アプリケーションプログラミングインターフェース）
- **JSON**: JavaScript Object Notation
- **RFC**: Request for Comments
- **SemVer**: Semantic Versioning（セマンティックバージョニング）
- **YAML**: YAML Ain't Markup Language

---

*この用語集は生きた文書であり、HSEARL仕様の進化に合わせて更新されます。*