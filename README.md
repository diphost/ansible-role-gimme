ansible-role-gimme
==================

Install multiple per user go versions by gimme shell script
(https://github.com/travis-ci/gimme)


Role Variables
--------------

- `golang_version` : Golang version (Default: 1.6.2)

Example Playbook
----------------

```yaml
- hosts: all
  become: yes

  golang_version: 1.6.1
  ansible_become_user: alice

  roles:
        - ansible-role-gimme
```

--
[![LICENSE WTFPL](wtfpl-badge-1.png)](LICENSE)

