# How to Install
Configure the `requirements.yml` file.
```
- name: brownsers
  src: https://github.com/nilsonvieira/ansible-role-brownsers
  version: main
```
In the Roles include:
```
  roles:
    - brownsers
```
Execute the command to install role.

```bash
ansible-galaxy role install -r requirements.yml