# ansible-role-cuda

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftyhal%2Fcuda.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftyhal%2Fcuda?ref=badge_shield)

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

## License

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftyhal%2Fcuda.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftyhal%2Fcuda?ref=badge_large)
