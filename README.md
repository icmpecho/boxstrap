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

### Dropbox
All dotfiles are stored in dropbox. We need to install it and sync everything down first.

## Synopsis

    $ ansible-playbook -i hosts/local setup.yml
