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
| `phpbuild_version` | `master` | String |

Dependencies
------------

- `cloud3rsio.yumrepo_epel`
- `cloud3rsio.yumrepo_remi`

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
