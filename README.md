# ansible-role-homelab
Ansbile role for proxmox create lxc and install tools

Create 

```yaml
---
- name: awx-operator
  src: https://github.com/homelaba/ansible-role-homelab.git
  scm: git
```

Command

```bash
ansible-galaxy install --role-file ansible/roles/requirements.yml --roles-path ansible/roles/ --ignore-errors
```

