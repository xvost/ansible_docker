# Docker installer to CentOs 7
## Requirements

Ansible 2.1.1.0

Python 2.7.12+
or
Python 3.5.2+

## Usage

Copy inventory/env.example to inventory/env

```
cp inventory/env.example inventory/env
```

Edit in inventory/env host addresses

```
editor inventory/env
```

Run

```
ansible-playbook -i 'inventory/env' ./startup_point.yml
```
