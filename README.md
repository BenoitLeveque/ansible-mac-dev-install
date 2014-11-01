Requirements
============

- XCode
- Homebrew
- Ansible

What will be installed
======================

- git
- zsh with plugin for : git, sublimetext, composer, symfony2, history, history-substring-search
- vim

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
