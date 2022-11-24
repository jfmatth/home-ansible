# Home ansible setup

Ansible playbook(s) to setup my home lab, mainly K3s Kubernetes
- Laptop (k3s-laptop)
- Nodes 

**Make sure you're inventory(hosts.yaml) is correct**


## Playbook - closelid.yaml

This playbook will hit the 'laptops' inventory and turn off the screen after 10s and make it so the lid doesn't suspend the laptop.

`ansible-playbook playbooks/closelid.yaml`

