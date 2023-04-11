# Home ansible setup

Ansible playbook(s) to setup my home lab, mainly K3s Kubernetes
- Laptop (k3s-laptop)
- Nodes 

**Make sure you're inventory(hosts.yaml) is correct**

## TODO
- New linux boxes get SUDO ALL for sudo group  
    ```
    %sudo   ALL=(ALL) NOPASSWD: ALL
    ```
- add Nano program  
- turn off swap  


## Instructions

Uses Pipenv to use Ansible

`pipenv shell`

Run the playbooks below as needed

## Playbook - closelid.yaml

This playbook will hit the 'laptops' inventory and turn off the screen after 10s and make it so the lid doesn't suspend the laptop.

`ansible-playbook playbooks/closelid.yaml`

