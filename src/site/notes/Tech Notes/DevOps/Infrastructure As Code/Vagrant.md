---
{"dg-publish":true,"dg-pass-frontmatter":true,"eleventyNavigation":{"key":"Vagrant","parent":"Infrastructure As Code"},"permalink":"/tech-notes/dev-ops/infrastructure-as-code/vagrant/","dgHomeLink":true,"dgPassFrontmatter":true}
---


# Vagrant

Vagrant is a CLI that creates and manages consistent environement for
developing and testing.

## Installation
#### Fedora
`sudo dnf install vagrant`

#### Debian
**Direct Deb Download**
```shell
wget https://releases.hashicorp.com/vagrant/2.2.19/vagrant_2.2.19_x86_64.deb
sudo apt install ./vagrant_2.2.19_x86_64.deb
```


**Via Repo**


## Snippets

- [Create](_Create.md) Vagrantfile in current directory with the base Vagrant box:
  `vagrant init`

- Create [Vagrant](Tech%20Notes/DevOps/Infrastructure%20As%20Code/Vagrant.md)file with the Ubuntu 20.04 (Focal Fossa) box from HashiCorp Atlas:
  `vagrant init ubuntu/focal64`

- Start and provision the vagrant environment:
  `vagrant up`

- Suspend the machine:
  `vagrant suspend`

- Halt the machine:
  `vagrant halt`

- Connect to machine via SSH:
  `vagrant ssh`

- Output the SSH configuration file of the running Vagrant machine:
  `vagrant ssh-config`

- List all local boxes:
  `vagrant box list`

## Providers
### Docker
Unlike VM providers, it is not necessary to provide 

