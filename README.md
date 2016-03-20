# Ansible+Vagrantでローカル開発環境構築


## Depends
+ Vagrant`>=1.8`

## Usage
```
git clone git@github.com:egapool/centos66-ansible.git
cd centos66-ansible
vagrant up
```
## About
Vagrant1.8から使える`ansible_localプロビジョナ`を使用して、ゲストOSにansibleをインストールさせ、そこでローカルに対してplaybookを実行しています。

ホストOSにはVagrant以外何も必要ありません。

## 構成

+ apache2.4
+ phpenv
+ php-fpm
+ xdebug??
+ mysql5.6.22
+ nodejs??
+ python??
+ git2.7.2