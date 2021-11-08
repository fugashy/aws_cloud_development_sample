# aws_cloud_development

## 準備

- AWS CDK のインストール

  AmazonS3FullAccess

  AmazonCloudFormationFullAccess

  このポリシーを追加

  その後

  ```bash
  cdk bootstrap aws://aws://$AWS_USER_ID/$AWS_DEFAULT_REGION
  ```

- 使用するリポジトリのクローン

  ```bash
  git clone https://github.com/tomomano/learn-aws-by-coding-source-code.git
  ```

## reference

- AWSではじめるクラウド開発入門(真野智之著）
