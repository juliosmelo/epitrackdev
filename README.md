Download Ubuntu Trust64 vm box from https://atlas.hashicorp.com/ and install mongodb, nodejs in a vm Virtual Box with Ansible and Vagrant.

## Requirements

1. VirtualBox (latest)
2. Vagrant 1.7.1
3. Vagrant plugin for ansible provisioner
4. Ansible (latest)

```shell
vagrant plugin install ansible
```

## Usage
* clone this repository
```shell
  git clone git@github.com:juliosmelo/epitrackdev.git
```
* Up vm
```shell
  vagrant up
```
* be happy!

Does not support Windows, feel free to add Windows support :)
