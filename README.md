# Boxstrap
Ansible script used to setup development environment on my mac

## Prerequisite
### Command line tools

    $ xcode-select --install

### Homebrew

    $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

### Ansible

    $ brew update
    $ brew install ansible

## Synopsis

    $ ansible-playbook -i hosts/local setup.yml
