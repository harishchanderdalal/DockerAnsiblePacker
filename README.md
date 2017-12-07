## How to build

### Ansible

Build docker image with ansible provisioning

- Validate
```
$ sudo packer validate -var 'repo=foo' ansible.json
```
- Build
```
$ sudo packer build -var 'repo=foo' ansible.json
```

Check it.

```bash
$ docker run --rm -i -t foo/packer-ansible:0.1 bash
```

