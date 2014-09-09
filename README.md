# LAMP Stacks feito com Vagrant & Puppet

Ambiente Lamp stach com Puppet e Vagrant para desenvolvimento, testes e etc.

## pré-requisitos :
* [Vagrant](http://www.vagrantup.com/)
* [Virtual Box](https://www.virtualbox.org/)

## Instruções
0. Ter instalado o virtual box.
1. Instale precise32 Vagrant box. (Se já não estiver instalado)

        $ vagrant box add precise32 http://files.vagrantup.com/precise32.box

2. Clone o repositório.
3. Crie o diretório "webroot" no diretório principal "/vagrant/webroot" 
4. Inicialize.

        $ vagrant up

E pronto, você já esta pronto para desenvolver, acesse : http://localhost:8888

## Incluso :

* apache2 - rewrite mode enabled, having virtual host with config - refer manifest/vagrant_webroot.sample
* php5
* php5-cli
* php5-mysql
* php-pear - pacotes instalados : phpunit e dependências.
* php5-dev
* php5-gd
* php5-mcrypt
* libapache2-mod-php5
* mysql-server
* curl
* vim
* htop
*composer
*phpmyadmin
