# devmetrics

開発プロセスにおけるメトリクスのメガリスト作成・整理・標準化と取得方法の考察

## MEGALIST

開発プロセスに関する考えうるメトリクスのをまとめ巨大なリスト

- [MEGALIST](./MEGALIST.tsv)

注意：

PullRequestに関する指標では「特定期間内に本流ブランチにマージされた」という点は

共通コンテキストでありPullRequest自体の特性を表す表現のため割愛する。

### Metric Name

メトリクス名称。UPPER_CASEで表記。

### Evaluation Target

その指標が主に何(誰)を評価するのか。評価対象。論理的な物体。

__例:__
- Repository
- PullRequest
- Developer

### Evaluation Characteristic

その指標が評価対象のどのような特性を評価するのか。評価特性。

__例:__
- Application Maintainability
- Development Productivity

例えば「各開発者のアプリケーション品質・保守性への貢献度」を表す指標の場合には

Evaluation Target: Developer
Evaluation Characteristic: Application Maintainability

となり、「各PullRequestの開発生産性」の状態を表す指標の場合には

Evaluation Target: PullRequest
Evaluation Characteristic: Development Productivity

となる。

### Data Source

そのメトリクスを取得する情報元。取得できないものである場合には記載しない。

__例:__
- CodeClimateQuality API
- Github API

### Description(JP)

日本語の説明文。