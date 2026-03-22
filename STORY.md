# Day024 Story — Signal Card Mixer

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day024専用にテーマをseed固定して再生成時の見た目を安定化
- fun用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: idea_cards
- Mechanic: random_recombination
- Input/Output: multi_select_tokens -> card_stack
- Audience Promise: faster_idea_divergence
- Publish Hook: デッキを引くだけで試作テーマが決まる
- Complexity Tier: small
- Selected components: none
- Complexity hint: Keep the tool single-purpose and stable. Add at most one safe enhancement component.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day024｜Signal Card Mixer
カードの組み合わせから次の試作案を素早く作るデッキ型ツール。（話題:GitHub Trending (A）
