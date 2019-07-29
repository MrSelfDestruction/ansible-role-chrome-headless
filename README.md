esolitos.chrome-headless
=========

Ansible role to install chrome and chromedriver, which are useful for Behat testing.

Role Variables
--------------

See [defaults/main.yml](./defaults/main.yml)

variable | default | description
---------|---------|------------
chromedriver_version | latest | Version to use for installation. Use Latest to get always the most up to date. |
chromedriver_bin | chromedriver | The binaly name of chromedriver. |
chromedriver_path | /opt/google/chromedriver/bin/ | The path where the chromedriver is installed. |

Dependencies
------------

none

Example Playbook
----------------

```
- hosts: servers
  roles:
     - esolitos.chrome-headless
```

License
-------

BSD
