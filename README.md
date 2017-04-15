# ansible-round-about

> Ansible playbook for configuring showcase env for Round-About.

This playbook will install
- docker and docker-compose
- setup plugins inside Wordpress container
- setup MySQL container

## Usage

Provision Amazon EC2 instances with:

```bash
$ ansible-playbook site.yml --private-key <private_key.pem> -i inventory -u ubuntu
```
