# ADR-0001: Exclude Big Five Trait Model
Date: 2025-04-04
Status: **Rejected**

## Context
検討案: HSEARL の Head 構造に Big Five（OCEAN）を追加するアイデア
## Decision
**採用しない** と決定。理由は以下:

1. **理論重複**
   - Head と Self=Enneagram の組合せで十分な差別化指標。
2. **効果が薄い**
   - Big Five は情報量が薄い。記述が煩雑になる割に説明性が弱い。

## Consequences
- `hsearl/core` の拡張候補から Big Five を削除。
- 将来 Big Five を**再検討する条件**:
  1. coreでは説明しきれない問題が多発したとき  2.LLMの賢さがあがり、BIG５もうまく理解できたとき
## Authors / Reviewers
- @ryouseki (author)
- @xxx (review)
