# Ansible Playbooks

Update unifi
```
ansible-playbook unifi.yaml --tags "update" -K
ansible-playbook unifi.yaml --tags "update" -K --check
```

Update HTPC containers on antman
```
ansible-playbook antman-update-htpc-containers.yml -K
ansible-playbook antman-update-htpc-containers.yml -K --check
```
