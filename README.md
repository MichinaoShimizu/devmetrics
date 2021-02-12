# devmetrics-standard

開発プロセスにおけるメトリクスの抽出・分類・標準化に対する考察

## MEGALIST

開発プロセスに関する考えうるメトリクスのをまとめ巨大なリスト

- [MEGALIST](./megalist.tsv)

### Metric Name

メトリクス名称。UPPER_CASEで表記。

### Evaluation Target

その指標が主に何(誰)を評価するのか。評価対象。論理的な物体。

PullRequestに関する指標では「特定期間内に本流ブランチにマージされた」という点は共通コンテキストとする。

### Evaluation Characteristic

その指標が評価対象のどのような特性を評価するのか。評価特性。〇〇性。

#### 例：「各開発者のアプリケーション品質・保守性への貢献度」を表す指標

- Evaluation Target: Developer
- Evaluation Characteristic: Application Maintainability

#### 例：「各PullRequestの開発生産性」の状態を表す指標

- Evaluation Target: PullRequest
- Evaluation Characteristic: Development Productivity

### Data Source

そのメトリクスを取得する情報元。取得できないものである場合には記載しない。

直接取得できないが、取得できる情報をもとに一定の演算(加工)を行えば導ける場合も含む。

### Description(JP)

日本語の説明文。
