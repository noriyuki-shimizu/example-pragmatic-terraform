# 『実践Terraform』サンプルコード

このリポジトリでは、『**[実践Terraform](https://www.amazon.co.jp/dp/4844378139/)**』のサンプルコードを公開しています。

## 使い方

本リポジトリは、各章ごとにディレクトリを分けています。
tfファイルについては、書籍内のコードのキャプション番号をファイル名にしてあります。
それ以外については、書籍内でファイル名を明示しています。

## 検証環境

動作確認はすべて、macOS上で行っています。
バージョンは次のとおりです。

- Terraform：0.12.5
- AWSプロバイダ：2.20.0

これ以降のバージョンであれば概ね動くと思いますが、うまく動かない場合は上記のバージョンをお試しください。

## License

Apache 2 Licensed. See LICENSE for full details.

## バージョン管理システム
バージョン管理システムでは `tfenv` を使用します。

```
$ brew install terraform
$ brew unlink terraform
$ brew install tfenv
$ tfenv -v
$ tfenv list-remote
$ tfenv install 0.12.5
$ tfenv use 0.12.5
$ terraform -v
Terraform v0.12.5

Your version of Terraform is out of date! The latest version
is 0.15.4. You can update by downloading from www.terraform.io/downloads.html
```
