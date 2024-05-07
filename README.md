# ansible-role-homelab
Ansbile role for proxmox create lxc and install tools

Create file `ansible/roles/requirements.yml`

```yaml
---
- name: lxc
  src: https://github.com/homelaba/ansible-role-homelab.git
  scm: git
```

Install command

```bash
ansible-galaxy install --role-file ansible/roles/requirements.yml --roles-path ansible/roles/ lxc.isntall_docker
```

