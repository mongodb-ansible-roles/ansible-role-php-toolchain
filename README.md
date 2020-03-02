Ansible role for php-toolchain
==================================

Installs the php toolchain

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-php-toolchain/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-php-toolchain/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-php-toolchain/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-php-toolchain/actions?query=workflow%3A%22Molecule+Test%22)

Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| `php_toolchain_sha` | SHA of the toolchain to download | string | "37dbfb7b800408897e2dbb6c85ae9e67ce6f7c49" | true |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-php-toolchain
      vars:
        php_toolchain_sha: 37dbfb7b800408897e2dbb6c85ae9e67ce6f7c49
```

License
-------

[Apache License](LICENSE)
