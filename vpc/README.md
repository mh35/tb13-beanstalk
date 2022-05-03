# VPCのCloudFormation

このディレクトリは、VPCのCloudFormation定義です。

## 使い方

AZ数別に2azから6azまでディレクトリがあるので、その中のformation.ymlを使ってデプロイしてください。

## デプロイされるもの

* VPCを1つ
* 上記VPCに各AZごとにパブリックサブネットとプライベートサブネットを1つずつ
* 上記VPC用のInternet GatewayとEgess-Only Gatewayを1つずつ
* 上記VPC用のS3 Gateway EndpointとDynamoDB Gateway Endpoint
* 上記VPC用のパブリックルートテーブルおよび各AZごとのプライベートサブネット用のルートテーブル