Requirements
============

- XCode
- Homebrew
- Ansible

What will be installed
======================

- git
- zsh
- vim
- PHP 5.6 with xdebug

What will be configured
=======================

# Git

- config
- global ignore

# ZSH

add some plugins:

- git
- sublime
- composer
- symfony2
- history
- history-substring-search

Installation
============

## Homebrew

Go to http://brew.sh/ and follow the installation procedure

## Ansible

```
brew install ansible
```

## Launch ansible

```
ansible-playbook -i hosts -K local.yml
```
