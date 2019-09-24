cloud3rsio.phpbuild
=========

Install php-build.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.phpbuild
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `phpbuild_packages` | Reference to [defaults/main.yml](defaults/main.yml) | List |
| `phpbuild_destination` | `/usr/local/php-build` | String |

Dependencies
------------

- `cloud3rsio.yumrepo_epel`

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.phpbuild
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
