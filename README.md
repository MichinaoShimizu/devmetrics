# devmetrics

開発プロセスにおけるメトリクスのメガリスト作成・整理・標準化と取得方法の考察

# MEGALIST

開発プロセスに関する考えうるメトリクスのをまとめ巨大なリスト

- [MEGALIST](./MEGALIST.tsv)

PullRequestに関する指標は「特定期間内に本流ブランチにマージされた」という点は共通

## 評価対象

論理的な物体。そのメトリクスが主に何を評価する指標となるのか。

__例:__
- Repository
- PullRequest
- Developer

## 評価特性

論理的な特性。そのメトリクスが評価対象のどのようなことを評価する指標となるのか。

__例:__
- Maintainability
- Productivity

## 名称

今後表現を統一するのに適したメトリクス名称。UPPER_CASEで表記。

## データソース

そのメトリクスを取得する情報元。

__例:__
- CodeClimateQuality API
- Github API

## 説明文

日本語の説明文。