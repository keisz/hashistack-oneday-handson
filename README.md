# hashistack-oneday-handson

## 事前準備

* Install HashiCorp Stack
	* https://www.vaultproject.io/downloads.html
	* https://www.terraform.io/downloads.html
	* https://www.consul.io/downloads.html
	* https://www.nomadproject.io/downloads.html
	* 上記からそれぞれダウンロードいただきパスを通しておいて下さい。

* AWSアカウント作成
	* https://portal.aws.amazon.com/billing/signup?refid=em_127222&redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation#/start
	* AWSのアカウントを作成しRootユーザのAccess KeyとSecret Keyをメモしておいて下さい。

* Install MySQL 5.7
	* https://dev.mysql.com/downloads/mysql/5.7.html
	* 上記からダウンロードしていただきMySQLが起動するところまでご確認下さい。

* Install Docker
	* https://docs.docker.com/docker-for-mac/install/

* GitHubアカウント作成とgit cliインストール
	* https://github.com/
	* https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

* Install curl, jq
	* https://stedolan.github.io/jq/download/
	* https://curl.haxx.se/download.html

## ラップトップについて

* 各々ご自身のラップトップをご持参ください
* 手順書はmacOS, Linux環境が前提となっているのでWindows端末の方はCygwinやLinuxをVirtual Box上にインストールいただくなどを推奨いたします。
* インターネットにアクセス出来るよう設定しておいて下さい(プロキシの設定などは解除下さい)

## アジェンダ

* HashiCorp Introduction
* Vault
	* [Vaultのコンフィグレーションと起動](https://github.com/hashicorp-japan/vault-workshop/blob/master/contents/hello-vault.md#vault%E3%81%AE%E3%82%B3%E3%83%B3%E3%83%95%E3%82%A3%E3%82%B0%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3)
	* [Database Secret Engine](https://github.com/hashicorp-japan/vault-workshop/blob/master/contents/db.md)
	* [Vault認証とポリシー](https://github.com/hashicorp-japan/vault-workshop/blob/master/contents/policy.md)
	* [Transit Secret Engine](https://github.com/hashicorp-japan/vault-workshop/blob/master/contents/transit.md)
	* [SSH Secret Engine(Optional)](https://github.com/hashicorp-japan/vault-workshop/blob/master/contents/ssh.md)
	* [KV Secret Engine(Optional)](https://github.com/hashicorp-japan/vault-workshop/blob/master/contents/kv.md)
	* AWS Secret Engine(Demo)
* Terraform
	* [Terraform OSSでインスタンスをプロビジョニング](https://github.com/hashicorp-japan/terraform-workshop/blob/master/contents/hello-terraform.md)
	* [Enterprise機能1: VCS連携](https://github.com/hashicorp-japan/terraform-workshop/blob/master/contents/vcs.md)
	* [Enterprise機能2: Secure Variable Storage](https://github.com/hashicorp-japan/terraform-workshop/blob/master/contents/variables.md)
	* [Enterprise機能3: Policy as Code](https://github.com/hashicorp-japan/terraform-workshop/blob/master/contents/sentinel.md)
	* [Enterprise機能4: Private Module Registry(Optional)](https://github.com/hashicorp-japan/terraform-workshop/blob/master/contents/module.md)
* Consul
	* [Consulのコンフィグレーションと起動](https://github.com/hashicorp-japan/consul-workshop/blob/master/contents/hello-consul.md#%E9%80%9A%E5%B8%B8%E3%83%A2%E3%83%BC%E3%83%89%E3%81%A7consul%E3%82%92%E8%B5%B7%E5%8B%95%E3%81%99%E3%82%8B)
	* [Service Discovery](https://github.com/hashicorp-japan/consul-workshop/blob/master/contents/srd.md)
	* [Sidecar Proxy and Intensions](https://github.com/hashicorp-japan/consul-workshop/blob/master/contents/mesh.md)
	* [L7 Traffic Management(Optional)](https://github.com/hashicorp-japan/consul-workshop/blob/master/contents/mesh.md)
* Nomad
* [アンケート](https://docs.google.com/forms/d/1omJQf9jjx7dx4b5bZSwhW95do0p6iO7qMozFSo8uUdM/edit)

## 資料

* [プレゼン資料](https://docs.google.com/presentation/d/1XY8d50uL_K05KGhVyRIfW9kasaZIaW_kex0WdrBtmrk/edit?usp=sharing)
* [進捗表](https://docs.google.com/spreadsheets/d/1CjTs4V4cFvXliRAswCcSQ7v_OyXkGc_ZvzM_WLvPUtw/edit?usp=sharing)
