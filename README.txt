vagrantとansibleを使用して開発用サーバを構築する

1.virtual boxをインストール

2.vagrantをインストール

3.vagrant.esからboxを選択し、addする

	vagrant add box ubuntu1404 https://cloud-images.ubuntu.com/vagrant/trusty/current/trusty-server-cloudimg-i386-vagrant-disk1.box

4.作業ディレクトリを作成・移動

	mkdir vagrant
	cd vagrant

5.vagrant initコマンドでvagrantを初期化

	vagrant init ubuntu1404

6.vagrant upコマンドでvmを起動

	vagrant up

7.vagrant sshコマンドでvmに接続

	vagrant ssh

8.python-pipをインストール

	sudo apt-get install python-pip

9.ansibleをインストール

	sudo pip install ansible


