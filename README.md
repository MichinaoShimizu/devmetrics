# devmetrics

開発プロセスにまつわる指標の抽出・整理

## 概要

循環的複雑度等、静的コード解析上の詳細なメトリクスは

REMEDIATION_TIME等、より上位の指標に集約されるため言及しない

## 指標の分類

ソースコード・開発者・時間など様々な指標が絡まり合うため

ある程度の目的に応じて指標の分類を行う

- [ソースコードの現況を表す指標](metrics/sourcecode.tsv)
  - 目的：RepositoryOwnerがRepositoryの現況を俯瞰する
- [単一のPullRequestの状態を表す指標](metrics/pullrequest.tsv)
  - 目的：開発者・レビュアーがマージされたPullRequestを振り返る
- [開発プロセスの状態を表す指標](metrics/pullrequests.tsv)
  - 目的：開発プロセスの無駄な時間や生産性の増減を検知する
- [開発者のコスト・貢献度を表す指標](metrics/developer.tsv)
  - 目的：特定の開発者に対する負荷や、特定の開発者によるソースコードに対する貢献度を検知する