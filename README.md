# round-about-deploy

> Ansible playbook for deploying Round-About to AWS instance.

This playbook will install
- docker and docker-compose
- setup Wordpress container
- setup MySQL container, restore data we already had.


## Setup Configurations

Open `group_vars/all`, edit it as you want. Example is already there.

### Domain
```
# setup domain as what you want as below
domain: www.roundabout.com
```

### Database
```
# setup mysql configuration as below
DB_NAME: round_about
DB_ROOT_PASSWORD: round_about
DB_USER: round_about
DB_PASSWORD: round_about
```

## Usage
```bash
$ ansible-playbook site.yml --private-key <private_key.pem> -i inventory -u ubuntu
```
