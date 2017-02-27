# packer-catalog

First download the ansible role in each sub repository.

```
ansible-galaxy install angstwad.docker_ubuntu  -p .
```
If you see errors about bytes and not str, please install ansible using python2, or pip2.


Then run `packer build ubuntu_1404_aufs3` 


