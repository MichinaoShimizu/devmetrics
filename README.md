# devmetrics

## 概要
開発プロセスにまつわる指標の抽出・整理

## 前提

循環的複雑度等の静的コード解析上の指標は

より上位の指標(REMEDIATION_TIME)に集約されるため言及しない

## 指標の分類

ソースコード・開発者・時間など様々な指標が絡まり合うため

ある程度の目的に応じて指標の分類を行う

- [ソースコードの現況を表す指標](metrics/sourcecode.tsv)
  - 目的
    - Repositoryの現況を把握する
- [単一のPullRequestの状態を表す指標](metrics/pullrequest.tsv)
  - 目的
    - 自らのPullRequestの規模・質量を知る
    - 自らのPullRequestのマージによって本流ブランチに与えた影響を知る
- [開発プロセスの状態を表す指標](metrics/pullrequests.tsv)
  - 目的
    - 開発プロセスの無駄な時間や生産性の増減を把握する
- [開発者のコスト・貢献度を表す指標](metrics/developer.tsv)
  - 目的
    - 特定の開発者に対する負荷の増大を知る
    - 特定の開発者のソースコードに対する貢献を知る