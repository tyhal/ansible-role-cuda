# ansible-role-cuda

Create a requirements.yml in your ansible project

```yaml
- src: git@github.com:tyhal/ansible-role-cuda.git
  scm: git
  version: f8508a66
  name: cuda
```

Then you can install this with:

```bash
ansible-galaxy -r requirements.yml install --force
```

Then you can use this with:
```yaml
- hosts: all
  roles:
    - { role: cuda, sudo: yes}
```
