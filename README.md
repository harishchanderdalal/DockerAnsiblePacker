## How to build

### Ansible

Build docker image with ansible provisioning

```
$ packer build ansible.json
```

Check it.

```bash
$ docker run --rm -i -t harish/packer-ansible:0.1 bash
```

