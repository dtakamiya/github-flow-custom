# github-flow-custom
github-flowをカスタマイズしたflowです。

## 前提条件
- originは拠点１のリモートリポジトリ
- 拠点１のリモートリポジトリは特定のメジャーバージョン専用である
- 拠点２のリモートリポジトリ（マスター）
- 拠点３のリモートリポジトリ
- masterブランチは、拠点１と拠点２をマージした開発用ブランチ
- 拠点２/masterブランチは常にデプロイ可能である
- 拠点３は拠点１と拠点３で共有したいものだけを共有
