# Ansibleでサーバ構築を自動化

## VagrantにCentOSをインストールしてrbenvの設定をする

次のコマンドを実行する。

  - `vagrant up`

サーバーを起動し、CentOSをインストールして、プロビジョニング（provisioning/playbook.ymlに書いてある処理を実行）する。

初回以降の`vagrant up`では、プロビジョニングは行われないので注意する。プロビジョニングだけを行うときは、

  - `vagrant provision`

を実行する。
