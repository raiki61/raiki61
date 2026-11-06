# raiki61

普段の開発で気づいた摩擦を、Claude Code用のプラグインにして直しています。

## 作ったもの

- [claude-plugins](https://github.com/raiki61/claude-plugins) — 収束するまで回す4つのループ（レビュー／調査／診断／初読）。実装者(writer)と採点者(grader)を別contextに分離し、収束を機械に宣言させない設計
- [works-factory](https://github.com/raiki61/works-factory) — AIによるソフトウェア修正工場（Archon上）。計画をレビューしてからコードを書き、赤テストを証明してから直し、エージェントの主張を証拠と照合する、検証ファーストな開発基盤（構築中）
- [tab-tint](https://github.com/raiki61/tab-tint) — Claude Codeが応答待ちの間だけターミナル背景を控えめに変えるフックプラグイン
