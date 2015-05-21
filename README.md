<img src="http://www.elao.com/images/corpo/logo_red_small.png"/>

# Ansible Role: gearman

This role will assume the setup of gearman

It's part of the ELAO [Ansible stack](http://ansible.elao.com) but can be used as a stand alone component.

## Requirements

- Ansible 1.7.2+

## Dependencies

None.

## Installation

You can add this role as a dependency for other roles by adding the role to the meta/main.yml file of your own role:

```yaml
dependencies:
  - { role: elao.gearman }
```

## Role Handlers

| Name            | Type    | Description            |
| --------------- | ------- | ---------------------- |
| gearman restart | Service | Restart gearman server |

## Example playbook

    - hosts: servers
      roles:
         - { role: elao.gearman }

# Licence

MIT

# Author information

ELAO [**(http://www.elao.com/)**](http://www.elao.com)
