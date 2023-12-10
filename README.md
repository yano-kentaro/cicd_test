# CodePipeline の CloudFormation Template

## 作成するリソース

- アーティファクト用 S3 バケット
- CodeCommit
- CodeBuild
  - IAM ロール
- CodeDeploy
  - IAM ロール
- CodePipeline
  - IAM ロール
- EventBridge ルール
  - CodePipeline 動作用
- EC2 用 IAM ロール
- デプロイ先の EC2、VPC、サブネット、セキュリティグループなど
  - 不要

## 作成しないリソース

- CodeCommit に push する IAM ユーザー
