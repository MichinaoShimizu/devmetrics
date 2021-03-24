# devmetrics

## 概要

開発プロセスにまつわる指標の抽出・整理。

## 前提

- 指標を表現するための粒度として必要aaaaなメタ情報も含む
- DataSourceには情報取得元となるサービス・APIなどを記載する
- DataSourceにはそこから取得した値に演算を加えることで算出できる場合も含む
- 静的コード解析上の詳細な指標はより上位の指標(REMEDIATION_TIME)に集約されるため記載しない

## 指標の洗い出し

どのような時にどのような指標が必要かを追加していく。

- [metrics-bucket.tsv](metrics-bucket.tsv)

## 指標の分類

下記はサンプル。

- [各Repositoryの状態を表す指標](metrics/repository.tsv)
  - 目的
    - Repositoryの現況を把握する
- [各PullRequestの状態を表す指標](metrics/pullrequest.tsv)
  - 目的
    - 各PullRequestの規模・質量を知る
    - 各PullRequestのマージによって本流ブランチに与えた影響を知る
- [複数のPullRequestの集合の状態を表す指標](metrics/pullrequests.tsv)
  - 目的
    - 開発プロセスの無駄な時間や生産性の増減を把握する
- [各開発者の状態を表す指標](metrics/developer.tsv)
  - 目的
    - 特定の開発者に対する負荷の増大を知る
    - 特定の開発者のソースコードに対する貢献を知る
