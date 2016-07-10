# Ansible Role: Beetbox CakePHP

[![CircleCI](https://circleci.com/gh/beetboxvm/ansible-role-beetbox-cakephp.svg?style=svg)](https://circleci.com/gh/beetboxvm/ansible-role-beetbox-cakephp)

An Ansible role that creates a CakePHP project on beetbox.

## Requirements

This role is specifically developed as an extension to beetbox -- https://github.com/drupalmel/beetbox

## Role Variables

Available variables are listed below, along with default values:

Create new CakePHP project.

    cake_create_project: no
    
CakePHP version. Composer compatible version, leave blank to use the latest version.

    cake_version: "*"


# beetbox

https://github.com/beetboxvm/beetbox

## Requirements

* [Vagrant](https://www.vagrantup.com/) >= 1.8
* [Virtualbox](https://www.virtualbox.org/)
* [Vagrant Hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater)
* [Vagrant Auto-network](https://github.com/oscar-stack/vagrant-auto_network)

## Quickstart

  1. Open terminal (or [git bash](https://msysgit.github.io/) for windows users) and run the following commands --

  ```
  git clone https://github.com/beetboxvm/ansible-role-beetbox-cakephp.git cakephp && cd $_
  vagrant up
  ```

  2. Go to http://cakephp.local/

  ```
  username: admin
  password: admin
  ```

## License

MIT
