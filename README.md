# ansible-role-cuda

Create a requirements.yml in your ansible project

```yaml
- src: tyhal.cuda
```

Then you can install this with:

```bash
ansible-galaxy -r requirements.yml install
```

Then you can use this with:
```yaml
- hosts: all
  roles:
    - { role: tyhal.cuda, sudo: yes}
```
