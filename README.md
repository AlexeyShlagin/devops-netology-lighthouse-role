Role Name
=========

This role install lighthouse using ansible. <br>
LightHouse is a lightweight GUI interface for ClickHouse. <br>
More about lighthouse you can read here: https://github.com/VKCOM/lighthouse

Requirements
------------

Ansible version >=2.15 (It might work on previos versions, but i can't garantee it )

Role Variables
--------------

| Name            | Default Value   | Description     |
| --------------- | --------------- | --------------- |
| lighthouse_dest | /opt/lighthouse | folder location |

Example Playbook
----------------

Example of how to use role:

```yml
- name: Installing lighthouse
  hosts: lighthouse
  roles:
    - role: lighthouse 
```

License
-------

BSD
