# Redmine Vagrant

## Overview

The is a development environment virtual machine for Redmine. It should work on any operating system that supports VirtualBox and Vagrant.

## Requirements

1. [VirtualBox](https://www.virtualbox.org/)
2. [Vagrant](http://www.vagrantup.com/) 1.8.5+
3. [git](https://git-scm.com/)

## Use

VirtualBox:

1. `git clone https://github.com/yorkulibraries/redmine_vagrant`
2. `cd redmine_vagrant`
3. `vagrant up`

You can connect to the machine via ssh:

* `vagrant ssh`
* `ssh -p 2222 vagrant@localhost`

The default VM login details are:
  
* username: vagrant
* password: vagrant

## Maintainers

* [Nick Ruest](https://github.com/ruebot)

## License

[MIT](LICENSE)
