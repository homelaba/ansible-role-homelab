# ansible-role-proxmox
Ansbile role for proxmox create lxc and install tools

Create file `ansible/roles/requirements.yml`

```yaml
---
roles:
  - src: https://github.com/homelaba/ansible-role-proxmox.git
    name: create_lxc
    version: main
    scm: git
```

Install command

```bash
ansible-galaxy role install -r ansible/roles/requirements.yml -p ansible/roles
```

