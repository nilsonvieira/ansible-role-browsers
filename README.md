# How to Install
Configure the `requirements.yml` file.
```
- name: browsers
  src: https://github.com/nilsonvieira/ansible-role-browsers
  version: main
```
In the Roles include:
```
  roles:
    - browsers
```
Execute the command to install role.

```bash
ansible-galaxy role install -r requirements.yml