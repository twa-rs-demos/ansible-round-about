# ansible-round-about-showcase

> Ansible playbook for configuring showcase env for Round-About.

This playbook will install **docker** and **docker-compose**, set up plugins inside Wordpress container. 

## Usage

Provision Amazon EC2 instances with:

```bash
$ ansible-playbook site.yml --private-key <private_key.pem> -i show_case -u ubuntu
```
